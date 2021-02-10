<template>
  <div class="main">
    <img class="iphone" src="https://cdn.iphoneincanada.ca/wp-content/uploads/2016/08/tumblr_inline_obae6aJ6lz1svf3j7_540.jpg" alt="">
    <div class="move">
    <div class="hello">
      
      <img
        src="https://stackspancakebar.com.au/wp-content/uploads/2018/05/instagram-logo.png"
        alt="InstaClone"
      />
      <form class="login-form" action="">
        <input type="text" placeholder="Phone number, user name, or email" />
        <input type="text" placeholder="Password" />
        <button class="btn btn-primary">Log In</button>
        <h4 class="or">OR</h4>
        <h3><a href="https://www.facebook.com/">Log in with Facebook </a></h3>
        <p><a class="forgot-password" href="https://www.instagram.com/accounts/password/reset/"> Forgot password? </a></p>
      </form>
    </div>
    <div class="option-signup">Don't have an account? <a class="sign-up" href="">Sign up </a> </div>
  </div>
</div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.main{
  position: absolute;
  top: 0;
  background-color: #fafafa;
  width: 100%;
  height: 100vh;
}
.move {
  position: absolute;
  top: 50px;
  right: 20%;
  
}

.hello {
  position: relative;
  height: 400px;
  width: 350px;
  padding: 10px;
  background-color: rgb(255, 255, 255);
  border: 1px solid rgb(211, 204, 204);
  text-align: center;
  align-items: center;
}
.hello img {
  position: absolute;
  top: 8%;
  width: 60%;
  height: 50px;
  left: 18%;
}
.login-form {
  margin-top: 100px;
}

.hello input {
  width: 70%;
  height: 30px;
  padding-left: 10px;
  background-color: #fafafa;
  border: 1px solid rgb(211, 204, 204);;
  border-radius: 3%;
  margin: 4px auto;
  display: block;
  align-items: center;
}

.btn-primary {
  width: 74%;
  height: 35px;
  margin: 18px auto;
  padding: 4px 8px 8px 8px;
  display: block;
  align-items: center;
  border: 1px solid transparent;
  border-radius: 3%;
  background-color: #0095f6;
  color: white;
  font-weight: bold;
}

.option-signup {
  width: 350px;
  padding: 20px 10px 20px 10px;
  margin-top: 12px;
  background-color: white;
  border: 1px solid rgb(211, 204, 204);
  text-align: center;
  align-items: center;
}
.or {
  padding-top: 8px;
  line-height: 1px;
  opacity: 0.5;
}
.hello a,
h3 {
  color: #2a4f9e;
  font-size: 16px;
  padding-top: 26px;
  text-decoration: none;
}
.forgot-password{
  font-size: 10px;
  }
  .iphone{

    width: 370px;
    height: 600px;
    float: left;
    align-content: center;
    padding-left: 350px;
    padding-top: 22px;
  }

  .sign-up{
    text-decoration: none;
    color: #2a4f9e;
  }
</style>
