---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Nov 13, 2022 15:38:12").getTime(); // Set the date we're counting down to
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
## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

We had 9 matches with 200 unique people and the biggest lobby had 100 playing. There were 0 people who played every match. The highest XP level was 'SEN Bugha' at 297. The lowest XP was 'Falconer' at 57, welcome to our lobby you GOAT! About 97.6% of us used girl skins. Nobody killed an NPC, what gives? By the way, Three people need to turn off ANONYMOUS MODE. Sixteen people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: SurfWitch(34), Kor(32), Tigeress(25)<br>
* Most common pickaxes: IceBreaker(65), StarWand(31), StuddedAxe(26)<br>
* Most common emotes: GetGriddy(33), Bringitaround(23), TakeTheL(23)<br>

Bot identified 35 error occurances affecting 31 player(s) with a net error balance of 56.00. Only ~72.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: [FNCS] WAVE VADEAL, Falcon TaySon, ManCity Hellf, WAVE JannisZ, [FNCS] alex, [FNCS] Bravado FKS, [FNCS] cold, [FNCS] Cuhmmandment, [FNCS] FS Edgey, [FNCS] FS on1, [FNCS] GUILD Hen 75, [FNCS] GXR Queasy, [FNCS] J?efn, [FNCS] WAVE NOAHREYL, alex, Baily, BL Kami, EdRoadToGlory, Falcon Spy, favs3x, FS Edgey, Guild Anas, Jamper, kitoz, ManCity Threa, Mikson, trulex 381, TT9 Chico, vic0, WAVE NOAHREYL, Yousrixd. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 15.4% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|11,526|00|11,582|85.1%|0.0%|0.0%|0.0%|0.0%|15.4%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|$100k|Tundra Veno|266.0|9.3 <5,4,21,32,1,2,1,14,4>|25 (3.1) <3,4,3,0,7,2,2,3,1>|0|0|0|0|22%|60|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|2|$100k|GXR Queasy|246.0|9.3 <5,4,21,32,1,2,1,14,4>|15 (2.1) <1,2,1,0,4,1,2,0,4>|0|0|0|0|11%|25|![](https://media.fortniteapi.io/images/c5ee0db8f7bdc6bfa2b925ab5eb8c7b9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ad66c8fb852a29ebdb4167c0562bf30f/transparent.png){:height="35px"}|
|3|$70k|BL Settyz 8|246.0|10.6 <1,6,34,2,32,1,14,4,1>|18 (2.3) <2,1,1,3,0,4,2,2,3>|0|0|0|0|56%|55|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|4|$70k|AST Th0masHD|243.0|11.4 <11,15,8,7,4,4,7,13,34>|22 (2.8) <3,3,3,2,3,4,3,1,0>|0|0|0|0|0%|11|![](https://media.fortniteapi.io/images/d369130-9e518e8-cc5bfb6-a52d7c6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|5|$60k|BL Kami|242.0|10.6 <1,6,34,2,32,1,14,4,1>|16 (2.7) <4,3,0,1,1,4,0,0,3>|0|0|0|0|22%|77|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|6|$60k|cold|222.0|14.7 <47,1,6,17,3,40,11,5,2>|18 (3.0) <0,6,0,1,1,0,3,2,5>|0|0|0|0|100%|11|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|7|$45k|cented -_-|214.0|14.7 <47,1,6,17,3,40,11,5,2>|14 (2.8) <0,0,1,1,3,0,0,4,5>|0|0|0|0|0%|111|![](https://media.fortniteapi.io/images/86da499-f41aa44-6696faf-408b001/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|8|$45k|trippernn|207.0|11.4 <11,15,8,7,4,4,7,13,34>|4 (1.3) <0,0,2,1,0,0,1,0,0>|0|0|0|0|22%|34|![](https://media.fortniteapi.io/images/ea4a5d0-7c1cd4a-7a9e792-7d981d2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|9|$35k|xeat|178.0|17.6 <15,7,17,13,28,9,5,48,16>|12 (3.0) <0,0,2,3,0,2,5,0,0>|0|0|0|0|0%|31|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|10|$35k|KBR|178.0|17.6 <15,7,17,13,28,9,5,48,16>|12 (1.7) <1,4,0,1,1,1,3,0,1>|0|0|0|0|0%|71|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|11|$30k|Acorn|169.0|18.6 <2,42,16,6,17,3,18,22,41>|11 (2.2) <4,0,1,3,0,1,2,0,0>|0|0|0|0|0%|45|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ad66c8fb852a29ebdb4167c0562bf30f/transparent.png){:height="35px"}|
|12|$30k|kitoz|165.0|19.8 <13,3,11,18,44,36,10,21,22>|16 (3.2) <3,3,4,2,0,0,4,0,0>|0|0|0|0|0%|58|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|13|$25k|Falcon Refsga|164.0|17.0 <17,25,22,23,15,20,21,2,8>|10 (2.5) <0,0,0,0,4,1,0,1,4>|0|0|0|0|0%|47|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|14|$25k|Not_BadSnipR|161.0|20.3 <7,38,20,38,13,16,8,38,5>|16 (2.3) <7,1,1,0,1,1,1,0,4>|0|0|0|0|11%|23|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|15|$20k|Larson .|161.0|22.2 <50,5,9,10,10,43,6,42,25>|14 (3.5) <0,3,4,3,0,0,4,0,0>|0|0|1|0|33%|13|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|16|$20k|WAVE NOAHREYL|161.0|20.3 <7,38,20,38,13,16,8,38,5>|16 (3.2) <1,0,2,0,0,2,6,0,5>|0|0|0|0|0%|35|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|17|$15k|GUILD Hen 75|161.0|22.3 <40,2,24,43,37,41,4,1,9>|18 (4.5) <0,4,0,0,0,0,3,6,5>|0|0|0|0|100%|28|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|18|$15k|vic0|160.0|22.8 <18,16,36,36,8,8,20,18,45>|25 (3.6) <3,2,0,1,4,11,2,2,0>|0|1|0|0|33%|87|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|19|$10k|FS Edgey|159.0|18.6 <2,42,16,6,17,3,18,22,41>|6 (1.5) <0,0,0,3,1,1,0,1,0>|0|0|0|0|0%|35|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|20|$10k|Avery|159.0|19.7 <25,31,7,1,33,32,19,11,18>|15 (2.1) <0,1,2,4,0,2,1,4,1>|0|0|0|0|11%|58|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|21|$8k|smіte|159.0|22.2 <50,5,9,10,10,43,6,42,25>|13 (2.2) <0,4,2,1,3,0,1,0,2>|0|1|0|1|44%|31|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|22|$8k|bifrost klown|158.0|17.0 <17,25,22,23,15,20,21,2,8>|7 (1.4) <0,0,1,1,0,0,1,2,2>|0|0|0|0|11%|95|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|23|$7k|FOKUS Vortex|155.0|22.3 <40,2,24,43,37,41,4,1,9>|15 (3.8) <0,3,0,0,0,0,7,3,2>|0|0|0|0|0%|34|![](https://media.fortniteapi.io/images/1e55a45-cb54ceb-bafa8c9-805b40b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|24|$7k|tundra pinquk|155.0|18.7 <21,24,12,11,20,22,23,24,11>|13 (2.2) <1,1,2,7,1,0,0,0,1>|0|0|0|0|11%|14|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|25|$5k|Jоefn|155.0|20.4 <10,30,1,42,11,27,17,20,26>|17 (2.4) <3,0,4,1,2,3,3,1,0>|0|0|0|0|11%|49|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|26|$5k|Siko Vortexer|155.0|21.1 <29,9,39,16,2,33,3,46,13>|12 (2.4) <0,4,1,3,2,0,0,0,2>|0|1|1|1|33%|41|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|27|$4,750|zAndy|153.0|20.4 <10,30,1,42,11,27,17,20,26>|16 (2.7) <2,0,5,0,4,2,2,1,0>|0|0|0|0|67%|13|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|28|$4,750|Guild Anas|153.0|18.7 <21,24,12,11,20,22,23,24,11>|12 (2.0) <4,0,3,0,1,1,2,0,1>|0|0|0|0|89%|40|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|29|$4,000|bevvys|153.0|21.1 <29,9,39,16,2,33,3,46,13>|11 (2.2) <0,1,0,2,3,0,3,0,2>|0|0|0|0|100%|53|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|30|$4,000|TT9 Chico|150.0|19.8 <6,8,37,31,26,5,16,32,17>|12 (2.4) <2,2,0,0,1,6,1,0,0>|0|0|0|1|11%|45|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|31|$3,500|Cuhmmandment|149.0|19.7 <25,31,7,1,33,32,19,11,18>|10 (1.4) <1,1,0,2,2,0,1,2,1>|0|0|0|0|0%|33|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|32|$3,500|Phzin 愛|145.0|19.8 <13,3,11,18,44,36,10,21,22>|6 (2.0) <0,0,0,1,0,0,3,0,2>|0|0|0|0|44%|51|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|33|$3,500|Fatch|136.0|23.0 <8,29,10,20,9,15,25,47,44>|10 (2.0) <0,0,3,2,2,2,0,0,1>|0|0|0|0|22%|58|![](https://media.fortniteapi.io/images/fe959e1e4f2e3f3c16c5dc9fb09765d6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|34|$3,500|trulex 381|134.0|19.8 <6,8,37,31,26,5,16,32,17>|4 (1.0) <1,0,0,1,0,1,1,0,0>|0|0|0|0|0%|38|![](https://media.fortniteapi.io/images/4cf0e96-cd67885-b054b0f-e54d851/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|35|$3,500|TSM Reet|132.0|22.6 <46,19,18,21,35,6,27,19,12>|10 (2.0) <0,2,1,0,0,3,0,1,3>|0|0|0|0|11%|31|![](https://media.fortniteapi.io/images/4eeca0c-54bb892-ff4f01a-6538f2a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|36|$3,500|NRG Clix|128.0|22.6 <9,34,32,5,36,12,26,29,20>|12 (3.0) <4,0,0,5,2,1,0,0,0>|0|0|0|0|0%|56|![](https://media.fortniteapi.io/images/99dbb44-e5cf279-6fdc8de-0462ab4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|37|$3,500|WAVE JannisZ|126.0|22.3 <22,27,38,27,21,25,2,36,3>|12 (1.7) <1,1,2,1,1,0,2,0,4>|0|0|0|0|0%|92|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|38|$3,500|WAVE VADEAL|126.0|22.3 <22,27,38,27,21,25,2,36,3>|12 (2.4) <3,0,0,1,1,0,3,0,4>|0|0|0|0|22%|13|![](https://media.fortniteapi.io/images/f7352c1ab53561c594a12499d3810881/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|39|$3,500|Siko Merijn|122.0|22.8 <18,16,36,36,8,8,20,18,45>|6 (1.5) <0,1,1,0,0,2,2,0,0>|0|1|0|1|89%|55|![](https://media.fortniteapi.io/images/ea4a5d0-7c1cd4a-7a9e792-7d981d2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|40|$3,500|PaMstou|122.0|23.0 <8,29,10,20,9,15,25,47,44>|3 (1.5) <2,0,1,0,0,0,0,0,0>|0|0|0|0|11%|32|![](https://media.fortniteapi.io/images/fe959e1e4f2e3f3c16c5dc9fb09765d6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|41|$3,000|EpikWhale|118.0|22.6 <46,19,18,21,35,6,27,19,12>|3 (1.0) <0,1,0,0,0,1,0,1,0>|0|0|0|0|67%|22|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|42|$3,000|DIG Duke|116.0|22.6 <9,34,32,5,36,12,26,29,20>|6 (1.2) <2,1,1,1,0,1,0,0,0>|0|0|0|0|11%|78|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|43|$3,000|PSG TNA KEWL|116.0|26.4 <3,33,44,4,18,23,35,45,33>|10 (2.5) <4,1,0,3,2,0,0,0,0>|0|0|0|0|100%|25|![](https://media.fortniteapi.io/images/eb39b40-d9c7ad6-4136277-f1fa182/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|44|$3,000|CubeX Khanada|113.0|24.0 <24,13,23,26,27,17,28,44,14>|12 (2.0) <1,2,1,3,0,1,0,0,4>|0|1|0|2|11%|40|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|45|$3,000|Wox|113.0|28.8 <34,46,29,49,42,7,9,3,40>|12 (2.4) <0,0,1,0,1,3,1,6,0>|0|0|0|0|11%|20|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|46|$3,000|ALBA Zagou281|112.0|27.7 <4,20,2,25,45,44,34,28,47>|11 (2.2) <5,1,3,1,0,0,0,1,0>|0|0|0|0|0%|53|![](https://media.fortniteapi.io/images/10152349852b512cf59d93156e451ca7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|47|$3,000|PSG TNA Yumi|108.0|26.4 <3,33,44,4,18,23,35,45,33>|6 (2.0) <3,0,0,2,0,0,0,0,1>|0|0|0|0|56%|42|![](https://media.fortniteapi.io/images/eb39b40-d9c7ad6-4136277-f1fa182/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|48|$3,000|Falcon TaySon|106.0|27.6 <37,12,46,22,49,14,24,7,37>|10 (3.3) <0,2,0,0,0,5,0,3,0>|0|0|0|0|89%|35|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|49|$3,000|Hijoe|106.0|24.1 <26,17,26,28,16,38,42,17,7>|8 (1.3) <1,1,2,1,1,0,0,2,0>|0|0|0|0|89%|33|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f50e3335f85347ba6346ec79a597d0e9/transparent.png){:height="35px"}|
|50|$3,000|EdRoadToGlory|106.0|25.6 <33,41,33,14,12,18,33,27,19>|10 (1.7) <0,2,0,2,1,2,0,1,2>|0|0|0|0|0%|23|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|51|$2,000|ALBA merem 魅|104.0|27.7 <4,20,2,25,45,44,34,28,47>|7 (1.8) <3,0,1,0,0,1,0,2,0>|0|0|0|0|100%|13|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|52|$2,000|Belusi|104.0|24.1 <26,17,26,28,16,38,42,17,7>|7 (2.3) <0,2,0,0,0,0,0,4,1>|0|1|0|0|11%|40|![](https://media.fortniteapi.io/images/e929e25a6235af435c07f8d7aad19ab3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|53|$2,000|Robbabkebab|103.0|28.8 <34,46,29,49,42,7,9,3,40>|7 (2.3) <0,0,0,0,0,2,2,3,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ee5a08b-89496af-c3093dc-d6c50bf/transparent.png){:height="35px"}|
|54|$2,000|Falcon Andile|103.0|26.8 <28,23,4,37,41,35,44,8,21>|9 (2.3) <0,1,5,0,0,0,0,1,2>|0|0|0|0|0%|25|![](https://media.fortniteapi.io/images/9ef8a5f2ce2eec295d3bf0aa460fb592/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|55|$2,000|BL MrSavage|103.0|30.2 <49,21,15,3,50,48,37,43,6>|8 (2.0) <0,1,1,5,0,0,0,0,1>|0|1|1|1|0%|14|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|56|$2,000|MackWood1x.|101.0|24.0 <24,13,23,26,27,17,28,44,14>|6 (1.5) <2,1,1,0,0,0,0,0,2>|0|0|0|0|0%|34|![](https://media.fortniteapi.io/images/b667ff2-c60b6a1-0ce08dd-3cbc910/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|57|$2,000|apeks IDrop 7|101.0|30.2 <49,21,15,3,50,48,37,43,6>|7 (1.4) <0,1,2,2,0,0,0,1,1>|0|0|0|0|100%|70|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|58|$2,000|GXR Malibuca|98.0|27.0 <20,22,35,8,22,30,29,31,46>|10 (2.0) <0,1,1,5,2,0,1,0,0>|0|0|0|0|0%|57|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|59|$2,000|GHC Rapit|97.0|26.8 <28,23,4,37,41,35,44,8,21>|6 (2.0) <0,0,3,0,0,0,0,2,1>|0|0|0|0|11%|50|![](https://media.fortniteapi.io/images/9ef8a5f2ce2eec295d3bf0aa460fb592/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|60|$2,000|chapix|96.0|27.6 <37,12,46,22,49,14,24,7,37>|5 (1.7) <0,0,0,2,0,0,1,2,0>|0|0|0|0|11%|30|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|61|$1,500|FaZe k1NG ㇺ|96.0|25.6 <33,41,33,14,12,18,33,27,19>|5 (1.3) <0,0,0,1,1,2,0,0,1>|0|0|0|0|11%|22|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|62|$1,500|ManCity Threa|95.0|25.2 <16,40,27,15,24,19,40,15,31>|5 (1.7) <0,1,0,0,0,0,0,3,1>|0|0|0|0|67%|43|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|63|$1,500|ManCity Hellf|94.0|29.8 <48,45,19,39,7,39,15,33,23>|11 (2.2) <0,0,2,0,4,2,2,0,1>|0|0|0|0|100%|41|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|64|$1,500|Merstach|92.0|27.0 <20,22,35,8,22,30,29,31,46>|7 (1.4) <0,1,1,2,0,0,1,2,0>|0|0|0|0|22%|51|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|65|$1,500|alice|91.0|25.2 <16,40,27,15,24,19,40,15,31>|3 (1.5) <2,0,0,0,0,0,0,1,0>|0|0|0|0|0%|28|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|66|$1,500|FS on1|91.0|33.0 <23,47,48,47,6,28,12,37,49>|14 (2.3) <4,0,1,0,3,1,3,2,0>|0|0|0|0|67%|24|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|67|$1,500|siko rifty 33|90.0|28.0 <38,32,43,9,5,24,39,30,32>|8 (2.0) <0,0,1,4,2,0,1,0,0>|0|0|0|0|56%|46|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|68|$1,500|CHIMPERATIE|89.0|29.6 <35,26,3,33,40,46,49,6,28>|7 (1.8) <0,2,2,0,0,0,0,2,1>|0|0|0|0|89%|62|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c713c090223cb2e8478dbfe6d5fd649/transparent.png){:height="35px"}|
|69|$1,500|Yousrixd|89.0|29.4 <31,44,14,12,47,45,31,26,15>|9 (1.8) <0,2,3,1,0,0,0,1,2>|0|0|0|0|11%|132|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ee5a08b-89496af-c3093dc-d6c50bf/transparent.png){:height="35px"}|
|70|$1,500|SEN Bugha|89.0|29.9 <43,10,13,34,38,26,45,10,50>|7 (1.8) <0,1,1,1,0,0,0,4,0>|0|0|0|0|100%|164|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|71|$1,000|WAVE Juu|85.0|29.4 <31,44,14,12,47,45,31,26,15>|7 (1.8) <1,0,0,1,0,0,0,2,3>|0|0|0|0|11%|107|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|72|$1,000|dig mero|81.0|29.9 <43,10,13,34,38,26,45,10,50>|3 (1.5) <0,1,0,0,0,0,0,2,0>|0|0|1|0|33%|19|![](https://media.fortniteapi.io/images/eb39b40-d9c7ad6-4136277-f1fa182/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|73|$1,000|Falconer|80.0|29.8 <48,45,19,39,7,39,15,33,23>|4 (1.3) <0,1,1,0,0,0,0,0,2>|0|0|0|0|11%|25|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|74|$1,000|Grolzz|80.0|28.0 <38,32,43,9,5,24,39,30,32>|3 (1.0) <0,1,0,0,1,1,0,0,0>|0|0|0|0|100%|31|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|75|$1,000|Mikson|79.0|30.9 <41,35,49,19,19,13,50,25,27>|7 (2.3) <0,0,0,0,5,1,0,0,1>|0|0|0|0|0%|60|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb46e47da50c22a3ef2e7fec4c4bca2e/transparent.png){:height="35px"}|
|76|$1,000|ManCity Skram|79.0|29.6 <35,26,3,33,40,46,49,6,28>|2 (1.0) <0,0,1,0,0,0,0,1,0>|0|0|0|0|33%|30|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|77|$1,000|aqua 42|77.0|30.1 <30,39,5,40,39,37,22,49,10>|5 (1.7) <0,0,3,0,1,0,1,0,0>|0|0|0|0|0%|84|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|78|$1,000|Rezon Ay|75.0|30.1 <30,39,5,40,39,37,22,49,10>|4 (1.3) <0,0,2,0,1,0,1,0,0>|0|0|0|0|0%|29|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|79|$1,000|FLu bacca|73.0|33.0 <23,47,48,47,6,28,12,37,49>|5 (2.5) <0,0,0,0,4,0,0,1,0>|0|1|1|1|100%|33|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|80|$1,000|CPHF PabloWin|71.0|29.0 <42,36,28,35,29,31,13,12,35>|4 (1.3) <0,1,0,1,0,0,0,2,0>|0|0|0|0|0%|70|![](https://media.fortniteapi.io/images/e69e001baccca6b4f6e2b96b4c370822/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/81f8e8dd30cc7948c0a4fe364235921d/transparent.png){:height="35px"}|
|81|$750|2AM Parz|70.0|32.3 <44,14,41,41,34,21,32,16,48>|7 (2.3) <0,0,0,0,0,4,2,1,0>|0|0|0|0|0%|11|![](https://media.fortniteapi.io/images/99dbb44-e5cf279-6fdc8de-0462ab4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|82|$750|alex|68.0|33.8 <27,48,25,50,23,10,43,35,43>|9 (3.0) <0,0,1,0,4,4,0,0,0>|0|0|0|0|0%|25|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|83|$750|CPHF Swag|67.0|29.0 <42,36,28,35,29,31,13,12,35>|2 (2.0) <0,2,0,0,0,0,0,0,0>|0|0|0|0|89%|32|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|84|$750|Exeed artor|67.0|30.9 <41,35,49,19,19,13,50,25,27>|1 (1.0) <0,0,0,0,0,0,0,0,1>|0|0|0|0|78%|11|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|85|$750|Rays|66.0|32.3 <44,14,41,41,34,21,32,16,48>|5 (1.7) <0,2,0,0,0,2,0,1,0>|0|0|0|0|33%|39|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|86|$750|cr pepo ay ло|61.0|35.0 <14,43,45,44,14,47,38,41,29>|9 (3.0) <4,0,0,0,4,0,0,0,1>|0|0|0|0|100%|71|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|87|$750|Jamper|60.0|32.7 <32,37,42,30,31,42,41,9,30>|9 (1.5) <1,0,1,0,0,1,2,3,1>|0|0|0|0|89%|14|![](https://media.fortniteapi.io/images/74c6035f0634c8d53e98435652b9fd39/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|88|$750|Baily|60.0|33.8 <27,48,25,50,23,10,43,35,43>|5 (1.3) <1,0,0,0,1,2,1,0,0>|0|0|0|0|0%|39|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|89|$750|Peterbot ち|58.0|32.7 <32,37,42,30,31,42,41,9,30>|8 (1.3) <0,0,1,0,2,1,1,2,1>|0|0|0|0|0%|35|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|90|$750|CRuna3x|53.0|35.0 <14,43,45,44,14,47,38,41,29>|5 (1.7) <2,0,0,0,1,0,0,0,2>|0|0|0|0|11%|1|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|91|$500|favs3x|49.0|32.6 <36,18,40,29,25,34,30,39,42>|6 (1.2) <1,1,0,1,1,0,2,0,0>|0|0|0|0|44%|40|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|92|$500|TSM Snacky3x|47.0|32.6 <36,18,40,29,25,34,30,39,42>|5 (1.3) <0,2,1,0,0,1,0,0,1>|0|0|0|0|44%|33|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|93|$500|PSG TNA Muz|46.0|38.6 <19,49,50,48,46,11,48,40,36>|5 (1.7) <1,0,0,0,0,3,0,1,0>|0|1|0|1|0%|35|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|94|$500|PWR looter|42.0|38.6 <19,49,50,48,46,11,48,40,36>|3 (3.0) <3,0,0,0,0,0,0,0,0>|0|0|1|0|0%|35|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|95|$500|Bravado FKS|41.0|32.1 <39,28,30,24,30,29,36,34,39>|4 (1.3) <0,1,2,1,0,0,0,0,0>|0|0|0|0|56%|32|![](https://media.fortniteapi.io/images/9dbfba8d8a641c7964207739b01778f6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|96|$500|jace 21|40.0|36.9 <45,11,31,46,43,49,46,23,38>|2 (1.0) <0,1,0,0,0,0,0,1,0>|0|0|0|0|22%|57|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|97|$500|basil|38.0|36.9 <45,11,31,46,43,49,46,23,38>|1 (1.0) <0,1,0,0,0,0,0,0,0>|0|0|0|0|56%|66|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|98|$500|reтake|34.0|41.4 <12,50,47,45,48,50,47,50,24>|2 (2.0) <2,0,0,0,0,0,0,0,0>|0|0|3|0|11%|74|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|99|$500|nov1ce 7|34.0|41.4 <12,50,47,45,48,50,47,50,24>|2 (1.0) <1,0,0,0,0,1,0,0,0>|0|0|0|0|44%|22|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|100|$500|Falcon Spy|33.0|32.1 <39,28,30,24,30,29,36,34,39>||0|0|0|0|0%|13|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

