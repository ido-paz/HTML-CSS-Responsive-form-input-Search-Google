# HTML form , input , for searching google using CSS responsive design
*You can only use HTML form,label,input,select tags to achieve the user interface.<br/>
*Enable submiting the form only if there is text in the search text and between 1 to 25 search results.<br/>
*Use CSS selectors and rules to achieve the user interface.<br/>
*All the CSS should be written in external file named style.css<br/>
1. Create an index.html file with html structure
2. Add form to html body that will collect the user's data 
3. In the form collect the :<br/>
a. Text input that will contain the search query text (q)<br/>
b. Select with options of when the pages were first indexed (as_qdr)<br/>
c. Numeric input that will hold the number of results shown (num)<br/>
d. Checkbox that when checked it will limit the results to hebrew (lr)<br/>
*for explantion about the parameters to send google use https://moz.com/blog/the-ultimate-guide-to-the-google-search-parameters
4. Submit button with "Ask google" text
5. When clicking Submit button , send the user input to "https://google.co.il/search" and open the results in a black page. 
6. All tags in the form should take entire row and have 5px margin .
7. All labels text should be bold .
8. The "Ask google" button text should be green with round corners .
9. Display the form in wide view (450px, each row contains label and input)
10. Display the form in narrow view (270px, each row has only one tag) when the display is below 450px
11. The form should be in the center of the screen.