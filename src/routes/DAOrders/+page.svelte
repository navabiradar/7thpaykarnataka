<script>
    
    import {daorder} from "./DaOrder";
</script>


<main>
    <div class="card">
        <div class="card-header">
           <span class="text-center">Dearness Allowance / ತುಟ್ಟಿ ಭತ್ಯೆ</span> 
        </div>
        <div class="card-body">
            <div class="row">
                
                <div class="col table">
                    <div class="p-4">
                        <span class="text-center page-title">
                            State DA Orders / ರಾಜ್ಯ ಸರಕಾರದ ತುಟ್ಟಿ ಭತ್ಯೆ ಪ್ರಮಾಣ 
                        </span>
                    </div>
                    <table class="table table-responsive table-bordered">
                        <thead>
                            <tr>
                            <th>Month</th>
                            <th>DA Rate</th>
                            <th>Link</th>
                            
                            </tr>
                        </thead>
                        <tbody>
                                
                                    {#each daorder.reverse() as data }
                                    <tr>
                                        <td>{data.month}</td>
                                        <td>{data.daRate}</td>
                                        <td><a href={data.url}>Link</a></td>
                                    </tr>
                                    {/each}

                                
                        </tbody>

                    </table>
                </div>
                
                <div class="col table">
                    <div class="p-4">
                        <span class="text-center page-title">
                            Central/UGC DA  /ಕೇಂದ್ರ ಸರಕಾರದ ತುಟ್ಟಿ ಭತ್ಯೆ ಪ್ರಮಾಣ 
                        </span>
                    </div>
                    <table class="table table-responsive table-bordered">
                        <thead>
                            <tr>
                            <th>Month</th>
                            <th>DA Rate</th>
                            <th>Link</th>
                            
                            </tr>
                        </thead>
                        <tbody>
                                
                                   
                                    <tr>
                                        <td colspan="3" class="text-center">Upload is in progress</td>
                                        
                                    </tr>
                                   

                                
                        </tbody>

                    </table>
                </div>
            </div>
        </div>
    </div>
</main>