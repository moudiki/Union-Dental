<template>
    <nav class="uk-navbar-container bg-white shadow-md shadow-gray-200  ">
        <div class="uk-container  ">

            <div uk-navbar class=" flex py-2 ">
                <div class="uk-navbar-left">

                    <NuxtLink to="/"><img src="assets/logo.svg" alt=""></NuxtLink>
                </div>
                <div class="uk-navbar-right">

                    <p class="mt-5 text-[#1E3876] font-semibold hidden md:block cursor-pointer hover:text-[#3da1e5]">+
                        555 - 1234678</p>
                    <div class=" lg:flex gap-3  hidden lg:block  cursor-pointer">
                        <span uk-icon="facebook" class=" fill-[#1E3876] hover:fill-[#3da1e5] cursor-pointer "></span>
                        <span uk-icon="instagram" class=" fill-[#1E3876] hover:fill-[#3da1e5] cursor-pointer "></span>
                        <span uk-icon="linkedin" class=" fill-[#1E3876] hover:fill-[#3da1e5] cursor-pointer "></span>
                    </div>
                    <span uk-icon="search" class="cursor-pointer fill-[#1E3876] hover:fill-[#3da1e5]"></span>
                    <NuxtLink class="uk-navbar-toggle uk-navbar-toggle-animate  lg:hidden fill-[#3da1e5] "
                        uk-navbar-toggle-icon href="#">
                    </NuxtLink>
                    <div class="uk-dropbar uk-dropbar-top  bg-[#2853b9] lg:hidden "
                        uk-drop="stretch: true; animation: reveal-top; animate-out: true; duration: 700">
                        <ul class="  uk-navbar-dropdown-nav text-lg " uk-nav>
                            <li class=" py-2">
                                <NuxtLink to="/">Home</NuxtLink>
                            </li>
                            <li class="uk-parent uk-nav-divider py-2">
                                <NuxtLink to="/services"> Services <span uk-nav-parent-icon></span> </NuxtLink>

                                <ul class="uk-nav-sub">
                                    <li>
                                        <NuxtLink to="">All Services</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="">General Dentistry</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="">Implant Dentistry</NuxtLink>
                                        <ul>
                                            <li>
                                                <NuxtLink to="">Dental Implants</NuxtLink>
                                            </li>
                                        </ul>
                                    </li>
                                    <li>
                                        <NuxtLink to="">Cosmetic Dentistry</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="">Digital X-ray</NuxtLink>
                                    </li>
                                </ul>

                            </li>
                            <li class="uk-nav-divider py-2">
                                <NuxtLink to="#">Doctors</NuxtLink>
                            </li>
                            <li class="uk-nav-divider py-2">
                                <NuxtLink to="#">About Us</NuxtLink>
                            </li>
                            <li class="uk-nav-divider py-2">
                                <NuxtLink to="#">Contact</NuxtLink>
                            </li>
                            <li class="uk-nav-divider py-2">
                                <NuxtLink to="#">Blog</NuxtLink>
                            </li>
                        </ul>
                        <div
                            class="uk-button uk-button-primary bg-[#3da1e5] rounded-full m-auto w-full mt-5 py-4 font-semibold text-xs">
                            <NuxtLink to="" class="text-white no-underline ">
                                BOOK APPOINTMENT
                            </NuxtLink>
                        </div>
                        <p class="text-center text-white">+555 - 1234678</p>
                        <div class="flex w-fit m-auto gap-5 text-white">
                            <p class="mt-5 border-r pr-5">Imprint</p>
                            <p>Privacy Policy</p>
                        </div>

                    </div>

                </div>
            </div>

            <div uk-navbar="" uk-sticky class=" border-t-2 max-lg:hidden  flex  bg-white ">
                <div class="uk-navbar-left">
                    <ul class="  uk-navbar-nav [&>li>a]:font-small">
                        <li class="">
                            <NuxtLink to="/" active-class="uk-active !text-[#3da1e5] "
                                class=" text-black relative group">
                                <div
                                    class="absolute w-full h-0.5 bg-[#3da1e5] top-[-2px] scale-x-0 group-hover:scale-x-100 transition-transform duration-500 ">
                                </div>
                                Home
                            </NuxtLink>
                        </li>
                        <li class="">
                            <NuxtLink to="/services" active-class="" class=" text-black relative group">
                                <div
                                    class="absolute w-full h-0.5 bg-[#3da1e5] top-[-2px] scale-x-0 group-hover:scale-x-100 transition-transform duration-500 ">
                                </div>
                                services
                            </NuxtLink>
                            <div class=" uk-navbar-dropdown bg-[#2853b9] "
                                uk-dropdown="animation: reveal-top; animate-out: true; duration: 700; stretch: x;">
                                <div class="uk-nav uk-navbar-dropdown-nav flex gap-20 py-5 ]">

                                    <div class="grid lg:grid-cols-2 xl:grid-cols-3 gap-x-20 gap-y-10">
                                        <div class="flex gap-4">
                                            <img src="assets/icon-services-general-dentistry.svg" alt="">
                                            <div>
                                                <h4 class="text-white">General Dentisrty</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>


                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-digital-x-ray.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Digital-X-ray</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>

                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-cosmetic-dentistry.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Cosmetic Dentistry</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>

                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-implant-dentistry.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Implant Dentistry</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>

                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-Endodontics.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Endodontics</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>
                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-dental-surgery.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Dental surgery</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>

                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-prophylaxis.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Prophylaxis</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>

                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-emergency-care.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Emergency Care</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>

                                        <div class="flex gap-4 ">
                                            <img src="assets/icon-services-pediatric-dentistry.svg" alt="">
                                            <div>
                                                <h4 class="text-white">Pediatric Dentistry</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adip elit.</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div>
                                        <img src="assets/doctors-01.webp" class="">
                                        <h3 class="text-white">Do you have questions or need a construction?</h3>
                                        <div class="mt-8">
                                            <NuxtLink to=""
                                                class="uk-button-secondary uk-button-large bg-[#ECF0F5] text-[#1E3876] py-3 px-9 font-semibold text-xs rounded-full">
                                                CONTACT US</NuxtLink>

                                        </div>
                                    </div>


                                </div>

                            </div>


                        </li>
                        <li class="">
                            <NuxtLink to="/" active-class="" class=" text-black relative group">
                                <div
                                    class="absolute w-full h-0.5 bg-[#3da1e5] top-[-2px] scale-x-0 group-hover:scale-x-100 transition-transform duration-500 ">
                                </div>
                                Doctors
                            </NuxtLink>
                        </li>
                        <li class="">
                            <NuxtLink to="/" active-class="" class=" text-black relative group">
                                <div
                                    class="absolute w-full h-0.5 bg-[#3da1e5] top-[-2px] scale-x-0 group-hover:scale-x-100 transition-transform duration-500 ">
                                </div>
                                About Us
                            </NuxtLink>
                        </li>
                        <li class="">
                            <NuxtLink to="/" active-class="" class=" text-black relative group">
                                <div
                                    class="absolute w-full h-0.5 bg-[#3da1e5] top-[-2px] scale-x-0 group-hover:scale-x-100 transition-transform duration-500 ">
                                </div>
                                Contact
                            </NuxtLink>
                        </li>
                        <li class="">
                            <NuxtLink to="/" active-class="" class=" text-black relative group">
                                <div
                                    class="absolute w-full h-0.5 bg-[#3da1e5] top-[-2px] scale-x-0 group-hover:scale-x-100 transition-transform duration-500 ">
                                </div>
                                Blog
                            </NuxtLink>
                        </li>
                    </ul>

                </div>
                <div class="uk-navbar-right">
                    <div class="uk-button uk-button-primary bg-[#3da1e5] rounded-full  text-xs  h-fit py-3.5">
                        <NuxtLink to="" class="text-white no-underline text-center ">
                            BOOK APPOINTMENT
                        </NuxtLink>
                    </div>
                </div>



            </div>
        </div>
    </nav>
    <slot />

    <footer class="mt-8">
        <div class="uk-container">
            <div class=" lg:flex lg:justify-between">
                <img src="assets/logo.svg" class="m-auto md:m-0 lg:mb-[210px] ">
                <div class="grid grid-cols-2 mt-4 md:grid-cols-3 lg:gap-x-20 lg:mr-16 ">
                    <div class="mt-2">
                        <h5 class="text-[#1E3876]  mt-0 font-semibold">Location</h5>
                        <p class="">main Street 1234 <br>5678 Anytown <br>Germany</p>
                    </div>
                    <div class="mt-2">
                        <h5 class="text-[#1E3876]  mt-0 font-semibold">Contact</h5>
                        <p class="">info@example.com<br>+555-12345678</p>
                    </div>
                    <div class="mt-2">
                        <h5 class="text-[#1E3876]  mt-0 font-semibold">Office Hours</h5>
                        <p class="grid md:grid-cols-2">
                            <span>Mo-Tu</span><span>8am-5pm</span><span>We-Th</span><span>8am-4pm</span><span>Fr</span><span>8am-12pm</span>
                        </p>

                    </div>
                    <div class="mt-2">
                        <h5 class="text-[#1E3876]  mt-0 font-semibold">Company</h5>
                        <P class="">About Us <br>Contact <br> Imprint <br>Privacy Policy </P>
                    </div>
                    <div class="mt-2">
                        <h5 class="text-[#1E3876]  mt-0 font-semibold">Information</h5>
                        <P class="">Services <br>Doctors</P>
                    </div>
                    <div class="mt-2">
                        <h5 class="text-[#1E3876]  mt-0 font-semibold">Follow Us</h5>
                        <P class="">Services <br>Doctors</P>
                    </div>


                </div>
            </div>

            <div class="grid lg:flex lg:justify-between ">
                <p class="text-center md:text-left text-sm mt-2 lg:mt-6"><span class="pr-3">Imprint</span> <span
                        class="border-l-2 pl-3">Privacy
                        Policy</span></p>
                <p class="text-center md:text-left text-sm mt-0 lg:mt-5">@ 2024 Union Dental. All rights reserved.
                    Powered
                    by <span class="text-[#4FAAE7]">YOOtheme</span></p>
            </div>

        </div>
    </footer>
</template>