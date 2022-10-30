---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Oct 30, 2022 11:11:07").getTime(); // Set the date we're counting down to
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

Data updates within 5 minutes after each match. We had 9 matches with 65 unique people and the biggest lobby had 25 playing. There were 3 people who played every match. The highest XP level was 'sunshinehanne' at 295. The lowest XP was 'boskololez ttv' at 2, welcome to our lobby you GOAT! People used 49.0% girl skins. Guess what, we eliminated 5 NPCs, RIP! By the way, 1 people need to turn off ANONYMOUS MODE. 9 people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: Bonejamin(4), LennoxRose(4), MeowSkulls(4)<br>
* Most common pickaxes: SigiloftheEmpire(5), LectrostaticImpactor(4), RoseLightDaggers(4)<br>
* Most common emotes: CrowningAchievement(21), TheDip(13), Steady(10)<br>

Bot identified 2 error occurances affecting 1 player(s) with a net error balance of 0.00. Only ~1.92 total tournament points are at question due to kill feed data discrepancies. Affected players are: Relaxed Fit Jonesy. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 4.8% of all points earned this session and 12.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|959|88|783|31.6%|-2.6%|17.7%|12.0%|26.4%|4.8%|9.2%|0.9%|

E1 is how many times you scored the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|G^gg|LtBAM401 TTV|60.8|6.7 <4,6,1,13,14,11,9,1,1>|14 (2.8) <3,0,3,0,0,0,1,3,4>|0|1|1|0|33%|222|![](https://media.fortniteapi.io/images/a5a44c839f7779f43da1942d430ba3de/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f9044de32d1d864c49289bb666ddba04/transparent.png){:height="35px"}|
|2|bitties|CPK_kaso|47.6|13.2 <6,11,18,18,7,16,15,13,15>||1|0|1|0|67%|74|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|3|stars|Johnny the Taco|34.9|10.8 <8,13,9,15,10,5,12,11,14>|8 (1.3) <1,0,2,0,1,1,2,0,1>|0|1|0|0|11%|67|![](https://media.fortniteapi.io/images/58dd2ce5b48859425c4603533946eb02/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2149460bed6da81cbc9a5c8ba2a0e4ff/transparent.png){:height="35px"}|
|4|nada!|ZeroCoolDL|34.0|4.5 <7,2,3,6>|4 (1.3) <1,2,1,0>|1|0|0|0|50%|113|![](https://media.fortniteapi.io/images/5d20f6c9fb8851f92ee9ec086be1809e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7c9afa14cbc3d768fe4caabfeed34867/transparent.png){:height="35px"}|
|5|bruh?|TTVLejawon_|30.3|2.8 <5,1,3,2>|17 (4.3) <4,4,3,6>|0|1|0|0|0%|65|![](https://media.fortniteapi.io/images/a4ae8f546570a63acd3d87f50d37bdfc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f5a2fb23fafa18eebe48bf2bb33d3c2c/transparent.png){:height="35px"}|
|6||Kamilox ツ|28.1|10.6 <14,10,10,12,17,6,5>|9 (1.8) <1,1,2,0,0,2,3>|1|1|0|0|100%|73|![](https://media.fortniteapi.io/images/563d1ba1d0a8f2b9cf438c3c06c985d4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a2cc22d2f7dc9b3133be728e06948897/transparent.png){:height="35px"}|
|7||OGfresh777|23.7|9.7 <8,16,13,8,3,10>||0|0|0|0|0%|49|![](https://media.fortniteapi.io/images/b954f412518352259111c2813f90e2b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7c9afa14cbc3d768fe4caabfeed34867/transparent.png){:height="35px"}|
|8||Sladernader30|23.3|9.7 <1,17,11>|8 (4.0) <7,0,1>|0|0|0|0|100%|144|![](https://media.fortniteapi.io/images/4c883d5-fae2066-25c7cc8-daefe01/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/39dd730-6b8a44c-c53ec7e-d19fa45/transparent.png){:height="35px"}|
|9||LonelyCamel731|23.2|13.0 <8,15,19,7,16>|2 (1.0) <1,0,0,1,0>|0|0|0|0|100%|68|![](https://media.fortniteapi.io/images/eed1dc1709f78c998adf0df066086eed/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|10|zen|xXsnazzychipXx|23.0|3.3 <5,2,3>|2 (1.0) <1,1,0>|0|0|0|0|100%|93|![](https://media.fortniteapi.io/images/a7357a2339f39bf2e76b3ddfa5b84ef8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e3e9d16-9aca214-c82eed9-b398cdc/transparent.png){:height="35px"}|
|11||L3SBI4N2004|20.5|17.7 <20,14,19>||0|0|1|0|100%|97|![](https://media.fortniteapi.io/images/cb7f23c5bb967f8618d51fa143d27fb2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9f01bb71d4127b4d54fdfa89b647e2bf/transparent.png){:height="35px"}|
|12||twitchsnowman|20.3|12.5 <5,15,16,14>||0|0|1|0|100%|78|![](https://media.fortniteapi.io/images/48df52cae09bef25606b1cfd32141ca8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|13||TTV bluflyingfox|19.9|6.0 <4,1,13>|9 (3.0) <1,6,2>|0|1|0|0|100%|208|![](https://media.fortniteapi.io/images/c159c82-32d838a-e4f5c75-b021dab/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|14||DYN TrashyTastic|19.5|8.3 <2,3,20>||0|0|1|0|0%|116|![](https://media.fortniteapi.io/images/a40ba1726d5029ab566aed545e7c6493/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3917968ae81f78c6032a317de3730b4e/transparent.png){:height="35px"}|
|15||BigRIBgaming|19.1|5.5 <9,2>|5 (2.5) <1,4>|0|0|0|0|100%|160|![](https://media.fortniteapi.io/images/279c7ba-f505255-0aa8c77-f84c036/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/05a4b5341b15ee1186be825311d823a4/transparent.png){:height="35px"}|
|16|sweet|MrCrazyMan777|17.1|3.0 <1,5>|3 (3.0) <3,0>|0|0|0|0|50%|56|![](https://media.fortniteapi.io/images/751c452f632a5831b5e0d9abf54192cd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2149460bed6da81cbc9a5c8ba2a0e4ff/transparent.png){:height="35px"}|
|17||GeltonasBananas2|15.5|1.0 <1>|10 (10.0) <10>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/8f227905f8f190434750999cd3b10fe9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/081600676f0a2ac62e8db6b2aa93a519/transparent.png){:height="35px"}|
|18||DYN GanjaGamer|15.1|9.5 <2,17>|2 (2.0) <2,0>|0|0|0|0|100%|119|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|19||GAHHHBIGE|14.8|14.5 <4,25>|1 (1.0) <1,0>|0|0|1|0|0%|77|![](https://media.fortniteapi.io/images/68d7d82375c1ae97e5ef7b7c7d833565/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a555187baf26263c4da7f71bfc0650cd/transparent.png){:height="35px"}|
|20||FuzzyForever|13.4|4.7 <4,8,2>|3 (3.0) <0,3,0>|0|1|0|0|100%|51|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b9ef8159c41c70190910adb40ced2ced/transparent.png){:height="35px"}|
|21|cheers!|faze_void2459|13.1|3.0 <3>|5 (5.0) <5>|0|0|0|0|100%|188|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/398bcab523d22e365ca26fb1bb2d8e66/transparent.png){:height="35px"}|
|22||DeafDeal3r|13.0|11.5 <4,19>|1 (1.0) <1,0>|0|0|1|0|0%|47|![](https://media.fortniteapi.io/images/4ba24f5-e9fb6bd-74785b3-3f6b25f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/839c000b65b0d7d47a158725b273cfb6/transparent.png){:height="35px"}|
|23||ZeroCoolReborn|12.7|6.5 <11,2>|4 (4.0) <0,4>|0|0|0|0|50%|85|![](https://media.fortniteapi.io/images/1c47a457188a9dc57e4336eba526a7ea/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/081600676f0a2ac62e8db6b2aa93a519/transparent.png){:height="35px"}|
|24||Smashken|12.5|7.3 <4,7,12,6>|1 (1.0) <0,0,0,1>|0|0|0|0|0%|78|![](https://media.fortniteapi.io/images/0bd4a367acec6dba8426309fdc35b564/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/8a4adf355b9635be82c75bbe8bb37e75/transparent.png){:height="35px"}|
|25||Steven x M x|11.7|11.8 <7,15,16,9>|5 (1.7) <0,1,3,1>|0|0|0|0|50%|103|![](https://media.fortniteapi.io/images/58dd2ce5b48859425c4603533946eb02/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1b797f7325f705c4eaec66c91dde5e4e/transparent.png){:height="35px"}|
|26||Nitro_clapz_ttv|11.6|1.0 <1>|4 (4.0) <4>|0|0|0|0|0%|145|![](https://media.fortniteapi.io/images/10152349852b512cf59d93156e451ca7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|27||XL Comical|11.3|13.0 <3,23>|3 (1.5) <2,1>|1|1|0|0|0%|63|![](https://media.fortniteapi.io/images/c0b107b18754af4906abf2ca3a3c6661/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|28||Vultun|10.9|8.7 <9,11,6>|1 (1.0) <1,0,0>|0|0|0|0|100%|169|![](https://media.fortniteapi.io/images/744f37053c7e060b143a797abc630b9c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/903041685a1e4b9bd6b807c8d998f4a3/transparent.png){:height="35px"}|
|29||Senapmedketchup|9.9|9.0 <14,4>|2 (2.0) <0,2>|0|0|0|0|100%|171|![](https://media.fortniteapi.io/images/9b15c8118fe22fae1819c88bdd149c76/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|30||MomzAdvice|9.6|8.5 <12,5>||0|0|0|0|100%|57|![](https://media.fortniteapi.io/images/f62eac592baed20007df92c81ac4b1f1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/65e15ffba968b03d600a5411704876e4/transparent.png){:height="35px"}|
|31||Knightscreen|9.3|19.0 <19>||0|0|1|0|100%|74|![](https://media.fortniteapi.io/images/864da97a1d158188c461f8f248467721/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/87324c24d74a69eabf39a8a1e59b49c6/transparent.png){:height="35px"}|
|32||Mrfishy6968|9.0|10.0 <10>||0|0|1|0|0%|113|![](https://media.fortniteapi.io/images/117f54c-2985b28-ee59013-a625629/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|33||User-6a88da4e46|8.9|14.0 <18,12,12>||0|0|0|0|100%|103|![](https://media.fortniteapi.io/images/b57c9b58faaea1e7bd18095245de42b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/875dc73d63a7b7ab59fc6d5a72039ca6/transparent.png){:height="35px"}|
|34||Camocean44813|8.6|9.0 <9>||0|0|0|0|100%|210|![](){:height="35px"}|![](){:height="35px"}|
|35||KinDingaling898|8.2|4.0 <4>|2 (2.0) <2>|0|0|0|0|100%|75|![](https://media.fortniteapi.io/images/744f37053c7e060b143a797abc630b9c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a7367c31bc7ac6483d7b7a0596d6cc97/transparent.png){:height="35px"}|
|36||lucasr4495|8.1|10.5 <11,10>||1|0|0|0|50%|79|![](https://media.fortniteapi.io/images/706d89f3b32e8f99d15300be5400e53e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/71a79f113c3956ade63047bb34464717/transparent.png){:height="35px"}|
|37||BROCKNCHEEZE455|7.9|7.0 <4,10>||0|0|0|0|100%|57|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/981eda5d964b80653594f6068b9b215b/transparent.png){:height="35px"}|
|38||mufcmurphy2012|7.4|6.0 <7,5>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/0c3ea68-65c83bb-6a93e44-0939ee3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d0ede8f-343a5e4-ca342cf-06f23a6/transparent.png){:height="35px"}|
|39||KickLizard|6.9|8.0 <13,3>||0|0|0|0|50%|50|![](https://media.fortniteapi.io/images/addacc3-e8cc989-58770ab-49e6656/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9f9742a8c232fcab89a5942bc6e48fc1/transparent.png){:height="35px"}|
|40||Ttvtuck128|6.9|6.3 <2,10,7>|4 (1.3) <1,1,2>|0|0|0|0|100%|85|![](https://media.fortniteapi.io/images/6ee85e0f8e42c3ce4040928bc580e03b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|41||Jazzeon9914|6.7|7.0 <7>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/ddb5dcf96f6154a21e90c80d0661d7a4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/570a2564cf556477a6f124d522f3d7b2/transparent.png){:height="35px"}|
|42||sunshinehanne|6.6|5.0 <5>|1 (1.0) <1>|0|0|0|0|100%|295|![](https://media.fortniteapi.io/images/d82392c-22671dc-f3bd5fe-90f0892/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e0223a3fe685ff4cd8e936ef4e5b9d91/transparent.png){:height="35px"}|
|43||JennTheFierceTTV|6.2|3.0 <3>||0|0|0|0|100%|234|![](https://media.fortniteapi.io/images/398ff504ae8deedd35f35022a820c2c5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3b0592f38af43c3107953c3b077e5660/transparent.png){:height="35px"}|
|44||boskololez ttv|6.0|14.0 <14>||0|0|0|0|100%|2|![](https://media.fortniteapi.io/images/4c5542e-6f3676d-6a54bd7-19b4d9d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|45||pinkrose0007|5.6|17.0 <17>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/89566b85647e0e8f9b331c6cb653f957/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/486ec6860e21fa074efff7c5aa7f0ea9/transparent.png){:height="35px"}|
|46||Dr1p MGK2105|5.3|18.0 <18>||0|0|0|0|100%|62|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7254e4d-91416f1-5ff1068-3713203/transparent.png){:height="35px"}|
|47||MSkaliwags|5.2|13.0 <13>||0|0|0|0|100%|232|![](https://media.fortniteapi.io/images/0961782-0c80ab5-6fbbc33-69160f0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7c9afa14cbc3d768fe4caabfeed34867/transparent.png){:height="35px"}|
|48||Unkel Hukun|5.2|7.5 <6,9>||0|0|0|0|0%|44|![](https://media.fortniteapi.io/images/e8987d971e156d9000f2c3596bc3b603/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb46e47da50c22a3ef2e7fec4c4bca2e/transparent.png){:height="35px"}|
|49||TurtleBrigade|5.0|21.0 <21>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/0a0911a-51ea32f-08d6334-52338f4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/54b5fbafce2723d3198106a3131623ff/transparent.png){:height="35px"}|
|50||GodlyAxis|4.9|22.0 <22>||0|0|0|0|0%|1|![](){:height="35px"}|![](){:height="35px"}|
|51||GFAMZ TTV|4.9|6.0 <6>||0|0|0|0|100%|22|![](https://media.fortniteapi.io/images/6ee85e0f8e42c3ce4040928bc580e03b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7c9afa14cbc3d768fe4caabfeed34867/transparent.png){:height="35px"}|
|52||Dino_nuggets645|4.6|9.0 <9>|1 (1.0) <1>|0|0|0|0|100%|107|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|53||kathybrito|4.4|6.0 <6>||0|0|0|0|100%|65|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/71a79f113c3956ade63047bb34464717/transparent.png){:height="35px"}|
|54||Twitch EllaGoofy|4.3|7.0 <7>||0|0|0|0|100%|60|![](https://media.fortniteapi.io/images/fa8b038efb78a4c5b25d3d6301aca046/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|55||BenjiLikesCake|3.8|8.0 <8>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/6ee85e0f8e42c3ce4040928bc580e03b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1470afcef74ebc3e9f96b52fd1320466/transparent.png){:height="35px"}|
|56||Bigpapito420|3.8|9.0 <9>|1 (1.0) <1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/8e5194a7a80141a1723ee25e8a4d00b3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a2cc22d2f7dc9b3133be728e06948897/transparent.png){:height="35px"}|
|57||Shaphilly|3.6|10.0 <8,12>||0|0|0|0|50%|82|![](https://media.fortniteapi.io/images/f320a80614e848de2b2f97edb63786dd/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e263dbdc1ca3b4d6175e24912693f00b/transparent.png){:height="35px"}|
|58||StormCuddles21|3.6|13.0 <15,11>|1 (1.0) <0,1>|0|0|0|0|50%|79|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0d37cb24e1ac0102361de0b4c0df269f/transparent.png){:height="35px"}|
|59||fortnitepasd|2.7|10.0 <10>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/48df52cae09bef25606b1cfd32141ca8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|60||BakedPotato2421|2.2|14.0 <14>||0|0|0|0|100%|75|![](https://media.fortniteapi.io/images/48df52cae09bef25606b1cfd32141ca8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/71a79f113c3956ade63047bb34464717/transparent.png){:height="35px"}|
|61||R1SE C0RRUPT|1.0|8.0 <8>|3 (3.0) <3>|0|1|0|0|0%|73|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e3940162064053d5f1e6096fc2c9d031/transparent.png){:height="35px"}|
|62||TTVoneshotallday|0.5|13.0 <13>||0|0|0|0|0%|143|![](https://media.fortniteapi.io/images/6ee85e0f8e42c3ce4040928bc580e03b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/54659001b6c523cc90c07e288e8afced/transparent.png){:height="35px"}|
|63||K9Gizmo|-0.7|8.0 <8>|2 (2.0) <2>|0|1|0|0|100%|131|![](https://media.fortniteapi.io/images/cbaf183-df5cac3-77c44c6-9ec36ca/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/34763944b590d7d08ffa89ec66ce1dde/transparent.png){:height="35px"}|
|64||Zachary_on60fps|-14.0|18.0 <12,24>|1 (1.0) <1,0>|0|0|0|0|50%|176|![](https://media.fortniteapi.io/images/4a4736af1b7de98fbbc2f53aa1af2848/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|65||FoxyThePirateAU||17.0 <17>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/ecac1ede2b9d0eb9282c41054e5afebb/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7c9afa14cbc3d768fe4caabfeed34867/transparent.png){:height="35px"}|


## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

