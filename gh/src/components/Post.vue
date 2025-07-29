<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-10 bg-dark py-4 rounded">
        <div class="card mb-4 bg-secondary text-white mx-auto" style="max-width: 700px;">
          <!-- Carousel -->
          <div id="postCarousel" class="carousel slide">
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="https://i.pinimg.com/736x/ae/bb/f0/aebbf08f3e8a3f9250d00a54b525ea74.jpg" class="d-block w-100" alt="Snoopy 1" />
              </div>
              <div class="carousel-item">
                <img src="https://i.pinimg.com/736x/13/04/15/13041568f37e71b275fba3e57b23a9c3.jpg" class="d-block w-100" alt="Snoopy 2" />
              </div>
              <div class="carousel-item">
                <img src="https://i.pinimg.com/1200x/9a/c1/03/9ac103b2b06555f8e18941384c480d4a.jpg" class="d-block w-100" alt="Snoopy 3" />
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#postCarousel" data-bs-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#postCarousel" data-bs-slide="next">
              <span class="carousel-control-next-icon"></span>
            </button>
          </div>

          <!-- Post Content -->
          <div class="card-body">
            <div class="d-flex align-items-center mb-3">
              <img src="https://i.pinimg.com/736x/07/a7/0f/07a70f2455b9769f1f893ace23b213f4.jpg" class="rounded-circle me-3" width="50" height="50" alt="avt user" />
              <div>
                <h6 class="fw-bold text-white mb-0">Tannn</h6>
                <small class="text-muted">11m</small>
              </div>
            </div>

            <h4 class="fw-bold mb-3">Adorable Snoopy Moment</h4>
            <p class="text-white">
              Snoopy is not your average beagle. He is a book lover and a book writer...
            </p>

            <!-- Action Buttons -->
            <div class="d-flex gap-4 mt-3">
              <button class="btn"><i class="fa-regular fa-heart"></i></button>
              <button class="btn" data-bs-toggle="collapse" data-bs-target="#comment"><i class="fa-solid fa-comment-dots"></i></button>
              <button class="btn"><i class="fa-regular fa-share-from-square"></i></button>
            </div>

            <!-- Comments Section -->
            <div id="comment" class="collapse mt-4">
              <h5 class="mb-3">Comments</h5>

              <!-- Render comments with v-for -->
              
              <div v-for="(comment,index) in comments" :key="index" class="mb-3">
                <div class="d-flex mb-2">
                    <img :src="comment.avatar" class="rounded-circle me-2" width="40" height="40"/>
                    <div>
                        <h6 class="mb-0">{{comment.name}}   </h6>
                            <small class="text-white">{{comment.text}}</small>
                     
                    </div>
                </div>
              </div>

              <!-- Add new comment -->
              <form @submit.prevent="addComment">
                <div class="mb-3">
                  <textarea v-model="newComment" class="form-control border-secondary" rows="2" placeholder="write comment"></textarea>
                </div>
                <div class="d-grid">
                  <button type="submit" class="btn btn-dark">Post</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      comments: [
        {
          name: 'nhen',
          text: 'its cute',
          avatar: 'https://i.pinimg.com/736x/76/5a/67/765a67c0f0b473adf44a72fdfc32b610.jpg'
        }
      ],
      newComment:''
    };
  },
  methods: {
    addComment() {
      if (this.newComment.trim() !== '') {
        this.comments.push({
          name: 'carla',
          text: this.newComment,
          avatar: 'https://i.pinimg.com/1200x/0b/00/9f/0b009f581cfd02d093d8f7850df93582.jpg' // default avatar
        });
        this.newComment = '';
      }
    }
  }
};
</script>
