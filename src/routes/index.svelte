<script>

let menu;


function handleClick() {
    if (menu.classList.contains('hidden')) {
        menu.classList.remove('hidden')
     } else { 
        menu.classList.add('hidden')        
    }
};

</script>


 

  <!--   nav wrapper -->  
   
  <!-- end nav -->


    
        <div class="flex justify-center md:justify-end">
            <a href="/" class='btn text-red-500 md:border-2 border-red-400 hover:bg-red-400 hover:text-white'>Log in</a>
            <a href="/" class='btn text-red-500 md:border-2 border-red-400 ml-2 hover:bg-red-400 hover:text-white'>Sign up</a>
        </div>

        <header>
            <h2 class="text-gray-700 text-6xl font-semibold leading-none tracking-wider">Recipes</h2>
             <h3 class="text-gray-700 text-2xl font-semibold tracking-wider">For Ninjas</h3>
        </header>

        <div >
            <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Latest Recipes</h4>
            
            
            <div class="mt-8 grid lg:grid-cols-3 gap-10 overflow-x-hidden">

                <!-- cards go here-->
                <div class="card">
                    <img src="stew.jpg" alt="" class="w-full h-32 sm:h-48 object-cover">
                    <div class="m-4">
                        <span class="font-bold">5 Bean Chillie Stew</span>
                        <span class='block text-gray-500 text-sm'>Recipe by Mario</span>
                    </div>
                    <div class="badge">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                          </svg>
                        <span>
                            25 mins
                        </span>
                    </div>
                </div>


                    <div class="card hover:shadow-lg">
                        <img src="noodles.jpg" alt="noodles" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span class="font-bold">Veg Noodles</span>
                            <span class='block text-gray-500 text-sm'>Recipe by Mario</span>
                        </div>
                        <div class="badge">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                              </svg>
                            <span>
                                25 mins
                            </span>
                        </div>
                    </div>

                        <div class="card hover:shadow-lg">
                            <img src="curry.jpg" alt="curry" class="w-full h-32 sm:h-48 object-cover">
                            <div class="m-4">
                                <span class="font-bold">Tofu Curry</span>
                                <span class='block text-gray-500 text-sm'>Recipe by Mario</span>
                            </div>
                            <div class="badge">
                                <svg xmlns="http://www.w3.org/2000/svg" class="w-5 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                                  </svg>
                                <span>
                                    25 mins
                                </span>
                            </div>
                        </div>
              


            </div>

            <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Most Popular </h4>
            <div class="mt-8">
                    <!--cards go here-->
                </div>
           
                <div class="flex justify-center">
                    <div class="btn bg-gray-300 text-gray-600 hover:shadow-inner transform hover:scale-125 hover:bg-opacity-50 transition ease-out-300">Load more</div>
                </div>

        </div>








<style>
    .card {
    @apply bg-white rounded overflow-hidden shadow-md relative;
        }

    .card:hover {
        @apply shadow-lg;
    }

    .badge {
        @apply bg-gray-300 text-red-500 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-2 mt-2;
    }


    .btn {
        @apply rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer;
    }

    .btn:hover {
        @apply shadow-inner;
    }
</style>