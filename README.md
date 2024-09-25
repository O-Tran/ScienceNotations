# Copy and Paste Mathematical Constants and Notations 

##  📝 A God-send tool for STEM students 🔬

Check out my tools
[Science Notation] ( https://o-tran.github.io/ScienceNotations/)

## What is this tool? ## 
This is a webpage that helps students with their lab reports by allowing students to copy and paste formatted scientific notations. 

## How does it work? 
- Step1: Find your section 
- Step2: Click button to copy & Paste your constants or your notations 
- Step 3: If what you're looking for is not here, please contact me in the footer section 

## Why did I build this? 
When I was doing lab experiments as part of my course requirement for college, I found myself having to search the degree notations '°' and the Delta notations "Δ" because I never knew the shortcuts at hand for Microsoft Word and Google Docs. With this tool, I hope future step students can use it to write their lab reports without having to "Google search" every notation under the sun. 

Please feel free to contact me more to add in notations that you think future students would need help with. 

Disclaimer: I build this webpage with the help of ChatGPT and with background knowledge of usage in HTML and CSS. 

Thank you for checking out my page! 

## Questions I addressed during web-development 
 
### Problem 1: How Can we enable subscripts and superscripts on a webpage? 
I use the <sup></sup> and the <sub></sub> tags in the description of the buttons as well as the pasted text of the buttons as well. This proved successful in visually showcasing the subscript and the superscript but it did not paste the correct script format. For example, they visually show '10<sup>n</sup>' when you click and paste the Exponents buttons.  

### Problem 2: How can we paste the subscript and superscript onto documents like Microsoft Word or Google Docs? 
I used the Clipboard API methods to copy rich text with formatting. (please note this was with the help of ChaptGPT) and implement a function in the "script" sections which allowed the formatted text to be copied and pasted onto rich text platforms like Google Docs and Microsoft Word. 

### Problem 3: Can we improve user experience and make the alert into a dissolved phase instead of having to press "okay" all the time? 
Problem: When I click on each button to copy, there is a pop-up alert that won't go away unless I press the "okay" button at the top. As for User interface features, I feel like this would cause a disconnect in the user's enjoyment of the website by having them click multiple things. This works against them if the students are trying to click and copy many functions often. Therefore I changed it to be more of a "delayed" and "fade out" effect. This type of alert will allow users to know that the button works (visual cues) without the extra step of closing the alert (tactile cue)

### Problem 4: How can we align all the text and buttons? 
This was more of a cosmetic option. I love the look of a center alignment on a webpage. So to fix this, I just adjusted the body text-alignment section to be "centered". 


---

Thank you for checking out my work. Please let me know if there are any feedback or concerns.

