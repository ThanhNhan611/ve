<template>
  <nav class="navbar navbar-expand-sm p-1 bg-secondary">
    <div class="container d-flex align-items-center">

      <!-- logo -->
      <div class="navbar-brand d-flex ">
        <img
          src="https://i.pinimg.com/736x/83/e0/af/83e0af00e44077e0f9bfe1f4fa5ccbb4.jpg"
          alt="Logo"
          class="rounded-circle"
          style="width: 50px; height: 50px;"
        />
      </div>
      <h5 class="d-flex align-items-center fw-bold text-white ms-2">blog</h5>

      <!-- nav links -->
      <ul class="navbar-nav me-auto ms-auto">
        <li class="nav-item me-4">
          <div class="nav-link text-white">
            <i class="fa-solid fa-house me-1"></i>Home
          </div>
        </li>
        <li class="nav-item me-4">
          <div class="nav-link text-white" >
            <i class="fa-solid fa-pen-to-square me-1"></i>Post
          </div>
        </li>
        <li class="nav-item me-4">
          <div class="nav-link text-white" >
            <i class="fa-solid fa-user me-1"></i>Profile
          </div>
        </li>
      </ul>

      <!-- search -->
      <form class="d-flex me-3" role="search">
        <input class="form-control" type="search" placeholder="search" />
        <button class="btn text-white" type="submit">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </form>

      <!-- login/signup -->
  <ul class="navbar-nav">
     <li class="nav-item me-3">
       <a class="nav-link text-white" href="#"> <i class="fa-solid fa-right-to-bracket me-1"></i>Login </a> </li> <li class="nav-item me-4"> <a class="nav-link text-white" href="#"> <i class="fa-solid fa-user-plus me-1"></i>Signup </a> </li> </ul>

    </div>
  </nav>
</template>
<script>


</script>