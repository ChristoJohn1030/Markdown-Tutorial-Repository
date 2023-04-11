# Adding headings to a .md file

To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

There are 6 heading sizes available
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
It previews like as of below :
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

When we use two or more headings, GitHub automatically generates a table of contents that we can access by clicking  within the file header. Each heading title is listed in the table of contents and we can click a title to navigate to the selected section.

# Styling a text in a .md file

We can give different styles to the text in a .md file using different symbols. The important style types and their symbols are :

  **STYLE**          **SYMBOL**
``` 
1. Bold    :      ** <TEXT HERE> ** or
                  __ <Text here__
              
2.Italics  :     * <Text here> *    or
                  _ <Text here> _
3.Strike through : ~~ <Text here> ~~
4.Italic Text inside a bold text :
      ** <This is a bold text with _Italics_ > **
  The whole text will be bold and the 'italics' word will only be applied italics style....
5.All bold and Italic : *** <Text here> ***

    The whole text will be Bold and Italic
6.Subscript : <sub> subscript Text here </sub>
      (html tag is used)
7.Superscript : <sup> super script text here </sup>
8.

```

examples:

1.** This is a bold text **
2._ This is an Italic Text _
3.**This is a bold text with _italics inside_ **
4.*** This is a full Bold-Italic Text ***
5.~~ This is a Strikethrough text ~~
6. <sub> This is a subScript </sub>
7. <sup> This is a superscript </sup>

# Bullets and numbering

We can add bullets and numberings in a .md file.There are two types of bullets
1.The first one is an empty bullet... Its syntax is
```
- Text here

```
The ```  - ``` will transform into a n emty bullet bullet - -  this 

# Quoting a text in .md file
We can quote a text in a. md file by using ' > ' symbol.

``` 
> text here
```
eg: > This is a quoted text


Quoted text is indented, with a different type color.


#Adding URL links to a .md file
We can add different URL's to a .md file. There are multiple methods for URL handling....










# Adding images to a .md file
We can add image to any .md file just by uaing the below syntax
```
![<Image Alt text>](<image web link here>)
```

first we have a ! Sign. Then in the next square bracket [ ] we give the ALT TEXT.
In case the  image doesn't show up users could know what it is for from the alt text..
And the third part is a curly bracket ( ) where we give the link to the image... First upload image to github
Then obtain the link of that image and then paste it in the .md file...
``` 
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
``` 
Shows an image of some cat as below
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


# Adding a code example to a  .md file
We could add a code example to the .md file by inserting whatever is in our codee withing ``` symbols 3 back quotes.

Eg:
```

Const Telegraf = require('telegraf');
const bot = new Telegraf('BOT_TOKEN');


```


You can copy whatever is inside these code sections with an inbuilt option...

# Adding task list (checkbox)

We can also add task lists which has a checkbox associated with it
We can create it like this
```
1.  - [ ] content text
2.  - [x] content text
```
It previews like of below
1.  - [ ] content text
2.  - [x] content text


The first line adds an empty check box with "Content text" as the text associated with the check box
and the second line creates a checked check box with content text as the text assosciated with the check box


