<script>
import AOS from 'aos'
import 'aos/dist/aos.css'

export default {
    mounted(){
        AOS.init();
    }
}

</script>
<template>
    <h2 class=" font-engplot text-[2rem] md:text-[2.6rem] text-center mt-8">Our Tour Package</h2>
    <p class=" font-engplot text-[1.1rem] md:text-[1.3rem] md:mt-[-0.7rem] text-center">Best Tour And Travel Service Just For You</p>
    <div class=" flex justify-center gap-4 flex-wrap w-[80%] mx-auto mt-5">
        <div class="package" data-aos="zoom-in"> 
            <img src="/images/package-1.jpg" alt=""> 
            <h3>Package Tour</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque pariatur.</p>
        </div>
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-2.jpg" alt=""> 
            <h3>Package Tour</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque pariatur.</p>   
        </div>
        <div class="package" data-aos="zoom-in"> 
             <img src="/images/package-3.jpg" alt=""> 
             <h3>Package Tour</h3>
             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque pariatur.</p>    
        </div>
        <div class="package" data-aos="zoom-in"> 
             <img src="/images/package-4.jpg" alt=""> 
             <h3>Package Tour</h3>
             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque pariatur.</p>
        </div>
        <div class="package" data-aos="zoom-in"> 
             <img src="/images/package-5.jpg" alt=""> 
             <h3>Package Tour</h3>
             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque pariatur.</p>
        </div>
        <div class="package" data-aos="zoom-in">
             <img src="/images/package-6.jpg" alt=""> 
             <h3>Package Tour</h3>
             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque pariatur.</p>    
        </div>
    </div>
</template>
<style>
.package {
    @apply bg-slate-200 w-[14rem] h-[17rem];
}
.package img {
    @apply w-full h-[10rem];
}
.package p{
    @apply font-engplot text-[0.8rem] px-1 text-center;
}
.package h3 {
    @apply font-engplot text-center mt-3;
}
</style>