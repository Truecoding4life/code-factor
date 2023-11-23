## html-refactor




### Description


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