<script setup>
    import QandA from '../components/QandA.vue';
</script>

<template>

    <div className="h-screen bg-cover  pt-14 text-white " style="margin-top: -56px; background-image: url('./bg.png'); height: ;">
        <div className="flex items-center  justify-between text-white my-6 w-full ">
            <div className="pl-[120px]">
                <img src="logo.png" className="w-[150px] "/>
            </div>
            <div className="flex pr-[120px]">
                <div className="flex items-center m-2 py-1 px-4 border-gray-500 border-[1px] rounded-md">
                    <svg width="17" height="17" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg" >
                        <path d="M8.5 17C7.33833 17 6.24042 16.7767 5.20625 16.3302C4.17208 15.8837 3.26882 15.2745 2.49645 14.5027C1.72465 13.7309 1.11548 12.8279 0.668951 11.7937C0.222418 10.7596 -0.000565589 9.66167 1.07731e-06 8.5C1.07731e-06 7.32417 0.223268 6.22257 0.669801 5.1952C1.11633 4.16783 1.7255 3.26853 2.4973 2.4973C3.2691 1.72493 4.1718 1.11577 5.2054 0.6698C6.239 0.223833 7.3372 0.000566667 8.5 0C9.67583 0 10.7774 0.223267 11.8048 0.6698C12.8322 1.11633 13.7315 1.7255 14.5027 2.4973C15.2751 3.2691 15.8842 4.16868 16.3302 5.19605C16.7762 6.22342 16.9994 7.32473 17 8.5C17 9.66167 16.7767 10.7596 16.3302 11.7937C15.8837 12.8279 15.2745 13.7312 14.5027 14.5035C13.7309 15.2753 12.8313 15.8845 11.804 16.331C10.7766 16.7776 9.67527 17.0006 8.5 17ZM8.5 15.2575C8.86833 14.7475 9.18708 14.2162 9.45625 13.6637C9.72542 13.1112 9.945 12.5233 10.115 11.9H6.885C7.055 12.5233 7.27458 13.1112 7.54375 13.6637C7.81292 14.2162 8.13167 14.7475 8.5 15.2575ZM6.29 14.9175C6.035 14.45 5.81173 13.9646 5.6202 13.4614C5.42867 12.9582 5.26943 12.4378 5.1425 11.9H2.635C3.04583 12.6083 3.55952 13.2246 4.17605 13.7487C4.79258 14.2729 5.49723 14.6625 6.29 14.9175ZM10.71 14.9175C11.5033 14.6625 12.2083 14.2729 12.8248 13.7487C13.4413 13.2246 13.9547 12.6083 14.365 11.9H11.8575C11.73 12.4383 11.5708 12.9591 11.3798 13.4623C11.1888 13.9655 10.9656 14.4506 10.71 14.9175ZM1.9125 10.2H4.8025C4.76 9.91667 4.72798 9.63673 4.70645 9.3602C4.68492 9.08367 4.67443 8.79693 4.675 8.5C4.675 8.2025 4.68577 7.91577 4.7073 7.6398C4.72883 7.36383 4.76057 7.0839 4.8025 6.8H1.9125C1.84167 7.08333 1.7884 7.36327 1.7527 7.6398C1.717 7.91633 1.69943 8.20307 1.7 8.5C1.7 8.7975 1.71785 9.08423 1.75355 9.3602C1.78925 9.63617 1.84223 9.9161 1.9125 10.2ZM6.5025 10.2H10.4975C10.54 9.91667 10.572 9.63673 10.5936 9.3602C10.6151 9.08367 10.6256 8.79693 10.625 8.5C10.625 8.2025 10.6142 7.91577 10.5927 7.6398C10.5712 7.36383 10.5394 7.0839 10.4975 6.8H6.5025C6.46 7.08333 6.42798 7.36327 6.40645 7.6398C6.38492 7.91633 6.37443 8.20307 6.375 8.5C6.375 8.7975 6.38577 9.08423 6.4073 9.3602C6.42883 9.63617 6.46057 9.9161 6.5025 10.2ZM12.1975 10.2H15.0875C15.1583 9.91667 15.2116 9.63673 15.2473 9.3602C15.283 9.08367 15.3006 8.79693 15.3 8.5C15.3 8.2025 15.2822 7.91577 15.2465 7.6398C15.2108 7.36383 15.1578 7.0839 15.0875 6.8H12.1975C12.24 7.08333 12.272 7.36327 12.2935 7.6398C12.3151 7.91633 12.3256 8.20307 12.325 8.5C12.325 8.7975 12.3142 9.08423 12.2927 9.3602C12.2712 9.63617 12.2394 9.9161 12.1975 10.2ZM11.8575 5.1H14.365C13.9542 4.39167 13.4408 3.77542 12.8248 3.25125C12.2088 2.72708 11.5039 2.3375 10.71 2.0825C10.965 2.55 11.1883 3.03535 11.3798 3.53855C11.5713 4.04175 11.7306 4.56223 11.8575 5.1ZM6.885 5.1H10.115C9.945 4.47667 9.72542 3.88875 9.45625 3.33625C9.18708 2.78375 8.86833 2.2525 8.5 1.7425C8.13167 2.2525 7.81292 2.78375 7.54375 3.33625C7.27458 3.88875 7.055 4.47667 6.885 5.1ZM2.635 5.1H5.1425C5.27 4.56167 5.42952 4.0409 5.62105 3.5377C5.81258 3.0345 6.03557 2.54943 6.29 2.0825C5.49667 2.3375 4.79173 2.72708 4.1752 3.25125C3.55867 3.77542 3.04527 4.39167 2.635 5.1Z" fill="white"/>
                    </svg>
                    <p className="ml-2 mr-4">English</p>
                    <svg width="9" height="7" viewBox="0 0 9 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M1.26874 4.11092e-05L7.2329 4.16306e-05C7.46836 -0.000299274 7.69911 0.0660479 7.89842 0.191404C8.09774 0.31676 8.25748 0.495999 8.35915 0.708375C8.47818 0.960359 8.52402 1.24071 8.49146 1.51748C8.4589 1.79425 8.34924 2.05631 8.17499 2.27379L5.1929 5.88629C5.07588 6.02132 4.93119 6.12961 4.76865 6.20383C4.6061 6.27806 4.42951 6.31647 4.25082 6.31647C4.07214 6.31647 3.89554 6.27806 3.733 6.20383C3.57045 6.12961 3.42577 6.02132 3.30874 5.88629L0.326654 2.27379C0.1524 2.05631 0.0427437 1.79425 0.0101824 1.51748C-0.0223788 1.24071 0.0234653 0.960358 0.142488 0.708374C0.244164 0.495999 0.403905 0.31676 0.603221 0.191404C0.802537 0.0660473 1.03328 -0.000299837 1.26874 4.11092e-05Z" fill="white"/>
                    </svg>
                </div>
                <div className="flex items-center m-2 py-1 px-4 font-semibold bg-red-600 rounded-md text-sm">
                    Sing In
                </div>
            </div>
        </div>
    
        <div className="text-center px-[180px] flex-col items-center my-[175px]">
            <p className="text-5xl font-extrabold ">Laughter. Tears. Thrills. Find it all on Netflix.</p>
            <p className="text-2xl mt-4">Endless entertainment starts at just THB99. Cancel anytime.</p>
            <p className="text-2xl mt-4">Ready to watch? Enter your email to create or restart your membership.</p>
            <div className="flex mt-4 justify-center">
                <div className="mx-2 flex justify-start items-center px-4 py-2 w-[400px] bg-black bg-opacity-60 border-gray-500 border-[1px] rounded-lg  ">
                    Email address
                </div>
                <div className="flex p-4 bg-red-600 rounded-lg">
                    <p className="px-2 text-2xl font-bold mr-2">Get Started</p>
                    <p className="text-xl ">></p>
                </div>
            </div>
        </div>
    </div>
    <div className="w-full bg-neutral-800 h-[10px]"></div>
    
    <div className="flex justify-center items-center py-14">
        <div className="text-white  w-2/6 m-2">
            <p className="text-5xl mb-4 font-extrabold">Enjoy on your TV </p>
            <p className="text-2xl">Watch on Smart TVs, Playstation, Xbox, Chromecast, Apple TV, Blu-ray players, and more.</p>
        </div>
        <div className="text-white  w-2/6">
            <img src="feature-1.png" style="width: 100%;">
        </div>
    </div>
    <div className="w-full bg-neutral-800 h-[10px]"></div>

    <div className="flex justify-center items-center py-14">
        <div className="text-white  w-2/6">
            <img src="feature-2.png" style="width: 100%;">
        </div>
        <div className="text-white  w-2/6 m-2">
            <p className="text-5xl mb-4 font-extrabold">Download your shows to watch offline</p>
            <p className="text-2xl">Save your favorites easily and always have something to watch.</p>
        </div>
    </div>
    <div className="w-full bg-neutral-800 h-[10px]"></div>

    <div className="flex justify-center items-center py-14">
        <div className="text-white  w-2/6 m-2">
            <p className="text-5xl mb-4 font-extrabold">Watch everywhere</p>
            <p className="text-2xl">Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
        </div>
        <div className="text-white  w-2/6">
            
        </div>
    </div>
    <div className="w-full bg-neutral-800 h-[10px]"></div>

    <div className="flex justify-center items-center py-14">
        <div className="text-white  w-2/6">
            <img src="feature-3.png" style="width: 100%;">
        </div>
        <div className="text-white  w-2/6 m-2">
            <p className="text-5xl mb-4 font-extrabold">Create profiles for kids</p>
            <p className="text-2xl">Send kids on adventures with their favorite characters in a space made just for them—free with your membership.</p>
        </div>
    </div>
    <div className="w-full bg-neutral-800 h-[10px]"></div>

    <div className="flex-col items-center flex w-8/10 mt-14 mb-8">
        <p className="font-extrabold text-white text-5xl">Frequently Asked Questions</p>
    </div>
    <QandA />
    <p className="mt-10 flex justify-center text-xl text-white">Ready to watch? Enter your email to create or restart your membership.</p>
    <div className="flex mt-4 justify-center mb-16">
        <div className="text-white mx-2 flex justify-start items-center px-4 py-2 w-[400px] bg-black bg-opacity-60 border-gray-500 border-[1px] rounded-lg  ">
            Email address
        </div>
        <div className="flex p-4 bg-red-600 rounded-lg ">
            <p className="px-2 text-2xl font-bold mr-2 text-white">Get Started</p>
            <p className="text-xl text-white">></p>
        </div>
    </div>
    <div className="w-full bg-neutral-800 h-[10px]"></div>

    <div className="text-white">
        <p>Questions? Call 1-800-012-298</p>
    </div>


</template>


<style>




</style>

