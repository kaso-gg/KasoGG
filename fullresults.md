---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Apr 15, 2023 11:51:56").getTime(); // Set the date we're counting down to
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

We had 5 matches with 50 unique people and the biggest lobby had 50 playing. There were 48 people who played every match. The highest XP level was 'cmon .' at 167. The lowest XP was 'deathbysociety' at 37, welcome to our lobby you GOAT! About 81.0% of us used girl skins. Guess what, we eliminated nineteen NPCs, they will be back next game though. Thank you everyone for NOT playing on Anonymous mode. Five people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: ArcticAdeline(12), Highwire(10), Thunder(7)<br>
* Most common pickaxes: TheVaultGuardian(7), TheAshglowBlade(5), Driver(3)<br>
* Most common emotes: CrowningAchievement(19), GetGriddy(9), BearHug(7)<br>

Bot identified 3 error occurances affecting 2 player(s) with a net error balance of 0.00. Only ~0.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: Polar Patroller, coachcoble. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 0.0% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|1,168|00|1,168|100.0%|0.0%|0.0%|0.0%|0.0%|0.0%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|GG|Old School 2.0|75.0|1.0 <1,1,1,1,1>|32 (6.4) <6,8,5,11,2>|2|0|0|0|20%|95|![](https://media.fortniteapi.io/images/1d6c273052d69c3dd72cd2520a7475c7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/8e37e41-4f55a66-bbefba5-c77d177/transparent.png){:height="35px"}|
|2|ggz|ᵀʷⁱᵗᶜʰ ZayBae1x|75.0|1.0 <1,1,1,1,1>|21 (4.2) <2,8,3,5,3>|3|0|0|1|60%|67|![](https://media.fortniteapi.io/images/1d6c273052d69c3dd72cd2520a7475c7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/128928a-3e4385b-50c4b4a-4240a82/transparent.png){:height="35px"}|
|3|good job|NaCole_69|75.0|1.0 <1,1,1,1,1>|20 (4.0) <8,2,2,6,2>|0|1|0|1|20%|1|![](https://media.fortniteapi.io/images/2f7d5b7ac5c4da2299db136e60685774/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/128928a-3e4385b-50c4b4a-4240a82/transparent.png){:height="35px"}|
|4|goat|FourAll2See|60.0|1.0 <1,1,1,1>|1 (1.0) <0,1,0,0>|1|0|0|0|0%|101|![](https://media.fortniteapi.io/images/ae10d7211a0aedd4824da7ef221111a8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/68b6461baddd6e9c623f292c6ccc940b/transparent.png){:height="35px"}|
|5|high five|ᴍᴏʟꜱᴏɴ|30.0|5.4 <5,5,2,13,2>|16 (3.2) <2,1,4,2,7>|0|0|0|0|80%|89|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7129fe22482a29f1fdacec0628cc095a/transparent.png){:height="35px"}|
|6||ASG_Rtad2002|30.0|5.4 <5,5,2,13,2>|11 (2.8) <1,5,1,0,4>|1|0|0|0|60%|55|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/cc25bc57d03f8fd5e9e40878ce9e7eb3/transparent.png){:height="35px"}|
|7||TYLER_MOREAU_YT|30.0|5.4 <5,5,2,13,2>|3 (1.5) <1,0,2,0,0>|0|0|0|0|60%|44|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|8||HippieRach|30.0|5.4 <5,5,2,13,2>|3 (1.5) <1,0,0,0,2>|0|0|0|0|100%|55|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|9||DocsGamesYouTube|28.0|5.4 <9,4,3,4,7>|15 (5.0) <4,0,3,8,0>|0|0|0|0|0%|74|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/636eaa8-89f8c9b-a3f96c1-4a7c468/transparent.png){:height="35px"}|
|10||Grizzel|28.0|5.6 <2,12,7,2,5>|9 (2.3) <3,0,1,2,3>|0|0|0|0|60%|162|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/68b6461baddd6e9c623f292c6ccc940b/transparent.png){:height="35px"}|
|11||Jolee Knox_TTV|28.0|5.6 <2,12,7,2,5>|7 (2.3) <1,0,0,1,5>|0|1|0|0|100%|135|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb7af48a7d83fc82e305216a9f48f35a/transparent.png){:height="35px"}|
|12||JiggaG_4PF|28.0|5.6 <2,12,7,2,5>|4 (2.0) <3,0,0,0,1>|0|1|0|1|100%|1|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|13||buckeyeyoyo|28.0|5.4 <9,4,3,4,7>|3 (1.5) <2,0,1,0,0>|0|0|1|0|100%|90|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e5b0563-df76037-8512749-99b2e5b/transparent.png){:height="35px"}|
|14||ConJoGaming|28.0|5.4 <9,4,3,4,7>|3 (3.0) <0,0,3,0,0>|0|1|0|1|40%|25|![](https://media.fortniteapi.io/images/d19f1f88b2f48fc58c061f22c0340184/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2821715ae77ce3a826a547fb21c4cae3/transparent.png){:height="35px"}|
|15||coachcoble|28.0|5.4 <9,4,3,4,7>|4 (2.0) <0,0,3,1,0>|0|0|0|0|60%|132|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ca6cfb9-54bc587-e5c6dce-1b4fc3e/transparent.png){:height="35px"}|
|16||Brackets132|28.0|5.6 <2,12,7,2,5>|2 (1.0) <0,0,0,1,1>|0|0|0|0|60%|1|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0e42a90699530feec9a43004f08a4a5a/transparent.png){:height="35px"}|
|17||fanzypantzy|24.0|6.2 <3,8,4,6,10>|14 (3.5) <2,0,2,6,4>|1|0|0|0|0%|1|![](https://media.fortniteapi.io/images/a93d01053af0de70bef99b3c9b737c8c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f216fc696f3a514de8399ae2e82229b3/transparent.png){:height="35px"}|
|18||gupi6|24.0|6.2 <3,8,4,6,10>|6 (1.5) <1,0,3,1,1>|3|0|0|0|80%|21|![](https://media.fortniteapi.io/images/a40ba1726d5029ab566aed545e7c6493/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e3e9d16-9aca214-c82eed9-b398cdc/transparent.png){:height="35px"}|
|19||RealQueen420|24.0|6.2 <3,8,4,6,10>|4 (1.3) <2,0,0,1,1>|1|0|0|0|100%|98|![](https://media.fortniteapi.io/images/a0cf0eb956aa5483a9ae4394d1157ff3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/958bce0b0f72dea23439f889cd91dd97/transparent.png){:height="35px"}|
|20||Ted302|24.0|6.2 <3,8,4,6,10>|3 (1.5) <2,0,1,0,0>|0|0|0|0|80%|99|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c7fb76aca7496083220a4c2d84fb110/transparent.png){:height="35px"}|
|21||cmon .|23.0|6.4 <11,6,5,7,3>|14 (2.8) <2,4,3,1,4>|0|0|0|0|0%|167|![](https://media.fortniteapi.io/images/99a22e03d3a66ed41bd47f78533f516e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2ddccff4a674659187ecd9fa835d070f/transparent.png){:height="35px"}|
|22||VincentDaGoatt|23.0|6.4 <11,6,5,7,3>|4 (1.3) <0,0,2,1,1>|0|0|0|0|80%|101|![](https://media.fortniteapi.io/images/c9e4e66cfb2050a5da6d762ea4ec4fb1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1470afcef74ebc3e9f96b52fd1320466/transparent.png){:height="35px"}|
|23||RichieHustles|23.0|6.4 <11,6,5,7,3>|2 (1.0) <0,0,1,0,1>|0|0|1|0|60%|43|![](https://media.fortniteapi.io/images/99a22e03d3a66ed41bd47f78533f516e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9a4d4a63cc04546f7b2058c5590f48e7/transparent.png){:height="35px"}|
|24||Sasquatch_59|23.0|6.4 <11,6,5,7,3>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/e551f3f02db8ee7ab0e0ff8dc847b941/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/07a1777f2c562ebf6979d3ba3c3f14e7/transparent.png){:height="35px"}|
|25||DayMan2990|22.0|7.0 <8,2,13,8,4>|7 (2.3) <0,3,0,1,3>|0|1|0|1|80%|155|![](https://media.fortniteapi.io/images/b57c9b58faaea1e7bd18095245de42b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/366532eef1bf2b47e16bf7b1a3ab8b28/transparent.png){:height="35px"}|
|26||CPK_kaso|22.0|7.0 <8,2,13,8,4>|5 (1.7) <1,2,0,0,2>|1|0|1|0|60%|101|![](https://media.fortniteapi.io/images/b57c9b58faaea1e7bd18095245de42b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|27||PRODR12|22.0|7.0 <8,2,13,8,4>|1 (1.0) <1,0,0,0,0>|1|0|0|0|20%|72|![](https://media.fortniteapi.io/images/b57c9b58faaea1e7bd18095245de42b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/fd14e2b4088bc5332387311d6fe90373/transparent.png){:height="35px"}|
|28||cece1234677655|22.0|7.0 <8,2,13,8,4>|1 (1.0) <1,0,0,0,0>|1|0|0|0|0%|9|![](https://media.fortniteapi.io/images/b57c9b58faaea1e7bd18095245de42b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7bd11ebf53706ac267b565ed3b1f71e0/transparent.png){:height="35px"}|
|29||skinnydog55|19.0|7.6 <6,13,8,3,8>|4 (2.0) <3,1,0,0,0>|0|0|0|0|40%|124|![](https://media.fortniteapi.io/images/a9bb473cc8e918e58171cf94630f58e3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9293e8e2a91396e03e3153b5b0c72f6a/transparent.png){:height="35px"}|
|30||deathbysociety|19.0|7.6 <6,13,8,3,8>|2 (1.0) <1,0,1,0,0>|0|0|0|0|60%|37|![](https://media.fortniteapi.io/images/dd35114d0cb56d5df4e2cd3c0fc992d0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9293e8e2a91396e03e3153b5b0c72f6a/transparent.png){:height="35px"}|
|31||OldManJersey|19.0|7.6 <6,13,8,3,8>|1 (1.0) <1,0,0,0,0>|0|0|0|0|40%|73|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d05d0ccff103c03578932034873e35a6/transparent.png){:height="35px"}|
|32||WatCKa007|19.0|7.6 <6,13,8,3,8>||0|0|0|0|60%|59|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3c7bc37b6e335269274991910a5dd2ef/transparent.png){:height="35px"}|
|33||ITZ_ARTT|15.0|8.2 <7,3,10,12,9>|2 (2.0) <0,2,0,0,0>|0|0|0|0|80%|86|![](https://media.fortniteapi.io/images/c52ad68e8c9547c86ceb44c48736845f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|34||RickAshtray|15.0|8.2 <7,3,10,12,9>||0|0|0|0|80%|40|![](https://media.fortniteapi.io/images/a7c4ac265dc8782c783abf34bb898810/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2149460bed6da81cbc9a5c8ba2a0e4ff/transparent.png){:height="35px"}|
|35||V1king of Norway|15.0|8.2 <7,3,10,12,9>||0|0|0|0|100%|31|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2ddccff4a674659187ecd9fa835d070f/transparent.png){:height="35px"}|
|36||iUsedKamui|13.0|6.7 <7,3,10>|4 (1.3) <2,1,1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0defc4cca4ad9a53c50473da2f352a0b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/958bce0b0f72dea23439f889cd91dd97/transparent.png){:height="35px"}|
|37||CPK_jamieo_TTV|13.0|8.8 <13,9,6,5,11>|2 (2.0) <0,0,2,0,0>|1|0|1|0|80%|87|![](https://media.fortniteapi.io/images/1d6c273052d69c3dd72cd2520a7475c7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/895655a-7f0c2ad-e3a4aa8-983ef5e/transparent.png){:height="35px"}|
|38||Schmeee76|13.0|8.8 <13,9,6,5,11>|1 (1.0) <0,0,1,0,0>|0|0|0|0|60%|65|![](https://media.fortniteapi.io/images/1d6c273052d69c3dd72cd2520a7475c7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/87324c24d74a69eabf39a8a1e59b49c6/transparent.png){:height="35px"}|
|39||PaCorze|13.0|8.8 <13,9,6,5,11>||0|0|0|0|100%|83|![](https://media.fortniteapi.io/images/1d6c273052d69c3dd72cd2520a7475c7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb488368dc072c4b4e11f9c7a9dbb08e/transparent.png){:height="35px"}|
|40||OldSniper69|13.0|8.8 <13,9,6,5,11>||0|0|0|0|100%|22|![](https://media.fortniteapi.io/images/1d6c273052d69c3dd72cd2520a7475c7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2149460bed6da81cbc9a5c8ba2a0e4ff/transparent.png){:height="35px"}|
|41||TOMMY OF TROY|8.0|10.0 <12,7,9,9,13>|12 (4.0) <0,6,1,5,0>|0|0|0|0|100%|76|![](https://media.fortniteapi.io/images/844b33e7bfb520ecdd545868892da34a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2ddccff4a674659187ecd9fa835d070f/transparent.png){:height="35px"}|
|42||crazytrain_85|8.0|10.0 <12,7,9,9,13>|2 (1.0) <0,1,0,1,0>|0|0|0|0|80%|1|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9e3618809db4e273cd485a6e04766020/transparent.png){:height="35px"}|
|43||DadNoBuild|8.0|10.0 <12,7,9,9,13>|1 (1.0) <0,1,0,0,0>|0|0|1|0|20%|126|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5e2d208e58d6203d5269dbada0e2439f/transparent.png){:height="35px"}|
|44||badCorpsman|8.0|9.8 <4,11,12,10,12>|1 (1.0) <1,0,0,0,0>|1|0|0|0|80%|63|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2522518cad0c15f736b51e90f888cb7/transparent.png){:height="35px"}|
|45||Chicken_Tender_9|8.0|9.8 <4,11,12,10,12>||0|0|0|0|20%|51|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f5424f49818936d1cdefb1afd58b090d/transparent.png){:height="35px"}|
|46||donzerelli76|8.0|9.8 <4,11,12,10,12>||2|0|0|0|0%|1|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/958bce0b0f72dea23439f889cd91dd97/transparent.png){:height="35px"}|
|47||SfromO|8.0|10.0 <12,7,9,9,13>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/d8f36a018fe77330bf83edc1967b6e70/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/958bce0b0f72dea23439f889cd91dd97/transparent.png){:height="35px"}|
|48||RLM Sherry|7.0|9.6 <10,10,11,11,6>|1 (1.0) <0,0,0,0,1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/56abbb6f8c9bfadae34ace004cc565bc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/299280f58b71dd38d333b888bc678656/transparent.png){:height="35px"}|
|49||BuckeyeBunny|7.0|9.6 <10,10,11,11,6>||0|0|0|0|100%|125|![](https://media.fortniteapi.io/images/b11bb2d9ee525954571b559e97371736/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/cbcb9e145a9ae22fdd377bc5af228b8c/transparent.png){:height="35px"}|
|50||QBall693971|7.0|9.6 <10,10,11,11,6>||0|0|0|0|60%|1|![](https://media.fortniteapi.io/images/ec72faa4d3b15d6b40726cd424122b1e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7c9afa14cbc3d768fe4caabfeed34867/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

