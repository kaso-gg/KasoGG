---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Nov 01, 2022 20:40:42").getTime(); // Set the date we're counting down to
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

Data updates ~5 minutes after each match. We had 6 matches with 117 unique people and the biggest lobby had 64 playing. There were 17 people who played every match. The highest XP level was 'CanadianFactorTV' at 308. The lowest XP was 'Rage-Baby' at 27, welcome to our lobby you GOAT! About 63.9% of us used girl skins. Guess what, we eliminated twelve NPCs, they will be back next game though. Thank you everyone for NOT playing on Anonymous mode. 21 people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: PoisedPlaymaker(6), Bytes(4), Spider-Man(4)<br>
* Most common pickaxes: StarWand(8), Reaper(7), Driver(6)<br>
* Most common emotes: CrowningAchievement(47), LaughItUp(21), TheDip(20)<br>

Bot identified 4 error occurances affecting 4 player(s) with a net error balance of 20.00. Only ~40.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: F7 FURNESTO, johnmc2005, MordenBirder, NICKO on FB. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 7.2% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|49,445|00|49,355|58.4%|0.0%|0.0%|0.0%|0.0%|7.2%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|Obiwon|NICKO on FB|1485.0|2.8 <1,1,1,3,3,8>|34 (5.7) <7,6,4,12,4,1>|0|2|0|1|33%|140|![](https://media.fortniteapi.io/images/d0ad8b2-38849f8-abef5ea-20bbefa/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/39dd730-6b8a44c-c53ec7e-d19fa45/transparent.png){:height="35px"}|
|2|FirstLoser|SkiddlySkip|1435.0|2.8 <1,1,1,3,3,8>|29 (4.8) <4,3,6,6,8,2>|0|0|0|1|50%|261|![](https://media.fortniteapi.io/images/ba1335e162101ae22b982180360d34c3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6e445da8c2b47cf6cf54d554d126ef12/transparent.png){:height="35px"}|
|3|Turd|F7 RipDillyOnFB|1415.0|2.8 <1,1,1,3,3,8>|27 (5.4) <6,6,3,6,6,0>|0|0|0|0|100%|225|![](https://media.fortniteapi.io/images/ea4a5d0-7c1cd4a-7a9e792-7d981d2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|4|Fourth|TMojo Yurrr|1395.0|2.8 <1,1,1,3,3,8>|25 (5.0) <6,6,8,3,2,0>|1|0|0|0|33%|140|![](https://media.fortniteapi.io/images/ed75411b50d130c08420a4599bc11a3c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f16d1a556ab61acad847dfef5f3c56a0/transparent.png){:height="35px"}|
|5|Jive|xFanaticalx5630|1060.0|3.2 <3,5,2,1,5>|20 (4.0) <5,6,4,3,2>|0|1|0|1|20%|52|![](https://media.fortniteapi.io/images/5d20f6c9fb8851f92ee9ec086be1809e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/11fb2f899525462b4405135ee5e8f35a/transparent.png){:height="35px"}|
|6||F7 FURNESTO|1050.0|3.2 <3,5,2,1,5>|19 (3.8) <1,7,3,5,3>|0|0|0|0|80%|139|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|7||CanadianFactorTV|1030.0|5.8 <6,2,4,15,7,1>|11 (3.7) <2,0,1,0,0,8>|0|0|0|0|17%|308|![](https://media.fortniteapi.io/images/9ee2208-af767e3-3e46637-4918a3f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d0ede8f-343a5e4-ca342cf-06f23a6/transparent.png){:height="35px"}|
|8||ARMYOFDARKNESS4|1020.0|5.8 <6,2,4,15,7,1>|10 (2.5) <0,1,3,1,0,5>|0|0|0|0|100%|171|![](https://media.fortniteapi.io/images/e9d61c4a4aae593fbac8d72182da83f2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|9||Snackybtw|1010.0|5.8 <6,2,4,15,7,1>|9 (2.3) <0,1,2,0,1,5>|0|0|0|0|83%|77|![](https://media.fortniteapi.io/images/cc42ad0f034ec6f144fadde8e518466d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|10|Zen|ᵀʷⁱᵗᶜʰ ZayBae1x|1000.0|5.8 <6,2,4,15,7,1>|8 (2.7) <0,1,3,0,0,4>|0|1|0|1|83%|104|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/778966daaa0a95313dd9fdd3488ba0e2/transparent.png){:height="35px"}|
|11||F7_clipbot|970.0|3.2 <3,5,2,1,5>|11 (2.2) <1,2,1,2,5>|0|0|0|0|100%|82|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3eda364936b106774751de0e64c8cbde/transparent.png){:height="35px"}|
|12||YiKES FL|965.0|5.8 <12,6,9,4,1,3>|7 (3.5) <0,0,0,3,4,0>|0|0|1|0|50%|130|![](https://media.fortniteapi.io/images/de91dcf2d9adee80477416adf10cbc1d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|13||TrippyOrange|895.0|6.2 <2,3,16,4,6,6>|5 (1.7) <0,2,0,2,1,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/79f850eb568dc732e20d42104492a3af/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|14||Facebook mrJBOT|890.0|7.3 <9,4,5,5,6,15>|11 (3.7) <0,6,2,0,3,0>|1|0|0|0|100%|147|![](https://media.fortniteapi.io/images/fb204f6e58df2949071607be20394b96/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|15||LadySteph_|875.0|8.8 <10,3,12,17,9,2>|7 (3.5) <0,0,1,0,0,6>|1|0|0|0|83%|66|![](https://media.fortniteapi.io/images/df00c808f2eacd0da37a13b17b14863a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|16||Langer123456|855.0|4.6 <6,9,4,1,3>|7 (3.5) <0,5,0,2,0>|0|0|0|0|20%|112|![](https://media.fortniteapi.io/images/f28b410b5ba246847532cf32a6e70924/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4e338bb41ff115af1851100c53062a7a/transparent.png){:height="35px"}|
|17||CoffeeCrystal|855.0|6.2 <2,3,16,4,6,6>|1 (1.0) <0,0,0,0,1,0>|0|0|0|0|50%|20|![](https://media.fortniteapi.io/images/e82286f7c100af0a3c753715106f0b61/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/78830d1cb4893f1ae9963b7625d6de30/transparent.png){:height="35px"}|
|18||Killer noob 999|830.0|3.3 <5,2,1,5>|13 (3.3) <2,2,5,4>|1|0|0|0|0%|62|![](https://media.fortniteapi.io/images/9873376-84e54dd-54c54dd-9ce5a82/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/14a375486863d7f10ed120bcf50ec5b2/transparent.png){:height="35px"}|
|19||dracoflames30|785.0|9.2 <9,13,6,10,15,2>|2 (2.0) <0,0,0,0,0,2>|1|0|0|0|100%|53|![](https://media.fortniteapi.io/images/e7318a9477d7d31fb14a8e322f151114/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f16d1a556ab61acad847dfef5f3c56a0/transparent.png){:height="35px"}|
|20||Dougie452|730.0|10.5 <11,13,10,9,16,4>|1 (1.0) <0,0,0,1,0,0>|0|0|1|0|100%|57|![](https://media.fortniteapi.io/images/3a5804ae4d324adc20daed88d5fb77f1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/41c2fdb554da82dacacc1935b55db23e/transparent.png){:height="35px"}|
|21||Bogus-Gas-Man|710.0|12.5 <12,16,17,10,16,4>||0|0|0|0|83%|1|![](https://media.fortniteapi.io/images/35d2821cc446c343046054eccf955d60/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|22||ALPHA DOG 487|705.0|9.8 <13,13,17,4,2>|4 (4.0) <0,0,0,0,4>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/c159c82-32d838a-e4f5c75-b021dab/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|23||CPK_kaso|690.0|10.7 <11,11,14,7,10,11>|1 (1.0) <0,0,0,0,1,0>|0|0|0|0|100%|76|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|24||Celiadia|670.0|7.4 <6,5,16,4,6>|3 (1.0) <0,1,1,0,1>|1|0|0|0|100%|14|![](https://media.fortniteapi.io/images/4bd08e586b3b07c73d4832cd790f2243/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9e3cb25-7961435-ad8b71f-cdcc882/transparent.png){:height="35px"}|
|25||Mercenary-Ox|625.0|4.7 <10,1,3>|11 (3.7) <4,6,1>|0|1|0|1|100%|131|![](https://media.fortniteapi.io/images/e4a765e43c88ebb1be3093017ead3cc8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/859e60ceafa2f46fadf43f1111031573/transparent.png){:height="35px"}|
|26||The_Joker_62470|620.0|8.4 <4,6,11,9,12>|1 (1.0) <1,0,0,0,0>|0|0|0|0|20%|1|![](https://media.fortniteapi.io/images/ba1335e162101ae22b982180360d34c3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|27||FXTBOII|615.0|6.5 <8,3,2,13>|4 (1.3) <0,1,2,1>|1|0|0|0|100%|94|![](https://media.fortniteapi.io/images/e8c4d88f1639a7741b6aefaa90958eb9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b4e367781ba31cd934ce595f38e34804/transparent.png){:height="35px"}|
|28||TwitchDestro|615.0|6.5 <8,3,2,13>|4 (4.0) <0,0,4,0>|0|0|0|0|100%|103|![](https://media.fortniteapi.io/images/a40ba1726d5029ab566aed545e7c6493/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|29||ObeyRealPrince|610.0|10.6 <5,17,10,15,6>|1 (1.0) <0,0,0,0,1>|0|0|2|0|100%|73|![](https://media.fortniteapi.io/images/722dddb-85539a2-d8e9a63-1b298df/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|30||ᴍᴏʟꜱᴏɴ|605.0|6.5 <8,3,2,13>|3 (1.5) <0,1,2,0>|0|0|0|0|100%|123|![](https://media.fortniteapi.io/images/e8c4d88f1639a7741b6aefaa90958eb9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f94b2e3221b1482efe8b2f1191a40afd/transparent.png){:height="35px"}|
|31||SGfour_|585.0|6.5 <8,3,2,13>|1 (1.0) <0,0,1,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/2f16d55fcbd0f9e1046693995d23ae2c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|32||Lehoisky11|565.0|11.5 <2,16,12,16>|5 (2.5) <2,0,3,0>|1|0|0|0|75%|25|![](https://media.fortniteapi.io/images/c33db0a26c632e6a133c7201440f1593/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/65e15ffba968b03d600a5411704876e4/transparent.png){:height="35px"}|
|33||KenzicornXD|550.0|15.6 <15,17,16,15,15>||0|0|0|0|80%|1|![](https://media.fortniteapi.io/images/f647b07e70d199b906978f3302f6dc08/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9e3cb25-7961435-ad8b71f-cdcc882/transparent.png){:height="35px"}|
|34||emarin8125|550.0|7.5 <4,10,4,12>|2 (2.0) <2,0,0,0>|0|0|0|0|100%|20|![](https://media.fortniteapi.io/images/bb65c41c924f4cd5653425b3145343f3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e1fb45085dde7bcace3daaebfe13575c/transparent.png){:height="35px"}|
|35||ISuckAtThisFYI|550.0|6.5 <4,9,9,4>|1 (1.0) <0,0,1,0>|0|0|0|0|0%|39|![](https://media.fortniteapi.io/images/4266f184d24a5159c7321cf4fa1841ce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/981eda5d964b80653594f6068b9b215b/transparent.png){:height="35px"}|
|36||Phee Gogh TTV|480.0|10.5 <15,6,14,7>|2 (2.0) <0,2,0,0>|0|0|0|0|100%|60|![](https://media.fortniteapi.io/images/c06b7481f7f0579b8a9fcbf8905932da/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/398bcab523d22e365ca26fb1bb2d8e66/transparent.png){:height="35px"}|
|37||Duh87_|480.0|10.5 <10,14,7,11>|2 (1.0) <0,0,1,1>|1|0|0|0|25%|1|![](https://media.fortniteapi.io/images/e82286f7c100af0a3c753715106f0b61/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/cc9a1eb2f3e87cd88cca8e2e54c3a1a7/transparent.png){:height="35px"}|
|38||cb3franchise|480.0|10.5 <5,10,11,16>||0|0|0|0|25%|14|![](https://media.fortniteapi.io/images/a0cf0eb956aa5483a9ae4394d1157ff3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a2cc22d2f7dc9b3133be728e06948897/transparent.png){:height="35px"}|
|39||KarasuRae|470.0|10.5 <15,6,14,7>|1 (1.0) <0,1,0,0>|0|0|0|0|50%|64|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/55c1f40-d376131-8c48e37-4b1fd11/transparent.png){:height="35px"}|
|40||Zenith_PGC|470.0|13.5 <10,10,17,17>|1 (1.0) <0,1,0,0>|0|0|0|0|100%|99|![](https://media.fortniteapi.io/images/b53f98b2a65e7eddca3fedeb5e5c69b0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/8185a53-8a18081-2b30189-1569590/transparent.png){:height="35px"}|
|41||johnmc2005|470.0|13.8 <18,12,11,14>|3 (3.0) <0,0,3,0>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/9d58c0abbda19dc101efbf88949fa305/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3eda364936b106774751de0e64c8cbde/transparent.png){:height="35px"}|
|42||ScoobieDubie|460.0|10.5 <10,14,7,11>||0|0|0|0|100%|36|![](https://media.fortniteapi.io/images/d2a9889e8c90f9287bb1d416ff78f019/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1470afcef74ebc3e9f96b52fd1320466/transparent.png){:height="35px"}|
|43||GeeNah_75|460.0|10.5 <15,6,14,7>||0|0|0|0|75%|1|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/87324c24d74a69eabf39a8a1e59b49c6/transparent.png){:height="35px"}|
|44||DirtyTurbans73|425.0|7.7 <12,9,2>|1 (1.0) <0,0,1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/5c14b54-2d251ed-5a5555f-7a1b319/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|45||ig__msprrrd|380.0|9.0 <7,12,8>|3 (1.5) <1,2,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/86da499-f41aa44-6696faf-408b001/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/54659001b6c523cc90c07e288e8afced/transparent.png){:height="35px"}|
|46||Grinzler_|360.0|10.7 <14,7,11>|2 (2.0) <0,2,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/5959bfe77d8db137551dd3dcba792902/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0b2f988-089c9c9-d2cf306-f1980ee/transparent.png){:height="35px"}|
|47||FB_RoyalTay|360.0|9.0 <7,12,8>|1 (1.0) <1,0,0>|0|1|0|1|33%|166|![](https://media.fortniteapi.io/images/f50e8410ad51cc6d12e0189c6cc135cc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/c554b2b0333cd08d87b3823c20b0acd9/transparent.png){:height="35px"}|
|48||xxbuzzed247xx|360.0|11.7 <15,6,14>|2 (2.0) <0,2,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/a5df3724c04d4f090c20187a44eaf7d3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6e445da8c2b47cf6cf54d554d126ef12/transparent.png){:height="35px"}|
|49||Tellvisions|360.0|9.0 <7,12,8>|1 (1.0) <0,1,0>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/cc42ad0f034ec6f144fadde8e518466d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec74412d5ce06732a68380256b008d5f/transparent.png){:height="35px"}|
|50||DeadlyMomEツ|355.0|3.5 <2,5>|3 (1.5) <2,1>|0|0|0|0|100%|112|![](https://media.fortniteapi.io/images/1587045-faf4027-af22aa5-bcddd0a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|51||Tshiamo_shoddie|350.0|10.7 <6,9,17>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/cb7f23c5bb967f8618d51fa143d27fb2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9f01bb71d4127b4d54fdfa89b647e2bf/transparent.png){:height="35px"}|
|52||FB SNF Dream|350.0|10.0 <9,15,6>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/c33374569550d49e99dc699e5d1747c5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c713c090223cb2e8478dbfe6d5fd649/transparent.png){:height="35px"}|
|53||OutofNowhereGirl|350.0|9.0 <7,12,8>||0|0|0|0|0%|42|![](https://media.fortniteapi.io/images/6b780520e4b82814611bf1d504ff9d23/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f16d1a556ab61acad847dfef5f3c56a0/transparent.png){:height="35px"}|
|54||YnwMelly626|340.0|13.0 <9,15,15>||0|0|1|0|0%|1|![](https://media.fortniteapi.io/images/e7318a9477d7d31fb14a8e322f151114/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7c9afa14cbc3d768fe4caabfeed34867/transparent.png){:height="35px"}|
|55||MghtyBruceLeroy|330.0|13.7 <11,18,12>||0|0|0|0|100%|44|![](https://media.fortniteapi.io/images/d41a043620a840291e2bb2f754dcfb7b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/375116215fc92197289b5268aea0948b/transparent.png){:height="35px"}|
|56||Rage-Baby|325.0|3.5 <2,5>||0|0|0|0|0%|27|![](){:height="35px"}|![](https://media.fortniteapi.io/images/a4166a6498e089366e78637f9aff0367/transparent.png){:height="35px"}|
|57||scarredpinky|325.0|3.5 <2,5>||0|0|0|0|100%|94|![](https://media.fortniteapi.io/images/e795245b0dd8412248b028f60c1b6207/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|58||SkipSafely|325.0|3.5 <2,5>||0|0|0|0|100%|1|![](){:height="35px"}|![](){:height="35px"}|
|59||GiLfPwNr89|300.0|7.5 <3,12>|3 (3.0) <0,3>|0|0|0|0|50%|1|![](https://media.fortniteapi.io/images/c33374569550d49e99dc699e5d1747c5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|60||Garciauli747|280.0|5.5 <5,6>|2 (2.0) <0,2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/d186f0daf4afcaec2e400ecc5259dd35/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|61||CosmicEclispe|270.0|10.0 <15,5>|2 (2.0) <0,2>|0|0|0|0|100%|194|![](https://media.fortniteapi.io/images/79f850eb568dc732e20d42104492a3af/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/40dc89866f0dd945e14eab40372cc228/transparent.png){:height="35px"}|
|62||izaacdude|270.0|10.0 <3,17>||1|0|0|0|100%|1|![](https://media.fortniteapi.io/images/e89ea7f23e17f1546ecaba65cd506cb6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2d7ea52a6427a5856d262f0a73e0881c/transparent.png){:height="35px"}|
|63||JNB8父|270.0|9.0 <8,10>|3 (1.5) <1,2>|1|0|0|0|100%|92|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|64||MidlifDorito|270.0|7.0 <9,5>|1 (1.0) <1,0>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/ec3f88b34ce01474d3064eb248b9d97c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7500ad3-1ad26f5-c425093-84deca6/transparent.png){:height="35px"}|
|65||JenniferAnne635|270.0|9.0 <8,10>|3 (3.0) <0,3>|0|0|0|0|100%|48|![](https://media.fortniteapi.io/images/c0b107b18754af4906abf2ca3a3c6661/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eae173d-282ab94-ffce067-5d60def/transparent.png){:height="35px"}|
|66||SKG-QUAWNDO5|265.0|1.0 <1>|3 (3.0) <3>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/8d6862e-986cd5c-af7fb61-73cc7ec/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0239283aac43ef28dbe38c409bba5a11/transparent.png){:height="35px"}|
|67||JonBigma|260.0|9.0 <8,10>|2 (1.0) <1,1>|0|0|0|0|50%|74|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6611610a7c2c07da2930b683dde37eef/transparent.png){:height="35px"}|
|68||ElCapitan1027|240.0|9.0 <8,10>||0|0|0|0|100%|32|![](https://media.fortniteapi.io/images/e084b05-b7132a4-3318158-114e7c0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/54659001b6c523cc90c07e288e8afced/transparent.png){:height="35px"}|
|69||Cr8zy_finger|240.0|7.0 <8,6>||0|0|0|0|100%|157|![](https://media.fortniteapi.io/images/4266f184d24a5159c7321cf4fa1841ce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/636eaa8-89f8c9b-a3f96c1-4a7c468/transparent.png){:height="35px"}|
|70||IGoBySlimJim|240.0|9.0 <9,9>||0|0|0|0|100%|67|![](https://media.fortniteapi.io/images/52f1f7d24620835f96dfe15fc8f5b1da/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3e5a1599e8620abd44155917aa2f5b2c/transparent.png){:height="35px"}|
|71||TheOfficialSetis|240.0|13.0 <10,16>|1 (1.0) <1,0>|0|0|0|0|100%|203|![](https://media.fortniteapi.io/images/330842271d864d27c50b7fb32aab7bd0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9c3f5e4cb1a6546b726a13fc8441258b/transparent.png){:height="35px"}|
|72||xxWINGMAN84xx|240.0|13.0 <17,9>|1 (1.0) <0,1>|0|0|0|0|50%|1|![](https://media.fortniteapi.io/images/5669cf0-7dcbc51-c40d4eb-8f4d007/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ab4df84-8907ba7-1371183-c532655/transparent.png){:height="35px"}|
|73||DMGKyr13|240.0|13.0 <10,16>|1 (1.0) <1,0>|0|0|0|0|50%|157|![](https://media.fortniteapi.io/images/0d5c412496aa9c49bfda07f1f549a970/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|74||stevobabygirlsky|230.0|13.5 <11,16>|1 (1.0) <1,0>|0|0|0|0|100%|70|![](https://media.fortniteapi.io/images/5cf884aa69c3677136bf05f98c474ae4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/18abe9969bbcf234d8758e034945043c/transparent.png){:height="35px"}|
|75||Pridefull_SinFB|230.0|12.0 <10,14>||0|0|0|0|100%|103|![](https://media.fortniteapi.io/images/844b33e7bfb520ecdd545868892da34a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e1fb45085dde7bcace3daaebfe13575c/transparent.png){:height="35px"}|
|76||F7 Durt.DeMar|230.0|13.5 <18,9>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/4266f184d24a5159c7321cf4fa1841ce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|77||BaseballBoy4255|230.0|10.5 <8,13>||0|0|0|0|100%|58|![](https://media.fortniteapi.io/images/2bff3c9e2636803c0165ef8748617690/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7db4f9589742d362456faec60e3ded91/transparent.png){:height="35px"}|
|78||Quinz543|220.0|14.5 <12,17>||0|0|0|0|100%|90|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2a2ab11ff80aa6f65b0e8b3d0c627c31/transparent.png){:height="35px"}|
|79||Sachitoku|220.0|14.5 <16,13>||0|0|0|0|0%|36|![](https://media.fortniteapi.io/images/844b33e7bfb520ecdd545868892da34a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6045978e076c5f9831aaeeff62527db1/transparent.png){:height="35px"}|
|80||YT ankers99|220.0|16.0 <15,17>||0|0|0|0|50%|17|![](https://media.fortniteapi.io/images/5ca15d1e9ebabe7dee16301dd2e06985/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f16d1a556ab61acad847dfef5f3c56a0/transparent.png){:height="35px"}|
|81||XXqueenJariXX|220.0|12.0 <13,11>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/a8f14c9ad13cf815283431ca583061d7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2149460bed6da81cbc9a5c8ba2a0e4ff/transparent.png){:height="35px"}|
|82||EggSaladMan22|220.0|12.0 <11,13>||0|0|0|0|100%|96|![](https://media.fortniteapi.io/images/bec69fe0327cb43be88004b4273278bc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|83||Livigdailytt|220.0|15.0 <18,12>||0|0|0|0|100%|51|![](https://media.fortniteapi.io/images/f647b07e70d199b906978f3302f6dc08/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2149460bed6da81cbc9a5c8ba2a0e4ff/transparent.png){:height="35px"}|
|84||MordenBirder|220.0|15.0 <13,17>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/cb7f23c5bb967f8618d51fa143d27fb2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c432ada4a32eb8e52774014785040ab/transparent.png){:height="35px"}|
|85||BeastKing1420|170.0|4.0 <4>|2 (2.0) <2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/6c84784e144e6b7fae3b0e104a040003/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a02b9082525370e9088801261a77c3e1/transparent.png){:height="35px"}|
|86||MyLootNow319|170.0|4.0 <4>|2 (2.0) <2>|0|0|0|0|0%|77|![](https://media.fortniteapi.io/images/516770e-ad0e965-2562313-fce091b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/724056f-15ca757-34a6fbe-e9c13b7/transparent.png){:height="35px"}|
|87||DMGRecklezzz|150.0|10.0 <10>|3 (3.0) <3>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/1b809b67e9382d56ec07f2439eab685c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|88||Queenofkings7272|150.0|4.0 <4>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/6b52762e083e94fd0b0615f1f007a523/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|89||xXRed_VixenxX|140.0|7.0 <7>|2 (2.0) <2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/864da97a1d158188c461f8f248467721/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a660570-f091b29-1decbf3-39fe9e6/transparent.png){:height="35px"}|
|90||BerserkBohemian|140.0|5.0 <5>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/1fef5980542c030ff867bf3fbd1acef1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/78fbd0cbbcbf7d843ca48d5af1062314/transparent.png){:height="35px"}|
|91||LushSeven9784|140.0|5.0 <5>||0|0|0|0|100%|85|![](https://media.fortniteapi.io/images/744f37053c7e060b143a797abc630b9c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1b797f7325f705c4eaec66c91dde5e4e/transparent.png){:height="35px"}|
|92||PrinceSkinFlute|140.0|7.0 <7>|2 (2.0) <2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/c4244d8ff76d14a67b275e2565b300e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0fed47e5e226c080be7933544d54aa8f/transparent.png){:height="35px"}|
|93||Zach_Zapp2008|140.0|5.0 <5>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/52438a58352ec6c671faffc27a948cc8/transparent.png){:height="35px"}|
|94||MTM3530|140.0|5.0 <5>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/4266f184d24a5159c7321cf4fa1841ce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a2cc22d2f7dc9b3133be728e06948897/transparent.png){:height="35px"}|
|95||Jwebber94|130.0|7.0 <7>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/6b780520e4b82814611bf1d504ff9d23/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|96||Atominizerz|130.0|7.0 <7>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/935187fbe94e1e0f26ac31e8fab60686/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|97||sG-Newfie|120.0|7.0 <7>||1|0|0|0|0%|1|![](https://media.fortniteapi.io/images/c5f76d6-e532d99-5ac26ec-49101c3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|98||Rezpunzel83|120.0|7.0 <7>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/6c84784e144e6b7fae3b0e104a040003/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/87324c24d74a69eabf39a8a1e59b49c6/transparent.png){:height="35px"}|
|99||ImbecileGlue333|120.0|14.0 <14>|1 (1.0) <1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/24f0953966ee2622df01353c50a2a211/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2d991bc2a476645b5c49f8d50c443f92/transparent.png){:height="35px"}|
|100||Newfound_Lander|120.0|9.0 <9>||0|0|0|0|100%|117|![](https://media.fortniteapi.io/images/9b870dc076559b59c913fd6992ce5b60/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/353476001a41d4b0ad0bb3e6e90ca158/transparent.png){:height="35px"}|
|101||iTzjD2962|120.0|8.0 <8>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/7b4dc64bc01160edee233b0147438739/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a2a6a67dc8b1b346aa4c20cff4bd75c6/transparent.png){:height="35px"}|
|102||BaseballRob8|120.0|10.5 <8,13>||0|0|0|0|50%|1|![](https://media.fortniteapi.io/images/adb3c01eccaad41a02b467acb81d2082/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ff9bfa252772b404af2b7be39c97398e/transparent.png){:height="35px"}|
|103||Midoriya2121048|120.0|8.0 <8>||0|0|0|0|100%|126|![](https://media.fortniteapi.io/images/48df52cae09bef25606b1cfd32141ca8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/71a79f113c3956ade63047bb34464717/transparent.png){:height="35px"}|
|104||guccigoat1621|110.0|17.0 <17>||0|0|0|0|100%|79|![](https://media.fortniteapi.io/images/b38c29d119cf418355ff425f8960bf09/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9f9742a8c232fcab89a5942bc6e48fc1/transparent.png){:height="35px"}|
|105||TTV_FireDragon51|110.0|17.0 <17>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/04d0044a926503aec44d178b7cbf227b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|106||FriskyLlama1|110.0|16.0 <16>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0ce7d6cee4fe5a6c90f64d2e2244051c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/300208f28dad9053288425731989ef9e/transparent.png){:height="35px"}|
|107||VexyFB|110.0|17.0 <17>||0|0|1|0|100%|1|![](https://media.fortniteapi.io/images/04d0044a926503aec44d178b7cbf227b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|108||Kingding2311|110.0|13.0 <13>||0|0|0|0|100%|143|![](https://media.fortniteapi.io/images/caf3036e352f86fdc4beacca788cbedc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/c630409d891712e1d089a13fce85920a/transparent.png){:height="35px"}|
|109||Lilnando817|110.0|13.0 <13>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/2bff3c9e2636803c0165ef8748617690/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/54659001b6c523cc90c07e288e8afced/transparent.png){:height="35px"}|
|110||Dragon66fox_|110.0|12.0 <12>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/1ac9c1fbd6c3ffa94a38d1037e4c0156/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|111||BaseballRob88|110.0|10.5 <8,13>||0|0|0|0|50%|1|![](https://media.fortniteapi.io/images/adb3c01eccaad41a02b467acb81d2082/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ff9bfa252772b404af2b7be39c97398e/transparent.png){:height="35px"}|
|112||Gizmofiggs5956|110.0|12.0 <12>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/b5acca5f9e0460f0120be44db1bc8ae1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3eb13f2ff6536ebb1986d2c443221d1b/transparent.png){:height="35px"}|
|113||cece1234677655|110.0|11.0 <11>||0|0|0|0|0%|67|![](https://media.fortniteapi.io/images/0bd4a367acec6dba8426309fdc35b564/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a52d92b4012082022570876353f44a3c/transparent.png){:height="35px"}|
|114||oCarterrrr|110.0|14.5 <13,16>||0|0|0|0|0%|35|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|115||Big-_-cloud43|110.0|12.0 <12>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/86da499-f41aa44-6696faf-408b001/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/398bcab523d22e365ca26fb1bb2d8e66/transparent.png){:height="35px"}|
|116||d0up3|110.0|15.0 <15>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/c899284fe528e0d9a5a22772a1e23104/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2522518cad0c15f736b51e90f888cb7/transparent.png){:height="35px"}|
|117||Lukas-FN-20-cxrv|110.0|12.0 <12>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/e9d61c4a4aae593fbac8d72182da83f2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

