/* body */
body{
    text-align: center;
    margin: 0 auto;
    background-color: #efefef;
}
/* the header */
.header{
    background-color: black;
    overflow: auto;
    width: 100%;
}
/* title */
img + h1{
    color: white;
    font-size: 50px;
    margin-right: 150px;
}
/* logos */
.scp-logo{
    width: 150px;
    height: 150px;
    float: left;
}
.scp-logo2{
    width: 150px;
    height: 150px;
    float: right;
}
/* links to other webpages */
.links{
    color: white;
    font-size: 35px;
    display: inline;
    margin-right: 20px;
    margin-left: 20px;
}
/* links hover */
a:hover{
    color: aqua;
}

section{
    width: 500px;
    margin: 0 auto;
    margin-top: 10px;
}
/* footer */
footer{
    background-color:black;
    text-align:center;
    padding:2em;
    position: fixed;
    bottom: 0;
    width:100%;
}
/* size of images */
img.home-image, .img-moreinformation, .img-character, .img-foundation{
    width: 500px;
    height: 400px;
}
/* filter transition brightness to image */
section.brightness123{
    transition:  filter 0.3s ease;
}
section.brightness123:hover{
    filter: brightness(1.5);
}
/* quit the decoration */
a.link-nodecoration{
    text-decoration: none;
    color: black;
}
/* link decoration */
a.link-nodecoration:hover{
    color: red;
}
/* title of sections */
h1.h1{
    font-size: 40px;
}
/* iframes videos in the center */
div.iframes{
    display: flex;
    justify-content: center;
    align-content: center;
}
/* box shadow */
article section{
    transition: box-shadow 0.3s ease;
    background-color: #fff;
    margin-bottom: 20px;
    border-radius: 0.5rem;
    padding: 0.25rem 0;
}
article section:hover{
    box-shadow: 0 0.1rem 0.4rem rgba(0, 0, 0, 0.5);
}
/* ox shadow diferrent colors */
.section-info1 , .section-info2 , .section-info3 , .section-info4 , .section-info5{
    transition: box-shadow 0.3s ease;
}
.section-info1:hover{
    box-shadow: 0 0.1rem 0.4rem rgb(0, 255, 0);
}
.section-info2:hover{
    box-shadow: 0 0.1rem 0.4rem rgb(255, 162, 0);
}
.section-info3:hover{
    box-shadow: 0 0.1rem 0.4rem rgb(255, 0, 0);
}
.section-info4:hover{
    box-shadow: 0 0.1rem 0.4rem rgb(0, 0, 0);
}
.section-info5:hover{
    box-shadow: 0 0.1rem 0.4rem rgb(0, 119, 12);
}
/* two elements in one line and same height */
section.section-2{
    display: inline-block;
    margin: 5px;
}
section.section-2 > div{
    min-height: 150px;
}
div#mas-grande{
    min-height: 175px;
}

