# JavaScript #

Creating Action
- on page load
- user interact

Most scripts are added just before the closihg `</body>` tag. 
It is best to keep JS code in its own JS file. They have .js extension.
`<script>` element is used in HTML to tell brower to load the JS file like `<link>` for CSS. 

`document.write('Good afternoon!');`

*document* represents the entire webpage. All browers implement this object and use it just by giving its name

*method* ( write() ) allows new content to be written into the page where `<script>` sits

# Basic JS instructions #

- script is a series on instructions a computer can follow. Each instruction/step is know as a **statement**. Statements should end with a semicolon.
- statments are organized into **code blocks.** They are surrounded by curly braces. They are often used to group together many statements making it more readable.

**variables** "var" ,can store data that `<script>` needs to do its job. "Memory". They arre used to represent values in your scripts that are likely to change. Must be defined!

**=** is called a assignment operator. Says you are going to asssign a value ot the variable. Until you have assigned a value to a variable, the value is *undefined.*

# Data Types # 
JS distinguishes between numbers, strings, and true or false values knows as *Booleans.*

**numeric data type** fors tasks that involve counting or calculating sums. As well as determining size of the screen, moving the position of an element on a page, or setting the amount of time an element should take to fade in.

**String data type** consists of letters and other characters. String is enclosed within a pair of quotes. EX: 'Hi, Ive!'. could be either single or double. Often used to add new content into a page and they can contain HTML markup.

**Boolean data type** can have one of two values, *true* or *false*

Flexible (browser) "if"
"typeof"