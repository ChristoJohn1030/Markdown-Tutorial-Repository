# Adding headings to a .md file
There are 6 heading sizes available
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
It previews like as of below
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

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
Eg: ![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
``` 
Shows an image of some cat as below
![Image of Yaktocat](https://octodex.github.com/


# Adding a code example to a  .md file
We could add a code example to the .md file by inserting whatever is in our codee withing ''' symbols 3 single quotes.

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
