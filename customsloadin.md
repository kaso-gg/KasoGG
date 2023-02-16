---
permalink: /customsloadin/
title: ""active customs code""
excerpt: ""All the details to join our customs""
markdown: kramdown
---
<meta http-equiv="refresh" content="15">
<script>
    var countUpdDate = new Date("Feb 16, 2023 10:56:24").getTime(); // Set the date we're counting down to
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


# <strong><span style="color:maroon;background-color:white">Kaso Customs</span></strong><br>

CustmKey: <strong><span style="color:black;background-color:white">feb2023_test</span></strong><br>
SvrRegion: <strong><span style="color:black;background-color:white">NA East</span></strong><br>
PlayMode: <strong><span style="color:black;background-color:white">Build</span></strong><br>
TeamSize: <strong><span style="color:black;background-color:white">Duos</span></strong><br>
FillMode: <strong><span style="color:black;background-color:white">Fill</span></strong><br>

Land at FRENZY FIELDS and stay there until the storm forces you out.

<strong><span id="countUpTimer" style="color:red;background-color:white;font-size:add_size"></span></strong>

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>
