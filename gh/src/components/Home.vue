<template>

           
  <div class="container mt-4">
  <div class="row">

    <!-- left-->
    <div class="col-md-9">
      <h4 class="fw-bold mb-4 text-secondary text-center">All</h4>
      <div class="row g-4">
        <!-- post1 -->
        <div class="col-md-4">
          <div class="card h-80" style="width:260px;">
           <img src="https://i.pinimg.com/736x/fb/01/a2/fb01a22101a8d715ce62f0d4e296f781.jpg" class="card-img-top" style="height: 150px; object-fit: cover;">
            <div class="card-body">
              <h6 class="card-title fw-bold">Wave to earth</h6>
              <p class="card-text small">A touching story of a boy and his sister from the future, with Snoopy by their side.</p>
                <div class="d-flex gap-2">
                  <button class="btn"><i class="fa-regular fa-heart"></i></button>
                  <button class="btn"><i class="fa-solid fa-comment-dots"></i></button>
                  <button class="btn"><i class="fa-regular fa-share-from-square"></i></button>
               </div>
            </div>
          </div>
        </div>

        <!-- post2 -->
        <div class="col-4">
          <div class="card h-80 " style="width:260px;">
            <img src="https://i.pinimg.com/1200x/64/18/55/641855f2c2689f2ea7a5a9c4092bd03e.jpg" class="card-img-top" style="height: 150px; object-fit: cover;">
            <div class="card-body">
              <h6 class="card-title fw-bold">How to train your dragon</h6>
              <p class="card-text small">Toothless is more Hiccups best friend than his pet. He is extremely protective of his Viking soul mate.</p>
              <div class="d-flex gap-4 mt-3">
                  <button class="btn"><i class="fa-regular fa-heart"></i></button>
                  <button class="btn"><i class="fa-solid fa-comment-dots"></i></button>
                  <button class="btn"><i class="fa-regular fa-share-from-square"></i></button>
                </div>
            </div>
          </div>
        </div>

        <!--post3 -->
        <div class="col-md-4">
          <div class="card h-80" style="width:260px;">
            <img src="https://i.pinimg.com/1200x/9c/b4/aa/9cb4aa47955097d20f8bb70168d9020d.jpg" class="card-img-top" style="height: 150px; object-fit: cover;">
            <div class="card-body">
              <h6 class="card-title fw-bold">minions</h6>
              <p class="card-text small">The hilarious yellow henchmen search for the perfect villain to serve in their chaotic adventure</p>
              <div class="d-flex gap-2">
                  <button class="btn"><i class="fa-regular fa-heart"></i></button>
                  <button class="btn"><i class="fa-solid fa-comment-dots"></i></button>
                  <button class="btn"><i class="fa-regular fa-share-from-square"></i></button>
                </div>
            </div>
          </div>
        </div>

        <!--post4 -->
        <div class="col-md-4">
          <div class="card h-80 " style="width:260px;">
            <img src="https://i.pinimg.com/736x/7a/88/03/7a8803ede57f415b03fdedb6bd4f8f52.jpg" class="card-img-top" style="height: 150px; object-fit: cover;">
            <div class="card-body">
              <h6 class="card-title fw-bold">Lover</h6>
              <p class="card-text small">A dreamy pop album that celebrates love</p>
              <div class="d-flex gap-2">
                  <button class="btn"><i class="fa-regular fa-heart"></i></button>
                  <button class="btn"><i class="fa-solid fa-comment-dots"></i></button>
                  <button class="btn"><i class="fa-regular fa-share-from-square"></i></button>
                </div>
            </div>
          </div>
        </div>
        <!--post6-->
           <div class="col-md-4">
          <div class="card h-80 " style="width:260px;">
            <img src="https://i.pinimg.com/1200x/54/72/b7/5472b71ac999f44bc7995de3b6f10dc3.jpg" class="card-img-top" style="height: 150px; object-fit: cover;">
            <div class="card-body">
              <h6 class="card-title fw-bold">Conan</h6>
              <p class="card-text small">A great mystery expert at only seventeen.</p>
              <div class="d-flex gap-2">
                  <button class="btn"><i class="fa-regular fa-heart"></i></button>
                  <button class="btn"><i class="fa-solid fa-comment-dots"></i></button>
                  <button class="btn"><i class="fa-regular fa-share-from-square"></i></button>
                </div>
            </div>
          </div>
        </div>
          <!--post7-->
           <div class="col-md-4">
          <div class="card h-80 " style="width:260px;">
            <img src="https://i.pinimg.com/736x/c0/4c/63/c04c6350502864fd302560a56bbe5abb.jpg" class="card-img-top" style="height: 150px; object-fit: cover;">
            <div class="card-body">
              <h6 class="card-title fw-bold">Blue</h6>
              <p class="card-text small">The song 'Blue' by Yung Kai portrays a deep longing</p>
              <div class="d-flex gap-2">
                  <button class="btn"><i class="fa-regular fa-heart"></i></button>
                  <button class="btn"><i class="fa-solid fa-comment-dots"></i></button>
                  <button class="btn"><i class="fa-regular fa-share-from-square"></i></button>
                </div>
            </div>
          </div>
        </div>

      </div>
    </div>
    


       <!-- right -->
    <div class="col-3">

 <div class="d-flex align-items-center">
              <div class="me-auto ms-auto mb-3">
                <button type="button" class="btn btn-secondary" data-bs-toggle="modal" data-bs-target="#newModal">create new post</button>
              </div>
            </div>
