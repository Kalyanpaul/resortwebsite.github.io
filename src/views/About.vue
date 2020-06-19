<template>
  <div id="app">
    <div class="container con-b">
      <article class="media">
        <div class="media-content">
          <div class="content has-text-white-ter is-italic has-background-dark">
            <p>
              <strong>Resort Name</strong>
              <br>
              <a class="title"> <u>ABOUT US</u></a> <br>
              <br>
                Our team, renowned for their warmth and heartfelt hospitality, <br>
                look forward to welcoming you to Resort Name, <br>
                a home away from home where you can arrive as a guest and leave as a friend. <br>
                <span>Our Focus</span>
                At Resort Name, customization is the key – whether it is <br>
                <ul>
                <li>a family celebration</li>
                <li>a wedding</li>
                <li>a business conference,</li>
                <li> an independent Traveler,</li>
                <li>an adventure program</li>
                <li>an annual day celebration,</li>
                <li>a product launch, or any event whatsoever….</li>
                <li>Customization & Interest Specific Planning is our USP.</li>
                </ul>
            </p>
              You Can Follow Us <br>
            <a href="#">Our Facebook</a> <br>
            <a href="#">Our Twitter</a> <br>
            <a href="#">Our Instagram</a> <br>
          </div>
        </div>
        <div class="media-right">
          <button class="delete"></button>
        </div>
      </article>
    </div>
  </div>
</template>
<style scoped>
#app{
  height: 100vh;
  width: 100vw;
  margin-left:-2%;
  background: url(../assets/about.jpg);
  padding: 25px;
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.media{
  height: 60vh;
  width: 40vw;
  margin-top: 8vh;
  padding: 2px;
}
</style>

<script>
export default {
};
</script>
