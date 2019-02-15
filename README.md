# Cheese-Toastie - Code Institute 5 Day Code Challenge (Final)

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cheese Toastie</title>
      <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
      <link rel="stylesheet" href="receipe.css" type="text/css"/>
 <!--[provide compatibility for IE Browsers older than IE 9 with html5shiv (new html 5 semantic elements) ]>-->
  <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
  <style>
  body{
font-family: monospace; 
background-color: antiquewhite; 
color:slategray;}

#container{
width:60%; 
margin:auto;}

h1{
font-size:300%;}

h1, h2 {
text-decoration-line: underline; 
text-decoration-style: dotted;
text-transform:uppercase;
font-weight:100;
background-color:yellow;
color:black;}

footer{
margin-top:50px; 
background-color:yellow;
width:100%;}

footer p {
text-align: right; 
margin-right: 20px; 
padding-top: 10px; 
padding-bottom:10px;}

.caption {
font-size:small; 
text-align: left;}

.toast {
border-style:dotted;
width:100%;}

@media screen and (max-width:768px){
#container{
width:90%;}
              
h1 {
font-size:150%;}
              
h1, h2 {text-decoration-line: none; }
}

</style>
</head>
    
  <body>
      <div id="container">
     <header>
        <h1>Cheese Toastie Sandwich</h1>
        <img class="toast" src="https://i.postimg.cc/nLqj2rvT/daria-nepriakhina-488775-unsplash.jpg">
        <p>Photo by Daria Nepriakhina on <a href="https://unsplash.com/@epicantus" target="_blank"> Unsplash</a></p>
    </header>
    <section id="preparation" onmouseover="prepHover()" onmouseout="prepNormal()">
        <h2>Ingredients
            <i class="fas fa-bread-slice"></i>
        </h2>
        <ul>
          <li>1 or 2 slice's of brown bread (<em>gluten free</em>)</li>
          <li>Cheese (<em>lactose free</em>)</li>
          <li>Tomato Ketchup</li>
          <li>Grain of Salt</li>
          <li>Sprinkle of black grounded pepper</li>
        </ul>
    </section>
    <section id="prep" onmouseover="prepHove()" onmouseout="prepNorma()">
        <h2>Preparation 
            <i class="fas fa-check"></i>
        </h2>
        <ol>
          <li>Grill one side of the bread to desired taste and keep to one side to cool.</li>
          <li>Cut 3 or 4 slices of cheese.</li>
          <li>Place cheese on one of the un-toasted bread side and grill until melted (careful not to over-melt).</li>
          <li>Remove the cheese toastie and season it with salt and pepper. Place the other toast on top to make the sandwich.</li>
          <li>Enjoy with or without a dollop of Tomato Ketchup!</li>
          </ol>
    </section>
    <footer>
      <p> Me &copy; 2019</p>
    </footer>
          </div>
      
      <script>
      
      function prepHover(){
            document.getElementById('preparation').style.backgroundColor="white";
          document.getElementById('preparation').style.color="black";
      }
           function prepNormal(){
          document.getElementById('preparation').style.backgroundColor="antiqueWhite";
      }
      
       function prepHove(){
          document.getElementById('prep').style.backgroundColor="white";
          document.getElementById('prep').style.color="black";
      }
           function prepNorma(){
          document.getElementById('prep').style.backgroundColor="antiqueWhite";
      }
    
      </script>
  </body>
</html>
