<script>

  let da = 31 ;
  let fixationRate = 27.5 ; 
  let newDA = 0 ;
  
  let formValues = {
    "oldPay" : 0,
    "newPay" : 0,
    "newPayAug" : 0,
    "payScale" : "Select",
    "hraGroup" : "",
    "group" : "",
  }

  function calculateSalary() {
        let newPayCalculated = formValues.oldPay + Math.round((formValues.oldPay*da)/100) + Math.round((formValues.oldPay*fixationRate)/100)

        formValues.newPay = newPayCalculated ;
  }

</script>

<main>
    <div class="row row-card">
    <div class="col-md-4">
        <div class="card">
          <div class="card-header">
            <h3 class="card-title">6th Pay Details/6ನೇ ವೇತನ ಮಾಹಿತಿ</h3>
          </div>
          <div class="card-body">
            <div class="mb-3">
              <label class="form-label required" for="">Current Pay Scale/ಪ್ರಸ್ತುತ ವೇತನ ಶ್ರೇಣಿ</label>
              <div>
                <select class="form-select" bind:value={formValues.payScale}>
                  <option value="Select">Select Pay Current Scale</option>
                  <option value='17000-400-18600-450-20400-500-22400-550-24600-600-27000-650-28950'>6th-Pay/17000-400-18600-450-20400-500-22400-550-24600-600-27000-650-28950</option>
                  <option value='18600-450-20400-500-22400-550-24600-600-27000-650-29600-750-32600'>6th-Pay/18600-450-20400-500-22400-550-24600-600-27000-650-29600-750-32600</option>
                  <option value='19950-450-20400-500-22400-550-24600-600-27000-650-29600-750-32600-850-36000-950-37900'>6th-Pay/19950-450-20400-500-22400-550-24600-600-27000-650-29600-750-32600-850-36000-950-37900</option>
                  <option value='21400-500-22400-550-24600-600-27000-650-29600-750-32600-850-36000-950-39800-1100-42000'>6th-Pay/21400-500-22400-550-24600-600-27000-650-29600-750-32600-850-36000-950-39800-1100-42000</option>
                  <option value='23500-550-24600-600-27000-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-47650'>6th-Pay/23500-550-24600-600-27000-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-47650</option>
                  <option value='27650-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-52650'>6th-Pay/27650-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-52650</option>
                  <option value='30350-750-32600-850-36000-950-39800-1100-46400-1250-53900-1450-58250'>6th-Pay/30350-750-32600-850-36000-950-39800-1100-46400-1250-53900-1450-58250</option>
                  <option value='33450-850-36000-950-39800-1100-46400-1250-53900-1450-62600'>6th-Pay/33450-850-36000-950-39800-1100-46400-1250-53900-1450-62600</option>
                  <option value='37900-950-39800-1100-46400-1250-53900-1450-62600-1650-70850'>6th-Pay/37900-950-39800-1100-46400-1250-53900-1450-62600-1650-70850</option>
                  <option value='40900-1100-46400-1250-53900-1450-62600-1650-72500-1900-78200'>6th-Pay/40900-1100-46400-1250-53900-1450-62600-1650-72500-1900-78200</option>
                  <option value='43100-1100-46400-1250-53900-1450-62600-1650-72500-1900-83900'>6th-Pay/43100-1100-46400-1250-53900-1450-62600-1650-72500-1900-83900</option>
                  <option value='45300-1100-46400-1250-53900-1450-62600-1650-72500-1900-83900-2200-88300'>6th-Pay/45300-1100-46400-1250-53900-1450-62600-1650-72500-1900-83900-2200-88300</option>
                  <option value='52650-1250-53900-1450-62600-1650-72500-1900-83900-2200-97100'>6th-Pay/52650-1250-53900-1450-62600-1650-72500-1900-83900-2200-97100</option>
                  <option value='56800-1450-62600-1650-72500-1900-83900-2200-97100-2500-99600'>6th-Pay/56800-1450-62600-1650-72500-1900-83900-2200-97100-2500-99600</option>
                  <option value='67550-1650-72500-1900-83900-2200-97100-2500-104600'>6th-Pay/67550-1650-72500-1900-83900-2200-97100-2500-104600</option>
                  <option value='74400-1900-83900-2200-97100-2500-109600'>6th-Pay/74400-1900-83900-2200-97100-2500-109600</option>
                  <option value='82000-1900-83900-2200-97100-2500-112100-2800-117700'>6th-Pay/82000-1900-83900-2200-97100-2500-112100-2800-117700</option>
                  <option value='90500-2200-97100-2500-112100-2800-123300'>6th-Pay/90500-2200-97100-2500-112100-2800-123300</option>
                  <option value='97100-2500-112100-2800-128900-3100-141300'>6th-Pay/97100-2500-112100-2800-128900-3100-141300</option>
                  <option value='104600-2500-112100-2800-128900-3100-150600'>6th-Pay/104600-2500-112100-2800-128900-3100-150600</option>
                  <option value='25800-600-27000-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-51400'>6th-Pay/25800-600-27000-650-29600-750-32600-850-36000-950-39800-1100-46400-1250-51400</option>
                  <option value='36000-950-39800-1100-46400-1250-53900-1450-62600-1650-67550'>6th-Pay/36000-950-39800-1100-46400-1250-53900-1450-62600-1650-67550</option>
                  <option value='48900-1250-53900-1450-62600-1650-72500-1900-83900-2200-92700'>6th-Pay/48900-1250-53900-1450-62600-1650-72500-1900-83900-2200-92700</option>
                  <option value='61150-1450-62600-1650-72500-1900-83900-2200-97100-2500-102100'>6th-Pay/61150-1450-62600-1650-72500-1900-83900-2200-97100-2500-102100</option>
                  
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
            <h3 class="card-title">7th Pay Details/7ನೇ ವೇತನ ಆಯೋಗದ ವರದಿಯಂತೆ</h3>
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
                      <td>{formValues.payScale}</td>
                      <td >
                        {formValues.payScale}
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