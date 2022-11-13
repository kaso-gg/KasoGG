---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Nov 12, 2022 20:32:59").getTime(); // Set the date we're counting down to
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

We had 6 matches with 193 unique people and the biggest lobby had 100 playing. There were 7 people who played every match. The highest XP level was 'SEN Bugha' at 296. The lowest XP was 'Falconer' at 56, welcome to our lobby you GOAT! About 97.6% of us used girl skins. Nobody killed an NPC, what gives? By the way, Two people need to turn off ANONYMOUS MODE. Sixteen people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: SurfWitch(31), Kor(28), Tigeress(22)<br>
* Most common pickaxes: IceBreaker(55), StarWand(28), StuddedAxe(25)<br>
* Most common emotes: GetGriddy(32), TakeTheL(23), Bringitaround(21)<br>

Bot identified 25 error occurances affecting 24 player(s) with a net error balance of 34.00. Only ~50.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: WAVE JannisZ, [FNCS] alex, [FNCS] Bravado FKS, [FNCS] FS Edgey, [FNCS] FS on1, [FNCS] GXR Queasy, [FNCS] J?efn, [FNCS] WAVE VADEAL, alex, Baily, BL Kami, EdRoadToGlory, Falcon Spy, Falcon TaySon, favs3x, FS Edgey, Guild Anas, Jamper, ManCity Hellf, trulex 381, TT9 Chico, vic0, WAVE NOAHREYL, Yousrixd. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 16.6% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|6,590|00|6,624|83.9%|0.0%|0.0%|0.0%|0.0%|16.6%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|$200k|Tundra Veno|174.0|10.8 <5,4,21,32,1,2>|19 (3.8) <3,4,3,0,7,2>|0|0|0|0|17%|67|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|2|$140k|AST Th0masHD|155.0|8.4 <11,15,8,0,4,4>|16 (3.2) <3,3,3,0,3,4>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/d369130-9e518e8-cc5bfb6-a52d7c6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|3|$120k|GXR Queasy|154.0|10.8 <5,4,21,32,1,2>|9 (1.8) <1,2,1,0,4,1>|0|0|0|0|17%|38|![](https://media.fortniteapi.io/images/a40ba1726d5029ab566aed545e7c6493/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|4|$90k|trippernn|127.0|8.4 <11,15,8,0,4,4>|2 (2.0) <0,0,2,0,0,0>|0|0|0|0|33%|51|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|5|$70k|BL Kami|125.0|14.8 <1,6,34,0,32,1>|13 (2.6) <4,3,0,1,1,4>|0|0|0|0|17%|86|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|6|$60k|vic0|124.0|20.3 <18,16,36,36,8,8>|21 (4.2) <3,2,0,1,4,11>|0|1|0|0|33%|130|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|7|$50k|BL Settyz 8|115.0|14.8 <1,6,34,0,32,1>|8 (2.0) <2,1,1,0,0,4>|0|0|0|0|67%|83|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|8|$40k|Jоefn|113.0|20.2 <10,30,1,42,11,27>|13 (2.6) <3,0,4,1,2,3>|0|0|0|0|17%|37|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|9|$30k|Fatch|113.0|14.2 <8,29,10,0,9,15>|9 (2.3) <0,0,3,2,2,2>|0|0|0|0|17%|58|![](https://media.fortniteapi.io/images/fe959e1e4f2e3f3c16c5dc9fb09765d6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|10|$20k|zAndy|113.0|20.2 <10,30,1,42,11,27>|13 (3.3) <2,0,5,0,4,2>|0|0|0|0|67%|20|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|11|$16k|TT9 Chico|111.0|18.8 <6,8,37,31,26,5>|11 (2.8) <2,2,0,0,1,6>|0|0|0|1|0%|67|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|12|$14k|Acorn|110.0|16.0 <2,42,16,0,17,3>|8 (2.0) <4,0,1,2,0,1>|0|0|0|0|0%|50|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|13|$10,000|cold|105.0|19.4 <47,1,6,0,3,40>|8 (2.7) <0,6,0,1,1,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|14|$9,500|KBR|103.0|15.2 <15,7,17,0,28,9>|7 (1.8) <1,4,0,0,1,1>|0|0|0|0|0%|64|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|15|$8,000|FS Edgey|102.0|16.0 <2,42,16,0,17,3>|4 (1.3) <0,0,0,2,1,1>|0|0|0|0|0%|18|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|16|$7,000|xeat|101.0|15.2 <15,7,17,0,28,9>|6 (2.0) <0,0,2,2,0,2>|0|0|0|0|0%|46|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|17|$7,000|PaMstou|101.0|14.2 <8,29,10,0,9,15>|3 (1.5) <2,0,1,0,0,0>|0|0|0|0|0%|32|![](https://media.fortniteapi.io/images/fe959e1e4f2e3f3c16c5dc9fb09765d6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|18|$7,000|Not_BadSnipR|98.0|22.0 <7,38,20,38,13,16>|11 (2.2) <7,1,1,0,1,1>|0|0|0|0|0%|34|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|19|$7,000|cented -_-|97.0|19.4 <47,1,6,0,3,40>|4 (2.0) <0,0,1,0,3,0>|0|0|0|0|0%|133|![](https://media.fortniteapi.io/images/86da499-f41aa44-6696faf-408b001/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|20|$7,000|smіte|95.0|23.4 <50,5,9,0,10,43>|10 (2.5) <0,4,2,1,3,0>|0|1|0|1|50%|31|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|21|$7,000|trulex 381|95.0|18.8 <6,8,37,31,26,5>|3 (1.0) <1,0,0,1,0,1>|0|0|0|0|0%|38|![](https://media.fortniteapi.io/images/4cf0e96-cd67885-b054b0f-e54d851/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|22|$7,000|kitoz|94.0|21.4 <13,3,11,0,44,36>|11 (2.8) <3,3,4,1,0,0>|0|0|0|0|0%|69|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|23|$7,000|Larson .|93.0|23.4 <50,5,9,0,10,43>|9 (3.0) <0,3,4,2,0,0>|0|0|1|0|0%|1|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|24|$7,000|ALBA Zagou281|93.0|23.0 <4,20,2,0,45,44>|10 (2.5) <5,1,3,1,0,0>|0|0|0|0|0%|20|![](https://media.fortniteapi.io/images/10152349852b512cf59d93156e451ca7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|25|$7,000|Siko Merijn|90.0|20.3 <18,16,36,36,8,8>|4 (1.3) <0,1,1,0,0,2>|0|0|0|0|100%|41|![](https://media.fortniteapi.io/images/ea4a5d0-7c1cd4a-7a9e792-7d981d2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|26|$7,000|WAVE NOAHREYL|86.0|22.0 <7,38,20,38,13,16>|5 (1.7) <1,0,2,0,0,2>|0|0|0|0|0%|52|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|27|$7,000|Siko Vortexer|84.0|22.4 <29,9,39,0,2,33>|10 (2.5) <0,4,1,3,2,0>|0|0|1|0|17%|61|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|28|$7,000|Guild Anas|84.0|19.8 <21,24,12,0,20,22>|9 (2.3) <4,0,3,0,1,1>|0|0|0|0|100%|45|![](https://media.fortniteapi.io/images/e69e001baccca6b4f6e2b96b4c370822/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|29|$7,000|ALBA merem 魅|83.0|23.0 <4,20,2,0,45,44>|5 (1.7) <3,0,1,0,0,1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|30|$7,000|tundra pinquk|82.0|19.8 <21,24,12,0,20,22>|8 (1.6) <1,1,2,3,1,0>|0|0|0|0|17%|20|![](https://media.fortniteapi.io/images/e69e001baccca6b4f6e2b96b4c370822/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|31|$7,000|PSG TNA KEWL|77.0|24.2 <3,33,44,0,18,23>|9 (2.3) <4,1,0,2,2,0>|0|0|0|0|100%|38|![](https://media.fortniteapi.io/images/eb39b40-d9c7ad6-4136277-f1fa182/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|32|$7,000|CubeX Khanada|76.0|20.8 <24,13,23,0,27,17>|8 (1.6) <1,2,1,3,0,1>|0|1|0|1|17%|30|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|33|$7,000|Falcon Refsga|76.0|19.8 <17,25,22,0,15,20>|5 (2.5) <0,0,0,0,4,1>|0|0|0|0|0%|47|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|34|$7,000|Phzin 愛|74.0|21.4 <13,3,11,0,44,36>|1 (1.0) <0,0,0,1,0,0>|0|0|0|0|33%|31|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|35|$7,000|bevvys|74.0|22.4 <29,9,39,0,2,33>|5 (1.7) <0,1,0,1,3,0>|0|0|0|0|100%|27|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|36|$7,000|TSM Reet|72.0|24.8 <46,19,18,0,35,6>|6 (2.0) <0,2,1,0,0,3>|0|0|0|0|17%|31|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|37|$7,000|bifrost klown|70.0|19.8 <17,25,22,0,15,20>|2 (1.0) <0,0,1,1,0,0>|0|0|0|0|17%|142|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|38|$7,000|NRG Clix|69.0|24.6 <9,34,32,0,36,12>|8 (2.0) <4,0,0,1,2,1>|0|0|0|0|0%|56|![](https://media.fortniteapi.io/images/99dbb44-e5cf279-6fdc8de-0462ab4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|39|$7,000|MackWood1x.|68.0|20.8 <24,13,23,0,27,17>|4 (1.3) <2,1,1,0,0,0>|0|0|0|0|0%|26|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|40|$7,000|PSG TNA Yumi|65.0|24.2 <3,33,44,0,18,23>|3 (3.0) <3,0,0,0,0,0>|0|0|0|0|83%|47|![](https://media.fortniteapi.io/images/eb39b40-d9c7ad6-4136277-f1fa182/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|41|$7,000|EpikWhale|64.0|24.8 <46,19,18,0,35,6>|2 (1.0) <0,1,0,0,0,1>|0|0|0|0|67%|16|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|42|$7,000|alex|64.0|30.5 <27,48,25,50,23,10>|9 (3.0) <0,0,1,0,4,4>|0|0|0|0|0%|37|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|43|$7,000|DIG Duke|63.0|24.6 <9,34,32,0,36,12>|5 (1.3) <2,1,1,0,0,1>|0|0|0|0|17%|58|![](https://media.fortniteapi.io/images/99dbb44-e5cf279-6fdc8de-0462ab4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|44|$7,000|Avery|62.0|25.6 <25,31,7,0,33,32>|8 (2.0) <0,1,2,3,0,2>|0|0|0|0|17%|58|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|45|$7,000|Hijoe|60.0|25.2 <26,17,26,28,16,38>|6 (1.2) <1,1,2,1,1,0>|0|0|0|0|83%|1|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f50e3335f85347ba6346ec79a597d0e9/transparent.png){:height="35px"}|
|46|$7,000|Falcon Andile|60.0|28.0 <28,23,4,37,41,35>|6 (3.0) <0,1,5,0,0,0>|0|0|0|0|0%|19|![](https://media.fortniteapi.io/images/9ef8a5f2ce2eec295d3bf0aa460fb592/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|47|$7,000|FS on1|60.0|33.2 <23,47,48,47,6,28>|9 (2.3) <4,0,1,0,3,1>|0|0|0|0|67%|18|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|48|$7,000|EdRoadToGlory|58.0|27.4 <33,41,33,0,12,18>|7 (1.8) <0,2,0,2,1,2>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|49|$7,000|SEN Bugha|58.0|27.3 <43,10,13,34,38,26>|3 (1.0) <0,1,1,1,0,0>|0|0|0|0|100%|148|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9bfd9bacc26801f4fd617575e69ecbb9/transparent.png){:height="35px"}|
|50|$7,000|ManCity Hellf|56.0|32.8 <48,45,19,39,7,39>|8 (2.7) <0,0,2,0,4,2>|0|0|0|0|100%|61|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|51||GXR Malibuca|54.0|25.8 <20,22,35,0,22,30>|5 (1.3) <0,1,1,1,2,0>|0|0|0|0|0%|43|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|52||GHC Rapit|54.0|28.0 <28,23,4,37,41,35>|3 (3.0) <0,0,3,0,0,0>|0|0|0|0|17%|38|![](https://media.fortniteapi.io/images/9ef8a5f2ce2eec295d3bf0aa460fb592/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|53||cr pepo ay ло|54.0|34.5 <14,43,45,44,14,47>|8 (4.0) <4,0,0,0,4,0>|0|0|0|0|100%|53|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|54||Falcon TaySon|54.0|31.6 <37,12,46,0,49,14>|7 (3.5) <0,2,0,0,0,5>|0|0|0|0|83%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|55||dig mero|54.0|27.3 <43,10,13,34,38,26>|1 (1.0) <0,1,0,0,0,0>|0|0|0|0|33%|28|![](https://media.fortniteapi.io/images/eb39b40-d9c7ad6-4136277-f1fa182/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|56||Cuhmmandment|54.0|25.6 <25,31,7,0,33,32>|4 (1.3) <1,1,0,0,2,0>|0|0|0|0|0%|33|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|57||Baily|54.0|30.5 <27,48,25,50,23,10>|4 (1.3) <1,0,0,0,1,2>|0|0|0|0|0%|39|![](https://media.fortniteapi.io/images/274df4d16d062845b44a069f4a1117fa/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|58||WAVE JannisZ|53.0|26.7 <22,27,38,27,21,25>|6 (1.2) <1,1,2,1,1,0>|0|0|0|0|0%|103|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|59||Merstach|52.0|25.8 <20,22,35,0,22,30>|4 (1.3) <0,1,1,2,0,0>|0|0|0|0|33%|38|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|60||Belusi|52.0|25.2 <26,17,26,28,16,38>|2 (2.0) <0,2,0,0,0,0>|0|0|0|0|17%|60|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|61||CHIMPERATIE|51.0|30.5 <35,26,3,33,40,46>|4 (2.0) <0,2,2,0,0,0>|0|0|0|0|100%|69|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c713c090223cb2e8478dbfe6d5fd649/transparent.png){:height="35px"}|
|62||WAVE VADEAL|51.0|26.7 <22,27,38,27,21,25>|5 (1.7) <3,0,0,1,1,0>|0|0|0|0|33%|20|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|63||FaZe k1NG ㇺ|50.0|27.4 <33,41,33,0,12,18>|3 (1.5) <0,0,0,0,1,2>|0|0|0|0|17%|33|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|64||Mikson|50.0|31.4 <41,35,49,0,19,13>|6 (3.0) <0,0,0,0,5,1>|0|0|0|0|0%|45|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb46e47da50c22a3ef2e7fec4c4bca2e/transparent.png){:height="35px"}|
|65||FLu bacca|50.0|33.2 <23,47,48,47,6,28>|4 (4.0) <0,0,0,0,4,0>|0|1|1|1|100%|17|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|66||alice|49.0|25.2 <16,40,27,0,24,19>|2 (2.0) <2,0,0,0,0,0>|0|0|0|0|0%|42|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|67||GUILD Hen 75|48.0|31.2 <40,2,24,43,37,41>|4 (4.0) <0,4,0,0,0,0>|0|0|0|0|100%|42|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|68||siko rifty 33|47.0|28.4 <38,32,43,0,5,24>|3 (1.5) <0,0,1,0,2,0>|0|0|0|0|67%|46|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|69||ManCity Threa|47.0|25.2 <16,40,27,0,24,19>|1 (1.0) <0,1,0,0,0,0>|0|0|0|0|50%|64|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|70||Grolzz|47.0|28.4 <38,32,43,0,5,24>|3 (1.0) <0,1,0,0,1,1>|0|0|0|0|100%|46|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|71||FOKUS Vortex|46.0|31.2 <40,2,24,43,37,41>|3 (3.0) <0,3,0,0,0,0>|0|0|0|0|0%|34|![](https://media.fortniteapi.io/images/15fa2ad67a2f8eb4afd63641bc14e235/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|72||Wox|45.0|34.5 <34,46,29,49,42,7>|5 (1.7) <0,0,1,0,1,3>|0|0|0|0|17%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|73||ManCity Skram|45.0|30.5 <35,26,3,33,40,46>|1 (1.0) <0,0,1,0,0,0>|0|0|0|0|33%|22|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|74||CRuna3x|44.0|34.5 <14,43,45,44,14,47>|3 (1.5) <2,0,0,0,1,0>|0|0|0|0|17%|1|![](){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|75||PSG TNA Muz|44.0|37.2 <19,49,50,48,46,11>|4 (2.0) <1,0,0,0,0,3>|0|1|0|1|0%|35|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|76||Falconer|44.0|32.8 <48,45,19,39,7,39>|2 (1.0) <0,1,1,0,0,0>|0|0|0|0|17%|19|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|77||chapix|44.0|31.6 <37,12,46,0,49,14>|2 (2.0) <0,0,0,2,0,0>|0|0|0|0|17%|30|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|78||Rays|43.0|32.5 <44,14,41,41,34,21>|4 (2.0) <0,2,0,0,0,2>|0|0|0|0|50%|58|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|79||2AM Parz|43.0|32.5 <44,14,41,41,34,21>|4 (4.0) <0,0,0,0,0,4>|0|0|0|0|0%|17|![](https://media.fortniteapi.io/images/99dbb44-e5cf279-6fdc8de-0462ab4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|80||PWR looter|42.0|37.2 <19,49,50,48,46,11>|3 (3.0) <3,0,0,0,0,0>|0|0|1|0|0%|26|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|81||aqua 42|41.0|31.7 <30,39,5,40,39,37>|4 (2.0) <0,0,3,0,1,0>|0|0|0|0|0%|84|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|82||TSM Snacky3x|40.0|30.3 <36,18,40,29,25,34>|4 (1.3) <0,2,1,0,0,1>|0|0|0|0|67%|1|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|83||favs3x|40.0|30.3 <36,18,40,29,25,34>|4 (1.0) <1,1,0,1,1,0>|0|0|0|0|50%|40|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|84||Rezon Ay|39.0|31.7 <30,39,5,40,39,37>|3 (1.5) <0,0,2,0,1,0>|0|0|0|0|0%|44|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|85||Robbabkebab|39.0|34.5 <34,46,29,49,42,7>|2 (2.0) <0,0,0,0,0,2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ee5a08b-89496af-c3093dc-d6c50bf/transparent.png){:height="35px"}|
|86||Exeed artor|38.0|31.4 <41,35,49,0,19,13>||0|0|0|0|83%|17|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|87||BL MrSavage|38.0|36.6 <49,21,15,0,50,48>|4 (1.3) <0,1,1,2,0,0>|0|1|1|1|0%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|88||apeks IDrop 7|38.0|36.6 <49,21,15,0,50,48>|4 (1.3) <0,1,2,1,0,0>|0|0|0|0|100%|53|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|89||Yousrixd|35.0|36.2 <31,44,14,0,47,45>|6 (2.0) <0,2,3,1,0,0>|0|0|0|0|0%|119|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ee5a08b-89496af-c3093dc-d6c50bf/transparent.png){:height="35px"}|
|90||basil|28.0|37.5 <45,11,31,46,43,49>|1 (1.0) <0,1,0,0,0,0>|0|0|0|0|67%|74|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|91||Bravado FKS|28.0|31.2 <39,28,30,0,30,29>|4 (1.3) <0,1,2,1,0,0>|0|0|0|0|67%|32|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|92||jace 21|28.0|37.5 <45,11,31,46,43,49>|1 (1.0) <0,1,0,0,0,0>|0|0|0|0|33%|51|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|93||WAVE Juu|27.0|36.2 <31,44,14,0,47,45>|2 (1.0) <1,0,0,1,0,0>|0|0|0|0|17%|80|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|94||nov1ce 7|25.0|42.0 <12,50,47,45,48,50>|2 (1.0) <1,0,0,0,0,1>|0|0|0|0|33%|16|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|95||reтake|25.0|42.0 <12,50,47,45,48,50>|2 (2.0) <2,0,0,0,0,0>|0|0|1|0|0%|74|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|96||CPHF PabloWin|22.0|33.5 <42,36,28,35,29,31>|2 (1.0) <0,1,0,1,0,0>|0|0|0|0|0%|42|![](https://media.fortniteapi.io/images/e69e001baccca6b4f6e2b96b4c370822/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/81f8e8dd30cc7948c0a4fe364235921d/transparent.png){:height="35px"}|
|97||CPHF Swag|22.0|33.5 <42,36,28,35,29,31>|2 (2.0) <0,2,0,0,0,0>|0|0|0|0|100%|16|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|98||Peterbot ち|21.0|35.7 <32,37,42,30,31,42>|4 (1.3) <0,0,1,0,2,1>|0|0|0|0|0%|53|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|99||Falcon Spy|20.0|31.2 <39,28,30,0,30,29>||0|0|0|0|0%|20|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|100||Jamper|19.0|35.7 <32,37,42,30,31,42>|3 (1.0) <1,0,1,0,0,1>|0|0|0|0|100%|20|![](https://media.fortniteapi.io/images/74c6035f0634c8d53e98435652b9fd39/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

