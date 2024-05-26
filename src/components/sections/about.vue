<template>

    <div>
        <Heading tempID="about" heading="About" headingNum="01"></Heading>

        <div class="nav-sm:w-[80%] ssm:w-[85%] w-2/3 flex justify-center flex-col mx-auto select-none">
            
            <p class="w-full text-base ssm:text-base-sm text-main text-justify">
            
                A highly enthusiastic and proactive student pursuing the sixth semester of Bachelor's degree in Information Systems at Gunadarma University. Possessing a profound interest in technology, particularly in the fields of system development and web development. Committed to continuously enhancing skills and knowledge in system and web development to achieve success in the technology industry.        
            </p>
    
        </div>
    </div>

</template>

<script>
    import Heading from '../heading.vue';

    export default {
        name: "about",
        components: { Heading }
    }
    

</script>