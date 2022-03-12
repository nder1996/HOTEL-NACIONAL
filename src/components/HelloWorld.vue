<template>
    <v-container class='container_navbar_1' fluid>
        <v-row>
            <v-col class='columnas_navbar' sm='10'>
                <h5 class='mt-1' style='margin: auto;position: relative;left: 7rem;'>Last COVID19 update - Security measures</h5>
            </v-col>
            <v-col class='columnas_navbar d-flex justify-center' sm='2'>
              <div>
                 <h6  class='mt-1'>Join us</h6>
              </div>
                <div class='icon_navbar d-flex justify-space-between'>
                    <h6  class='mt-1'>
                        <v-icon>
                            mdi-instagram
                        </v-icon>
                    </h6>
                    &nbsp;&nbsp;
                    <h6  class='mt-1'>
                        <v-icon>
                            mdi-facebook
                        </v-icon>
                    </h6>
                    &nbsp;&nbsp;
                    <h6  class='mt-1'>
                        <v-icon>
                            mdi-twitter
                        </v-icon>
                    </h6>
                    &nbsp;&nbsp;
                </div>
            </v-col>
        </v-row>
    </v-container>
</template>
<script>
export default {
    name: 'HelloWorld',
}
</script>
<style>
.container_navbar_1 {
    #border: 5px solid red;
    background-color: #2C3A52;
    color: white !important;
    padding: 15px !important;
}
.columnas_navbar {
    #border: 5px solid black;
    margin: 0;
    padding: 0;
}
.icon_navbar {
    position: relative;
    left: 1rem;
}
.icon_navbar p{
  position: relative;
  #left: 1rem;
}
</style>