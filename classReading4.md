IMAGES

we can add the page image to page by using <img> and it has no closing tag
we can find images from these websites:
www.istockphoto.com
www.gettyimages.com
www.veer.com
www.sxc.hu
www.fotolia.com
Always good to be well organized so that keep your images in a different folder and
keep it organize.
<img src="path of image file" alt="provide text description title ="gives information about image"/>
We can place to image before ,inside paragraph.It can also can be middle of a paragraph
   it is better to make alignment with css
   align ="left"-->text flows right side of image
   align="right" --> text flows right side of image
   align ="top" -->first line of the text near the appears top of image, and rest of the text will be in the under the image
   align ="middle" -->first line of the text will be middle of the image, and rest of the text will be in under the image
   allign ="bottom" -->first line of the text will be bottom of the image, and rest of the text will be in under the image
There are three rules to creating images
 -- generally jpeg,gif,png are used. We should chose the right format because otherwise it may slow down to web page.
    jpeg--> if picture have many colors use it.
    gif ,png -->if image has few color and if large area has same color use it.
 -- size is also important.
 -- while measuring the image, use pixels.
 To edit images you can use these websites:
 www.photoshop.com
 www.pixlr.com
 www.splashup.com
 www.ipiccy.com
 <figure> -->contains image and its captions, figure groups the image and caption
 <figcaption> -->it keeps caption of image
  -----------------------------------------------------------------------------------------
  COLOR
  Color specifies the text color.
  There are three types of expressing color
  ---color:Blue;
  ---color:#ee9221;
  ---color:rgb(100,120,111) ;
  back ground color is changes background color of block
  its important to choosing background and foreground color. They need to be contrast.
  --background-color:rgba(0,0,0,0) last value specify the opacity.
  -- background-color:hsla(0,100%,100%,0,5); also specify color.
  -------------------------------------------------------------------------------------------------
  TEXT
  there are many typeface. Typefaces will be shown in page if user installs  that typeface.
  Serif--> if pasages are long,we should use it.
  sans-serif--> if the text is small, we use it.
  monospace-->  makes align of text well.

  Font-family:Arial; ---> specify typeface
  font-size:200% -->specify size the fonts

  we use pixel,percentages or ems to setting size of font.
  font-weight:normal||bold
  font-style:italic||normal||oblique

  we can convert to text lower case to uppecase with text-transform:uppercase;
  text-decoration:none||underline||overline||line-through||blinkd
  line-height:1.4m --> we can change the line height
  word-spacing:1em; -->control the space between word
  text-align:left||right||center||justify -->make  the text align
  vertical-align:baseline||sub||super||top||text-top||middle||bottom||text-bottom
  vertical-align generally works in table cells.
  text-indent:20px --> can be also used negative numbers.
  text-shadow:1px 1px #111111 -->takes length, color and drop
  text-decoration:none||underline||
  a:link{} -->  set styles of unvisited link
  a:visited{} --> set styles of visited link
  a:active{} --> gives a feels that you clicked button or link
  input.submit:hover{} --> changes aperance of link or button when user place their mouse
  input.submit:active{} -->changes aperance of link or button when user clicked the link
  input.text.focus{}