<div class="modal fade" id="newModal">
  <div class="modal-dialog">
    <div class="modal-content bg-dark text-white">
      <div class="modal-header">
        <button type="button" class="btn text-white" data-bs-dismiss="modal">Cancel</button>
        <h5 class="modal-title mx-auto">New post</h5>
        <div style="width: 70px;"></div>
      </div>
      <div class="modal-body">
        <!-- title-->
        <label class="form-label">Title</label>
        <input type="text" class="form-control mb-3" placeholder="write post title">

        <!-- content -->
        <label class="form-label">Content</label>
        <textarea class="form-control mb-3" rows="4" placeholder="write somthing"></textarea>

        <!-- img -->
        <label class="form-label">Files or images</label>
        <input class="form-control" type="file">
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-light">Post</button>
      </div>
    </div>
  </div>
</div>

           
      <!-- posts-->
      <div class="card ">
        
        <div class="card-header bg-secondary text-white fw-bold text-center">
          some posts
        </div>
        <ul class="list-group list-group-flush">
          <li class="list-group-item d-flex">
            <img src="https://i.pinimg.com/736x/41/ca/bd/41cabd739868c384a2533030698d707b.jpg" class="rounded-circle me-3" style="width: 40px; height: 40px;  object-fit: cover; ">
            <div>
              <small class="fw-bold">Yoshii</small><br>
              <small class="text-muted">A quirky 3D character...</small>
            </div>
          </li>
          <li class="list-group-item d-flex">
            <img src="https://i.pinimg.com/736x/ae/58/e8/ae58e89eb11fa860723da625eff3ca32.jpg" class="rounded-circle me-3" style="width: 40px; height: 40px;  object-fit: cover;">
            <div>
              <small class="fw-bold">Ponyo</small><br>
              <small class="text-muted">The film tells the story of Ponyo...</small>
            </div>
          </li>
           <li class="list-group-item d-flex">
            <img src="https://i.pinimg.com/736x/87/04/27/8704275a9ad454f408d61d0d26947b19.jpg" class="rounded-circle me-3" style="width: 40px; height: 40px; object-fit: cover;">
            <div>
              <small class="fw-bold">Shin</small><br>
              <small class="text-muted">The story of the film begins with Shinnosuke..</small>
            </div>
          </li>
           <li class="list-group-item d-flex">
            <img src="https://i.pinimg.com/736x/42/53/11/425311cb112c85278e5e54fa97bb8b4e.jpg" class="rounded-circle me-3" style="width: 40px; height: 40px; object-fit: cover;">
            <div>
              <small class="fw-bold">Loopy</small><br>
              <small class=" text-muted">Loopy is a pretty, cute, young female beaver..</small>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>

</template>
