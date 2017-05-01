# HTML-CSS-jQuery

# Important links to follow!

- [https://flatuicolors.com/] = Just Click and Pick. At the top there are many options for color mode.
- [https://dribbble.com/] = Wonderful design palettes
- [https://daneden.github.io/animate.css/] = Great Site for css only animations
  tutorial /------/ How to use it? : [https://www.youtube.com/watch?v=QYQ0I1mvFDE] and
  [https://www.youtube.com/watch?v=CBQGl6zokMs]
  To include file (animate.css) link it as another stylesheet
  ```
  <head>
    <link href="style/animate.css" rel="stylesheet"/>
  </head>
   <!--Use CDN-->
   <head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
   </head>
  ```
  For CSS
  ```
  /*Original Statement*/
  <button type="button" class="btn-register" id="click-register">Register</button>
  /*With stylesheet of animate.css*/
  <button type="button" class="btn-register animated rollIn" id="click-register">Register</button>
  ```
  For jQuery:
  ```
  $('#yourElement').addClass('animated bounceOutLeft');
  ```

# HTML-CSS-jQuery Example Repository

- Collapsing Header
- Hover Effect via CSS
- Slide over menu
- Drop Down Menu

# Collapsing Header

This will fix header and keep it top of the stack, fix banner with content scrolling under header.

[https://github.com/adityasingh11/HTML-CSS-jQuery/tree/master/Collapsing%20Header]

# Hover Effect

Suppose you define a div container and gave it an id as "alpha"
```
alpha{
  background-image = url("space-picture.jpg");
}
```

To apply hover effect on this you just have to add colon and hover keyword

```
alpha:hover {
  background-image = url("pool-picture.jpg");
}
```

So now when you take your mouse at space-picture.jpg it will change to pool-picture.jpg image.

# Slide over Menu

A simple toggle button to slide open the menu and close it.

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script type="text/javascript">
        window.jQuery || document.write("<script src='jquery-3.2.1.js'><\/script>");
    </script>
    <script type="text/javascript">
        $(function(){
            $(".nav-toggle").on("click",function(){
                $(".main-navigation").toggleClass("open");
            });
        });
    </script>
```

# Drop Down Menu

An abstract concept code is uploaded.

Tutorial: [https://www.youtube.com/watch?v=AIdslaUj9wg]
