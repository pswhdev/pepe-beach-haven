# Pepe Beach Haven Testing

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [JavaScript Validator](#javascript-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

A series of manual tests were conducted to ensure the robust functionality and usability of the website. Each project feature, like navigation menu, links and form submissions were carefully examined to ascertain its proper operation and alignment with user needs.

The testing in different  browsers and diverse computers and mobile devices of different sizes and models show the website works reliably and effectivelly, providing users with a smooth navigation experience.

Visit the deployed site: [Pepe Beach Haven](https://pswhdev.github.io/pepe-beach-haven/)

## Responsiveness test

- Responsiveness tests were conducted manually by accessing the live website using different computer, browsers and mobile devices.

- The website is fully responsvive resizing the content of all pages according to the devices's screen sizes as can be seen on the images below.

    - The home page:
![Responsive home](documentation/am-i-responsive-index-two.png)

    - The accommodation page:
![Responsive accomodation](documentation/am-i-responsive-accommodation.png)

    - The FAQ page:
![Responsive faq](documentation/am-i-responsive-faq.png)

    - The contact us page:
![Responsive contact us](documentation/am-i-responsive-contact.png)

    - The thank you page:
![Responsive thank you](documentation/am-i-responsive-thankyou.png)


## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

- HTML:

  - No errors were returned when passing through the official W3C validator:

    - [Home page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Findex.html)

    - [Accommodation page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Faccommodation.html)

    - [Faq page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Ffaq.html)

    - [Contact page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Fcontact.html)

    - [Thank you page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Fthank.html)
  
- CSS:

  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fpswhdev.github.io%2Fpepe-beach-haven%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

  
### Lighthouse tests:
- All pages were tested using the Lighthouse feature on Dev Tools from Google Chrome. The results can be seen on the pictures below. The pictures with a black backgroung are the results of tests conducted for desktop version whereas the ones with a white background are the results of tests for mobile version:

- Home page:

![Home page lh test desktop](documentation/lh-index-desktop.png)

![Home page lh test mobile](documentation/lh-mobile-index.png)

- Accommodation page:

![Accommodation page lh test desktop](documentation/lh-accommodation-desktop.png)

![Accommodation page lh test mobile](documentation/lh-mobile-accommodation.png)

- FAQ page:

![FAQ page lh test desktop](documentation/lh-desktop-faq.png)

![FAQ page lh test mobile](documentation/lh-mobile-faq.png)

- Contact page:

![Contact page lh test desktop](documentation/lh-desktop-contact.png)

![Contact page lh test mobile](documentation/lh-mobile-contact.png)

- Thank you page:

![Thank you page lh test desktop](documentation/lh-desktop-thankyou.png)

![Thank you page lh test mobile](documentation/lh-mobile-thankyou.png)


## MANUAL TESTING

### Testing User Stories

- Expectation:
As a traveler planning a trip to Rio de Janeiro:
I want to easily find and book accommodation so I can have a comfortable place to stay during my visit.
- Result:
When I open the website, I can see that it is a page advertising a vacation rental. I can easily find the link that redirects me to the Airbnb page where the apartment is listed for booking.

- Expectation:
I want to view high-quality photos of the apartment, so I can decide if it is a place I would like to stay.
- Result:
I can intuitively find the Accommodation section on the navigation menu, which takes me to the accommodation's page with high-resolution photos depicting all the apartment rooms.

- Expectation:
I want to access practical information about the surrounding area to help plan my activities during my stay.
- Result:
On the home page, I can see a functioning map of the area where I can study the surroundings using Google Maps and explore nearby amenities and attractions.

- Expectation:
I want to easily find answers to frequently asked questions (FAQs) such as check-in process, and policies.
- Result:
On the navigation menu and in the page's footer, I see links that redirect me to the FAQ page, where I find answers to my questions.

### Full Testing

Full testing was performed on the following devices:

- Laptop:
  - Macbook Air 13 inch screen
- Mobile Devices:
  - iPhone 13 pro.
  - iPhone 11 pro.
  - Phone X.

Each device tested the site using the following browsers:

* Google Chrome
* Safari
* Firefox

Additional testing was taken by friends and family on a variety of devices and screen sizes. They reported no issues when playing.

One tester in peer code review stated that the bottom of the play screen was cut off when testing on an iphone SE (2nd gen). I was unable to replicate this issue using google chrome developer tools.

`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| How to play button | Displays the modal with the instructions on how to play the game | Clicked on button | Modal with instructions on how to play opens | Pass |
| Modal close button | Closes the modal | Clicked on close button | Modal closed | Pass |
| Play Button | Directs the user to the game page | Clicked on button | Game page opens to display the difficulty selections | Pass |
| High Scores Button | Directs the user to the high scores page | Clicked on button | Directs to the high scores page | Pass |
| All buttons - hover effect | All black buttons with white text should change to white with black text when hovered over. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |

`Game Page - Difficulty Selection`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | Directed back to home page | Pass |
| All buttons - hover effect | All buttons with a black background & white text should change when hovered over to a background colour of white with black text. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |
| Easy Button | Calls the easy quiz URL for the API | By console logging the data called from the API I was able to check the difficulty level of the questions corresponded with the level called | ![data-console.log-easy](testing/data-consolelog-easy.png) | Pass |
| Medium Button | Calls the medium quiz URL for the API | By console logging the data called from the API I was able to check the difficulty level of the questions corresponded with the level called | ![data-console.log-medium](testing/data-consolelog-medium.png) | Pass |
| Hard Button | Calls the hard quiz URL for the API | By console logging the data called from the API I was able to check the difficulty level of the questions corresponded with the level called | ![data-console.log-hard](testing/data-consolelog-hard.png) | Pass |

`Game Page - Quiz Area`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | directed back to home page | Pass |
| All buttons - hover effect | All buttons with a black background & white text should change when hovered over to a background colour of white with black text. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |
| Question populated | The question from the API is correctly pulled from the JSON data | console.log the data and check that the question has been pulled correctly | The question is displaying | Pass |
| Answers populated | The answers from the API are correctly pulled from the JSON data | console.log the data and check that the answers have been pulled correctly | The answers are displaying | Pass |
| Data attribute correct | The data attribute correct has been applied to the correct answer | By console logging the data I am able to check what the correct answer should be. I can then console.log the id of the buttons to check whether the data attribute has been applied only to the button containing the correct answer | only the correct answer has the correct attribute | Pass |
| Correct answer - border colour | When a correct answer is clicked the border around the game area should display green | Clicked on a correct answer | Border displayed green | Pass |
| Incorrect answer - border colour | When an incorrect answer is clicked the border around the game area should display red | Clicked incorrect answer | Border displayed red | Pass |
| Correct answer - button colour | When a correct answer is clicked the button should change background colour to green | Clicked a correct answer | Button background turned green | Pass |
| Incorrect answer - button colour | When an incorrect answer is clicked the clicked buttons background should turn red | Clicked incorrect answer | Button background turned red | Pass |
| Incorrect answer - display correct answer | When an incorrect answer is clicked, the correct answer should display a green background | Clicked incorrect answer | The correct answer turned green | Pass |
| Question No counter | The Question No counter should start at 1 and increase by 1 time the next button is selected. | answered questions and clicked next button | Each time the next button is clicked the Answer no counter increases by 1. | Pass |
| Score Counter | The score counter should begin at 0. Each time a correct answer is selected the score should increase by 10. If an incorrect answer is selected the score should remain the same | Clicked a correct answer to check if the score increased. Clicked an incorrect answer to check the score stayed the same| When a correct answer was selected the score increased by 10. When an incorrect score was selected the score stayed the same | Pass |
| Not Allowed Cursor | Once an answer has been selected, the answer buttons should then be disabled and when hovered over the not allowed cursor will display | Clicked on one answer button and then clicked on the remaining answer buttons | After the answer was selected each answer button clicked on subsequently displayed the not allowed cursor | Pass |
| Next button - becomes visible | When an answer is clicked the next button should be displayed so the user can progress to the next question, or to the end section if all 15 questions have been answered| Clicked on an answer button | The next button displayed | Pass |
| Next button hover effect | A button with a white background & black text should change to a button with a black background & white text when hovered over.| Hovered over the button | Style changed as expected | Pass |
| Next button - clicked | When clicked all answer styles should be removed, the next button should become hidden again and a new question and answer loaded if there are questions left. If all questions have been answered the end game should appear | Clicked on the next button | All styles were removed and a new question and answers were displayed. After question 15 was answered I was taken to the end game. | Pass |

`Game Page - End of Quiz`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| All buttons - hover effect | All buttons with a black background & white text should change when hovered over to a background colour of white with black text. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |
| Score Display | The Your Score area should populate with the score you have achieved | I added my score as I played, checked the score on the last question & compared to the score displayed | The score displays correctly | Pass |
| Submit Button - enabled/disabled | The submit button should be disabled and show the not allowed cursor by default. Once the user types their team name into the input field the button is enabled | I hovered over and clicked the submit button without filling in the team name field. I then added a team name, hovered over and clicked the submit button | Without a team name filled in the cursor displays as not allowed and the button will not submit. Once I filled in a team name the cursor became a 🍺 when hovered over the button and I was able to click and submit the score | Pass |
| Submit button - on submit | Once clicked the submit button will redirect you to the high scores page | Clicked the button with the team name filled in | Redirected to the high scores page | Pass |
| Play again? button | Clicking on this button will return you to the start of the game page where you can select a quiz difficulty level | Clicked on the play again? button | Directed to the beginning of the game to select a difficulty level | Pass |
| Home button | Clicking on this button will take you back to the home page | Clicked the home button | Directed back to the home page | Pass |

`High Scores Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| All buttons - hover effect | All buttons with a black background & white text should change when hovered over to a background colour of white with black text. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |
| Score Displayed | If your score is in the top ten, your team name and score will be displayed in the high scores area in descending order | Played 11+ games and logged a variety of scores. | Once 10 scores were displayed on the high scores board, only scores that were better than the ones logged would then be added to the board | Pass |
| Play again? button | Takes the user to the beginning of the game page to select a difficulty level | Clicked the button | Taken to the beginning of the game page to select a difficulty level | Pass |
| Home button | Takes the user to the home page | Clicked the button | Taken to the home page | Pass |

`404 Error Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| All buttons - hover effect | All buttons with a black background & white text should change when hovered over to a background colour of white with black text. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |
| Go home button | Takes the user back to the home page | Clicked the button | Taken to the home page | Pass |
| Play button | Takes the user to the beginning of the game page | Clicked the button | Taken to the beginning of the game page to choose a difficulty level | Pass|
| View high Scores button | Takes the user to the high scores page | Clicked the button | Taken to the high scores page | Pass |

`500 Error Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| All buttons - hover effect | All buttons with a black background & white text should change when hovered over to a background colour of white with black text. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |
| Go home button | Takes the user back to the home page | Clicked the button | Taken to the home page | Pass |
| View high Scores button | Takes the user to the high scores page | Clicked the button | Taken to the high scores page | Pass |