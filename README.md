## html-refactor

##### Resources
[GitHub Repository](https://github.com/Truecoding4life/html-refactor)

[Deployed Link](https://truecoding4life.github.io/html-refactor/)

[Jay's Studio](https://truecoding4life.github.io/Jaystudio/)



---



##### Table of contents
* [Description](#description)
* [Adding Semantic Element](#html-semantic-element)
* [Code Refactor](#code-refactor)
* [Added Accessibility](#added-alt-to-each-img)
* [Technologies Used](#technologies-used)

---






### Description

This is my first challenge at UC Berkely boot camp, my task was to refractor the provided code and make the page better than before so let's see how I refractor this page and optimize it's accessibility.

---


![Landing Page](./assets/images/Screenshot%202023-11-22%20at%209.20.29%20PM.png)







---





#### HTML Semantic Element

I implement footer and header tag to make use of html semantic elements
```
<footer>
    <h2>Made with ❤️️ by Horiseon</h2>
    <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
    </p>

</footer>
```
---








#### Code Refactor

The code here look great but we can optimize this code by simply
adding attribute and have them target the same attribute

```
.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

```

**Then I refactor the code to**

the result of this was that I was able to cut down 100 line of codes and optimize the system to process faster

```
.mainbox {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

/* condensed 3 img tag */
.mainbox img {
    max-height: 200px;
}



/* condensed triple h2 tag*/
.mainbox h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
```
---







#### Added alt to image for accessibility
Making the page more accessible using alt so that we can provide our services to peoples with needs

```
<img src="./assets/images/cost-management.png" alt="a gear surrounded by dollar coins" />
```
---


### Technologies Used

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

[More info about HTML](https://www.w3schools.com/css/)

![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 

[More Info about CSS3](https://www.w3schools.com/html/)

---







### Credit
This README was created based on the GOOD README guide.

---




This Website is made available by © Jay's Studio 
