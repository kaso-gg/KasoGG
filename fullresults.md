---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Sep 16, 2022 19:55:25").getTime(); // Set the date we're counting down to
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


<style>
      .tableFixHead {
        overflow-y: auto;
        height: 195px;
      }
      .tableFixHead thead th {
        position: sticky;
        top: 0;
      }
      table {
        border-collapse: collapse;
        width: 100%;
      }
      th,
      td {
        padding: 2px 2x;
        border: 1px solid #ccc;
      }
      th {
        background: #eee;
      }
</style>

<strong><span id="countUpTimer" style="color:red;background-color:white;font-size:add_size"></span></strong>

## [GO BACK](https://www.kaso.gg)

<br>
<br>

We had 2 matches with 5 unique people and the biggest lobby had 4 playing. There were 3 people who played every match. The highest XP level was 'CJ-n-wild' at 267. The lowest XP was 'Walking_Dude' at 103, welcome to our lobby you GOAT!Thank you everyone for NOT playing on Anonymous mode. 1 people have donkey laugh in their locker emotes, LOL!

* Most common skins: Charlotte(1), Cammy(1), Blackheart(1)<br>
* Most common pickaxes: LeBeau'sBo(1), IdentityDisc(1), All-WeatherExtractor(1)<br>
* Most common emotes: JumpAround(3), CrowningAchievement(2), TheDip(2)<br>

Bot identified 4 error occurances affecting 3 player(s) with a net error balance of 4.79. Only ~4.79 total tournament points are at question due to kill feed data discrepancies. Affected players are: Walking_Dude, CPK_kaso, LetsGoooBuddy. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 10.5% of all points earned this session and 8.7% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|46|00|51|74.4%|0.0%|16.9%|8.7%|0.0%|10.5%|0.0%|0.0%|

| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|G^gg|Walking_Dude|16.1|1.0 <1,1>|3 (1.0) <2,1>|0|0|0|0|50%|103|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a02b9082525370e9088801261a77c3e1/transparent.png){:height="35px"}|
|2|bitties|CPK_kaso|11.9|3.0 <4,3>|1 (0.0) <0,1>|0|0|0|0|100%|196|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|3|stars|LetsGoooBuddy|11.6|2.0 <3,2>|1 (0.0) <0,1>|0|0|0|0|0%|241|![](https://media.fortniteapi.io/images/de92b06-8bbfd0f-cae852b-b674681/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb488368dc072c4b4e11f9c7a9dbb08e/transparent.png){:height="35px"}|
|4|nada!|CJ-n-wild|5.6|2.0 <2>|0 (0.0) <0>|0|0|0|0|0%|267|![](https://media.fortniteapi.io/images/ddb5dcf96f6154a21e90c80d0661d7a4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/13740ad6d3e279f08b9dbea3fd0f52bc/transparent.png){:height="35px"}|
|5|bruh?|K9Gizmo|5.4|4.0 <4>|0 (0.0) <0>|0|0|0|0|100%|247|![](https://media.fortniteapi.io/images/6cfd3b3628dc294d7f8cd19365035d68/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/53fc505eb57eddda378f01036da25181/transparent.png){:height="35px"}|

