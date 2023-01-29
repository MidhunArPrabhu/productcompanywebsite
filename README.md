# EXPERIMENT-07
# WEB DESIGN FOR SOFTWARE PRODUCT COMPANY :
## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

```pytho
DEVELOPED : MIDHUN AZHAHU RAJA P
REF NO : 22008311
```
### HOME.HTML :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dc Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> </div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">HOME</a></div>
        <div class="menuitem"><a href="/static/products.html">PRODUCTS</a></div>
        <div class="menuitem"><a>PEOPLE</a></div>
        <div class="menuitem"><a>CONTACT US</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/comic.jpg" alt="Marvel" />
          <div class="contenttext">
            In the name of his murdered parents, Bruce Wayne wages eternal war on the criminals of Gotham City. He is vengeance. He is the night. He is Batman.

One of the most iconic fictional characters in the world, Batman has dedicated his life to an endless crusade, a war on all criminals in the name of his murdered parents, who were taken from him when he was just a child. Since that tragic night, he has trained his body and mind to near physical perfection to be a self-made Super Hero. He's developed an arsenal of technology that would put most armies to shame. And he's assembled teams of his fellow DC Super Heroes, like the Justice League, the Outsiders and Batman, Incorporated.
            <br />
             A playboy billionaire by day, Bruce Wayne’s double life affords him the comfort of a life without financial worry, a loyal butler-turned-guardian and the perfect base of operations in the ancient network of caves beneath his family’s sprawling estate. By night, however, he sheds all pretense, dons his iconic scalloped cape and pointed cowl and takes to the shadowy streets, skies and rooftops of Gotham City.
            <ul>
              <li>Powers:
                  exceptional martial artist, combat strategy, inexhaustible wealth, brilliant deductive skill, advanced technology</li>
              <li>
First Appearance
DETECTIVE COMICS #27 (1939)
</li>
              <li>Alias/Alter Ego:
Bruce Wayne</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2022 Dc Private Limited, Developed By Midhun Ar Aka Midz.
      </div>
    </div>
  </body>
</html>
```

### PRODUCT.HTML :
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dc Private Limited.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> </div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">HOME</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">PRODUCTS</a>
        </div>
        <div class="menuitem"><a>PEOPLE</a></div>
        <div class="menuitem"><a>CONTACT US</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
<h1 style="font-family:'Times New Roman', Times, serif">PRODUCTS WE HAVE : </h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tshirt.jpg" alt="product image">
                  </div>
                  <div class="itemname">Marvel T-shirt</div>
                  <div class="itemprice">Price: Rs.40,00.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/airpods.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Earpods</div>
                  <div class="itemprice">Price: Rs.6,999.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/legbat.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Lego set</div>
                  <div class="itemprice">Price: Rs.3,699.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/bottle.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Water Bottle</div>
                  <div class="itemprice">Price: Rs.1,699.00 </div>
              </div>
              
                   
              
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/watch.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Watch</div>
                  <div class="itemprice">Price: Rs.17,699.00 </div>
              </div>
              
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/case.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mobile Case</div>
                  <div class="itemprice">Price: Rs.2,699.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 Dc Private Limited, Developed By Midhun Ar Aka Midz.
      </div>
    </div>
  </body>
</html>
```
### LAYOUT.CSS :
```css
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #ffffff;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/banner.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: black;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #d18316;
}

.menuitem a {
  text-decoration: none;
  color: red;
}

.content {
  display: block;
  width: 100%;
  background-color: #25e2c2;
  background-image: url("/static/img/back.jpg");
  background-position: 100%;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #ffffff;
}
```

## OUTPUT:

### HOME PAGE :

![Screenshot (73)](https://user-images.githubusercontent.com/118054670/215335736-85eda3f4-470d-42ec-9413-741dccdd3662.png)


## PRODUCT PAGE :

![Screenshot (74)](https://user-images.githubusercontent.com/118054670/215335748-7f9b7b84-7191-458d-b80f-cd12306cf5db.png)

## HTML VALIDATOR :

![Screenshot (76)](https://user-images.githubusercontent.com/118054670/215337399-be637787-c5a4-47fa-8b78-13cbf4b49df1.png)



## RESULT :

Thus a website is designed for the software product company and the HTML,CSS code are validated.
