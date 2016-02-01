# Product Landing Page

**Product Landing Page** is for showcasing any saas based product with pricing, features, and testimonials.

## Features

**Product Landing Page** consists of a flat style landing page promoting a digital product, with a simple CTA button to register for a Slack group.
![screencast](http://g.recordit.co/LwrTP6HFQb.gif)

Some sections of the index.html contain nice JS transitions to reveal content like the testimonials below. 
![screencast](http://g.recordit.co/PHHCzVULZd.gif)

![screencast](http://g.recordit.co/0EG88azNyE.gif)

## Installation

Upload the code and assests to your server, then modify the appearence, links, Google Analytics 

Google Analyics JS Script
```ruby
  <script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', '', 'auto');
  ga('send', 'pageview');

</script>
```

Twitter Follow Button Script
```ruby
<script>window.twttr = (function(d, s, id) {
            var js, fjs = d.getElementsByTagName(s)[0],
            t = window.twttr || {};
            if (d.getElementById(id)) return t;
            js = d.createElement(s);
            js.id = id;
            js.src = "https://platform.twitter.com/widgets.js";
            fjs.parentNode.insertBefore(js, fjs);
 
            t._e = [];
            t.ready = function(f) {
            t._e.push(f);
            };
 
        return t;
}(document, "script", "twitter-wjs"));
</script>
```

##Web based

**Product Landing Page** is implemented in **HTML, CSS, JS**.

## Dependencies

None.

## Creator

Nicholas Ivanecky ([@ivantr0n](http://twitter.com/ivantr0n)), To visit all my works visit ([www.ivantron.com](http://www.ivantron.com))



