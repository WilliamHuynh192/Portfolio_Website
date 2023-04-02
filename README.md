# Portfolio_Website
This is an assignment from my Web design courses. I took advantages of the assignment to make a website which can be use as my portfolio in the future.
- Author: William Huynh
- Description: I used this assignment to created a website as a portfolio, and a blog to express my interest.
- Names of File and Structure:

 Website (folder):
 |   |_ audio (folder):
 |      |     |
 |      |     |_ piano.mp3
 |      |_ css (folder):
 |      |     |
 |      |     |_ flightsim.css
 |      |     |
 |      |     |_ index.css
 |      |     |
 |      |     |_ music.css
 |      |     |
 |      |     |_ photography.css
 |      |     |
 |      |     |_ portfolio.css
 |      |     
 |      |_ img (folder):
 |      |     |_ flightsim (folder): img1.png -> img9.png
 |      |     |
 |      |     |_ photography (folder): img1.jpg
 |      |     |
 |      |     |_ favicon.jpg
 |      |
 |      |_ video (folder):
 |      |     |
 |      |     |_ vid1.mp4
 |      |
 |      |_ flightsim.html
 |      |
 |      |_ index.html
 |      |
 |      |_ music.html
 |      |
 |      |_ photography.html
 |      |
 |      |_ portfolio.html
 |
 |_ CodeReview.pdf
 |
 |_ DesignWriteUp.pdf
 |
 |_ README.txt (you are here)

---------------------------------------------------------------------------------------------------------------------
- Three webpages I choose to modify and style are:
+ index.html
+ portfolio.html
+ flightsim.html

- The other two website: photography.html, music.html are left behind so I can do it in the future.

---------------------------------------------------------------------------------------------------------------------
- Code documentation and assignment required features's location:

	**********Features that are the same for all three webspages and css files*************
+ index.html line 10->90, index.css line 53->55: Put the body of the webpage into a div block to style its background color in css
+ portfolio.html line 9->136, portfolio.css line 42->44: Put the body of the webpage into a div block to style its background color in css
+ flightsim.html line 9->92, flightsim.css line 64->66: Put the body of the webpage into a div block to style its background color in css

CSS Funtions:
+ h1: align the header center, its all around margin is 0px and all around padding is 30px.
+ h2: add color blue to all header in tag h2.
+ a: add color to URL text.
+ nav: used the navigation bar as a flex items, items will wrap normally, each item gap is 50px, the content is in the middle with padding. Its border will be on the top and bottom.
+ main: main content of the webpage will have paddings on left right and margin on top bottom. Depend on the webpage, there will be small modification to either margin or padding, but overall function is the same
+ footer: add padding and margin to the bottom of the webpages.
+ p, footer > a: define font family for these tag will be sans-serif, with each line height is 25px.
+ body: add margin to left and right, background color, and color of the text in the body.
+ #content: add background color to the content div block.
+ ::selection: this is a pseudo element, it will be mention again in the pseudo section, main purpose is to change the background color when user select texts.
+ [target="_blank"]:hover: when hover cursor over URL that will open in a new tab, change color.

        *************************** index.css ******************************
+ table, tr, td, th line 37: add font sans-serif, add collapse border with solid color to the table and its element.
+ th, td line 42: align text left and add padding.

        *************************** portfolio.css ******************************
+ h2 + h3 line 54: any header h3 after h2 and have the same parent, add top border to h3 and padding on top.
+ h2 ~ ol line 59: any ol tag that is adjacent to h2 and have the same parent, add border on top.
+ h2 + ul line 63: any unordered list ul after h2 and have the same parent, add top border above ul and padding on top.

        *************************** flightsim.css ******************************
+ h3 ~ p line 41: any p tag that is adjacent to h3 and have the same parent, add margin all around
+ *.photos line 82: all content in class photos is display in grid, which will has 3 columns, gap and padding
+ img line 89: each image will have rounded border, width and heigth is 100%, add padding on top and margin on the bottom.
+ video line 97: each video will have rounded border, width and heigth is 100%, and margin on the bottom.
+ iframe line 104: each embeddeed youtube video will have rounded border and width of 100%.
+ ol line 109: the ordered list will have padding on left and right.
+ li line 114: each element of list will have padding on the bottom.

---------------------------------------------------------------------------------------------------------------------------
- Selectors location:
+ Universal: line 82 in flightsim.css
+ Multiple: line 37 in index.css
+ Child: line 32 in flightsimm.css
+ Sibling: line 59 in portfolio.css
+ Adjacent Sibling: line 63 in portfolio.css
+ Pseudo-element: line 65 in index.css

-------------------------------------------------------------------------------------------------------------------------------------
- In all html file, in the footer section, I included links to my Facebook, Instagram, and my Youtube channel video
- All photos in this assignment is my work.
- Flight sim videos in this assignment is my work, not the music video, the music citation is below 

Citation:
[1] Metallica. 2022. Nothing Else Matters. Video. (7 June 2022). Retrieved Febuary 7, 2023 from https://www.youtube.com/watch?v=ozXZnwYTMbs
[2] Brian Hyland. 2019. Sealed With A Kiss. Video. (7 Feb 2019). Retrieved Febuary 7, 2023 from https://www.youtube.com/watch?v=qsvTtp-n_a0
[3] Kavinsky. 2011. Nightcall. Video. (21 Sep 2011). Retrieved Febuary 7, 2023 from https://www.youtube.com/watch?v=MV_3Dpw-BRY
[4] Soviet war song. 2019. "Afghan, I Will Never Forget You". Video. (19 May 2019). Retrieved Febuary 7, 2023 from https://www.youtube.com/watch?v=BQWGxrqv84M
