
<!DOCTYPE html>
<!-- Credit to Khan Academy for creating this challenge and teaching me!
Most(not all) of this is not real
THANK YOU Khan Academy for teaching me everything I know, and thank to Mrs. Mackin for starting Khan Acdemy and introducing it to me.
The Comment Function comes from A KHAN ACADEMY template and all credit for that goes to KHAN ACADEMY, but i did complete the Khan Acdemy challenge so I did the code and then copied it to do this
This Contains HARRY POTTER SPOILERS
I also learned the Video function from Codecademy
I also learned the form function from Khan Acdemy, but did a challenge for the code.
YOU HAVE BEEN WARNED!!
Sources:
https://www.w3schools.com/colors/colors_picker.asp
https://websitesetup.org/web-safe-fonts-html-css/
https://www.w3schools.com/tags/tag_video.asp
https://www.w3schools.com/html/html5_video.asp
https://css-tricks.com/snippets/css/typewriter-effect/ Thank you so much for the typewriter effect
Khan Academy 
Codecademy - https://www.codecademy.com/learn 
https://www.khanacademy.org
-->
<html lang = "en">
    <head>
        <meta charset="utf-8">
        <title>Tech Fair Blog</title>
   
    <style>
        #chicago {
        text-decoration:underline;
        }
        #comment-button {
        background-color: white;
        }
        #comment {
            color:rgb(0, 0, 0);
            font-family:Garamond;
            text-align:center;
            font-weight: bold;
            font-style:italic;
            text-decoration:underline;
            
        }
        .content {
            border:10px ridge rgb(74, 77, 79);
            font-family:helvetica;
            margin:10px;
            padding:5px;
            background-color:rgb(255, 255, 255);
            
            
        }
        body {
            background-color:rgb(76, 154, 232);
            font-family:helvetica ;
            
          
        }
        
        #cs {
            position:absolute;
            right:116px;
        }
        #nat-champ {
            
            
        }
        #db {
            text-align:center;
            
            margin:69px;
            padding:7px;
            color:white;
        }
        .post{
            text-align:center;
            margin:44px;
            background-color:white;
            border:10px ridge rgb(74, 77, 79);
        }
        #Christmas p:hover {
            color:rgb(255, 255, 255);
            text-decoration:underline;
        }
       
        
         a:hover {
            color:rgb(0, 0, 0);
            text-decoration:none;
        }
        a:link {
            color:rgb(9, 0, 255);
        }
        
        .posted {
            font-family:Corbel;
            border:5px ridge rgb(99, 99, 99);
            margin:44px;
            padding:4px;
            text-align:center;
            background:rgb(255, 255, 255);
            
            
        }
        #info-one {
            font-family:Corbel;
        }
        #info-two {
            font-family:helvetica;
        }
        #info-three {
            font-family:Corbel;
        }
        #info-four {
            font-family:monotype;
        }
        #info-five {
            font-family:ariel;
        }
        
        #info-six {
            font-family:georgia;
        }
        #info-seven {
            font-family:monotype;
        }
        #info-eight {
            font-family:helvetica;
        }
        #info-nine {
            font-family:bookman ;
        }
        #info-ten {
        font-family: Corbel;
        }
        #info-eleven {
        font-family: georgia ;
        }
        #info-twelve {
        font-family: helvetica;
        }
        #info-fif {
        font-family: Corbel;
        }
        #four-post {
            
            font-family:times;
        }
        
        #third-post {
           
            font-family:Corbel;
        }
        
        #second-post {
            
            font-family:helvetica;
        }
        
        #first-post {
            
            font-family:Corbel;
        }
        #five-post {
            
            font-family:courier;
        }
        #six-post {
          font-family:helvetica;  
        }
        #seven-post {
            
            font-family:times;
        }
        #eight-post {
            font-family:Bookman ;
        }
        
        #nine-post {
           font-family:Garamond ;
            
        }
        #ten-post {
            font-family:courier ;
        }
        #eleven-post {
        font-family: bookman;
        }
        #twelve-post {
        font-family: Corbel;
        }
        #fourt-post {
        font-family: ariel;
        }
        #fif-post {
        font-family:helvetica;
        }
        #help {
            cursor:help;
        }
        #comment-table {
            background-color:rgb(255, 255, 255);
            font-family:Garamond;
            color:rgb(0, 0, 0);
            position:absolute;
            left:300px;
        }
        #newY {
            text-decoration:underline;
            background-color:rgb(64, 89, 230);
        }
        
        #Christmas {
            background-color:rgb(76, 191, 74);
        }
        
        #warning {
            color:white;
            background-color:red;
        }
        #ClemW {
            background-color:white;
        }
        #CT {
        float:left;
            
        }
        #spoiler {
            background-color:red;
            color:white;
        }
        .comment-function {
            position:absolute;
            left:1070px;
        
        }
        .input-lister {
            position:absolute;
            left: 1000px;
        }
        .awesome:hover {
        color: red;
        }
        #commentF {
            position:absolute;
        botto: 350px;
            left: 1000px;
        
        }
        .awesome {
        text-align:center;
        }
        #result {
        border: 2px dotted gold;
            background-color: grey;
        }
        #ff-result {
        border: 2px dotted gold;
        background-color: grey;
            
        }
        #ff-but {
        background-color: gold;
        }
        #hpbut {
        background-color: gold;
        }
        #ani-but {
        background-color: gold;
        }
        #pla-but {
        background-color: gold;
        }
        #why {
        text-align:center;
        }
        .natchampword {
            color: rgb(251, 255, 0);
        }
        #ski-img {
            border: 0px ridge gold;
        }
        #not-there{
            font-size:0px;
        }
        #why-pic {
            border: 0px ridge blue;
        }
        .typewriter {
        overflow:hidden;
        border-right:.15em solid red;
        white-space:nowrap;
        margin:0 auto;
        letter-spacing:.15em;
        animation:
            typing 3.5s steps(40, end),
            blink-caret .75s step-end infinite;
        
        
        }
        
        @keyframes typing {
            from {width: 0;}
            to { width: 100%;}
            
        
        }
        @keyframes blink-caret {
            from, to {border-color: transparent;}
            50% {border-color:black;}
        }
        #h3-mar {
        
        }
        #sb-report {
        background-color:red;
        color:white;
        }
        #hp-result {
        border: 2px dotted gold;
        background-color: grey;
        }
        
        
        </style>
         </head>
    <body>
        
        <h1 id  = 'db' class = 'typewriter'>Livin' The Life</h1>
        <marquee> <h3 id = 'h3-mar'> The revolutionary blog that is sweeping the nation!! Just Kidding🙁. </h3> </marquee>
        <h3>Contents</h3>
        <ul>
            
            <li class = 'content'> <a href = "#first-post"> My first ever post!!!!!!</a> </li>
            <li class = 'content'> <a href = '#second-post'> Christmas day </a> </li>
            <li class = 'content'> <a href = '#third-post'> New Years Day</a> </li>
            <li class = 'content'> <a href = '#four-post'> Trip to New York </a></li> 
            <li class = 'content'> <a href = '#five-post'> Super Bowl </a> </li>
            <li class = 'content'> <a href = '#six-post'> National Championship</a> </li>
            <li class = 'content'> <a href = '#seven-post'> Harry Potter Binge</a> </li>
            <li class = 'content'> <a href = '#eight-post'> Scholar's Bowl </a> </li>
            <li class = 'content'> <a href = '#nine-post'> More Scholar's Bowl </a> </li>
            <li class = 'content'> <a href = '#ten-post'> Trouble with a website </a> </li>
            <li class = 'content'> <a href = '#eleven-post'> Tannerite </a> </li>
            <li class = 'content'> <a href = '#twelve-post'> Amazing Places </a> </li>
            <li class = 'content'> <a href = '#thir-post'> Me Bored </a> </li>
            <li class = 'content'> <a href = '#fourt-post'> Ski Trip in Gatlinburg </a> </li>
            <li class= 'content' > <a href = '#fif-post'> Fortnite </a> </li>
            <li class = 'content'> <a href = '#sixt-post'> The REAL Super Bowl </a> </li>
            <li class = 'content'> <a href = '#teenseventh-post'> Scholar's Bowl State Trip </a> </li>
            <li class = 'content'> <a href = '#pic-sel'> Pick a Place </a> </li>
            <li class = 'content'> <a href = '#fav-ani'> Pick an animal </a> </li>
            <li class = 'content'> <a href = '#do-like'> Fortnite Form! </a> </li>
            <li class = 'content'> <a href = '#harrypotter'> Harry Potter Form </a> </li>
            <li class = 'content'> <a href = '#why'> Why? </a> </li>
            <li class = 'content'> <a href = '#comment'> Comments! </a> </li>
            
            
        </ul>
        
        <!-- First Post -->
        
        <h2 id = 'first-post' class = 'post'>My  first ever post!</h2>
        <h6 class = 'posted'>Posted on 11/11/11</h6>
        
        <p id = 'info-one'>This is my first post, so tell me in the <a href = '#comment-table'> comments </a> if my post is good!!!! Ok now I will be back on Monday. Sorry that this post is so short I will have longer posts in the future.Please come back to look at my next post.  </p>
        
        <!-- Christmas -->
        
        <div id = 'Christmas'>
        <h2 id = 'second-post' class = 'post'>Christmas Day!</h2>
        <h6 class = 'posted'>Posted on 12/25/11</h6>
        <img id = 'CT' src = 'https://www.kasandbox.org/programming-images/seasonal/xmas-tree-with-presents.png' alt = 'animated christmas tree with presents' width= '113'>
        <p id = 'info-two'>Sorry it took so long it is just that November was hard. I had to buy a lot of christmas presents and do a lot of work, but it was still awesome because it is Christmas. We had the whole family over and it was amazing I had so much fun playing with my cousins. I also had a gingerbread party and I made my gingerbread man loaded with candy, so he was fun to eat. I also went to my grandparents house and had a marshmellow fight, it was so cool and my team won. I also went on a Duck Boat tour and it was really fun. Here is a picture of a Christmas Tree.</p>
        
        
        
        </div>
        
        <!-- New Years-->
        
        <h2 id = 'third-post' class = 'post'>New Years Day! </h2>
        <h6 class = 'posted'>Posted on 1/1/12</h6>
        <p id = 'info-three'> Since yesterday was <span id = 'newY'>New Years</span> I had a party and it was amazing. I had so much fun playing soccer with my friends!<span id = 'chicago'> I also told everyone that I was going to Chigaco.</span> I had some sparkling White Grape Juice and it tasted awesome it was like sprite but better. In fact it is now my favorite drink in the entire world, so now you know that it is good. </p>
        
        <!-- Trip to NEw York -->
        
        <h2 id = 'four-post' class = 'post'>Trip to Chicago </h2>
        <h6 class = 'posted'>Posted on 1/24/12</h6>
        <p id = 'info-four'>I went to Chicago and it was amazing. I saw a ton of cool stuff like giant buildings. I also met up with my friend, William! In Chicago I had so much fun with William! I bought a ton of "futuristic" things that now do not work, so the lesson is: If you go to Chicago do not buy the "futuristic" things. Though I do recommend going to Chicago because it was fun. If you do want to go to Chicago go to the help page in the help bar put in: I want to go to Chicago and then follow the directions.
        
             </p>
        
        <!-- Super Bowl-->
        
        <h2 id = 'five-post' class = 'post'> Watching the Super Bowl!</h2>
        <h6 class = 'posted'> Posted on February 2, 2018</h6>
        <p id = 'info-five'> The Giants clapped the Eagles five days ago in the NFC Championship, and I was so happy. Then, the Giants flattered the Patriots in the Super Bowl with a 77-3 victory! The Giants are amazing! I cannot wait until next football season, for the Giants to dominate some more.(This article is completely fake)  </p>
        
        
        <!-- National Championship -->
        
        <h2 id = 'six-post' class = 'post'> The National Championship</h2>
        <h6 class = 'posted'> Posted on January 7, 2019</h6>
        <p id = 'info-six'>(Click the paragraph) I am watching the College Football National Championship(just kidding I am mostly coding this website), and it is a high scoring game. It is Clemson vs. Alabama, and Clemson has the lead with 37-16. I will update later to tell who won. <span id = 'ClemW'>Update: Clemson won 44-16.</span> Most Alabama fans in my grade are sad, but I knew that Alabama was going to lose at one point. I mean you can't win every game can you? Well, bye.</p>
