<script>
export default {
  data() {
    return {
      name: 'RSVP neve'
    }
  },
  methods: {
    rsvp() {
      this.$router.push('/rsvp')
    }
  }
}
</script>

<template>
  <main class="body-bg">
    <section id="header-section" class="header-backg">
        <div class="header-overlay">
            <nav class="navbar navbar-expand navbar-light">
                <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
                    <ul class="header-nav">
                        <li class="active"><a href="#header-section">HOME</a></li>
                        <li ><a href="#story-section">STORY</a></li>
                        <li ><a href="#wedding-section">WEDDING</a></li>
                        <li ><a href="#">GALLERY</a></li>
                        <li ><a href="#">PAGES</a></li>
                        <li ><a href="/rsvp">RSVP</a></li>
                    </ul>
                </div>
            </nav>
            <div class="mr-dafoe-regular">
                <p>Albert</p>
                <p class="smaller-hw" >and</p>
                <p>Emily</p>
            </div>
            <div class="bottom-text text-center text-white">
                <p>
                    WE ARE GETTING MARRIED
                </p>
            </div>
        </div>
    </section>
    <section id="story-section">
        <div class="container">
            <div class="main-text text-center">
                <h4 class="text-center text-uppercase mb-3">Happy couple</h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                </p>
            </div>
            <div class="card-group mb-3">
                
                <div class="card border-0 mx-2 body-bg">
                        <img class="card-img-top" src="/img/him-1.jpeg" alt="Card image cap">
                        <div class="card-body px-0">
                            <h6 class="card-title text-uppercase">The groom</h6>
                            <p class="card-text">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.</p>
                        </div>
                </div>
                <div class="card border-0 mx-2 body-bg">
                    <img class="card-img-top" src="/img/her-1.jpeg" alt="Card image cap">
                    <div class="card-body px-0">
                        <h6 class="card-title text-uppercase">The bride</h6>
                        <p class="card-text">Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <div class="spacer1-backg">
        <div class="header-overlay">
            <div class="center-div">
                <div class="mr-dafoe-regular">
                    <p class="smaller-hw">Let the</p>
                    <p>Adventure</p>
                    <p class="smaller-hw">Begin</p>
                </div>
                <div class="text-center text-white spacer-margin">
                    <p>
                        MARCH 19, 2017
                    </p>
                </div>
            </div> 
        </div>
    </div>

    <section id="wedding-section">
        <div class="container mb-5">
            <div class="main-text text-center mx-5">
                <h4 class="text-center text-uppercase mb-4">Our wedding</h4>
                <p>
                    At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio.
                </p>
            </div>
            <div class="card-group mt-5">
              
                    <div class="card border-0 mx-2">
                        <img class="card-img-top" src="/img/wedding-1.jpeg" alt="Card image cap">
                        <div class="card-body px-0 text-center mt-2">
                            <h6 class="card-title text-uppercase">reception</h6>
                            <p class="card-text p-2">Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus.</p>
                        </div>
                    </div>
                
                    <div class="card border-0 mx-2">
                        <img class="card-img-top" src="/img/wedding-2.jpeg" alt="Card image cap">
                        <div class="card-body px-0 text-center mt-2">
                            <h6 class="card-title text-uppercase">ceremony</h6>
                            <p class="card-text p-2">Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates.</p>
                        </div>
                    </div>
           
                    <div class="card border-0 mx-2">
                        <img class="card-img-top" src="/img/wedding-3.jpeg" alt="Card image cap">
                        <div class="card-body px-0 text-center mt-2">
                            <h6 class="card-title text-uppercase">party</h6>
                            <p class="card-text p-2">Morbi ut euismod quam. Integer pharetra libero ut auctor porttitor. Integer lacinia pretium elit. Maecenas euismod ultrices semper.</p>
                        </div>
                    </div>
               
            </div>
        </div>
    </section>

    <div class="spacer2-backg mb-5">
        <div class="header-overlay">
        </div>
    </div>

    <section id="footer-section">
        <div class="container">
            <div class="main-text text-center">
                <h4 class="text-center text-uppercase mb-3">are you attending?</h4>
                <p>
                    Aliquam posuere luctus nibh, nec varius nisl mattis a. Nam non rutrum nulla. Integer nec fermentum tellus. Donec non volutpat odio. Aliquam id fringilla erat, id vehicula elit. Ut congue enim lectus, sit amet interdum tellus feugiat et. Sed pharetra odio in arcu viverra, non mattis massa tincidunt. Duis a justo enim.
                </p>
            </div>
            <div class="d-flex justify-content-center mt-3">
                <div class="kocka">
                   <h5>0</h5> 
                   <p>Days</p>
                </div>
                <div class="kocka">
                    <h5>0</h5> 
                    <p>Hours</p>
                </div>
                <div class="kocka">
                    <h5>0</h5> 
                    <p>Minutes</p>
                </div>
                <div class="kocka">
                    <h5>0</h5> 
                    <p>Seconds</p>
                </div>  
            </div>
            <div class="text-center mt-3 mb-5">
                <button class="btn btn-danger" @click="rsvp">RSVP</button>
            </div>
        </div>

        <div class="footer-backg">          
                <div class="header-overlay">
                    <div class="center-div">
                        <div class="mr-dafoe-regular">
                            <p>Thank</p>
                            <p>You</p>
                        </div>
                        <div class="text-center text-white spacer-margin">
                            <p>
                                ALBERT & EMILY
                            </p>
                        </div>
                    </div> 
                </div>
        </div>
    </section>
  </main>
</template>
