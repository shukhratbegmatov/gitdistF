<template>
  <div data-v-5c645100="" class="c-sidebar c-sidebar-dark c-sidebar-lg-show c-sidebar-fixed">
    <div class="c-sidebar-brand" style="cursor: pointer;">
      <h6>Kasb maktab uz</h6>
    </div>
    <ul  class="c-sidebar-nav h-100 ps" style="position: relative;">
      <li class="c-sidebar-nav-item" >
        <router-link to="/teacher-dashboard"
           class="router-link-exact-active c-active c-sidebar-nav-link"
           target="_self">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" role="img" class="c-sidebar-nav-icon">
          <path
              d="M3.375 17.25h17.25c0.621-0.001 1.124-0.504 1.125-1.125v-11.25c-0.001-0.621-0.504-1.124-1.125-1.125h-17.25c-0.621 0.001-1.124 0.504-1.125 1.125v11.25c0.001 0.621 0.504 1.124 1.125 1.125h0zM3.75 5.25h16.5v10.5h-16.5z"></path>
          <path d="M0.75 18.75h22.5v1.5h-22.5v-1.5z"></path>
        </svg>Бош меню
        </router-link>
      </li>
      <li class="c-sidebar-nav-title" >Маълумотлар</li>
      <li class="c-sidebar-nav-dropdown" >
        <a class="c-sidebar-nav-dropdown-toggle">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" role="img" class="c-sidebar-nav-icon">
          <path
              d="M19.294 16.109l-3.414-2.219 1.287-2.359c0.288-0.519 0.457-1.137 0.458-1.796v-3.735c0-2.9-2.351-5.25-5.25-5.25s-5.25 2.351-5.25 5.25v0 3.735c0.001 0.658 0.17 1.277 0.468 1.815l-0.010-0.019 1.287 2.359-3.414 2.219c-1.033 0.676-1.706 1.828-1.706 3.137 0 0.002 0 0.005 0 0.007v-0 3.997h17.25v-3.997c0-0.002 0-0.005 0-0.007 0-1.309-0.673-2.461-1.692-3.128l-0.014-0.009zM19.5 21.75h-14.25v-2.497c0-0.001 0-0.003 0-0.004 0-0.785 0.404-1.477 1.015-1.877l0.009-0.005 4.578-2.976-1.952-3.578c-0.173-0.311-0.274-0.682-0.275-1.077v-3.735c0-2.071 1.679-3.75 3.75-3.75s3.75 1.679 3.75 3.75v0 3.735c-0 0.395-0.102 0.766-0.281 1.089l0.006-0.012-1.952 3.579 4.578 2.976c0.62 0.406 1.024 1.097 1.024 1.882 0 0.001 0 0.003 0 0.004v-0z"></path>
        </svg> Фойдаланувчилар маълумотномаси </a>
        <ul class="c-sidebar-nav-dropdown-items">
          <li class="c-sidebar-nav-item" visible="visible">
            <a href="/PersonalInfo/Employee" class="c-sidebar-nav-link" target="_self">
              Ходимлар
            </a>
          </li>
          <li class="c-sidebar-nav-item" visible="visible">
            <a href="/PersonalInfo/Department" class="c-sidebar-nav-link"  target="_self">
              Бўлим
            </a>
          </li>
        </ul>
      </li>