<img id = 'nat-champ' src = 'http://static-30.sinclairstoryline.com/resources/media/fd32f01a-14de-4d2c-a9a6-10a4336195f9-CollegeFootball1.jpg?1446654512586' width = '300' alt = 'national championship trophy'>
<div id = 'natchamplace'> </div>
     
        <!-- Harry Potter Binge -->

        <h2 id = 'seven-post' class = 'post'>Harry Potter Binge!!</h2>
        <h6 class = 'posted'>Posted on March 2,2019</h6>
        <p id = 'info-seven'>I love <span id = 'dot'>Harry Potter</span> and it is my favorite book. Last week I binged the books for my sixth time, and today I will binge the movies.<span id = 'spoiler'> Do not read if you have not read the books.</span> I am on the seventh movie part two, and...oh come Neville you can kill Nagini come on. Sorry for the interuption I was about to say that Harry potter is my favorite series, and leave in the comments what your favorite book is. Personally my favorite book is the sixth, The Half-Blood Prince, beacuse it reveals a lot about Voldemort and who he was. I'll see you on my next post.   </p>
        
        <!-- Scholar's Bowl -->
       
        <h2 id = 'eight-post' class = 'post'> Scholar's Bowl Trip </h2>
        <h6 class = 'posted'>Posted on January 8, 2019  </h6>
        <p id = 'info-eight'>Last weekend(January 4 through January 5) I went on a Scholar's Bowl trip to Russellville. The trip was nine hours, but it was really fun. One the way up we went to McAlister's Deli and the waiter acted like I was 7, it was still fun though. When we got there we pulled into a Best Western and I shared a room with Bennet and Philip, and we may or may not have locked ourselves out. At 5:40 we went downstairs to the meeting room and played card games. We played to rounds of Uno and then one of the teachers who came with us joined. The game lasted forever because someone get on swaping hands with whoever was winning. The guy who was swapping hands was about to win, but the teacher who came with us made an epic comeback. At night we watched some YouTube, played some Fortnite, and then got in bed. While in bed we talked for about 45 minutes, and there was a flickering lightbulb. We went to the competition and the 6th graders(my team) won two games, and the 7th and 8th graders won zero, and neither of us made the playoff. On the way back I played Flats and then once my computer died just hung out on the bus. Anyway it was a very fun trip and I hope to do it again.  </p>
        <!-- Button thing -->
