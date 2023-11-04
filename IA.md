# Unit_3: project of creating a blog for my client 

![](https://github.com/24536urdj/Unit_3/blob/main/Project_unit_3/dd36613d-aaf4-4c07-acd1-0026086aa5bd.gif)


## Criteria A planning

### Problem definition
My client who is currently the leader of pottery club in their respective school decided that many local pottery makers create some wonderful artistic products out of clay such as cups , teapots , and bowls….etc, however these artists find it difficult to sell their products to others and expand their business due to many reasons, but most importantly the language barrier as many of them do not speak english and therefore find it difficult to sell their pottery to tourists or foreigners.
Therefore my client decided that they want to have a website for these artists where they can showcase their work and sell it to foreigners within the prefecture, especially international students that study in my client’s school. 
However since my client does not know how to make a website , did not get enough funding to hire a web developer to make it for them they way they wanted to be and also did not use other free web developing platforms as they do not offer the specific structure they want the website to be as , they have asked me as a member of pottery club in my respective school to create the  website for them and use it as my IA project for computer science.
### Proposed solution

Considering the client’s requirements, an adequate solution includes creating a website where users can create an account and learn more about the general information of the pottery shop and where these pots come from  in the about us  page. The users will be able also to view the latest products added in the Home page along with the price in Japanese yen. Moreover the website will also contain a registration platform , so that users can use it  to create an account and keep track of the products they bought  and pay the fees  which will be indicated on the payment  page once they finish shopping .In addition there will be a contact page where users can contact the pottery club organizer  for more information on the artists or maybe possible collaboration.
In order to achieve what had been described above I will be using python , html and css because firstly python is a multi-functionality language having capabilities to operate in multiple ways, that does not need a license and also easily understandable and usable for the programmer2.for html and css,as Both HTML and CSS are frequently used languages for web development , also HTML uses a tag-based structure which is easy to understand even without any prior technical experience, and CSS uses a simplistic structure as well making the learning curve for mastery relatively easy3; therefore it is more adequate for the developer of the website who is more comfortable with these languages than others like java scripts and in order to keep it organized and fulfill the success criteria , I will use sql to associate a database to the website because it's portability makes it a convenient option for users, as they can transfer it from one device to another with no issues. It processes queries quickly. No matter how large data might be, SQL can retrieve it quickly and efficiently.
### Desing statement
I will design and program a low-cost blog application which will alow the owner to add,withdraw and edit her historical topics in an organized way. This application will also have the ability to share its topics through viewing option. This project is for our client who  needs a low cost blog application that will help her keep her pursue her passion about history easly and effectively . The blog will be created using the software PyCharm and oop programing paradigm that includes the use of python language, taking three weeks to make. All of the findings will be displayed on a 4 min informational video which will also include a discussion of how the code is well organized so that future developers can extend it
if found[^1]. The proposed solution will be evaluated according to criteria A and B.
### Success Criteria 
1.[issue tackled : enable users to log  in  the website ]: The solution needs to have a login   and a sign up  system.
2.[issue tackled : having access to general information about where does these products come from and who make them  ]The website needs to be have a home and about page that contains the general information about the pots , the artists and material used in the process of making it 
3.[issue tackled :  access to available products  ]The solution needs to have a page where users  can view current products , and their prices  along with an add to cart button so that they can select the products they like and buy them. 
4.[issue tackled : Liking products to know which ones are more in demand   ]The solution needs to enable the users to like products and keep counting of these likes so that other users can see reviews and how popular the product is in the review page.
5.[issue tackled : payment methods]
Users need to be able to pay for the products they want to buy through linking paypal to the website, the payment needs to be secure and uncomplicated.
6.[issue tackled : contact the organizing party ] The solution needs to have a contact page where users can send emails to the organizing party and contact for either collaboration or just inquiring information.
## Criteria B design 




|    | Planned Action                                        | Planned Outcome                                                                            | Design Cycle   | Time Estimate | Target Completion | Criteria |
|----|-------------------------------------------------------|--------------------------------------------------------------------------------------------|----------------|---------------|-------------------|----------|
| 1  | First meeting with client                             | meeting with Pottery leader to discuss her deisre for a website to showcase pottery they made                                | Planning       | 8 minutes    | 2nd Septmener        | A        |
| 2  | Write down success criteria                           | discussing my client success criteria and eliminating the unnecessary ones.                                                | Planning       | 7 minutes    | 6 september        | A        |
| 3  | finalizing the success criteria                              |  Meeting with the pottery leader to show her the finalized success criteria and get her consent to start | Planning       | 10 minutes        | 6 septmeber         | A        |
| 4  | Write down the problem definition                              | state a detailed version of the problem and identify  the client                         | Planning       | 40 minutes    | 8 september        | A        |
| 5  | Write down the proposed solution with justification of tools implied | Reasearch and evaluation of solutions to choose an adequate one                                   | Planning       | 1 hours    | 8 september      | A        |
| 6  | presenting the solution to the client  | getting the consent of my client and agreement on the solution                                                     | Planning       | 15 min      | 11 septmeber       | A        |
| 7  | Starts working on website's home page     | complete half the website interface and chose artistic colors for pottery                                      | Development    | 1 day         | 11 september         | C        |
| 8  | Create system diagram                              | system diagram that will be presented to the client                          | Design         | 45 minutes        | 13 september         | B        |
| 9  | start working on the remained website's home page                              | website's home page is ready to be presented                                      | Developement         | 50 min      | 15 september         | C       |
| 10 | Add client's review                    | add client's review of the pots presented in the homepage              | Development    | 30 min        | 15 september         | C        |
| 11 | Create python file to add payment and email function                                                                  | Development    |  15 min      | 16 september        | C        |
| 12 | Add products posts in the website's homepage   | using html and css, add posts of products create by Karuizawa and mashiko pottery maker                                   | development     |     | 18 september       | c        |


### Criteria C development 
## technique used 
-Python
-Html along with Java script inside some html files
-CSS
-Flask library
-SQlite
-If statement
-Functions
-Variables


## Code 
```.py
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta https-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <title>Pottery@Isak</title>

    <link rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="static/Css_2.css">

</head>
<body>
<header>
    <input type="checkbox" name="" id="toggler">
    <label for="toggler" class="fas fa-bars"></label>
<a href="#" class="logo">Pottery@Isak<span>.</span></a>

<nav class="navbar">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#reviews ">Reviews</a>
    <a href="#Contact">Contact</a>



</nav>
<div class ="icons">
    <a href="#" class="fas fa-heart"></a>
    <a href="#" class="fas fa-shopping-cart"></a>
    <a href="#" class="fas fa-user"></a>

</div>
</header>

<section class="home" id="home">
    <div class="content">
        <h3>Pottery@Isak</h3>
        <span>Beautiful pots made by Isak students and local Karuizawa citizens </span>
        <p>Beautiful pots made by isak students </p>
        <a href="#" class="btn">shop now </a>


    </div>
</section>

<section class="about" id="about">
    <h1 class="heading"> <span> About </span> us</h1>
    <div class="row">
{#        <div class="video-container">#}
{#            <video src#}
        <h3>Best Pottery makers just for you </h3>



        </div>
    <div class="content">
        <h3>
            Why choose us ?
        </h3>
        <p>because we are the best</p>
        <a href="#" class="btn">Learn more about us </a>
    </div>
    </div>

</section>
<section class="icons-container">
    <div class="icons">
        <img src="static/salut.png" alt="">
        <div class="info">
            <h3> free Shipping </h3>
            <span> for first order </span>

        </div>

    </div>
     <div class="icons">
        <img src="static/salma.png" alt="">
        <div class="info">
            <h3> Shop before 2nd october  </h3>
            <span> and get 10% discount  </span>

        </div>

    </div>


</section>

<section class="Products" id="Products">
    <h1 class="heading">Latest<span>Products </span> </h1>
    <div class="box-container" >
        <div class="box">
            <span class="discount">-5%</span>
            <div class="image">
                <img src="static/pot.png" alt="">
                <div class="icons">
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="cart-btn">Add to cart</a>
                    <a href="#" class="fas fa-share"></a>


                </div>


            </div>
            <div class="content">
                <h3>Flower pot made of clay</h3>
                <div class="price">800¥<span></span>
                </div>
            </div>
        </div>
        <div class="box">
            <span class="discount">-10%</span>
            <div class="image">
                <img src="static/flower.png" alt="">
                <div class="icons">
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="cart-btn">Add to cart</a>
                    <a href="#" class="fas fa-share"></a>


                </div>


            </div>
            <div class="content">
                <h3>Glazed Cup </h3>
                <div class="price">1000¥<span></span>
                </div>

            </div>
            <div class="box">
                <span class="discount">-5%</span>
                <div class="image">
                    <img src="static/flower_pot%20.png" alt="">
                    <div class="icons">
                        <a href="#" class="fas fa-heart"></a>
                        <a href="#" class="cart-btn">Add to cart</a>
                        <a href="#" class="fas fa-share"></a>


                    </div>


                </div>
                <div class="content">
                    <h3> Red Bowl </h3>
                    <div class="price">900¥<span></span>
                    </div>
                </div>
                <div class="box">
                    <span class="discount">-5%</span>
                    <div class="image">
                        <img src="static/pot.png" alt="">
                        <div class="icons">
                            <a href="#" class="fas fa-heart"></a>
                            <a href="#" class="cart-btn">Add to cart</a>
                            <a href="#" class="fas fa-share"></a>


                        </div>


                    </div>
                    <div class="content">
                        <h3>Flower pot made of clay</h3>
                        <div class="price">1500¥<span></span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="paypal-button-container">

   <!-- PayPal Button Code Goes Here -->
</div>

</section>
<section class="review" id="review">
    <h1 class="heading">customer's <span>review</span></h1>
    <div class="box-container">
        <div class="box">
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>


            </div>
            <p>We will be writing this section later when the website is done </p>
            <div class="user">
                <img src="static/sherine.png" alt="">
                <div class="user-info">
                    <h3>Salma Bennani</h3>
                    <span>Customer's experience</span>

                </div>



            </div>
            <span class="fas fa-quote-right"></span>

        </div>
         <div class="box">
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>


            </div>
            <p>We will be writing this section later when the website is done </p>
            <div class="user">
                <img src="static/sherine.png" alt="">
                <div class="user-info">
                    <h3>Amal Fallah</h3>
                    <span>Customer's experience</span>

                </div>



            </div>
            <span class="fas fa-quote-right"></span>

        </div>
         <div class="box">
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>


            </div>
            <p>We will be writing this section later when the website is done </p>
            <div class="user">
                <img src="static/sherine.png" alt="">
                <div class="user-info">
                    <h3>Antonio Tchikhov</h3>
                    <span>Customer's experience</span>

                </div>


            </div>
            <span class="fas fa-quote-right"></span>

        </div>
    </div>

</section>
<section class="contact" id="contact">
    <h1 class="heading"> <span>Contact </span> us </h1>
    <div class="row">
        <input action="">
            <input type="text" placeholder="name" class="box">
            <input type="text" placeholder="email" class="box">
            <input type="text" placeholder="number" class="box">
            <textarea name=""  class="box" placeholder="message" cols="30" rows="10"></textarea>

            <input type="submit" value="send message" class="btn"> </input>

        </form>

    </div>

</section>
<script>

<script src="https://www.paypal.com/sdk/js?client-id=YOUR_CLIENT_ID"></script>
</body>
</html>
```