<!--      <li class="c-sidebar-nav-title" >Ҳужжатлар</li>-->
<!--      <li class="c-sidebar-nav-dropdown" >-->
<!--        <a class="c-sidebar-nav-dropdown-toggle">-->
<!--        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" role="img" class="c-sidebar-nav-icon">-->
<!--          <path-->
<!--              d="M22.872 7.599l-10.5-6c-0.107-0.062-0.235-0.099-0.372-0.099s-0.265 0.037-0.376 0.101l0.004-0.002-10.5 6c-0.227 0.132-0.378 0.374-0.378 0.651 0 0.285 0.158 0.532 0.392 0.659l0.004 0.002 10.5 5.625c0.102 0.056 0.224 0.089 0.354 0.089s0.252-0.033 0.358-0.091l-0.004 0.002 10.5-5.625c0.237-0.129 0.396-0.377 0.396-0.661 0-0.277-0.15-0.519-0.374-0.649l-0.004-0.002zM12 13.024l-8.951-4.795 8.951-5.115 8.951 5.115z"></path>-->
<!--          <path-->
<!--              d="M1.5 11.182v1.712l10.139 5.576c0.104 0.058 0.229 0.093 0.361 0.093s0.257-0.034 0.365-0.095l-0.004 0.002 10.139-5.576v-1.712l-10.5 5.775z"></path>-->
<!--          <path-->
<!--              d="M1.5 15.3v1.7l10.147 5.412c0.102 0.056 0.224 0.088 0.353 0.088s0.251-0.033 0.357-0.090l-0.004 0.002 10.147-5.412v-1.7l-10.5 5.6z"></path>-->
<!--        </svg>-->
<!--        Кадрлар ҳисоби-->
<!--      </a>-->
<!--        <ul class="c-sidebar-nav-dropdown-items">-->
<!--          <li class="c-sidebar-nav-item" visible="visible">-->
<!--            <a href="/HRManagement/HROrgStructure" class="c-sidebar-nav-link" target="_self">-->
<!--              Ташкилот тузилмаси-->
<!--            </a>-->
<!--          </li>-->
<!--          <li class="c-sidebar-nav-item" visible="visible">-->
<!--            <a href="/HRManagement/HrAcceptanceWork" class="c-sidebar-nav-link" target="_self">-->
<!--              Ходимни ишга қабул қилиш (бўшатиш)-->
<!--            </a>-->
<!--          </li>-->
<!--        </ul>-->
<!--      </li>-->
      <li class="c-sidebar-nav-title" >Ҳисоботлар</li>
      <li class="c-sidebar-nav-dropdown" ><a class="c-sidebar-nav-dropdown-toggle">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" role="img" class="c-sidebar-nav-icon">
          <path
              d="M4.125 3.375v14.813c0 0.518-0.42 0.938-0.938 0.938s-0.938-0.42-0.938-0.938v0-11.063h-1.5v11.063c0.002 1.346 1.092 2.436 2.437 2.438h17.625c1.346-0.002 2.436-1.092 2.438-2.437v-14.813zM21.75 18.188c-0.001 0.518-0.42 0.937-0.937 0.938h-15.375c0.119-0.276 0.188-0.598 0.188-0.935 0-0.001 0-0.001 0-0.002v0-13.313h16.125z"></path>
          <path d="M13.875 6.375h-6.75v7.5h6.75zM12.375 12.375h-3.75v-4.5h3.75z"></path>
          <path d="M15.375 6.375h4.875v1.5h-4.875v-1.5z"></path>
          <path d="M15.375 9.375h4.875v1.5h-4.875v-1.5z"></path>
          <path d="M15.375 12.375h4.875v1.5h-4.875v-1.5z"></path>
        </svg>
        Ўқувчилар
      </a>
        <ul class="c-sidebar-nav-dropdown-items">
          <li class="c-sidebar-nav-item" visible="visible">
            <a href="/StudentReports/OtherStudentsCount" class="c-sidebar-nav-link" target="_self">
                Ўқувчилар сони бўйича ҳисобот
            </a>
          </li>
        </ul>
      </li>
      <li class="c-sidebar-nav-dropdown" ><a class="c-sidebar-nav-dropdown-toggle">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" role="img" class="c-sidebar-nav-icon">
          <path
              d="M4.125 3.375v14.813c0 0.518-0.42 0.938-0.938 0.938s-0.938-0.42-0.938-0.938v0-11.063h-1.5v11.063c0.002 1.346 1.092 2.436 2.437 2.438h17.625c1.346-0.002 2.436-1.092 2.438-2.437v-14.813zM21.75 18.188c-0.001 0.518-0.42 0.937-0.937 0.938h-15.375c0.119-0.276 0.188-0.598 0.188-0.935 0-0.001 0-0.001 0-0.002v0-13.313h16.125z"></path>
          <path d="M13.875 6.375h-6.75v7.5h6.75zM12.375 12.375h-3.75v-4.5h3.75z"></path>
          <path d="M15.375 6.375h4.875v1.5h-4.875v-1.5z"></path>
          <path d="M15.375 9.375h4.875v1.5h-4.875v-1.5z"></path>
          <path d="M15.375 12.375h4.875v1.5h-4.875v-1.5z"></path>
        </svg>
        Мактаб таълими
      </a>
        <ul class="c-sidebar-nav-dropdown-items">
          <li class="c-sidebar-nav-item" visible="visible">
            <a href="/SchoolEducationReports/ReportEmployeesCount" class="c-sidebar-nav-link" target="_self">
            Ўқитувчилар сони бўйича ҳисобот
            </a>
          </li>
        </ul>
      </li>
      <li class="c-sidebar-nav-title" >Бошқариш</li>
      <li class="c-sidebar-nav-dropdown" >
        <a class="c-sidebar-nav-dropdown-toggle">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" role="img" class="c-sidebar-nav-icon">
          <path
              d="M11.491 7.875c-2.278 0-4.125 1.847-4.125 4.125s1.847 4.125 4.125 4.125c2.278 0 4.125-1.847 4.125-4.125v0c-0.003-2.277-1.848-4.122-4.125-4.125h-0zM11.491 14.625c-1.45 0-2.625-1.175-2.625-2.625s1.175-2.625 2.625-2.625c1.45 0 2.625 1.175 2.625 2.625v0c-0.002 1.449-1.176 2.623-2.625 2.625h-0z"></path>
          <path
              d="M21.783 15.109l-1.489-1.226c0.126-0.566 0.198-1.216 0.198-1.883s-0.072-1.317-0.209-1.943l0.011 0.060 1.489-1.226c0.21-0.173 0.342-0.432 0.342-0.723 0-0.173-0.047-0.335-0.129-0.474l0.002 0.004-1.529-2.648c-0.164-0.283-0.466-0.469-0.811-0.469-0.119 0-0.232 0.022-0.337 0.062l0.006-0.002-1.808 0.677c-0.908-0.823-1.996-1.467-3.196-1.866l-0.064-0.018-0.317-1.902c-0.075-0.447-0.459-0.783-0.922-0.783-0.001 0-0.002 0-0.003 0h-3.057c-0.001 0-0.002 0-0.003 0-0.463 0-0.847 0.336-0.921 0.778l-0.001 0.005-0.317 1.902c-1.263 0.417-2.351 1.061-3.267 1.891l0.008-0.007-1.808-0.677c-0.098-0.038-0.211-0.060-0.33-0.060-0.345 0-0.646 0.187-0.808 0.465l-0.002 0.004-1.529 2.648c-0.079 0.135-0.126 0.296-0.126 0.469 0 0.291 0.133 0.55 0.341 0.722l0.002 0.001 1.489 1.226c-0.126 0.566-0.198 1.216-0.198 1.883s0.072 1.317 0.209 1.943l-0.011-0.060-1.489 1.226c-0.21 0.173-0.342 0.432-0.342 0.723 0 0.173 0.047 0.335 0.129 0.474l-0.002-0.004 1.529 2.648c0.164 0.283 0.466 0.47 0.811 0.47 0.119 0 0.232-0.022 0.337-0.062l-0.006 0.002 1.808-0.677c0.908 0.823 1.996 1.467 3.196 1.866l0.064 0.018 0.317 1.902c0.075 0.447 0.459 0.783 0.922 0.783 0.001 0 0.002 0 0.003 0h3.057c0.001 0 0.002 0 0.003 0 0.463 0 0.847-0.336 0.921-0.778l0.001-0.005 0.317-1.902c1.263-0.417 2.351-1.061 3.267-1.891l-0.008 0.007 1.808 0.677c0.098 0.038 0.211 0.060 0.33 0.060 0.345 0 0.646-0.187 0.808-0.465l0.002-0.004 1.529-2.648c0.079-0.135 0.126-0.296 0.126-0.469 0-0.291-0.133-0.55-0.341-0.722l-0.002-0.001zM19.409 17.786l-2.255-0.845-0.341 0.344c-0.914 0.921-2.064 1.605-3.352 1.955l-0.053 0.012-0.469 0.124-0.396 2.374h-2.104l-0.396-2.374-0.469-0.124c-1.341-0.362-2.491-1.047-3.404-1.967l-0-0-0.341-0.344-2.255 0.845-1.052-1.822 1.858-1.529-0.127-0.467c-0.166-0.59-0.261-1.267-0.261-1.967s0.095-1.377 0.274-2.020l-0.013 0.053 0.127-0.467-1.858-1.529 1.052-1.822 2.255 0.845 0.341-0.344c0.914-0.921 2.064-1.605 3.352-1.955l0.053-0.012 0.469-0.124 0.396-2.374h2.104l0.396 2.374 0.469 0.124c1.341 0.362 2.491 1.047 3.404 1.967l0 0 0.341 0.344 2.255-0.845 1.052 1.822-1.858 1.529 0.127 0.467c0.166 0.59 0.261 1.267 0.261 1.967s-0.095 1.377-0.274 2.020l0.013-0.053-0.127 0.467 1.858 1.529z"></path>
        </svg>
          Бошқариш
        </a>
        <ul class="c-sidebar-nav-dropdown-items">
          <li class="c-sidebar-nav-item" visible="visible">
            <a href="/Management/Roles" class="c-sidebar-nav-link" target="_self">
              Ваколатлар
            </a>
          </li>
        </ul>
      </li>
      <div class="ps__rail-x" style="left: 0px; bottom: 0px;">
        <div class="ps__thumb-x" tabindex="0" style="left: 0px; width: 0px;"></div>
      </div>
      <div class="ps__rail-y" style="top: 0px; right: 0px;">
        <div class="ps__thumb-y" tabindex="0" style="top: 0px; height: 0px;"></div>
      </div>
    </ul>
    <button type="button" class="c-sidebar-minimizer d-md-down-none"></button>
  </div>
</template>
