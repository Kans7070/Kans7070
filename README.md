- 👋 Hi, I’m @Kans7070
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
*{
    margin: 0;
}
.header_left img{
    height: 35px;
    width: 50px;
}
.user_avatar{
    border-radius:50% ;
    width: 35px;
    height: 35px;
    
}
.header{
    padding: 15px 20px;
    display: flex;
    justify-content: space-between;
    position: sticky;
    top: 0;
    background-color: white;
    z-index: 100 ;
    box-shadow: 0 5px 8px -9px rgba(0, 0, 0, 0.75);
}
.header_left{
    display: flex;
    align-items: center;
    justify-content:space-evenly;
}
.header_input{
    display: flex;
    align-items: center;
    background-color: #eff2f5;
    padding: 10px;
    margin-left: 10px;
    border-radius: 999px;

}
.header_input input{
    border: none;
    background-color: transparent;
    outline-width: 0;

}
.header_middle{
    display: flex;
    flex: 1;
    justify-content:center ;
    
}
.header_option .material-icons{
    font-size: xx-large;
    color: gray;
}
.header_option:hover .material-icons{
    color:#2e81f4;
}
.header_option{
    display: flex;
    align-items: center;
    padding: 0 30px;
    cursor: pointer;
}
.header_option.active .material-icons{
    color:#2e81f4;
}
.header_option.active{
    border-bottom: 4px solid #2e81f4;
}
.header_option:hover{
    background-color: #eff2f5;
    border-radius: 10px;
    align-items: center;
    padding: 0 30px;
    border-bottom: none;
}
.header_info{
    display: flex;
    align-items: 20px;
   
}
.header_right{
    display: flex;
    align-items: center;
   
}
.header_right .material-icons{
    color: gray;
    margin: 0 10px;
    cursor: pointer;
   
}
/* header finished */
.sidebarRow{
    top: 0;
 
    display: flex;
    align-items: center;
    padding: 10px;
    cursor:pointer ;

  
}
.sidebar{
    width: 20%;
    height: 450px;
    align-items: center;
    justify-content: center;
    background-color: #F0F2F5;
    border:none;

    
}
.sidebar_holder{
    position: fixed;
}
.main_body{
    width: 100%;
    height: 2275px;
    background-color: #F0F2F5;
    display: flex;
    
}
.story{
    margin-top: 20px;
    border-radius: 7px;
    background-color: #fff;
    margin-right: 10px;
}
.story h3{

    text-align: center;

}
.story img{
    width: 120px;
    height:160px; 
    border-radius: 7px;
    
}
.story_holder{
    display: flex;
    margin-left: 115px;
   

}
.feed_holder{
    
    width: 520px;
    height: auto;
   
    margin-left: 115px;
    
}
.create_feed{
    margin-top: 20px;
    width: 100%;
    height: 100px;
    background-color: white;
    border-radius: 7px;
}
.create_part1 img{
    margin-top: 10px;
    margin-left: 20px ;
    width: 35px;
    height: 35px;
    border-radius: 50%;
}
.create_part1 input{
    width: 80%;
    margin-top: 10px;
    margin-left: 10px;
    height: 30px;
    border-radius: 6px;
    border: none;
    background-color: #F0F2F5;
  
}
.create_part1{
   display: flex;
   margin-bottom:10px;
}
.create_part2{
    display: flex;
    margin-top:15px ;
    justify-content: space-around;
 }
 .create_icon{
     display: flex;
    
 }
 .create_icon h3{
     margin-left: 10px;
 }
