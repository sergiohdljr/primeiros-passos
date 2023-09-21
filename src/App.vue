<template>
  <div id="app">
    <div>
      <h1>
        Hello World
        <p>.</p>
      </h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,900&display=swap");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "DM Sans", sans-serif;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
  width: 100dvw;
  background-color: #401580;
  display: flex;
  justify-content: center;
  align-items: center;
}

#app > div {
  width: 70%;
  height: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 16px;
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(11.7px);
  -webkit-backdrop-filter: blur(11.7px);
  border: 1px solid rgba(255, 255, 255, 0.01);
}

#app > div > h1 {
  font-size: 4.5rem;
  color: white;
  letter-spacing: 1rem;
  display: flex;
  transition: all 2ms ease-in-out;
}

#app > div > h1 > p {
  color: #efa500;
}
</style>
