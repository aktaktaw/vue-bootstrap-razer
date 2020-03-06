<template>
 <div>
     <section>
     <b-carousel id="carousel-1"
                 v-model="slide"
                 :interval="4000"
                 controls
                 fade
                 indicators
                 img-width="1024"
                 img-height="480"
                 background="#ababab"
                 style="text-shadow: 1px 1px 2px #333"
                 >
        <b-carousel-slide img-src="https://cdn.glitch.com/205bdfe9-5f43-4464-affa-fe6b82c8f534%2Fcarousel-2.png?v=1583419900328" >
            <h1>Build with Vue and BootstrapVue</h1>
            <b-button variant="outline-light" size="lg">Learn More</b-button>
        </b-carousel-slide>

        <b-carousel-slide img-src="https://cdn.glitch.com/205bdfe9-5f43-4464-affa-fe6b82c8f534%2Fcarousel-1.png?v=1583419902108">
            <h1>Test Landing Page</h1>
        </b-carousel-slide>

        <b-carousel-slide img-src="https://cdn.glitch.com/205bdfe9-5f43-4464-affa-fe6b82c8f534%2Fcarousel-3.png?v=1583419901339">
            <h1>Build Game Server Website</h1>
        </b-carousel-slide>
     </b-carousel>
    </section>
    <section >
        <b-jumbotron fluid="md" bg-variant="dark" text-variant="white">
            <template v-slot:header>Bootstrap Vue</template>
            <template v-slot:lead>
                This is a simple hero unit, a simple jumbotron-style component for calling extra attention to feature content or information
            </template>
            <hr class="my-4"/>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Repudiandae, quia in? Voluptates saepe veniam labore possimus alias impedit incidunt dolore.</p>
            
            <b-button variant="danger" href="#">Do Something</b-button>
        </b-jumbotron>
    </section>
    <section>
        <b-container fluid="sm" class="bv-example-row">
            <b-row>
                <b-col>Column1</b-col>
                <b-col>Column1</b-col>
                <b-col>Column1</b-col>
                <div class="w-100"></div>
                <b-col>Column1</b-col>
                <b-col>Column1</b-col>
                <b-col>Column1</b-col>
            </b-row>
            <b-row>
                <b-col>Column2</b-col>
                <b-col>Column2</b-col>
                <b-col>Column2</b-col>
                <b-col>Column2</b-col>
            </b-row>
        </b-container>
    </section>
 </div>
</template>

<script>
export default {

}
</script>

<style>

</style>