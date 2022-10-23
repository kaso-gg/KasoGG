---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Oct 23, 2022 17:08:56").getTime(); // Set the date we're counting down to
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

We had 8 matches with 33 unique people and the biggest lobby had 20 playing. There were 4 people who played every match. The highest XP level was 'RainbowPlsFan' at 252. The lowest XP was 'Marmalade672' at 1, welcome to our lobby you GOAT! Guess what, we eliminated 4 NPCs, RIP! By the way, 2 people need to turn off ANONYMOUS MODE. 3 people have donkey laugh in their locker emotes, LOL!

* Most common skins: Spider-Gwen(3), Bytes(2), DiamondHanz(2)<br>
* Most common pickaxes: Reaper(4), BladeoftheWaningMoon(2), Crowbar(2)<br>
* Most common emotes: CrowningAchievement(8), PumpMeUp(7), GetGriddy(5)<br>

Bot identified 1 error occurances affecting 1 player(s) with a net error balance of 0.96. Only ~0.96 total tournament points are at question due to kill feed data discrepancies. Affected players are: Garciauli747. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 7.2% of all points earned this session and 12.1% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|904|68|769|39.6%|-3.9%|12.8%|12.1%|23.4%|7.2%|8.3%|0.6%|

| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|G^gg|OFAD_SPECIALIST|49.7|3.2 <1,2,10,2,1>|8 (2.0) <1,5,0,1,1>|0|0|0|0|80%|87|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/65e15ffba968b03d600a5411704876e4/transparent.png){:height="35px"}|
|2|bitties|MghtyBruceLeroy|48.7|6.0 <1,10,4,9,3,5,10>|5 (2.5) <4,0,0,0,1,0,0>|0|0|0|0|100%|107|![](https://media.fortniteapi.io/images/d41a043620a840291e2bb2f754dcfb7b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/375116215fc92197289b5268aea0948b/transparent.png){:height="35px"}|
|3|stars|Garciauli747|47.5|5.3 <15,4,2,4,5,4,3>|10 (2.5) <0,3,0,1,0,2,4>|1|0|1|0|86%|163|![](https://media.fortniteapi.io/images/eed1dc1709f78c998adf0df066086eed/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|4|nada!|FreshUnk|45.5|4.8 <5,6,11,1,5,1>|4 (1.0) <1,0,0,1,1,1>|0|0|1|1|50%|59|![](https://media.fortniteapi.io/images/164b6aad9ac6e84a008d8cb75a03709e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/95b9eb8934ad6ae52af0e9ab075207e6/transparent.png){:height="35px"}|
|5|bruh?|ITZ_ARTT|45.4|7.4 <6,13,7,10,6,1,9>|9 (1.8) <3,1,0,1,0,3,1>|0|0|0|0|71%|215|![](https://media.fortniteapi.io/images/c33374569550d49e99dc699e5d1747c5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/41c2fdb554da82dacacc1935b55db23e/transparent.png){:height="35px"}|
|6||MordenBirder|43.7|6.6 <5,2,1,10,11,3,10,11>|12 (3.0) <2,1,4,0,0,5,0,0>|0|1|1|1|100%|150|![](https://media.fortniteapi.io/images/cb7f23c5bb967f8618d51fa143d27fb2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|7||TwitchDestro|43.5|7.6 <14,8,9,4,3,7,2,14>|7 (2.3) <0,0,0,2,0,2,3,0>|0|0|1|1|38%|85|![](https://media.fortniteapi.io/images/b4ef9b1bac7fbf1f507478cddb8fcd0a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|8||patrickpjscott|40.4|3.8 <3,3,1,5,4,7>|29 (4.8) <2,9,12,2,1,3>|0|2|0|0|83%|133|![](https://media.fortniteapi.io/images/7e7ec6a-0ec6229-5b3667d-f7c2d49/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|9||SB Jericho|38.2|5.3 <8,3,3,9,3,7,4>|3 (1.5) <0,2,0,0,0,1,0>|0|0|0|0|86%|47|![](https://media.fortniteapi.io/images/3d703cf-22d3ca8-f7ce270-c179685/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/353476001a41d4b0ad0bb3e6e90ca158/transparent.png){:height="35px"}|
|10|zen|PopPopTaterhead|37.9|7.0 <9,5,6,2,10,10>|5 (1.7) <2,0,1,2,0,0>|0|0|0|0|83%|76|![](https://media.fortniteapi.io/images/df00c808f2eacd0da37a13b17b14863a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a7367c31bc7ac6483d7b7a0596d6cc97/transparent.png){:height="35px"}|
|11||CPK_kaso|34.7|6.1 <11,6,6,5,7,6,6,2>|3 (1.0) <1,0,0,1,0,0,0,1>|2|0|0|0|100%|71|![](https://media.fortniteapi.io/images/abd0a71856066e4fb431bc31174f27f1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|12||K9Gizmo|29.0|7.8 <7,14,7,8,10,4,7,5>|1 (1.0) <0,0,0,0,0,0,1,0>|0|0|0|0|88%|119|![](https://media.fortniteapi.io/images/cbaf183-df5cac3-77c44c6-9ec36ca/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/53fc505eb57eddda378f01036da25181/transparent.png){:height="35px"}|
|13||FXTBOII|29.0|3.8 <7,4,2,2>|3 (3.0) <0,0,3,0>|1|0|0|0|75%|82|![](https://media.fortniteapi.io/images/caf3036e352f86fdc4beacca788cbedc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b4e367781ba31cd934ce595f38e34804/transparent.png){:height="35px"}|
|14||GhostSniperMLB|27.6|4.4 <3,7,2,8,2>|1 (1.0) <1,0,0,0,0>|0|0|0|0|100%|89|![](https://media.fortniteapi.io/images/d96579630a4aa5fc9d427fbeec8ab712/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|15||GWBRage|25.7|6.2 <7,1,7,3,13>|5 (1.7) <0,2,1,2,0>|0|0|0|0|100%|85|![](https://media.fortniteapi.io/images/f80a6e5ef23990f7d04e0ffb9a8d1640/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9f01bb71d4127b4d54fdfa89b647e2bf/transparent.png){:height="35px"}|
|16|sweet|ShadowsniperCLB|25.7|7.0 <11,1,9>|1 (1.0) <0,1,0>|0|0|1|0|67%|67|![](https://media.fortniteapi.io/images/c33374569550d49e99dc699e5d1747c5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|
|17||Derpgod007|25.1|7.3 <9,4,4,12>|6 (3.0) <0,2,4,0>|0|0|0|0|0%|106|![](https://media.fortniteapi.io/images/61035e04850a248f9ed90cfc931cfd23/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|18||JMAN EST 1984|21.3|10.7 <11,10,11>||0|0|2|0|67%|56|![](https://media.fortniteapi.io/images/1c47a457188a9dc57e4336eba526a7ea/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/081600676f0a2ac62e8db6b2aa93a519/transparent.png){:height="35px"}|
|19||ツTechnicalLogicツ|20.7|5.0 <4,3,8>|5 (5.0) <0,5,0>|0|0|0|0|100%|43|![](https://media.fortniteapi.io/images/cb7f23c5bb967f8618d51fa143d27fb2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|20||OFAD_BUDROW|19.2|6.0 <9,3,6>|2 (1.0) <0,1,1>|0|0|0|0|33%|51|![](https://media.fortniteapi.io/images/b5feb14a63d47d29a06ede1d8903ff77/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e5dc54df74cd9f446566d50f7530f3e9/transparent.png){:height="35px"}|
|21|cheers!|PurplChikNik|18.6|6.3 <1,8,8,8>|1 (1.0) <1,0,0,0>|0|0|0|0|25%|82|![](https://media.fortniteapi.io/images/cee5d13-0f76fe4-e583286-6a39a17/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b9ef8159c41c70190910adb40ced2ced/transparent.png){:height="35px"}|
|22||IsaacEffinStylin|16.1|6.3 <1,8,8,8>|1 (1.0) <0,1,0,0>|0|0|0|0|50%|44|![](https://media.fortniteapi.io/images/e8987d971e156d9000f2c3596bc3b603/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb46e47da50c22a3ef2e7fec4c4bca2e/transparent.png){:height="35px"}|
|23||Brackets132|13.3|10.0 <12,10,8>||0|0|0|0|67%|74|![](https://media.fortniteapi.io/images/b8702f6f79247a80c436804f7edc9953/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f54f5cefaaa20b42251cf92b3e925ef1/transparent.png){:height="35px"}|
|24||Toxic_Toomernart|9.2|13.0 <13>||0|0|1|0|100%|101|![](https://media.fortniteapi.io/images/e9ab87e429739082425810ce1a287a74/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d3baf267b97dfacf60954c870351ae56/transparent.png){:height="35px"}|
|25||LePrEcHaUn_03|8.7|7.0 <5,9>||0|0|0|0|50%|28|![](https://media.fortniteapi.io/images/d2d5190-18275f7-2501511-640b025/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/05c48936305179b91613cac98be12beb/transparent.png){:height="35px"}|
|26||jenifer_ander929|7.1|11.0 <11>||0|0|0|0|100%|116|![](https://media.fortniteapi.io/images/a1cd663f492c15448a1eb77835250258/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/15058337f3d637d4a5a466001dce65b1/transparent.png){:height="35px"}|
|27||Marmalade672|5.5|5.0 <4,3,8>|5 (5.0) <0,5,0>|0|0|0|0|100%|43|![](https://media.fortniteapi.io/images/cb7f23c5bb967f8618d51fa143d27fb2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/241b1764d67963c5ded8f147c57527a2/transparent.png){:height="35px"}|
|28||STsixGAMING|4.8|4.0 <4>|1 (1.0) <1>|0|0|0|0|0%|153|![](https://media.fortniteapi.io/images/0c3ea68-65c83bb-6a93e44-0939ee3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/012d4e3266cf15800532a5a41473afd8/transparent.png){:height="35px"}|
|29||cintron1981|1.9|11.0 <10,12>|1 (1.0) <0,1>|0|1|0|0|0%|87|![](https://media.fortniteapi.io/images/744f37053c7e060b143a797abc630b9c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4e53d164a2dea81b5634a75401b0c475/transparent.png){:height="35px"}|
|30||RainbowPlsFan|0.9|5.0 <0,5>|4 (2.0) <3,1>|0|1|0|0|100%|252|![](https://media.fortniteapi.io/images/337a1b39ba5f980f19af27cd70a40332/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|31||Ƭricky Nicky|-3.2|9.0 <9>||0|0|0|0|100%|106|![](https://media.fortniteapi.io/images/6b780520e4b82814611bf1d504ff9d23/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|32||C3FJack34|-12.3|7.0 <5,9>||0|0|0|0|100%|27|![](https://media.fortniteapi.io/images/ff0e942-9fb4bec-7ac6735-7abdded/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2b96803147b57652833725dc7834ff5e/transparent.png){:height="35px"}|
|33||D3buff||||0|0|0|0|100%|11|![](https://media.fortniteapi.io/images/4a01aa4-70df324-0678838-f191df0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/991fc44-6a80944-025a92e-c0c37bd/transparent.png){:height="35px"}|

