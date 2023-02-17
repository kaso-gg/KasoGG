---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Feb 16, 2023 18:55:22").getTime(); // Set the date we're counting down to
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

We had 2 matches with 110 unique people and the biggest lobby had 99 playing. There were 48 people who played every match. The highest XP level was 'giantamongst' at 436. The lowest XP was 'PaPiHUDSHY' at 60, welcome to our lobby you GOAT! About 70.1% of us used girl skins. Guess what, we eliminated 47 NPCs, they will be back next game though. By the way, Three people need to turn off ANONYMOUS MODE. 28 people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: ScarletCommander(5), Evie(4), Veronika(4)<br>
* Most common pickaxes: StarWand(13), Crowbar(6), Pickaxe_VillainessVault(6)<br>
* Most common emotes: CrowningAchievement(49), LaughItUp(28), Tootsee(22)<br>

Bot identified 8 error occurances affecting 7 player(s) with a net error balance of 20.00. Only ~40.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: Cold Blooded Suit, Goya-_-16, H3ctic JapJim, HDR tiger, NICKO on FB, twitch tigerwyd, TwitchDestro. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for -573.3% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|22,390|11,270|-90|-6853.3%|0.0%|0.0%|0.0%|0.0%|-573.3%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|Obiwon|FB Classy|155.0|1.0 <0,1>|15 (7.5) <5,10>|0|0|0|0|100%|122|![](https://media.fortniteapi.io/images/9f8ef373f0778b2ab140c26385791190/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|2|FirstLoser|CHELOW RD|140.0|1.0 <0,1>|12 (6.0) <5,7>|0|0|0|0|100%|242|![](https://media.fortniteapi.io/images/fec2b771083648220d7597847a86b104/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|3|Turd|HDR tiger|135.0|1.0 <1,0>|9 (4.5) <6,3>|0|0|0|0|100%|240|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|4||SkiddlySkip|125.0|3.5 <1,0,6>|7 (2.3) <5,1,1>|1|0|0|0|0%|86|![](https://media.fortniteapi.io/images/2ad1e0e4c6cb7175e0ed2cca6d711a5b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5f4a4659ee9730ccb43e85598c067092/transparent.png){:height="35px"}|
|5|Fourth|Goya-_-16|125.0|1.0 <0,1>|4 (4.0) <0,4>|0|0|0|0|0%|211|![](https://media.fortniteapi.io/images/57ac005da8ad9c27771de868a23408ef/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f395796a68a2ab34ac2349228439af44/transparent.png){:height="35px"}|
|6|Jive|FB AllTimePrime|120.0|3.5 <1,0,6>|5 (2.5) <3,0,2>|2|0|0|0|67%|254|![](https://media.fortniteapi.io/images/97059b0a0e94d7d9cc8abf9bf6c99165/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b553eaf70ab4295b9a8c0299f9c260f2/transparent.png){:height="35px"}|
|7||OutKast On FB|95.0|5.0 <2,0,8>|15 (5.0) <3,5,7>|2|0|0|0|0%|223|![](https://media.fortniteapi.io/images/05d48c179fb90ae473093c07e02db4d3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c432ada4a32eb8e52774014785040ab/transparent.png){:height="35px"}|
|8||NICKO on FB|90.0|5.0 <2,0,8>|11 (3.7) <5,2,4>|1|0|0|0|0%|228|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|9||Unholy Dabs|90.0|8.5 <1,0,16>|1 (1.0) <1,0,0>|0|0|0|0|0%|233|![](https://media.fortniteapi.io/images/59eb4f6-e81c036-42fab23-375205c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dc2226d-4b7e29d-1701957-210f352/transparent.png){:height="35px"}|
|10||smidster1256|85.0|4.5 <7,0,2>|9 (3.0) <4,1,4>|1|0|0|0|0%|223|![](https://media.fortniteapi.io/images/8a7d59675dd875bb4c618395bdebd7e1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/59482506d87fbd96ff7f20d3d7ded71d/transparent.png){:height="35px"}|
|11||FB_BLAST215|85.0|8.5 <1,0,16>||0|0|0|0|0%|96|![](https://media.fortniteapi.io/images/b872ad3-923e9b4-ca31120-077f563/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e9d8b2cc107db6c5ee6535d54eb76934/transparent.png){:height="35px"}|
|12||Youtube-Jaay-Tee|60.0|4.0 <0,4>|12 (6.0) <4,8>|1|0|0|0|100%|1|![](https://media.fortniteapi.io/images/09be283-c697242-d13b3f6-748264d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/128928a-3e4385b-50c4b4a-4240a82/transparent.png){:height="35px"}|
|13||FB_Uncle Frank|60.0|5.0 <2,0,8>|4 (1.3) <2,1,1>|0|0|0|0|0%|218|![](https://media.fortniteapi.io/images/f0583410ad54e80d9f3a3a93d6469689/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|14||dracoflames30|55.0|4.0 <6,0,2>|2 (2.0) <2,0,0>|0|0|0|0|100%|71|![](https://media.fortniteapi.io/images/0488639b1fd10e1af2fd228ac4996b6a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/c48f75b56c93999ab661a3b5ec48ff4b/transparent.png){:height="35px"}|
|15|Zen|TwitchDestro|55.0|5.0 <2,0,8>|3 (1.5) <0,1,2>|0|0|0|0|67%|162|![](https://media.fortniteapi.io/images/a40ba1726d5029ab566aed545e7c6493/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|16||YiKES FL|55.0|2.0 <0,2>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/6fa359bab771370222f46885a6a9dd2c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|17||TTV Sick Prodigy|35.0|3.0 <0,3>|1 (1.0) <0,1>|5|0|0|0|100%|234|![](https://media.fortniteapi.io/images/a23a5e6-b8788e5-e9e35fc-be42323/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2b73b01-5d8bfc9-470f416-7c5e253/transparent.png){:height="35px"}|
|18||sniperkid-GGs|35.0|6.5 <11,0,2>||1|0|0|0|33%|35|![](https://media.fortniteapi.io/images/61353db005257542ce48c83d2485a24d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|19||Waifu me please|30.0|4.0 <4,0>|2 (2.0) <2,0>|0|0|0|0|100%|202|![](https://media.fortniteapi.io/images/99cd2ba-e442355-3eb9ee5-c8842d1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|20||j_e_r_i_e_l02|30.0|4.0 <0,4>|2 (2.0) <0,2>|0|0|0|0|0%|89|![](https://media.fortniteapi.io/images/3281a033bd25915f38bcb401c7ae5e60/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b9ef8159c41c70190910adb40ced2ced/transparent.png){:height="35px"}|
|21||CosmicEclispe04|30.0|3.0 <0,3>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/3216721deaac7ead0d0623a71f3989d2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ce322e2160a6aadce7c95bcf819bd43b/transparent.png){:height="35px"}|
|22||Sick Plays FB|30.0|3.0 <3,0>||1|0|0|0|100%|292|![](https://media.fortniteapi.io/images/c137899-d9cce8f-8e56b1c-1ea2635/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|23||Joedirte32|25.0|8.0 <3,0,13>|3 (3.0) <3,0,0>|1|0|0|0|67%|172|![](https://media.fortniteapi.io/images/a85cc36d483ace298e4fdfb2611d3a50/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9293e8e2a91396e03e3153b5b0c72f6a/transparent.png){:height="35px"}|
|24||FB_IAMpassano|25.0|5.0 <5>|3 (3.0) <3>|0|0|0|0|0%|345|![](https://media.fortniteapi.io/images/8f989fc3edf875e7f73b6dcdbe1f082d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|25||twitch tigerwyd|20.0|10.0 <0,10>|11 (5.5) <5,6>|0|0|0|0|100%|150|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|26||Newfound_Lander|20.0|4.0 <0,4>||1|0|0|0|100%|174|![](https://media.fortniteapi.io/images/9b870dc076559b59c913fd6992ce5b60/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/353476001a41d4b0ad0bb3e6e90ca158/transparent.png){:height="35px"}|
|27||ObeyRealPrince|20.0|4.5 <6,0,3>||0|0|0|0|67%|121|![](https://media.fortniteapi.io/images/eda4913-c868e30-42291e9-4a1ddcf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|28||ImAlabamaWorley|15.0|5.0 <0,5>|2 (1.0) <1,1>|0|0|0|0|0%|178|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|29||ZeroFoxtrot6124|15.0|5.0 <5>|1 (1.0) <1>|0|0|0|0|0%|186|![](https://media.fortniteapi.io/images/fec2b771083648220d7597847a86b104/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/8d7b7960776bd3be44711d8b3c7731c6/transparent.png){:height="35px"}|
|30||LtothaBeezy_ttv|10.0|10.0 <10,0,10>|7 (2.3) <3,1,3>|0|0|0|0|100%|72|![](https://media.fortniteapi.io/images/49d8994ceef2ea917eba44d6d2b0711d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|31||Ya-I-GotSkillz|10.0|7.0 <7>|4 (4.0) <4>|0|0|0|0|0%|246|![](https://media.fortniteapi.io/images/0f7759ecf52f51fb438857c38aa95e15/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|32||Gus_RDU|10.0|5.0 <0,5>||0|0|0|0|0%|236|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|33||Future_Glide|10.0|5.0 <0,5>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d6279cf759c1953515b220986b63f6f9/transparent.png){:height="35px"}|
|34||MDNT_DANK|5.0|9.0 <0,9>|4 (2.0) <1,3>|0|0|0|0|0%|214|![](https://media.fortniteapi.io/images/5b524450d52401962eb7df7d77b8903f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/bd735515375038c413af419f49d12527/transparent.png){:height="35px"}|
|35||KingOfCaffeine|5.0|7.0 <9,0,5>|2 (1.0) <0,1,1>|0|0|0|0|100%|199|![](https://media.fortniteapi.io/images/d0a789e2b1b8860647f07fcfc43e6dce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/75c6ab1eb8f21f2953a32c0c9e222a49/transparent.png){:height="35px"}|
|36||Quinz543|0.0|10.0 <10>|2 (2.0) <2>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/72c4ef1f1a2f5412882bc20a86cc290f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/05756913421d9f5c8e8427303875c12a/transparent.png){:height="35px"}|
|37||MDNT Kimmell|-5.0|18.7 <4,26,26>|7 (2.3) <3,2,2>|0|0|0|0|100%|239|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/335dd8d569d71a5680887c39f8663130/transparent.png){:height="35px"}|
|38||SleeplessREM-GG|-5.0|15.0 <0,15>|6 (3.0) <3,3>|0|0|0|0|0%|310|![](https://media.fortniteapi.io/images/7ef5c2d3fe4d91ba496ebfb9cf6040ec/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/38bc5835468fc357cd6305b4f6d95258/transparent.png){:height="35px"}|
|39||MDNT Cassie7|-5.0|9.0 <0,9>|1 (1.0) <0,1>|0|0|0|0|100%|222|![](https://media.fortniteapi.io/images/5b524450d52401962eb7df7d77b8903f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/335dd8d569d71a5680887c39f8663130/transparent.png){:height="35px"}|
|40||FNCS Ethan17|-5.0|13.5 <18,0,9>|2 (1.0) <0,1,1>|0|0|0|0|0%|214|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6611610a7c2c07da2930b683dde37eef/transparent.png){:height="35px"}|
|41||XxRETROGAMERxX80|-5.0|9.0 <9,0>|1 (1.0) <1,0>|0|0|0|0|100%|209|![](https://media.fortniteapi.io/images/5b524450d52401962eb7df7d77b8903f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c11d31f59ef6b26984a7b9464f12c00/transparent.png){:height="35px"}|
|42||Guttedheart1444|-10.0|10.5 <7,0,14>|5 (1.7) <3,1,1>|1|0|0|0|100%|69|![](https://media.fortniteapi.io/images/a743c6fa634f84ded8fadb10529677b3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ddb520ebf2db2db80b851de8c89a558e/transparent.png){:height="35px"}|
|43||ReadyUpJeffHaHa|-10.0|8.0 <6,10,0>|2 (1.0) <1,1,0>|0|0|0|0|33%|196|![](https://media.fortniteapi.io/images/97cecc17672237f13bfbc5cee17ae18f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|44||TikTok Greed.GGs|-10.0|11.0 <11,0>|3 (1.5) <2,1>|0|0|0|0|100%|343|![](https://media.fortniteapi.io/images/2abff3a-f937f9c-68a66ed-d0b2b10/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|45||Yukashika|-10.0|8.0 <8>||0|0|0|0|100%|62|![](https://media.fortniteapi.io/images/a06c370-44b6b5c-73d510c-39b8ebf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|46||hyper_youtube1|-10.0|10.0 <10>||0|0|0|0|0%|162|![](https://media.fortniteapi.io/images/1548c964b85d40663c8e9d2c693920ee/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|47||Qswin87_THF|-10.0|10.0 <0,10>||1|0|0|0|0%|1|![](https://media.fortniteapi.io/images/89566b85647e0e8f9b331c6cb653f957/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/486ec6860e21fa074efff7c5aa7f0ea9/transparent.png){:height="35px"}|
|48||MDNT-Stiles|-15.0|18.7 <4,26,26>|4 (1.3) <2,1,1>|1|0|0|0|100%|212|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/335dd8d569d71a5680887c39f8663130/transparent.png){:height="35px"}|
|49||Sfragida|-15.0|17.0 <5,23,23>|3 (1.0) <1,1,1>|0|0|0|0|33%|270|![](https://media.fortniteapi.io/images/117f54c-2985b28-ee59013-a625629/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4961c7a066362c6e6008e0a96cdedc7d/transparent.png){:height="35px"}|
|50||LyRiCaLgVa|-15.0|11.0 <11>|1 (1.0) <1>|1|0|0|0|0%|174|![](https://media.fortniteapi.io/images/20202e4e2efac90651b8df5dcc637474/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|51||Beef ʕᵒᴥᵒʔ|-15.0|8.0 <9,0,7>|1 (1.0) <0,0,1>|0|0|0|0|100%|133|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|52||FAIR2YOU|-15.0|11.0 <0,11>|2 (1.0) <1,1>|0|0|0|0|100%|115|![](https://media.fortniteapi.io/images/a0cf0eb956aa5483a9ae4394d1157ff3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/bc4d4d222c9be521d43989a7cc98595a/transparent.png){:height="35px"}|
|53||ᴍᴏʟꜱᴏɴ|-15.0|19.0 <19,19>|2 (1.0) <1,1>|0|0|0|0|100%|258|![](https://media.fortniteapi.io/images/a97caf0bd36ab4c7fa271683ddb78c8c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7129fe22482a29f1fdacec0628cc095a/transparent.png){:height="35px"}|
|54||H3ctic JapJim|-15.0|18.0 <18,18>|2 (1.0) <1,1>|0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/5047282e970a3e541244e880d9b2594f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c432ada4a32eb8e52774014785040ab/transparent.png){:height="35px"}|
|55||Snacky1x 私|-20.0|11.5 <17,0,6>|3 (1.0) <1,1,1>|0|0|0|0|100%|112|![](https://media.fortniteapi.io/images/cc42ad0f034ec6f144fadde8e518466d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|56||ᵀʷⁱᵗᶜʰ ZayBae1x|-20.0|11.5 <17,0,6>|2 (1.0) <1,0,1>|1|1|0|1|0%|158|![](https://media.fortniteapi.io/images/f0b26d053e6d305d220a1e7a40e7ed1d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6c713c090223cb2e8478dbfe6d5fd649/transparent.png){:height="35px"}|
|57||MDNT Swoley|-20.0|18.7 <4,26,26>|4 (2.0) <0,2,2>|0|1|0|1|100%|125|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/335dd8d569d71a5680887c39f8663130/transparent.png){:height="35px"}|
|58||Theprinciple465|-20.0|17.0 <5,23,23>|2 (1.0) <0,1,1>|0|0|0|0|100%|61|![](https://media.fortniteapi.io/images/b57c9b58faaea1e7bd18095245de42b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7ff26d205ceed6523ff08ebc472dd9d7/transparent.png){:height="35px"}|
|59||Creepz3617|-20.0|11.0 <11>||0|0|0|0|0%|178|![](https://media.fortniteapi.io/images/d49effb-e8c0866-3642ef4-44b0c2f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b679d42cc0ddfa85942297bdd3ba15ce/transparent.png){:height="35px"}|
|60||H4SH A77ACk|-20.0|16.0 <16>||0|0|0|0|0%|100|![](https://media.fortniteapi.io/images/8a7d59675dd875bb4c618395bdebd7e1/transparent.png){:height="35px"}|![](){:height="35px"}|
|61||Itzz Kaiden4|-20.0|16.0 <16,0>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9157c23-456079b-432ab35-ab64fb4/transparent.png){:height="35px"}|
|62||jickyron|-20.0|19.3 <18,20,20>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|63||Liliypad|-20.0|15.0 <0,15>||0|0|0|0|100%|117|![](https://media.fortniteapi.io/images/7ef5c2d3fe4d91ba496ebfb9cf6040ec/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ff2621ab894a8ed348609c3a07c2fd94/transparent.png){:height="35px"}|
|64||Ttv_paparugzzz|-20.0|11.0 <11>||0|0|0|0|100%|307|![](https://media.fortniteapi.io/images/eda4913-c868e30-42291e9-4a1ddcf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|65||TTV P3psiDad|-20.0|17.0 <17,17>||1|0|0|0|100%|1|![](https://media.fortniteapi.io/images/142913526bf1b32ba9433bf5de83e010/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9293e8e2a91396e03e3153b5b0c72f6a/transparent.png){:height="35px"}|
|66||SGfour_|-20.0|19.0 <19,19>||0|0|0|0|100%|201|![](https://media.fortniteapi.io/images/86da499-f41aa44-6696faf-408b001/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/32dbe6ef4702cc561bd5c8a86376ef94/transparent.png){:height="35px"}|
|67||light_ice_|-20.0|16.0 <0,16>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/dd61eceb80d87da4f4357b485813fd8d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3be2c7b-f65d0f3-ac50092-83d2017/transparent.png){:height="35px"}|
|68||ITZ_ARTT|-20.0|19.0 <19,19>||0|0|0|0|100%|149|![](https://media.fortniteapi.io/images/07429fa12a5f6a7f8e8f1db85656950f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|69||Megasauras97|-20.0|14.0 <14,0>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/a4fa870c1eb1022ddfab6e6b60bfbed0/transparent.png){:height="35px"}|![](){:height="35px"}|
|70||antsee22|-20.0|14.0 <0,14>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/15ec30ef7243253f918c8c21c6559eb9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/285f79e41b48fdacb3d3fb867972558a/transparent.png){:height="35px"}|
|71||VIPER_MOM_RPS|-20.0|11.0 <0,11>||0|0|0|0|100%|92|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/710d251ee0a3ec2d209e24ddde84bf65/transparent.png){:height="35px"}|
|72||GhostSniperMLB|-20.0|19.0 <19,19>||0|0|0|0|100%|230|![](https://media.fortniteapi.io/images/6ab699ca8456e1092e07ffc2bdb131c7/transparent.png){:height="35px"}|![](){:height="35px"}|
|73||prince pillar|-20.0|15.0 <15>||0|0|0|0|100%|213|![](https://media.fortniteapi.io/images/bc0dca1bae51a572088a28532ea5c62f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6611610a7c2c07da2930b683dde37eef/transparent.png){:height="35px"}|
|74||CPK_kaso|-25.0|15.7 <13,17,17>|3 (3.0) <3,0,0>|1|0|0|0|67%|112|![](https://media.fortniteapi.io/images/d21d66fa0862d77b174b07425d298335/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|75||Muttdogs|-25.0|10.0 <6,0,14>|1 (1.0) <1,0,0>|0|0|0|0|0%|218|![](https://media.fortniteapi.io/images/de5a3969792834fd25de931f4d435782/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/8e1d20f72c2877926994ac47b9871830/transparent.png){:height="35px"}|
|76||MDNT-AlltheLight|-25.0|18.7 <4,26,26>|1 (1.0) <1,0,0>|1|0|0|0|100%|326|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/335dd8d569d71a5680887c39f8663130/transparent.png){:height="35px"}|
|77||Spartan ᵒⁿ ᶠᵇ|-25.0|10.5 <10,0,11>|1 (1.0) <0,0,1>|0|0|0|0|33%|185|![](https://media.fortniteapi.io/images/4a4736af1b7de98fbbc2f53aa1af2848/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d0ede8f-343a5e4-ca342cf-06f23a6/transparent.png){:height="35px"}|
|78||fifa-hotsauce|-30.0|18.0 <14,20,20>|3 (1.0) <1,1,1>|0|0|0|0|0%|265|![](https://media.fortniteapi.io/images/a5df3724c04d4f090c20187a44eaf7d3/transparent.png){:height="35px"}|![](){:height="35px"}|
|79||BaseballBoy42555|-30.0|12.0 <12,12,0>|2 (2.0) <2,0,0>|0|0|0|0|100%|294|![](https://media.fortniteapi.io/images/4c5542e-6f3676d-6a54bd7-19b4d9d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a93738d58fc038fdb345fe51150fa39d/transparent.png){:height="35px"}|
|80||NastalG|-30.0|25.0 <25,25>|2 (1.0) <1,1>|0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/c06b7481f7f0579b8a9fcbf8905932da/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3e5a1599e8620abd44155917aa2f5b2c/transparent.png){:height="35px"}|
|81||Nadroj1987|-35.0|16.0 <17,0,15>|2 (1.0) <0,1,1>|0|0|0|0|100%|61|![](https://media.fortniteapi.io/images/0ea493661faa0b11a8e580481a58cf79/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4ce8fae-eb40b16-f9a789f-0ee6363/transparent.png){:height="35px"}|
|82||Twitch_elee|-35.0|18.0 <14,20,20>|2 (1.0) <0,1,1>|1|0|0|0|100%|1|![](https://media.fortniteapi.io/images/6ab699ca8456e1092e07ffc2bdb131c7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/890fed5-625a443-274afd6-82af64c/transparent.png){:height="35px"}|
|83||Jolee Knox_TTV|-35.0|15.7 <13,17,17>|1 (1.0) <1,0,0>|0|0|0|0|100%|253|![](https://media.fortniteapi.io/images/b5acca5f9e0460f0120be44db1bc8ae1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/580f79849458a2b1b74fe0b397034612/transparent.png){:height="35px"}|
|84||TTVbella_snipes|-35.0|18.0 <14,20,20>|1 (1.0) <1,0,0>|0|0|0|0|67%|275|![](https://media.fortniteapi.io/images/61353db005257542ce48c83d2485a24d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1b797f7325f705c4eaec66c91dde5e4e/transparent.png){:height="35px"}|
|85||BaseballRob89|-35.0|12.0 <12,12,0>|1 (1.0) <1,0,0>|0|0|0|0|33%|183|![](https://media.fortniteapi.io/images/a4fa870c1eb1022ddfab6e6b60bfbed0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/75c6ab1eb8f21f2953a32c0c9e222a49/transparent.png){:height="35px"}|
|86||Matty_On_GameBoy|-35.0|16.0 <17,0,15>|2 (1.0) <0,1,1>|0|0|1|0|67%|64|![](https://media.fortniteapi.io/images/0d13fd9-4330b64-620dedb-bbd40b9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c432ada4a32eb8e52774014785040ab/transparent.png){:height="35px"}|
|87||MDNT Ashley|-35.0|21.0 <21,21>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/392e1e9e14d613cef135931a046a9417/transparent.png){:height="35px"}|
|88||GRafAaliyah|-35.0|25.0 <25,25>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/f154ad1a24b0815edd5d4223c8c792a2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|89||MDNT-Linkfuzzbal|-35.0|21.0 <21,21>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/43b8dd9fc23b685d251e1d92139bd2c0/transparent.png){:height="35px"}|
|90||BethDawn|-35.0|23.0 <23,23>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/15ec30ef7243253f918c8c21c6559eb9/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a51e543eb31c41da84dd4f709812a807/transparent.png){:height="35px"}|
|91||Tshel5190|-35.0|21.0 <21,21>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/05c48936305179b91613cac98be12beb/transparent.png){:height="35px"}|
|92||hurley7324|-35.0|25.0 <25,25>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/3cdca1aa06541334304c079048443519/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/54659001b6c523cc90c07e288e8afced/transparent.png){:height="35px"}|
|93||Jquest77|-35.0|23.0 <23,23>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/021475605eaa0a166f7851b13054b522/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2434630764cd49440c7d54053a16d186/transparent.png){:height="35px"}|
|94||Piro018|-35.0|24.0 <24,24>||0|0|0|0|0%|245|![](https://media.fortniteapi.io/images/45834d28e0a7936dd0659e2838290c80/transparent.png){:height="35px"}|![](){:height="35px"}|
|95||Owl_Pacino_96|-35.0|22.0 <22,22>||0|0|0|0|0%|219|![](https://media.fortniteapi.io/images/783cb313214bae416a17c7135f1446b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/c8313c78ecb3fb6df0a64b45de91bb26/transparent.png){:height="35px"}|
|96||Bouliebeans|-35.0|21.0 <21,21>||0|0|0|0|100%|1|![](https://media.fortniteapi.io/images/8e14ac6adc717dc0b137c9b5484ee3e6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e3e9d16-9aca214-c82eed9-b398cdc/transparent.png){:height="35px"}|
|97||PurplChikNik|-35.0|24.0 <24,24>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4f06a17fc41e35ede5994db1db03f4ae/transparent.png){:height="35px"}|
|98||Crystal3477|-40.0|18.3 <7,24,24>|1 (1.0) <1,0,0>|0|0|0|0|67%|28|![](https://media.fortniteapi.io/images/ae08ad2ff50bb2e18b35c712e9865a80/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6f1a6625e283e48aa0319ba3a2c6fa3d/transparent.png){:height="35px"}|
|99||CPK_jamieo|-40.0|15.7 <13,17,17>||0|0|0|0|100%|214|![](https://media.fortniteapi.io/images/d03e1f9-eeda5c0-7c72636-f392e31/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/895655a-7f0c2ad-e3a4aa8-983ef5e/transparent.png){:height="35px"}|
|100||BaseballMom2114|-40.0|12.0 <12,0,12>||0|0|0|0|100%|63|![](https://media.fortniteapi.io/images/19fb294c23029dae4739d0945ad1fcd1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9293e8e2a91396e03e3153b5b0c72f6a/transparent.png){:height="35px"}|
|101||SamazyM09|-40.0|12.0 <12,12,0>||0|0|0|0|100%|133|![](https://media.fortniteapi.io/images/ec7cf478b8c0d34d89a7ee43da1f6bc5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b9ef8159c41c70190910adb40ced2ced/transparent.png){:height="35px"}|
|102||IsaacEffinStylin|-45.0|19.0 <9,24,24>||0|0|0|0|100%|130|![](https://media.fortniteapi.io/images/3f648f7d38cfe74d1f9e1e72b2f451fb/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/a93738d58fc038fdb345fe51150fa39d/transparent.png){:height="35px"}|
|103||Cowboyz 1119415|-50.0|20.0 <16,22,22>|2 (1.0) <0,1,1>|1|0|0|0|0%|80|![](https://media.fortniteapi.io/images/f527a208920502bb47e982a051e06e67/transparent.png){:height="35px"}|![](){:height="35px"}|
|104||triqulify|-50.0|20.0 <16,22,22>|2 (1.0) <0,1,1>|0|0|0|0|33%|70|![](https://media.fortniteapi.io/images/9ee2208-af767e3-3e46637-4918a3f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e52103c-718673f-6418bc7-4b4a6bd/transparent.png){:height="35px"}|
|105||PaPiHUDSHY|-50.0|27.0 <27,27>||0|0|0|0|100%|60|![](https://media.fortniteapi.io/images/5669cf0-7dcbc51-c40d4eb-8f4d007/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/090cd7cb26ef80eb3ee797a1ee78078f/transparent.png){:height="35px"}|
|106||giantamongst|-55.0|20.3 <17,22,22>||1|0|0|0|0%|146|![](https://media.fortniteapi.io/images/ceb0f681716aba2e7a383b450ca4155d/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/20656ae628d35bc204efd6fc3cff6526/transparent.png){:height="35px"}|
|107||MR-_AFK_-|-55.0|21.0 <13,25,25>||0|0|0|0|33%|76|![](https://media.fortniteapi.io/images/a4ae8f546570a63acd3d87f50d37bdfc/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4db13c6c4a2e960b5fe767c48ff42269/transparent.png){:height="35px"}|
|108||ImBuiltDiferent1|-60.0|20.7 <8,27,27>||0|0|1|0|100%|246|![](https://media.fortniteapi.io/images/ddb5dcf96f6154a21e90c80d0661d7a4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/408ef161c04a6910a98fcbd25a7a07cd/transparent.png){:height="35px"}|
|109||OutofNowhereGirl|-60.0|20.7 <8,27,27>||0|0|0|0|0%|40|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/65e15ffba968b03d600a5411704876e4/transparent.png){:height="35px"}|
|110||trippinbro596|-60.0|20.7 <8,27,27>||0|0|0|0|33%|53|![](https://media.fortniteapi.io/images/eed1dc1709f78c998adf0df066086eed/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

