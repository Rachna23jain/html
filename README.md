
<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Georgia, 'Times New Roman', Times, serif
  padding: 10px;
  background: #b2e94b;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  text-align: center;
  background: rgb(176, 231, 46);
}

.header h1 {
  font-size: 50px;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}


/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
}
.newspaper {
  column-count: 3;
  column-gap: 40px;
  column-rule-style: solid;
  column-rule-width: 1px;
  column-rule-color: lightblue;
}
</style>
</head>
<body>

<div class="header">
  <h1>Learn to Code</h1>
  <p>With the world's largest web developer site.</p>
</div>

<div class="topnav">
  <a href="#">Tutorial</a>
  <a href="#">Exercise</a>
  <a href="#">Refrence</a>
  <a href="#" style="float:right">Register</a>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2 style="color:rgb(6, 168, 47);">HTML-Hyper Text Mark-up Language</h2>
      <h5>DEVELOPE YOU OWN WEBSITE</h5>
      
<div class="gallery">
    <a target="_blank" href="html.jpg">
      <img src="html.jpg" alt="html" width="600" height="400">
    </a>
  </div>
  
      <p>HTML is the standard markup language for Web pages.
        With HTML you can create your own Website.
        HTML is easy to learn - You will enjoy it!</p>
    </div>
    <div class="card">
      <h2 style="color:rgb(6, 168, 47);">CSS-Cascading Style Sheets</h2>
      <h5>STYLE YOUR OWN WEBSITE</h5>
      <div class="gallery">
        <a target="_blank" href="css.gif">
          <img src="css.gif" alt="css" width="600" height="400">
        </a>
      </div>
      <p>CSS stands for Cascading Style Sheets
        CSS describes how HTML elements are to be displayed on screen, paper, or in other media
        CSS saves a lot of work. It can control the layout of multiple web pages all at once
        External stylesheets are stored in CSS files</p>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <div class="gallery">
        <a target="_blank" href="learn.png">
          <img src="learn.png" alt="learn" width="300" height="200">
    </div>
    <div class="card">
      <h3>Popular Post</h3>
      <div class="gallery">
        <a target="_blank" href="pop1.jpg">
          <img src="pop1.jpg" alt="pop" width="200" height="150">
        </a>
      </div> <div class="gallery">
        <a target="_blank" href="cpop.jpg">
          <img src="cpop.jpg" alt="cpop" width="200" height="150">
        </a>
      </div> <div class="gallery">
        <a target="_blank" href="bpop.jpg">
          <img src="bpop.jpg" alt="bpop" width="200" height="150">
        </a>
      </div>
    </div>
    <div class="card">
      <h3>Follow Me</h3>
      <p>INSTAGRAM:RJ_tutorials</p>
      <p>FACEBOOK:RJ Tutorials</p>
      <p>CONTACT-9191929393</p>
    </div>
  </div>
</div>
<br>
<div class="newspaper">
  <h1 style="color:green;">Why web design is important?</h1> 
  When your audience visits your website, it gives them their first impression of your business. They will judge your business within seconds. In these first few seconds, you want to make a positive impact on your audience.
  If your website looks unappealing or outdated, your audience will immediately have a negative impression of your business. They won’t find your website appealing, which deters them from your page. You’ll miss out on leads because they’ll leave your page for a competitor’s page.
  Web design is important because it impacts how your audience perceives your brand. The impression you make on them can either get them to remain on your page and learn about your business or leave your page and turn to a competitor. A good web design helps you keep your leads on your page.
  </div>
 <br>
 <div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>


