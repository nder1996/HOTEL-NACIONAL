<template>
    <v-parallax class='parallax' dark src="@/assets/slider.jpg">
        <v-row align="center" justify="center">
            <v-col class="text-center" cols="12">
                <h1 class="text-h4 font-weight-thin mb-4">
                   Hotel Nacional
                </h1>
                <h4 class="subheading">
                   40% off on Online-Bookings
                </h4>
            </v-col>
        </v-row>
    </v-parallax>
</template>
<script>
export default {
    name: 'slider'
}
</script>
<style scoped>
	.parallax{
		border: 5px solid red !important;
		height: 300px;
		 object-fit: cover;
		 color: white;
	}
</style>