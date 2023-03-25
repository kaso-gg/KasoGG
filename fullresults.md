---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Mar 25, 2023 10:07:30").getTime(); // Set the date we're counting down to
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

We had 2 matches with 46 unique people and the biggest lobby had 46 playing. There were 46 people who played every match. The highest XP level was 'fanzypantzy' at 108. The lowest XP was 'Brackets132' at 6, welcome to our lobby you GOAT! About 68.2% of us used girl skins. Guess what, we eliminated five NPCs, they will be back next game though. Thank you everyone for NOT playing on Anonymous mode. Three people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: Erisa(3), Glitch(3), ScarletCommander(3)<br>
* Most common pickaxes: Pickaxe_CrowbarSleek(3), DiveKnives(2), IdentityDisc(2)<br>
* Most common emotes: CrowningAchievement(22), BearHug(7), EID_Inferno(6)<br>

Bot identified 3 error occurances affecting 2 player(s) with a net error balance of 0.00. Only ~0.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: Triarch Nox, Schmeee76. Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for 0.0% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|468|00|468|100.0%|0.0%|0.0%|0.0%|0.0%|0.0%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|GG|NaCole_69|30.0|1.0 <1,1>|8 (4.0) <4,4>|0|0|0|0|100%|42|![](https://media.fortniteapi.io/images/f154ad1a24b0815edd5d4223c8c792a2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/841abef8a00eda5ecf1b596230acccac/transparent.png){:height="35px"}|
|2|ggz|JiggaG_4PF|30.0|1.0 <1,1>|6 (3.0) <3,3>|0|0|0|0|100%|64|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](){:height="35px"}|
|3|good job|BigPilisos|30.0|1.0 <1,1>|5 (2.5) <4,1>|0|0|0|0|0%|56|![](https://media.fortniteapi.io/images/5d89d43829d59c68aa1abef962f170fc/transparent.png){:height="35px"}|![](){:height="35px"}|
|4|goat|HippieRach|30.0|1.0 <1,1>|5 (2.5) <3,2>|1|0|0|0|100%|46|![](https://media.fortniteapi.io/images/20b57070e53fa93b5b421df31df6bf47/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|5|high five|iUsedKamui|16.0|3.0 <2,4>|5 (2.5) <2,3>|0|0|0|0|0%|52|![](https://media.fortniteapi.io/images/13e485f84b25cbca21c71cab7bfab1da/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c432ada4a32eb8e52774014785040ab/transparent.png){:height="35px"}|
|6||ᴍᴏʟꜱᴏɴ|16.0|3.0 <2,4>|3 (1.5) <1,2>|0|0|0|0|100%|63|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7129fe22482a29f1fdacec0628cc095a/transparent.png){:height="35px"}|
|7||CPK_jamieo|16.0|3.0 <2,4>|1 (1.0) <1,0>|0|0|0|0|100%|29|![](https://media.fortniteapi.io/images/d930dba-8e19b63-a6d5d94-6978fe3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/387bc01-74f3869-f996df6-ed18404/transparent.png){:height="35px"}|
|8||RickAshtray|16.0|3.0 <2,4>|1 (1.0) <0,1>|0|0|0|0|100%|15|![](https://media.fortniteapi.io/images/29973af14bd85f0b3d2a7f61a091c3b2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/8d7b7960776bd3be44711d8b3c7731c6/transparent.png){:height="35px"}|
|9||Old School 2.0|14.0|4.0 <5,3>|6 (3.0) <3,3>|1|1|0|1|50%|61|![](https://media.fortniteapi.io/images/97cecc17672237f13bfbc5cee17ae18f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|10||Grizzel|14.0|4.0 <5,3>|3 (1.5) <2,1>|1|0|1|0|100%|77|![](){:height="35px"}|![](https://media.fortniteapi.io/images/9293e8e2a91396e03e3153b5b0c72f6a/transparent.png){:height="35px"}|
|11||VincentDaGoatt|14.0|4.0 <5,3>|1 (1.0) <1,0>|0|0|0|0|100%|64|![](https://media.fortniteapi.io/images/04847ff144564319f170dd99681932ee/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1470afcef74ebc3e9f96b52fd1320466/transparent.png){:height="35px"}|
|12||cece1234677655|14.0|4.0 <5,3>||0|0|0|0|0%|18|![](https://media.fortniteapi.io/images/ae6278abbe3526e77d63a1faca4df818/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7bd11ebf53706ac267b565ed3b1f71e0/transparent.png){:height="35px"}|
|13||ᵀʷⁱᵗᶜʰ ZayBae1x|13.0|4.5 <7,2>|9 (4.5) <3,6>|0|1|0|0|100%|20|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6611610a7c2c07da2930b683dde37eef/transparent.png){:height="35px"}|
|14||Schmeee76|13.0|4.5 <7,2>|4 (2.0) <1,3>|0|0|0|0|100%|33|![](https://media.fortniteapi.io/images/e9d61c4a4aae593fbac8d72182da83f2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2149460bed6da81cbc9a5c8ba2a0e4ff/transparent.png){:height="35px"}|
|15||badCorpsman|13.0|4.5 <7,2>|1 (1.0) <0,1>|1|0|0|0|100%|28|![](https://media.fortniteapi.io/images/5d89d43829d59c68aa1abef962f170fc/transparent.png){:height="35px"}|![](){:height="35px"}|
|16||WatCKa007|13.0|4.5 <7,2>||0|0|0|0|100%|48|![](https://media.fortniteapi.io/images/b5c05e27736ff99ff547e6a9e847dc6b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/05c48936305179b91613cac98be12beb/transparent.png){:height="35px"}|
|17||cmon .|9.0|6.5 <6,7>|5 (2.5) <2,3>|0|0|0|0|100%|97|![](){:height="35px"}|![](){:height="35px"}|
|18||Brackets132|9.0|6.5 <6,7>|1 (1.0) <1,0>|0|0|0|0|100%|3|![](https://media.fortniteapi.io/images/d2a9889e8c90f9287bb1d416ff78f019/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/87813ad11ba0d379fc09ba6e003e8530/transparent.png){:height="35px"}|
|19||ConJoGaming|9.0|6.5 <6,7>||0|0|0|0|50%|34|![](https://media.fortniteapi.io/images/9dbfba8d8a641c7964207739b01778f6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/2821715ae77ce3a826a547fb21c4cae3/transparent.png){:height="35px"}|
|20||CPK_kaso|9.0|6.5 <6,7>||1|0|0|0|100%|50|![](https://media.fortniteapi.io/images/072402071dcaac29ee547d1c40ac24b5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|21||DocsGamesYouTube|8.0|7.0 <3,11>|5 (2.5) <4,1>|0|0|0|0|50%|30|![](https://media.fortniteapi.io/images/de92b06-8bbfd0f-cae852b-b674681/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d0ede8f-343a5e4-ca342cf-06f23a6/transparent.png){:height="35px"}|
|22||buckeyeyoyo|8.0|7.0 <3,11>|3 (1.5) <2,1>|0|0|0|0|100%|37|![](https://media.fortniteapi.io/images/5c25ad9-965d973-1ecd1c9-4a06e53/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/bf781d1-baafaa7-40a5dc8-7bb3923/transparent.png){:height="35px"}|
|23||DadNoBuild|8.0|7.0 <3,11>|2 (2.0) <2,0>|0|0|0|0|100%|48|![](https://media.fortniteapi.io/images/6af5fb0c4127ab98be084d6ec5ed499c/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6f1e20f1c9ffbc25f5d3ec2bcbbaeb79/transparent.png){:height="35px"}|
|24||SaberCodeRedYT|8.0|7.0 <4,10>|2 (2.0) <2,0>|0|0|0|0|100%|44|![](https://media.fortniteapi.io/images/dea0d24fae2f52363e9d3f5ec8029cad/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/813ae479b895c8f3669f63363d90d4aa/transparent.png){:height="35px"}|
|25||RealQueen420|8.0|7.0 <4,10>|1 (1.0) <1,0>|0|0|0|0|100%|58|![](https://media.fortniteapi.io/images/bf04b0beeb63b21268e99d9df769f51b/transparent.png){:height="35px"}|![](){:height="35px"}|
|26||TYLER_MOREAU_YT|8.0|7.0 <9,5>|1 (1.0) <0,1>|0|0|0|0|0%|28|![](https://media.fortniteapi.io/images/10152349852b512cf59d93156e451ca7/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/4ac77926c7446b593d03ef217e40f89b/transparent.png){:height="35px"}|
|27||ASG_Rtad2002|8.0|7.0 <9,5>||0|0|0|0|100%|31|![](https://media.fortniteapi.io/images/40274a4-d5db17a-d975314-a9971a6/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/e52103c-718673f-6418bc7-4b4a6bd/transparent.png){:height="35px"}|
|28||Ted302|8.0|7.0 <9,5>||0|0|0|0|100%|65|![](https://media.fortniteapi.io/images/97cecc17672237f13bfbc5cee17ae18f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1c7fb76aca7496083220a4c2d84fb110/transparent.png){:height="35px"}|
|29||QBall693971|8.0|7.0 <3,11>||0|0|0|0|50%|17|![](https://media.fortniteapi.io/images/f77256c89d682760479afca924a6da47/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/7db03922296208ea119eea6ce4b0d8a9/transparent.png){:height="35px"}|
|30||BuckeyeBunny|8.0|7.0 <4,10>||0|0|0|0|100%|94|![](https://media.fortniteapi.io/images/473c1f0e7f3c310eae7c3b580609429b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/cbcb9e145a9ae22fdd377bc5af228b8c/transparent.png){:height="35px"}|
|31||BfromO|8.0|7.0 <9,5>||0|0|0|0|0%|26|![](https://media.fortniteapi.io/images/a5df3724c04d4f090c20187a44eaf7d3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d6279cf759c1953515b220986b63f6f9/transparent.png){:height="35px"}|
|32||V1king of Norway|5.0|8.5 <11,6>|1 (1.0) <0,1>|0|0|0|0|50%|48|![](https://media.fortniteapi.io/images/151e3f434db4be26af0d928d7504c5a3/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b83fc2365d120052de1e245252f73e60/transparent.png){:height="35px"}|
|33||OldManJersey|5.0|8.5 <11,6>|1 (1.0) <0,1>|0|0|0|0|100%|43|![](https://media.fortniteapi.io/images/1de0ec7-3d274f7-fc013ae-a66d612/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/05c48936305179b91613cac98be12beb/transparent.png){:height="35px"}|
|34||SuPpLy_DrAwP_13|5.0|8.5 <11,6>||0|0|0|0|100%|45|![](https://media.fortniteapi.io/images/a22a0c603d543a60dd37432e09d1205e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb488368dc072c4b4e11f9c7a9dbb08e/transparent.png){:height="35px"}|
|35||gupi6|5.0|8.5 <11,6>||0|0|0|0|100%|27|![](https://media.fortniteapi.io/images/073639580890af786a3804bca6efb3e0/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/b6ca3b6d9dddfe2b1616d89fcd1be224/transparent.png){:height="35px"}|
|36||fanzypantzy|4.0|9.0 <10,8>|9 (4.5) <2,7>|0|0|0|1|0%|108|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/0692194-9c5b386-445cf82-2cb484d/transparent.png){:height="35px"}|
|37||donzerelli76|4.0|9.0 <10,8>|1 (1.0) <1,0>|0|0|0|0|0%|37|![](https://media.fortniteapi.io/images/d96579630a4aa5fc9d427fbeec8ab712/transparent.png){:height="35px"}|![](){:height="35px"}|
|38||RLM Sherry|4.0|9.0 <10,8>||0|0|0|0|100%|46|![](https://media.fortniteapi.io/images/97cecc17672237f13bfbc5cee17ae18f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/eb390e0a1e7ff085ff8c1e7a5a3afa53/transparent.png){:height="35px"}|
|39||FourAll2See|3.0|10.0 <8,12>|1 (1.0) <1,0>|0|0|0|0|0%|70|![](https://media.fortniteapi.io/images/ae10d7211a0aedd4824da7ef221111a8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/65346f1e401a2537731589e3149a7af3/transparent.png){:height="35px"}|
|40||coachcoble|3.0|10.0 <8,12>|1 (1.0) <1,0>|0|0|0|0|100%|101|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ca6cfb9-54bc587-e5c6dce-1b4fc3e/transparent.png){:height="35px"}|
|41||OldSniper69|3.0|10.0 <8,12>|1 (1.0) <1,0>|0|0|0|0|50%|32|![](https://media.fortniteapi.io/images/b84d6cac4da0214db9907771c0657b17/transparent.png){:height="35px"}|![](){:height="35px"}|
|42||SfromO|3.0|10.0 <8,12>||0|0|1|0|50%|37|![](https://media.fortniteapi.io/images/c4d9480a09360cce72c922389d99ff64/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1f3b661fb42bca6087ef654201c0e009/transparent.png){:height="35px"}|
|43||Mario From NY|2.0|10.5 <12,9>||0|0|0|0|50%|44|![](https://media.fortniteapi.io/images/142913526bf1b32ba9433bf5de83e010/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/1cfb016590d1c7688a25bb0fc591f9cc/transparent.png){:height="35px"}|
|44||TOMMY OF TROY|2.0|10.5 <12,9>||0|0|0|0|100%|63|![](https://media.fortniteapi.io/images/9cb0197858f70248e1cd90ba9055e36b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/effb24cea6003553a8c0088c51c92e26/transparent.png){:height="35px"}|
|45||PANDAGAMINGRD448|2.0|10.5 <12,9>||0|0|0|0|0%|59|![](https://media.fortniteapi.io/images/c630ae8da7c1f66f60c7f6d4c81131b5/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/9e36e49a4897bf9de11dde8eb805b121/transparent.png){:height="35px"}|
|46||skinnydog55|2.0|10.5 <12,9>||0|0|0|0|100%|95|![](){:height="35px"}|![](https://media.fortniteapi.io/images/9293e8e2a91396e03e3153b5b0c72f6a/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

