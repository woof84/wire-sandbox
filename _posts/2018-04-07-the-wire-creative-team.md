---
layout: post
title:  "Introducing the Creative Team"
date:   2018-04-07 21:15:05 +0000
image: /assets/images/art-creative-flying-17679.jpg
author: Doug
---
Ready for your next challenge? Add your profile to this post! Use the same process of forking the site, marking your changes, testing out your changes on your own version of the site, and then making a pull request.

We haven't added much in the way of directions here, so be sure to work together and get help!

There are some new things going on in the code of this post, including a mix of both `markdown` and <code>html</code>. We're also starting to leverage some of our [css framework](materializecss.com/), which is called `materialize`. We'll learn about all of these things as we continue working together - so it is ok if some of this code doesn't quite make sense yet. We'll keep exploring as we go!

You can copy and edit the following html code example:


<!-- this is a comment, we use comments to write notes that only appear in code -->
<!-- we also use comment to mark off sections of code to make things easier to read and scan -->
<!-- for example, in the code below, there is a start statement and an end statement to help us scan and read through the code. -->

<!-- Start Doug's profile -->
 <div class="col s12 offset-m2 l6 offset-l3">
        <div class="card-panel grey lighten-5 z-depth-1">
          <div class="row valign-wrapper">
            <div class="col s3">
              <img src="{{site.baseurl}}/assets/images/doug.jpg" alt="Doug's profile picture" class="circle responsive-img"> <!-- notice the "circle" class -->
            </div>
            <div class="col s9">
              <span class="black-text">
                Doug is passionately interested in how learners work together to build knowledge.
              </span>
            </div>
          </div>
        </div>
      </div>
<!-- End Doug's profile -->

<!-- Start Kian's profile -->
 <div class="col s12 offset-m2 l6 offset-l3">
        <div class="card-panel grey lighten-5 z-depth-1">
          <div class="row valign-wrapper">
            <div class="col s3">
              <img src="{{site.baseurl}}/assets/images/kian.jpg" alt="Kian's profile picture" class="circle responsive-img"> <!-- notice the "circle" class -->
            </div>
            <div class="col s9">
              <span class="black-text">
                Kian is an undergraduate Philosophy student who is fascinated by the potential for digital media to serve as an aid for learning.
              </span>
            </div>
          </div>
        </div>
      </div>
<!-- End Kian's profile -->

<!-- Start Kian's test profile -->
<ul class="collapsible" data-collapsible="expandable">
    <li>
    <div class="collapsible-header row z-depth-1 hoverable blue grey lighten-5">
       <div class="row valign-wrapper">
          <div class="col s3">
             <img src="{{site.baseurl}}/assets/images/kian.jpg" alt="Kian's profile picture" class="circle responsive-img"> 
          </div>
          <div class="col s9">
             <span class="black-text">
                Kian is an undergraduate Philosophy student who is fascinated by the potential for digital media to serve as an aid for learning.
             </span>
          </div>
       </div>
    </div>
    <div class="collapsible-body">
       <iframe width="90%" height="400" src="https://www.youtube.com/embed/sH9h4xkY4ys" frameborder="0" allowfullscreen</iframe>
    </div>
    </li>
<!-- End Kian's test profile -->