<button id ='m-but'> Make a picture!</button>
<br>
<marquee><img alt = "Scholar's Bowl Logo"id = 'm-img' src = 'https://www.etsu.edu/news/univschool_news/announcements/2018_2019/pictures/scholars_bowl_page_banner.jpg' width = '200px'></marquee>

        <!-- MORE Scholar's Bowl -->
       
        <h2 id = 'nine-post' class = 'post'> Scholars's Bowl Competition(at St. Paul's) </h2>
<h6 class = 'posted'> Posted on January 9, 2019 </h6>
<p id = 'info-nine'> Today I had a Scholar's Bowl competition. Me and my friend were the only sixth graders there yet we still did good. We won both of our games by and okay amount of points. We had a fun party before with pizza, snacks, and Sprite, Coke, and water. Sorry for the short post I just do not have a lot to write about. </p>
        
        <!-- Difficult time making a website -->

<h2 id = 'ten-post' class = 'post'> Trouble with a website </h2>
<h6 class = 'posted'> Posted on January 10, 2019 </h6>
<p id = 'info-ten'> Today I <strong>tried</strong> to make a website on WordPress and Wix. Keyword there is tried. I do not know how to do all of that fancy stuff, because I am used to coding with simple p tags and h1 tags. To me just coding a website is <strong>MUCH</strong> easier! I kept on trying and trying and trying to be succesful at regular website apps, but I cannot get I am am just used to using simple code to make websites. I hope that somebody will teach me how to do wordPress or Wix, because right now I can do nothing on it. Sorry I went on for so long about that it is just that I am mad. </p>
        <!-- Tannerite  -->

