<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-6">
        <div class="card bg-dark text-white p-4">
          <h4 class="text-center mb-4">Profile</h4>

          <div class="text-center mb-4">
            <img
              src="https://i.pinimg.com/736x/b5/90/67/b590671943a3cf061a9354cbcc4cff00.jpg"
              alt="Avatar"
              class="rounded-circle"
              width="200"
              height="200"
            />
          </div>

       
          <div class="mb-3">
            <label class="form-label">User name</label>
            <input type="text" class="form-control" value="tnhen" />
          </div>

          <div class="mb-3">
            <label class="form-label">Email</label>
            <input type="email" class="form-control" value="tnhan@gmail.com" />
          </div>

          <div class="mb-3 position-relative">
            <label class="form-label">Password</label>
            <input type="password" class="form-control" value="8888888" />
          </div>


          <div class="d-grid mt-4">
            <button class="btn btn-light" data-bs-toggle="modal" data-bs-target="#editModal">
              Edit Profile
            </button>
          </div>
        </div>
      </div>
    </div>

    <!-- modal-->
    <div class="modal fade" id="editModal">
      <div class="modal-dialog">
        <div class="modal-content bg-dark text-white">
          <div class="modal-header ">
            <h5 class="modal-title ms-auto me-auto" >Change profile</h5>
          </div>
          <div class="modal-body">
            <form>
              <div class="mb-3">
                <label class="form-label">User name</label>
                <input type="text" class="form-control" value="tnhen" />
              </div>
              <div class="mb-3">
                <label class="form-label">Email</label>
                <input type="email" class="form-control" value="tnhan@gmail.com" />
              </div>
              <div class="mb-3 position-relative">
                  <label for="password" class="form-label">Password</label>
            <input
              type="password"
              class="form-control"
              id="password"
              value="88888888"
              required
            />
               
              </div>
              <div class="mb-3">
               
                    <label class="form-label">change img</label>
                    <input class="form-control" type="file" multiple>
              </div>
            </form>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn text-white" data-bs-dismiss="modal">Cancel</button>
            <button type="button" class="btn  text-white">Done</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
