# tritonfest-template

BootStrap template for AS Graphic Studio use for Tritonfest event site.

## Getting Started (Designers)

* For designers: make designs which adhere to the [Figma](https://www.figma.com/file/JplyQ23KknRtXs8xDLEh41/Triton-Fest-FA22?node-id=0%3A1&t=2edQIpUHJoDFEmJD-1_)
* This will make everything fit nicely into the template

## Getting Started (Webmaster)

* The only files you need to edit are **index.html** and **style.css**
* Put all the images from the designer in the **assets/images** folder
* Read the comments within the **index.html** and **style.css** files to see where things are located
* For example, this code within **index.html** you would write or erase (depending on how many events there are) 
```
<!-- COPY PASTE THIS FOR NEW EVENTS (USE info-alt in the div's class for the alternate color [--alt-color]) -->
<a href="www.facebook.com/events/582910953475166" target="_blank">
 <div class="tf-info info-alt event-box">
  <div class="row">
   <div class="col-3"><h2>10/14</h2></div>    
   <div class="col-8"><h1>Event 4</h1></div>
  </div>
 </div>   
</a>
<!-- COPY PASTE THIS FOR NEW EVENTS (USE info-alt in the div's class for the alternate color [--alt-color]) -->
```
* Within the **style.css** file, this section lets you easly change the color of the boxes

```
/* CHANGE THESE COLORS TO MATCH YOUR THEME WITH THE FIGMA FILE */

:root {
  --background-color: #EEDFC9;
  --primary-color: #213E40;
  --secondary-color: #FFD346;
  --alt-color: #346550;
  --hover-color: #F29933;

  --gap: 0.5vw;
}
```

## Authors

[Austin Huynh](https://austinhuynh.dev/)

If you need any help, have any questions, or just want to chat, my contact info is on my site. :)

## Version History

* 0.1
    * Initial Release
    * I'm leaving the studio shortly after this so good luck future artists!


## Acknowledgments

* Melissa Ewart (ASGS's MOM)
* Alfredo Vilano (ASGS's Cool uncle)
* Juna Kim (Best deskmate ever + made the art for this)
* Rou Wen (Original site design which is the basis for the template)

 
