<template>
    <hr class="w-[50%] my-12 mx-auto" />
    <div class="flex gap-8 container mx-auto my-10 items-start">
        <img class="rounded-2xl drop-shadow-2xl -rotate-2 w-[25vw] " src="../assets/contact.png" alt="">
        <div class="flex flex-col gap-4 flex-1 px-8">
            <h1 class="text-3xl font-bold ">GET IN TOUCH</h1>
            <h4 class="text-gray-500">You can also write to me directly via contact@alamiphotography.com or call +212676545984</h4>
            <div class="flex flex-col w-full">
                <div class="flex w-full gap-4">
                    <input placeholder="first name" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                    <input placeholder="last name" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                </div>
                <div class="flex w-full gap-4">
                    <input placeholder="email address" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                    <input placeholder="phone number" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                </div>
                <div class="flex w-full gap-4">
                    <input placeholder="object" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                    <input placeholder="ceremony location" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                </div>
                <div class="flex w-full gap-4">
                    <input placeholder="scheduled date" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                    <input placeholder="how did you find us?" class="border-b flex-1 py-4 text-xl outline-none px-2" type="text" name="" id="">
                </div>
                <div class="flex w-full gap-4">
                    <textarea placeholder="message" class="border-b h-36 flex-1 py-4 text-xl outline-none px-2" type="text" name="" id=""></textarea>
                </div>
                <div>
                    <button class="border px-8 py-3 my-8 bg-gray-800 text-white font-normal rounded hover:bg-gray-200 ">Submit</button>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default{
        name:"contact"
    }
</script>