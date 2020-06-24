<template>
  <div id="app">
    <body>
      <div class="header">
        <nav class="navbar">
          <a href="#" class="navbar-brand">CRHSAMPLE</a>
          <a href="#" class="navbar-links">NEWS</a>
          <a href="#" class="navbar-links">SERVICE</a>
          <a href="#" class="navbar-links">COMPANY</a>
          <a href="#" class="navbar-links">CONTACT</a>
        </nav>
      </div>

      <div class="container">
        <section class="content-header">
          <img src="./assets/keyvisual.png">
        </section>

        <section class="content-article">
          <h3>SAMPLE 1</h3>
          <hr>
          <p>But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful. Nor again is there anyone who loves or pursues or desires to obtain pain of itself, because it is pain, but because occasionally circumstances occur in which toil and pain can procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious physical exercise, except to obtain some advantage from it? But who has any right to find fault with a man who chooses to enjoy a pleasure that has no annoying consequences, or one who avoids a pain that produces no resultant pleasure? On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee</p>
        </section>

        <section class="content-news">
          <h3>NEWS</h3>
          <hr>
          <ul class="news-list">
            <li class="news-item">
              <span class="news-item-date">2013/05/01</span>
              <span class="news-item-title">Please feel free to send us any additional dummy texts.</span>
            </li>
            <li class="news-item">
              <span class="news-item-date">2013/04/30</span>
              <span class="news-item-title">Please feel free to send us any additional dummy texts.</span>
            </li>
            <li class="news-item">
              <span class="news-item-date">2013/04/20</span>
              <span class="news-item-title">Please feel free to send us any additional dummy texts.</span>
            </li>
            <li class="news-item">
              <span class="news-item-date">2013/04/11</span>
              <span class="news-item-title">Please feel free to send us any additional dummy texts.</span>
            </li>
            <li class="news-item">
              <span class="news-item-date">2013/04/10</span>
              <span class="news-item-title">Website OPEN.</span>
            </li>
          </ul>
          <span class="glyphicon glyphicon-play"></span>
          <a href="#" class="news-moreinfo">More Information</a>
        </section>
      </div>

      <footer class="main-footer">
        <h4>Copyright (C) 2013 CRHSAMPLE All Rights Reserved</h4>
      </footer>
    </body>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  width: 100%;
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

/* Header styles */
.header {
  overflow: hidden;
  background-color: #79c7e8;
  position: sticky;
  position: -webkit-sticky;
}

.header a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.header a.navbar-brand {
  font-size: 36pt;
}

.header a.navbar-links {
  margin-top: 1%;
  float: right;
  font-size: 16pt;
}

/* Change color upon hover */
.header a.navbar-links:hover {
  background-color: #4196b4;
}

.navbar, .container {
  width: 80%;
  margin: auto;
}

/* Container */
.container {  
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.content-header, .content-article, .content-news, .main-footer {
  height: 100%;
  width: 100%;
  margin-top: 3%;
}

img {
  height: 100%;
  width: 100%;
}

.content-article h3, .content-news h3 {
  font-size: 28pt;
  padding-left: 1%;
  margin: 0;
  border-left: 10px solid #79c7e8;
}

.content-article p, .content-news ul {
  font-size: 16pt;
  width: 100%;
  margin: 0;
  padding: 0;
}

.content-article hr, .content-news hr {
  border: 1px solid #79c7e8;
}

.content-news .news-item {
  margin: 1%;
  list-style-type: none;
}

.content-news .news-item-date{
  margin-right: 5%;
}

.content-news .news-moreinfo {
  float: right;
  font-size: 16pt;
}

/* Footer */
footer {
  padding: 1%;
  font-size: 12pt;
  text-align: center;
  color: #ffffff;
  background-color: #79c7e8;
}
</style>