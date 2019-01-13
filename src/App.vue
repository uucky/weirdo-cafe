<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <header msg="Welcome to Your Vue.js App"/> -->
    <div id="wrapper">

      <div id="header">
          <img id="header-logo" src="./assets/weirdo-logo.jpg" alt="Weirdo Cafe Logo">
          <h1>Weirdo Cafe</h1>
      </div>

      <div id="content">
        <h2>~ menu ~</h2>

        <div class="menu">
          <h3>Pasta</h3>
          <ul>
            <li>P1. Weirdo Burger Spaghetti with Tomato Yogurt Sauce</li>
            <li>P2. Kimchi Beef Spaghetti (or Vegetarian Option)</li>
            <li>P3. Pesto Clam Spaghetti (or Seafood option)</li>
            <li>P4. Roasted Chicken Spaghetti with Basil Sauce</li>
            <li>P5. Chicken Karaage Spaghetti with Spacial Yogurt Sauce</li>
            <li>P6. Moonlight Spaghetti (Burger Option +$2.00) (Black Pepper, Beef, Onion, Parmesan Cheese)</li>
            <li>P7. Blueberry Yogurt Pork Chop Spaghetti</li>
            <li>P8. Golden Party Spaghetti (Pumpkin Puree, Prawn with Duck Egg Coating)</li>
            <li>P9. Rose Prawn Spaghetti (Prawn, Red Onion, Mushroom with Creamy Tomato Sauce)</li>
            <li>P10. Weirdo Carbonara Spaghetti (Bacon, Mushroom, Egg, Parmesan Cheese)</li>

          </ul>
        </div>

        <h2>~ contact ~</h2>

        <div class="contact">
          <div class="left-panel">
            <address>
              <span class="street-name">6459 Victoria Drive</span>
              <span class="city-name">Vancouver, BC V5P 3X5</span>
              <span class="phone-number"><a href="tel:(604) 559-8836">(604) 559-8836</a></span>
            </address>
            <br>
            <span>Monday Closed</span>
            <span>Tuesday ~ Sunday	10:00 am - 12:00 am</span>
            <!-- <span>Tue	10:00 am - 12:00 am</span>
            <span>Wed	10:00 am - 12:00 am</span>
            <span>Thu	10:00 am - 12:00 am</span>
            <span>Fri	10:00 am - 12:00 am</span>
            <span>Sat	10:00 am - 12:00 am</span>
            <span>Sun	10:00 am - 12:00 am</span> -->
          </div>
          <!-- <div class="contact-divider"></div> -->
          <div class="right-panel">
            <div class="mapouter">
              <div class="gmap_canvas">
                <iframe width="380" height="380" id="gmap_canvas" src="https://maps.google.com/maps?q=weirdo%20cafe&t=&z=11&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0">
                </iframe>
              </div>
            </div>
          </div>

        </div>
      </div>

      <div id="footer">
        <span class="footer">&copy; Chell Li 2018</span>
      </div>

    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import Header from './components/Header.vue';
export default {
  name: 'app',
  components: {
    Header,
  },
};
</script>

<style>
#app {
   font-family: 'Overlock', 'Sail', Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

<style lang="less" >
@import url("./assets/less.less");
</style>