.feed{
    margin-top: 20px;
    width: 100%;
    height: 597px;
    background-color:white;
   
    border-radius: 5px;

}
.feed_profile img{
    margin-top: 10px;
    margin-left: 20px ;
    margin-right: 10px;
    width: 35px;
    height: 35px;
    border-radius: 50%;;

}
.feed p{
    margin-top: 20px;
}
.feed h1{
    margin-left: 270px;
}
.feed_profile{
    display: flex;
   
   
}
.feed_image img{
    width: 100%;

}
.review{
    display: flex;
    justify-content: space-evenly;
}
.feed_icon:hover{
    background-color: #F0F2F5;
    border-radius: 5px;
    cursor: pointer;
}
.feed_icon{
    display: flex;
    
    
}
.feed_review_holder{
    padding:10px;
}
.feed_icon h3{
    margin-left: 10px;
}
.sidebarRow img{
    width: 40px;
    border-radius: 50%;
}
.feed_image1 img{   
    width: 100%;
    height: 485px;
    background-color:white;
    padding: auto;
}
.feed_image2 img{   
    width: 100%;
    height: 485px;
    background-color:white;
    padding: auto;
}
.story_feeder{
    padding: 0 40%;
}
.widget_home{
    
    position: fixed;
    margin-left: 910px;
    width: 400px;
    height: 2275px;
    background-color:#F0F2F5;
}
.widget_holder{
    margin-left: 30%;
    width: 70%;
    background-color:#F0F2F5;
    height: 2225px;
    
    padding: 40px 0 0 0;
}

