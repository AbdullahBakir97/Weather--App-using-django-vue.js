<template>
    <p>Cloud Cover: {{ cloudCover }}%</p>
  </template>
  
  <script>
  export default {
    props: {
      cloudCover: Number,
    },
  };
  </script>
  