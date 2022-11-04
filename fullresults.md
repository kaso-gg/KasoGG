---
permalink: /fullresults/
title: "full score results"
excerpt: "Full score results all on one page!"
markdown: kramdown
---
<meta http-equiv="refresh" content="30">

<script>
    var countUpdDate = new Date("Nov 03, 2022 20:04:08").getTime(); // Set the date we're counting down to
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

We had 1 matches with 50 unique people and the biggest lobby had 50 playing. There were 50 people who played every match. The highest XP level was 'L2 Bin Laden' at 262. The lowest XP was 'nmehra54' at 12, welcome to our lobby you GOAT! About 91.3% of us used girl skins. Nobody killed an NPC, what gives? By the way, Four people need to turn off ANONYMOUS MODE. Twelve people have donkey laugh in their locker emotes, HEE HAW!

* Most common skins: Joltara(4), Bytes(1), Bullseye(1)<br>
* Most common pickaxes: IceBreaker(9), StarWand(4), HarleyHitter(3)<br>
* Most common emotes: LaughItUp(12), GetGriddy(10), Bringitaround(4)<br>

Bot identified 1 error occurances affecting 1 player(s) with a net error balance of -250.00. Only ~250.00 total tournament points are at question due to kill feed data discrepancies. Affected players are: . Let me know if you feel like it's important to fix this, but I'll have to get your .replay file or watch your stream to confirm.

Here's a breakdown of points allocation across all players and matches. This data helps to understand for example that player elims accounted for -15.8% of all points earned this session and 0.0% of the points were given out for thanking the bus driver, LOL.

| Gross  | Penlty | Final  | Placmt | Anon   | Survivl  | ThksBus | YouDed | Elims  | Siphon | NPC    |
| :----: | :----: | :----: | :----: | :----: | :----:   | :----:  | :----: | :----: | :----: | :----: |
|5,485|3,500|-1,515|-115.2%|0.0%|0.0%|0.0%|0.0%|-15.8%|0.0%|0.0%|

This table shows placement result sorted by points. Bold **player name** means they use anonymous mode at least once. Placement and elim data shows the average value, then individual matches in brackets. All prize information and data is subject to a final review before payout. E1 is how many times you landed the first elim of the game, K1 is for first knock, and D1 is for when you were the first to be dead. TR is the bus driver thanking percentage.


