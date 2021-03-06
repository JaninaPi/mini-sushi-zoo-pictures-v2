# Make a zoo website! 

* Go to the starter trinket: http://dojo.soy/mini-trinket. On the right you will see a website and on the left is the code that makes the website.

* In the **code pane** go to the tab `styles.css`. Look for the properties `color` and `background-color`. Change the values to colours that you like and see what happens. For a list of colour names you can use, see http://dojo.soy/mini-web-colours.

### Add a picture
* For this step you’ll need a picture of a zoo animal that you like. It needs to be saved on your computer. If you don’t have one handy, you can search the internet and download a picture, or even draw one.

* Click the image icon to the right of the code tabs, then **Add Image**, then **Upload**, then **Click To Select Files**. Find the picture file on your computer, select it and click **Open**. Click **Done**.   
    ![](TktImageIcon.png)

* Now click on the `index.html` tab, and add the following line of code on a new line after the last `</p>` tag. Change `lions.jpg` to the filename of your picture. It must match the file name exactly. The picture should appear on your page.

   ```html
        <img src="lions.jpg" />
   ```
   
* If you want to change the size of your picture, go to `styles.css` and find this code:
   ```css
      img {
        width: 200px;
      }
   ``` 
   Change the number after `width`, making sure not to delete the `px` after the number.

### Create a new page 
* Click the **+** next to the image icon and type `lion.html` where it says **file name** (You can change it to whatever animal you have, but be sure it ends in `.html` as this is what makes it a **web page**).

* Go to the file `blank_page.html`. There you'll see all the code you need for a blank page. Copy that into your new file.

* To add a paragraph of text, click in the blank space between the`<main></main>`tags and type `<p></p>`. Type your text in between the tags, like this: `<p>This page is all about lions!!!!</p>`. You can add as many paragraphs like this as you want.
   * Try adding some pictures on this page too!

### Make a link
* **Go back to the `index.html` tab.** Find your image code and put it in between a pair of `<a></a>` tags like this:

  ```html
    <a href="lion.html"><img src="lions.jpg" /></a>
  ```
  Change `lion.html` to the name of the new page you created.
  You just turned your picture into a link! You should be able to click on the picture now and see the page about that animal.


Repeat these steps as many times as you like to fill your zoo with animals!

![](TktZooExample.png)
 
To learn how to do more with your website and earn yourself a digital badge, visit http://dojo.soy/mini-html-begin and try the Beginner HTML CSS Sushi Cards! To see this card online or print out more, go to http://dojo.soy/mini-sushi-html




