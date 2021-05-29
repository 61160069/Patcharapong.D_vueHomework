<template>
  <br />
  <div class="container">
    <div class="jumbotron text-left">
      <h1>Profile</h1>
      <div class="card" style="width: 400px">
        <img
          class="card-img-top"
          src="https://reg.buu.ac.th/registrar/getstudentimage.asp?id=61160069"
          alt="Card image"
        />
        <div class="card-body">
          <h4 class="card-title">Patcharapong Damrongpanitchai</h4>
          <p class="card-text"><b>Nickname :</b> J</p>
          <p class="card-text"><b>Age :</b> 21</p>
          <p class="card-text">
            <b>Skill :</b> Languange -> C++, C, HTML, PHP, CSS, JS, Java,
            python, SQL, Lua
          </p>
          <p class="card-text">
            <b>Soft Skill :</b> Collaboration and teamwork, Self Learning, Time
            management and organization, Emotional intelligence, Owning up to
            errors
          </p>
          <router-link to="Contact" v-slot="{ href, navigate }" custom>
            <button class="btn btn-primary" :href="href" @click="navigate">
              {{ "Contact Me" }}
            </button>
          </router-link>
        </div>
      </div>
      <br />
    </div>
  </div>
</template>

<script>
</script>

<style>
</style>