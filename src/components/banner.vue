<template>
    <div class="h-screen bg-red-200 bg-cover bg-[url('./assets/wedding1.jpg')]" >
        <div class="container p-8 mx-auto flex flex-col h-full text-[#fffb] pt-16">
            <nav class="flex items-end rounded-xl  uppercase  text-lg gap-16 justify-center ">
                <div class="flex-1 flex justify-between">
                    <div class="flex gap-4">
                        <a href="#">
                            <img class="h-6" src="../assets/icons/facebook.png">
                        </a>
                        <a href="#">
                            <img class="h-6" src="../assets/icons/instagram.png">
                        </a>
                    </div>
                    <ul class="flex gap-10 drop-shadow-md border-t border-[#fff5] p-1 px-4">
                        <li><a href="#">home</a></li>
                        <li><a href="#">wedding</a></li>
                        <li><a href="#">photo</a></li>
                    </ul>
                </div>
                <img src="../assets/logo.png" class="w-40 h-20 object-cover" alt="">
                <div class="flex-1 flex justify-start">
                    <ul class="flex gap-10  border-t border-[#fff5] p-1 px-4">
                        <li><a href="#">films</a></li>
                        <li><a href="#">about</a></li>
                        <li><a href="#">contact</a></li>
                    </ul>
                </div>
            </nav>
            <div class="flex justify-between items-center  flex-1">
                <button class="bg-[#fff2] p-4 rounded-lg hover:scale-105 hover:bg-[#fff3] duration-200 shadow-xl border border-[#fff3]">
                    <img class="w-8" src="../assets/icons/left-arrow.png" />
                </button>
                <button class="bg-[#fff2] p-4 rounded-lg  hover:scale-105 hover:bg-[#fff3] duration-200 shadow-xl border border-[#fff3]">
                    <img class="w-8" src="../assets/icons/right-arrow.png" />
                </button>
            </div>
        </div>
    </div>
</template>
<script>
    export default{
        name:"banner"
    }
</script>