<template>
  <div>
    <img
      class="image"
      src="https://i.pinimg.com/originals/13/9b/c0/139bc04adcfd5bec7235370d7ff43f40.jpg"
      alt=""
    />
    <h1 class="text">Hello Boxes</h1>
    <template v-for="n in 4">
      <div class="boxes" v-bind:key="n">
        <div class="box">Box {{n}}</div>
        <div class="box">Box {{n}}</div>
      </div>
    </template>
  </div>
</template>

<style scoped>
.image {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
}
.text {
  color: #ffffff;
}
.box {
  width: 500px;
  height: 300px;
  background-color: rgba(255, 255, 255, 0.5);
  margin: 15px 30px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 24px;
}
.boxes {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 15px 30px;
}
</style>