<h2 id = 'eleven-post' class = 'post'> Tannerite </h2>
<h6 class = 'posted'> Posted on January 13, 2019 </h6>
<p id = 'info-eleven'> Do you know what Tannerite is? Probably not unless if you have a hunting camp. Tannerite is like a legal explosive that only explodes on high impact like being shot by a 2 70 gun. So christmas of 2017 I got tannerite from my uncle, so we went to our hunting camp to shoot it. When we got to our hunting camp we went to the rifle range and got everything set up. When we got there we also figured out that our uncle had brought soda. We taped the tannerite to a tree and blew up a tree about two times. Then we taped the soda to a tree(after having a sip) and blow up a tree with soda on it about two times. Anyway it was fun, and if you want a good video just search up tannerite videos on youtube. Though I have a video below. </p>
<video src = 'BLogVid.mp4' poster = 'TanneriteForBlog.jpeg'  width = '320' height = '240' controls preload> </video> 

         
        <!-- awesome places -->
<h2 id = 'twelve-post' class = 'post'> Awesome Places  </h2>
<h6 class = 'posted'> Posted on January 13, 2019 </h6>
<ol class = 'awesome' id = 'info-twelve'> 
    <li> Montana(Lone Mountain Ranch) </li>
    <li> Disney World </li>
    <li> Baltimore </li>
    <li> North Georgia Mountains </li>
    <li> Atlanta </li>
