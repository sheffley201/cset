1. We learned web development so we could build user interfaces across all platforms. There are things we have to look out for such as making sure our website is accessible to all, like providing alternate image captions for people using a screen reader. Another part of accessibility is that we need to accommodate for all screen sizes, such as phones, tablets, desktops, and even watches. These are all relatively easy to implement and shows that building other platform specific user interfaces include all of these same things, in order to make them accessible to as many people as possible.
2. Two examples of CSS media queries are:
  a.```
  @media screen and (max-width: 400px) {
    body {
      background-color: blue;
    }
  }
  ```
  This media query will be triggered if the user's device has a screen and it's width is less than 400 (CSS) pixels. When the media query is selected, it will change the body's background color to blue.
  b.```
  @media print  {
    body {
      background-color: white;
      color: black;
      ...
    }
  }
  ```
  This media query will get triggered if the user is printing out the web page. When it gets selected, it may do things like make the background color white and the text black, among other things, to help the printer save on ink.
3. I believe it is better to define breakpoints using the specific content on your site. Device widths are all over the place nowadays, so you might miss a size you weren't aware of. Because of this, it is easier to resize your window and sprinkle in changes as they are needed. Defining device sizes and saying here are the styles for phones, tablets, and desktops might result in some unfit layouts on certain devices, so having a layout that looks best depending on the content is the best way to go.
