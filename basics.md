# Basics
## Lorem text
- Lorem is sample text that can be put in an HTML file. You can adjust the amount of text that you would like put in by using lorem10(or any number).
## Inline vs Block Level Elements
- Inline Elements do not have to start on a new line and only take the necessary width. 
- Block Elements start a new line and take the full width available. 

- Block Level tags include <div>, <h1>-<h6>, <p>, <form>
- Inline Level tags include <span>, <img>, <a>
## Div Tag
- A div tag is a container for block level elements. It shows the divisions between each block and is used by CSS and JS to manipulate a block element. 

## span tag
- a span tag is an inline container used to markup part of a text or document. It is similar to a div tag however it is an inline element instead of a block level element. 
- A span tag can be easily manipulated by CSS and JavaScript.
## Strong 
- A strong tag is used in HTML to bold any words within the opening and closing tags. However it is better to use CSS to change text. 
## Emphasized tag <em>
- An <em> tag is used to emphasise or italisize text that is within the opening and closing tags. Again best to use CSS. 
## Links <a>
- An <a> tag is for a links. Links can either be used locally, for example linking another file page to the homepage or sending the user to an external page. 
- <a href=""> href is an attribute to the link tag. If you want the user to open the link to another window you can add an target attribute. Best if you want the user to reman on your website however not best to use if you are navigating to other pages of your website. 
```md 
<a href="./basic.md"></a>
<a href="http://www.google.com" target="_blank"></a>
```
## Tag Attributes
- All tags can have attributes
- Provide information about an element
- Placed within the start tag
- Key/value pairs (id="someId")
```md 
<tagName attributeName="attributeValue">content></tagName>
<h1 title="My Company">About Us</h1>
```
## Forms
- Only can do look of the forms. you need other programs to let it function.
## labels and textarea vs input
- <label> are used to show user what information to put in a form. Such as first name, last name, a message etc. You can use tags input and textarea.
- <imput> is for small bits of information such as names. 
- <textarea> is for a larger input box such as message. 
- For the attribute type use the attribute value of "text" for any information with normal text and "email" for a persons email (when using the email value it will send an error if an invalid email is used.)
- You will not see the text within the name attribute you are calling that element that name. The text between the label tags will be shown. 


```md
<label>First Name</label>
<input type="text" name="firstName">

<label>Message</label>
<textarea></textarea>
```
- In a form you can put a placeholder in the text box showing the text temporarily until the user starts to put in text. 

```md
<label>First Name</label>
<input type="text" name="firstName" placeholder="Enter First Name">

## Select tag
- You can insert a select option for your form by using the select tag. This will provide you with a drop menu of options. You will also have to provide the option tag. Make sure to set the value and put in the option text.  

```md
<label>Gender</label>
<select name="gender">
    <option value="male">Male</option>
    <option value="female">Female</option>
</select>
```
## Other values
- When put in the value of number within the input type it will give you the form with arrow in the window that can be used to change the numbers. 
- When you put the value of date it will give you a calendar in the window that you can click to find a date. 

```md
<label>Age:</label>
<input type="number" name="age" value="30">

<label>Birthday:</label>
<input type="date" name="birthday">

```
## Button
- Within a form you can create a submit button by setting the input to the type submit. Remember the name is not the text shown it is what you are naming the element. The value is the text you see within the button. 

```md
<input type="submit" name="submit" value="Submit">
```
- You can also insert button outside of a form by using the tag button. Just like in forms a button will show but it will not do anything without JS. 
```md
<button>Click Me!</button>
```