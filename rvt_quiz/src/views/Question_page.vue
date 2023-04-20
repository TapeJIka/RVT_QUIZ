<template>
  <nav class="navbar bg-light">
    <div class="container-fluid">
      <p class="h1">Gudrais grāmatvedis</p>
    </div>
  </nav>

  <div class="d-flex justify-content-center align-items-center" style="width: 100%; margin-top: 10%;">
    <div class="d-flex flex-wrap justify-content-center align-items-center" style="width: 80%;">
      <Question
      />
    </div>
  </div>
</template>
<script>
import Question from "../components/Question.vue";

export default {
  name: "rvt_quiz",

  components: {
    Question,
  },
};

</script>
<style>
.navbar{
  padding: 0px;
}

.navbar > div{
  text-align: center;
  vertical-align: center;
}
.h1{
  color: #0D6EFD;
  font-family: 'Raleway', sans-serif;
  font-weight: bolder;
  line-height: 60px;
  font-size: 35px;
  letter-spacing: 1px;
  padding-left: 6%;
}

.d-flex{
  gap: 20px;
}

</style>