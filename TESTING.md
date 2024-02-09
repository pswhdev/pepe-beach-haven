# Testing 

A series of manual tests were conducted to ensure the robust functionality and usability of the website. Each project feature, like navigation menu, links and form submissions were carefully examined to ascertain its proper operation and alignment with user needs.

The testing in different  browsers and diverse computers and mobile devices of different sizes and models show the website works reliably and effectivelly, providing users with a smooth navigation experience. The website is fully responsvive resizing the content of all pages according to the devices's screen sizes as can be seen on the images below.

### The home page:
![Responsive home](documentation/am-i-responsive-index-two.png)

### The accommodation page:
![Responsive accomodation](documentation/am-i-responsive-accommodation.png)

### The FAQ page:
![Responsive faq](documentation/am-i-responsive-faq.png)

### The contact us page:
![Responsive contact us](documentation/am-i-responsive-contact.png)

### The thank you page:
![Responsive thank you](documentation/am-i-responsive-thankyou.png)

## Fixed bugs
During the test phase a few bugs were detected and corrected accordingly:
1. The logo and the logo text wouldn't align nicely, so after trying numerous approaches the problem was fixed by using `position: relative;` and definig the distance to the bottom `bottom: 16px;` for the logo's text;
2. The nav toggle showed the same missalignment and the same approach was used to fix it;
3. The mountain of the landing photo would be cropped on very large screens (1600px) and it didn't look as good. To fix the problem a media query was created for very large screens with a rule with a larger the height for the image;
4. The background color of the containers on the reasons section as well as the container that groups the photos on the accommodation page and the container of the form on contact and the message on the "thank you" pages didn't offer enough contrast making the text difficult to read. To fix this issue, the transparency was reduced and it created more contrast while still adding a nice look on the pages;
5. The embedded Google Maps would not cover the width of the page. The fix for the problem was to set a ` width: 100%;` on a css rule for the iframe element;
6. The photos on the accommodation page were not displaying nicely when looked on larger screens. To remediate the situation, the order of the room's photos was changed using the css "order" property.
7. During the Mid-Point Project Review call with my mentor it was pointed out that the contact us form could be submitted with an empty space on the First name and Last name fields,even though the "required" property was present in the input elements. After looking online on how to solve the problem, the following solution was found on the [Stackoverflow website](https://stackoverflow.com/questions/13766015/is-it-possible-to-configure-a-required-field-to-ignore-white-space) and the following attributes were added to the input elements: `required pattern=".*\S+.*" title="This field is required"`.
8. The navigation menu was not nicely aligned when the site was visited using the Mozilla Firefox browser.



## Known bugs
1. The fix for problem 7 didn't work 100% on the textarea input field. It does stop the message from beign sent without any character beign typed, but doesn't stop it from being sent with a space. So far I couldn't find a solution for this problem using exclusively html language and I believe the use of aditional programming, using JavaScript would be necessary to fix this problem.


## Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Findex.html)
  (https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Faccommodation.html)
  (https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Ffaq.html)
  (https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Fcontact.html)
  (https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Fthank.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 