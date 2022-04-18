<template>
  <div class="profile">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="d-flex align-items-center">
                    <div class="flex-shrink-0">
                        <img src="../assets/img/my-pic.jpeg" alt="image" class="user-pic mr-3">
                    </div>
                    <div class="flex-grow-1 ms-3">
                        <h5>Arta Tri Pamuda</h5>
                        <p>This is some content from a media component. You can replace this with any content and adjust it as needed.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'Profile',
  components: {
  }
}
</script>

<style scoped>
.user-pic {
    height: 80px;
    widows: 80px;
    border-radius: 200%;
}
</style>