</ol>

        <!-- Me bored -->
        <h2 id = 'thir-post' class = 'post'> Me Bored </h2>
        <h6 class = 'posted'> Posted on January 17, 2019 </h6>
        <p id = 'info-thir'> Do you get bored? Me too. I mostly am writing this to help my form, if you haven't done it do it now, but part is because I am bored. Well I could go farther into jQuery, but I want to work on my blog right now so. Tommorrow I leave for a ski trip and I am excited to go! That is pretty much it. Sorry for the short entry, but I need to work on the form. Bye. </p>
        <!-- SKi TRip -->
        
        <h2 id = 'fourt-post' class = 'post'> Ski Trip in Gatlinburg </h2>
        <h6 class = 'posted'> Posted on January 22, 2019 </h6>
        <p id = 'info-fourt'> (CLICK THE PARAGRAPH!) It was amazing! On the bus I sat Parker, Dylan, and Elliott. We had a lot of fun playing games until it happened. We pulled into a gas station, stopped, and noticed that the High School boy's bus was smoking. Five minutes later, we pulled into the exact same gas station. We stayed there for about one hour and thirty minutes while the adults TRIED to fix the bus. Finally the adults decided to move the high schoolers to the boys and girls bus. It was CROWDED. The rest of the ride was just me and Thomas Allen, from Scholar's Bowl, talking about anime. Then Dylan fell on us three times, so me and TA took the two seats, Dylan went to the floor, and Parker went to the floor. This whole time Elliott was sleeping. We finally get to Camp Wesley Woods, go to our bunkrooms, and go to sleep, without a pillow. The next morning I wake up, talk to Elliott and Dylan, bundle up, and go to the place where we eat breakfast. We play some good Uno, until we have to get our pillows and then we just stop. We sit down, all of us, sing praise, and then listen to a long, but good, sermon by Macon. Then we finally get dressed to ski, and before we leave I lose my tooth. I sit with Silas on the way to Gatlinburg, an hour trip, and he does magic tricks. We get there, do paperwork, get in line for the Tram, get our boots, get our skis, get our helmets, and then finally head out to ski. I was REJECTED to ski schools because I didn't have my papers, but I got Mr. Davidson to teach me. I learned on the bunny slope and then finally got on the green turny slope, and fell a lot. We went back to the cabins, put our clothes out to dry, and then went to bed. We woke up had a devotional, ate breakfast, had another long sermon and sang songs, and set out yet again to ski. I skied with a lot of people, but ate lunch with Emma and GinnyLou. Whan we had to return our stuff I sat in a long line when I could have just put my boots on the desk. This caused me to have to go home with the girls with TA. We got back had showers, had lows, highs, and a devotional, and then went to bed. On the way back I was in Elliott's car with his parents, himself, Dylan, and Parker. We played My Cow, learned about the Merrick family, watched Transformers, went to Chick-fil-a, and had singing competitions. The trip was really fun!    </p>
        <img id = 'ski-img' src = 'https://www.travelwyoming.com/sites/default/files/uploads/consumer/visitJH-imageLibrary-grandTarghee-04.jpg' width = '150' alt = 'Man skiing on a mountain'> 
        <p id = 'not-there'>Ski Picture!! </p>
        
        <!-- Fortnite -->
        <h2 id = 'fif-post' class = 'post'> Fortnite </h2>
        <h6 class = 'posted'> Posted on January 24, 2019 </h6>
        <p id = 'info-fif'> Do you like Fortnite? I personal like it, but I know that you might not. To me it is a good game, though don't worry because my mom makes sure that I don't play to much. I have about 32 wins and like 500+ kills. I know that you don't care about this, I am mostly just doing this for a video opportunity, and a form oppertunity. Please watch the video, and take the form. You can also leave in the comments if you like it. You can also tell me how many wins you have (if you play). </p>
        <video src = 'ForBBlog.mp4' poster = 'forposter.jpg' width = '320' height = '280' controls preload> </video>
        <!-- real super bowl -->
        <h2 id = 'sixt-post' class = 'post'> The REAL Super Bowl</h2>
        <h6 class = 'posted'> Posted on Febuary 3, 2019 </h6>
        <p id = 'info-sixt'> It is the day of the Super Bowl! In the morning I played Fortnite, went to Church, watched my brothers play Fortnite and Terraria, played Soccer, practiced Typing Pal, and read. Then we started the game and all I did was read most of the time, and watched commercials. Then I finished my book, we had dinner, ribs, beans, and broccoli, and we resumed watching the show. Then I did some SQL and Ruby, made some edits to the blog, and searched up how to make it better. Oh wait, I just realized that this is supposed to be about the Super Bowl, anyway the score now is 10-3 Patriots with 2:25 left in the game. I will give the final score later:<span id = 'sb-report'> 13-3 Patriots won. </span> </p>
        <!-- Scholar's Bowl State -->
        <h2 id = 'teenseventh-post' class = 'post'> Scholar's State Trip </h2>
        <h6 class = 'posted'> Posted on March 25, 2019 </h6>
            <p id = 'info-se'>(Click the paragraph) So I made the State team and it was AWESOME. I finally had a phone for the trip so that made it even better. We drove up and stayed in a hotel. I was shared a room with Cam and Ben and we just watched YouTube in the room. After we got there, we went downstairs and practiced. After we practiced, we played games and I played QuizUp against Caroline. The Great QuizUp 
            War is a war where Caroline (and AK and Maya and our teacher) and I had a war with QuizUp, a trivia game app. Then we got to the competition, won 3 out of 5 games, and I won the third best scorer in our division. Then we went on the bus, got Chick-Fil-A, and went home.</p>
            <img id = 'quizUp' src = 'https://is3-ssl.mzstatic.com/image/thumb/Purple114/v4/cf/75/a5/cf75a503-ed11-7a27-c40a-22cac5f14063/AppIcon-1x_U007emarketing-85-220-0-5.png/246x0w.jpg' width '0' alt = 'QuizUp Logo'>
        <!-- Select Place -->
