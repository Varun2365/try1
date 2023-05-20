<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>P-TECH SCALES</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <nav class="nav">
        <div class="nav-left">
            <h1>P-TECH SCALES</h1>
        </div>
        <div class="nav-right">
            <ul>
                <a href="#" >
                    <li>HOME</li>
                </a>
                <a href="#products">
                    <li>PRODUCTS</li>
                </a>
                <a href="#weigh">
                    <li>WEIGHING BRIDGE</li>
                </a>
                <a href="#">
                    <li>ABOUT US</li>
                </a>
            </ul>
            <button class="button-default">
                <div class="flex"><span>
                        <div class="icon"></div>Store
                    </span></div>
                </button>
            </div>
            <button class="ham" onclick="showmenu()" id="ham"><div class="hamburger"></div></button>
    </nav>
    <div class="menu" id="panel">
        <button class="cross-button" onclick="hidemenu()"><div class="cross"></div></button>
        <ul>
            <a href="#" onclick="hidemenu()">
                <li>HOME</li>
            </a>
            <a href="#products"onclick="hidemenu()">
                <li>PRODUCTS</li>
            </a>
            <a href="#weigh"onclick="hidemenu()">
                <li>WEIGHING BRIDGE</li>
            </a>
            <a href="#"onclick="hidemenu()">
                <li>ABOUT US</li>
            </a>
        </ul>
    </div>
    <div class="home section">
        <div class="home-left">
            <h1>P-TECH SCALES</h1>
            <center><h4>- Leading Indian Weighing Scale Manufacturers</h4>
            <h4 class="margin">- Where Quality Meets Satisfaction!</h4>
            <a href="#trust" class="no-decoration"><button class="button-default no-margin-button">Visit</button></a>
        </center>
        </div>
        <div class="home-right">
            <div class="hero"></div>
        </div>
    </div>
    <div class="trust" id="trust">
        <h3>Trusted By 1000+ Companies</h3>
        <h2>All Over The India.</h2>
    </div>
    <div class="products section" id="products">
        <h1>&nbsp;PRODUCTS&nbsp;</h1>
        <div class="card-section">
            <div class="card">
                <div class="card-image table-top"></div>
                <div class="card-info">
                    <h2>TABLE TOP</h2>
                    <h5>Capacity: 30Kg <br> Ideal For Retail Shops and Homes</h5>
                    <h4>₹2700/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image digital-indicator"></div>
                <div class="card-info">
                    <h2>DIGITAL INDICATOR</h2>
                    <h5>Capacity: Variable <br> Ideal For Weighing Bridges</h5>
                    <h4>₹5000/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image kitchen"></div>
                <div class="card-info">
                    <h2>KITCHEN SCALE</h2>
                    <h5>Capacity: 5Kg <br> Ideal For Kitchens</h5>
                    <h4>₹700/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image personal"></div>
                <div class="card-info">
                    <h2>PERSONAL WEIGHING SCALE</h2>
                    <h5>Capacity: 150Kg <br> Ideal For Hospitals/Clinics</h5>
                    <h4>₹900/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image hanging"></div>
                <div class="card-info">
                    <h2>HANGING SCALE</h2>
                    <h5>Capacity: 120Kg <br> Ideal For Industrial Use</h5>
                    <h4>₹700/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image jewellery"></div>
                <div class="card-info">
                    <h2>JEWLLERY SCALE</h2>
                    <h5>Capacity: Upto 5Kg <br> Ideal For High Precision Use</h5>
                    <h4>₹4000/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image pocket"></div>
                <div class="card-info">
                    <h2>POCKET SCALE</h2>
                    <h5>Capacity: 3Kg <br> Portable Weighing Scale</h5>
                    <h4>₹900/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image hanging"></div>
                <div class="card-info">
                    <h2>HANGING SCALE</h2>
                    <h5>Capacity: 120Kg <br> Ideal For Industrial Use</h5>
                    <h4>₹700/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image hanging"></div>
                <div class="card-info">
                    <h2>HANGING SCALE</h2>
                    <h5>Capacity: 120Kg <br> Ideal For Industrial Use</h5>
                    <h4>₹700/-</h4>
                </div>
            </div>
            <div class="card">
                <div class="card-image hanging"></div>
                <div class="card-info">
                    <h2>HANGING SCALE</h2>
                    <h5>Capacity: 120Kg <br> Ideal For Industrial Use</h5>
                    <h4>₹700/-</h4>
                </div>
            </div>
        </div>
        <center> <button class="button-default no-margin-button">Show More</button></center>
    </div>
    <div class="weighing-bridge" id="weigh">
        <div class="weighing-bridge-left">
            <h1>Weighing Bridge <br>
                <h4>& Automation</h4>
            </h1>
        </div>
        <div class="weighing-bridge-right">
            <div class="weigh-top">
                <h3>We, at P-Tech Scales <sup>TM</sup> provide you with world class technical Weighing Bridges, with
                    high durability, reasonable pricing and that's why we outstand from our competitors.</h3>
            </div>
            <div class="weigh-bottom">
                <div class="weigh-card">
                    <div class="weigh-image pit"></div>
                    <div class="weigh-info">
                    <div class="weigh-heading"><h4>Pit-Less Weigh Bridge</h4></div>
                    <div class="weigh-text">This type of weighbridge is most suitable for places with limited space e.g. Non-hilly areas where the construction of pit is not a costly affair.</div>
                </div>
                </div>
                <div class="weigh-card">
                    <div class="weigh-image pit-type"></div>
                    <div class="weigh-info">
                    <div class="weigh-heading"><h4>Pit-Type Weigh Bridge</h4></div>
                    <div class="weigh-text">This type of weighbridge is most suitable for places with limited space e.g. Non-hilly areas where the construction of pit is not a costly affair.</div>
                </div>
                </div>
                <div class="weigh-card no-border">
                    <div class="weigh-image mobile "></div>
                    <div class="weigh-info">
                    <div class="weigh-heading"><h4>Mobile Weigh Bridge</h4></div>
                    <div class="weigh-text">These kinds of weighbridges have the ability to place directly in the path of the vehicles and thus reduce the cost of transport compared to the fixed weighbridge installation.</div>
                </div>
                </div>
            </div>
            <!-- <button class="button-default" >Know More</button> -->
        </div>
    </div>
    <div class="about-us section">
        <!-- <marquee behavior="alternate" direction=""><center style="padding-top: 10rem">CURRENTLY WEBSITE UNDER CONSTRUCTION</center></marquee> -->
        <button onclick="showmenu()">hello</button>
    </div>
    <script>
        document.getElementById("panel").id = "tab";
        document.getElementById("ham").id = "ham";
        function hidemenu(){
            // let tab = document.getElementById("panel");
            tab.style.display = "none";
            // tab.style.zindex = "-100";
            // ham.style.zindex = "100";
        }
        function showmenu(){
            console.log("clicked");
            
            // tab.style.z-index = "100";
            tab.style.display = "block";

        }
    </script>
</body>

</html>
