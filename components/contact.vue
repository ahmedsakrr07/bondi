<template>
      <div class="contact">
      <div class="container">
        <div class="text-center">
          <h1 class="text-uppercase mt-5 mb-5" style="font-size: 32px">
            Contact Me
          </h1>
        </div>
        <div class="row">
          <div class="col-md-6">
            <form action="">
              <input
                class="form-control mb-3"
                type="text"
                placeholder="Name"
                name=""
                id=""
              />
              <input
                class="form-control mb-3"
                type="email"
                placeholder="Email"
                name=""
                id=""
              />
              <input
                class="form-control mb-3"
                type="text"
                placeholder="Subject"
                name=""
                id=""
              />
              <textarea
                class="form-control mb-3"
                name=""
                id=""
                cols="30"
                rows="10"
                placeholder="Message"
              ></textarea>
              <input
                class="btn-2 btn-dark"
                type="submit"
                value="Send Message"
              />
            </form>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.contact {
	background-color: #fbfbfb;
	padding-top: 30px;
	padding-bottom: 30px;
	margin-top: 30px;
	margin-bottom: 30px;
}
.btn-2{
    margin-left: 60%;
    color: white;
    background-color: black;
    border: none;
    padding: 7px;
    border-radius: 7px;
}
.form-control {
    margin-left: 60%;
}

@media screen and (max-width: 768px) {
	.form-control {
		margin-left: 1%;
	}
	.btn-2{
		margin-left: 1% ;
	
	}
	.title{
		font-size: 30px;
	}
}
</style>