<form id = 'pic-sel'> 
    
    <label>
        Places
        <select name = 'place'>
            <option value = 'disney'> Disney World </option>
            <option value = 'LMR'> LMR in Montana </option>
            <option value = 'baltimore' > Baltimore </option>
            
            
        </select>
        </label>
        <button type = 'submit' id = 'pla-but'>Go!</button>
        
    
    </form>
        <div id = 'picPLAce'>Picture: </div>
        
          <!-- Favorite Animal -->
        
        <form id = 'fav-ani'> 
        <label>
        Favorite animal
            <select id = 'ani'> 
                <option value = 'dog'> Dog </option>
                <option value = 'cat'> Cat </option>
                <option value = 'other'> Other </option>
                </select>
            </label>
            <button type = 'submit' id = 'ani-but'> Choose </button>
        </form>
        <div id = 'result'> </div>
        <!-- Fortnite Form-->
        
        
        <form id = 'do-like' >
        <label>
        Do you like Fortnite?
            <select id = 'like'>
                <option value = 'yes'> Yes </option>
                <option value = 'no'> No </option>
                <option value = 'dn'> Don't Know </option>

                </select>
            </label>
            <button type = 'submit' id = 'ff-but'> Do you like it? </button>
        </form>
        <div id = 'ff-result'>  </div>
        
        <form id = 'harrypotter'>
            <label>
                Do you like Harry Potter?
                <select id = 'yn'>
                    <option value = 'y'> Yes </option>
                    <option value = 'n'> No </option>
                    <option value = 'nr'> Never read it </option>
                    <option value = 'sri'> Stopped reading it </option>
                </select>
            </label>
            <button type = 'submit' id = 'hpbut'> Do you like it? </button>
        </form>
        <div id = 'hp-result'> </div>
                   
        <!-- WHY? -->
        <h2 id = 'why'> Why? </h2>
        <p id = 'why-info'> You may be wondering why I am doing this. I am doing this one for Tech Fair, and two to help encourage people to code. Guess what this blog was all coded by ME. If you want to learn go to <a href = 'https://www.khanacademy.org/'> Khan Academy </a> or <a href = 'https://www.codecademy.com/'> Codecademy</a>. They are both great and to get started just make an account and find the coding area. If you have questions/problems email me at <a href = "mailto:dgill@stpaulsmobile.net?Subject=Help" target = "_top" > DGill@stpaulsmobile.net. </a> </p>
        <button type = 'submit' id = 'why-but'> Why?? </button>
        <br>
        <img width = '0' id = 'why-pic'  src = 'https://www.asalesguy.com/wp-content/uploads/2017/09/why.png' alt = 'sign with Why?? written on it'>
        <!-- comments -->
        <h2 id = 'comment'> Comments </h2>
        <table id ='comment-table'>
            <thead>
                <tr>
                    <th>From?? </th>
                    <th> Message</th>
                    
                </tr>
                
            </thead>
            <tbody> 
                <tr>
                <td>Hater302</td>
                <td> This is so cringy. Feel the cringe.</td>
                
                    
                </tr>
                <tr>
                    <td> Non-Hater </td>
                    <td> I don't know what you mean. This blog is amazing.</td>
                </tr>
                <tr>
                <td> Daniel </td>
                <td> Hater that hurt me, but thank you non-hater I will send you a  present!</td>
                    </tr>
                    
                    <tr>
                        <td> Amazing101  
                        <td>  I love this Blog!!!!!!!!
                    </tr>
                    
                    <tr>
                        <td> BlogCritic123
                        <td> This Blog is amazing! It is the best blog that I have ever seen.
                    </tr>
                    
                    <tr>
                        <td> Daniel
                        <td> Thank you!
                    </tr>
                    
                    <tr>
                        <td> hater43
                        <td> I do not know what you mean BlogCritic123.
                    </tr>
                    
                    <tr>
                        <td> mayalikestea
                        <td> Hi y'all.
                    </tr>
                    
                    <tr>
                        <td>willthehater22
                        <td>this blog is trash you should delete it.
                    </tr>
                    <tr>
                        <td> elliot67
                        <td> i can relate, i like harry potter too!
                    </tr>
                    <tr>
                        <td> jackson789
                        <td> i love this blog
                    </tr>
                <tr> 
                <td>hungergames45
                    <td> Hunger Games is much better than harry potter
                </tr>
                <tr> 
                <td>harrypotterfan
                    <td> Harry Potter is much better 
                </tr>
                
                <tr> 
                    <td> elliott67
                        <td> I think Harry Potter is better
                </tr>
                
                <tr> 
                <td> william90
                <td> the Scholar's Bowl section is amazing y'all.    
                </tr>
                
                <tr>
                    
                <td>tuffieWuffie
                <td> forgot the answer to the scholars bowl question tuffie wuffie y'all
                    
                </tr>
                
               
               <tr> 
                <td> Daniel
                    <td> "Robert Frost"
                   
                </tr>
                <tr> 
                <td> phillepe890
                    
                <td> I love Scythe and Harry Potter.
                </tr>
                
                <tr> 
                <td>bennettTheLogicLess
                <td> i love this blog 
                </tr>
                
                <tr> 
                <td> Charlegmane 2.0
                <td> I will take over this blog!
                
                </tr>
                
                <tr> 
                <td> countryboy12
                    <td> i love tannerite
                </tr>
                
                <tr> 
                    
                <td> Daniel
                    <td> Watch Lachlan
                </tr>
                <tr> 
                    
                <td> LazarBeam
                    <td> i hate lachlan
                </tr>
                <tr>
                <td> vgvbygnvbvfbbgcvgvf
                <td> you should add more spam
                    
                </tr>
                <tr>
                <td> Danner Jr. 3th
                    <td>I am amazing because i am a junior and a third
                    
                </tr>
                <tr>
                <td> former
                <td> add a form
                </tr>
                
                <tr>
                <td> tuffieWuffie
                    <td> I've been thinking
                
                </tr>
                <tr> 
                <td> tuffieWuffie
                    <td> I want you to be Happier
                    
                </tr>
                <tr>
                <td> bigChungus
                <td> I am the heaviest thing in the universe    
                </tr>
                <tr> 
                <td> SaNicBoI
                <td> GoTtA gO fAsT!!!!!111
                </tr>
                <tr> 
                    <td id = 'td-from'> </td>
                    <td id = 'td-what'> </td>
                </tr>
            </tbody>
            
        </table>
