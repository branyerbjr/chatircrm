<template>
    <div>
        <Navbar />
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-3">
            <Sidebar />
          </div>
          <div class="col-md-9">
           
            <!-- Main content slot -->
            <router-view></router-view>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import Navbar from "@/components/Navbar.vue";
  import Sidebar from "@/components/Sidebar.vue";
  
  export default {
    components: {
      Navbar,
      Sidebar,
    },
    // Dashboard component logic
  };
  </script>
  
  <style scoped>
  /* Dashboard component styles */
  </style>
  