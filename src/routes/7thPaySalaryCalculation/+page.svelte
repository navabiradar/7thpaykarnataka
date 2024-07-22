<script>

  let da = 31 ;
  let fixationRate = 27.5 ; 
  let newDA = 0 ;
  
  let formValues = {
    "oldPay" : 0,
    "newPay" : 0,
    "newPayAug" : 0,
    "payScale" : "Select",
    "seventhpayScale" : "",
    "sixthpayScale" : "",
    "hraGroup" : "",
    "group" : "",
  }

  let scaleExtract = [27000,27650,28300,28950,29600,29600,30325,31050,31775,32500,32500,33300,34100,34900,35700,35700,36600,37500,38400,39300,39300,40300,41300,42300,43300,43300,44425,45550,46675,47800,47800,49050,50300,51550,52800,52800,54175,55550,56925,58300,58300,59800,61300,62800,64300,64300,65950,67600,69250,70900,72550,74200,74200,76100,78000,79900,81800,83700,85600,85600,87900,90200,92500,94800,97100,99400,99400,102100,104800,107500,110200,112900,115600,115600,118700,121800,124900,128000,131100,134200,134200,137700,141200,144700,148200,151700,155200,155200,159200,163200,167200,171200,175200,179200,179200,183700,188200,192700,197200,201700,206200,206200,211200,216200,221200,226200,231200,236200,241200] ;
  

  let payScaleData = [
     {
      "id" : 1,
      "sixthPay" : "17000-400-18600-450-20400-500-22400-550-24600-600-27000-650-28950",
      "seventhPay" : "27000-650-29600-725-32500-800-35700-900-39300-1000-43300-1125-46675",
      "max" : 46675,
      "min" : 27000,
       },
     {
      "id" : 2,
      "sixthPay" : "18600-450-20400-500-22400-550-24600-600-27000-650-29600-750-32600",
      "seventhPay" : "29600-725-32500-800-35700-900-39300-1000-43300-1125-47800-1250-52800",
      "max" : 52800,
      "min" : 29600,
        },
     {
      "id" : 3,
      "sixthPay" : "19950-450-20400-500-22400-550-24600-600-27000-650-29600-750-32600-850-36000-950-37900",
      "seventhPay" : "31755-725-32500-800-35700-900-39300-1000-43300-1125-47800-1250-52800-1375-58300-1500-61300",
      "max" : 61300,
      "min" : 31755,
       },
     {
      "id" : 4,
      "sixthPay" : "21400-500-22400-550-24600-600-27000-650-29600-750-32600-850-36000-950-39800-1100-42000",
      "seventhPay" : "34100-800-35700-900-39300-1000-43300-1125-47800-1250-52800-1375-58300-1500-64300-1650-67600",
      "max" : 67600,
      "min" : 34100,
        },
     {
      "id" : 5,
      "sixthPay" : "23500-550-24600-600-27000-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-47650",
      "seventhPay" : "37500-900-39300-1000-43300-1125-47800-1250-52800-1375-58300-1500-64300-1650-74200-1900-76100",
      "max" : 46675,
      "min" : 37500,
        },
     {
      "id" : 6,
      "sixthPay" : "25800-600-27000-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-51400",
      "seventhPay" : "41300-1000-43300-1125-47800-1250-52800-1375-58300-1500-64300-1650-74200-1900-81800",
      "max" : 81800,
      "min" : 41300,
       },
     {
      "id" : 7,
      "sixthPay" : "27650-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-52650",
      "seventhPay" : "44425-1125-47800-1250-52800-1375-58300-1500-64300-1650-74200-1900-83700",
      "max" : 83700,
      "min" : 44425,
        },
     {
      "id" : 8,
      "sixthPay" : "30350-750-32600-850-36000-950-39800-1100-46400-1250-53900-1450-58250",
      "seventhPay" : "49050-1250-52800-1375-58300-1500-64300-1650-74200-1900-85600-2300-92500",
      "max" : 92500,
      "min" : 49050,
       },
     {
      "id" : 9,
      "sixthPay" : "33450-850-36000-950-39800-1100-46400-1250-53900-1450-62600",
      "seventhPay" : "54175-1375-58300-1500-64300-1650-74200-1900-85600-2300-99400",
      "max" : 99400,
      "min" : 54175,
        },
     {
      "id" : 10,
      "sixthPay" : "36000-950-39800-1100-46400-1250-53900-1450-62600-1650-67550",
      "seventhPay" : "58300-1500-64300-1650-74200-1900-85600-2300-99400-2700-107500",
      "max" : 107500,
      "min" : 58300,
         },
     {
      "id" : 11,
      "sixthPay" : "37900-950-39800-1100-46400-1250-53900-1450-62600-1650-70850",
      "seventhPay" : "61300-1500-64300-1650-74200-1900-85600-2300-99400-2700-112900",
      "max" : 112900,
      "min" : 61300,
        },
     {
      "id" : 12,
      "sixthPay" : "40900-1100-46400-1250-53900-1450-62600-1650-72500-1900-78200",
      "seventhPay" : "65950-1650-74200-1900-85600-2300-99400-2700-115600-3100-124900",
      "max" : 124900,
      "min" : 65950,
       },
     {
      "id" : 13,
      "sixthPay" : "43100-1100-46400-1250-53900-1450-62600-1650-72500-1900-83900",
      "seventhPay" : "69250-1650-74200-1900-85600-2300-99400-2700-115600-3100-134200",
      "max" : 134200,
      "min" : 69250,
       },
     {
      "id" : 14,
      "sixthPay" : "45300-1100-46400-1250-53900-1450-62600-1650-72500-1900-83900-2200-88300",
      "seventhPay" : "72550-1650-74200-1900-85600-2300-99400-2700-115600-3100-134200-3500-141200",
      "max" : 141200,
      "min" : 72550,
       },
     {
      "id" : 15,
      "sixthPay" : "48900-1250-53900-1450-62600-1650-72500-1900-83900-2200-97100-2500-99600",
      "seventhPay" : "78000-1900-85600-2300-99400-2700-115600-3100-134200-3500-148200",
      "max" : 148200,
      "min" : 78000,
      },
     {
      "id" : 16,
      "sixthPay" : "52650-1250-53900-1450-62600-1650-72500-1900-83900-2200-97100",
      "seventhPay" : "83700-1900-85600-2300-99400-2700-115600-3100-134200-3500-155200",
      "max" : 155200,
      "min" : 83700,
        },
     {
      "id" : 17,
      "sixthPay" : "56800-1450-62600-1650-72500-1900-83900-2200-97100-2500-99600",
      "seventhPay" : "90200-2300-99400-2700-115600-3100-134200-3500-155200-4000-159200",
      "max" : 159200,
      "min" : 90200,
       },
     {
      "id" : 18,
      "sixthPay" : "61150-1450-62600-1650-72500-1900-83900-2200-97100-2500-102100",
      "seventhPay" : "97100-2300-99400-2700-115600-3100-134200-3500-155200-4000-163200",
      "max" : 163200,
      "min" : 97100,
       },
     {
      "id" : 19,
      "sixthPay" : "67550-1650-72500-1900-83900-2200-97100-2500-104600",
      "seventhPay" : "107500-2700-115600-3100-134200-3500-155200-4000-167200",
      "max" : 167200,
      "min" : 107500,
      },
     {
      "id" : 20,
      "sixthPay" : "70850-1650-72500-1900-83900-2200-97100-2500-104600",
      "seventhPay" : "112900-2700-115600-3100-134200-3500-155200-4000-171200",
      "max" : 171200,
      "min" : 112900,
       },
     {
      "id" : 21,
      "sixthPay" : "74400-1900-83900-2200-97100-2500-109600",
      "seventhPay" : "118700-3100-134200-3500-155200-4000-175200",
      "max" : 175200,
      "min" : 118700,
       },
     {
      "id" : 22,
      "sixthPay" : "82000-1900-83900-2200-97100-2500-112100-2800-117700",
      "seventhPay" : "131100-3100-134200-3500-155200-4000-179200-4500-188200",
      "max" : 188200,
      "min" : 131100,
      },
     {
      "id" : 23,
      "sixthPay" : "90500-2200-97100-2500-112100-2800-123300",
      "seventhPay" : "144700-3500-155200-4000-179200-4500-197200",
      "max" : 197200,
      "min" : 144700,
       },
     {
      "id" : 24,
      "sixthPay" : "97100-2500-112100-2800-128900-3100-141300",
      "seventhPay" : "155200-4000-179200-4500-206200-5000-226200",
      "max" : 226200,
      "min" : 155200,
      },
     {
      "id" : 25,
      "sixthPay" : "104600-2500-112100-2800-128900-3100-150600",
      "seventhPay" : "167200-4000-179200-4500-206200-5000-241200",
      "max" : 241200,
      "min" : 167200,
     }
  ]

  

  function calculateSalary() {
        let newPayCalculated = formValues.oldPay + Math.round((formValues.oldPay*da)/100) + Math.round((formValues.oldPay*fixationRate)/100)
        
        scaleExtract.forEach((x) => {
          if (newPayCalculated > payScaleData[Number(formValues.payScale)-1].max){
            formValues.newPay = payScaleData[Number(formValues.payScale)-1].max
            return true
          } else if(newPayCalculated < payScaleData[Number(formValues.payScale)-1].min){
            formValues.newPay = payScaleData[Number(formValues.payScale)-1].min
            return true
          } else if (newPayCalculated <= x){
            console.log(x)
            return true
          }
        });
        





        
        formValues.seventhpayScale = payScaleData[Number(formValues.payScale)-1].seventhPay
        formValues.sixthpayScale = payScaleData[Number(formValues.payScale)-1].sixthPay
        
  }

