<template>
  <div>
    <Navbar />
    <section class="home">
      <div class="image">
        <img src="https://media.discordapp.net/attachments/887300703314387035/1018101275918860338/106097658_n-modified.png?width=576&height=576" alt="" />
      </div>
      <div class="content">
        <h3>hi, i am {{name}}</h3>
        <span>Belive the Impossible is Possible.</span>
        <p>
          {{motto}}
        </p>
        <p>{{content}}</p>
        <router-link to="/about" class="btn">
          about me <i class="fas fa-user"></i>
        </router-link>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
  components: { Navbar },
  data() {
    return {
      name: "Nikorn Nuanaun",
      motto:"GGEZ",
      content:"GGWP",
    };
  },
};
</script>

<style>
</style>