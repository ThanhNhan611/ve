<template>
  <div class="container-fluid mt-5">
    <div class="row">

      <div class="col-lg-6 d-flex justify-content-center align-items-center">
        <img src="https://i.pinimg.com/736x/4e/aa/60/4eaa60f99e873d2b824548b9f49b3d65.jpg" alt="Illustration" style="width: 100%; max-width: 600px;"/>
      </div>


      <div class="col-lg-6 px-5">
        <h3 class="mb-3 text-center ">Login</h3>
        <p class="text-muted mb-4">Please login to continue</p>

        <form>
          <div class="mb-3">
            <label for="email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email"
            />
          </div>

          <div class="mb-3">
            <label for="password" class="form-label">Password</label>
            <input
              type="password"
              class="form-control"
              id="password"
              placeholder="Enter your password"
              required
            />
          </div>

          <div class="d-grid mb-3">
            <button type="submit" class="btn btn-secondary">Login</button>
          </div>

          <div class="d-flex align-items-center mt-3">
            <span class="me-2 text-muted">If you don't have an account, please</span>
            <a class="text-dark" href="Register.vue">sign up</a>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
