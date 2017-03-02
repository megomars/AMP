#Getting started with AMP
The following page will get you started with accelerated mobile pages (AMP).
Why AMP? Because speed should be a core feature of a mobile website.
A slow site equals a bad user experience and a bad user experience results in a non-returning visitor.
Stats have shown that 40% of users drop off after 3 seconds if the page has not loaded.

1. ##Opening tags
			```
		
		<!doctype html>
		<html amp lang="en">
		  <head>
		    <meta charset="utf-8">
		    <script async src="https://cdn.ampproject.org/v0.js"></script>
		    <title>THE MATRIARCHS OF MTHATHA | Al Jazeera English</title>
		    <link rel="apple-touch-icon" sizes="400x400" href="images/favicon.png">
		    <link rel="icon" type="image/png" sizes="400x400" href="images/favicon.png">
		    <link rel="shortcut icon" href="images/favicon.ico">
		    <link rel="canonical" href="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/index.html" />
		    <meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
		    <script async custom-element="amp-social-share" src="https://cdn.ampproject.org/v0/amp-social-share-0.1.js"></script>
		    <script async custom-element="amp-carousel" src="https://cdn.ampproject.org/v0/amp-carousel-0.1.js"></script>
		    <script async custom-element="amp-analytics" src="https://cdn.ampproject.org/v0/amp-analytics-0.1.js"></script>
		    <script async custom-element="amp-apester-media" src="https://cdn.ampproject.org/v0/amp-apester-media-0.1.js"></script>
		    <script async custom-element="amp-vimeo" src="https://cdn.ampproject.org/v0/amp-vimeo-0.1.js"></script>
		    <script type="application/ld+json">
		      {
		        "@context": "http://schema.org",
		        "@type": "NewsArticle",
		        "headline": "Open-source framework for publishing content",
		        "datePublished": "2015-10-07T12:02:41Z",
		        "image": [
		          "logo.jpg"
		        ]
		      }
		    </script>
		    
		```
2. ##Metadata tags
			```
   		 <meta name="author" content="Al Jazeera"/>
   		 <meta property="og:title" content="THE MATRIARCHS OF MTHATHA"/>
    		 <meta property="og:description" content="Almost 1.5 million or 11% of all households in South Africa are now run by women over the age of 60."/>
   		 <meta property="title" content="THE MATRIARCHS OF MTHATHA"/>
    		 <meta property="description" content="Almost 1.5 million or 11% of all households in South Africa are now run by women over the age of 60."/>
  		 <meta property="og:type" content="article.other"/>
   		 <meta name="twitter:card" content="summary_large_image"/>
	    	 <meta name="twitter:site" content="@AJEnglish"/>
    		 <meta property="twitter:title" content="THE MATRIARCHS OF MTHATHA"/>
   		 <meta property="twitter:description" content="Almost 1.5 million or 11% of all households in South Africa are now run by women over the age of 60."/>
   		 <meta property="image" content="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/outside.jpg"/>
   		 <meta property="twitter:image:src" content="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/outside.jpg"/>
   		 <meta property="og:image" content="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/outside.jpg"/>
   		 <meta name="image" content="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/outside.jpg">
   		 <meta name="title" content="THE MATRIARCHS OF MTHATHA" >
   		 <meta name="description" content="Almost 1.5 million or 11% of all households in South Africa are now run by women over the age of 60.">
   		 <style amp-boilerplate>body{-webkit-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-moz-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-ms-animation:-amp-start 8s steps(1,end) 0s 1 normal both;animation:-amp-start 8s steps(1,end) 0s 1 normal both}@-webkit-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-moz-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-ms-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-o-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}</style><noscript><style amp-boilerplate>body{-webkit-animation:none;-moz-animation:none;-ms-animation:none;animation:none}</style></noscript>
		```

