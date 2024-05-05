<title>Page Title</title>

    <!-- ... -->

    <link
      rel="canonical"
      href="https://getbootstrap.com/docs/5.0/examples/starter-template/"
  
         
    />

    <!-- Bootstrap core CSS -->
    <!-- Do not remove or edit -->

    <link
      href="http://pachecod.github.io/bootstrap/assets/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />

    <!-- Custom styles for this template -->
    <!-- Do not remove or edit -->

    <link href="style.css" rel="stylesheet" />

  </head>
<style>
body {
    background-color: #0047AB; /* Cobalt blue background color */
    color: white; /* Set text color to white */
    border: 10px solid black; /* Add a black border */
    font-size: 16px; /* Set font size for body text */
}

.footer p {
    /* This is how you add styles for only the p text within the footer. */
    font-family: "Times New Roman";
    background-color: #1434A4;
    text-align: center;
    font-size: 30px;
    margin-bottom: 0;
}

.header {
    height: auto;
    font-weight: bold;
    font-size: 50px;
    text-align: center;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
    background-color: black;
}

h1 {
    font-size: 25px;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
}

/* Add red underline to The Fan Factor */
/* Reduce the space between The Fan Factor and the following paragraph */
h4 {
    margin-bottom: 10px; /* Adjust the bottom margin */
    font-style: italic;
    font-size: 40px; /* Adjust font size for h4 */
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
    text-decoration: underline; /* Add underline */
    text-decoration-color: red; /* Set underline color to red */
}

h3 {
    margin-top: 10px; /* Adjust the top margin */
    font-style: italic;
    font-size: 20px;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
}

h5 {
    font-style: italic;
    font-size: 15px;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
}

iframe {
    border: 20px solid black; /* Add a black border to all iframes */
    background-color: #ffffff; /* Add white background to all iframes */
}

/*Don't worry about this section yet*/
@media only screen and (max-width: 767px) {
    .list {
        float: none;
        min-width: 90%;
        margin-left: 10px;
        margin-bottom: 30px;
        margin-top: 30px;
    }

    iframe {
        min-width: 90%;
        margin-right: 10px;
    }
}

</style>
  <body>
    <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
      <div class="container-fluid">

   
    
        <div class="collapse navbar-collapse" id="navbarsExampleDefault">
          <ul class="navbar-nav me-auto mb-2 mb-md-0">

        <!-- ... -->
        <!-- ... -->
        <!-- ... -->
        <!-- PAGE CONTENT STARTS HERE -->
        <!-- ... -->
        <!-- ... -->
        <!-- ... -->

        <a name="top"></a>

        <h4>
          The Fan Factor</h4>
          <h3>
		As time has passed, the National Basketball Association’s popularity has skyrocketed with the game going global. However, is there a correlation between team performance and their average attendance? What are the characteristics of teams with high attendance? And how can the data be used to predict attendance for the following season? 
        </h3>
        <h5>By Jacob LeRea</h5>