</script>

<main>
    <div class="row row-card">
    <div class="col-md-4">
        <div class="card">
          <div class="card-header">
            <h3 class="card-title">sixth Pay Details/6ನೇ ವೇತನ ಮಾಹಿತಿ</h3>
          </div>
          <div class="card-body">
            <div class="mb-3">
              <label class="form-label required" for="">Current Pay Scale/ಪ್ರಸ್ತುತ ವೇತನ ಶ್ರೇಣಿ</label>
              <div>
                <select class="form-select" bind:value={formValues.payScale}>
                  <option value="Select">Select Pay Current Scale</option>
                  {#each payScaleData as data }

                    <option value={data.id} >sixth Pay / {data["sixthPay"]}</option>
                    
                  {/each}
                </select>
                <small class="form-hint">ನಿಮ್ಮ ವೇತನ ಶ್ರೇಣಿಯನ್ನು <a href="https://hrmsess.karnataka.gov.in" > hrmsess.karnataka.gov.in </a> ಪಡೆಯಿರಿ. </small>
              </div>
            </div>
            <div class="mb-3">
              <label class="form-label required" for="">Present Basic Pay/ಈಗಿನ ಮೂಲ ವೇತನ</label>
              <div>
                <input type="number" class="form-control" bind:value={formValues.oldPay} placeholder="Curren Basic Pay">
                <small class="form-hint">
                    ಈಗಿನ ಮೂಲ ವೇತನವನ್ನು ಸರಿಯಾಗಿ ನಮೂದಿಸಿ.
                </small>
              </div>
            </div>
            <div class="row">
              <div class="col-6">
                <div class="mb-3">
                  <label class="form-label" for="">Employee Group/ನೌಕರನ ವರ್ಗ</label>
                  <div>
                    <select class="form-select">
                      <option value="A">A</option>
                      <option value="B">B</option>
                      <option value="C">C</option>
                      <option value="D">D</option>
                    </select>
                    <small class="form-hint">
                      ನಿಮ್ಮ ಪದನಾಮವು ಯಾವ ವರ್ಗಕ್ಕೆ ಸೇರುತ್ತದೆ.
                    </small>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="mb-3">
                  <label class="form-label" for="">HRA City Grade/ಮನೆ ಬಾಡಿಗೆ ಭತ್ಯೆ ವರ್ಗ</label>
                  <div>
                    <select class="form-select">
                      <option>A</option>
                      <option>B</option>
                      <option>C</option>
                    </select>
                    <small class="form-hint">
                      ನೀವು ವೇತನ ಪಡೆಯುವ ಕಚೇರಿಯ ಯಾವ ವರ್ಗಕ್ಕೆ ಸೇರುತ್ತದೆ ಎಂದು ಆಯ್ಕೆ ಮಾಡಿ.
                    </small>
                  </div>
                </div>
              </div>
              
            </div>
          </div>
          <div class="card-footer text-end">
              <button type="submit" class="btn btn-danger">Clear</button>
              <button type="submit" class="btn btn-primary" on:click={calculateSalary}>Submit</button>
          </div>
        </div>
    </div>
    <div class="col-md-8">
        <div class="card">
          <div class="card-header">
            <h3 class="card-title">seventh Pay Details/7ನೇ ವೇತನ ಆಯೋಗದ ವರದಿಯಂತೆ</h3>
          </div>
          <div class="card-body">
            <div class="table-responsive">
                <table
                      class="table table-vcenter table-bordered table-wrap">
                  <thead>
                    <tr>
                      <th>Current Pay Scale/ಈಗೀನ ವೇತನ ಶ್ರೇಣಿ</th>
                      <th>New Pay Scale/ಪರಿಷ್ಕ್ರತ ವೇತನ ಶ್ರೇಣಿ</th>
                      
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>{formValues.sixthpayScale}</td>
                      <td >
                        {formValues.seventhpayScale}
                      </td>
                      
                    
                    
                    </tr>
                  </tbody>
                </table>
            </div>

            <div class="table-responsive">
              <table
                    class="table table-vcenter table-bordered table-wrap">
                <thead>
                  <tr>
                    <th>Current Pay /ಈಗೀನ ವೇತನ </th>
                    <th>New Pay /ಪರಿಷ್ಕ್ರತ ವೇತನ As on 01-07-2022 </th>
                    <th>New Pay /ಪರಿಷ್ಕ್ರತ ವೇತನ As on 01-08-2024 </th>
                    
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>{formValues.oldPay}</td>
                    <td>{formValues.newPay}</td>
                    <td>{formValues.newPayAug}</td>
                    
                  
                  
                  </tr>
                </tbody>
              </table>
            </div>
            <div class="table-responsive">
              <table
                    class="table table-vcenter table-bordered table-wrap">
                <thead>
                  <tr>
                    
                    <th>DA/ತುಟ್ಟಿ ಭತ್ಯೆ </th>
                    <th>HRA / ಮನೆ ಬಾಡಿಗೆ ಭತ್ಯೆ </th>
                    <th>Medical Allowance/ ವೈದ್ಯಕೀಯ ಭತ್ಯೆ </th>
                    <th>Gross Salary/ ಒಟ್ಟು ವೇತನ </th>
                    
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>{formValues.oldPay}</td>
                    <td>{formValues.newPay}</td>
                    <td>{formValues.newPayAug}</td>
                    <td>{formValues.newPayAug}</td>
                    
                  
                  
                  </tr>
                </tbody>
              </table>
            </div>
              
            
          </div>
          
        </div>
    </div>
    </div>
</main>