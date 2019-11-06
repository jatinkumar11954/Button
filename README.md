# Button
<h2>how to change image after clicking a Button ???<h2>
<h4>Discription</h4>
<p> Normal button can be easily created by using button tag and css for it can be seen in the
button{}
In this code I am using Javascript DOM to change the image after clicking a button 
<p> If you want a different image to be appeared the image link to be changed to your favour</p>
   Can also change your preferred image link <br>

In the script at the src<br>
<p>document.querySelector('.routeimg img').src = "<b>link_of_the_image</b>"</p>

Specify location of image<br>
A demo for the code which i have integrated can be view in this <br>
section of this website <a href="https://usoneinfotech.com/wp/transport/#goto">---CLICK HERE---</a>

In this we have another intresting thing to learn:--<br>
 1. we can use the id as i have set it to goto<br>
      we can to to specific section of the page without scrolling to that section just by setting an id<br>
      and by giving a link by using href="#<b>IDNAME</b>" <br>
      ex:        button href="#goto">Route No.2 </button><br>
2. Or else by using javascript code:<br>
  document.body.scrollTop = <b>number</b>;// For Safari<br>
 
document.documentElement.scrollTop = <b>number</b>;      /*For Chrome, Firefox, IE and Opera */<br>
The number is based on the height of the page it may vary fot site to site <br>

best reference would be<a href="https://www.w3schools.com/howto/howto_js_scroll_to_top.asp"> --CLICK HERE--</a><br>


 3. Media queries <b>"@media( max-width: 568px)" or "@media( min-width: 568px)"</b>    --useful to make the page responsive<br>
  by using media queries we can toggle(reduce or enlarge) the padding,margin,line height,font size and all other attributes of the    css class<br>
   to remember <br>
   When you design for desktop and want to reduce it for mobile<br>
   then in the <b>"@media( max-width: 568px)"</b> media query should use max width<br>

   and<br><br>

   when you have designed or written code for the mobile and want to change (/make responsive) for desktop <br>
   then should use<br>
   <b>"@media( min-width: 568px)"</b> min-width<br>
      
     <b> Another rule is you have to write the media query after the real css class</b><br>
      for example<br>
      .content {<br>
        display: inline-block;<br>
        /* vertical-align: top; */<br>
        position: relative;<br>
        z-index: 10;<br>
        margin: 0;<br>
        margin-left: 4%;<br>
        margin-right: 5%;<br>
        padding: 0;<br>
        width: 18%;<br>
        min-width: 170px;<br><br>

       @media (max-width: 568px) {<br>
        .content {<br>
          margin-right: 0% !important;<br>
          margin-left: 0% !important;<br>
          min-width: 160px !important;<br>
        }<br>
  
   best reference would be<a href="https://www.youtube.com/watch?v=2KL-z9A56SQ"> to watch this video click here</a>
