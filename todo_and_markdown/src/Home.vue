<template>
  <h1>Hello World!</h1>
    <p>
    <!-- use the router-link component for navigation. -->
    <!-- specify the link by passing the `to` prop. -->
    <!-- `<router-link>` will render an `<a>` tag with the correct `href` attribute -->
    <router-link to="/">Go to Home</router-link>
    <router-link to="/tool">Go to Tool</router-link>
  </p>
  <!-- route outlet component matched by the route will render here -->
  <router-view/>
</template>