<img src= "steph.jpg" alt="an image of Steph Curry celebrating with fans, from NBA's website of a Golden State Warriors Championship parade" height="400" width="700px">
        

    <h5>
        <p>
          In 2010, my father took me to my first ever NBA game as my favorite team, the Boston Celtics, were in town to face off against the New York Knicks. Because it was my first NBA game, I had little idea about the game’s environment so when I saw Madison Square Garden for the first time, I was stunned. The bright lights gleamed off the hardwood. The aroma of popcorn, cotton candy, and beer saturated the air. Loud rap music boomed out of large speakers. The large screens and top-notch graphics on the Jumbotron captivated my eyes. However, what stuck with me most was how engaged New York Knicks fans were. The crowd would consistently go berserk, play after play. “Let’s Go Knicks” would echo throughout the garden. And because the fanbase is comprised of New Yorkers, of course, wide-eyed 6-year-old me got cursed out by a Knicks fan for rocking my Kevin Garnett jersey. The more I followed basketball, the more I understood the significance of fans. It became evident to me that there’s a significant connection between team success and fan engagement, with both drastically affecting each other. 
        </p>

        <p>
          Before diving into the data, it’s important to acknowledge professional NBA organizations have two main goals: to win a championship and make money. While these goals may seem distinct, they are deeply intertwined and shape the decision-making processes of teams both on and off the court. NBA Attendance is not only a a reflection of an organization’s ability to construct a viable, cohesive roster and engage fans, but a key indicator of its success in achieving both of its primary goals. Therefore, understanding the relationship between winning, NBA attendance, and organizational objectives is essential for NBA franchises and fans to understand the league’s landscape and team’s goals.

    
       	<h3>What the Now Tells Us</h3>
    <h5>
        <p>
          If there is any doubt about the NBA's rise in popularity, the league has set records for regular-season total attendance, average attendance, percentage of capacity, and sellouts for two years in a row, according to the NBA Public Communications Office. However, did it affect the success of teams? Here are the following twelve teams that sold out every true home game:
				<ol>
					<li>Boston Celtics</li>
					<li>Cleveland Cavaliers</li>
					<li>Dallas Mavericks</li>
					<li>Denver Nuggets</li>
					<li>Golden State Warriors</li>
					<li>Miami Heat</li>
					<li>Milwaukee Bucks</li>
					<li>Minnesota Timberwolves</li>
					<li>Philadelphia 76ers</li>
					<li>Phoenix Suns</li>
					<li>Sacramento Kings</li>
					<li>Utah Jazz</li>
		<h5>		
      	<h5>Based on the 23-24 season, the average amount of Home Wins was 22.3. To see if having more fans leads to winning, let’s examine how each of these twelve teams performed at home:</h5>
    <h5>    

          <iframe title="Teams that Sold Out Every Home Game and Their Record  " aria-label="Table" id="datawrapper-chart-ly8cL" src="https://datawrapper.dwcdn.net/ly8cL/2/" scrolling="no" frameborder="0" style="border: none;" width="740" height="511" data-external="1"></iframe>

        <p>
          <h5>Out of the 12 teams, nine of them had an above-average amount of home wins this season with the Heat, Jazz, and Warriors all not qualifying. All nine of those teams successfully made it to the postseason this year, with eight of them reaching the actual playoffs (Sacremento lost in the Play-In). This suggests that there may be a positive relationship between fan support at home games and team performance.<h5>
      	</p>
      	<h3>Is this a Trend?</h3>
                <p>
         Based on the 23-24 NBA season, teams with more consistent attendance are more likely to win. But is this a common trend over time in the NBA? In order to answer this question, the average placement of each team over the past three seasons was calculated. Additionally, using ESPN’s NBA Attendance Report which is updated weekly, the average total fans a team gets a year was calculated using the past three NBA seasons as well. After both were calculated, the 10 best and worst performing teams based off standing position were separated, along with each team’s specific total fan average. 
         		</p>

         <iframe title="Top Team Teams with their Total Fans Over 3 Seasons" aria-label="Scatter Plot" id="datawrapper-chart-ImjSc" src="https://datawrapper.dwcdn.net/ImjSc/6/" scrolling="no" frameborder="0" style="border: none;" width="636" height="673" data-external="1"></iframe>


         <iframe title="Worst Teams with their Total Fans Over 3 Seasons " aria-label="Scatter Plot" id="datawrapper-chart-ROJTf" src="https://datawrapper.dwcdn.net/ROJTf/2/" scrolling="no" frameborder="0" style="border: none;" width="524" height="681" data-external="1"></iframe>

        <p>
          Based off the graphs, out of the 10 best teams, only the Phoenix Suns, Minnesota Timberwolves, and Memphis Grizzlies didn’t reach the 700k fan threshold. Out of the 10 worst teams, six of them didn’t reach the 700k fan threshold. The more successful teams average more total fans a season than the failing ones. The relationship between winning and fan engagement forms a positive feedback loop, where success on the court drives increased fan support, which, in turn, enhances the team's competitiveness and financial stability. 
        </p>
		<h3>The Market Factor</h3>
        <p>
          But what role does the actual market play in this? Market pertains to the region a team is located, operates, and draws a fan base. The previously mentioned three teams that didn’t meet the 700k fan threshold are all located in cities that the NBA considers smaller markets (Phoenix, Minneapolis, and Memphis) compared to the likes of large markets, such as New York City, Chicago, and Los Angeles. 

        </p>

        <p>
          Teams located in larger markets often benefit from a larger population base, greater economic activity, and stronger media presence. This leads to higher attendance numbers and increased fan engagement, providing teams with a competitive advantage both on and off the court. In contrast, teams in smaller markets face challenges in attracting and retaining fans, particularly during periods of poor performance or rebuilding phases. Out of the 10 worst performing teams over the past three seasons, all 10 have been considered to be in a rebuilding phase at one point over the with all of them having at least one draft lottery selection over the past three seasons. NBA Comissioner Adam Silver understands the potential problem, stating, “I believe it’s an area where we can do better.”. 
        </p>

        <p>
          The data analyzed is not only telling about the current and past landscape of the NBA, but can be by teams and the NBA to create future advantages. 

        </p>
        <p>
          A team’s performance from the previous season has been shown to carry over into next season, as fan numbers are usually dependent on it. Take into consideration the New York Knicks. For the majority of the 2010s, the Knicks were considered one of the league’s laughing stocks. However, the Knicks have seen recent success as showed by the table. 
       	</p>

       <iframe title="Knicks Fan and Team Performance Over Past 3 Seasons" aria-label="Table" id="datawrapper-chart-0Wecr" src="https://datawrapper.dwcdn.net/0Wecr/2/" scrolling="no" frameborder="0" style="border: none;" width="650" height="318" data-external="1"></iframe>


        <p>
          In 2022-23, the New York Knicks finished eighth in the entire NBA: the highest they have placed in NBA League standings since 2013, where they were seventh total. This resulted in the Knicks having the fifth highest Total Fans during the 23-24 season, as their success from the previous season encouraged fans to be active in supporting the team. This has ultimately paid off, as the Knicks in the 23-24 season have been one of the best teams in basketball, as shown by their place in league standings. Based off the Knicks success this year, the NBA can predict that more people will be willing to go to Knicks games next season, meaning they can see record attendance numbers next year which can lead to more winning. 
        </p>

        <p>
          While the numbers can quantify attendance figures, they can’t actual tell how engaged fans at a game are, only people who are at the game can explain that, especially the players. Players are the ones that experience both the game and the audience. When a team wins or loses, it usually falls onto the players. 
        </p>

        <p>
          Former professional NBA player and current New York Knicks, John Wallace, who played from 1996-2004, spent several seasons in vastly different markets, including New York for two seasons. Currently, Wallace is a Knicks Ambassador meaning he spends time with fans at home games while being present within the organization. Wallace only played in New York for two seasons, but when reflecting on his time playing in Madison Square Garden, Wallace claimed “It always helped you. It was a place I played in in college. It always gave you that extra incentive to play well in front of people you know truly care about the game.”. Wallace thrived off the energy of the fans when he stepped onto the hardwood. In a day and age where the world is so connected and social media is a large presence, players most likely care more about the fan’s perspectives now more than ever. 
        </p>

        <p>
          By prioritizing fan engagement, investing in player development, and understanding the dynamics of NBA markets, teams can position themselves for this positive feedback loop that covers both goals of an NBA franchise. 
        </p>
    <h5>

        <h6>
          Jacob LeRea is a Sophomore Broadcast and Digital Journalism student. This paper was written for JNL 221 and Professor Nausheen Husain.
        </h6>

        <!-- ... -->
        <!-- ... -->
        <!-- ... -->
        <!-- END PAGE CONTENT -->
        <!-- ... -->
        <!-- ... -->
        <!-- ... -->
        
      </div>
    </main>
    <!-- /.container -->

    <script src="../assets/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
