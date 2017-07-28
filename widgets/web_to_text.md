# Web to Text

The __web to text__ widget allows your site visitors to text your Skipio account from within a web browser.

Here's an example integration.

```html
<html>
  <head><title>Your Site</title></head>
  <body>
    <!-- your site content ... -->
  
    <!-- place this line where you'd like the widget to show on your site -->
    <script·type='text/javascript'·src='https://app.skipio.com/scripts/web2txt/123456789'></script>
  
    <!-- your site content ... -->
  </body>
</html>
```

The format of the JavaScript URL matches the following pattern.

```
https://app.skipio.com/scripts/web2txt/123456789
                                  |       |
                                  |       |- Your Skipio account's widget token 
                                  |
                                  |- The Skipio widget id
```

You can find your widget token on your Skipio user profile. https://app.skipio.com/users/edit
