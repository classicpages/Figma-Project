<template>
  <section class="con pt-5">
    <div class="lorem">
      <div class="text-left font-medium text-6xl leading-7 mt-36"></div>
      <p class="text-4xl h-10 mt-96">A Price To Suit Everyone</p>

      <div class="mt-10 dolor text-blue-700 leading-7">
        <p>
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula <br />
          eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient <br />
          montes, nascetur ridiculus .
        </p>
      </div>
      <div class="num">$40</div>
      <p class="ui">UI Design Kit</p>
      <p class="see">See, One price. Simple.</p>

      <button class="btn mb-10 mt-5">Purchase Now</button>
    </div>
  </section>
  <section class="Mon">
    <div class="icon flex">
      <p class="ml-5 pt-5">&#169;2023 Yourcompany</p>
      <p class="land pt-5"><img src="/src/assets/Landie.png" /></p>
      <button class="now">Purchase Now</button>
    </div>
    <div class="icons flex">
      <p class="mt-5 ml-3 mb-5">Home</p>
      <p class="ml-36 mt-5">About</p>
      <p class="ml-36 mt-5">Contact</p>
      <p class="ml-96 mt-5"><img src="/public/Instagram Copy 4.png" /></p>
      <p class="ml-16 mt-5"><img src="/public/Instagram Copy 3.png" /></p>
      <p class="ml-16 mt-5"><img src="/public/Instagram Copy 2.png" /></p>
      <p class="ml-16 mt-5"><img src="/public/Instagram.png" /></p>
      <p class="ml-16 mt-5"><img src="/public/Shape.png" /></p>
    </div>
  </section>
</template>

<style scoped>
.con {
  background-image: url(/src/assets/Rectangle.png);
  text-align: center;
}

.now {
  border: 1px solid rgb(11, 11, 70);
  background-color: rgb(11, 11, 70);
  color: #fff;
  padding-left: 40px;
  padding-right: 40px;
  padding-top: 3px;
  padding-bottom: 3px;
  margin-left: 400px;
  margin-top: 20px;
  margin-bottom: 15px;
}

.land {
  padding-left: 400px;
}

.icons {
  background-color: #e7ecff;
  border: 2px solid #cdd1d4;
}

.icon {
  background-color: #e7ecff;
}

.see {
  height: 24px;
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  margin-top: 30px;
}

.last {
  background-color: #e7ecff;
  margin-bottom: 40px;
}

.btn {
  border: 1px solid rgb(11, 11, 70);
  background-color: rgb(11, 11, 70);
  color: #fff;
  padding-left: 40px;
  padding-right: 40px;
  padding-top: 3px;
  padding-bottom: 3px;
}

.ui {
  height: 26px;
  font-weight: 400;
  font-size: 16px;
  line-height: 26px;
  margin-top: 10px;
}

.dolor {
  height: 78px;
  top: 64px;
  font-weight: 400;
  size: 16px;
  line-height: 26px;
}

.num {
  height: 66px;
  top: 4022px;
  left: 540px;
  font-weight: 500;
  font-size: 50px;
  letter-spacing: 1px;
  margin-top: 20px;
}
</style>
