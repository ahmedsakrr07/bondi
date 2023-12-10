<template>
      <div class="CV">
      <div class="text-center">
        <h1 class="text-uppercase mt-2 mb-2 text-black"> Start To Download My CV</h1>
        <button type="button" class="btn btn-dark mt-3 mb-3">Download CV</button>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
  .CV {
    background-color: #f6fdff;
    padding-top: 30px;
    padding-bottom: 34px;
    margin-top: 30px;
    margin-bottom: 30px;
  }
  .CV h1 {
    font-size: 35px;
  }

  @media screen and (max-width: 768px) {
    .CV h1 {
    font-size: 28px;
  }

}
</style>