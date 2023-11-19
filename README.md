# testing
So, as a new html and css learner, I have faced some issues. I have used the media query and in which I'v eused the "max-width" thing. but unfortuntely for me the code isnt working properly
and does not do the things as mentioned. Im facing issues from line 105 and under.

html :

<!DOCTYPE html>
<html>
    <head>
        <title>tom</title>
        <link rel="stylesheet" href="tom.css">
        <title>gayshit</title>
    </head>
    <body>
        <header>
           <div class="all-together">
                <div class="nav">
                    <ul>
                        <li><a href=""><img src="SSUIMUN 7.0 Black Logo.png" alt="" height="65px" width="65px"></a></li>
                        <li>
                            <b><a href="https://youtu.be/dQw4w9WgXcQ?si=qT38V-lJ9FkHJCLD">SSUIMUN</a></b>
                        </li>
                    </ul>
                </div>
                <div class="middle-part" id="mp1">
                    <ul>
                        <li><a href="https://youtu.be/dQw4w9WgXcQ?si=qT38V-lJ9FkHJCLD">Home</a></li>
                        <li><a href="https://youtu.be/dQw4w9WgXcQ?si=qT38V-lJ9FkHJCLD">Event</a></li>
                        <li><a href="https://youtu.be/dQw4w9WgXcQ?si=qT38V-lJ9FkHJCLD">Schedule</a></li>
                        <li><a href="https://youtu.be/dQw4w9WgXcQ?si=qT38V-lJ9FkHJCLD">Tickets</a></li>
                    </ul>
                </div>
                <div class="subs">
                    <ul><li><a href="https://youtu.be/dQw4w9WgXcQ?si=qT38V-lJ9FkHJCLD">Subscribe</a></li></ul>
                </div>
           </div>
          
        </header>
    </body>
</html>


CSS:

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
body{
    margin: 0px;
    font-family: 'Inter', sans-serif;
    /*line-height: 10; */    
}  
.all-together{
    background-color: white; height: 80px; width: auto;
    color: black;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.nav ul li{
    list-style-type: none;
}
.nav ul li a{
    color: black;
    text-decoration: none;
    font-size: x-large;
}
.nav ul{
    gap: 11px;
    display: flex;
    align-items: center;
}
.middle-part ul li{
    font-size: 14px;
    list-style-type: none;
}
.middle-part ul{
    display: flex;    
    gap: 27px;
}
.middle-part ul li a{
    text-decoration: none;
    color: black;
}
.subs ul li{
    list-style: none;
    padding-right: 20px;
}
.subs ul li a{
    text-decoration: none;
    font-size: 13px;
    color: whitesmoke;
    background-color: black;
    padding: 12px 20px;
    border-radius: 11px;
    line-height: 20;
}
.header{
    margin: 0px;
}
.nav ul a li{
    display: flex;
}
.nav ul li a img{
    padding-top: 11px;
}
@media (max-width: 768px) {
    .middle-part{
       display: none;
    }
    .subs{
       display: none;
    }
}



