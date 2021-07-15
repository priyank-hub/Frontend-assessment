<template>
  <div class="pt-4 pb-4 justify-content-center">
    <div class="bg-light">
      <b-navbar toggleable="lg" type="light" variant="" class="p-0 navs">
        <b-navbar-brand href="#">
          <div class="d-flex flex-row">
            <i class="fa fa-search text-muted p-2" aria-hidden="true"></i>
            <div class="">
              <input type="email" class="form-control foorm" placeholder="search">
            </div>
          </div>
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapsed" class="m-2"></b-navbar-toggle>

        <b-collapse id="nav-collapsed" is-nav class="p-2 pb-0">
          <div class="w-100 d-flex flex-row">
            <ul class="nav nav-tabs w-75 no-outline" id="myTab" role="tablist">
              <li class="nav-item act" role="presentation">
                <button class="nav-link text-primary fnt-wgt" id="home-tab" data-bs-toggle="tab" data-bs-target="#home" type="button" role="tab" aria-controls="home" aria-selected="false">Blog</button>
              </li>
              <li class="nav-item" role="presentation">
                <button class="nav-link text-muted" id="profile-tab" data-bs-toggle="tab" data-bs-target="#profile" type="button" role="tab" aria-controls="profile" aria-selected="true">Questions</button>
              </li>
              <li class="nav-item" role="presentation">
                <button class="nav-link text-muted" id="contact-tab" data-bs-toggle="tab" data-bs-target="#contact" type="button" role="tab" aria-controls="contact" aria-selected="false">Companies</button>
              </li>
              <li class="nav-item" role="presentation">
                <button class="nav-link text-muted" id="contact-tab" data-bs-toggle="tab" data-bs-target="#contact" type="button" role="tab" aria-controls="contact" aria-selected="false">Contract</button>
              </li>
            </ul>
            <div class="p-2 mr">
              <b-icon-gear font-scale="1" />
            </div>
            <div class="p-2 mr">
              <b-icon-envelope-open font-scale="1" />
            </div>
            <div class="p-2 mr">
              <b-icon-box-arrow-right font-scale="1" />
            </div>
          </div>

        </b-collapse>
      </b-navbar>
      
      <div class="tab-content" id="myTabContent">
        <div class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">
            <div class="pl-2">
              <div class="p-2 pb-0">
                <h3 class="m-4 mb-0">Master</h3>
                <p class="m-4 mt-0 mb-2 text-muted">Chemical Tanker</p>
              </div>
            </div>

            <div class="p-4 pl-8">
              <ul class="nav nav-tabs " id="myTabs" role="tablist">
                <li class="nav-item act first" role="presentation">
                  <button class="nav-link text-primary first fnt-wgt" id="home-tab" data-bs-toggle="tab" data-bs-target="#home" type="button" role="tab" aria-controls="home" aria-selected="false">Description</button>
                </li>
                <li class="nav-item" role="presentation">
                  <button class="nav-link text-muted" id="profile-tab" data-bs-toggle="tab" data-bs-target="#profile" type="button" role="tab" aria-controls="profile" aria-selected="true">Insight</button>
                </li>
                <li class="nav-item" role="presentation">
                  <button class="nav-link text-muted" id="contact-tab" data-bs-toggle="tab" data-bs-target="#contact" type="button" role="tab" aria-controls="contact" aria-selected="false">Applicants</button>
                </li>
                <li class="nav-item" role="presentation">
                  <button class="nav-link text-muted" id="contact-tab" data-bs-toggle="tab" data-bs-target="#contact" type="button" role="tab" aria-controls="contact" aria-selected="false">Notifications</button>
                </li>
              </ul>
            </div>

            <div class="p-4 pt-0">
              <div class="container">
                <div class="row g-2 temp">
                  <div class="main p-4 rounded">
                    <h4 class="text-muted">Job Description</h4>
                    <table class="table table-borderless text-muted">
                        <thead>
                          <tr class="border-none">
                            <th scope="col" class=""></th>
                            <th scope="col"></th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr class="border-bottom">
                            <td>Rank</td>
                            <td>Master</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Ship type</td>
                            <td>Chemical Tanker</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Min Experience</td>
                            <td>06 Months</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>US Visa</td>
                            <td>Required</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Approx Joining</td>
                            <td>20 September 2016</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Salary</td>
                            <td>5000 USD</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Ship Details</td>
                            <td>
                              Chembulk gibrlater<br>
                              210000 DWT<br>
                              2010 Built
                            </td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Description</td>
                            <td>
                              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur."
                            </td>
                          </tr>
                        </tbody>
                      </table>
                    <!-- <div class="p-3 border bg-light">Custom column padding</div> -->
                  </div>
                  
                  <div class="col">
                    <div class="col-12">
                      <div class="main p-4 rounded">
                        <b-icon-facebook  font-scale="2"></b-icon-facebook>
                        <span class="margin">Share on facebook</span>
                      </div>
                      <!-- <div class="p-3 border bg-light">Custom column padding</div> -->
                    </div>
                    <div class="col-12 mt-4">
                      <div class="main p-4 rounded">
                        <h4 class="text-muted">Other Jobs</h4>

                        <div class="d-flex flex-row border-bottom pb-3">
                          <i class="fa fa-building text-muted p-4" aria-hidden="true"></i>
                          <div class="">
                              <h5>Master</h5>
                              <span class="text-muted">Chemical Tanker</span>
                              <br><span class="text-muted">Posted: 20 Aug 2016</span>
                          </div>
                        </div>

                        <div class="d-flex flex-row border-bottom pb-3 pt-3">
                          <i class="fa fa-building text-muted p-4" aria-hidden="true"></i>
                          <div class="">
                              <h5>Master</h5>
                              <span class="text-muted">Chemical Tanker</span>
                              <br><span class="text-muted">Posted: 20 Aug 2016</span>
                          </div>
                        </div>

                        <div class="d-flex flex-row border-bottom pb-3 pt-3">
                          <i class="fa fa-building text-muted p-4" aria-hidden="true"></i>
                          <div class="">
                              <h5>Master</h5>
                              <span class="text-muted">Chemical Tanker</span>
                              <br><span class="text-muted">Posted: 20 Aug 2016</span>
                          </div>
                        </div>

                        <div class="d-flex flex-row pt-3">
                          <i class="fa fa-building text-muted p-4" aria-hidden="true"></i>
                          <div class="">
                              <h5>Master</h5>
                              <span class="text-muted">Chemical Tanker</span>
                              <br><span class="text-muted">Posted: 20 Aug 2016</span>
                          </div>
                        </div>
                  
                      </div>
                      <!-- <div class="p-3 border bg-light">Custom column padding</div> -->
                    </div>
                  </div>
                </div>
              </div>
            </div>





              <!-- <div class="p-4"> -->
                
                <!-- <div class="container p-0">
                  <div class="row">
                    <div class="col-9 p-5 main rounded">
                      <h4 class="text-muted">Job Description</h4>
                      <table class="table table-borderless text-muted">
                        <thead>
                          <tr class="border-none">
                            <th scope="col" class="">
                              
                            </th>
                            <th scope="col"></th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr class="border-bottom">
                            <td>Rank</td>
                            <td>Master</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Ship type</td>
                            <td>Chemical Tanker</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Min Experience</td>
                            <td>06 Months</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>US Visa</td>
                            <td>Required</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Approx Joining</td>
                            <td>20 September 2016</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Salary</td>
                            <td>5000 USD</td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Ship Details</td>
                            <td>
                              Chembulk gibrlater<br>
                              210000 DWT<br>
                              2010 Built
                            </td>
                          </tr>
                          <tr class="border-bottom">
                            <td>Description</td>
                            <td></td>
                          </tr>
                        </tbody>
                      </table>
                    </div>
                    <div class="col">
                      <div class="row align-items-start m-4 mt-0">
                        <div class="col main rounded d-block">
                          <b-icon-facebook  class="">
                          </b-icon-facebook>
                        </div>
                      </div>

                      <div class="row align-items-end m-4">
                        <div class="col main rounded">
                          down
                        </div>
                      </div>
                    </div>
                  </div>
                </div>               
              </div>
            </div> -->
        </div>

        <!-- <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">
          This is some placeholder content the Profile tab's associated content. Clicking another tab will toggle the visibility of this one for the next.
        </div>
        <div class="tab-pane fade" id="contact" role="tabpanel" aria-labelledby="contact-tab">
          This is some placeholder content the Contact tab's associated content. Clicking another tab will toggle the visibility of this one for the next.
        </div> -->
      </div>     
    </div>

  </div>
</template>

<script>
  // import { BNavbar, BCollapse } from 'bootstrap-vue'
  // import { BIconFacebook } from 'bootstrap-vue'

  export default {
    name: 'HelloWorld',
    props: {
      msg: String
    },

    components: {
      // BNavbar,
      // BTab,
      // BCollapse,
      // BIconFacebook,
    }, 

    data() {
      return {
        blog: true,
        questions: false,
        companies: false,
        contact: false,
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#myTabContent {
  background-color: #e6e6e6;
}
.navs {
  background-color: #fff; 
}
.main {
  background-color: #fff;
}

#myTab {
  border: none;
  text-align: center;
}

#myTabs {
  border-bottom: 0px solid #6c757d;
  text-align: center;
}

.act {
  border-bottom: 2px solid #0d6efd;
}

.fnt-wgt {
  font-weight: 700;
}

.mr {
  margin-right: 20px;
} 

.temp {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-gap: 1rem;
}


@media (min-width: 600px) {
  .temp { grid-template-columns: repeat(2, 1fr); }
}

@media (min-width: 900px) {
  .temp { grid-template-columns: 2fr 1fr; }
}

.margin {
  margin-left: 20px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.foorm {
  border: none;
}

.first {
  padding-left: 0px;
}
</style>
