---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Sep 14, 2022 19:05:56").getTime(); // Set the date we're counting down to
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

We had 2 matches with 2 unique people and the biggest lobby had 2 playing. There were 2 people who played every match. The highest XP level was 'CPK_jamieo' at 256. The lowest XP was 'CPK_kaso' at 194, welcome to our lobby you GOAT!Thank you everyone for NOT playing on Anonymous mode. 1 people have donkey laugh in their locker emotes, LOL!

Most common skins: Bigfoot(1), Aura(1)
Most common pickaxes: IdentityDisc(1), AbyssalBlade(1)
Most common emotes: GALAXIAN(1), FireSpinner(1), EagleFang(1)

No routine scoring errors were detected. Please notify us if you feel anything was missed.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for -22.1% of all points earned this session and 2.9% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|49|08|34|55.9%|0.0%|4.6%|2.9%|41.2%|-22.1%|4.1%|13.2%|

| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|G^gg|CPK_kaso|20.0|2.0 <2,2>|1 (0.0) <0,1>|2|0|1|0|50%|194|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|2|bitties|CPK_jamieo|14.0|1.0 <1,1>|1 (0.0) <0,1>|1|1|0|0|0%|256|![](https://media.fortniteapi.io/images/8f227905f8f190434750999cd3b10fe9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/353476001a41d4b0ad0bb3e6e90ca158/transparent.png){:height="35px"}|

