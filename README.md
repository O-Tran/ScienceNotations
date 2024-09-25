# Copy and Paste Mathematical Constants and Notations 

##  📝 A God-send tool for STEM students 🔬


## What is this tool? ## 
This is a webpage that help students with their lab report by allowing the students to copy and paste formated scientific notations. 

## How does it work ? 
- Step1: Find your section 
- Step2: Click button to copy & Paste your constants or your notations 
- Step 3: If what you're looking for is not here, please contact me in the footer section 

## Why did i build this ? 
When I was doing lab experiments as part of my course requirement for college, I find myself having to search the degree notations '°' and the Delta notations "Δ" because I never knew the shortcuts at hand for Microsoft word and Google Docs. With this tool, I hope future step students can use it to write their lab reports without having to "google search" every notations under the sun. 

Please feel free to contact me more to add in notations that you think future students would need help with. 

Disclaimer: I build this webpage with the help of ChatGPT and with background knowledge of usage in HTML and CSS. 

Thank you for checking out my page! 

## Questions I addressed during web-development 
 
### Problem 1: How Can we enable supscript and superscript on webpage? 
I use the <sup></sup> and the <sub></sub> tags in the description of the buttons as well as the paste text of the buttons as well. This proved sucessful in visually showcasing the subscript and the superscript but it did not paste the correct script format. For example, they visuall show '10<sup>n</sup>' when you click and paste the Exponents buttons.  

### Problem 2: How can we paste the supscript and superscript onto documents like Microsoft Word or Google Doc ? 
I used the Clipboard API methods to copy rich text with formating. (please note this was with the help of ChaptGPT) and implement a fucntion in the "script" sections which allowed the formated text to be copy and paste onto rich text platforms like Google Doc and Microsoft word. 

### Problem 3: Can we improve user experience and make the alert into a dissolve phase instead of having to press "okay" all the time? 
Problem: When I clicked on each button to copy, there is a pop up alert which won't go away unless you press "okay" button at the top. As for User interface features, I feel like this would cause a disconnect into the user's enjoyment of the website by having them click multiple things. This works against them if the students are trying to click and copy many functions often. Therefore I changed it to be more of a "delayed" and "fade out" effect. This type of alert will allow users to know that the button work (visual cues) without the extra step of closing the alert (tactile cue)

### Problem 4: How can we align all the text and buttons? 
This was more of a cosmetic options. I love the look of a center alignment in a webpage. So to fix this, i just adjust the body text-alignment section to be "centered". 


---

Thank you for checking out my work. Please let me know if there's any feedbacks or concern. Looking forward to hearing your reply. 


