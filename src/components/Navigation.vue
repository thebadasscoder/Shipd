<template>
  <div class="navigation">
    <img src="../assets/convoy.png" alt="convoy" id="navigation-logo">
    <button type="button" class="navigation-button-one">Offers</button>
    <button type="button" class="navigation-button-two">My Jobs</button>
    <hr>
  </div>
</template>

<script>
export default {
  name: "Navigation"
};
</script>

<style>
.navigation {
  background-color: #ffffff;
  width: auto;
  height: 56px;
  padding-top: 10px;
  padding-left: 50px;
  display: flex;
  align-items: center;
}

#navigation-logo {
  width: auto;
  height: 30px;
}

.navigation-button-one {
  background-color: transparent;
  background-repeat: no-repeat;
  border: none;
  cursor: pointer;
  outline: none;
  overflow: hidden;
  margin: 0;
  margin-left: 50px;
}

.navigation-button-two {
  background-color: transparent;
  background-repeat: no-repeat;
  border: none;
  cursor: pointer;
  outline: none;
  overflow: hidden;
  margin: 50px;
  margin-left: 50px;
}

.navigation-button-two:hover ~ hr {
  margin-left: auto;
}

hr {
  height: 4px;
  width: 70px;
  margin-left: -215px;
  margin-top: 40px;
  background: #F65335;
  border: none;
  transition: 2s ease-in-out;
}
</style>