<!-- Comment input -->
        <ul>
            <li> <span class = 'input-lister'>From:</span> <input type = 'text' id = 'from' class = 'comment-function'> </li>
            <li> <span class = 'input-lister'> Comment: </span> <input type = 'text' id = 'comment2' class = 'comment-function' > </li>
</ul>
<!-- Button and where Comment appears -->


<button id = 'comment-button' class = 'comment-function'> Comment it </button>
<p class = 'comment-function' id ='commentF'> Your Comment: <span id = 'story'> </span></p>


<!-- Extra Comment Stuff -->
          <h2 id = 'reward'> <a href = 'https://www.amazon.com'> Reward for comment!! </a> </h2>
      
        <h2 id = 'help'> <a href = 'https://www.khanacademy.org/computer-programming/blog-help-menu/5646119011254272'>Help</a></h2>
		<h2 id = 'sources'> <a href = 'C:\Users\dgill\Desktop\Codewriter%20files\sourcesfor2019.html'> Sources</a></h2>

        <!-- JAVA -->
        <!-- source for jQuery-->
        <script src = 'https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js'></script>
        <script>
            //add comment to page 
        var commentButton = document.getElementById('comment-button');
        var commentIt = function() {
            var storyDiv = document.getElementById("story");
            storyDiv.innerHTML = "??Your story here";
             commentButton.addEventListener('click', commentIt);
             var from  = document.getElementById ('from').value;
            var comment = document.getElementById ('comment2').value;
            
            storyDiv.textContent = from + '     ' + comment + '.' ;
        };
        commentButton.addEventListener('click', commentIt);
            //add comment to table
             $('#comment-button').on('click', function(event){
                var from = $('#from')
                var what = $('#comment2')
                var fromv = from.val();
                var whatv = what.val();
                $('#td-from').text(fromv)
                $('#td-what').text(whatv)
                
            })
            //dictionary with pics
            var placeImages = {
                'LMR': 'https://media-cdn.tripadvisor.com/media/photo-s/09/89/9f/9d/lone-mountain-guest-ranch.jpg',
                'disney': 'https://parade.com/wp-content/uploads/2017/06/Disney-World-Cinderella-Castle-FTR.jpg',
                'baltimore' : 'http://images.realclear.com/343429_5_.jpeg'
                
            };
            //go anywhere
            $('#pic-sel').on('submit', function(event){
                event.preventDefault();
                var $picplace = $(this).find('[name=place]')
                var picplace = $picplace.val();
                var $img = $('<img>');
                $img.width(200)
                $img.attr('src', placeImages[picplace])
                $img.appendTo('#picPLAce')
                
            });
            
            //favorite animal
            $('#fav-ani').on('submit', function(event) {
            event.preventDefault();
            var $answer = $('#ani');
            var answer = $answer.val();
                if (answer === 'dog') {
                $('#result').text('I like dogs too!');
                }
                if (answer === 'cat') {
                $('#result').text('I respect your opinion.');
                } 
                if (answer === 'other') { 
                $('#result').text('Tell me in the comments or go to the help page to tell me.');
                }
            });
            //fortnite form
            $('#do-like').on('submit', function(event) {
            event.preventDefault();
            var $$answer = $('#like');
            var $$$answer = $$answer.val();
                if ($$$answer === 'yes') {
                $('#ff-result').text('I kind of like Fortnite.');
                }
                if ($$$answer === 'no') {
                $('#ff-result').text("I am sure that you have a good reason.");
                } 
                if ($$$answer === 'dn') { 
                $('#ff-result').text('Maybe you can play and figure out if you like it.');
                }
            });
            //harry potter form 
            $('#harrypotter').on('submit', function(event) {
            event.preventDefault();
                var $aanswer = $('#yn')
                var $$aanswer = $aanswer.val();
                if ($$aanswer === 'y') {
                $('#hp-result').text("I love Harry Potter too!")
                    
                }
                if ($$aanswer === 'n'){
                $('#hp-result').text('You must have a good reason.')
                
                }
                if($$aanswer === 'nr') {
                $('#hp-result').text('You need to read it.')
                }
                if ($$aanswer === 'sri') {
                $('#hp-result').text('You need to pick it up especially if you stopped during the Order of the Pheonix. The Half-Blood Prince, the next book, is AWESOME.')
                }
            })
            
            $('#nat-champ').hide();
            $('#info-six').on('click', function(event) {
                $('#nat-champ').fadeIn(3000, function(event){
                    $h1 = $('<h2>')
                    $h1.text('National Championship Trophy')
                    $h1.addClass('natchamword')
                    $h1.appendTo('#natchamplace')
                    
                })
                
                
            })
            $('#ski-img').hide();
            $('#info-fourt').on('click', function(event){
                $('#ski-img').animate({
                    width: '200px',
                    borderWidth: '10px'
                    
                    
                })
                $('#not-there').animate({
                    fontSize: '20px'
                    
                })
            })
            $('#why-pic').hide();
            $('#why-but').on('click', function(event) {
            $('#why-pic').animate ({
            width: '250px',
                borderWidth: '8px'
                
            })
            
            })
            //marquee picture
            $('#m-img').hide()
            $('#m-but').on('click', function(event) {
                $('#m-img').show();
                
            })
            //QuizUp picture
            $('#quizUp').hide()
            $('#info-se').on('click', function(event) {
                $('#quizUp').animate ({
                width: '270px'
                })
            
            
            })
        </script>
    </body>
</html>
<!-- Thank you for Watching!-->
    
