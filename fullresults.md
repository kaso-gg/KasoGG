---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Sep 14, 2022 15:54:09").getTime(); // Set the date we're counting down to
    var x = setInterval(function () {
        var timeNow = new Date().getTime(); // Get today's date and time
        var distance = timeNow - countUpdDate; // Find the distance between now and the count down date
        var days = Math.floor(distance / (1000 * 60 * 60 * 24));
        var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        var seconds = Math.floor((distance % (1000 * 60)) / 1000);
        var minutesString = minutes.toString();
        var secondsString = seconds.toString();
        if (minutesString.length < 2) {
            minutesString = "0" + minutesString;
        }
        if (secondsString.length < 2) {
            secondsString = "0" + secondsString;
        }
        document.getElementById("countUpTimer").innerHTML = minutesString + ":" + secondsString + " since updt"; // Display the result in the element with id="demo"
        // If the count down is finished, write some text
        if (distance < 0) {
            clearInterval(x);
            document.getElementById("countUpTimer").innerHTML = "EXPIRED";
        }
    }, 1000); // Update the count down every 1000 milliseconds
</script>


<strong><span id="countUpTimer" style="color:red;background-color:white;font-size:add_size"></span><strong>

## [GO BACK](https://www.kaso.gg)

4 matches, 46 unique players, biggest lobby 39. 14 gamers played every match tonight. Highest level player was AMYLCx at 311! Lowest level player was MTM3530 at 57. Most common skin was Son Goku, common axe was Ice Breaker.

Here' a breakdown of points allocation across all players and matches. This data helps to understand for example that elims accounted for 5.6% of all points earned this session and 3.0% of the points were given out for just being the first one to be eliminated, LOL. E1 are points for getting first elimination and D1 is for being the first one to BE eliminated. TR is the bus driver thanks percentage!
 
| Points | Placement | Knock | Elims | Survival | Siphon | FirstElim | FirstDead | ThanksBus |
| :--- | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1,065|28.8%|19.0%|5.6%|21.3%|8.6%|-1.9%|3.0%|15.6%|

### ACTIVE POINTS ALGORITHM 2022.08.21:
- Placement: 1st = 5 pts down to 10th = 0.5 pt
- Noc/Elim: 2 pt per knock, 0.5 pt per elim (let 'em revive...knock again!)
- Survival: 0.15 pt per minute (about 3pts to end game)
- Elim Siphon: 0.5 pt for each of your victim's kill count
- PENALTY: -5 pts first elim of the game (NPC's don't count)
- Bonus: 15 pts if you're the first eliminated (self-elim doesn't count)
- Bonus: 2 pt for thanking bus driver
<br>
<br>

FULL TABLE AND HEADER HERE

