<script>
    import "@tabler/core/dist/css/tabler.min.css";
</script>


<svelte:head>
    <script src="https://cdn.jsdelivr.net/npm/@tabler/core@1.0.0-beta17/dist/js/tabler.min.js"></script>
    <style>
        input[type=number]::-webkit-inner-spin-button, 
input[type=number]::-webkit-outer-spin-button { 
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    margin: 0; 
}
    </style>

</svelte:head>


<div class="page">
    <!-- Navbar -->
    <header class="navbar navbar-expand-md d-print-none">
      <div class="container-xl">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-menu" aria-controls="navbar-menu" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="navbar-brand navbar-brand-autodark d-none-navbar-horizontal pe-0 pe-md-3">
          <a href=".">
            <svg width="281" height="17" viewBox="0 0 281 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M5.432 13.4L5.12 7.184L11.456 0.199999H17.624L10.52 8.024L7.376 11.24L5.432 13.4ZM0.368 17V0.199999H5.936V17H0.368ZM11.408 17L6.464 10.472L10.136 6.584L17.96 17H11.408ZM16.0518 17L23.3958 0.199999H28.9638L36.3078 17H30.4518L25.0278 2.888H27.2358L21.8118 17H16.0518ZM20.4198 14.072L21.8598 9.992H29.5878L31.0278 14.072H20.4198ZM37.2118 17V0.199999H45.2998C46.8678 0.199999 48.2198 0.455999 49.3558 0.967999C50.5078 1.48 51.3958 2.216 52.0198 3.176C52.6438 4.12 52.9558 5.24 52.9558 6.536C52.9558 7.832 52.6438 8.952 52.0198 9.896C51.3958 10.824 50.5078 11.536 49.3558 12.032C48.2198 12.528 46.8678 12.776 45.2998 12.776H40.3558L42.8758 10.448V17H37.2118ZM47.2678 17L43.1398 10.88H49.1398L53.3158 17H47.2678ZM42.8758 11.072L40.3558 8.504H44.9398C45.7238 8.504 46.2998 8.328 46.6678 7.976C47.0518 7.624 47.2438 7.144 47.2438 6.536C47.2438 5.928 47.0518 5.448 46.6678 5.096C46.2998 4.744 45.7238 4.568 44.9398 4.568H40.3558L42.8758 2V11.072ZM55.0946 17V0.199999H59.7506L68.2946 10.424H66.1346V0.199999H71.6546V17H66.9986L58.4546 6.776H60.6146V17H55.0946ZM72.5596 17L79.9036 0.199999H85.4716L92.8156 17H86.9596L81.5356 2.888H83.7436L78.3196 17H72.5596ZM76.9276 14.072L78.3676 9.992H86.0956L87.5356 14.072H76.9276ZM96.5238 17V4.592H91.6038V0.199999H107.108V4.592H102.188V17H96.5238ZM105.911 17L113.255 0.199999H118.823L126.167 17H120.311L114.887 2.888H117.095L111.671 17H105.911ZM110.279 14.072L111.719 9.992H119.447L120.887 14.072H110.279ZM132.135 13.4L131.823 7.184L138.159 0.199999H144.327L137.223 8.024L134.079 11.24L132.135 13.4ZM127.071 17V0.199999H132.639V17H127.071ZM138.111 17L133.167 10.472L136.839 6.584L144.663 17H138.111ZM142.755 17L150.099 0.199999H155.667L163.011 17H157.155L151.731 2.888H153.939L148.515 17H142.755ZM147.123 14.072L148.563 9.992H156.291L157.731 14.072H147.123ZM172.838 17L179.174 2.216L180.686 4.592H172.718L174.926 2.024V7.04H170.246V0.199999H184.622V3.68L179.03 17H172.838ZM190.227 17V4.592H185.307V0.199999H200.811V4.592H195.891V17H190.227ZM213.178 0.199999H218.842V17H213.178V0.199999ZM207.946 17H202.282V0.199999H207.946V17ZM213.562 10.808H207.562V6.152H213.562V10.808ZM228.766 17V0.199999H236.854C238.422 0.199999 239.774 0.455999 240.91 0.967999C242.062 1.48 242.95 2.216 243.574 3.176C244.198 4.12 244.51 5.24 244.51 6.536C244.51 7.832 244.198 8.952 243.574 9.896C242.95 10.84 242.062 11.576 240.91 12.104C239.774 12.616 238.422 12.872 236.854 12.872H231.91L234.43 10.448V17H228.766ZM234.43 11.072L231.91 8.504H236.494C237.278 8.504 237.854 8.328 238.222 7.976C238.606 7.624 238.798 7.144 238.798 6.536C238.798 5.928 238.606 5.448 238.222 5.096C237.854 4.744 237.278 4.568 236.494 4.568H231.91L234.43 2V11.072ZM243.7 17L251.044 0.199999H256.612L263.956 17H258.1L252.676 2.888H254.884L249.46 17H243.7ZM248.068 14.072L249.508 9.992H257.236L258.676 14.072H248.068ZM268.102 17V9.632L269.398 13.016L261.766 0.199999H267.742L272.902 8.96H269.422L274.63 0.199999H280.102L272.518 13.016L273.766 9.632V17H268.102Z" fill="#3DB9F9"/>
            </svg>
                
          </a>
        </div>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-menu" aria-controls="navbar-menu" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
      </div>
    </header>
    <header class="navbar-expand-md">
      <div class="collapse navbar-collapse" id="navbar-menu">
        <div class="navbar">
          <div class="container-xl">
            <div class="row flex-fill align-items-center">
              <div class="col">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link" href="./">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/home -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M5 12l-2 0l9 -9l9 9l-2 0"></path><path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7"></path><path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        Home
                      </span>
                    </a>
                  </li>
                  
                  <li class="nav-item">
                    <a class="nav-link" href="./illustrations.html">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/brand-figma -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path><path d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"></path><path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        7th Pay Salary Calculation 
                      </span>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="./illustrations.html">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/brand-figma -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path><path d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"></path><path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        7th Pay Pension Calculation 
                      </span>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="./illustrations.html">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/brand-figma -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path><path d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"></path><path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        7th Pay Family Pension Calculation 
                      </span>
                    </a>
                  </li>
                </ul>
              </div>
             
            </div>
          </div>
        </div>
      </div>
    </header>
    <div class="page-wrapper">
      <!-- Page body -->
      <div class="page-body">
        <div class="container-xl my-auto">

            
            <slot></slot>
        </div>
      </div>
      
    </div>
  </div>