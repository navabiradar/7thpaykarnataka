<script>
    import "@tabler/core/dist/css/tabler.min.css";
</script>


<svelte:head>
    <meta name="description" content="Karnataka Govt Orders , Karnataka 7th Pay, Pay Fixation, Pension Fixation, Family Pension Fixation">
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
                    <a class="nav-link" href="/DAOrders">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/brand-figma -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path><path d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"></path><path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        DA Orders / ತುಟ್ಟಿ ಭತ್ಯೆ ಆದೇಶಗಳು 
                      </span>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="/NormalPensionCalculator">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/brand-figma -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path><path d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"></path><path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        Pension Calculator 
                      </span>
                    </a>
                  </li>
                  
                  <li class="nav-item">
                    <a class="nav-link" href="/7thPaySalaryCalculation">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/brand-figma -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path><path d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"></path><path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        7th Pay Salary Calculation 
                      </span>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="/7thPayPensionCalculation">
                      <span class="nav-link-icon d-md-none d-lg-inline-block"><!-- Download SVG icon from http://tabler-icons.io/i/brand-figma -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path><path d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"></path><path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15"></path></svg>
                      </span>
                      <span class="nav-link-title">
                        7th Pay Pension Calculation 
                      </span>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="/7thPayFamilyPensionCalculation">
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

          <div class="card mb-2">
            <div class="card-body ">
              <h3 class="text-center" ><a href="https://t.me/ksgesangh">
                
                <svg width="64px" height="64px" viewBox="-10.88 -10.88 53.76 53.76" fill="none" xmlns="http://www.w3.org/2000/svg"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <circle cx="16" cy="16" r="14" fill="url(#paint0_linear_87_7225)"></circle> <path d="M22.9866 10.2088C23.1112 9.40332 22.3454 8.76755 21.6292 9.082L7.36482 15.3448C6.85123 15.5703 6.8888 16.3483 7.42147 16.5179L10.3631 17.4547C10.9246 17.6335 11.5325 17.541 12.0228 17.2023L18.655 12.6203C18.855 12.4821 19.073 12.7665 18.9021 12.9426L14.1281 17.8646C13.665 18.3421 13.7569 19.1512 14.314 19.5005L19.659 22.8523C20.2585 23.2282 21.0297 22.8506 21.1418 22.1261L22.9866 10.2088Z" fill="white"></path> <defs> <linearGradient id="paint0_linear_87_7225" x1="16" y1="2" x2="16" y2="30" gradientUnits="userSpaceOnUse"> <stop stop-color="#37BBFE"></stop> <stop offset="1" stop-color="#007DBB"></stop> </linearGradient> </defs> </g></svg>
                ಎಲ್ಲಾ ಕರ್ನಾಟಕ ಸರ್ಕಾರಿ ನೌಕರರು ಟೆಲಿಗ್ರಾಂ ಸೇರಿಕೊಳ್ಳಲು ಕ್ಲಿಕ್ ಮಾಡಿ </a></h3>
              
            </div>
        </div>

            
        <slot></slot>

        <div class="row row-card">
              
                <div class=" card  mt-2 ">
                  <a href="https://t.me/ksgesangh">
                  <div class="card-body">
                    <svg id="svgQrWrapper" viewBox="0 0 300 300" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="300" height="300" style="width: 100%; height: 100%; background-color: rgb(255, 255, 255);"><svg><g transform="translate(9, 9)scale(0.95)" fill="none"><svg width="300" height="300"><style>.background-color{ fill: #fff; }.dot-color{ fill: #000000; }.corners-square-color-0-0{ fill: #000000; }.corners-dot-color-0-0{ fill: #000000; }.corners-square-color-1-0{ fill: #000000; }.corners-dot-color-1-0{ fill: #000000; }.corners-square-color-0-1{ fill: #000000; }.corners-dot-color-0-1{ fill: #000000; }</style><defs/><g class="dot-color"><rect x="5" y="85" width="10" height="10" transform="rotate(0,10,90)"/><rect x="5" y="95" width="10" height="10" transform="rotate(0,10,100)"/><rect x="5" y="105" width="10" height="10" transform="rotate(0,10,110)"/><rect x="5" y="125" width="10" height="10" transform="rotate(0,10,130)"/><rect x="5" y="135" width="10" height="10" transform="rotate(0,10,140)"/><rect x="5" y="165" width="10" height="10" transform="rotate(0,10,170)"/><rect x="5" y="175" width="10" height="10" transform="rotate(0,10,180)"/><rect x="5" y="185" width="10" height="10" transform="rotate(0,10,190)"/><rect x="15" y="85" width="10" height="10" transform="rotate(0,20,90)"/><rect x="15" y="95" width="10" height="10" transform="rotate(0,20,100)"/><rect x="15" y="115" width="10" height="10" transform="rotate(0,20,120)"/><rect x="15" y="135" width="10" height="10" transform="rotate(0,20,140)"/><rect x="15" y="175" width="10" height="10" transform="rotate(0,20,180)"/><rect x="15" y="185" width="10" height="10" transform="rotate(0,20,190)"/><rect x="25" y="85" width="10" height="10" transform="rotate(0,30,90)"/><rect x="25" y="105" width="10" height="10" transform="rotate(0,30,110)"/><rect x="25" y="115" width="10" height="10" transform="rotate(0,30,120)"/><rect x="25" y="145" width="10" height="10" transform="rotate(0,30,150)"/><rect x="25" y="155" width="10" height="10" transform="rotate(0,30,160)"/><rect x="25" y="195" width="10" height="10" transform="rotate(0,30,200)"/><rect x="35" y="85" width="10" height="10" transform="rotate(0,40,90)"/><rect x="35" y="105" width="10" height="10" transform="rotate(0,40,110)"/><rect x="35" y="135" width="10" height="10" transform="rotate(0,40,140)"/><rect x="35" y="165" width="10" height="10" transform="rotate(0,40,170)"/><rect x="35" y="185" width="10" height="10" transform="rotate(0,40,190)"/><rect x="45" y="85" width="10" height="10" transform="rotate(0,50,90)"/><rect x="45" y="95" width="10" height="10" transform="rotate(0,50,100)"/><rect x="45" y="135" width="10" height="10" transform="rotate(0,50,140)"/><rect x="45" y="195" width="10" height="10" transform="rotate(0,50,200)"/><rect x="45" y="205" width="10" height="10" transform="rotate(0,50,210)"/><rect x="55" y="105" width="10" height="10" transform="rotate(0,60,110)"/><rect x="55" y="115" width="10" height="10" transform="rotate(0,60,120)"/><rect x="55" y="145" width="10" height="10" transform="rotate(0,60,150)"/><rect x="55" y="155" width="10" height="10" transform="rotate(0,60,160)"/><rect x="55" y="165" width="10" height="10" transform="rotate(0,60,170)"/><rect x="55" y="175" width="10" height="10" transform="rotate(0,60,180)"/><rect x="55" y="195" width="10" height="10" transform="rotate(0,60,200)"/><rect x="55" y="205" width="10" height="10" transform="rotate(0,60,210)"/><rect x="65" y="85" width="10" height="10" transform="rotate(0,70,90)"/><rect x="65" y="105" width="10" height="10" transform="rotate(0,70,110)"/><rect x="65" y="125" width="10" height="10" transform="rotate(0,70,130)"/><rect x="65" y="145" width="10" height="10" transform="rotate(0,70,150)"/><rect x="65" y="165" width="10" height="10" transform="rotate(0,70,170)"/><rect x="65" y="185" width="10" height="10" transform="rotate(0,70,190)"/><rect x="65" y="205" width="10" height="10" transform="rotate(0,70,210)"/><rect x="75" y="85" width="10" height="10" transform="rotate(0,80,90)"/><rect x="75" y="105" width="10" height="10" transform="rotate(0,80,110)"/><rect x="75" y="125" width="10" height="10" transform="rotate(0,80,130)"/><rect x="75" y="145" width="10" height="10" transform="rotate(0,80,150)"/><rect x="75" y="165" width="10" height="10" transform="rotate(0,80,170)"/><rect x="75" y="175" width="10" height="10" transform="rotate(0,80,180)"/><rect x="75" y="185" width="10" height="10" transform="rotate(0,80,190)"/><rect x="75" y="195" width="10" height="10" transform="rotate(0,80,200)"/><rect x="75" y="205" width="10" height="10" transform="rotate(0,80,210)"/><rect x="85" y="15" width="10" height="10" transform="rotate(0,90,20)"/><rect x="85" y="25" width="10" height="10" transform="rotate(0,90,30)"/><rect x="85" y="45" width="10" height="10" transform="rotate(0,90,50)"/><rect x="85" y="65" width="10" height="10" transform="rotate(0,90,70)"/><rect x="85" y="75" width="10" height="10" transform="rotate(0,90,80)"/><rect x="85" y="95" width="10" height="10" transform="rotate(0,90,100)"/><rect x="85" y="185" width="10" height="10" transform="rotate(0,90,190)"/><rect x="85" y="205" width="10" height="10" transform="rotate(0,90,210)"/><rect x="85" y="225" width="10" height="10" transform="rotate(0,90,230)"/><rect x="85" y="245" width="10" height="10" transform="rotate(0,90,250)"/><rect x="85" y="255" width="10" height="10" transform="rotate(0,90,260)"/><rect x="85" y="265" width="10" height="10" transform="rotate(0,90,270)"/><rect x="85" y="275" width="10" height="10" transform="rotate(0,90,280)"/><rect x="85" y="285" width="10" height="10" transform="rotate(0,90,290)"/><rect x="95" y="5" width="10" height="10" transform="rotate(0,100,10)"/><rect x="95" y="25" width="10" height="10" transform="rotate(0,100,30)"/><rect x="95" y="35" width="10" height="10" transform="rotate(0,100,40)"/><rect x="95" y="45" width="10" height="10" transform="rotate(0,100,50)"/><rect x="95" y="75" width="10" height="10" transform="rotate(0,100,80)"/><rect x="95" y="85" width="10" height="10" transform="rotate(0,100,90)"/><rect x="95" y="125" width="10" height="10" transform="rotate(0,100,130)"/><rect x="95" y="135" width="10" height="10" transform="rotate(0,100,140)"/><rect x="95" y="145" width="10" height="10" transform="rotate(0,100,150)"/><rect x="95" y="175" width="10" height="10" transform="rotate(0,100,180)"/><rect x="95" y="185" width="10" height="10" transform="rotate(0,100,190)"/><rect x="95" y="195" width="10" height="10" transform="rotate(0,100,200)"/><rect x="95" y="265" width="10" height="10" transform="rotate(0,100,270)"/><rect x="95" y="285" width="10" height="10" transform="rotate(0,100,290)"/><rect x="105" y="15" width="10" height="10" transform="rotate(0,110,20)"/><rect x="105" y="25" width="10" height="10" transform="rotate(0,110,30)"/><rect x="105" y="35" width="10" height="10" transform="rotate(0,110,40)"/><rect x="105" y="45" width="10" height="10" transform="rotate(0,110,50)"/><rect x="105" y="55" width="10" height="10" transform="rotate(0,110,60)"/><rect x="105" y="65" width="10" height="10" transform="rotate(0,110,70)"/><rect x="105" y="75" width="10" height="10" transform="rotate(0,110,80)"/><rect x="105" y="85" width="10" height="10" transform="rotate(0,110,90)"/><rect x="105" y="205" width="10" height="10" transform="rotate(0,110,210)"/><rect x="105" y="245" width="10" height="10" transform="rotate(0,110,250)"/><rect x="105" y="255" width="10" height="10" transform="rotate(0,110,260)"/><rect x="105" y="275" width="10" height="10" transform="rotate(0,110,280)"/><rect x="105" y="285" width="10" height="10" transform="rotate(0,110,290)"/><rect x="115" y="25" width="10" height="10" transform="rotate(0,120,30)"/><rect x="115" y="35" width="10" height="10" transform="rotate(0,120,40)"/><rect x="115" y="55" width="10" height="10" transform="rotate(0,120,60)"/><rect x="115" y="95" width="10" height="10" transform="rotate(0,120,100)"/><rect x="115" y="195" width="10" height="10" transform="rotate(0,120,200)"/><rect x="115" y="205" width="10" height="10" transform="rotate(0,120,210)"/><rect x="115" y="215" width="10" height="10" transform="rotate(0,120,220)"/><rect x="115" y="225" width="10" height="10" transform="rotate(0,120,230)"/><rect x="115" y="235" width="10" height="10" transform="rotate(0,120,240)"/><rect x="115" y="245" width="10" height="10" transform="rotate(0,120,250)"/><rect x="115" y="275" width="10" height="10" transform="rotate(0,120,280)"/><rect x="125" y="15" width="10" height="10" transform="rotate(0,130,20)"/><rect x="125" y="65" width="10" height="10" transform="rotate(0,130,70)"/><rect x="125" y="85" width="10" height="10" transform="rotate(0,130,90)"/><rect x="125" y="205" width="10" height="10" transform="rotate(0,130,210)"/><rect x="125" y="225" width="10" height="10" transform="rotate(0,130,230)"/><rect x="125" y="235" width="10" height="10" transform="rotate(0,130,240)"/><rect x="135" y="5" width="10" height="10" transform="rotate(0,140,10)"/><rect x="135" y="15" width="10" height="10" transform="rotate(0,140,20)"/><rect x="135" y="25" width="10" height="10" transform="rotate(0,140,30)"/><rect x="135" y="35" width="10" height="10" transform="rotate(0,140,40)"/><rect x="135" y="75" width="10" height="10" transform="rotate(0,140,80)"/><rect x="135" y="95" width="10" height="10" transform="rotate(0,140,100)"/><rect x="135" y="205" width="10" height="10" transform="rotate(0,140,210)"/><rect x="135" y="215" width="10" height="10" transform="rotate(0,140,220)"/><rect x="135" y="225" width="10" height="10" transform="rotate(0,140,230)"/><rect x="135" y="235" width="10" height="10" transform="rotate(0,140,240)"/><rect x="135" y="275" width="10" height="10" transform="rotate(0,140,280)"/><rect x="135" y="285" width="10" height="10" transform="rotate(0,140,290)"/><rect x="145" y="15" width="10" height="10" transform="rotate(0,150,20)"/><rect x="145" y="35" width="10" height="10" transform="rotate(0,150,40)"/><rect x="145" y="65" width="10" height="10" transform="rotate(0,150,70)"/><rect x="145" y="75" width="10" height="10" transform="rotate(0,150,80)"/><rect x="145" y="95" width="10" height="10" transform="rotate(0,150,100)"/><rect x="145" y="215" width="10" height="10" transform="rotate(0,150,220)"/><rect x="145" y="225" width="10" height="10" transform="rotate(0,150,230)"/><rect x="145" y="235" width="10" height="10" transform="rotate(0,150,240)"/><rect x="145" y="265" width="10" height="10" transform="rotate(0,150,270)"/><rect x="145" y="285" width="10" height="10" transform="rotate(0,150,290)"/><rect x="155" y="5" width="10" height="10" transform="rotate(0,160,10)"/><rect x="155" y="45" width="10" height="10" transform="rotate(0,160,50)"/><rect x="155" y="55" width="10" height="10" transform="rotate(0,160,60)"/><rect x="155" y="85" width="10" height="10" transform="rotate(0,160,90)"/><rect x="155" y="195" width="10" height="10" transform="rotate(0,160,200)"/><rect x="155" y="205" width="10" height="10" transform="rotate(0,160,210)"/><rect x="155" y="215" width="10" height="10" transform="rotate(0,160,220)"/><rect x="155" y="235" width="10" height="10" transform="rotate(0,160,240)"/><rect x="165" y="5" width="10" height="10" transform="rotate(0,170,10)"/><rect x="165" y="15" width="10" height="10" transform="rotate(0,170,20)"/><rect x="165" y="25" width="10" height="10" transform="rotate(0,170,30)"/><rect x="165" y="35" width="10" height="10" transform="rotate(0,170,40)"/><rect x="165" y="55" width="10" height="10" transform="rotate(0,170,60)"/><rect x="165" y="65" width="10" height="10" transform="rotate(0,170,70)"/><rect x="165" y="75" width="10" height="10" transform="rotate(0,170,80)"/><rect x="165" y="85" width="10" height="10" transform="rotate(0,170,90)"/><rect x="165" y="195" width="10" height="10" transform="rotate(0,170,200)"/><rect x="165" y="225" width="10" height="10" transform="rotate(0,170,230)"/><rect x="165" y="235" width="10" height="10" transform="rotate(0,170,240)"/><rect x="165" y="255" width="10" height="10" transform="rotate(0,170,260)"/><rect x="165" y="275" width="10" height="10" transform="rotate(0,170,280)"/><rect x="175" y="15" width="10" height="10" transform="rotate(0,180,20)"/><rect x="175" y="45" width="10" height="10" transform="rotate(0,180,50)"/><rect x="175" y="55" width="10" height="10" transform="rotate(0,180,60)"/><rect x="175" y="75" width="10" height="10" transform="rotate(0,180,80)"/><rect x="175" y="85" width="10" height="10" transform="rotate(0,180,90)"/><rect x="175" y="95" width="10" height="10" transform="rotate(0,180,100)"/><rect x="175" y="195" width="10" height="10" transform="rotate(0,180,200)"/><rect x="175" y="205" width="10" height="10" transform="rotate(0,180,210)"/><rect x="175" y="225" width="10" height="10" transform="rotate(0,180,230)"/><rect x="175" y="275" width="10" height="10" transform="rotate(0,180,280)"/><rect x="175" y="285" width="10" height="10" transform="rotate(0,180,290)"/><rect x="185" y="5" width="10" height="10" transform="rotate(0,190,10)"/><rect x="185" y="25" width="10" height="10" transform="rotate(0,190,30)"/><rect x="185" y="45" width="10" height="10" transform="rotate(0,190,50)"/><rect x="185" y="65" width="10" height="10" transform="rotate(0,190,70)"/><rect x="185" y="95" width="10" height="10" transform="rotate(0,190,100)"/><rect x="185" y="205" width="10" height="10" transform="rotate(0,190,210)"/><rect x="185" y="215" width="10" height="10" transform="rotate(0,190,220)"/><rect x="185" y="275" width="10" height="10" transform="rotate(0,190,280)"/><rect x="185" y="285" width="10" height="10" transform="rotate(0,190,290)"/><rect x="195" y="15" width="10" height="10" transform="rotate(0,200,20)"/><rect x="195" y="25" width="10" height="10" transform="rotate(0,200,30)"/><rect x="195" y="75" width="10" height="10" transform="rotate(0,200,80)"/><rect x="195" y="85" width="10" height="10" transform="rotate(0,200,90)"/><rect x="195" y="105" width="10" height="10" transform="rotate(0,200,110)"/><rect x="195" y="115" width="10" height="10" transform="rotate(0,200,120)"/><rect x="195" y="125" width="10" height="10" transform="rotate(0,200,130)"/><rect x="195" y="155" width="10" height="10" transform="rotate(0,200,160)"/><rect x="195" y="175" width="10" height="10" transform="rotate(0,200,180)"/><rect x="195" y="205" width="10" height="10" transform="rotate(0,200,210)"/><rect x="195" y="225" width="10" height="10" transform="rotate(0,200,230)"/><rect x="195" y="275" width="10" height="10" transform="rotate(0,200,280)"/><rect x="195" y="285" width="10" height="10" transform="rotate(0,200,290)"/><rect x="205" y="5" width="10" height="10" transform="rotate(0,210,10)"/><rect x="205" y="25" width="10" height="10" transform="rotate(0,210,30)"/><rect x="205" y="55" width="10" height="10" transform="rotate(0,210,60)"/><rect x="205" y="65" width="10" height="10" transform="rotate(0,210,70)"/><rect x="205" y="125" width="10" height="10" transform="rotate(0,210,130)"/><rect x="205" y="165" width="10" height="10" transform="rotate(0,210,170)"/><rect x="205" y="175" width="10" height="10" transform="rotate(0,210,180)"/><rect x="205" y="185" width="10" height="10" transform="rotate(0,210,190)"/><rect x="205" y="205" width="10" height="10" transform="rotate(0,210,210)"/><rect x="205" y="215" width="10" height="10" transform="rotate(0,210,220)"/><rect x="205" y="225" width="10" height="10" transform="rotate(0,210,230)"/><rect x="205" y="235" width="10" height="10" transform="rotate(0,210,240)"/><rect x="205" y="245" width="10" height="10" transform="rotate(0,210,250)"/><rect x="215" y="85" width="10" height="10" transform="rotate(0,220,90)"/><rect x="215" y="95" width="10" height="10" transform="rotate(0,220,100)"/><rect x="215" y="105" width="10" height="10" transform="rotate(0,220,110)"/><rect x="215" y="115" width="10" height="10" transform="rotate(0,220,120)"/><rect x="215" y="165" width="10" height="10" transform="rotate(0,220,170)"/><rect x="215" y="175" width="10" height="10" transform="rotate(0,220,180)"/><rect x="215" y="195" width="10" height="10" transform="rotate(0,220,200)"/><rect x="215" y="205" width="10" height="10" transform="rotate(0,220,210)"/><rect x="215" y="245" width="10" height="10" transform="rotate(0,220,250)"/><rect x="215" y="275" width="10" height="10" transform="rotate(0,220,280)"/><rect x="215" y="285" width="10" height="10" transform="rotate(0,220,290)"/><rect x="225" y="85" width="10" height="10" transform="rotate(0,230,90)"/><rect x="225" y="95" width="10" height="10" transform="rotate(0,230,100)"/><rect x="225" y="135" width="10" height="10" transform="rotate(0,230,140)"/><rect x="225" y="145" width="10" height="10" transform="rotate(0,230,150)"/><rect x="225" y="185" width="10" height="10" transform="rotate(0,230,190)"/><rect x="225" y="195" width="10" height="10" transform="rotate(0,230,200)"/><rect x="225" y="205" width="10" height="10" transform="rotate(0,230,210)"/><rect x="225" y="225" width="10" height="10" transform="rotate(0,230,230)"/><rect x="225" y="245" width="10" height="10" transform="rotate(0,230,250)"/><rect x="225" y="265" width="10" height="10" transform="rotate(0,230,270)"/><rect x="225" y="275" width="10" height="10" transform="rotate(0,230,280)"/><rect x="225" y="285" width="10" height="10" transform="rotate(0,230,290)"/><rect x="235" y="95" width="10" height="10" transform="rotate(0,240,100)"/><rect x="235" y="105" width="10" height="10" transform="rotate(0,240,110)"/><rect x="235" y="115" width="10" height="10" transform="rotate(0,240,120)"/><rect x="235" y="125" width="10" height="10" transform="rotate(0,240,130)"/><rect x="235" y="135" width="10" height="10" transform="rotate(0,240,140)"/><rect x="235" y="175" width="10" height="10" transform="rotate(0,240,180)"/><rect x="235" y="185" width="10" height="10" transform="rotate(0,240,190)"/><rect x="235" y="205" width="10" height="10" transform="rotate(0,240,210)"/><rect x="235" y="245" width="10" height="10" transform="rotate(0,240,250)"/><rect x="235" y="285" width="10" height="10" transform="rotate(0,240,290)"/><rect x="245" y="85" width="10" height="10" transform="rotate(0,250,90)"/><rect x="245" y="95" width="10" height="10" transform="rotate(0,250,100)"/><rect x="245" y="105" width="10" height="10" transform="rotate(0,250,110)"/><rect x="245" y="115" width="10" height="10" transform="rotate(0,250,120)"/><rect x="245" y="125" width="10" height="10" transform="rotate(0,250,130)"/><rect x="245" y="135" width="10" height="10" transform="rotate(0,250,140)"/><rect x="245" y="145" width="10" height="10" transform="rotate(0,250,150)"/><rect x="245" y="165" width="10" height="10" transform="rotate(0,250,170)"/><rect x="245" y="185" width="10" height="10" transform="rotate(0,250,190)"/><rect x="245" y="205" width="10" height="10" transform="rotate(0,250,210)"/><rect x="245" y="215" width="10" height="10" transform="rotate(0,250,220)"/><rect x="245" y="225" width="10" height="10" transform="rotate(0,250,230)"/><rect x="245" y="235" width="10" height="10" transform="rotate(0,250,240)"/><rect x="245" y="245" width="10" height="10" transform="rotate(0,250,250)"/><rect x="245" y="255" width="10" height="10" transform="rotate(0,250,260)"/><rect x="245" y="275" width="10" height="10" transform="rotate(0,250,280)"/><rect x="255" y="95" width="10" height="10" transform="rotate(0,260,100)"/><rect x="255" y="105" width="10" height="10" transform="rotate(0,260,110)"/><rect x="255" y="115" width="10" height="10" transform="rotate(0,260,120)"/><rect x="255" y="135" width="10" height="10" transform="rotate(0,260,140)"/><rect x="255" y="155" width="10" height="10" transform="rotate(0,260,160)"/><rect x="255" y="165" width="10" height="10" transform="rotate(0,260,170)"/><rect x="255" y="185" width="10" height="10" transform="rotate(0,260,190)"/><rect x="255" y="205" width="10" height="10" transform="rotate(0,260,210)"/><rect x="255" y="215" width="10" height="10" transform="rotate(0,260,220)"/><rect x="255" y="245" width="10" height="10" transform="rotate(0,260,250)"/><rect x="265" y="85" width="10" height="10" transform="rotate(0,270,90)"/><rect x="265" y="95" width="10" height="10" transform="rotate(0,270,100)"/><rect x="265" y="105" width="10" height="10" transform="rotate(0,270,110)"/><rect x="265" y="115" width="10" height="10" transform="rotate(0,270,120)"/><rect x="265" y="135" width="10" height="10" transform="rotate(0,270,140)"/><rect x="265" y="155" width="10" height="10" transform="rotate(0,270,160)"/><rect x="265" y="165" width="10" height="10" transform="rotate(0,270,170)"/><rect x="265" y="175" width="10" height="10" transform="rotate(0,270,180)"/><rect x="265" y="195" width="10" height="10" transform="rotate(0,270,200)"/><rect x="265" y="235" width="10" height="10" transform="rotate(0,270,240)"/><rect x="265" y="245" width="10" height="10" transform="rotate(0,270,250)"/><rect x="265" y="265" width="10" height="10" transform="rotate(0,270,270)"/><rect x="265" y="285" width="10" height="10" transform="rotate(0,270,290)"/><rect x="275" y="85" width="10" height="10" transform="rotate(0,280,90)"/><rect x="275" y="95" width="10" height="10" transform="rotate(0,280,100)"/><rect x="275" y="105" width="10" height="10" transform="rotate(0,280,110)"/><rect x="275" y="115" width="10" height="10" transform="rotate(0,280,120)"/><rect x="275" y="125" width="10" height="10" transform="rotate(0,280,130)"/><rect x="275" y="135" width="10" height="10" transform="rotate(0,280,140)"/><rect x="275" y="145" width="10" height="10" transform="rotate(0,280,150)"/><rect x="275" y="165" width="10" height="10" transform="rotate(0,280,170)"/><rect x="275" y="175" width="10" height="10" transform="rotate(0,280,180)"/><rect x="275" y="195" width="10" height="10" transform="rotate(0,280,200)"/><rect x="275" y="215" width="10" height="10" transform="rotate(0,280,220)"/><rect x="275" y="225" width="10" height="10" transform="rotate(0,280,230)"/><rect x="275" y="235" width="10" height="10" transform="rotate(0,280,240)"/><rect x="275" y="275" width="10" height="10" transform="rotate(0,280,280)"/><rect x="285" y="95" width="10" height="10" transform="rotate(0,290,100)"/><rect x="285" y="155" width="10" height="10" transform="rotate(0,290,160)"/><rect x="285" y="165" width="10" height="10" transform="rotate(0,290,170)"/><rect x="285" y="175" width="10" height="10" transform="rotate(0,290,180)"/><rect x="285" y="195" width="10" height="10" transform="rotate(0,290,200)"/><rect x="285" y="205" width="10" height="10" transform="rotate(0,290,210)"/><rect x="285" y="225" width="10" height="10" transform="rotate(0,290,230)"/><rect x="285" y="245" width="10" height="10" transform="rotate(0,290,250)"/><rect x="285" y="275" width="10" height="10" transform="rotate(0,290,280)"/><rect x="285" y="285" width="10" height="10" transform="rotate(0,290,290)"/></g><g class="corners-square-color-0-0"><rect x="5" y="5" width="10" height="10" transform="rotate(0,10,10)"/><rect x="5" y="15" width="10" height="10" transform="rotate(0,10,20)"/><rect x="5" y="25" width="10" height="10" transform="rotate(0,10,30)"/><rect x="5" y="35" width="10" height="10" transform="rotate(0,10,40)"/><rect x="5" y="45" width="10" height="10" transform="rotate(0,10,50)"/><rect x="5" y="55" width="10" height="10" transform="rotate(0,10,60)"/><rect x="5" y="65" width="10" height="10" transform="rotate(0,10,70)"/><rect x="15" y="5" width="10" height="10" transform="rotate(0,20,10)"/><rect x="15" y="65" width="10" height="10" transform="rotate(0,20,70)"/><rect x="25" y="5" width="10" height="10" transform="rotate(0,30,10)"/><rect x="25" y="65" width="10" height="10" transform="rotate(0,30,70)"/><rect x="35" y="5" width="10" height="10" transform="rotate(0,40,10)"/><rect x="35" y="65" width="10" height="10" transform="rotate(0,40,70)"/><rect x="45" y="5" width="10" height="10" transform="rotate(0,50,10)"/><rect x="45" y="65" width="10" height="10" transform="rotate(0,50,70)"/><rect x="55" y="5" width="10" height="10" transform="rotate(0,60,10)"/><rect x="55" y="65" width="10" height="10" transform="rotate(0,60,70)"/><rect x="65" y="5" width="10" height="10" transform="rotate(0,70,10)"/><rect x="65" y="15" width="10" height="10" transform="rotate(0,70,20)"/><rect x="65" y="25" width="10" height="10" transform="rotate(0,70,30)"/><rect x="65" y="35" width="10" height="10" transform="rotate(0,70,40)"/><rect x="65" y="45" width="10" height="10" transform="rotate(0,70,50)"/><rect x="65" y="55" width="10" height="10" transform="rotate(0,70,60)"/><rect x="65" y="65" width="10" height="10" transform="rotate(0,70,70)"/></g><g class="corners-dot-color-0-0"><rect x="25" y="25" width="10" height="10" transform="rotate(0,30,30)"/><rect x="25" y="35" width="10" height="10" transform="rotate(0,30,40)"/><rect x="25" y="45" width="10" height="10" transform="rotate(0,30,50)"/><rect x="35" y="25" width="10" height="10" transform="rotate(0,40,30)"/><rect x="35" y="35" width="10" height="10" transform="rotate(0,40,40)"/><rect x="35" y="45" width="10" height="10" transform="rotate(0,40,50)"/><rect x="45" y="25" width="10" height="10" transform="rotate(0,50,30)"/><rect x="45" y="35" width="10" height="10" transform="rotate(0,50,40)"/><rect x="45" y="45" width="10" height="10" transform="rotate(0,50,50)"/></g><g class="corners-square-color-1-0"><rect x="225" y="5" width="10" height="10" transform="rotate(0,230,10)"/><rect x="225" y="15" width="10" height="10" transform="rotate(0,230,20)"/><rect x="225" y="25" width="10" height="10" transform="rotate(0,230,30)"/><rect x="225" y="35" width="10" height="10" transform="rotate(0,230,40)"/><rect x="225" y="45" width="10" height="10" transform="rotate(0,230,50)"/><rect x="225" y="55" width="10" height="10" transform="rotate(0,230,60)"/><rect x="225" y="65" width="10" height="10" transform="rotate(0,230,70)"/><rect x="235" y="5" width="10" height="10" transform="rotate(0,240,10)"/><rect x="235" y="65" width="10" height="10" transform="rotate(0,240,70)"/><rect x="245" y="5" width="10" height="10" transform="rotate(0,250,10)"/><rect x="245" y="65" width="10" height="10" transform="rotate(0,250,70)"/><rect x="255" y="5" width="10" height="10" transform="rotate(0,260,10)"/><rect x="255" y="65" width="10" height="10" transform="rotate(0,260,70)"/><rect x="265" y="5" width="10" height="10" transform="rotate(0,270,10)"/><rect x="265" y="65" width="10" height="10" transform="rotate(0,270,70)"/><rect x="275" y="5" width="10" height="10" transform="rotate(0,280,10)"/><rect x="275" y="65" width="10" height="10" transform="rotate(0,280,70)"/><rect x="285" y="5" width="10" height="10" transform="rotate(0,290,10)"/><rect x="285" y="15" width="10" height="10" transform="rotate(0,290,20)"/><rect x="285" y="25" width="10" height="10" transform="rotate(0,290,30)"/><rect x="285" y="35" width="10" height="10" transform="rotate(0,290,40)"/><rect x="285" y="45" width="10" height="10" transform="rotate(0,290,50)"/><rect x="285" y="55" width="10" height="10" transform="rotate(0,290,60)"/><rect x="285" y="65" width="10" height="10" transform="rotate(0,290,70)"/></g><g class="corners-dot-color-1-0"><rect x="245" y="25" width="10" height="10" transform="rotate(0,250,30)"/><rect x="245" y="35" width="10" height="10" transform="rotate(0,250,40)"/><rect x="245" y="45" width="10" height="10" transform="rotate(0,250,50)"/><rect x="255" y="25" width="10" height="10" transform="rotate(0,260,30)"/><rect x="255" y="35" width="10" height="10" transform="rotate(0,260,40)"/><rect x="255" y="45" width="10" height="10" transform="rotate(0,260,50)"/><rect x="265" y="25" width="10" height="10" transform="rotate(0,270,30)"/><rect x="265" y="35" width="10" height="10" transform="rotate(0,270,40)"/><rect x="265" y="45" width="10" height="10" transform="rotate(0,270,50)"/></g><g class="corners-square-color-0-1"><rect x="5" y="225" width="10" height="10" transform="rotate(0,10,230)"/><rect x="5" y="235" width="10" height="10" transform="rotate(0,10,240)"/><rect x="5" y="245" width="10" height="10" transform="rotate(0,10,250)"/><rect x="5" y="255" width="10" height="10" transform="rotate(0,10,260)"/><rect x="5" y="265" width="10" height="10" transform="rotate(0,10,270)"/><rect x="5" y="275" width="10" height="10" transform="rotate(0,10,280)"/><rect x="5" y="285" width="10" height="10" transform="rotate(0,10,290)"/><rect x="15" y="225" width="10" height="10" transform="rotate(0,20,230)"/><rect x="15" y="285" width="10" height="10" transform="rotate(0,20,290)"/><rect x="25" y="225" width="10" height="10" transform="rotate(0,30,230)"/><rect x="25" y="285" width="10" height="10" transform="rotate(0,30,290)"/><rect x="35" y="225" width="10" height="10" transform="rotate(0,40,230)"/><rect x="35" y="285" width="10" height="10" transform="rotate(0,40,290)"/><rect x="45" y="225" width="10" height="10" transform="rotate(0,50,230)"/><rect x="45" y="285" width="10" height="10" transform="rotate(0,50,290)"/><rect x="55" y="225" width="10" height="10" transform="rotate(0,60,230)"/><rect x="55" y="285" width="10" height="10" transform="rotate(0,60,290)"/><rect x="65" y="225" width="10" height="10" transform="rotate(0,70,230)"/><rect x="65" y="235" width="10" height="10" transform="rotate(0,70,240)"/><rect x="65" y="245" width="10" height="10" transform="rotate(0,70,250)"/><rect x="65" y="255" width="10" height="10" transform="rotate(0,70,260)"/><rect x="65" y="265" width="10" height="10" transform="rotate(0,70,270)"/><rect x="65" y="275" width="10" height="10" transform="rotate(0,70,280)"/><rect x="65" y="285" width="10" height="10" transform="rotate(0,70,290)"/></g><g class="corners-dot-color-0-1"><rect x="25" y="245" width="10" height="10" transform="rotate(0,30,250)"/><rect x="25" y="255" width="10" height="10" transform="rotate(0,30,260)"/><rect x="25" y="265" width="10" height="10" transform="rotate(0,30,270)"/><rect x="35" y="245" width="10" height="10" transform="rotate(0,40,250)"/><rect x="35" y="255" width="10" height="10" transform="rotate(0,40,260)"/><rect x="35" y="265" width="10" height="10" transform="rotate(0,40,270)"/><rect x="45" y="245" width="10" height="10" transform="rotate(0,50,250)"/><rect x="45" y="255" width="10" height="10" transform="rotate(0,50,260)"/><rect x="45" y="265" width="10" height="10" transform="rotate(0,50,270)"/></g><svg id="telegramLogotype" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50" x="107" y="107" width="86px" height="86px"><path fill="#08C" d="M50 25c0 13.807-11.193 25-25 25S0 38.807 0 25 11.193 0 25 0s25 11.193 25 25Zm-24.104-6.544c-2.432 1.012-7.291 3.105-14.58 6.28-1.183.47-1.803.931-1.86 1.381-.095.761.858 1.06 2.155 1.469.177.055.36.113.547.174 1.277.415 2.994.9 3.886.92.81.017 1.714-.317 2.712-1.002 6.809-4.597 10.324-6.92 10.545-6.97.155-.035.371-.08.517.05.147.13.132.376.117.442-.095.402-3.835 3.88-5.77 5.679-.603.56-1.031.959-1.119 1.05-.196.203-.396.396-.588.58-1.185 1.144-2.075 2.001.05 3.401 1.02.673 1.838 1.23 2.652 1.784.89.606 1.778 1.21 2.927 1.964.292.191.572.39.844.585 1.036.738 1.966 1.402 3.116 1.296.668-.062 1.358-.69 1.709-2.563.828-4.428 2.456-14.02 2.832-17.974a4.413 4.413 0 0 0-.042-.984c-.033-.195-.103-.472-.355-.677-.3-.243-.763-.294-.97-.29-.94.016-2.382.518-9.325 3.405Z"/></svg></svg></g></svg></svg>
                   
                  </div>
                </a>
                </div>
             
              
                <div class=" card  mt-2 ">
                  <a href="https://whatsapp.com/channel/0029VakqlvMJuyA6wh42iE3B">
                  <div class="card-body">
                    <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
width="450px" height="450px" viewBox="0 0 450 450" enable-background="new 0 0 450 450" xml:space="preserve">
<rect x="0" y="0" width="450" height="450" fill="rgb(255,255,255)" /><g transform="translate(20,20)"><g transform="translate(100,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,0) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,10) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,20) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,30) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,30) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,30) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,30) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,30) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,30) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,30) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,40) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,50) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,60) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,70) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,80) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,90) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,100) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,110) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,120) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,130) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,140) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,150) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,160) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,170) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,180) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,190) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,200) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,210) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,220) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,230) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,240) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,250) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,260) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,270) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,280) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,290) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(30,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,300) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(70,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,310) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(10,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(40,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(50,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(60,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,320) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,330) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(170,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,340) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,350) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(380,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,360) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(160,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(290,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,370) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(80,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(180,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(240,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(350,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(400,380) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(90,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(130,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(150,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(250,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(260,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,390) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(100,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(110,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(120,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(190,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(200,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(210,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(220,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(230,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(270,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(280,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(300,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(310,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(320,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(330,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(340,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(370,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(390,400) scale(0.1,0.1)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(0,0) scale(0.7, 0.7)"><g transform="" style="fill: rgb(0, 0, 0);">
<g>
	<rect x="15" y="15" style="fill:none;" width="70" height="70"/>
	<path d="M85,0H15H0v15v70v15h15h70h15V85V15V0H85z M85,85H15V15h70V85z"/>
</g>
</g></g><g transform="translate(340,0) scale(0.7, 0.7)"><g transform="" style="fill: rgb(0, 0, 0);">
<g>
	<rect x="15" y="15" style="fill:none;" width="70" height="70"/>
	<path d="M85,0H15H0v15v70v15h15h70h15V85V15V0H85z M85,85H15V15h70V85z"/>
</g>
</g></g><g transform="translate(0,340) scale(0.7, 0.7)"><g transform="" style="fill: rgb(0, 0, 0);">
<g>
	<rect x="15" y="15" style="fill:none;" width="70" height="70"/>
	<path d="M85,0H15H0v15v70v15h15h70h15V85V15V0H85z M85,85H15V15h70V85z"/>
</g>
</g></g><g transform="translate(20,20) scale(0.3, 0.3)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(360,20) scale(0.3, 0.3)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(20,360) scale(0.3, 0.3)"><g transform="" style="fill: rgb(0, 0, 0);">
<rect width="100" height="100"/>
</g></g><g transform="translate(140,140) scale(0.13,0.13)" width="130" height="130"><svg
   xmlns:dc="http://purl.org/dc/elements/1.1/"
   xmlns:cc="http://creativecommons.org/ns#"
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:svg="http://www.w3.org/2000/svg"
   xmlns="http://www.w3.org/2000/svg"
   version="1.1"
   width="1000"
   height="1000"
   viewBox="0 0 1000 1000"
   id="svg6742">
  
  
  <g
     transform="translate(0,-52.362183)"
     id="layer1">
    <g
       transform="matrix(7.2949439,0,0,7.2949439,2134.0674,1337.574)"
       id="g7102">
      <path
         d="m -292.54062,-107.63844 c 0,-37.85375 30.6875,-68.54 68.54125,-68.54 37.85375,0 68.54,30.68625 68.54,68.54 0,37.854997 -30.68625,68.541247 -68.54,68.541247 -37.85375,0 -68.54125,-30.68625 -68.54125,-68.541247"
         id="path3834"
         style="fill:#30bf39;fill-opacity:1;fill-rule:nonzero;stroke:none" />
      <path
         d="m -220.81062,-147.26844 c -20.64875,0 -37.39,16.74 -37.39,37.3925 0,7.065 1.96125,13.671247 5.36625,19.308747 l -6.75,20.06 20.70125,-6.62625 c 5.35875,2.96125 11.51875,4.65 18.0725,4.65 20.655,0 37.39625,-16.7425 37.39625,-37.392497 0,-20.6525 -16.74125,-37.3925 -37.39625,-37.3925 z m 0,68.521247 c -6.31875,0 -12.20875,-1.89625 -17.1225,-5.14875 l -11.96375,3.83 3.88875,-11.56 c -3.72625,-5.13125 -5.92625,-11.436247 -5.92625,-18.249997 0,-17.1675 13.9625,-31.13 31.12375,-31.13 17.16625,0 31.13,13.9625 31.13,31.13 0,17.162497 -13.96375,31.128747 -31.13,31.128747 z m 17.53375,-22.632497 c -0.93625,-0.51375 -5.54125,-2.99875 -6.40375,-3.34875 -0.8625,-0.3525 -1.495,-0.53375 -2.16875,0.3975 -0.66875,0.92875 -2.5825,3.01125 -3.15875,3.62625 -0.5825,0.61875 -1.14125,0.67625 -2.08,0.16125 -0.93375,-0.5125 -3.97375,-1.63625 -7.4975,-5.025 -2.7425,-2.635 -4.54,-5.83125 -5.06125,-6.8075 -0.52375,-0.97625 -0.004,-1.47375 0.49125,-1.93125 0.44625,-0.41375 0.9975,-1.08125 1.49625,-1.62 0.495,-0.5375 0.67,-0.93125 1.0125,-1.555 0.34125,-0.62375 0.20375,-1.1875 -0.0187,-1.67375 -0.22,-0.48625 -1.9525,-5.255 -2.675,-7.19625 -0.725,-1.93875 -1.53125,-1.65125 -2.0875,-1.67375 -0.5575,-0.0187 -1.19,-0.1225 -1.82625,-0.1475 -0.63875,-0.0225 -1.68125,0.1775 -2.58875,1.09875 -0.9125,0.92125 -3.46625,3.13875 -3.64,7.83625 -0.1775,4.695 3.0725,9.3625 3.52625,10.015 0.45375,0.65625 6.205,10.836247 15.76125,15.021247 9.5625,4.1875 9.61375,2.91125 11.36625,2.8175 1.75625,-0.0937 5.73375,-2.1 6.61375,-4.2975 0.88,-2.1975 0.95,-4.10875 0.7275,-4.514997 -0.225,-0.4075 -0.8525,-0.67 -1.78875,-1.1825"
         id="path3836"
         style="fill:#f1f2f2;fill-opacity:1;fill-rule:evenodd;stroke:none" />
    </g>
  </g>
</svg>
</g></g></svg>
                   
                  </div>
                </a>
                </div>
              </div>
              
       
      </div>
    </div>
  </div>
</div>
      
   
 
  