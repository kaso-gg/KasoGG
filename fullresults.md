---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Nov 12, 2022 15:21:57").getTime(); // Set the date we're counting down to
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

We had 1 matches with 100 unique people and the biggest lobby had 100 playing. There were 100 people who played every match. The highest XP level was 'SEN Bugha' at 295. The lowest XP was 'GUILD Hen 75' at 82, welcome to our lobby you GOAT! About 98.0% of us used girl skins. Nobody killed an NPC, what gives? One person was ANON mode, big sad. Fifteen people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: Kor(18), SurfWitch(11), Focus(9)<br>
* Most common pickaxes: IceBreaker(34), StuddedAxe(13), StarWand(12)<br>
* Most common emotes: GetGriddy(31), TakeTheL(23), Bringitaround(21)<br>

Bot identified 6 error occurances affecting 6 player(s) with a net error balance of 30.00. Only ~30.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: [FNCS] FS on1, [FNCS] GXR Queasy, [FNCS] WAVE VADEAL, Baily, BL Kami, Guild Anas. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for -16.4% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|10,960|7,000|-3,010|-114.8%|0.0%|0.0%|0.0%|0.0%|-16.4%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|Obiwon|BL Kami|125.0|1.0 <1>|4 (4.0) <4>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|2|FirstLoser|[FNCS] BL Settyz 8|115.0|1.0 <1>|2 (2.0) <2>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|3|Turd|Acorn|75.0|2.0 <2>|4 (4.0) <4>|0|0|0|0|0%|99|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|4|Fourth|[FNCS] FS Edgey|55.0|2.0 <2>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|5|Jive|[FNCS] PSG TNA KEWL|50.0|3.0 <3>|4 (4.0) <4>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|6||PSG TNA Yumi|45.0|3.0 <3>|3 (3.0) <3>|0|0|0|0|100%|93|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|7||[FNCS] ALBA Zagou281|45.0|4.0 <4>|5 (5.0) <5>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/10152349852b512cf59d93156e451ca7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|8||[FNCS] ALBA merem 魅|35.0|4.0 <4>|3 (3.0) <3>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|9||Tundra Veno|25.0|5.0 <5>|3 (3.0) <3>|0|0|0|0|0%|134|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|10|Zen|Not_BadSnipR|25.0|7.0 <7>|7 (7.0) <7>|0|0|0|0|0%|101|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|11||[FNCS] GXR Queasy|15.0|5.0 <5>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/a40ba1726d5029ab566aed545e7c6493/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|12||[FNCS] NRG Clix|10.0|9.0 <9>|4 (4.0) <4>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/99dbb44-e5cf279-6fdc8de-0462ab4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|13||[FNCS] Jоefn|5.0|10.0 <10>|3 (3.0) <3>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/326d7ac-21ef4cf-c71367c-919dd57/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|14||[FNCS] cr pepo ay ло|0.0|14.0 <14>|4 (4.0) <4>|0|0|0|0|100%|1|![](){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|15||[FNCS] TT9 Chico|0.0|6.0 <6>|2 (2.0) <2>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/04d0044a926503aec44d178b7cbf227b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|16||DIG Duke|0.0|9.0 <9>|2 (2.0) <2>|0|0|0|0|100%|173|![](https://media.fortniteapi.io/images/99dbb44-e5cf279-6fdc8de-0462ab4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c713c090223cb2e8478dbfe6d5fd649/transparent.png){:height="35px"}|
|17||PaMstou|0.0|8.0 <8>|2 (2.0) <2>|0|0|0|0|0%|95|![](https://media.fortniteapi.io/images/04d0044a926503aec44d178b7cbf227b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|18||[FNCS] zAndy|0.0|10.0 <10>|2 (2.0) <2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/956018371300988c78970a99c8f7ac89/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|19||[FNCS] PWR looter|-5.0|19.0 <19>|3 (3.0) <3>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|20||kitoz|-5.0|13.0 <13>|3 (3.0) <3>|0|0|0|0|0%|103|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|21||[FNCS] trulex 381|-5.0|6.0 <6>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/04d0044a926503aec44d178b7cbf227b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|22||WAVE NOAHREYL|-5.0|7.0 <7>|1 (1.0) <1>|0|0|0|0|0%|156|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|23||AST Th0masHD|-5.0|11.0 <11>|3 (3.0) <3>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|24||vic0|-5.0|18.0 <18>|3 (3.0) <3>|0|0|0|0|0%|258|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|25||[FNCS] CRuna3x|-10.0|14.0 <14>|2 (2.0) <2>|0|0|0|0|100%|1|![](){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|26||[FNCS] alice|-10.0|16.0 <16>|2 (2.0) <2>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|27||reтake|-10.0|12.0 <12>|2 (2.0) <2>|0|0|0|0|0%|111|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/14a375486863d7f10ed120bcf50ec5b2/transparent.png){:height="35px"}|
|28||Fatch|-10.0|8.0 <8>||0|0|0|0|0%|171|![](https://media.fortniteapi.io/images/04d0044a926503aec44d178b7cbf227b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|29||KBR|-15.0|15.0 <15>|1 (1.0) <1>|0|0|0|0|0%|127|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|30||Guild Anas|-15.0|21.0 <21>|4 (4.0) <4>|0|0|0|0|100%|88|![](https://media.fortniteapi.io/images/e69e001baccca6b4f6e2b96b4c370822/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|31||[FNCS] FS on1|-15.0|23.0 <23>|4 (4.0) <4>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|32||[FNCS] nov1ce 7|-15.0|12.0 <12>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|33||[FNCS] PSG TNA Muz|-15.0|19.0 <19>|1 (1.0) <1>|0|1|0|1|0%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|34||[FNCS] xeat|-20.0|15.0 <15>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/ffb6dfe-af7cd7d-1782ad9-480ba48/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|35||[FNCS] GXR Malibuca|-20.0|20.0 <20>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/10152349852b512cf59d93156e451ca7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|36||trippernn|-20.0|11.0 <11>||0|0|0|0|100%|102|![](https://media.fortniteapi.io/images/aa32e41-a4c103f-6192067-9208810/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|37||bifrost klown|-20.0|17.0 <17>||0|0|0|0|0%|213|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|38||[FNCS] Merstach|-20.0|20.0 <20>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|39||ManCity Threa|-20.0|16.0 <16>||0|0|0|0|100%|127|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9bfd9bacc26801f4fd617575e69ecbb9/transparent.png){:height="35px"}|
|40||[FNCS] Phzin 愛|-20.0|13.0 <13>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|41||Falcon Refsga|-20.0|17.0 <17>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|42||[FNCS] Siko Merijn|-20.0|18.0 <18>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|43||[FNCS] WAVE VADEAL|-20.0|22.0 <22>|3 (3.0) <3>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|44||[FNCS] MackWood1x.|-25.0|24.0 <24>|2 (2.0) <2>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|45||[FNCS] CubeX Khanada|-30.0|24.0 <24>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c432ada4a32eb8e52774014785040ab/transparent.png){:height="35px"}|
|46||[FNCS] Cuhmmandment|-30.0|25.0 <25>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|47||tundra pinquk|-30.0|21.0 <21>|1 (1.0) <1>|0|0|0|0|0%|120|![](https://media.fortniteapi.io/images/e69e001baccca6b4f6e2b96b4c370822/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|48||WAVE JannisZ|-30.0|22.0 <22>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|49||[FNCS] FLu bacca|-35.0|23.0 <23>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|50||Avery|-35.0|25.0 <25>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|51||Baily|-45.0|27.0 <27>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/05cf241-4373694-759585a-ce4310c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|52||[FNCS] Hijoe|-45.0|26.0 <26>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|53||GHC Rapit|-50.0|28.0 <28>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/9ef8a5f2ce2eec295d3bf0aa460fb592/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|54||aqua 42|-50.0|30.0 <30>||0|0|0|0|0%|251|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/778966daaa0a95313dd9fdd3488ba0e2/transparent.png){:height="35px"}|
|55||alex|-50.0|27.0 <27>||0|0|0|0|0%|110|![](https://media.fortniteapi.io/images/05cf241-4373694-759585a-ce4310c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|56||bevvys|-50.0|29.0 <29>||0|0|0|0|100%|158|![](https://media.fortniteapi.io/images/04d0044a926503aec44d178b7cbf227b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/bcb936b-e88999a-f701fea-afe213e/transparent.png){:height="35px"}|
|57||Rezon Ay|-50.0|30.0 <30>||0|0|0|0|0%|261|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|58||Siko Vortexer|-50.0|29.0 <29>||0|0|0|0|0%|121|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|59||Belusi|-50.0|26.0 <26>||0|0|0|0|0%|119|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|60||[FNCS] Falcon Andile|-50.0|28.0 <28>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/9ef8a5f2ce2eec295d3bf0aa460fb592/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|61||[FNCS] favs3x|-55.0|36.0 <36>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|62||[FNCS] WAVE Juu|-55.0|31.0 <31>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0f4cd3609dd11ba4b2260adc84a18c4a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|63||[FNCS] Jamper|-55.0|32.0 <32>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/10152349852b512cf59d93156e451ca7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|64||[FNCS] siko rifty 33|-60.0|38.0 <38>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|65||[FNCS] Falcon TaySon|-60.0|37.0 <37>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7da36e2a6c30c344c73bfdc4216bc3ec/transparent.png){:height="35px"}|
|66||[FNCS] ManCity Skram|-60.0|35.0 <35>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|67||Robbabkebab|-60.0|34.0 <34>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/eb39b40-d9c7ad6-4136277-f1fa182/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|68||chapix|-60.0|37.0 <37>||0|0|0|0|0%|90|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7da36e2a6c30c344c73bfdc4216bc3ec/transparent.png){:height="35px"}|
|69||GUILD Hen 75|-60.0|40.0 <40>||0|0|0|0|100%|82|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|70||[FNCS] Bravado FKS|-60.0|39.0 <39>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|71||[FNCS] EdRoadToGlory|-60.0|33.0 <33>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|72||[FNCS] Wox|-60.0|34.0 <34>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|73||[FNCS] Falcon Spy|-60.0|39.0 <39>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|74||[FNCS] CHIMPERATIE|-60.0|35.0 <35>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c713c090223cb2e8478dbfe6d5fd649/transparent.png){:height="35px"}|
|75||Peterbot ち|-60.0|32.0 <32>||0|0|0|0|0%|105|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|76||[FNCS] Yousrixd|-60.0|31.0 <31>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0f4cd3609dd11ba4b2260adc84a18c4a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|77||[FNCS] FaZe k1NG ㇺ|-60.0|33.0 <33>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|78||[FNCS] Grolzz|-60.0|38.0 <38>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|79||[FNCS] TSM Snacky3x|-60.0|36.0 <36>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|80||FOKUS Vortex|-60.0|40.0 <40>||0|0|0|0|0%|101|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|81||[FNCS] smіte|-70.0|50.0 <50>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|82||EpikWhale|-70.0|46.0 <46>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|83||[FNCS] BL MrSavage|-70.0|49.0 <49>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|84||SEN Bugha|-70.0|43.0 <43>||0|0|0|0|100%|295|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6e445da8c2b47cf6cf54d554d126ef12/transparent.png){:height="35px"}|
|85||[FNCS] apeks IDrop 7|-70.0|49.0 <49>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|86||[FNCS] CPHF PabloWin|-70.0|42.0 <42>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3b994941d143e7152146b3322d101a79/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/81f8e8dd30cc7948c0a4fe364235921d/transparent.png){:height="35px"}|
|87||2AM Parz|-70.0|44.0 <44>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|88||[FNCS] dig mero|-70.0|43.0 <43>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c432ada4a32eb8e52774014785040ab/transparent.png){:height="35px"}|
|89||cented -_-|-70.0|47.0 <47>||0|0|0|0|0%|199|![](https://media.fortniteapi.io/images/336825a-9f7d969-6584112-c8b952e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|90||[FNCS] jace 21|-70.0|45.0 <45>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/1e55a45-cb54ceb-bafa8c9-805b40b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ac33f06-f6d6ca5-e54a0a7-6d0b84d/transparent.png){:height="35px"}|
|91||basil|-70.0|45.0 <45>||0|0|0|0|100%|148|![](https://media.fortniteapi.io/images/1e55a45-cb54ceb-bafa8c9-805b40b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|92||Exeed artor|-70.0|41.0 <41>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/326d7ac-21ef4cf-c71367c-919dd57/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|93||ManCity Hellf|-70.0|48.0 <48>||0|0|0|0|100%|120|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|94||[FNCS] CPHF Swag|-70.0|42.0 <42>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|95||[FNCS] Mikson|-70.0|41.0 <41>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/87ed7ed-f11dd6f-e069443-f26dc94/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|96||TSM Reet|-70.0|46.0 <46>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|97||Rays|-70.0|44.0 <44>||0|0|0|0|100%|172|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|98||[FNCS] Larson .|-70.0|50.0 <50>||0|0|1|0|0%|1|![](https://media.fortniteapi.io/images/a395b5efbef021a7e74d152b12acf265/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|99||Falconer|-70.0|48.0 <48>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|100||[FNCS] cold|-70.0|47.0 <47>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/336825a-9f7d969-6584112-c8b952e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

