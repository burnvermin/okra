<template>
  <div class="container">
    <div class="header">
      <div class="banner">
        <img v-bind:src="images.bannerPattern" alt="Banner-Pattern" id="BannerPatternLeft">
        <p><a href="" id="parent"><a href="" id="underline" class="fromRight">How Okra Powers Multi-Banking</a><i class="fa-solid fa-arrow-up"></i></a></p>
        <img v-bind:src="images.bannerPattern2" alt="Banner-Pattern2" id="BannerPatternRight">
      </div>
    </div>
    <div class="menuBar ">
      <div class="menuContents one">
        <div class="left">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>Products</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <i class="fa-solid fa-shield" style="color: rgb(102, 236, 109);"></i>
                  <strong>Authentication</strong>
                  <p>Verify finacial account credentials</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-layer-group" style="color: purple; font-weight: bold;"></i>
                  <strong>Transaction</strong>
                  <p>Get comprehensive transaction data</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-fingerprint" style="color: yellow; font-weight: bold;"></i>
                  <strong>Identity</strong>
                  <p>Verify customer Identiy</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-scroll" style="color: yellow; font-weight: bold;"></i>
                  <strong>Balance</strong>
                  <p>Get account balance information</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-file" style="color: rgb(102, 236, 109); font-weight: bold;"></i>
                  <strong>Income</strong>
                  <p>Verify income and employment data</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-money-check-dollar" style="color: purple; font-weight: bold;"></i>
                  <strong>Payments <button>BETA</button></strong>
                  <p>Collect bank payments efficiently</p>
                </div>
              </div>
              <div class="footer">
                <a href=""><a href="" id="underline" class="toRight">See all products</a> &nbsp;<i class="fa-solid fa-arrow-right"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="right">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>Global coverage</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <i class="fa-regular fa-building-columns" style="color: rgb(102, 236, 109); font-weight: bold;"></i>
                  <a href=""><a href="" id="underline" class="toRight">Bank coverage</a></a>
                  <p>See institutions and countries supported</p>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
    <div class="menuContents two">
        <div class="left">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>Use Cases</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <i class="fa-solid fa-hand-holding-hand" style="color: rgb(102, 236, 109);"></i>
                  <strong>Lending</strong>
                  <p>Give out loans confidently</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-layer-group" style="color: purple; font-weight: bold;"></i>
                  <strong>Personal finance</strong>
                  <p>Design personalized experiences</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-paper-plane" style="color: yellow; font-weight: bold;"></i>
                  <strong>Remittance</strong>
                  <p>Make payments with ease</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-mobile" style="color: yellow; font-weight: bold;"></i>
                  <strong>Digital banks</strong>
                  <p>Access crucial building blocks</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-chart-line" style="color: rgb(102, 236, 109); font-weight: bold;"></i>
                  <strong>Busines finance</strong>
                  <p>Plan for the future</p>
                </div>
              </div>
              <div class="footer">
                <a href=""><a href="" id="underline" class="toRight">See all use cases</a> &nbsp;<i class="fa-solid fa-arrow-right"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="right">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>Featured customer story</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <i class="fa-brands fa-product-hunt" style="color: rgb(102, 236, 109); font-weight: bold;"></i>
                  <a href=""><a href="" id="underline" class="toRight">Patricia</a></a>
                  <p>Discover how Patricia onboarded its customes with a 98% success rate through Okra's identity API.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
    <div class="menuContents three">
        <div class="left">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>Developers</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <i class="fa-solid fa-bolt" style="color: purple;"></i>
                  <strong>Get started</strong>
                  <p>View all developer resources</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-book" style="color: rgb(102, 236, 109); font-weight: bold;"></i>
                  <strong>Documentation</strong>
                  <p>See all developer docs</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-code" style="color: black; font-weight: bold;"></i>
                  <strong>API reference</strong>
                  <p>Reference all API endpoints</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-stack-overflow" style="color: yellow; font-weight: bold;"></i>
                  <strong>Developer community</strong>
                  <p>Ask questions and discuss ideas</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="right">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>Resources</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <a href="" style="position: absolute; left: 0; margin: 0% 0%;"><a href="" id="underline" class="toRight"  style="margin: 0% 0%;">API status</a></a>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
    <div class="menuContents four">
        <div class="left">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>Company</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <i class="fa-solid fa-house" style="color: rgb(102, 236, 109);"></i>
                  <strong>About us</strong>
                  <p>Learn about Okra</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-briefcase" style="color: yellow; font-weight: bold;"></i>
                  <strong>Careers</strong>
                  <p>Find the right role for you</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-building" style="color: purple; font-weight: bold;"></i>
                  <strong>Customers</strong>
                  <p>See how businesses use Okra</p>
                </div>
                <div class="product">
                  <i class="fa-regular fa-message" style="color: rgb(102, 236, 109); font-weight: bold;"></i>
                  <strong>Get in touch</strong>
                  <p>Contact the Okra team</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="right">
          <div class="body">
            <div class="products">
              <div class="top">
                <p>From the blog</p>
              </div>
              <div class="bottom">
                <div class="product">
                  <img v-bind:src="images.blogCover" alt="blogCover" id="blogCover">
                  <div class="texts">
                    <p>How Okra Powers Multi-Banking</p>
                    <a href=""><a href="" id="underline" class="toRight">Read all articles</a> &nbsp;<i class="fa-solid fa-arrow-right"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>

    <div class="bodyContainer">
      <div class="menu">
        <div class="top">
          <div class="left">
            <a href=""><img v-bind:src="images.logo" alt="Logo" id="logo"></a>
          </div>

          <div class="center">
            <ul>
              <li @mouseenter="showProducts()">Products <i class="fa-solid fa-angle-down prod"></i></li>
              <li @mouseenter="showUseCase()">Use cases <i class="fa-solid fa-angle-down uCase"></i></li>
              <li @mouseenter="showDevelopers()">Developers <i class="fa-solid fa-angle-down sDev"></i></li>
              <li @mouseenter="showCompany()">Company <i class="fa-solid fa-angle-down sComp"></i></li>
              <li @mouseenter="hideAll()"><a href="">Pricing</a></li>
            </ul>
          </div>

          <div class="right">
            <button class="login">Login</button>
            <button class="signUp">Sign Up</button>
          </div>
        </div>
      </div>
    </div>
    </div>
    <div @mouseenter="hideAll()" class="container-01">
      <div class="body">
        <div class="section-one">
          <div class="text">
            <h1>The fastest way to access finicial data.</h1>
            <p>Access finicial information from banks and more-with one API-to build finicial products.</p>
            <div class="buttons">
              <button id="free">Start for free</button>
              <button id="demo">See demo</button>
            </div>
          </div>
          <img v-bind:src="images.dashboard" alt="dashboard" id="dashboard">
          <img v-bind:src="images.widget" alt="widget" id="widget">
        </div>
        <div class="section-two">
          <p>Trusted by:</p>
          <div class="images">
            <img v-bind:src="images.logoDlocal" alt="logoDlocal" id="logoDlocal">
            <img v-bind:src="images.foodcourt" alt="logoDlocal" id="logoDlocal">
            <img v-bind:src="images.fairmoney" alt="logoDlocal" id="logoDlocal">
            <img v-bind:src="images.interswitchLogo" alt="logoDlocal" id="logoDlocal">
            <img v-bind:src="images.umba" alt="logoDlocal" id="logoDlocal">
            <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
          </div>
        </div>
        <div class="section-three">
          <div class="layer-one">
            <div class=" window windowOne">
              <div class="top">
                <h3>IDENTITY</h3>
                <h1>Speed up your onboarding</h1>
                <p>Realiably sign up your prospects with their KYC profile from any financial institution in seconds.</p>
                <button>Learn more</button>
              </div>
              <hr>
              <div class="middle">
                <p>Companies building with Identity</p>
                <div class="logos">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                </div>
                <div class="bottom">
                  <div class="pattern">
                    <img v-bind:src="images.hpp" alt="hpp" id="hpp">
                  </div>
                  <div class="image">
                    <img v-bind:src="images.identityWindow" alt="identityWindow" id="identityWindow">
                  </div>
                </div>
              </div>
            </div>
            <div class="window windowTwo">
              <div class="top">
                <h3>INCOME</h3>
                <h1>Supercharge financial managemt</h1>
                <p>Design personal financial management experiences with consolidated data.</p>
                <button>Learn more</button>
              </div>
              <hr>
              <div class="middle">
                <p>Companies building with Income</p>
                <div class="logos">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                </div>
                <div class="bottom">
                  <div class="pattern">
                    <img v-bind:src="images.hpp" alt="hpp" id="hpp">
                  </div>
                  <div class="image">
                    <img v-bind:src="images.incomeWindow" alt="incomeWindow" id="incomeWindow">
                  </div>
                </div>
              </div>
            </div>
            <div class="window windowThree">
              <div class="top">
                <h3>PAYMENTS</h3>
                <h1>Collect bank payments efficiently</h1>
                <p>Collect one-time and recurring payments from your customers via USSD and internet banking.</p>
                <button>Learn more</button>
              </div>
              <hr>
              <div class="middle">
                <p>Companies building with Payments</p>
                <div class="logos">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                </div>
                <div class="bottom">
                  <div class="pattern">
                    <img v-bind:src="images.hppw" alt="hppw" id="hppw">
                  </div>
                  <div class="image">
                    <img v-bind:src="images.paymentWindow" alt="paymentWindow" id="paymentWindow">
                  </div>
                </div>
              </div>
            </div>
            <div class="window windowFour">
              <div class="top">
                <h3>BALANCE</h3>
                <h1>Get real-time balance information</h1>
                <p>Validate the vuying power of your customers and reduce failed payments.</p>
                <button>Learn more</button>
              </div>
              <hr>
              <div class="middle">
                <p>Companies building with Balance</p>
                <div class="logos">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                </div>
                <div class="bottom">
                  <div class="pattern">
                    <img v-bind:src="images.hpp" alt="hpp" id="hpp">
                  </div>
                  <div class="image">
                    <img v-bind:src="images.balanceWindow" alt="balanceWindow" id="balanceWindow">
                  </div>
                </div>
              </div>
            </div>
            <div class="window windowFive">
              <div class="top">
                <h3>TRANSACTIONS</h3>
                <h1>Get helpful financial context</h1>
                <p>Profile customers with transaction history and data of up to 24 months.</p>
                <button>Learn more</button>
              </div>
              <hr>
              <div class="middle">
                <p>Companies building with Transactions</p>
                <div class="logos">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                  <img v-bind:src="images.Paga" alt="logoDlocal" id="logoDlocal">
                </div>
                <div class="bottom">
                  <div class="pattern">
                    <img v-bind:src="images.hppw" alt="hppw" id="hppw">
                  </div>
                  <div class="image">
                    <img v-bind:src="images.transactionWindow" alt="transactionWindow" id="transactionWindow">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="layer-two">
            <h1>Explore core products</h1>
            <a href=""><a href="" id="underline" class="toRight">See all products</a> &nbsp;<i class="fa-solid fa-arrow-right"></i></a>
            <div class="select">
              <div @click="radioButtonOne(), identity()" class="radio-button radio-buttonOne active">
                <div class="button">
                  <div class="innerbutton"></div>
                </div>
                <p>Identity</p>
              </div>
              <div @click="radioButtonTwo(), income()" class="radio-button radio-buttonTwo ">
                <div class="button">
                  <div class="innerbutton"></div>
                </div>
                <p>Income</p>
              </div>
              <div @click="radioButtonThree(), payments()" class="radio-button radio-buttonThree">
                <div class="button">
                  <div class="innerbutton"></div>
                </div>
                <p>Payments</p>
              </div>
              <div @click="radioButtonFour(), balance()" class="radio-button radio-buttonFour ">
                <div class="button">
                  <div class="innerbutton"></div>
                </div>
                <p>Balance</p>
              </div>
              <div @click="radioButtonFive(), transaction()" class="radio-button radio-buttonFive ">
                <div class="button">
                  <div class="innerbutton"></div>
                </div>
                <p>Transaction</p>
              </div>
            </div>
          </div>
        </div>
        <div class="section-four">
          <div class="contain">
            <div class="section-four-container">
              <h1>How Okra powers businesses</h1>
              <p>A single API for multiple use cases across industries </p>
              <div class="contents">
                <div class="content">
                  <i class="fa-solid fa-hand-holding-hand" style="color: rgb(102, 236, 109);"></i>
                  <div class="texts">
                    <h5>LENDING</h5>
                    <a href=""><a href="" id="underline" class="toRight">Give out loans confidently</a> </a>
                    <p>Match Customers with sustainable
                      loans in real-time, and lower your
                      default rates.
                    </p>
                  </div>
                </div>
                <div class="content">
                  <i class="fa-regular fa-mobile" style="color: yellow; font-weight: bold;"></i>
                  <div class="texts">
                    <h5>DIGITAL BANKS</h5>
                    <a href=""><a href="" id="underline" class="toRight">Access crucial building blocks</a> </a>
                    <p>Go to market faster with preset
                      features needed to set up your digital
                      bank.
                    </p>
                  </div>
                </div>
                <div class="content">
                  <i class="fa-regular fa-layer-group" style="color: purple; font-weight: bold;"></i>
                  <div class="texts">
                    <h5>PERSONAL FINACE</h5>
                    <a href=""><a href="" id="underline" class="toRight">Design personalised experiences</a> </a>
                    <p>Build tailored finance managemnt experiences for each user with their financial information.
                    </p>
                  </div>
                </div>
                <div class="content">
                  <i class="fa-regular fa-paper-plane" style="color: yellow; font-weight: bold;"></i>
                  <div class="texts">
                    <h5>REMITTANCE</h5>
                    <a href=""><a href="" id="underline" class="toRight">Make payments with ease</a> </a>
                    <p>Leverage bank-to-bank payments to boost conversions and increase your revenue.
                    </p>
                  </div>
                </div>
                <div class="content">
                  <i class="fa-regular fa-chart-line" style="color: rgb(102, 236, 109); font-weight: bold;"></i>
                  <div class="texts">
                    <h5>BUSINESS FINACE</h5>
                    <a href=""><a href="" id="underline" class="toRight">Plan for the future</a> </a>
                    <p>Use real-time data insights to make budgeting and furtre planning decisions.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section-five">
          <div class="contentsContainer">
            <div class="contents">
              <div class="left">
                <h1>One API for all financial data</h1>
                <p>Implement any or all of Okra's products with just a few lines of code in any language</p>
                <button>Explore Okra docs</button>
              </div>
              <div class="right">
                <p>
                  <span style="color: orange;">import </span><span style="color: skyblue;">Okra </span><span style="color: orange;">from </span><span style="color: lightgreen;">'okra-js'</span><br>
                  <br>
                  <span style="color: skyblue;">Okra</span>.buildWithOptions({<br>
                  &nbsp;&nbsp;name: <span style="color: lightgreen;">'Peter the builder'</span>,<br>
                  &nbsp;&nbsp;env: <span style="color: lightgreen;">'production-sandbox'</span>,<br>
                  &nbsp;&nbsp;key: <span style="color: lightgreen;">''</span>, <span style="color: purple;">//Your key from okra dashboard</span><br>
                  &nbsp;&nbsp;token: <span style="color: lightgreen;">''</span>, <span style="color: purple;">//Your token from okra dashboard</span><br>
                  &nbsp;&nbsp;onSuccess: <span style="color: orange;">function</span>(<span style="color: skyblue;">data</span>){<br>
                  &nbsp;&nbsp;&nbsp;&nbsp;<span style="color: skyblue;">console</span>.log(<span style="color: lightgreen;">'options close'</span>)<br>
                  &nbsp;&nbsp;},<br>
                  <span class="one">&nbsp;&nbsp;onClose: <span style="color: orange;">function</span>(<span style="color: skyblue;">data</span>){&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br></span>
                  <span class="two">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: skyblue;">console</span>.log(<span style="color: lightgreen;">'options close'</span>,<span style="color: skyblue;">data</span>)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br></span>
                  <span class="three">&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;&nbsp;&nbsp;&nbsp;<br></span>
                  <span class="four">})&nbsp;&nbsp;&nbsp;&nbsp;<br></span>
                  <br>
                  <span class="five"><span style="color: skyblue;">Okra</span>.buildWithShortUrl({&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br></span>
                  <span class="six">&nbsp;&nbsp;short_url: <span>''</span>, <span style="color: purple;">//Your short url from the app builder</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br></span>
                  <span class="seven">})&nbsp;&nbsp;&nbsp;&nbsp;<br></span>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="section-six">
          <div class="contentsContainer">
            <div class="contents">
              <div class="left">
                <h1>The largest API coverage across financial institutions in Africa</h1>
                <p>Get financial information from all banks and other financial institutions in Nigeria. Currently in beta for Kenya and South Africa</p>
                <button>View coverage</button>
              </div>
              <div class="right">
                <div class="x">
                  <div class="y">
                    <img  v-bind:src="images.logo" alt="Logo" id="logo">
                    <p>Okra</p>
                    </div>
                  <div class="y y2">
                    <img  v-bind:src="images.umba" alt="Logo" id="logo">
                    <p>Umba</p>
                    </div>
                </div>
                <div class="x2">
                  <div class="y">
                    <img  v-bind:src="images.Paga" alt="Logo" id="logo">
                    <p>Paga</p>
                    </div>
                  <div class="y y2">
                    <img  v-bind:src="images.fairmoney" alt="Logo" id="logo">
                    <p>Fairmoney</p>
                    </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section-seven">
          <div class="top-right">
            <img v-bind:src="images.hpp" alt="hpp" id="hpp">
          </div>
          <div class="bottom-left">
            <img v-bind:src="images.hpp" alt="hpp" id="hpp">
            </div>
          <div class="contentsContainer">
            <div class="contents">
              <div class="top">
                <h1>Build. Eaiser. Faster.</h1>
              </div>
              <div class="bottom">
                <div class="texts">
                  <div class="count">
                    <span>
                      <number ref="number1" :from="0.0" :to="99.9"  :format="theFormat" :duration="10" :delay="3" easing="Expo.easeOut"/><span id="symbol">%</span>
                    </span>
                    <p>Bank uptime</p>
                  </div>
                  <div class="count">
                    <span>
                      <number ref="number2"  :from="0" :to="400"   :duration="10" :delay="13" easing="Expo.easeOut" /><span id="symbol">+</span>
                    </span>
                    <p>Budinesses building with Okra</p>
                  </div>
                  <div class="count">
                    <span>
                      <number ref="number2"  :from="0" :to="20"   :duration="5" :delay="23" easing="Expo.easeOut" /><span id="symbol">+</span>
                    </span>
                    <p>Integrations options</p>
                  </div>
                  <div class="count">
                    <span>
                      <number ref="number2"  :from="0" :to="10"   :duration="3" :delay="25" easing="Expo.easeOut" /><span id="symbol">+</span>
                    </span>
                    <p>Compliance audits</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section-eight">
          <div class="contents">
            <div class="left">
              <h1>Get 100 free API calls when you sign up</h1>
            </div>
            <div class="right">
              <button>Get started</button>
            </div>
          </div>
        </div>
        <div class="section-nine">
          <div class="contents">
            <div class="column-01">
              <a href=""><img v-bind:src="images.logo" alt="Logo" id="logo"></a>
              <div class="icons">
                <a href="https://github.com/burnvermin"><i class="fa-brands fa-github"></i></a>
                <a href="https://twitter.com/KoningDavid_I"><i class="fa-brands fa-twitter"></i></a>
                <a href="https://www.instagram.com/koningdavid_i/"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://www.linkedin.com/in/oluwagbemiga-david-049592165/"><i class="fa-brands fa-linkedin"></i></a>
              </div>
            </div>
            <div class="column-02">
              <p>Products</p>
              <div class="list">
                <ul>
                  <li><a href=""><a href="" id="underline" class="toRight">Authentication</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Balance</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Transactions</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Balance</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Payments</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Identity</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Income</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Links</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Selfie verifications</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Guarantors</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Spending patterns</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Revenue</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Complete view</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Pricing</a> &nbsp;</a></li>
                </ul>
              </div>
            </div>
            <div class="column-03">
              <p>Use Cases</p>
              <div class="list">
                <ul>
                  <li><a href=""><a href="" id="underline" class="toRight">Lending</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Personal finance</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Digital banks</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Remittance</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Businesse finance</a> &nbsp;</a></li>
                  <li>&nbsp;</li>
                </ul>
              </div>
              <p>Developers</p>
              <div class="list">
                <ul>
                  <li><a href=""><a href="" id="underline" class="toRight">Get started</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Developer Docs</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">API reference</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Libaries and SDKs</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Developer community</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">API status</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Okra demo</a> &nbsp;</a></li>
                </ul>
              </div>
            </div>
            <div class="column-04">
              <p>Company</p>
              <div class="list">
                <ul>
                  <li><a href=""><a href="" id="underline" class="toRight">Careers</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Customers finance</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Contact us</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Blog</a> &nbsp;</a></li>
                  <li></li>
                </ul>
              </div>
              <p>Legal</p>
              <div class="list">
                <ul>
                  <li><a href=""><a href="" id="underline" class="toRight">Developer policy</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Privacy policy</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Okra IMS</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">Cookie policy</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">End user agreement</a> &nbsp;</a></li>
                  <li><a href=""><a href="" id="underline" class="toRight">End user privacy policy</a> &nbsp;</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="section-zero">
          <p> &copy; 2022 Okra, Inc.</p>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
import bannerPattern from '../assets/banner-pattern.svg'
import bannerPattern2 from '../assets/banner-pattern2.svg'
import logo from '../assets/logo.png'
import dashboard from '../assets/hero-dash.svg'
import widget from '../assets/dlocal-widget.svg'
import blogCover from '../assets/blogCover.png'
import logoDlocal from '../assets/logo-dlocal.png'
import interswitchLogo from '../assets/interswitch_logo.svg'
import Paga from '../assets/Paga.png'
import fairmoney from '../assets/fairmoney.png'
import umba from '../assets/umba.png'
import foodcourt from '../assets/foodcourt.png'
import identityWindow from '../assets/identityWindow.svg'
import incomeWindow from '../assets/incomeWindow.svg'
import paymentWindow from '../assets/paymentWindow.svg'
import balanceWindow from '../assets/balanceWindow.svg'
import transactionWindow from '../assets/transactionWindow.svg'
import hpp from '../assets/home-products-pattern.svg'
import hppw from '../assets/home-products-pattern-white.svg'

export default {
  name: 'HomePage',
  data () {
    return {
      images: {
        bannerPattern: bannerPattern,
        bannerPattern2: bannerPattern2,
        logo: logo,
        dashboard: dashboard,
        widget: widget,
        blogCover: blogCover,
        logoDlocal: logoDlocal,
        interswitchLogo: interswitchLogo,
        Paga: Paga,
        fairmoney: fairmoney,
        umba: umba,
        foodcourt: foodcourt,
        identityWindow: identityWindow,
        balanceWindow: balanceWindow,
        incomeWindow: incomeWindow,
        paymentWindow: paymentWindow,
        transactionWindow: transactionWindow,
        hpp: hpp,
        hppw: hppw
      },
      countNum: 0
    }
  },
  created () {
  },
  mounted: function () {
    this.counter()
  },
  methods: {
    showProducts () {
      document.querySelector('.prod').classList.add('rotate')
      document.querySelector('.uCase').classList.remove('rotate')
      document.querySelector('.sDev').classList.remove('rotate')
      document.querySelector('.sComp').classList.remove('rotate')
      document.querySelector('.one').classList.add('active')
      document.querySelector('.two').classList.remove('active')
      document.querySelector('.three').classList.remove('active')
      document.querySelector('.four').classList.remove('active')
    },
    showUseCase () {
      document.querySelector('.prod').classList.remove('rotate')
      document.querySelector('.uCase').classList.add('rotate')
      document.querySelector('.sDev').classList.remove('rotate')
      document.querySelector('.sComp').classList.remove('rotate')
      document.querySelector('.one').classList.remove('active')
      document.querySelector('.two').classList.add('active')
      document.querySelector('.three').classList.remove('active')
      document.querySelector('.four').classList.remove('active')
    },
    showDevelopers () {
      document.querySelector('.prod').classList.remove('rotate')
      document.querySelector('.uCase').classList.remove('rotate')
      document.querySelector('.sDev').classList.add('rotate')
      document.querySelector('.sComp').classList.remove('rotate')
      document.querySelector('.one').classList.remove('active')
      document.querySelector('.two').classList.remove('active')
      document.querySelector('.three').classList.add('active')
      document.querySelector('.four').classList.remove('active')
    },
    showCompany () {
      document.querySelector('.prod').classList.remove('rotate')
      document.querySelector('.uCase').classList.remove('rotate')
      document.querySelector('.sDev').classList.remove('rotate')
      document.querySelector('.sComp').classList.add('rotate')
      document.querySelector('.one').classList.remove('active')
      document.querySelector('.two').classList.remove('active')
      document.querySelector('.three').classList.remove('active')
      document.querySelector('.four').classList.add('active')
    },
    hideAll () {
      document.querySelector('.prod').classList.remove('rotate')
      document.querySelector('.uCase').classList.remove('rotate')
      document.querySelector('.sDev').classList.remove('rotate')
      document.querySelector('.sComp').classList.remove('rotate')
      document.querySelector('.one').classList.remove('active')
      document.querySelector('.two').classList.remove('active')
      document.querySelector('.three').classList.remove('active')
      document.querySelector('.four').classList.remove('active')
    },
    radioButtonOne () {
      document.querySelector('.radio-buttonOne').classList.add('active')
      document.querySelector('.radio-buttonTwo').classList.remove('active')
      document.querySelector('.radio-buttonThree').classList.remove('active')
      document.querySelector('.radio-buttonFour').classList.remove('active')
      document.querySelector('.radio-buttonFive').classList.remove('active')
    },
    radioButtonTwo () {
      document.querySelector('.radio-buttonOne').classList.remove('active')
      document.querySelector('.radio-buttonTwo').classList.add('active')
      document.querySelector('.radio-buttonThree').classList.remove('active')
      document.querySelector('.radio-buttonFour').classList.remove('active')
      document.querySelector('.radio-buttonFive').classList.remove('active')
    },
    radioButtonThree () {
      document.querySelector('.radio-buttonOne').classList.remove('active')
      document.querySelector('.radio-buttonTwo').classList.remove('active')
      document.querySelector('.radio-buttonThree').classList.add('active')
      document.querySelector('.radio-buttonFour').classList.remove('active')
      document.querySelector('.radio-buttonFive').classList.remove('active')
    },
    radioButtonFour () {
      document.querySelector('.radio-buttonOne').classList.remove('active')
      document.querySelector('.radio-buttonTwo').classList.remove('active')
      document.querySelector('.radio-buttonThree').classList.remove('active')
      document.querySelector('.radio-buttonFour').classList.add('active')
      document.querySelector('.radio-buttonFive').classList.remove('active')
    },
    radioButtonFive () {
      document.querySelector('.radio-buttonOne').classList.remove('active')
      document.querySelector('.radio-buttonTwo').classList.remove('active')
      document.querySelector('.radio-buttonThree').classList.remove('active')
      document.querySelector('.radio-buttonFour').classList.remove('active')
      document.querySelector('.radio-buttonFive').classList.add('active')
    },
    identity () {
      document.querySelector('.layer-one').style.left = '24%'
    },
    income () {
      document.querySelector('.layer-one').style.left = '-59%'
    },
    payments () {
      document.querySelector('.layer-one').style.left = '-142%'
    },
    balance () {
      document.querySelector('.layer-one').style.left = '-225%'
    },
    transaction () {
      document.querySelector('.layer-one').style.left = '-308%'
    },
    theFormat (number) {
      return number.toFixed(1)
    }

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$size: 60%;

@keyframes fade-right {
    0% {
        border-bottom-width: 100%;
    }
    100% {
        border-bottom-width: 0%;
    }
}
@keyframes appear {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}
@keyframes disappear {
    0% {
        opacity: 1;
    }
    100% {
        opacity: 0;
    }
}
@keyframes x {
  100% {
    transform: translateX( calc(25vw - #{$size}) );
  }
}

@keyframes y {
  100% {
    transform: translateY( calc(50vh - #{$size}) );
  }
}
@keyframes animate {
  0% {
    background-position: -500%;
  }
  100% {
    background-position: 500%;
  }
}
@keyframes slideIn {
  0% {
    background-position: -500%;
  }
  100% {
    background-position: 0%;
  }
}

h5, p {
  color: rgb(128, 128, 128);
}
.container {
  width: 100vw;
  height: 100vh;
  .header {
    width: 100%;
    text-align: center;
    .banner {
      width: 100%;
      background-color: #000;
      display: flex;
      flex-direction: row;
      p{
        flex: 90%;
        color: #fff;
        a {
          text-decoration: none;
          color: inherit;
          margin: 0%;
          font-size: 18px;
          cursor: pointer;
        }
        #underline {
          text-decoration: none;
          color: inherit;
          margin: 0%;
          font-size: 18px;
          padding-bottom: 3px;
          display:inline-block;
        }
        .fromRight:after {
          display:block;
          content: '';
          border-bottom: solid 1px #ffffff;
          transform: scaleX(1);
          transition: transform 250ms ease-in-out;
        }
        .fromRight:hover:after {
          transform: scaleX(0);
        }
        .fromRight:after{
          transform-origin:100% 50%;
        }
        i{
          transform-origin: bottom;
          transform: rotate(45deg);
          font-size: 15px;
          padding: 0 5px;
        }
      }
    }
  }
  .menuBar.active {
    position: fixed;
    width: 100vw;
    z-index: 10;
    top: 0;
    .bodyContainer {
      box-shadow: 0px .1px 5px rgba(0, 0, 0, .1);
    }
  }
  .bodyContainer {
    position: relative;
    width: 100%;
    background-color: #fff;
  }
  .menu {
    width: 60%;
    margin: 0 auto;
    color: #000;
    font-weight: bold;
    position: relative;
    z-index: 7;
    .top {
      display: flex;
      flex-direction: row;
      padding: 2% 0;
      .left{
        margin: auto;
        img {
          width: 100px;
        }
      }
      .center {
        flex: 70%;
        ul {
          list-style: none;
          display: flex;
          justify-content: center;
          margin: 0;
          li {
            margin: 2% 2%;
            cursor: pointer;
            a{
              text-decoration: none;
              color: inherit;
            }
            i {
              transition: all 200ms ease-in;
            }
            .prod.rotate {
              transform: rotate(180deg);
              transition: all 200ms ease-in;
            }
            .uCase.rotate {
              transform: rotate(180deg);
              transition: all 200ms ease-in;
            }
            .sDev.rotate {
              transform: rotate(180deg);
              transition: all 200ms ease-in;
            }
            .sComp.rotate {
              transform: rotate(180deg);
              transition: all 200ms ease-in;
            }
          }
          li:hover {
            color: rgb(42, 173, 134);
          }
        }
      }
      .right {
        margin: auto;
        position: relative;
        z-index: 7;
        button {
          font-weight: bold;
          font-size: 18px;
          background: none;
          border: none;
          outline: none;
          padding: 15px;
          border-radius: 10px;
          cursor: pointer;

        }
        .login:hover {
          color: rgb(42, 173, 134);
        }
        .signUp {
          background-color: rgb(42, 173, 134);
          color: white;
        }

      }
    }
  }
  .menuContents {
    position: absolute;
    z-index: 3;
    width: 100vw;
    display: none;
    p{
      text-align: left;
      margin: 0;
    }
    .left {
      position: absolute;
      width: 68%;
      height: 46vh;
      background-color: #fff;
      box-shadow: 0px 25px 30px rgba(0, 0, 0, .1);
      .body {
        position: relative;
        margin-top: 7%;
        width: 70.5882%;
        margin-left: 29.4117%;
        opacity: 0;
        transition: opacity 200ms ease-out;
        .products {
          position: absolute;
          display: flex;
          flex-direction: column;
          align-items: left;
          width: 91%;
          .top {
            padding: 2% 0;
            border-bottom: 2px solid rgb(204, 204, 204);
            p {
              font-weight: bold;
            }
          }
          .bottom {
            padding: 2% 0;
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            .product {
              margin: 5% 0 1%;
              display: grid;
              grid-template-areas:
                'icons  strong'
                'icons  p'
              ;
              grid-template-columns: .2fr 1.5fr;
              grid-template-rows: 1fr 1fr;
              text-align: left;
              padding: 2% 5%;
              margin: 1;
              border-radius: 5px;
              cursor: pointer;
              i {
                grid-area: icons;
                font-size: 24px;
                padding: 0 5px;
              }
              strong {
                grid-area: strong;
                font-size: 16px;
                margin: 1% 0;
              }
              p {
                grid-area: p;
                font-size: 13px;
                margin: 2% 0;
              }
              button {
                border: none;
                outline: none;
                background-color: rgb(102, 236, 109);
                cursor: pointer;
                padding: 5px 10px;
                border-radius: 5px;
                font-weight: lighter;
                transform: scale(.8);
              }
            }
            .product:hover {
              background-color: rgb(241, 241, 241);
              transition: all 500ms ease;
            }
          }
          .footer {
            position: absolute;
            left: 0;
            top: 100%;
            margin-top: 3%;
            width: 100%;
            padding: 2% 0;
            text-align: left;
            border-top: 1px solid rgb(224, 224, 224);
            a {
              text-decoration: none;
              color: #000;
            }
            #underline {
              text-decoration: none;
              color: rgb(42, 173, 134);
              margin: 0%;
              padding-bottom: 3px;
              display:inline-block;
            }
            .toRight:after {
              display:block;
              content: '';
              border-bottom: solid 1px rgb(42, 173, 134);
              transform: scaleX(0);
              transition: transform 250ms ease-in-out;
            }
            .toRight:hover:after {
              transform: scaleX(1);
            }
            .toRight:after{
              transform-origin:0% 50%;
            }
            i {
              font-size: 10px;
              color: rgb(42, 173, 134);
            }
          }
        }
      }
    }
    .right {
      position: absolute;
      z-index: 5;
      height: 200px;
      width: 32%;
      height: 46vh;
      border-left: 1px solid rgb(116, 116, 116);
      border-left-style: dotted;
      box-shadow: 0px 25px 30px rgba(0, 0, 0, .1);
      background-image: linear-gradient(to right, rgb(230, 230, 230) , rgb(255, 255, 255));
      right: 0;
      .body {
        position: relative;
        margin-top: 13%;
        margin-left: 5%;
        opacity: 0;
        transition: opacity 200ms ease-in;
        .products {
          position: absolute;
          display: flex;
          flex-direction: column;
          align-items: left;
          width: 100%;
          .top {
            padding: 6% 0;
            border-bottom: 2px solid rgb(204, 204, 204);
            p {
              font-weight: bold;
            }
          }
          .bottom {
            padding: 2% 0;
            .product {
              margin: 5% 0;
              display: grid;
              grid-template-areas:
                'icons  strong'
                'icons  p'
              ;
              grid-template-columns: .2fr 2.5fr;
              grid-template-rows: 1fr 1fr;
              text-align: left;
              padding: 2% 5%;
              margin: 1;
              border-radius: 5px;
              cursor: pointer;
              i {
                grid-area: icons;
                font-size: 24px;
              }
              a {
                text-decoration: none;
                color: inherit;
                font-weight: bold;
                grid-area: strong;
                margin: 1% 1%;
              }
              #underline {
                padding-bottom: 3px;
                display:inline-block;
              }
              #underline:hover {
                color: rgb(42, 173, 134);
              }
              .toRight:after {
                display:block;
                content: '';
                border-bottom: solid 1px rgb(42, 173, 134);
                transform: scaleX(0);
                transition: transform 250ms ease-in-out;
              }
              .toRight:hover:after {
                transform: scaleX(1);
              }
              .toRight:after{
                transform-origin:0% 50%;
              }
              p {
                grid-area: p;
                margin: 1% 1%;
              }
            }
            .product:hover {
              transition: all 500ms ease;
            }
          }
        }
      }
    }
  }
  .menuContents.two{
    display: none;
    .right {
      .body {
        .products {
          .bottom {
            .product{
              P {
                margin-top: -4%;
                padding: 0 3px;
              }
            }
          }
        }
      }
    }
  }
  .menuContents.three{
    display: none;
  }
  .menuContents.four{
    display: none;
    .right {
      .body {
        .products {
          .bottom {
            .product{
              display: flex;
              flex-direction: column;
              justify-content: left;
              img {
                width: 70%;
              }
              .texts {
                margin: 5% 0 0;
                p {
                  font-size: 18px;
                  margin: 0 0 2%;
                }
                a {
                  color: rgb(42, 173, 134);
                  font-size: 18px;
                  margin: 0;
                  i {
                    font-size: 12px;
                  }
                }
              }
            }
          }
        }
      }
    }
  }
  .menuContents.active{
    display: block;
    .left {
      .body {
        opacity: 1;
        animation: appear 200ms;
      }
    }
    .right {
      .body {
        opacity: 1;
        animation: appear 200ms;
      }
    }
  }
  .menuContents.two.active{
    display: block;
  }
  .menuContents.three.active{
    display: block;
  }
  .menuContents.four.active{
    display: block;
  }
  .container-01 {
    width: 100vw;
  }
  .body {
    width: 60%;
    margin: 10% auto 0;
    .section-one {
      width: 100%;
      .text {
        width: 45%;
        color: inherit;
        text-align: left;
        h1 {
          font-size: 55px;
          font-weight: bolder;
          line-height: 70px;
        }
        p {
          font-size: 22px;
        }
        button {
          outline: none;
          border: none;
          background: none;
          color: black;
          padding: 15px 35px;
          cursor: pointer;
          border-radius: 5px;
          font-size: 14px;
          font-weight: bold;
        }
        #free {
          background-color: rgb(42, 173, 134);
          color: #fff;
        }
        #demo {
          border: 1px solid rgb(153, 153, 153);
          margin-left: 5%;
        }
        #demo:hover {
          background-color: rgb(241, 241, 241);
        }
      }
      #dashboard {
        position: absolute;
        right: 10%;
        top: 20%;
      }
      #widget {
        position: absolute;
        top: 30%;
        right: 35%;
      }
    }
    .section-two {
      margin-top: 10%;
      text-align: left;
      .images {
        display: flex;
        flex-direction: row;
        img {
          width: 10%;
          height: 10%;
          margin-right: 5%;
          padding: 2%;
        }
      }
    }
    .section-three {
      position: relative;
      display: flex;
      flex-direction: row;
      width: 100%;
      height: 80vh;
      z-index: 2;
      margin: 10% 0;
      overflow-x: hidden;
      .layer-one {
        position: absolute;
        display: flex;
        flex-direction: row;
        width: 250vw;
        height: 62vh;
        margin: 5vh 0;
        left: 24%;
        transition: left 500ms ease-in;
        border-radius: 20px;
        z-index: 2;
        .window {
          flex: 100%;
          position: relative;
          background-color: rgb(233, 233, 233);
          width: 41.5%;
          height: 100%;
          overflow-y: hidden;
          padding: 1%;
          margin-left: 0;
          margin-right: 2%;
          border-radius: 20px;
          text-align: left;
          .top {
            p {
              font-size: 19px;
            }
            button {
              outline: none;
              border: none;
              color: white;
              background-color: rgb(42, 173, 134);
              padding: 15px 35px;
              cursor: pointer;
              border-radius: 5px;
              font-size: 14px;
              font-weight: bold;
            }
          }
          hr {
            margin: 5% 0;
          }
          .middle {
            position: relative;
            width: 100%;
            .logos {
              width: 40%;
              position: absolute;
              text-align: right;
              top: 0;
              right: 0;
              z-index: 7;
              img {
                width: 25%;
                margin: 0 0 0 5%;
              }
            }
          }
          .bottom {
            margin-top: 3%;
            .image {
              position: relative;
              width: 100%;
              z-index: 3;
              img {
                width: 94%;
                margin: 2% 3% 0;
              }
            }
            .pattern {
              width: 100%;
              height: 20vh;
              position: absolute;
              margin-top: 23%;
              border-radius: 20px;
              background-color: rgb(255, 238, 0);
              z-index: 2;
              img {
                border-radius: 20px;
              }
            }
          }
        }
        .window.windowTwo {
          .bottom {
            .pattern {
                background-color: rgb(102, 236, 109);
            }
          }
        }
        .window.windowThree {
          .bottom {
            .pattern {
                background-color: rgb(143, 44, 255);
            }
          }
        }
        .window.windowFive {
          .bottom {
            .pattern {
                background-color: purple;
            }
          }
        }
      }
      .layer-two {
        position: relative;
        top: 0;
        width: 20%;
        height: 73vh;
        padding: 2%;
        text-align: left;
        background-color: #fff;
        z-index: 3;
        a {
          text-decoration: none;
          color: #000;
        }
        #underline {
          text-decoration: none;
          color: rgb(42, 173, 134);
          margin: 0%;
          padding-bottom: 3px;
          font-weight: bold;
          display:inline-block;
        }
        .toRight:after {
          display:block;
          content: '';
          border-bottom: solid 1px rgb(42, 173, 134);
          transform: scaleX(0);
          transition: transform 250ms ease-in-out;
        }
        .toRight:hover:after {
          transform: scaleX(1);
        }
        .toRight:after{
          transform-origin:0% 50%;
        }
        i {
          font-size: 10px;
          color: rgb(42, 173, 134);
        }
        .select {
          margin-top: 40%;
        }
        .radio-button {
          position: relative;
          cursor: pointer;
          .button {
            position: absolute;
            display: flex;
            flex-direction: column;
            justify-content: center;
            width: 20px;
            height: 20px;
            border-radius: 50px;
            transition: all 200ms ease-in-out;
            .innerbutton {
              position: relative;
              width: 12px;
              height: 12px;
              margin: auto;
              border-radius: 50px;
              background-color: rgb(155, 155, 155);
              transition: all 200ms ease-in-out;
            }
          }
          p {
            padding: 1% 0;
            margin-left: 20%;
            font-weight: bold;
          }
        }
        .radio-button.active {
          .button {
            border: 1px solid rgb(42, 173, 134);
            transition: all 500ms ease-in-out;
            .innerbutton {
              background-color: rgb(42, 173, 134);
              transition: all 500ms ease-in-out;
            }
          }
        }
      }
    }
    .section-four {
      position: relative;
      left: -33.3333333333%;
      width: 100vw;
      background-color: rgb(237, 240, 243);
      .section-four-container {
        width: 60%;
        margin: 7% auto 0;
        text-align: left;
        padding: 5% 0;
        .contents {
          display: grid;
          grid-template-columns: 1fr 1fr 1fr;
          .content {
            background-color: #fff;
            padding: 5%;
            width: 80%;
            margin: 5% 0;
            cursor: pointer;
            border-radius: 10px;
            box-shadow: 5px 5px 20px rgba(0, 0, 0, .2);
            .texts {
              width: 93%;
            }
            i {
              font-size: 50px;
            }
            h5 {
              padding: 12% 0 0;
            }
            a {
              text-decoration: none;
              color: #000;
              font-size: 18px;
            }
            #underline {
              transition: color 200ms ease-in;
              margin: 0%;
              padding-bottom: 3px;
              font-weight: bold;
              display:inline-block;
            }
            .toRight:after {
              display:block;
              content: '';
              border-bottom: solid 1px rgb(42, 173, 134);
              transform: scaleX(0);
              transform-origin:0% 50%;
              transition: transform 500ms ease-in-out;
            }
            p {
              font-size: 16px;
              line-height: 25px;
            }
          }
          .content:hover {
            #underline {
              color: rgb(42, 173, 134);
              transition: color 500ms ease-in;
            }
            .toRight:after {
              display:block;
              content: '';
              border-bottom: solid 1px rgb(42, 173, 134);
              transform: scaleX(1);
              transform-origin:0% 50%;
              transition: transform 500ms ease-in-out;
            }
          }
        }
      }
    }
    .section-five {
      position: relative;
      width: 100vw;
      left: -33.3333333333%;
      background-color: rgb(12, 50, 71);
      color: #fff;
      z-index: 3;
      .contentsContainer {
        width: 60%;
        margin: auto;
        padding: 5%;
        .contents {
          display: flex;
          flex-direction: row;
          padding: 3%;
          .left {
            flex: 50%;
            text-align: left;
            display: flex;
            padding: 2%;
            flex-direction: column;
            justify-content: center;
            p {
              color: white;
              width: 90%;
              font-size: 20px;
            }
            button {
              width: 35%;
              font-size: 18px;
              padding: 3% 2%;
              color: white;
              background-color: rgb(42, 173, 134);
              outline: none;
              border: none;
              border-radius: 5px;
              cursor: pointer ;
            }
            button:hover {
              box-shadow: 0px 0px 10px rgba(42, 173, 134, .5);
            }
          }
          .right {
            flex: 43%;
            text-align: left;
            line-height: 25px;
            padding: 2% 5%;
            border-radius: 10px;
            background-color: rgb(47, 69, 80);
            letter-spacing: 2px;
            p {
              color: yellow;
              font-size: 14px;
              .one,.two,.three,.four,.five,.six,.seven {
                margin: 0;
                width: 100%;
                background-image: linear-gradient(to right, yellow, yellow);
                overflow: hidden;
                background-repeat: no-repeat;
                background-size: 80%;
                background-clip: text;
                -webkit-background-clip: text;
                -webkit-text-fill-color: transparent;
                animation: slideIn 500ms  linear ;
                transition: animation 500ms ease-in;
              }
            }
          }
        }
      }
    }
    .section-six {
      position: relative;
      width: 100vw;
      left: -33.3333333333%;
      z-index: 2;
      background-color: rgb(238, 238, 238);
      .contentsContainer {
        width: 60%;
        margin: auto;
        padding: 0 5%;
        .contents {
          display: flex;
          flex-direction: row;
          .left {
            flex: 50%;
            text-align: left;
            display: flex;
            padding: 2%;
            flex-direction: column;
            justify-content: center;
            h1 {
              color: rgb(0, 0, 0);
            }
            p {
              color: inherit;
              width: 90%;
              font-size: 20px;
            }
            button {
              width: 35%;
              font-size: 18px;
              padding: 3% 2%;
              color: white;
              background-color: rgb(42, 173, 134);
              outline: none;
              border: none;
              border-radius: 5px;
              cursor: pointer ;
            }
            button:hover {
              box-shadow: 0px 0px 10px rgba(42, 173, 134, .5);
            }
          }
          .right {
            flex: 43%;
            height: 40vh;
            padding: 2% 5%;
            overflow: hidden;
            position: relative;
            img, div {
              width: $size;
              position: absolute;
              left: 15%;
            }
            .y2 {
              margin: 50%;
            }
            .y {
              p {
                font-size: 18px;
                background-color: #fff;
                border-radius: 20px;
                position: relative;
                display: none;
                margin: 25%;
                text-align: center;
                box-shadow: 0px 0px 10px #000;
              }
            }
            .y:hover {
              p {
                display: block;
              }
            }

            .x {
              margin-top: -20%;
              margin-left: -10%;
              animation: x 13s linear infinite alternate;
              .y {
                animation: y 7s linear infinite alternate;
              }
            }
            .x2 {
              margin-top: -20%;
              margin-left: -10%;
              animation: x 13s linear infinite alternate-reverse;
              .y {
                animation: y 7s linear infinite alternate-reverse ;
              }
            }
          }
        }
      }
    }
    .section-seven {
      position: relative;
      width: 100vw;
      left: -33.3333333333%;
      z-index: 2;
      background-color: rgb(12, 50, 71);
      .top-right {
        position: absolute;
        right: 0;
        top: 0;
        transform: rotate(180deg);
      }
      .bottom-left {
        position: absolute;
        left: 0;
        bottom: 0;
      }
      .contentsContainer {
        width: 60%;
        margin: auto;
        padding: 5% 0;
        .contents {
          .top {
            h1 {
              margin: 0;
              font-size: 70px;
              font-weight: bold;
              background: linear-gradient(to right, rgb(94, 255, 0), rgb(229, 255, 0), rgb(94, 255, 0));
              overflow: hidden;
              background-repeat: no-repeat;
              background-size: 80%;
              background-clip: text;
              -webkit-background-clip: text;
              -webkit-text-fill-color: rgba(94, 255, 0, .6);
              animation: animate 3s linear infinite;
            }
          }
          .bottom{
            .texts {
              font-size:60px;
              color: White;
              margin: 5% 0 0;
              padding: 3%;
              border-top: 1px solid #fff;
              border-bottom: 1px solid #fff;
              display: flex;
              flex-direction: row;
              justify-content: center;
              .count{
                margin: 0 5%;
                #symbol {
                  font-size: 45px;
                  margin: auto;
                  margin-left: -10%;
                  position: relative;
                }
                p {
                  margin: 0;
                  color: #fff;
                  font-size: 14px;
                }
              }
            }
          }
        }
      }
    }
    .section-eight {
      padding: 5% 0;
      .contents {
        background-color: rgb(134, 70, 255);
        padding: 5% 10%;
        position: relative;
        color: #fff;
        border-radius: 10px;
        .left{
          width: 50%;
          text-align: left;
          h1 {
            margin: 0%;
          }
        }
        .right{
          position: absolute;
          right:10%;
          top: 40%;
          margin: auto;
          button {
            position: relative;
            width: 150px;
            outline: none;
            border: none;
            padding: 10%;
            border-radius: 5px;
            font-weight: bolder;
            font-size: 16px;
            background-color: #fff;
          }
        }
      }
    }
    .section-nine {
      padding: 5% 0;
      .contents {
        padding: 5% 0%;
        position: relative;
        border-radius: 10px;
        display: flex;
        flex-direction: row;
        justify-content: left;
        p {
          font-weight: bold;
        }
            ul {
              padding: 0;
              li {
                margin: 5px 0;
                list-style: none;
                padding: 5px 0;
                a {
                  text-decoration: none;
                  color: rgb(114, 114, 114);
                }
                #underline {
                  padding-bottom: 3px;
                  display:inline-block;
                }
                #underline:hover {
                  color: rgb(42, 173, 134);
                }
                .toRight:after {
                  display:block;
                  content: '';
                  border-bottom: solid 1px rgb(42, 173, 134);
                  transform: scaleX(0);
                  transition: transform 250ms ease-in-out;
                }
                .toRight:hover:after {
                  transform: scaleX(1);
                }
                .toRight:after{
                  transform-origin:0% 50%;
                }
              }
            }
        .column-01 {
          flex: 25%;
          display: flex;
          flex-direction: column;
          justify-content: left;
          position: relative;
          img{
            width: 35%;
            position: absolute;
            left: 0;
          }
          .icons {
            margin-top: 25%;
            text-align: left;
            a {
              color: inherit;
            }
            i {
              margin-right: 5%;
            }
          }
        }
        .column-02 {
          flex: 25%;
          text-align: left;
          p {
            color: black;
            margin: 0;
          }
          .list {
            text-align: left;
          }
        }
        .column-03 {
          flex: 25%;
          text-align: left;
          p {
            color: black;
            margin: 0;
          }
          .list {
            text-align: left;
          }
        }
        .column-04 {
          flex: 25%;
          text-align: left;
          p {
            color: black;
            margin: 0;
          }
          .list {
            text-align: left;
          }
        }
      }
    }
    .section-zero {
      text-align: left;
      margin:0 0 10% 0;
    }
  }
}

</style>
