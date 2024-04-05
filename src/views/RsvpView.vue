<!-- <style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style> -->
<script>
  export default{
    data(){
      return{
        name:'',
        email:'',
        selected:'',
        message:'',
        name_error: false,
        email_error: false,
        selected_error: false,
        // message_error: false
      }
    },
    methods:{
      validateInputs(){
        if (this.name == '') {
          this.name_error = true;
        } else {
          this.name_error = false;
        }
        if (this.email == '') {
          this.email_error = true;
        } else {
          this.email_error = false;
        }
        if (this.selected == '') {
          this.selected_error = true;
        } else {
          this.selected_error = false;
        }
        // if (this.message == '') {
        //   this.message_error = true;
        // } else {
        //   this.message_error = false;
        // }
      },
      alertolo(){
        this.validateInputs();
        if (! this.isAllFieldValid){
          return;
        }
        alert("Name: " + this.name + "\n" + "Email: " + this.email + "\n" + "You selected: " + this.selected + "\n" + "Message: " + this.message )
      }
    },
    computed:{
      isAllFieldValid(){
        if (this.name_error) {
          return false;
        }
        if (this.email_error){
          return false;
        }
        if (this.selected_error){
          return false;
        }
        // if (this.message_error){
        //   return false;
        // }
        return true;
      }
    }
  }
</script>

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
                    <h6>RSVP</h6>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque et metus in quam fringilla scelerisque at sit amet nunc. </p>                 
                </div>
                <div class="spacer-margin">
                    <p>
                        A+E
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
              <!-- <input type="text" class="form-control" id="name" name="name"> -->
              <input v-model="name" @input="validateInputs" class="form-control">
              <p v-if="name_error" class="red">Name is required</p>
              <label for="email" class="text-uppercase mt-3 mb-1">*email</label>
              <!-- <input type="email" class="form-control" id="email" name="email"> -->
              <input v-model="email" @input="validateInputs" class="form-control">
              <p v-if="email_error" class="red">Email is required</p>
              
              <div class="form-group option-box">
                <label for="option" class="text-uppercase mt-3 mb-1">*I will attend to</label>
                <select v-model="selected" @input="validateInputs" multiple class="form-control" id="option" name="option">
                  <option value="Wedding Day">Wedding Day</option>
                  <option value="Ceremony Day">Ceremony Day</option>
                  <option value="The Party">The Party</option>
                </select>
              </div>
              <p v-if="selected_error" class="red">I will attend to field seleciton is required</p>

            </div>
            <div class="col">
              <div class="form-group">
                <label for="message" class="text-uppercase mt-3 mb-1">Leave message</label>
                <textarea v-model="message" class="form-control" id="message" rows="10"></textarea>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col text-center">
              <button @click="alertolo" class="btn btn-danger mb-2 tex-center text-uppercase">Submit</button>
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




