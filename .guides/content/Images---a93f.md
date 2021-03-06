Now we are going to brighten our page up with an image. Over on the left hand side, we can see some HTML code which contains an image.

It's actually very easy to add images by using the `<img>` tag. 

`src="cute.jpg"` tells the browser that the image to load in this tag is `cute.jpg` image. Try clicking on `cute.jpg` in the Filetree panel and you can see the file open up.

We'll explain `src=` in more detail on the next page.

|||info
### Image tags do not have a closing tag
Notice that there is no closing tag to match the opening tag. The `<img>` tag is one of the few tags where this is the case.

What this means is that the `img` tag is opened and closed by itself and doesn’t need an additional `</img>` to be closed when used this way.

There are a few HTML tags like this which we'll come across later.

|||

{Check It!|assessment}(test-1585508735)


|||guidance

```html
<!DOCTYPE HTML>
<html>
  <head>
      <title></title>
  </head>
  <body>
    <h1>Puppies and Kittens</h1>
    <p>Here is a cuter picture.</p>
    <img src="not-cute.jpg" alt="A cute puppy and kitten.">
  </body> 
</html>
```

|||