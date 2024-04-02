<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<template>
  <div class="body-bg">
    <section id="rsvp-header-section" class="spacer1-backg">
        <div class="header-overlay">
            <nav class="navbar navbar-expand navbar-light">
                <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
                    <ul class="header-nav">
                        <li class="active"><a href="/header-section">HOME</a></li>
                        <li ><a href="/story-section">STORY</a></li>
                        <li ><a href="/wedding-section">WEDDING</a></li>
                        <li ><a href="#">GALLERY</a></li>
                        <li ><a href="#">PAGES</a></li>
                        <li ><a href="/rsvp">RSVP</a></li>
                    </ul>
                </div>
            </nav>

            <div class="center-div text-white text-center">
                <div class="main-text">
                    <h4>RSVP</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque et metus in quam fringilla scelerisque at sit amet nunc. </p>                 
                </div>
                <div class="spacer-margin">
                    <p>
                        A/E
                    </p>
                </div>
            </div> 

        </div>
    </section>


    <section id="center-form">
      <div class="container">
        <!-- <div class="form-group"> -->
          <div class="row">
            <div class="col">
              <label for="name" class="text-uppercase mt-3 mb-1">*Name:</label>
              <input type="text" class="form-control" id="name" name="name">
              <label for="email" class="text-uppercase mt-3 mb-1">*email</label>
              <input type="email" class="form-control" id="email" name="email">
              
              <div class="form-group">
                <label for="option" class="text-uppercase mt-3 mb-1">*I will attend to</label>
                <select multiple class="form-control" id="option" name="option">
                  <option value="1">wedding day</option>
                  <option value="2">ceremony day</option>
                  <option value="3">the party</option>
                </select>
              </div>

            </div>
            <div class="col">
              <div class="form-group">
                <label for="message" class="text-uppercase mt-3 mb-1">Leave message</label>
                <textarea class="form-control" id="message" rows="10"></textarea>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col text-center">
              <button type="submit" class="btn btn-primary mb-2 tex-center text-uppercase">Submit</button>
              <!-- <input type="submit" value="Submit"> -->
            </div>
          </div>
        <!-- </div> -->
      </div>


    </section>


    <section id="rsvp-footer">
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
  </div>
</template>




