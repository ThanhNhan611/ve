<template>
  <div class="container mt-5" >

    <div class="row">
        <div class="col-6">
                <h3 class="mb-4 text-center">Sign up</h3>
            <form>
    
      <div class="mb-3">
        <label for="username" class="form-label">Username</label>
        <input type="text" class="form-control" id="username" placeholder="your name">
      </div>


      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" placeholder="your email">
      </div>

   
      <div class="mb-3">
        <label for="password" class="form-label">Password</label>
        <input type="password" class="form-control" id="password" placeholder="your password" required>
      </div>

       <div class="d-grid">
        <button type="submit" class="btn btn-secondary">Register</button>
       </div>
           
          <div class="d-flex align-items-center mt-3">
            <span class="me-2 text-muted">If you have an account, please</span>
            <a class=" text-dark" href="Login.vue">login</a>
          </div>
      
    </form>
        </div>
        <div class="col-6">
        <img src="https://i.pinimg.com/736x/4e/aa/60/4eaa60f99e873d2b824548b9f49b3d65.jpg" alt="Illustration" style="width: 100%; max-width: 600px;"/>
        </div>
    </div>
    
  </div>
</template>
