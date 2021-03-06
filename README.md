<!DOCTYPE html>
<html>

<header>
<h2><b>Short Readme document about Headless Browsers</b></h2>
</header>

<body>
<p>Each Browser has own specific behaviour of the test automation.</p>

<h3>Firefox and Chrome do not have a big difference :trollface: in the automated testing:</h3>
<div>
<p>:pushpin: <i>Geckodriver</i> is required for the <b>Firefox</b> and <i>chromedriver</i> is required for the <b>Chrome</b> browser.</p>
<p>:pushpin: Make sure that you have set the path of each driver. It is required for running tests as well.</p>
<p>:pushpin: You need to import <b>options</b> and add <b>--headless</b> argument.</p>
</div>
<br>
           <div align="center">
           <a href="https://github.com/SviatoslavBordovski/Headless_Browsers_Automation"><img alt="headless-browser" src="https://www.multidots.com/wp-content/uploads/2018/07/Headless-browser.jpg" width="300" height="160" margin="15px" hspace="30"></a>
           <a href="https://github.com/SviatoslavBordovski/Headless_Browsers_Automation">
            <img alt="headless-browser" src="https://miro.medium.com/max/3440/0*WHo7bG8yHKyt_nzn.png" width="300" height="160" margin="15px" hspace="30"></a>
           </div>
           <br>
           <div>
           <p align="left">
            <h4>:stars: How it looks for the Chrome browser</h4>
            <code>chrome_options = Options()</code>
            <br>
            <code>chrome_options.add_argument('--headless')</code>
            <br>
            <h4>:fox_face: and for the Firefox browser...</h4>
            <code>firefox_options = Options()</code>
            <br>
            <code>firefox_options.add_argument('--headless')</code>
           </p>
           </div>
<br>
<div>
<h3>:bulb: Advantages of using <b>headless</b> browser testing approach are:</h3>
<br>
<ol>
   <li>Better test performance compared to browser automation.</li>
   <li>Time consuming tests would run less as a result because headless browsers run faster.</li>
   <li>Opportunity to run tests on a system which doesn’t have a browser or for the app that does not have a GUI.</li>
   <li>Scrape website without a render of the full browser, you just need to compare some data, prices for instance.</li>
   <li>It could be a part of TDD that is very interesting and effective approach in web automation testing.</li>
</ol>
</div>
<div>
<h3>:point_up: Popular Headless Browsers:</h3>
<ul>
   <li>Google <a href="https://developers.google.com/web/tools/puppeteer/">Puppeteer</a> - the Headless Browser Puppeteer is    a Node library. It gives you a high-level API to control headless Chrome or Chromium over the DevTools Protocol. It also      can also be tweaked to use full (non-headless) Chrome or Chromium</li>
   <li>Google Chrome since version 59</li>
   <li>Firefox versions 55 and 56</li>
   <li><a href="http://htmlunit.sourceforge.net/">HtmlUnit</a> is a “GUI-Less browser for Java programs”. It models HTML        documents and provides an API that allows you to invoke pages, fill out forms, click links, etc… just like you do in          your “normal” browser</li>
   <li><a href="https://splinter.readthedocs.io/en/latest/">Splinter</a> is a headless browser Python-centric option.  It's      open-sourced browser and is used for testing web applications using Python.  For example, you can use it to automate browser actions, such as visiting URLs and interacting with their items</li>
</ul>
</div>
</body>
</html>
