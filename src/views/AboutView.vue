<template>
  <div class="body">
    <div class="head">
      <h1>わたしについて</h1>
    </div>
    <div class="profile">
      <div class="leftPro">
        <ul>
          <li>Name : chisato takahashi</li>
          <li>Age : 22</li>
          <li>Born : 1999.8.18</li>
          <li>Blood type : A</li>
          <li>Height : 175.6cm</li>
          <li>Hometown : chiba(kamagaya)</li>
        </ul>
      </div>
      <div class="rightPro">
        <img src="@/assets/chisamikan.jpg" alt="" class="photo" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.head {
  display: flex;
  align-items: center;
  justify-content: center;
  border: 6px solid #000;
  height: 100px;
  margin: 0px 100px;
  padding: 40px;
}
.head h1 {
  font-size: 40px;
  letter-spacing: 30px;
}
.profile {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 120px;
}
.leftPro {
  margin-right: 170px;
}

.leftPro ul {
  list-style: none;
  letter-spacing: 5px;
  line-height: 55px;
}
.photo {
  height: 500px;
}
</style>
