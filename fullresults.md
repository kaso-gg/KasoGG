---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Sep 14, 2022 20:43:14").getTime(); // Set the date we're counting down to
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

We had 2 matches with 7 unique people and the biggest lobby had 6 playing. There were 4 people who played every match. The highest XP level was 'CPK_jamieo' at 256. The lowest XP was 'SpideyTTV-' at 164, welcome to our lobby you GOAT!Thank you everyone for NOT playing on Anonymous mode. 4 people have donkey laugh in their locker emotes, LOL!

Most common skins: Marshmello(1), Mariana(1), Bigfoot(1)
Most common pickaxes: IdentityDisc(1), Flawless(1), CrescentShroom(1)
Most common emotes: LaughItUp(4), TheDip(4), JiggleJiggle(3)

Bot identified 8 error occurances affecting 6 player(s) with a net error balance of 8.62. Only ~8.62 total tournament points are at question due to kill feed data discrepancies. Affected players are: CPK_kaso, thegodamongus345, CPK_jamieo, ?rab0n0F, PopPopTaterhead, SpideyTTV-. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 13.9% of all points earned this session and 11.2% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|62|00|71|68.3%|0.0%|18.1%|11.2%|0.0%|13.9%|0.0%|2.4%|

| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|G^gg|thegodamongus345|15.9|1.0 <1,2>|3 (1.0) <2,1>|0|0|0|0|50%|250|![](https://media.fortniteapi.io/images/dfaafc5-4d29590-774f1a3-ee676eb/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/8ce4c1a-87ff7fd-adb3f91-25d7cb2/transparent.png){:height="35px"}|
|2|bitties|CPK_jamieo|14.0|1.0 <2,1>|1 (0.0) <0,1>|0|0|0|0|50%|256|![](https://media.fortniteapi.io/images/8f227905f8f190434750999cd3b10fe9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/353476001a41d4b0ad0bb3e6e90ca158/transparent.png){:height="35px"}|
|3|stars|CPK_kaso|12.6|3.0 <3,4>|2 (1.0) <1,1>|0|0|0|0|50%|194|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|4|nada!|Ɔrab0n0F|10.0|4.0 <4,5>|1 (0.0) <1,0>|0|0|0|0|50%|197|![](https://media.fortniteapi.io/images/1a238b8a99e547fd5adff822277a2bb9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9bfd9bacc26801f4fd617575e69ecbb9/transparent.png){:height="35px"}|
|5|bruh?|SpideyTTV-|8.8|3.0 <3>|1 (1.0) <1>|1|0|0|0|100%|164|![](https://media.fortniteapi.io/images/d6400d2b9f845912f10d954d324e373c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3591ee17867120d32feedd8945028f36/transparent.png){:height="35px"}|
|6||PopPopTaterhead|5.5|5.0 <5>|1 (1.0) <1>|0|0|0|0|100%|207|![](https://media.fortniteapi.io/images/01fb97b67e3078c01fc6cc353499279c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a02b9082525370e9088801261a77c3e1/transparent.png){:height="35px"}|
|7||Seven SIy|4.1|6.0 <6>|0 (0.0) <0>|0|0|0|0|100%|214|![](https://media.fortniteapi.io/images/3465cb35e5189c394c21a1694e165fab/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4e982968d59f16afb3b5c5f146aa3439/transparent.png){:height="35px"}|

