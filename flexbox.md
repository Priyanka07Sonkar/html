# display:flex; CSS Property
    display:block
           :inline
           :inline-block
    container design krte the uske jo child div the uspe hm display property 
    apply krte the.
           :flex
    parent conatiner pr apply hota hai.
    display:flex;
    usle baad he ye sb property apply kr skte hai.
    1.flex-direction : row | coloumn | row-reverse | coloumn-reverse.
    row: left to right arrange krta hai
    row-reverse: right to left arrange krega
    column: content ko top to bottom arrange krta hai
    column-reverse: content ko bottom se top arrange krta hai
    2.flex-wrap: arange content according to width
    3.flex-flow : flex-direction aur flex wrap ko ek he line mein likhne ka tarika hai
    4.justify-content : ye apka horizonatlly content pr property apply krta hai. 
    5.align-items : ye apka verically kaam krta 
                    left | center | right : space-between | space-around | space-evenly
                    left : arrange content left to right
                    right: arrange content on right
                    center : arrange content on center
                    space-between : create space in between
                    space-around : it create space arround 
                    space-evenly : it create space same in all side.  
    6.align-content
```html
<html>
    <head>
        <title>
            inline example
        </title>
        <style>
            .container{
                border:1px solid;
                height:500px;
                background-color: teal;
                display:flex;
            }
            #div1,#div2,#div3,#div4,#div5{
                border: 1px solid;
                width:100px;
                height: 100px;
                margin:10px;
                background-color: pink;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div id="div1">1</div>
            <div id="div2">2</div>
            <div id="div3">3</div>
            <div id="div4">4</div>
            <div id="div5">5</div>
        </div>
    </body>
</html>
```
