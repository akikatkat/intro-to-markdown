# INTRODUCTION TO MARKDOWN

 <!--HEADING-->
 # Heading 1
 
 ## Heading 2
 
 ### Heading 3
 
 #### Heading 4
 
 ##### Heading 5
 
 ###### Heading 6

 ---

 <!--Italics-->

 _This is going to be a paragraph that is using italic styling_
 
 *This is going to be a paragraph that is using italic styling*

---

<!--Strong-->

This is an example of **strong text** , anything between the two opening asterisk and two closing asterisk will be displayed as **strong text**

This another example of a way to have __strong text__ in our document. Anything between the two double opening underscore and closing underscore will be displayed as __strong text__

<!--Strike Through-->

This is an example of a ~~strikethrough~~ text, anything between the double tilde opening characters and closing double tilde characters will be displayed as ~~strike through~~ text 

---
<!--Horizontal Rule-->

We can add triple hypens to be able to create a horizontal rule for separating content.

Another way to add __HORIZONTAL RULES__ in our document markdown is by using three underscores.
___


<!--Escape Character Rule using Backlash-->

This an example of a *text with an asterisk*. When we don't want it to be italicized. We want to use the backlash \ to escape the rule of using an opening \*asterisk* and closing \*asterisk* to enclose the text contents.

---

<!--Blockquote Rule-->

> We use the greater than symbol to display a block of text as a quote with a background and line on the left side.

> *"You don't have to be great to start, but you need to start to be great."* - __Unknown Author__ 
___

<!--Link Rule-->

**NOTE**: We would want to put the link description inside of square brackets and the link to the resource inside of two open and close parenthesis 
[KG-2023/Activity-Images-2023](https://github.com/KG-2023/Activity-Images-2023)

__NOTE__: We can add a baloon tip description to our link using double quotes after the link to the resource.
[KG-2023/Activity-Images-2023](https://github.com/KG-2023/Activity-Images-2023 "This is KG-2023/Activity-Images-2023")

---

<!--List Item Rules-->

<!--UNORDERED LIST-->

* Item 1 - this is going to be our list item 1
  * This is our list item 1 child item 1
  * This is our list item 1 child item 2
* Item 2 - this is going to be our list item 2
  * This is our list item 2 child item 1
  * This is our list item 2 child item 2
* Item 3 - this is going to be our list item 1
  * This is our list item 3 child item 1
  * This is our list item 3 child item 2
* Item 4 - this is going to be our list item 1
  * This is our list item 4 child item 1
  * This is our list item 4 child item 2
* Item 5 - this is going to be our list item 1
  * This is our list item 5 child item 1
  * This is our list item 5 child item 2

<!--ORDERED LISTS-->
1. Item 1 - this is going to be our list item 1
   
   1.1 This is our list item 1 child item 1
   
   1.2 This is our list item 1 child item 2
   
2. Item 2 - this is going to be our list item 2
   
   2.1 This is our list item 2 child item 1
   
   2.2 This is our list item 2 child item 2
   
3. Item 3 - this is going to be our list item 3
   
   3.1 This is our list item 3 child item 1
   
   3.2 This is our list item 3 child item 2
   
4. Item 1 - this is going to be our list item 4
    
   4.1 This is our list item 4 child item 1
    
   4.2 This is our list item 4 child item 2
   
5. Item 5 - this is going to be our list item 5
   
   5.1 This is our list item 5 child item 1
   
   5.2 This is our list item 5 child item 2

---

<!--Code Block Inline Example Rule-->

**NOTE**: *__Backtics__ will allow us to show the code block or the paragraph tags in this example. It is located below the tilde character and on top of the tab key*

`<p> This is a paragraph tag with an inline code block example opening and closing tags </p>`

---

<!--IMAGE RULE-->

![This is an image](https://i.pinimg.com/564x/17/34/4e/17344e5df38aa8eae885e3cd214a667b.jpg "Link to a dog image")

---

<!--GITHUB FLAVOR SET OF CODE BLOCK-->

<!--CODE BLOCKS FOR GITHUB DOCUMENTATION-->

```install npm
npm install

npm start
```

**NOTE**: You can specify some syntax code blocks for different languages

```javascript
function jsAdd(num1,num2){
  return num1 + num2;
}
```

```python
def pythonAdd(num1,num2):
  return num1 + num2;
```

```C#
   public static int Sum(int num1, int num2)
   {
     int total
     total = num1 + num2;
     return total;
   }
```

---

<!--Table rules-->

| Name |  Nickname | Email             |
|------|-----------|-------------------|
| Katrina | kat    | kat@gmail.com     |
| katkat  | katy   | testkat@gmail.com |


---

<!--Tasks Lists-->

* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [ ] Task 4
