## Ezra Boersma - ITAS 191 #


- #### [Project Link](https://dev.itas.ca/~ezra.boersma/ITAS191/191_finalproject_ezra.boersma/index.html) # 

  
***
# Boersma Oilfields Services  # 
### Business Information and Contact Page #



This website was put together for my brother's business as a contact and information site. 
The design of this website was very much influenced by the vision of the 'client'.

The site is intended to serve as essentially a digital business card, with the added function of providing a communication relay for anyone looking to schedule a date to discuss contracting.

I chose a high-quality template that focuses on visual design. Standing out is important, so I kept the design simple and fresh, with all of the important things available right away, and the rest tucked down below, but the animations keep it kind of interesting - the different layers of content make you want to keep scrolling down.



### Validation Errors with Site #    
  

Validation errors for **HTML** files:
```
index.html: none. Successfully validated.
```
```
formpage.html: none. Successfully validated.
```


Validation errors for **CSS** files:

```
style.css: none. Successfully validated.
```
```
animate.css: none. Successfully validated.
```
```
pe-icons.css: none. Successfully validated.
```  




### CSS added to the project: #
- Inline styling for a handful of div contents, to change the text alignment to better match the bootstrap grid layout & responsive design
- Customized **all** content from the IMPACT template.
- Customized preloader gif
- Defined custom `flipInY` animation from `animate.css` in `init.js`
- Customized animations for elements on the page
- Added custom icons
- Added custom logo icons to `pe-7s` package, called 'bigjack' and 'jack'.
- Imported `Lato` Google font for local use
- Used bootstrap grid for all of the custom positioning
- Custom nav gradient and opacity colouring on form styling, for best visibility
- Added form styling CSS to `formpage.html` to override specificity on form styling from `style.css`
As well as several other changes to `style.css`, `index.html`, and `formpage.html` ...




### Colour application in this project:
 Colour scheming to match the brand/logo theme. I used the color wheel to extract colours from the logo image, and then I specifically  chose versions of the colours that sit well together, and lighten up the theme of the page - without washing it out.

 Visibility contrast has also been a large factor in the colour design. The site colour design also really keeps mobile viewers in mind with the layout.
   


### Development To-Do List

##### Features I would have liked to add: 

- Services buttons take you to the `formpage.html#form` *and* will automatically start a message with the selected service specified.
- Add email and date authentication to the form
- Finish Implementing the button to add a map div to the form page
- Information Window on map marker click
- Separate divs for services that can pop-out light a lightbox and expand to show more info
- Add different contact types buttons to team members (ie. Text Message, Messenger, Email)
- Implement call function on phone icons
- Improve overall site usefulness
- Add a date range selector for appointments, or implement a schedule widget




##### Content I would have liked to add:

- Northwest Professional Photography content to replace stock photos
- Finish importing custom icon pack and replace all icons on the page with themed ones.
- Follow-through with social media account buttons - unfreeze account status
- Wellsite locations within proximity of work area
- Expandable Services descriptions
- Add service subcategories
- Add more correlative information to the `formpage.html` footer
- Add additional contact info for each team member
- Brush up contact form div styling
- Add a hiring section
- Add certifications & safety page



### Plugins/Add-ons

Included with this bootstrap 4 template are a number of useful and fun plugins.
They add features like animation, lightboxes, and custom icons.

| Template |  
| ------ |  
| [IMPACT](https://templatemag.com/impact/) |

| Plugins/Add-ons |  
| ------ |  ------ |  
| [animate](http://daneden.me/animate) |
| [prettyPhoto](https://www.no-margin-for-errors.com/projects/prettyphoto-jquery-lightbox-clone/) |
| [Font Awesome](https://fontawesome.com/icons?d=gallery) | 
| [pe-7 Stroke Icons](https://themes-pixeden.com/font-demos/7-stroke/) |
| jQuery | 
| Bootstrap 4 |



### Work-in-Progress

#### asynchronous jQuery: On button click, create a map div by renaming another. 
>##### (Code is in `formpage.html`)


 The idea with this code is to be able to adda small map widget somewhere on the page as a way to engage the reader with the content


**Line 86 - Line 96**
```
<script>
       
        $(document).ready(function () {
            $("#btn1").click(function () {
                $("#divmap").attr("id", "mapwrapper");
                $("#divmap1").attr("id", "map");
            });

        });

    </script>
```


**Line 235 - Line 242** 
```
 <div class="gap"></div>

            <button id="btn1">This is a button</button>
            <div id="divmap">
                <div id="divmap1">

                </div>
            </div> 

```



### Course Feedback

- Had a lot of fun this semester, and I enjoyed the variety in labs.
- Some lab/lecture themes were hard to follow - and some of the reference links were broken.
- Including a bit more interactive lesson content in the online materials would be beneficial for helping individuals develop skills they are struggling with.



* * * 
&copy; Ezra Boersma 2020

