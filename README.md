# cpnt260-a1

# CPNT 260-a1

 Instoructor: (https://github.com/lilyx13)[Ashylyn];

 ## Anitube:

 Its about Avengers movies, its call "About pages so I made about Avenger pages"

 **How I used:**

 - I used hwading and list of items and grid.

- I focus on flexbox on css and with gried.

### Code I used: 

## html

```
<h1></h1>
<h2></h2>
<header class="text-container margin-auto">
<h4></h4>
<h3></h3>
<img src="" alt="">
```

Also I used css for 

```
body {
  background-color: whitesmkoe;
  box-sizing:border-box;
}

header {
  margin-top:50px;
}
header > * {
  margin:0 auto;
  padding: 5px 0;
}
footer {
  background-color: black;
  color: whitesmoke;
  height: 20%;
  margin-top:flex;
  /* These are dependent on the flex direction */
  justify-content: center;
  align-items: center;
}

nav {
  background-color: black;
  color:white;
  display:flex;
}
.nav-links{
  display: flex;
  justify-content: Space-around;
  
  list-style-type: none;
  width:100%;
}
/* images */
img {
  width: 100%;
  height:auto;
}

* Fonts */
h1,
h2,
h3,
h4{
  font-family: 'Montserrat', sans-serif;
}

h1 {
  font-size: clamp(2.5rem, 10vw, 4.5rem);
  font-weight: 900;
}
h2 {
  font-size: clamp(2rem, 5vw, 3rem);
}
h3 {
  font-size: clamp(1.5rem, 5vw, 2rem);
}
h4 {
  font-size: clamp(1.4rem, 5vw, 1.8rem);
  margin: 1;
}
p,
li,
a {
  max-width: 75ch;
  font-family: 'Open Sans', sans-serif;
  font-size: clamp(1.2rem, 5vw, 1.4rem);
  line-height: 1.3;
}

/* ******************** */
/* **** containers **** */
/* ******************** */
.page-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.article-container {
  border: 5px solid;
  padding: 20px 10px;
  margin: 20px 20px;
}

.img-wrapper {
  max-width: 800px;
}

.text-box {
  width: 15ch;
  border: 3px solid blue;
  padding: 20px 25px;
}

/* ******************* */
/* **** utilities **** */
/* ******************* */

/* colors */
.bg-red {
  background-color: lightgray;
}
.bg-blue {
  background-color:  lightblue;
}

/* layout */
.margin-auto {
  margin: 0 auto;
}
.text-center {
  text-align: center;
}

.rounded-corners {
  border-radius: 3px;
}
/* text */
.underline {
  text-decoration: underline;
}

.list-style-none {
  list-style-type: none;
}

```