3. ##Style
			```
		<style amp-custom>
      body {
      background-color: white;
      margin: 0 auto;
      }
      amp-img {
      background-color: gray;
      }
      .container, header {
      display: block;
      margin: 0 auto;
      max-width: 600px;
      }
      .containimage{
          float:left;
      }
      .imagecaption{
        text-align: right;
      }
      .bg {
        background-image: url('images/topfacessmall.gif');
        background-repeat: repeat-x;
        background-attachment: fixed;
        background-position: center top;
        /*background-size:cover;*/
        height: 200px;
        text-align: center;
        color: #ffffff;
      }
      .brand-logo p {
      color: #666666;
      font-size: 16px;
      font-family: arial;
      }
      blockquote p,
      body {
      margin: 0;
      font-family: Georgia
      }
      h1,
      h2,
      h5 {
      font-family: Georgia
      }
      h1 {
      font-size: 48px;
      margin: 10px 0;
      font-weight:700;
      line-height: 100%;
      color:#333333;
      text-align:center;
      }
      h2 {
      font-size: 24px;
      margin-top: 20px;
      margin-bottom: 20px
      }
      h5 {
      color: #fa9000;
      font-size: 14
      }
      p a {
      color: #fa9000;
      text-decoration: none;
      font-weight: normal;
      }
      p {
      line-height: 1.5;
      font-size: 18px;
      margin-top: 0
      }
      footer {
      align-items: center;
      justify-content: center;
      background: #333333;
      margin-top: 20px;
      padding: 15px;
      }
      .stories{
        align-items: center;
        justify-content: center;
        background: #333333;
        margin-top: 20px;
        padding: 15px;
        background:#eeeeee;
      }
      blockquote p {
      font-size: 24px;
      color: #6c6b6c;
      margin: 0 0 20px 5px
      }
      .article-body {
      margin: 20px 15px;
      }

      blockquote {
        background: #eee;
        border-left: 15px solid transparent;
        margin: 1.5em 0px;
        line-height: 150%;
        padding: 1em 10px;
        padding-left:70px;
        quotes: "\201C""\201D""\2018""\2019";
        font-family: georgia;
        font-style: italic;
        position: relative;
        font-size: 1.4em;
        -webkit-border-image: url("images/beadsplitleft.jpg") 30 stretch; /* Safari 3.1-5 */
        -o-border-image: url("images/beadsplitleft.jpg") 30 stretch; /* Opera 11-12.1 */
        border-image: url("images/beadsplitleft.jpg") 30 stretch;
      }

      blockquote:before {
        display: block;
        padding-left:10px;
      color: #283469;
      position: absolute;
      left: -5px;
      top:56px;
      content: "\201C";
      font-size: 5em;
      line-height: 0.1em;
      }
      blockquote p {
      display: block;
      }
      a#hamburger {
        float: right;
        padding: 22px;
      }
      footer img {
        background: #333333;
      }

      .socialbutton1{
        float:right;
        margin-top:15px;
      }

      .socialbutton2{
        float:right;
        margin-top:15px;
        margin-right:5px;
      }
      .ajlogo{
        width: 175px;
        height: 60px;
      }
  		</style>
			```
4. ##Social sharing buttons
			```
					<amp-social-share  width="60" height="44" class="socialbutton1" type="whatsapp" data-param-text="THE MATRIARCHS OF MTHATHA" data-param-url="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/index.html"></amp-social-share>
          <amp-social-share  width="60" height="44" class="socialbutton2" type="twitter" data-param-text="THE MATRIARCHS OF MTHATHA" data-param-url="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/index.html"></amp-social-share>
          <amp-social-share  width="60" height="44" class="socialbutton2" type="facebook" data-param-url="THE MATRIARCHS OF MTHATHA" data-param-url="http://interactive.aljazeera.com/aje/2017/south-africa-grandmothers/index.html"></amp-social-share>
		```

5. ##Responsive images
			```
			<amp-img src="images/landgif.gif" layout="responsive" alt="" height="338" width="600"></amp-img>
			```
6. ##Blockquotes
			```
			<blockquote>We, as women of this area, took a decision to support one another - <strong>Nozukhile Hadi</strong> </blockquote>
		 ```
7. ##Vimeo videos
			```
			<amp-vimeo
        data-videoid="205344910"
        layout="responsive"
        width="500" height="281">
    </amp-vimeo>
		  ```
8. ##Carousel
			```
		<amp-carousel id="carousel" width="800" height="667" autoplay controls layout="responsive" type="slides">
          <amp-img src="images/kids.jpg" layout="responsive" alt="" height="667" width="800"></amp-img>
          <amp-img src="images/farming.jpg" layout="responsive" alt="" height="667" width="800"></amp-img>
          <amp-img src="images/women.jpg" layout="responsive" alt="" height="667" width="800"></amp-img>
    </amp-carousel>
		```
9. ##Quiz
			```
		<amp-apester-media
        height="390"
        data-apester-media-id="58aab4d23d7ca9a841f32966">
    </amp-apester-media>
		```

10. ##amp-analytics
		```
		<amp-analytics type="chartbeat">
    <script type="application/json">
        {
            "vars": {
                "uid": "3291",
                "domain": "aljazeera.com",
                "sections": "South Africa, Unemployment"
            }
        }
    </script>
    </amp-analytics>
    <amp-analytics type="googleanalytics" id="analytics1">
    <script type="application/json">
    {
      "vars": {
        "account": "UA-1615344-7"
      },
      "triggers": {
        "trackPageview": {
          "on": "visible",
          "request": "pageview"
        }
      }
    }
    </script>
    </amp-analytics>
		```
