# Web Design for a Software Product Company

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

home.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Malini Techonlogies</title>
    <link rel="stylesheet" href="./css/layout1.css" />
    <link rel="icon" href="./img/exp7_icon.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Malini Technologies Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/exp7_web2.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product boat 103 wireless neckband takes this to a new level, 
            making your start to automation, or your switch to boat Rockerz 370
            than ever before. You can now discover the product much more easily and 
            make the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Malini Technologgies Limited, Developed by Aravindhnath.
      </div>
    </div>
  </body>
</html>
```

products.html
```html
<!DOCTYPE html> 
<html lang="en">
    <head>
        <title>Malini Techonlogies Limited</title>
        <link rel="stylesheet" href="./css/layout1.css" />
        <link rel="icon" href="./img/exp7_icon.jpg" type="image/x-icon" />
    </head>

    <body>
        <div class="container">
            <div class="banner">Malini Technologies Limited.</div> 
            <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        
        </div>
            <div class="content">
                <div class="productcontent">
                    <h1>Our Premium Products</h1> 
                    <div class="productitems">
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod1.png"  alt="product image"> 
                            </div>
                            <div class="itemname">boAt Immortal 121 TWS Gaming Earbuds</div>
                            <div class="itemprice">Price: Rs.1,499.00 </div>
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod2.png" alt="product image"> 
                            </div>
                            <div class="itemname">Ascetic Foldable GPS FPV Drone</div>
                            <div class="itemprice">Price: Rs.4,999.00 </div> 
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod3.png"  alt="product image"> 
                            </div>
                            <div class="itemname">Apple iPhone 13 128 GB, Red</div> 
                            <div class="itemprice">Price: Rs.62,999.00 </div>
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod4.png"  alt="product image"> 
                            </div>
                            <div class="itemname">Fire-Boltt Pink Hurricane Smartwatch </div>
                            <div class="itemprice">Price: Rs.1,399.00 </div> 
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod5.png"  alt="product image"> 
                            </div>
                            <div class="itemname">realme tablet pc Android</div>
                            <div class="itemprice">Price: Rs.6,999.00 </div> 
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod6.png"  alt="product image"> 
                            </div>
                            <div class="itemname">HP Pavilion Intel Core i5 </div>
                            <div class="itemprice">Price: Rs.72,369.00 </div> 
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod7.png"  alt="product image"> 
                            </div>
                            <div class="itemname">OnePlus Nord CE 2 Lite</div>
                            <div class="itemprice">Price: Rs.17,990.00 </div> 
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod8.png"  alt="product image"> 
                            </div>
                            <div class="itemname">boAt 103 Wireless Neckband (Black)</div> 
                            <div class="itemprice">Price: Rs.1,199.00 </div>
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod9.png"  alt="product image"> 
                            </div>
                            <div class="itemname">BoAt Rockerz 370</div>
                            <div class="itemprice">Price: Rs.1,184.00 </div> 
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod10.png"  alt="product image"> 
                            </div>
                            <div class="itemname">Fingerprint encrypted Solid State USB Flash Drive</div>
                            <div class="itemprice">Price: Rs.3,699.00 </div> 
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod11.png"  alt="product image"> 
                            </div>
                            <div class="itemname">boAt Stone Grenade 5W Portable Bluetooth Speaker</div> 
                            <div class="itemprice">Price: Rs.1,499.00 </div>
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/exp7_prod12.png"  alt="product image"> 
                            </div>
                            <div class="itemname">Keyboard Mouse Sets USB Wired Keyboard</div> 
                            <div class="itemprice">Price: Rs.2,499.00 </div>
                        </div>
                    </div> 
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2023 Malini Technologies Limited, Developed by Aravindhnath
            </div>
        </div>
    </body> 
</html>
```

people.html
```html
<!DOCTYPE html> 
<html lang="en">
    <head>
        <title>Malini Techonlogies Limited</title>
        <link rel="stylesheet" href="./css/layout1.css" />
        <link rel="icon" href="./img/exp7_icon.jpg" type="image/x-icon" />
    </head>

    <body>
        <div class="container">
            <div class="banner">Malini Technologies Limited.</div> 
            <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>

        <div class="content">
        <div class="productcontent"> 
            <h1>People Of Company </h1> 
            <figure>
        <p>
            <img src="./img/exp7_founder.png" width="332px" height="277px">
        </p>
        <figcaption> <h2>FOUNDER</h2></figcaption>
        <hr> 
        <p>
        <img src="./img/exp7_cofounder.png" width="332px" height="277px">
        </p>
        <figcaption> <h2>CO-FOUNDER</h2></figcaption> <hr>
        <p>
        <img src="./img/exp7_ceo.png" width="332px" height="277px">
        </p>
        <figcaption> <h2>CEO</h2></figcaption> <hr>
        <p>
        <img src="./img/exp7_manager.png" width="332px" height="277px">
        </p>
        <figcaption> <h2>MANAGER</h2></figcaption> <hr>
        <p>
        <img src="./img/exp7_deputymanager.png" width="332px" height="277px">
        </p>
        <figcaption> <h2>DEPUTY-MANAGER</h2></figcaption> <hr>
        <p>
        <img src="./img/exp7_saleshead.png" width="332px" height="277px">
        </p>
        <figcaption> <h2>SALES-REPRESENTATIVE HEAD</h2></figcaption> <hr>
        </figure> </div>
        </div>
        <div class="footer">
            Copyright &#169; 2023 Malini Technologies Limited, Developed by Aravindhnath </div>
        </div>
    </body>
</html>
```

contactus.html
```html
<!DOCTYPE html> 
<html lang="en">
    <head>
        <title>Malini Techonlogies Limited</title>
        <link rel="stylesheet" href="./css/layout1.css" />
        <link rel="icon" href="./img/exp7_icon.jpg" type="image/x-icon" />
    </head>

    <body>
        <div class="container">
            <div class="banner">Malini Technologies Limited.</div> 
            <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>

        <div class="content">
            <h1>Our Contact Address</h1> 
            <div class="contacttext">
            Phone:987654321
            <br>Email-address:maliniechonlogieslimited@gmail.com 
            </div>
        </div>
        <div class="footer">
            Copyright &#169; 2023 Malini Techonlogies Limited, Developed by Aravindhnath </div>
        </div> 
    </body> 
</html>
```

layout.css
```css
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(30, 255, 0);
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid BLACK;
  box-shadow: 15px 15px 8px rgb(17, 0, 255);
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/exp7_web1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: rgb(251, 255, 0);
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: rgb(255, 149, 0);
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
  color: #ff0000;
}

.menuitem a {
  text-decoration: none;
  color: #fdfdfd;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(201, 135, 240);
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
  background-color: rgb(255, 0, 255);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}
.contact{
    border:100px;
}
.contenttext {
  text-align: justify;
}
```

## OUTPUT:

### Home Page:

![output](./Output/exp7_output1.png)

### Product Page:

![output](./Output/exp7_outpu21.png)

### People Page:

![output](./Output/exp7_output3.png)

### Contactus Page:

![output](./Output/exp7_output4.png)

## Server Output:

![output](./Output/exp7_serveroutput.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
