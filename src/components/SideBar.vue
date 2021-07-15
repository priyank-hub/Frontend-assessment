<template>
  <div class="mt-5" id="side">
    
    <div>
      <b-navbar toggleable="lg" type="light" variant="" class="d-flex flex-column m-0">
        
        <b-navbar-toggle target="nav-collapse" class="mt-0"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav class="w-100">
          <b-navbar-nav class="d-flex flex-column w-100">
            <div class="">
              <b-navbar-brand href="#" class="">
                <div class="p-4 pb-0"><b-icon-person-fill font-scale="2" class="text-white w-100 border rounded-circle h-25 p-4"/></div>
              </b-navbar-brand>
              <h6 class="text-white m-0 text-center">Devinder Kumar</h6>
              <p class="text-center text-white">Chief officer</p>

              <div class="text-center">
                <button type="button" class="roun btn btn-outline-light">Update Profile</button>
              </div>
            </div>  
            <div class="mt-5">
              <div class="d-flex flex-column p-4 w-100 sec">
                <div>
                  <b-icon-laptop font-scale="3" class="w-100 text-white"/>
                </div>
                <div class="text-center mt-2 text-white">DASHBOARD</div>
              </div>

              <div class="d-flex flex-column p-4 sec active">
                <div>
                  <b-icon-newspaper font-scale="3" class="w-100 text-white"/>
                </div>
                <div class="text-center mt-2 text-white">JOBS</div>
              </div>

              <div class="d-flex flex-column p-4 sec">
                <div>
                  <b-icon-file-earmark-word font-scale="3" class="w-100 text-white"/>
                </div>
                <div class="text-center mt-2 text-white">SEA DOCS</div>
              </div>

              <div class="d-flex flex-column p-4 sec">
                <div>
                  <b-icon-people font-scale="3" class="w-100 text-white"/>
                </div>
                <div class="text-center mt-2 text-white">CONNECTIONS</div>
              </div>
            </div>
            
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>

  </div>
</template>

<script>
  import { BNavbar, BCollapse } from 'bootstrap-vue'
  export default {
    name: 'SideBar',
    props: {
      
    },

    components: {
      BNavbar,
      BCollapse,
    }
  }
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@200&display=swap');

h6 {
  font-family: 'Raleway';
}


.items-center {
  text-align: center;
}

#side {
  background-color: #3e5eb7;
}

.sec:hover {
  background-color: #1d2c96;
  border-left: 2px solid #05fbf0;
}

.active {
  background-color: #1d2c96;
  border-left: 2px solid #05fbf0;
}

.roun {
  border-radius: 40px;
}

</style>