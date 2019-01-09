Row Column Layout Css
=====

[Website & Docs](https://darongaron.github.io/rc-layout/)

Quick Start
-----------

```console
git clone --depth 1 https://github.com/darongaron/rc-layout.git
```

Edit my-site.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <title>my-site</title>
  <link rel="stylesheet" href="rc-layout/dist/rc-layout.css">
</head>
<body>
  <h1>my-site</h1>
  <div class="container">
    <div class="row">
      <div class="col" style="width: 20%; background-color: #fee;">one</div>
      <div class="col" style="width: 50%; background-color: #efe;">two</div>
      <div class="col" style="width: 30%; background-color: #eef;">three</div>
    </div>
  </div>
</body>
</html>
```

IE8 support of media queries
----------------------------

Internet Explorer 8 requires the use of [Respond.js](https://github.com/scottjehl/Respond) to enable media query support.


