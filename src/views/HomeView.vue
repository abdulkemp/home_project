<template>
  <div class="children">
    <div class="logo">
      <img src="../assets/Screenshot_20230227_161029.png" alt="" srcset="">
    </div>
    <div class="signing animate__animated animate__slideInRight">
      <div class="circle">
        <form action="">
          <h1>WELCOME BACK!</h1>
          <div class="insert">
            <div>
              <h4>Email</h4>
              <input type="text" class="input">
            </div>
          </div>
          <div class="insert">
            <div>
              <h4>Password</h4>
              <input type="password" class="input">
            </div>
          </div>
          <h4>Forgot Password?</h4>
          <input type="submit" value="login" class="btn">
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.children {
  /* background-color: green; */
  width: 100vw;
  height: 100vh;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 8rem;
  padding: 0 20rem;
  /* margin: 20rem; */

}

.children img {
  width: 300px;
}

.circle{
  border: 1px solid black;
  width: 20rem;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 20rem;
  border-radius: 20rem;
}

.logo {
  display: flex;
  justify-content: center;
  align-items: center;
}

.signing {
  display: flex;
  align-items: center;
  justify-content: center;
  /* background-color: rgba(105, 104, 104, 0.144); */
}

/* form {
  width: 300rem;
} */

@media screen and (max-width: 1050px) {
  .children {
    grid-gap: 5rem;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}

@media screen and (max-width: 1000px) {
  form {
    width: 9rem;
    align-items: center;
  }

  .children img {
    width: 20rem;
  }
}

@media screen and (max-width: 900px) {
  .logo {
    display: none;
  }

  .children {
    grid-template-columns: 1fr;
  }

  .circle {
    display: flex;
    justify-content: center;
    align-items: center;
  }
}

</style>