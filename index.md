<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="styles.css" type="text/css" rel="stylesheet">
        <script src="greeting.js"></script>
    </head>

    <body class="container">

            <!--Adds an overlay effect to the page content (100% width and height with a black background color with 50% opacity)-->
            <div id="overlay" onclick="off_overlay()">
                <hr id="line_1" />
                Today's tip:
                <q> <em> Drink Water Regularly </em> </q>
                <hr />
            </div>
            <!-- Some form of dynamism is needed for the tips, It could be a different one for everyreload
            or a different one for every time of the day(Morning, Afternoon and Night) or every day-->

            <header id="header">
                <nav>
                    <ul>
                        <li><a class="active" href="">Home</a></li>
                        <li><a href="">Breakfast</a></li>
                        <li><a href="">Lunch</a></li>
                        <li><a href="">Dinner</a></li>
                        <li><a href="">Tips</a></li>
                    </ul>
                </nav>

                <div>
                    <!--<h1>Feeding Suppport System</h1>-->
                    <br/>
                    <br/>
                    <p><script>document.write('<h1>'+ greeting +'</h1>');</script></p>
                    <p id="question">What would you like to eat? </p>

                    <!-- Don't forget to deactivate this button later or reassign it. It is present now for testing
                    <button onload="on_overlay()">Turn on overlay effect</button>-->
                </div>
                    
            </header>

            <section>
                
                    <div id="breakfast" style="padding:20px">
                        <h2 class="meal_heading">Breakfast</h2>
                        <div class="box showSlide fade">
                            <img src="images\egg-sauce.png"  alt="Yam and Fried Egg">
                            <p><h2><strong>Yam and Fried Egg</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Drink water as much as possible daily</em></q></p>
                            </div>
                        </div>

                        <div class="box showSlide fade">
                            <img src="images\download.jfif" alt="Jollof Rice, Meat and Boiled Egg">
                            <p><h2><strong>Jollof Rice, Meat and Boiled Egg</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                        </div>

                       <div class="box showSlide fade">
                            <img src="C:\Users\timot\Desktop\PROJECT FINALS\FOOD HUNT Snips\New folder\JUMIA FOOD.png" alt="Meal">
                            <p><h2><strong>Beans and Plantain</strong></h2></p> -->
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                        </div>

                        <div class="box showSlide fade">
                            <img src="C:\Users\timot\Desktop\PROJECT FINALS\FOOD HUNT Snips\New folder\Jevinik's menu2.png" alt="Meal">
                            <p><h2><strong>Beans and Plantain</strong></h2></p>-->
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                        </div>

                        <div class="box showSlide fade">
                            <img src="C:\Users\timot\Desktop\PROJECT FINALS\FOOD HUNT Snips\New folder\Jevinik's menu3.png" alt="Meal">
                            <p><h2><strong>Beans and Plantain</strong></h2></p> -->
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                        </div>-->
                    </div> 
            </section>

            <section>
                <div id="lunch" style="padding:20px">
                    <h2 class= "meal_heading">Lunch</h2>
                    <div class="box">
                        <img src="images\jollof ric, plantain and chicken.jpg" alt="Jollof Rice, Plantain and Chicken"/>
                        <p><h2><strong>Jollof Rice, Plantain and Chicken</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\fried rice and chicken.jpg" alt="Fried Rice and Chicken" />
                        <p><h2><strong>Fried Rice and Chicken</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:400</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>You can add a salad</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images ax.jfif" alt="Beans and Plantain" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>
                </div>
            </section>

            <section>
                <div id="dinner" style="padding:20px">
                    <h2 class= "meal_heading">Dinner</h2>
                    <div class="box">
                        <img src="images\download spag.jfif" alt="Spaghetti and Fish" />
                        <p><h2><strong>Spaghetti and Fish</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images .jfif" alt="Moi-Moi and Boiled Egg" />
                        <p><h2><strong>Moi-Moi and Boiled Egg</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>
                </div>
            </section>

            <section>
                <div id="other_meal_options" style="padding:20px">
                    <h2 class= "meal_heading">Others</h2>
                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>

                    <div class="box">
                        <img src="images\images.jfif" />
                        <p><h2><strong>Beans and Plantain</strong></h2></p>
                            <!--In this box everything below appears only on hover or mouse over -->
                            <div class="meal_details">
                                <p><strong>Base Price:</strong></p>
                                <p><strong>Available in: </strong>TDC Cafeteria</p>
                                <p><strong>Food Based Guideline: </strong><q><em>Eat Vegetables</em></q></p>
                            </div>
                    </div>
                </div>
            </section>

            <footer>
                &trade; 2020 Feeding Support System
            </footer>

    </body>

    <!--JS for greeting the user-->
    <script>
        function on_overlay() {
            document.getElementById("overlay").style.display = "block";
        }

        function off_overlay() {
            document.getElementById("overlay").style.display = "none";
        }

        if (document.onloadstart = true) {
            on_overlay();
        }
    </script>

</html>
