Hi this is markdown <!-- By default is normal text-->
<!-- Separate all elements of markdown by one empty line -->

<!-- 
Add two spaces press enter to break a line in markdown for two paras 
-->
Normal Text  
This is written using two spaces and one line break

                             Headings
 <!--  Add # for This is h1, ## for h2 and so on upto h6 -->
# This is h1
## This is h2
### This is h3
#### This is h4
##### This is h5
###### This is h6

                         Italic/Bold/Italic & Bold
*This text is italic*  
**This text is bold**  
***This text is bold and italic***

<!-- 
These were all basic markdown. There is also extended markdown like Github flavored markdown, which we'll use now -->

                         Highlight and Strikethrough   
~~This is strikethrough text~~
<!-- 
==This is highlighted text== (some markdowns like Github flavored md support this while some mds don't support this syntax like our VS code markdown. So now to highlight we can use standard HTML tag 
--> 
<!-- <mark> This is Highlighted text </mark> -->


                        Subscript and Superscript

<!-- 
1. ~H~(For subscript) and ^^ (For superscript)
2. Again we have to use <sub> and <sup> tags of standard HTML because our VS code markdown don't support this syntax of sub and superscript 
-->
H<sub>2</sub>O  
x<sup>2</sup>

                                Emojis
<!-- :smile: (Not supported in our VS code markdown). So copy and paste emoji directly -->
😊


                                 Code
<!-- 
Use `` ``(Single tilde for one line, and ```js ``` triple tilde along with extension of programming language for multiple lines and syntax highlighting) 
-->
` let a = 5; `
```js 
let x = 5;
let y = 6;
// This is comment
```


                                 Link
<!-- Syntax: [Link text](link path)-->
Link to [Google](https://www.google.com)

                                 Image
<!-- Syntax: ![Alt attrb](path to img) -->
![Burger](/img/i5.jpg)

                                Blockquotes
<!-- Syntax: >  (Angle bracket and space) -->
> If you're getting something for free, you are the product


                               Horizontal Rule
<!-- Syntax: --- OR ___ or *** -->
This is line 1
___

This is line 2

                                Ordered Lists
<!-- Syntax: 1. (Any number followed by dot and space)-->
1. Item 1
2. Item 2
3. Item 3

                            Unordered Lists
<!-- 
Syntax: * OR - OR + (And use tab or 4 spaces to nest lists like in below example 
-->

* Outer l1
- Outer l2
    * Inner l1
    * Inner l2
    1. Inner item 1
    2. Inner item 2
+ Outer l3


                              Checkbox
<!-- 
        For unchecked checkbox
Syntax: [ ] (space followed by square bracket (Square bracket should also have space) followed by space
        For checked checkbox
Syntax: [x] (space followed by square bracket (Square bracket should have x) followed by space

- Supported only in extended markdown (like Github flavored md)
-->

<!-- 
- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon) 
-->

