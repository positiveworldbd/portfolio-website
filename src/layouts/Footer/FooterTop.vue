<template>
    <section class="footerTop bg-slate-900 text-center">
        <div class="footerTop__content container mx-auto py-28 px-4">
            <h2 class="text-white font-bold pb-12 text-4xl sm:text-5xl">{{ title }}</h2>
            <div class="footerTop__socials text-white grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
                <div class="footerTop__widget text-left my-2 sm:my-4 lg:m-auto">
                    <span class="capitalize text-slate-100 inline-block mb-1">call</span>
                    <p class="text-2xl lg:text-3xl  font-medium">{{ phone }}</p>
                </div>
                <div class="footerTop__widget text-left my-2 sm:my-4 lg:m-auto">
                    <span class="capitalize text-slate-100 inline-block mb-1">email:</span>
                    <p class="text-2xl lg:text-3xl  font-medium">{{ email }}</p>
                </div>
                <div class="footerTop__widget text-left my-2 sm:my-4 lg:m-auto">
                    <span class="capitalize text-slate-100 inline-block mb-1">follow me:</span>
                    <div class="social__icons flex space-x-3">
                        <a href="https://www.facebook.com/CoderSujon/" class="w-10 h-10 leading-10 bg-red-600 text-center rounded-sm hover:bg-white hover:text-red-600 transition duration-200 ease-in" target="_blank">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        <a href="https://www.linkedin.com/in/codersujon/" class="w-10 h-10 leading-10 bg-red-600 text-center rounded-sm hover:bg-white hover:text-red-600 transition duration-200 ease-in" target="_blank">
                            <i class="fa-brands fa-linkedin-in"></i>
                        </a>
                        <a href="https://github.com/positiveworldbd" class="w-10 h-10 leading-10 bg-red-600 text-center rounded-sm hover:bg-white hover:text-red-600 transition duration-200 ease-in" target="_blank">
                            <i class="fa-brands fa-github-alt"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default{
    name: 'FooterTop',
    
    data(){
        return{
            title: "Let's work together",
            phone: '+8801970 366 446',
            email: 'csesujon155@gmail.com'
        }
    }
};
</script>

<!-- flex flex-col md:flex-row justify-between -->