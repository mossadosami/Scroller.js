# Scroller.js
<header class="header">
  <div class="container">
    <div class="row "  >
      <div class="col-lg-8 col-lg-push-2 text-center">
        <h1  moel-ani-data="fadeInUp after-0-5s for-0-5s" >Scroller.js v1</h1>
        <h2  moel-ani-data="fadeInUp after-0-5s for-0-5s" >by Mosaad Osami</h2>
        <p class="lead"  moel-ani-data="fadeInUp after-0-5s for-0-5s" ><strong>The only 2K file and the easiest Way ever to animate your page on scroll!</strong><br>
          <br>
          NO hassel NO wierd stuff, <br>
          just add ONE attribute to animate your page on Scroll.</p>
        <form class="form-inline" role="form">
          <br>
          <p  moel-ani-data="fadeInUp after-0-5s for-0-5s" >Download from git</p>
          <button type="submit" class="btn btn-lg btn-default"  moel-ani-data="fadeInUp after-0-5s for-0-5s" >DOWNLAOD</button>
        </form>
      </div>
    </div>
  </div>
</header>
<main class="content"> 
  
  <!-- Lead -->
  <section class="container space-before space-after "  >
    <div class="row">
      <div class="col-sm-10 col-sm-push-1">
        <div moel-ani-data="fadeInDown after-0-5s for-0-5s">
          <h1 class="text-center">What it's all about</h1>
          <p class="lead text-center"> This just do the job, add animation to the HTML elements on Scroll <br/>
            depending on Animate.css and jquey. </p>
        </div>
        <div>
          <h1 class="text-center big-margin"   moel-ani-data="fadeInDown after-1s for-1s">Why it's that simple</h1>
          <p class="lead text-center"   moel-ani-data="fadeInDown after-1s for-1s"> because you need only two steps: </p>
          <ol>
            <li   moel-ani-data="fadeInDown after-1s for-1s">Add these links to your page &lt;head&gt;<br/>
              <code>&lt;link rel=&quot;stylesheet&quot; href=&quot;http://s.mlcdn.co/animate.css&quot;&gt;<br/>
              &lt;script src=&quot;https://code.jquery.com/jquery-2.2.4.js&quot;&gt;&lt;/script&gt;<br/>
              &lt;script src=&quot;https://cdnjs.cloudflare.com/Scroller.js&quot;&gt;&lt;/script&gt; </code></li>
            <li   moel-ani-data="fadeInDown after-1s for-1s"> Add attribute  moel-ani-data= and its values as below. <br/>
              <code> &lt;h1 moel-ani-data=&quot;fadeInUp after-1s for-1s&quot; &gt;&lt;/h1&gt; </code> </li>
          </ol>
        </div>
        <div   moel-ani-data="fadeInRight after-1s for-1s">
          <h1 class="text-center big-margin">How to Customize?</h1>
          <p class="lead text-center"> Only in three steps: </p>
          <ol>
            <li    moel-ani-data="fadeInDown after-1s for-1s"> <b>Animation type</b><br/>
              you can use all class on <a href="https://github.com/daneden/animate.css">Animate.css</a><br/>
              <code>&lt;h1 ... moel-ani-data=&quot;<b>fadeInUp</b> ...&quot; &gt;&lt;/h1&gt;</code> </li>
            <li   moel-ani-data="fadeInDown after-1s for-1s"> <b>Animation delay </b>(start animation after 1 sec or 2 sec ...)<br/>
              <code>&lt;h1 ... moel-ani-data=&quot;...<b>after-1s</b> ...&quot; &gt;&lt;/h1&gt;</code> Check the other options:<br/>
              after-0-5s<br/>
              after-1s<br/>
              after-1-5s<br/>
              ...<br/>
              after-5-5s </li>
            <li   moel-ani-data="fadeInDown after-1s for-1s"> <b>Animation duration</b><br/>
              <code>&lt;h1 ... moel-ani-data=&quot;...<b>for-1s</b>&quot; &gt;&lt;/h1&gt;</code> Check the other options:<br/>
              for-0-5s<br/>
              for-1s<br/>
              for-1-5s<br/>
              ...<br/>
              for-5-5s </li>
          </ol>
        </div>
      </div>
    </div>
  </section>
  <!-- /Lead --> 
  
  <!-- Features -->
  <section class="container space-before">
    <div class="row featurelist space-after">
      <div class="col-md-5 col-sm-6 col-md-push-1 "   moel-ani-data="fadeInLeft after-0-5s  for-0-5s"> <img class="img-feature img-responsive" src="assets/images/screen1.png" alt="Sample image"> </div>
      <div class="col-md-5 col-md-push-1 col-sm-6  "   moel-ani-data="fadeInRight after-0-5s  for-0-5s" >
        <h2 class="space-before">Upcoming features Super Awesome version 1.5! yay</h2>
        <ul>
          <li>Now it's only entrance version (On page load, elements is hidden then appears and animates by scroll). The next existence version the element is not hidden by default, the scroll triggers the animation itself on existed element.</li>
          <li>Using multiple animations and time options on the same element.</li>
        </ul>
      </div>
    </div>
  </section>
  <!-- /Features --> 
  
</main>
