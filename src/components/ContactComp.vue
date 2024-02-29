<template>

    <div class="container col-xl-10 col-xxl-8">
        <div class="row align-items-center g-lg-5 py-5">
          <div class="col-lg-7 text-center text-lg-start" id="vidcontainer">
            <!-- <video src="../assets/VID-20240214-WA0005.mp4" type="video/mp4"
              autoplay
              muted
              loop
              id="videoIsPlayable123"
            >
            </video> -->
            <!-- <h1 class="display-4 fw-bold lh-1 text-body-emphasis mb-3" id="position-234-00">Vertically centered hero sign-up form</h1> -->
          </div>
          <div class="col-md-10 mx-auto col-lg-5">

            <form class="p-4 p-md-5" id="formBody">

              <div class="form-floating mb-3">
                <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                <label for="floatingInput">Email address</label>
              </div>

              <div class="form-floating mb-3">
                <input type="text" class="form-control" id="floatingFirstname" placeholder="firstname">
                <label for="floatingFirstname">First name</label>
              </div>

              <div class="form-floating mb-3">
                <input type="text" class="form-control" id="floatingPassword" placeholder="Password">
                <label for="floatingPassword">Last name</label>
              </div>

              <button class="w-100 btn btn-lg" id="btn" type="submit">Sign up</button>
              <hr class="my-4">
              <small class="text-body-secondary">By clicking Sign up, you agree to the terms of use.</small>
              
            </form>
          </div>
        </div>
      </div>


</template>
<script>
export default {
}
</script>
<style scoped>

#formBody{
    border: 1px solid black;
    border-radius: 20px;
}

 #videoIsPlayable123{
    height: 460px;
    width: 100%;
    box-shadow: 5px 5px 10px 5px rgba(0, 0, 0, 0.2);
} 
    
</style>