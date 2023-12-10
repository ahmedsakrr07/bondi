<template>
  <div class="skils">
    <b-container>
        <div class="text-center">
            <h1 class="text-uppercase mt-5 mb-5" style="font-size: 32px">
              My Skills
            </h1>
          </div>
          <b-row>
            <b-col md="3">
              <div class="box">
                <img style="width: 57%" src="../assets/html.png" alt="" />
              </div>
            </b-col>
            <b-col md="3">
              <div class="box">
                <img style="width: 57%" src="../assets/css.png" alt="" />
              </div>
            </b-col>
            <b-col md="3">
              <div class="box">
                <img style="width: 57%" src="../assets/java.png" alt="" />
              </div>
            </b-col>
            <b-col md="3">
              <div class="box">
                <img style="width: 57%" src="../assets/bootstrap.png" alt="" />
              </div>
            </b-col>
          </b-row>

    </b-container>
  </div>
</template>

<script>
export default {
  name: "Skils",
};
</script>

<style>
.box {
	
    box-shadow: 0 12px 20px 0 rgb(0 0 0 / 13%), 0 2px 4px 0 rgb(0 0 0 / 12%);
    padding: 30px;
    margin: 20px 0;
    background-color: #f9f9f9;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 20px;
    padding: 57px;

}
</style>
