---
permalink: /killfeed/
title: "full killfeed"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Sep 14, 2022 19:22:05").getTime(); // Set the date we're counting down to
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

# Game <strong>One</strong> Killfeed<br>
# Game <strong>Two</strong> Killfeed<br>
CPKkaso <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> SevenSentry at 6:37 near <strong>CreamyCrossroads</strong>, with a Rifle from 6m (why you pick on NPCs?)<br>
CPKkaso <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> SevenSentry at 6:51 near <strong>CreamyCrossroads</strong>, with a Rifle from 9m (why you pick on NPCs?)<br>
CPKjamieo <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> BeachBomber at 7:33 near <strong>CreamyCrossroads</strong>, with a HeavyAR from 16m (why you pick on NPCs?)<br>
CPKjamieo <strong><span style="color:crimson;background-color:">Killed</span></strong> CPKkaso at 7:59 near <strong>CreamyCrossroads</strong>, with a Sniper from 67m<br>
CPKkaso <strong><span style="color:crimson;background-color:">Killed</span></strong> CPKjamieo at 8:11, with a Logout<br>
CPKkaso <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> BeachBomber at 1:46 near <strong>CreamyCrossroads</strong>, with a TacticalShotgun from 1m (why you pick on NPCs?)<br>
CPKkaso <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> SevenSentry at 2:20 near <strong>CreamyCrossroads</strong>, with a TacticalShotgun from 4m (why you pick on NPCs?)<br>
CPKjamieo <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> SevenSentry at 3:14 near <strong>CreamyCrossroads</strong>, with a HeavyAR from 10m (why you pick on NPCs?)<br>
CPKjamieo <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> SevenSentry at 6:15 near <strong>TiltedTowers</strong>, with a Shotgun from 6m (why you pick on NPCs?)<br>
CPKkaso <strong><span style="color:dodgerblue;background-color:yellow">BULLIED</span></strong> TheUnderwriter at 6:28 near <strong>TiltedTowers</strong>, with a Shotgun from 2m (why you pick on NPCs?)<br>
CPKjamieo <strong><span style="color:crimson;background-color:">Killed</span></strong> CPKjamieo at 8:02, with a Environment from 36m<br>
<!--CREATED BY CODE-->
<!--9/14/2022 7:22:05 PM-->
