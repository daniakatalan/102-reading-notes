# HTML Lists, Control Flow with JS, and the CSS Box Model

# Lists:
HTML provides us with three different types:

1. Ordered lists: 
are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order,
or a legal contract where each point needs to be identified by a section number.
```
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
```



2. Unordered lists:
are lists that begin with a bullet point (rather than characters that indicate order).
```
<ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
```

3. Definition lists:
are made up of a set of terms along with the definitions for each of those terms.
```
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
condiments such as shredded daikon radish or
ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
weight of ingredients</dd>
<dd>A technique by which the scales are removed
from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
cow's milk (although it was traditionally made
from buffalo milk)</dd>
</dl>
```
- Nested Lists:

You can put a second list inside an < li > element to create a sublist or nested list.

# Boxes: 
CSS treats each HTML element as if it lives in its own box.

- Every box has three available properties that can be adjusted to control its appearance:
1. Border:

Every box has a border (even if it is not visible or is specified to be 0 pixels wide).
The border separates the edge of one box from another.

2. Margin:

Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

3. Padding:

Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.


# SWITCH STATEMENTS

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the
variable matches that value.

```
switch (level) {
case 'O ne ':
title= 'Level 1 ' ;
break;
case 'Two':
tit 1 e = ' Level 2 ' ;
break;
case ' Three' :
title = 'Level 3' ;
break ;
default :
title= 'Test';
break;
}
```

# Loops

loops check a condition. if it returns true, a code block will run. then the condition will be checked again and if it still returns true, the code block will run again.
it repeats until the condition returns false. 

- Loops types:

![image](https://user-images.githubusercontent.com/84705312/121790585-8985d500-cbe9-11eb-8929-c801007c723d.png)

![image](https://user-images.githubusercontent.com/84705312/121790599-9d313b80-cbe9-11eb-924f-ce009425a905.png)


  
