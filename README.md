# Exercise1
 <!DOCTYPE html
    PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

<link href="Exercise1.css" type="text/css" rel="stylesheet" />
<html>

<head></head>

<body>



    Flexbox Exercise 1



    <h1>Flexbox Exercise 1</h1>
    <p>A</p>
    <div class="wrapper">
        <p1>1</p1>
        <p2>2</p2>
        <p3>3</p3>
        <p4>4</p4>
        <p5>5</p5>
    </div>
    <p>B</p>
    <div class="wrapper-2">
        <p6>1</p6>
        <p7>2</p7>
        <p8>3</p8>
        <p9>4</p9>
        <p10>5</p10>
    </div>
    <p>C</p>
    <div class="small-wrapper">
        <div class="wrapper-3">
            <p6>1</p6>
            <p7>2</p7>
            <p8>3</p8>
            <p9>4</p9>
            <p10>5</p10>
        </div>
    </div>
    <p>D</p>
    <div class="wrapper-4">
        <p11>1</p11>
        <p12>2</p12>
        <p13>3</p13>
        <p14>4</p14>
        <p15>5</p15>
    </div>
    <p>E</p>
    <div class="wrapper-5">
        <p16>1</p16>
        <p17>2</p17>
        <p18>3</p18>
        <p19>4</p19>
        <p20>5</p20>
    </div>

    <p>F</p>
    <div class="wrapper-6">
        <p16>1</p16>
        <p17>2</p17>
        <p18>3</p18>
        <p19>4</p19>
        <p20>5</p20>
    </div>

    <p>G</p>
    <div class="wrapper-7">
        <p21>1</p21>
        <p22>2</p22>
        <p23>3</p23>
        <p24>4</p24>
        <p25>5</p25>
    </div>


    <script type="text/javascript" src="/d2l/common/math/MathML.js?v=20.21.12.34152 "></script>
    <script
        type="text/javascript">document.addEventListener('DOMContentLoaded', function () { D2LMathML.DesktopInit('https://s.brightspace.com/lib/mathjax/2.7.4/MathJax.js?config=MML_HTMLorMML', 'https://s.brightspace.com/lib/mathjax/2.7.4/MathJax.js?config=TeX-AMS-MML_HTMLorMML', '110', false); });</script>
</body>

</html>






CSS HERE:
.wrapper{
background-color: rgb(204, 204, 204);
display: flex;
padding: 10px;

}

p1 {
background-color: white;
margin: 10px;
padding: 20px;
}

p2 {
background-color: white;
margin: 10px;
padding: 20px;
padding-bottom: 40px;
}

p3 {
background-color: white;
margin: 10px;
padding: 20px;
}

p4 {
background-color: white;
margin: 10px;
padding: 20px;
}

p5 {
background-color: white;
margin: 10px;
padding: 20px;
}

.wrapper-2{
background-color: rgb(204, 204, 204);
flex-direction: row;
justify-content: center;
display: flex;
padding: 10px;
}

p6 {
background-color: white;
margin: 10px;
padding: 20px;
}
    
p7 {
background-color: white;
margin: 10px;
padding: 20px;
padding-bottom: 40px;
}
    
p8 {
background-color: white;
margin: 10px;
padding: 20px;
 }
    
p9 {
 background-color: white;
margin: 10px;
padding: 20px;
 }
    
p10 {
background-color: white;
margin: 10px;
 padding: 20px;
    }

.wrapper-3{
display: flex;
flex-direction: row;
justify-content: center;
background-color: rgb(204, 204, 204);
padding: 40px;

}

.wrapper-4{
background-color: rgb(204, 204, 204);
display: flex;
padding: 10px;
flex-direction: row;
justify-content: flex-end;
}

p11 {
background-color: white;
margin: 10px;
padding: 20px;
}
    
p12 {
background-color: white;
margin: 10px;
padding: 20px;
padding-bottom: 40px;
}
    
p13 {
background-color: white;
margin: 10px;
padding: 20px;
}
    
p14 {
background-color: white;
margin: 10px;
padding: 20px;
}
    
p15 {
background-color: white;
margin: 10px;
padding: 20px;
}


.wrapper-5{
display: flex;
background-color: rgb(204, 204, 204);
padding: 40px;
flex-direction: row;
justify-content:space-between;
}

p16 {
background-color: white;
margin: 10px;
padding: 20px;
}
        
p17 {
background-color: white;
margin: 10px;
padding: 20px;
padding-bottom: 40px;
}
        
p18 {
background-color: white;
margin: 10px;
padding: 20px;
}
        
p19 {
background-color: white;
margin: 10px;
padding: 20px;
}
        
p20 {
background-color: white;
margin: 10px;
padding: 20px;
}

.wrapper-6{
    display: flex;
    background-color: rgb(204, 204, 204);
    padding: 20px;
    flex-direction: row;
    justify-content:space-evenly;
}

.wrapper-7{
    display: flex;
    background-color: rgb(204, 204, 204);
    padding: 40px;
    flex-direction: row;
    justify-content: start;
    flex-grow: 2;
    
}

p21 {
background-color: white;
margin: 10px;
padding: 60px;
padding-right: 60px;
width: max-content;
flex-grow: 2;
}
            
p22 {
background-color: white;
margin: 10px;
padding: 60px;
padding-right: 60px;
width: max-content;
flex-grow: 2;
}
            
p23 {
background-color: white;
margin: 10px;
padding: 60px;
padding-right: 60px;
width: max-content;
flex-grow: 2;
}
            
p24 {
background-color: white;
margin: 10px;
padding: 60px;
padding-right: 60px;
width: max-content;
flex-grow: 2;
}
            
p25 {
background-color: white;
margin: 10px;
padding-right: 60px;
padding: 60px;
width: max-content;
flex-grow: 2;
}

.small-wrapper{
display: flex;
flex-direction: row;
justify-content: center;
background-color: rgb(255, 255, 255);
}