| #      | Prize | Player | Pts    | Plcmnt | Elims | NPCs   | E1     | D1     | K1     | TR     | Lvl    | Skin   | Axe    |
| :----: | :---  | :---   | :----: | :---   | :---  | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|1|Obiwon|Twitch Scratdog|120.0|1.0 <1>|3 (3.0) <3>|0|0|0|0|0%|65|![](){:height="35px"}|![](){:height="35px"}|
|2|FirstLoser|twitch braydz|75.0|2.0 <2>|4 (4.0) <4>|0|0|0|0|0%|158|![](){:height="35px"}|![](){:height="35px"}|
|3|Turd|onyx kyn|40.0|4.0 <4>|4 (4.0) <4>|0|0|0|0|0%|127|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|4|Fourth|L2 Bin Laden|40.0|3.0 <3>|2 (2.0) <2>|0|0|0|0|0%|262|![](){:height="35px"}|![](){:height="35px"}|
|5|Jive|Wiji 小|15.0|7.0 <7>|5 (5.0) <5>|0|0|0|0|0%|213|![](https://media.fortniteapi.io/images/04d7bd3eed40ebe4794958c43e213398/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|6||Prime Jimbo|15.0|5.0 <5>|1 (1.0) <1>|0|0|0|0|0%|30|![](){:height="35px"}|![](){:height="35px"}|
|7||RivAntics|0.0|15.0 <15>|4 (4.0) <4>|0|0|0|0|0%|79|![](https://media.fortniteapi.io/images/3c83cd1-592e881-d91e78b-34442d8/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|8||Twitch Rjheha|0.0|9.0 <9>|2 (2.0) <2>|0|0|0|0|0%|127|![](){:height="35px"}|![](){:height="35px"}|
|9||Twitch Donniefn_|-5.0|6.0 <6>|1 (1.0) <1>|0|0|0|0|0%|22|![](https://media.fortniteapi.io/images/0a516b5a4fdf57074e8e0a63737ea4bf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|10|Zen|Icebearsp ʕᵒᴥᵒʔ|-5.0|10.0 <10>|1 (1.0) <1>|0|0|0|0|0%|112|![](https://media.fortniteapi.io/images/12a28cee9cf139fa3cc39cca6277b986/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|11||RYZE AIM|-10.0|20.0 <20>|2 (2.0) <2>|0|0|0|0|0%|75|![](){:height="35px"}|![](){:height="35px"}|
|12||JBуa|-10.0|8.0 <8>||0|0|0|0|0%|74|![](){:height="35px"}|![](){:height="35px"}|
|13||cbt reZNikisqt|-10.0|13.0 <13>|2 (2.0) <2>|0|0|0|0|0%|89|![](){:height="35px"}|![](){:height="35px"}|
|14||0SSKR|-15.0|16.0 <16>|1 (1.0) <1>|0|0|0|0|0%|1|![](){:height="35px"}|![](){:height="35px"}|
|15||Fousi.|-15.0|11.0 <11>|1 (1.0) <1>|0|0|0|0|0%|255|![](https://media.fortniteapi.io/images/5cb1508ab8223aee905bcf1afb57c43f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/6fd6c8c77fe3da8f776952dd8171570b/transparent.png){:height="35px"}|
|16||isizメ|-15.0|19.0 <19>|1 (1.0) <1>|0|0|0|0|0%|105|![](){:height="35px"}|![](){:height="35px"}|
|17||Piece CTRL Iroh|-15.0|17.0 <17>|1 (1.0) <1>|0|0|0|0|0%|123|![](){:height="35px"}|![](){:height="35px"}|
|18||PookyFN|-20.0|14.0 <14>||0|0|0|0|0%|165|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|19||ElimzX8627|-20.0|24.0 <24>|3 (3.0) <3>|0|0|0|0|0%|155|![](https://media.fortniteapi.io/images/3342d8f2545e8a2fccfa64b389169d92/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|20||Jim Lahey Ⅴ|-20.0|12.0 <12>||0|0|0|0|0%|77|![](https://media.fortniteapi.io/images/e76cb8d-bec8b2f-0161c68-5da68b4/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/14a375486863d7f10ed120bcf50ec5b2/transparent.png){:height="35px"}|
|21||nmehra54|-20.0|18.0 <18>||0|0|0|0|0%|12|![](){:height="35px"}|![](){:height="35px"}|
|22||YouTube RezzFN|-25.0|22.0 <22>|2 (2.0) <2>|0|1|0|0|0%|130|![](){:height="35px"}|![](){:height="35px"}|
|23||Twitch WMicc|-25.0|21.0 <21>|2 (2.0) <2>|0|0|0|0|0%|143|![](https://media.fortniteapi.io/images/71d6cc1e0c4af7f362b7a5874003a94e/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/128928a-3e4385b-50c4b4a-4240a82/transparent.png){:height="35px"}|
|24||sprinkle_spark69|-30.0|23.0 <23>|1 (1.0) <1>|0|0|0|0|0%|93|![](https://media.fortniteapi.io/images/29973af14bd85f0b3d2a7f61a091c3b2/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|25||Twitch Carterr1x|-35.0|25.0 <25>||0|0|0|0|0%|98|![](https://media.fortniteapi.io/images/3e756f27efe7f24dfcde9018cedc5912/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|26||JustDarkyTTV|-45.0|28.0 <28>|1 (1.0) <1>|0|0|0|0|0%|110|![](https://media.fortniteapi.io/images/a745f6813a1e61d275745cf0ba517a7f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/dd690be-dacba62-13998ad-a50a04c/transparent.png){:height="35px"}|
|27||Shaduke7.|-45.0|29.0 <29>|1 (1.0) <1>|0|0|0|0|0%|149|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/3e5a1599e8620abd44155917aa2f5b2c/transparent.png){:height="35px"}|
|28||skiic|-45.0|26.0 <26>|1 (1.0) <1>|0|0|0|0|0%|96|![](){:height="35px"}|![](){:height="35px"}|
|29||User-56bb00296a|-45.0|27.0 <27>|1 (1.0) <1>|0|0|0|0|0%|82|![](){:height="35px"}|![](){:height="35px"}|
|30||itsnotlogii|-50.0|30.0 <30>||0|0|0|0|0%|1|![](https://media.fortniteapi.io/images/4266f184d24a5159c7321cf4fa1841ce/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|31||cooney FN|-55.0|35.0 <35>|1 (1.0) <1>|0|0|0|0|0%|127|![](https://media.fortniteapi.io/images/b80232a24d16c48333a63a8bf9d4717b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/d2e8284-fb06feb-ea3fbe3-c41fd8b/transparent.png){:height="35px"}|
|32||gouldy pulls 9s|-60.0|36.0 <36>||0|0|0|0|0%|45|![](https://media.fortniteapi.io/images/3f3824cdbbe5ff412907572724f8fd5a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|33||T1 Lizzy|-60.0|39.0 <39>||0|0|0|0|0%|134|![](https://media.fortniteapi.io/images/1e55a45-cb54ceb-bafa8c9-805b40b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|34||ttv bdhcalc|-60.0|40.0 <40>||0|0|0|0|0%|174|![](https://media.fortniteapi.io/images/921bcff-7a6474b-20912b8-ed4f78a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/c630409d891712e1d089a13fce85920a/transparent.png){:height="35px"}|
|35||crippled halezy|-60.0|37.0 <37>||0|0|0|0|0%|78|![](https://media.fortniteapi.io/images/d67798f-6f476dc-9a88c27-7c7b46b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|36||2Pac Solos|-60.0|38.0 <38>||0|0|0|0|0%|72|![](){:height="35px"}|![](){:height="35px"}|
|37||youtube ShackFN|-60.0|32.0 <32>||0|0|0|0|0%|77|![](https://media.fortniteapi.io/images/5d6b82ff761b71350a84f2ed1fe9275f/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/f33b9ce-7202975-6778b2d-3fc30e2/transparent.png){:height="35px"}|
|38||daddy rex .|-60.0|31.0 <31>||0|0|0|0|0%|166|![](https://media.fortniteapi.io/images/0b5882b79617ef560fdc9e1de8b113e1/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/5dfc05d405ea8986edbd63fc8b433274/transparent.png){:height="35px"}|
|39||ToxicGG on YT|-60.0|33.0 <33>||0|0|0|0|0%|55|![](){:height="35px"}|![](){:height="35px"}|
|40||NRG.AussieAntics|-60.0|34.0 <34>||0|0|0|0|0%|173|![](){:height="35px"}|![](){:height="35px"}|
|41||Rocko h|-70.0|46.0 <46>||0|0|0|0|0%|65|![](https://media.fortniteapi.io/images/90283196e9baff14ed1ba93943d5710b/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|42||ᵗᵒⁿʸ ᵗᵗᵛ|-70.0|48.0 <48>||0|0|0|0|0%|128|![](){:height="35px"}|![](){:height="35px"}|
|43||SKLZ7|-70.0|43.0 <43>||0|0|0|0|0%|78|![](https://media.fortniteapi.io/images/3f9527a18c9da23166b91a1c63bc9faf/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/ec32e95-f5e82af-93e78e7-d72ff97/transparent.png){:height="35px"}|
|44||zase.|-70.0|45.0 <45>||0|0|0|0|0%|32|![](){:height="35px"}|![](){:height="35px"}|
|45||ㅤknee grow|-70.0|44.0 <44>||0|0|0|0|0%|36|![](){:height="35px"}|![](){:height="35px"}|
|46||StinkyToes_TTV|-70.0|50.0 <50>||0|0|1|0|0%|41|![](){:height="35px"}|![](){:height="35px"}|
|47||CPK_kaso|-70.0|47.0 <47>||0|0|0|0|0%|81|![](){:height="35px"}|![](){:height="35px"}|
|48||I bench 255lb|-70.0|42.0 <42>||0|0|0|0|0%|89|![](){:height="35px"}|![](){:height="35px"}|
|49||FаZe wavy horked|-70.0|41.0 <41>||0|0|0|0|0%|137|![](){:height="35px"}|![](){:height="35px"}|
|50||TTV PeterFNN|-70.0|49.0 <49>||0|0|0|0|0%|99|![](https://media.fortniteapi.io/images/b4ef9b1bac7fbf1f507478cddb8fcd0a/transparent.png){:height="35px"}|![](https://media.fortniteapi.io/images/56f77648c5f31b9a089c183b21034834/transparent.png){:height="35px"}|

## Click for >[HOME](https://www.kaso.gg) >[TABLE](https://www.kaso.gg/fullresults) >[KILL FEED](https://www.kaso.gg/killfeed)<br>

