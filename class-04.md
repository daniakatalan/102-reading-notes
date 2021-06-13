# HTML Links, JS Functions, and Intro to CSS Layout

# Links

Links are created using the <a> element. Users can click on anything between the opening < a > tag and the closing </a> tag. You specify
which page you want to link to using the href attribute.
  
  ```
  <a href="http://www.imdb.com">IMDB</a>
  ```
  
# Layout
  
  - Key Concepts in Positioning Elements: 
  
  1. Building Blocks
  
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.
  
  2. Containing Elements
  
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
  
  
# Functions
  
  - WHAT IS A FUNCTION?
  
  Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements).
  
  ```
  var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(};
  ```
  
- Declaring a Function:
  
  ![image](https://user-images.githubusercontent.com/84705312/121791597-2a798d80-cbf4-11eb-8167-a689acba9ad8.png)

  - Calling a function:
  
  ![image](https://user-images.githubusercontent.com/84705312/121791607-4c731000-cbf4-11eb-9abd-f531b5ef42b0.png)

  
  # 6 Reasons for Pair Programming Article 
  
  How does pair programming work?
  
   pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.
  
  Why pair program?
  
  Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.
  
  
  
  
  
  
