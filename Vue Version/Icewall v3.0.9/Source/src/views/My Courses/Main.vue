<template>
  <h2 class="intro-y text-lg font-medium mt-10">My Courses</h2>
  <div class="grid grid-cols-12 gap-6 mt-5">
    <div class="intro-y col-span-12 flex flex-wrap sm:flex-nowrap items-center ml-auto mt-2">

      <div class="w-full sm:w-auto mt-3 sm:mt-0 sm:ml-auto md:ml-0 ">
        <div class="w-56 relative text-slate-500">
          <input type="text" class="form-control w-56 box pr-10" placeholder="Search..." />
          <SearchIcon class="w-4 h-4 absolute my-auto inset-y-0 mr-3 right-0" />
        </div>
      </div>

    </div>

  </div>
  <h2 class="intro-y text-lg font-medium">Recent Courses</h2>
    <div class="grid grid-cols-12 gap-6 mt-5">
      <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-4">
         <div
            class="h-64 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group1.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10" style="background-color:#F4791D !important;">Sky Study</span>
            <div class="absolute w-full bottom-0 text-white px-5 pb-6 z-10"> <div class="flex items-center"><h2 class="text-lg font-medium" style="    font-size: 35px;">Course Title 01 </h2></div>
            <div class="flex items-center mt-2"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mt-2"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>

            <button class="btn btn-lg btn-light" style="color: black; background: white; width: 240px;height: 50px;margin-top: 27px;"> View More</button>
          </div>
          </div>
        </div>

     <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-4">
         <div
            class="h-64 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask _group2.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10" style="background-color:#F4791D !important;">Space Study</span>
            <div class="absolute w-full bottom-0 text-white px-5 pb-6 z-10"> <div class="flex items-center"><h2 class="text-lg font-medium" style="    font-size: 35px;">Course Title 02 </h2></div>
            <div class="flex items-center mt-2"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mt-2"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>

            <button class="btn btn-lg btn-light" style="color: black; background: white; width: 240px;height: 50px;margin-top: 27px;"> View More</button>
          </div>
          </div>
        </div>


         <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-4">
         <div
            class="h-64 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group3.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10" style="background-color:#F4791D !important;">Ocean Study</span>
            <div class="absolute w-full bottom-0 text-white px-5 pb-6 z-10"> <div class="flex items-center"><h2 class="text-lg font-medium" style="    font-size: 35px;">Course Title 03 </h2></div>
            <div class="flex items-center mt-2"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mt-2"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>

            <button class="btn btn-lg btn-light" style="color: black; background: white; width: 240px;height: 50px;margin-top: 27px;"> View More</button>
          </div>
          </div>
        </div>
    </div>
  <div class="grid grid-cols-12 gap-6 mt-5">
     <div class="intro-y col-span-12 md:col-span-12 lg:col-span-12 xl:col-span-12">
<TabGroup>
    <TabList class="nav-link-tabs flex-none">
        <Tab class="py-2" tag="button">All</Tab>
        <Tab class="py-2 flex-none" tag="button">Popular</Tab>
        <Tab class="py-2" tag="button">Favourites</Tab>
        <Tab class="py-2" tag="button">Drafts</Tab>
    </TabList>
    <TabPanels class="mt-5">
        <TabPanel class="leading-relaxed">
            <div class="grid grid-cols-12 gap-6 mt-5">
   <!-- BEGIN: Users Layout -->
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>

    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
              </div>

        </TabPanel>
          <TabPanel class="leading-relaxed">
            <div class="grid grid-cols-12 gap-6 mt-5">
   <!-- BEGIN: Users Layout -->
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>

    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
              </div>

        </TabPanel>
          <TabPanel class="leading-relaxed">
            <div class="grid grid-cols-12 gap-6 mt-5">
   <!-- BEGIN: Users Layout -->
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>

    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
              </div>

        </TabPanel>
          <TabPanel class="leading-relaxed">
            <div class="grid grid-cols-12 gap-6 mt-5">
   <!-- BEGIN: Users Layout -->
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>

    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>
          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        

      </div>
    </div>
    <div class="intro-y col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3">
      <div class="box">
        <div class="p-5">
          <div
            class="h-40 2xl:h-56 image-fit rounded-md overflow-hidden ">
            <img alt="Midone - HTML Admin Template" class="rounded-md" src="/src/assets/images/Mask_group.png"><span
              class="absolute top-0 bg-pending/80 text-white text-xs m-5 px-2 py-1 rounded z-10">New</span>
          </div>
          <div class="text-slate-600 dark:text-slate-500 mt-5">
            <div class="flex items-center"><h2 class="text-lg font-medium">Course Title 01 </h2></div>
            <div class="flex items-center my-4"><img alt="Midone - HTML Admin Template" class="icons-image" height="20" width="20" src="/src/assets/images/preview-12.jpg"/> Instructor: John Smith | 5.5 <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill=" #FEC64F"  stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-auto" style=""><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg></div>
            <div class="flex items-center mb-4"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mr-3"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>2h 30 min   <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide block mx-3"><path d="M14.5 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline></svg> 8 Lessons</div>
          </div>
          <p>Duis autem vel eum iriure dolor in hendrerit lorem ipsum dolor...</p>

          <button class="btn btn-lg btn-outline-primery" style=" height: 54px; width: 100%; margin-top: 17px; color: #1D409B; border-color: #1D409B;">Edit Course</button>
        </div>
        
      </div>
    </div>
              </div>

        </TabPanel>
    </TabPanels>
</TabGroup>
        </div>
 
    
    <!-- END: Users Layout -->
    <!-- BEGIN: Pagination -->
    <div class="intro-y col-span-12 flex flex-wrap sm:flex-row sm:flex-nowrap items-center">
      <nav class="w-full sm:w-auto sm:mr-auto">
        <ul class="pagination">
          <li class="page-item">
            <a class="page-link" href="#">
              <ChevronsLeftIcon class="w-4 h-4" />
            </a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#">
              <ChevronLeftIcon class="w-4 h-4" />
            </a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#">...</a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#">1</a>
          </li>
          <li class="page-item active">
            <a class="page-link" href="#">2</a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#">3</a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#">...</a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#">
              <ChevronRightIcon class="w-4 h-4" />
            </a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#">
              <ChevronsRightIcon class="w-4 h-4" />
            </a>
          </li>
        </ul>
      </nav>
     
    </div>
    <!-- END: Pagination -->
  </div>
  <!-- BEGIN: Delete Confirmation Modal -->
  <Modal :show="deleteConfirmationModal" @hidden="deleteConfirmationModal = false">
    <ModalBody class="p-0">
      <div class="p-5 text-center">
        <XCircleIcon class="w-16 h-16 text-danger mx-auto mt-3" />
        <div class="text-3xl mt-5">Are you sure?</div>
        <div class="text-slate-500 mt-2">
          Do you really want to delete these records? <br />This process cannot
          be undone.
        </div>
      </div>
      <div class="px-5 pb-8 text-center">
        <button type="button" @click="deleteConfirmationModal = false" class="btn btn-outline-secondary w-24 mr-1">
          Cancel
        </button>
        <button type="button" class="btn btn-danger w-24">Delete</button>
      </div>
    </ModalBody>
  </Modal>
  <!-- END: Delete Confirmation Modal -->
</template>

<script setup>
import { ref } from "vue";

const deleteConfirmationModal = ref(false);
</script>
