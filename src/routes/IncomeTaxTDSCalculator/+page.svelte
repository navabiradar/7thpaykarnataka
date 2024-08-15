<script>

    let totalSalary ;
    // {
    //     "feb" : {
    //         "earning" : {
    //             "basicPay" : 0,
    //             "dearnessAllowance" : 0,
    //             "houseRentAllowance" : 0,
    //             "cityCompensatoryAllowance" : 0,
    //             "chargeAllowance" : 0,
    //             "otherAllowance" : 0,
    //             "grossSalary" : 0,
    //         },
    //         "deduction" : {
    //             "professionalTax" : 200,
    //             "groupInsuranceScheme" : 0,
    //             "kgid" : 0,
    //             "licInsurance" : 0,

    //         }

    //     }
    // }

    totalSalary = [
        
        ["Mar-24",2,3,4,5,6,7,8,9,10,11,12,13,14,15,16],
        ["Apr-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["May-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["Jun-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["Jul-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["Aug-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["Sep-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["Oct-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0], 
        ["Nov-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["Dec-24",0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
        ["Jan-25",0,0,0,0,0,0,0,0,0,0,0,0,0,155,0],
        ["Feb-25",2,3,4,5,6,7,8,9,10,11,12,13,14,15,16],
    ]


   function calSalary(id){
        console.log( id) ;
   }
    
</script>

<svelte:head>
    <title>Karnataka State Government Employees DA Calculator and Arrears Calculator Orders,UGC DA Orders, AICTE DA Orders, Dearness Allowance, Employee Salary Hike</title>
    <meta name="description" content="Find the latest Karnataka State Government Employees DA Calcuator and Arrears orders and updates. Stay informed about dearness allowance hikes for government employees in Karnataka. Check eligibility, notification dates, and implementation details.">


</svelte:head>


<main>
    <div class="card">
        <div class="card-header">
           <span class="text-center">Income Tax/TDS Calculator</span> 
        </div>
        <div class="card-body">
            <table class="table table-bordered table-responsive">
                <tbody>
                  <tr>
                    
                    <th class="text-wrap">Month</th>
                    <th class="text-wrap">Basic Pay</th>
                    <th class="text-wrap">DA</th>
                    <th class="text-wrap">HRA</th>
                    <th class="text-wrap">CCA</th>
                    <th class="text-wrap">Charge Allowance</th>
                    <th class="text-wrap">Other Allowance</th>
                    <th class="text-wrap">Gross Pay</th>
                    <th class="text-wrap">P.T</th>
                    <th class="text-wrap">G.I.S</th>
                    <th class="text-wrap">K.G.I.D</th>
                    <th class="text-wrap">LIC/Insurance</th>
                    <th class="text-wrap">NPS</th>
                    <th class="text-wrap">GPF</th>
                    <th class="text-wrap">Other Deduction</th>
                    <th class="text-wrap">Net Pay</th>
                  </tr>
                </tbody>
                <tbody>
                    {#each totalSalary as data, i }
                    <tr>
                            
                            <th>{ data[0] }</th>
                            <th>{ #if i < 13}
                                <input type="number" bind:value={totalSalary[i][0]} on:change={calSalary} class="form-control border-0 focus-none"  />
                            {/if }</th>
                            <th>{data[2]}</th>
                            <th>{data[3]}</th>
                            <th>{data[4]}</th>
                            <th>{ #if i < 13}
                                <input type="number" class="form-control border-0 focus-none"  />
                            {/if }</th>
                            <th>{ #if i < 13}
                                <input type="number" class="form-control border-0 focus-none"  />
                            {/if }</th>
                            <th>{data[7]}</th>
                            <th>{data[8]}</th>
                            <th>{data[9]}</th>
                            <th>{ #if i < 13}
                                <input type="number" class="form-control border-0 focus-none"  />
                            {/if }</th>
                            <th>{ #if i < 13}
                                <input type="number" class="form-control border-0 focus-none"  />
                            {/if }</th>
                            <th>{data[12]}</th>
                            <th>{ #if i < 13}
                                <input type="number" class="form-control border-0 focus-none"  />
                            {/if }</th>
                            <th>{ #if i < 13}
                                <input type="number" class="form-control border-0 focus-none"  />
                            {/if }</th>
                            <th>{data[15]}</th>
                           
                        </tr>
                    {/each}
                 
                 
                
                </tbody>
              </table>
        </div>
    </div>
</main>