.things_holder{
    margin-top: 10px;
    display: flex;
    justify-content: space-evenly;
    
}
.things_holder h3{
    
    margin-right: 130px;
}
.things h3{
    margin-bottom: 10px;
}
.freinds img{
    width: 35px;
    height: 35px;
    border-radius: 50%;
}
.freinds{
    display :flex ;
    margin-top:10px;
}
.freinds h4{
    margin-top: 5px;
    margin-left: 5px;
}
.conversation button{
    margin-top: 10px;
    border-radius: 50%;
    width:20px;
    height: 20px;
    
    border: 1px solid black;
}
.conversation{
    display: flex;
}
.conversation h3{
    padding: 10px;
}
.freinds:hover{
    background-color:#385898;
    cursor: pointer;
    border-radius: 5px;
}
.sidebarRow:hover{
    background-color: #385898;
    cursor: pointer;
    border-radius: 5px;
}
.more:hover{
    background-color: #385898;
    cursor: pointer;
    border-radius: 5px;
}
.search:hover{
    background-color: #385898;
    cursor: pointer;
    border-radius: 5px;
}
.video:hover{
    background-color: #385898;
    cursor: pointer;
    border-radius: 5px;
}
.conversation:hover{
    background-color: #385898;
    cursor: pointer;
    border-radius: 5px;
}
.header_right:hover{
    cursor: pointer;
    
    border-radius: 5px
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Clone</title>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
    <link href="facebook.css" type="text/css" rel="stylesheet">
</head>
<body>
    <div class="header">
        <div class="header_left">
            <img src="Image/Facebook_logo_PNG12.png">
            <div class="header_input">
                <span class="material-icons">
                    search
                    </span>
                <input type="text" placeholder="Search Facebook">    
            </div>
        </div>
        <div class="header_middle">
            <div class="header_option active">
                <span class="material-icons">
                    home
                    </span>               
            </div>
            <div class="header_option">
                <span class="material-icons">
                    flag
                    </span>
            </div>
            <div class="header_option">
                <span class="material-icons">
                    subscriptions
                    </span>
            </div>
            <div class="header_option">
                <span class="material-icons">
                    storefront
                    </span>
            </div>
            <div class="header_option">
                <span class="material-icons">
                    supervised_user_circle
                    </span>
            </div>
            
        </div>
        <div class="header_right">
            <div class="header_info">
                <span class="material-icons">
                    person
                    </span>
                <h4>Cristiano</h4>
            </div>
            <span class="material-icons">
                add
             </span>
             <span class="material-icons">
                    forum
           </span>
           <span class="material-icons">
            notifications
            </span>
            <span class="material-icons">
                expand_more
            </span>

        </div>
    </div>
    
<!-- header finished -->

    <div class="main_body">
        <div class="sidebar">
            <div class="sidebar_holder">
            <div class="sidebarRow">
                <img src="Image/Cr7.jpg" alt="">
                <h4>Cristiano Ronaldo</h4>
            </div>
            <div class="sidebarRow">
                <img class="hu5pjgll bixrwtb6" src="https://static.xx.fbcdn.net/rsrc.php/v3/yx/r/5rR6LRpNc5u.png" alt="" style="height: 36px; width: 36px;">
                    <h4>Covid - 19 Information Center</h4>
            </div>
            <div class="sidebarRow">
                <img class="hu5pjgll bixrwtb6" src="https://static.xx.fbcdn.net/rsrc.php/v3/yH/r/kyCAf2jbZvF.png" style="height:36px;width:36px" alt="">
                    <h4>Pages</h4>

            </div>

            <div class="sidebarRow">
                <img class="hu5pjgll bixrwtb6" src="https://static.xx.fbcdn.net/rsrc.php/v3/y8/r/S0U5ECzYUSu.png" alt="" style="height: 36px; width: 36px;">
                    <h4>People</h4>
            </div>
            <div class="sidebarRow">
                <img class="hu5pjgll bixrwtb6" src="https://static.xx.fbcdn.net/rsrc.php/v3/y5/r/4Y9Xi2D3hJv.png" alt="" style="height: 36px; width: 36px;">
                    <h4>Messanger</h4>
                
            </div>
            <div class="sidebarRow">
                <img class="hu5pjgll bixrwtb6" src="https://static.xx.fbcdn.net/rsrc.php/v3/y5/r/duk32h44Y31.png" alt="" style="height: 36px; width: 36px;">
                    <h4>Market Place</h4>
                
            </div>
            <div class="sidebarRow">
                <img class="hu5pjgll bixrwtb6" src="https://static.xx.fbcdn.net/rsrc.php/v3/y5/r/duk32h44Y31.png" style="height:36px;width:36px" alt="">
                    <h4>Watch</h4>
                
            </div>
            <div class="sidebarRow">
                <h4>More</h4>
                
            </div>
        </div>    
       
        </div>
        <div class="story_feed">
            <div class="story_holder">
                <div class="story">
                    <img src="Image/Cr72.jpg" alt="">
                    <h3 class="text">Cr7</h3>
                </div>
                <div class="story">
                    <img src="Image/Cr71.jpg" alt="">
                    <h3 class="text">Cr7</h3>
                </div>
                <div class="story">
                    <img src="Image/Cr73.jpg" alt="">
                    <h3 class="text">Cr7</h3>
                </div>
                <div class="story">
                    <img src="Image/Cr74.jpg" alt="">
                    <h3 class="text">Cr7</h3>
                </div>
            </div>
            <div class="feed_holder">
                <div class="create_feed">
                    <div class="create_part1">
                        <img src="Image/Cr7.jpg" alt="">
                        <input type="text" placeholder="What's on your mind.Cristiano?" >
                    </div>
                    <hr>
                    <div class="create_part2">
                        <div class="create_icon">                            
                            <i data-visualcompletion="css-img" style="background-image: url(&quot;https://static.xx.fbcdn.net/rsrc.php/v3/y8/r/q8wO7xsrEK8.png&quot;); background-position: 0px 0px; background-size: auto; width: 24px; height: 24px; background-repeat: no-repeat; display: inline-block;"></i>
                            <h3>Live video</h3>
                        </div>
                        <div class="create_icon">                            
                            <i data-visualcompletion="css-img" style="background-image: url(&quot;https://static.xx.fbcdn.net/rsrc.php/v3/y8/r/q8wO7xsrEK8.png&quot;); background-position: 0px -275px; background-size: auto; width: 24px; height: 24px; background-repeat: no-repeat; display: inline-block;"></i>
                            <h3>Photo/Video</h3>
                        </div>
                        <div class="create_icon">                            
                            <i data-visualcompletion="css-img" style="background-image: url(&quot;https://static.xx.fbcdn.net/rsrc.php/v3/y8/r/q8wO7xsrEK8.png&quot;); background-position: 0px -50px; background-size: auto; width: 24px; height: 24px; background-repeat: no-repeat; display: inline-block;"></i>
                            <h3>FeelingActivity</h3>
                        </div>
                    </div>


                </div>
                <div class="feed">
                       <div class="feed_profile">
                           <img src="Image/Cr7.jpg" alt="">
                           <p><strong>Cr7</strong> king of football</p>
                           <p><strong><h1>...</h1></strong></p>
                       

                   </div>
                   <div class="feed_image">
                       <img src="Image/Cr7.jpg" alt="">
                    </div>
                    <div class="feed_review">
                        <div class="feed_review_holder">

                        
                       
                        <div class="review">
                        <div class="feed_icon">
                            <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -214px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>  
                            <h3>Like</h3>
                        </div>
                        <div class="feed_icon">
                            <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -176px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>
                            <h3>Comments</h3>
                        </div>
                        <div class="feed_icon">
                            <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -176px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>
                            <h3>Share</h3>
                        </div>
                       </div>
                       <br>
                    </div>
                    </div>
                </div>
                <div class="feed">
                    <div class="feed_profile">
                        <img src="Image/Cr7.jpg" alt="">
                        <p><strong>Cr7</strong> king of football</p>
                        <p><strong><h1>...</h1></strong></p>
                    

                </div>
                <div class="feed_image1">
                    <img src="Image/Cr73.jpg" alt="">
                 </div>
                 <div class="feed_review">
                     <div class="feed_review_holder">

                     
                     
                     <div class="review">
                     <div class="feed_icon">
                         <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -214px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>  
                         <h3>Like</h3>
                     </div>
                     <div class="feed_icon">
                         <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -176px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>
                         <h3>Comments</h3>
                     </div>
                     <div class="feed_icon">
                         <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -176px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>
                         <h3>Share</h3>
                     </div>
                    </div>
                    <br>
                 </div>
                 </div>
             </div>
             <div class="feed">
                <div class="feed_profile">
                    <img src="Image/Cr7.jpg" alt="">
                    <p><strong>Cr7</strong> king of football</p>
                    <p><strong><h1>...</h1></strong></p>
                

            </div>
            <div class="feed_image2">
                <img src="Image/Cr74.jpg" alt="">
             </div>
             <div class="feed_review">
                 <div class="feed_review_holder">

                 
                
                 <div class="review">
                 <div class="feed_icon">
                     <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -214px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>  
                     <h3>Like</h3>
                 </div>
                 <div class="feed_icon">
                     <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -176px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>
                     <h3>Comments</h3>
                 </div>
                 <div class="feed_icon">
                     <i data-visualcompletion="css-img" class="hu5pjgll m6k467ps" style="background-image:url('https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/FGD3rBSG9Oa.png');background-position:0 -176px;background-size:auto;width:18px;height:18px;background-repeat:no-repeat;display:inline-block"></i>
                     <h3>Share</h3>
                 </div>
                </div>
                <br>
             </div>
             </div>
         </div>
               
            </div>
        </div>
        <div class="widget_home">
            <div class="widget_holder">
                <div class="widget">
                    <div class="things">
                        
                        <h3>Sponsored</h3>
                    </div>
                    <hr>
                    <div class="things1">
                        <div class="things_holder">
                            <div class="contacts">
                            <h3>contacts</h3>
                        </div>
                        <div class="video">
                            <span class="material-icons">
                                video_call
                            </span>
                        </div>
                        <div class="search">
                            <span class="material-icons">
                                search
                            </span>
                        </div>
                        <div class="more">
                        <h2>...</h2>
                    </div>
                            
                        </div>
                    </div>
                    <div class="freinds">
                        <img src="Image/messi.jpg" alt="">
                        <h4>Lionel Messi</h4>
                    </div>
                    <div class="freinds">
                        <img src="Image/neymer.jpg" alt="">
                        <h4>Neymer Jr</h4>
                    </div>
                    <div class="freinds">
                        <img src="Image/marcello.jpg" alt="">
                        <h4>Marcello</h4>
                    </div>
                    <hr>
                    <h3>Group conversation</h3>
                    <div class="conversation">
                    <h3>+</h3>
                    <h3>Create new Group</h3>

                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
- 📫 How to reach me ...

<!---
Kans7070/Kans7070 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
