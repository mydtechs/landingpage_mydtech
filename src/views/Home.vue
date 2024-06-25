<template>
  <v-col>
    <v-row>
      <v-col style="display: flex;">
        <v-card-text>
          <v-icon>mdi-phone</v-icon>
          18667545970
        </v-card-text>
        <v-card-text>
          <v-icon>mdi-phone</v-icon>
          18667545970
        </v-card-text>
      </v-col>
      <v-col></v-col>
      <v-col>
        <v-card-text>
          <v-icon>mdi-map-marker</v-icon>
          3133 W, Frye rd. Suite #101 Chandler, AZ 85226
        </v-card-text>
      </v-col>
    </v-row>
    <v-row>
      <v-img :src="defaultImage" style="height: 60px"></v-img>
    </v-row>
    <v-row>
      <v-col style="background-color: green; height: 50vh; display: grid; align-content: center; justify-content: center; text-align: center; justify-items: center">
        <v-card-title style="padding:0; font-size: 38px; font-weight: bold;">
          100k SOLUTIONS
        </v-card-title>
        <v-card-title style="padding:0; margin-bottom: 12px; font-size: 25px;">
          Provide high-quality services for our valued clients
        </v-card-title>
        <v-btn color="success " style="width: fit-content;">Get a Free Estimate</v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="5"></v-col>
      <v-col style="background-color: white; height: 50vh; display: grid; align-content: center; justify-content: center; text-align: center; justify-items: center">
        <v-img :src="defaultImage" style="height: 60px"></v-img>
        <v-card-title style="padding:0; font-size: 25px; font-weight: bold;">
          Is your current cleaning company under performing & Unreliable?
        </v-card-title>
        <v-card-text style="padding:0; margin-bottom: 12px; font-size: 18px;">
          Provide high-quality services for our valued clients
        </v-card-text>
        <v-btn color="success " style="width: fit-content;">Get a Free Estimate</v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col style="background-color: #eeeeee; height: 50vh; display: grid; align-content: center; justify-content: center; text-align: center; justify-items: center">
        <v-card-title style="padding:0; font-size: 30px; font-weight: bold;">
          Limited Time Offer
        </v-card-title>
        <v-card-text style="padding:0; margin-bottom: 12px; font-size: 20px;">
          50% OFF for the first month only available until the end of month
        </v-card-text>
      </v-col>
    </v-row>
    <v-row>
      <v-col style="background-color: white; height: 50vh; display: grid; align-content: center; justify-content: center; text-align: center; justify-items: center">
        <v-card-text style="padding:0; font-size: 18px; font-weight: bold;">
          ------ Services -------
        </v-card-text>
        <v-card-title style="padding:0; margin-bottom: 12px; font-size: 38px;">
          Services We Offer
        </v-card-title>
        <v-btn color="success " style="width: fit-content;">Get a Free Estimate</v-btn>
      </v-col>
    </v-row>
  </v-col>
</template>

<script>
import InterviewBuilder from "@/assets/logo.svg"

export default{
  data() {
    return{
      defaultImage: InterviewBuilder
    }
  }
}

</script>

<style scoped>

</style>