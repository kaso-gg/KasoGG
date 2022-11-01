---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Nov 01, 2022 18:38:57").getTime(); // Set the date we're counting down to
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

Data updates ~5 minutes after each match. We had 1 matches with 40 unique people and the biggest lobby had 40 playing. There were 40 people who played every match. The highest XP level was 'CanadianFactorTV' at 308. The lowest XP was 'cb3franchise' at 56, welcome to our lobby you GOAT! About 75.0% of us used girl skins. Guess what, we eliminated three NPCs, they will be back next game though. Thank you everyone for NOT playing on Anonymous mode. Fifteen people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: Bytes(2), Joltara(2), Polarity(2)<br>
* Most common pickaxes: Unmaker(3), Ava'sRavers(2), Driver(2)<br>
* Most common emotes: CrowningAchievement(22), LaughItUp(15), TheDip(10)<br>

Bot identified 1 error occurances affecting 1 player(s) with a net error balance of 10.00. Only ~10.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: NICKO on FB. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 6.3% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|6,025|00|5,925|60.7%|0.0%|0.0%|0.0%|0.0%|6.3%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|Obiwon|NICKO on FB|305.0|1.0 <1>|7 (7.0) <7>|0|0|0|0|0%|140|![](https://media.fortniteapi.io/images/d0ad8b2-38849f8-abef5ea-20bbefa/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/39dd730-6b8a44c-c53ec7e-d19fa45/transparent.png){:height="35px"}|
|2|FirstLoser|F7 RipDillyOnFB|295.0|1.0 <1>|6 (6.0) <6>|0|0|0|0|100%|225|![](https://media.fortniteapi.io/images/7875e1d-3919b46-67c114b-907a59b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|3|Turd|TMojo Yurrr|295.0|1.0 <1>|6 (6.0) <6>|0|0|0|0|0%|140|![](https://media.fortniteapi.io/images/3e756f27efe7f24dfcde9018cedc5912/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f16d1a556ab61acad847dfef5f3c56a0/transparent.png){:height="35px"}|
|4|Fourth|SkiddlySkip|275.0|1.0 <1>|4 (4.0) <4>|0|0|0|0|100%|261|![](https://media.fortniteapi.io/images/7a4f80638e9c156e4d51d896555e0136/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6e445da8c2b47cf6cf54d554d126ef12/transparent.png){:height="35px"}|
|5|Jive|xFanaticalx5630|210.0|3.0 <3>|5 (5.0) <5>|0|0|0|0|100%|130|![](https://media.fortniteapi.io/images/5d20f6c9fb8851f92ee9ec086be1809e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/11fb2f899525462b4405135ee5e8f35a/transparent.png){:height="35px"}|
|6||Lehoisky11|205.0|2.0 <2>|2 (2.0) <2>|0|0|0|0|100%|98|![](https://media.fortniteapi.io/images/c33db0a26c632e6a133c7201440f1593/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/65e15ffba968b03d600a5411704876e4/transparent.png){:height="35px"}|
|7||TrippyOrange|185.0|2.0 <2>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/79f850eb568dc732e20d42104492a3af/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/c554b2b0333cd08d87b3823c20b0acd9/transparent.png){:height="35px"}|
|8||CoffeeCrystal|185.0|2.0 <2>||0|0|0|0|0%|115|![](https://media.fortniteapi.io/images/216b0d3f136cc0c5e505363f1118dc33/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/27fbbd8878c6ca48d952f2fb264c35d2/transparent.png){:height="35px"}|
|9||BeastKing1420|170.0|4.0 <4>|2 (2.0) <2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/6c84784e144e6b7fae3b0e104a040003/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a02b9082525370e9088801261a77c3e1/transparent.png){:height="35px"}|
|10|Zen|F7 FURNESTO|170.0|3.0 <3>|1 (1.0) <1>|0|0|0|0|100%|174|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|11||F7_clipbot|170.0|3.0 <3>|1 (1.0) <1>|0|0|0|0|100%|205|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3eda364936b106774751de0e64c8cbde/transparent.png){:height="35px"}|
|12||izaacdude|160.0|3.0 <3>||1|0|0|0|100%|1|![](https://media.fortniteapi.io/images/e89ea7f23e17f1546ecaba65cd506cb6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2d7ea52a6427a5856d262f0a73e0881c/transparent.png){:height="35px"}|
|13||LushSeven9784|140.0|5.0 <5>||0|0|0|0|100%|85|![](https://media.fortniteapi.io/images/744f37053c7e060b143a797abc630b9c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1b797f7325f705c4eaec66c91dde5e4e/transparent.png){:height="35px"}|
|14||ObeyRealPrince|140.0|5.0 <5>||0|0|0|0|100%|182|![](https://media.fortniteapi.io/images/15ec30ef7243253f918c8c21c6559eb9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|15||CanadianFactorTV|140.0|6.0 <6>|2 (2.0) <2>|0|0|0|0|100%|308|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/14a375486863d7f10ed120bcf50ec5b2/transparent.png){:height="35px"}|
|16||cb3franchise|140.0|5.0 <5>||0|0|0|0|0%|56|![](https://media.fortniteapi.io/images/a0cf0eb956aa5483a9ae4394d1157ff3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a2cc22d2f7dc9b3133be728e06948897/transparent.png){:height="35px"}|
|17||MTM3530|140.0|5.0 <5>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/4266f184d24a5159c7321cf4fa1841ce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a2cc22d2f7dc9b3133be728e06948897/transparent.png){:height="35px"}|
|18||ig__msprrrd|130.0|7.0 <7>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/04d7bd3eed40ebe4794958c43e213398/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/54659001b6c523cc90c07e288e8afced/transparent.png){:height="35px"}|
|19||FB_RoyalTay|130.0|7.0 <7>|1 (1.0) <1>|0|1|0|1|100%|166|![](https://media.fortniteapi.io/images/04d7bd3eed40ebe4794958c43e213398/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/c554b2b0333cd08d87b3823c20b0acd9/transparent.png){:height="35px"}|
|20||Facebook mrJBOT|120.0|9.0 <9>||0|0|0|0|100%|177|![](https://media.fortniteapi.io/images/d49effb-e8c0866-3642ef4-44b0c2f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/778966daaa0a95313dd9fdd3488ba0e2/transparent.png){:height="35px"}|
|21||IGoBySlimJim|120.0|9.0 <9>||0|0|0|0|100%|67|![](https://media.fortniteapi.io/images/52f1f7d24620835f96dfe15fc8f5b1da/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3e5a1599e8620abd44155917aa2f5b2c/transparent.png){:height="35px"}|
|22||Cr8zy_finger|120.0|8.0 <8>||0|0|0|0|100%|157|![](https://media.fortniteapi.io/images/4266f184d24a5159c7321cf4fa1841ce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/636eaa8-89f8c9b-a3f96c1-4a7c468/transparent.png){:height="35px"}|
|23||Snackybtw|120.0|6.0 <6>||0|0|0|0|100%|93|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|24||LadySteph_|120.0|10.0 <10>||1|0|0|0|100%|79|![](https://media.fortniteapi.io/images/05cf241-4373694-759585a-ce4310c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|25||FB SNF Dream|120.0|9.0 <9>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/c33374569550d49e99dc699e5d1747c5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c713c090223cb2e8478dbfe6d5fd649/transparent.png){:height="35px"}|
|26||Tellvisions|120.0|7.0 <7>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/cc42ad0f034ec6f144fadde8e518466d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec74412d5ce06732a68380256b008d5f/transparent.png){:height="35px"}|
|27||ᵀʷⁱᵗᶜʰ ZayBae1x|120.0|6.0 <6>||0|0|0|0|100%|104|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/778966daaa0a95313dd9fdd3488ba0e2/transparent.png){:height="35px"}|
|28||ScoobieDubie|120.0|10.0 <10>||0|0|0|0|100%|144|![](https://media.fortniteapi.io/images/d2a9889e8c90f9287bb1d416ff78f019/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1470afcef74ebc3e9f96b52fd1320466/transparent.png){:height="35px"}|
|29||ARMYOFDARKNESS4|120.0|6.0 <6>||0|0|0|0|100%|171|![](https://media.fortniteapi.io/images/07429fa12a5f6a7f8e8f1db85656950f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/72c6e47-4a65b88-4758c03-ca440ea/transparent.png){:height="35px"}|
|30||OutofNowhereGirl|120.0|7.0 <7>||0|0|0|0|0%|125|![](https://media.fortniteapi.io/images/6b780520e4b82814611bf1d504ff9d23/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f16d1a556ab61acad847dfef5f3c56a0/transparent.png){:height="35px"}|
|31||dracoflames30|120.0|9.0 <9>||1|0|0|0|100%|159|![](https://media.fortniteapi.io/images/e7318a9477d7d31fb14a8e322f151114/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f16d1a556ab61acad847dfef5f3c56a0/transparent.png){:height="35px"}|
|32||Pridefull_SinFB|120.0|10.0 <10>||0|0|0|0|100%|206|![](https://media.fortniteapi.io/images/844b33e7bfb520ecdd545868892da34a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d824f90501405a5df29f5bc7f8a037a6/transparent.png){:height="35px"}|
|33||Duh87_|120.0|10.0 <10>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/e82286f7c100af0a3c753715106f0b61/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/cc9a1eb2f3e87cd88cca8e2e54c3a1a7/transparent.png){:height="35px"}|
|34||EggSaladMan22|110.0|11.0 <11>||0|0|0|0|100%|96|![](https://media.fortniteapi.io/images/bec69fe0327cb43be88004b4273278bc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|35||Dougie452|110.0|11.0 <11>||0|0|0|0|100%|114|![](https://media.fortniteapi.io/images/3a5804ae4d324adc20daed88d5fb77f1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/41c2fdb554da82dacacc1935b55db23e/transparent.png){:height="35px"}|
|36||cece1234677655|110.0|11.0 <11>||0|0|0|0|0%|67|![](https://media.fortniteapi.io/images/0bd4a367acec6dba8426309fdc35b564/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a52d92b4012082022570876353f44a3c/transparent.png){:height="35px"}|
|37||YiKES FL|110.0|12.0 <12>||0|0|1|0|100%|130|![](https://media.fortniteapi.io/images/230fd5eb77e2896028a49c8cc31b3734/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|38||CPK_kaso|110.0|11.0 <11>||0|0|0|0|100%|76|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|39||Bogus-Gas-Man|110.0|12.0 <12>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/35d2821cc446c343046054eccf955d60/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|40||oCarterrrr||13.0 <13>||0|0|0|0|0%|70|![](https://media.fortniteapi.io/images/edbffd61da38e7065d32cf3a9ed4eefd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

