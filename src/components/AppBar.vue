<template>

        <v-app-bar
          color="primary"
          density="compact"
        >
          
  
          <v-app-bar-title> Groovy</v-app-bar-title>
  
          <template v-slot:append>
            <v-btn to="gallery">Gallery</v-btn>
            <v-btn to="/about">About Us</v-btn>
            <v-btn to="/appointment">Appointment</v-btn>
        </template>
        </v-app-bar>
  </template>