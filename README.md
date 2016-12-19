# hero-featured-video
With the increasing amount of video content online, organizations are increasingly using video to engage with website visitors. Conversation rates on the use of a video in the top level of your website are much higher than say a hero with text and graphics. In this article, [Solodev](https://www.solodev.com/) will show you how to add a hero to your homepage with a featured video.

## Tutorial

For detailed instructions, view Solodev's [Creating a Homepage Hero with a Featured Video](https://www.solodev.com/blog/web-design/creating-a-homepage-hero-with-a-featured-video.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/6t25ebsq/).

## HTML

This tutorial contains the following HTML markup.

```
<div class="hero-content">
   <div class="row">
      <div class="col-md-6">
         <div class="well">
            <h2>Reach the right customers.</h2>
            <p>With advanced targeting by MicoCorp, you can reach the right customer at the right place at the right time. Jumpstart your marketing efforts today with MicroCorp!</p>
            <br>
            <button class="btn btn-success center-block" target="_blank">
            Launch Now!
            </button>
         </div>
      </div>
      <div class="col-md-6">
         <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/9R0GT5Dyihk"></iframe>
         </div>
      </div>
   </div>
</div>

```
## CSS

All necessary CSS is included in the file featured-video.css

## External Includes

This tutorial contains the following third party resources.

```
<link rel="stylesheet" href="featured-video.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
