# mlb-the-show-franchise-os

<html>

<head>

<style>

/* ========================================= */
/* MLB THE SHOW 26 FRANCHISE OS */
/* COMPLETE CSS */
/* ========================================= */

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  background:
  linear-gradient(
    135deg,
    #0f172a,
    #111827,
    #020617
  );

  color:#f8fafc;

  font-family:
  Arial,
  Helvetica,
  sans-serif;

  padding:20px;

  min-height:100vh;
}

h1{

text-align:center;

font-size:38px;

margin-bottom:25px;

color:white;

letter-spacing:2px;

text-transform:uppercase;

text-shadow:
0 0 15px
rgba(59,130,246,.5);

}


h2{
  margin-bottom:15px;
  color:#93c5fd;
}

button{
  cursor:pointer;
}

/* ========================================= */
/* NAVIGATION */
/* ========================================= */

.nav{

  display:grid;

  grid-template-columns:
  repeat(auto-fit,minmax(150px,1fr));

  gap:8px;

  margin-bottom:20px;

}

.nav button{

background:

linear-gradient(
135deg,
#2563eb,
#1d4ed8
);

border:none;

border-radius:12px;

padding:14px;

font-weight:bold;

color:white;

transition:.2s;

}


.nav button:hover{

  background:#2563eb;

}

/* ========================================= */
/* TAB */
/* ========================================= */

.tab{

  background:#1e293b;

  border-radius:14px;

  padding:20px;

  margin-bottom:20px;

  box-shadow:
  0 0 10px rgba(0,0,0,.35);

}

/* ========================================= */
/* INPUTS */
/* ========================================= */

input{

width:100%;

padding:14px;

margin-bottom:10px;

border-radius:10px;

border:

1px solid
rgba(255,255,255,.08);

background:#0f172a;

color:white;

font-size:15px;

}

textarea{

  width:100%;

  min-height:300px;

  background:#334155;

  color:white;

  border:none;

  border-radius:10px;

  padding:12px;

  resize:vertical;

}

input::placeholder,
textarea::placeholder{

  color:#94a3b8;

}

/* ========================================= */
/* BUTTONS */
/* ========================================= */

.tab button{

  width:100%;

  padding:14px;

  margin-top:8px;

  margin-bottom:15px;

  background:#2563eb;

  border:none;

  color:white;

  border-radius:10px;

  font-weight:bold;

}

.tab button:hover{

  background:#3b82f6;

}

/* ========================================= */
/* RESULTS */
/* ========================================= */

.result{

  background:#172554;

  padding:15px;

  border-left:5px solid #60a5fa;

  border-radius:10px;

  margin-top:15px;

  min-height:50px;

}

/* ========================================= */
/* DASHBOARD */
/* ========================================= */

.dashboard-grid{

  display:grid;

  grid-template-columns:
  repeat(auto-fit,minmax(220px,1fr));

  gap:15px;

}

.card{

background:

linear-gradient(
145deg,
#1e293b,
#334155
);

padding:20px;

border-radius:18px;

border:
1px solid
rgba(255,255,255,.08);

box-shadow:

0 8px 20px
rgba(0,0,0,.35);

transition:.2s;

}

.card-title{

  font-size:13px;

  color:#cbd5e1;

  margin-bottom:8px;

}

.card-value{

font-size:32px;

font-weight:700;

margin-top:10px;

}

/* ========================================= */
/* PLAYER CARDS */
/* ========================================= */

.player-card{

background:

linear-gradient(
145deg,
#1e293b,
#334155
);

padding:18px;

margin-bottom:12px;

border-radius:15px;

border:

1px solid
rgba(255,255,255,.08);

}

.player-card h3{

  margin-bottom:6px;

  color:#93c5fd;

}

/* ========================================= */
/* SELECT */
/* ========================================= */

select{

  width:100%;

  padding:12px;

  border:none;

  border-radius:8px;

  background:#334155;

  color:white;

  margin-bottom:10px;

}

/* ========================================= */
/* STATUS COLORS */
/* ========================================= */

.good{

  color:#22c55e;

  font-weight:bold;

}

.average{

  color:#facc15;

  font-weight:bold;

}

.bad{

  color:#ef4444;

  font-weight:bold;

}

.dynasty{

  color:#22c55e;

  font-weight:bold;

}

.championship{

  color:#84cc16;

  font-weight:bold;

}

.contender{

  color:#facc15;

  font-weight:bold;

}

.rebuild{

  color:#ef4444;

  font-weight:bold;

}

/* ========================================= */
/* MOBILE */
/* ========================================= */

@media(max-width:768px){

  body{

    padding:10px;

  }

  .dashboard-grid{

    grid-template-columns:
    1fr;

  }

  .nav{

    grid-template-columns:
    1fr 1fr;

  }

}

/* ========================================= */
/* SCROLL BOX */
/* ========================================= */

#rosterList{

  margin-top:20px;

}

#historyNotes{

  margin-top:10px;

}

.briefing-card{

background:
linear-gradient(
145deg,
#172554,
#1e3a8a
);

padding:20px;

border-radius:15px;

margin-top:20px;

border:
1px solid rgba(255,255,255,.08);

}

.briefing-card h3{

margin-bottom:10px;

color:#93c5fd;

}

.briefing-card ul{

padding-left:20px;

line-height:1.8;

}

.player-header{

display:flex;

justify-content:space-between;

align-items:center;

margin-bottom:15px;

}

.player-position{

background:#2563eb;

padding:6px 12px;

border-radius:8px;

font-weight:bold;

}

.rating-grid{

display:grid;

grid-template-columns:repeat(4,1fr);

gap:10px;

margin-bottom:15px;

}

.rating-box{

background:#0f172a;

padding:10px;

border-radius:10px;

text-align:center;

}

.rating-label{

font-size:12px;

color:#94a3b8;

}

.rating-number{

font-size:24px;

font-weight:bold;

}

.player-info{

line-height:1.8;

}

.attribute-section{

margin-top:15px;

}

.attribute-row{

display:grid;

grid-template-columns:
80px 1fr 40px;

gap:10px;

align-items:center;

margin-bottom:8px;

}

.attribute-bar{

background:#0f172a;

height:14px;

border-radius:10px;

overflow:hidden;

}

.attribute-fill{

height:100%;

background:
linear-gradient(
90deg,
#22c55e,
#84cc16
);

}

.attribute-row span{

font-size:12px;

}

</style>

</head>

<body>

<div id="app">

  <h1>⚾ MLB THE SHOW 26 FRANCHISE OS</h1>

  <div class="nav">

    <button onclick="showTab('dashboard')">Dashboard</button>

    <button onclick="showTab('organization')">Organization</button>

    <button onclick="showTab('roster')">Roster Database</button>

    <button onclick="showTab('playerlab')">Player Lab</button>

    <button onclick="showTab('prospectlab')">Prospect Lab</button>

    <button onclick="showTab('tradewarroom')">Trade War Room</button>

    <button onclick="showTab('draftroom')">Draft Room</button>

    <button onclick="showTab('contracts')">Contracts</button>

    <button onclick="showTab('payroll')">Payroll</button>

    <button onclick="showTab('owner')">Owner's Office</button>

    <button onclick="showTab('history')">History</button>

  </div>

  <!-- ===================================== -->
  <!-- DASHBOARD -->
  <!-- ===================================== -->

  <div id="dashboard" class="tab">

    <h2>Executive Dashboard</h2>

    <div class="dashboard-grid">

      <div class="card">
        <div class="card-title">Organization Health</div>
        <div class="card-value" id="orgHealth">--</div>
      </div>

      <div class="card">
        <div class="card-title">Competitive Window</div>
        <div class="card-value" id="competitiveWindow">--</div>
      </div>

      <div class="card">
        <div class="card-title">Owner Approval</div>
        <div class="card-value" id="ownerApproval">--</div>
      </div>

      <div class="card">
        <div class="card-title">Payroll Grade</div>
        <div class="card-value" id="payrollGrade">--</div>
      </div>

      <div class="card">
        <div class="card-title">Farm System Grade</div>
        <div class="card-value" id="farmGrade">--</div>
      </div>

      <div class="card">
        <div class="card-title">Top Prospect</div>
        <div class="card-value" id="topProspect">--</div>
      </div>

    </div>

<h2>Front Office Briefing</h2>

<div class="briefing-card">

<h3>Current Objectives</h3>

<ul>
<li>Review extension candidates</li>
<li>Monitor top prospects</li>
<li>Evaluate trade deadline needs</li>
<li>Track payroll health</li>
</ul>

</div>

<div class="briefing-card">

<h3>Organization Notes</h3>

<textarea
id="gmNotes"
placeholder="Write season notes, trade targets, goals, concerns..."
></textarea>

</div>

  </div>

  <!-- ===================================== -->
  <!-- ORGANIZATION -->
  <!-- ===================================== -->
<div id="organization" class="tab" style="display:none;">

<h2>Organization Evaluation</h2>

<input id="teamWins" placeholder="Wins Last Season">

<input id="teamPayroll" placeholder="Current Payroll">

<input id="farmTop100"
placeholder="Top Prospects Count">

<input id="corePlayers"
placeholder="Core Players Under 30">

<input id="rotationOVR"
placeholder="Average Rotation OVR">

<input id="teamControlYears"
placeholder="Average Core Control Years">

<button onclick="runOrganizationEvaluation()">
Evaluate Organization
</button>

<div id="organizationResults"
class="result"></div>

</div>

  <!-- ===================================== -->
  <!-- ROSTER DATABASE -->
  <!-- ===================================== -->

  <div id="roster" class="tab" style="display:none;">

    <h2>Roster Database</h2>

    <input id="playerName" placeholder="Player Name">
    <input id="playerNumber" placeholder="Number">
    <input id="playerHeight" placeholder="Height (e.g. 6'2)">

<input id="playerWeight" placeholder="Weight">
    <input id="playerPosition" placeholder="Position">
    <input id="secondaryPosition1" placeholder="Secondary Position 1">

<input id="secondaryPosition2" placeholder="Secondary Position 2">

<input id="secondaryPosition3" placeholder="Secondary Position 3">
    <input id="playerAge" placeholder="Age">
    <input id="playerOVR" placeholder="Overall">
    <input id="playerPotential" placeholder="Potential">

    <input id="contactL" placeholder="Contact vs L">
    <input id="contactR" placeholder="Contact vs R">
    <input id="powerL" placeholder="Power vs L">
    <input id="powerR" placeholder="Power vs R">

    <input id="vision" placeholder="Vision">
    <input id="discipline" placeholder="Discipline">

    <input id="fielding" placeholder="Fielding">
    <input id="arm" placeholder="Arm">
    <input id="speed" placeholder="Speed">
    <input id="durability" placeholder="Durability">

    <input id="avg" placeholder="AVG">
    <input id="obp" placeholder="OBP">
    <input id="ops" placeholder="OPS">

    <input id="salary" placeholder="Salary">
    <input id="controlYears" placeholder="Years Control">

    

<input id="batHand" placeholder="Bats (L/R/S)">

<input id="throwHand" placeholder="Throws (L/R)">

<input id="clutch" placeholder="Clutch">

<input id="armAccuracy" placeholder="Arm Accuracy">

<input id="steal" placeholder="Stealing">

<input id="reactionForward" placeholder="Reaction Forward">

<input id="reactionBackward" placeholder="Reaction Backward">

<input id="reactionLeft" placeholder="Reaction Left">

<input id="reactionRight" placeholder="Reaction Right">

<input id="serviceTime" placeholder="Service Time (Years)">

<textarea id="playerNotes"
placeholder="Scouting Notes">
</textarea>

    <button onclick="addPlayer()">
      Add Player
    </button>

    <button onclick="clearRoster()">
Clear Entire Roster
</button>

    <div id="rosterList"></div>

  </div>

  <!-- ===================================== -->
  <!-- PLAYER LAB -->
  <!-- ===================================== -->

  <div id="playerlab" class="tab" style="display:none;">

    <h2>Player Lab</h2>

    <select id="playerSelector"></select>

    <button onclick="evaluateSelectedPlayer()">
      Evaluate Player
    </button>

    <div id="playerResults" class="result"></div>

  </div>

  <!-- ===================================== -->
  <!-- PROSPECT LAB -->
  <!-- ===================================== -->

  <div id="prospectlab" class="tab" style="display:none;">

    <h2>Prospect Lab</h2>

    <input id="prospectName" placeholder="Prospect Name">
    <input id="prospectAge" placeholder="Age">
    <input id="prospectLevel" placeholder="Level">
    <input id="prospectOVR" placeholder="Overall">
    <input id="prospectPotential" placeholder="Potential">
    <input id="prospectProduction" placeholder="Production Score">

    <button onclick="evaluateProspect()">
      Evaluate Prospect
    </button>

    <div id="prospectResults" class="result"></div>

  </div>

  <!-- ===================================== -->
  <!-- TRADE WAR ROOM -->
  <!-- ===================================== -->

  <div id="tradewarroom" class="tab" style="display:none;">

    <h2>Trade War Room</h2>

    <input id="incomingFV" placeholder="Incoming Future Value">
    <input id="outgoingFV" placeholder="Outgoing Future Value">
    <input id="payrollImpact" placeholder="Payroll Impact">

    <button onclick="evaluateTrade()">
      Analyze Trade
    </button>

    <div id="tradeResults" class="result"></div>

  </div>

  <!-- ===================================== -->
  <!-- DRAFT ROOM -->
  <!-- ===================================== -->

  <div id="draftroom" class="tab" style="display:none;">

    <h2>Draft Room</h2>

    <input id="draftPotential" placeholder="Potential">
    <input id="draftContact" placeholder="Contact">
    <input id="draftPower" placeholder="Power">
    <input id="draftDiscipline" placeholder="Discipline">
    <input id="draftDefense" placeholder="Defense">

    <button onclick="evaluateDraft()">
      Grade Prospect
    </button>

    <div id="draftResults" class="result"></div>

  </div>

  <!-- ===================================== -->
  <!-- CONTRACTS -->
  <!-- ===================================== -->

  <div id="contracts" class="tab" style="display:none;">

    <h2>Contracts Department</h2>

    <input id="contractAge" placeholder="Age">
    <input id="contractFV" placeholder="Future Value">
    <input id="contractDemand" placeholder="Contract Demand">

    <button onclick="evaluateContract()">
      Evaluate Contract
    </button>

    <div id="contractResults" class="result"></div>

  </div>

  <!-- ===================================== -->
  <!-- PAYROLL -->
  <!-- ===================================== -->

  <div id="payroll" class="tab" style="display:none;">

    <h2>Payroll Department</h2>

    <input id="currentPayroll" placeholder="Current Payroll">

    <input id="futurePayroll" placeholder="Future Payroll">

    <button onclick="evaluatePayroll()">
      Evaluate Payroll
    </button>

    <div id="payrollResults" class="result"></div>

  </div>

  <!-- ===================================== -->
  <!-- OWNER -->
  <!-- ===================================== -->

  <div id="owner" class="tab" style="display:none;">

    <h2>Owner's Office</h2>

    <input id="wins" placeholder="Wins">
    <input id="development" placeholder="Player Development Grade">
    <input id="farmGradeScore" placeholder="Farm System Grade">
    <input id="payrollEfficiency" placeholder="Payroll Efficiency">

    <button onclick="evaluateOwner()">
      Evaluate GM
    </button>

    <div id="ownerResults" class="result"></div>

  </div>

  <!-- ===================================== -->
  <!-- HISTORY -->
  <!-- ===================================== -->

  <div id="history" class="tab" style="display:none;">

    <h2>Franchise History</h2>

    <textarea
      id="historyNotes"
      placeholder="Championships, Hall of Fame, Best Trades, Retired Numbers, Legends, Team Records..."
    ></textarea>

  </div>

<script>

//////////////////////////////////////////////////////
// MLB THE SHOW 26 FRANCHISE OS
//////////////////////////////////////////////////////

let franchise = {

players: [],

prospects: [],

historyNote: ""

};

//////////////////////////////////////////////////////
// LOAD SAVE
//////////////////////////////////////////////////////

function saveData(){

localStorage.setItem(
"franchiseOS",
JSON.stringify(franchise)
);

}

function loadData(){

const saved =
localStorage.getItem(
"franchiseOS"
);

if(saved){

franchise =
JSON.parse(saved);

}
else{

franchise = {

players: [],

prospects: [],

historyNote: ""

};

}

}


//////////////////////////////////////////////////////
// TAB SYSTEM
//////////////////////////////////////////////////////

function showTab(tabId){

document
.querySelectorAll(".tab")
.forEach(tab=>{

tab.style.display = "none";

});

document
.getElementById(tabId)
.style.display = "block";

}

//////////////////////////////////////////////////////
// PLAYER DATABASE
//////////////////////////////////////////////////////

function convertPotential(potential){

switch(potential.toUpperCase()){

case "A":
return 95;

case "B":
return 85;

case "C":
return 75;

case "D":
return 65;

case "F":
return 50;

default:
return 75;

}

}

function addPlayer(){

const player = {

name: playerName.value,

position: playerPosition.value,

age: Number(playerAge.value),

overall: Number(playerOVR.value),

potential:
convertPotential(playerPotential.value),

potentialGrade:
playerPotential.value.toUpperCase(),

contactL: Number(contactL.value),

contactR: Number(contactR.value),

powerL: Number(powerL.value),

powerR: Number(powerR.value),

vision: Number(vision.value),

discipline: Number(discipline.value),

fielding: Number(fielding.value),

arm: Number(arm.value),

speed: Number(speed.value),

durability: Number(durability.value),

avg: Number(avg.value),

obp: Number(obp.value),

ops: Number(ops.value),

salary: Number(salary.value) * 1000000,

serviceTime: Number(serviceTime.value),

controlYears: Number(controlYears.value),

number: playerNumber.value,

height: playerHeight.value,

weight: playerWeight.value,

bats: batHand.value,

throws: throwHand.value,

secondaryPosition1: secondaryPosition1.value,

secondaryPosition2: secondaryPosition2.value,

secondaryPosition3: secondaryPosition3.value,

clutch: Number(clutch.value),

armAccuracy: Number(armAccuracy.value),

steal: Number(steal.value),

reactionForward: Number(reactionForward.value),

reactionBackward: Number(reactionBackward.value),

reactionLeft: Number(reactionLeft.value),

reactionRight: Number(reactionRight.value),

};

franchise.players.push(player);

saveData();

renderRoster();

refreshPlayerSelector();

updateDashboard();

playerName.value = "";
playerPosition.value = "";
playerAge.value = "";
playerOVR.value = "";
playerPotential.value = "";

contactL.value = "";
contactR.value = "";
powerL.value = "";
powerR.value = "";

vision.value = "";
discipline.value = "";

fielding.value = "";

arm.value = "";
speed.value = "";
durability.value = "";

avg.value = "";
obp.value = "";
ops.value = "";

salary.value = "";
serviceTime.value = "";
controlYears.value = "";

playerNumber.value = "";
playerHeight.value = "";
playerWeight.value = "";

batHand.value = "";
throwHand.value = "";

secondaryPosition1.value = "";
secondaryPosition2.value = "";
secondaryPosition3.value = "";

clutch.value = "";
armAccuracy.value = "";
steal.value = "";

reactionForward.value = "";
reactionBackward.value = "";
reactionLeft.value = "";
reactionRight.value = "";

}

//////////////////////////////////////////////////////
// ROSTER DISPLAY
//////////////////////////////////////////////////////

function renderRoster(){

let html = "";

franchise.players.forEach((player,index)=>{

let fv = calculateFutureValue(player);

let cv = calculateCurrentValue(player);

let contactAverage = Math.round(

((player.contactL || 0) +
(player.contactR || 0))

/ 2

);

let powerAverage = Math.round(

((player.powerL || 0) +
(player.powerR || 0))

/ 2

);

let defenseAverage = Math.round(

((player.fielding || 0) +
(player.arm || 0) +
(player.armAccuracy || 0) +
(player.reactionForward || 0) +
(player.reactionBackward || 0) +
(player.reactionLeft || 0) +
(player.reactionRight || 0))

/ 7

);

let role = "";

if(fv >= 90){
role = "⭐ Franchise Cornerstone";
}
else if(fv >= 80){
role = "✅ Core Star";
}
else if(fv >= 70){
role = "⚾ Starter";
}
else{
role = "🔄 Depth Piece";
}

let salaryInMillions =
(player.salary || 0) / 1000000;

let valueRatio =
fv - (salaryInMillions * 2);

let contractValue = "";

if(valueRatio >= 75){
contractValue = "💎 Team Friendly";
}
else if(valueRatio >= 60){
contractValue = "✅ Fair Contract";
}
else if(valueRatio >= 45){
contractValue = "⚠ Slight Overpay";
}
else{
contractValue = "❌ Negative Asset";
}

html += `

<div class="player-card">

<div class="player-header">

<h3>${player.name}</h3>

<div class="player-position">

${player.position}

</div>

</div>

<div class="rating-grid">

<div class="rating-box">

<div class="rating-label">
OVR
</div>

<div class="rating-number">
${player.overall || 0}
</div>

</div>

<div class="rating-box">

<div class="rating-label">
POT
</div>

<div class="rating-number">
${player.potentialGrade || 0}
</div>

</div>

<div class="rating-box">

<div class="rating-label">
FV
</div>

<div class="rating-number">
${fv}
</div>

</div>

<div class="rating-box">

<div class="rating-label">
CV
</div>

<div class="rating-number">
${cv}
</div>

</div>

</div>

<div class="player-info">

Age: ${player.age || 0}

<br>

#${player.number || ""}

<br>

B/T:
${player.bats || ""}
/
${player.throws || ""}

<br>

${player.height || ""}
 |
${player.weight || ""} lbs

<br>

Contract:
${contractValue}

<br>

Salary:
$${((player.salary || 0) / 1000000).toFixed(1)}M

<br>

Control:
${player.controlYears || 0} yrs

<br>

Service Time:
${player.serviceTime || 0}

<div class="attribute-section">

<div class="attribute-row">

<span>Contact</span>

<div class="attribute-bar">

<div
class="attribute-fill"
style="width:${contactAverage}%">
</div>

</div>

<span>${contactAverage}</span>

</div>

<div class="attribute-row">

<span>Power</span>

<div class="attribute-bar">

<div
class="attribute-fill"
style="width:${powerAverage}%">
</div>

</div>

<span>${powerAverage}</span>

</div>

<div class="attribute-row">

<span>Defense</span>

<div class="attribute-bar">

<div
class="attribute-fill"
style="width:${defenseAverage}%">
</div>

</div>

<span>${defenseAverage}</span>

</div>

<div class="attribute-row">

<span>Speed</span>

<div class="attribute-bar">

<div
class="attribute-fill"
style="width:${player.speed || 0}%">
</div>

</div>

<span>${player.speed || 0}</span>

</div>

</div>

</div>

<button onclick="editPlayer(${index})">
Edit Player
</button>

<button onclick="deletePlayer(${index})">
Delete Player
</button>

</div>

`;

});

rosterList.innerHTML = html;

}

function deletePlayer(index){

franchise.players.splice(index,1);

saveData();

renderRoster();

refreshPlayerSelector();

updateDashboard();

}

function editPlayer(index){

const player = franchise.players[index];

playerName.value = player.name || "";

playerPosition.value = player.position || "";

playerAge.value = player.age || "";

playerOVR.value = player.overall || "";

playerPotential.value = player.potential || "";

contactL.value = player.contactL || "";

contactR.value = player.contactR || "";

powerL.value = player.powerL || "";

powerR.value = player.powerR || "";

vision.value = player.vision || "";

discipline.value = player.discipline || "";

fielding.value = player.fielding || "";

arm.value = player.arm || "";

speed.value = player.speed || "";

durability.value = player.durability || "";

avg.value = player.avg || "";

obp.value = player.obp || "";

ops.value = player.ops || "";

salary.value = player.salary || "";

serviceTime.value = player.serviceTime || "";

controlYears.value = player.controlYears || "";

playerNumber.value = player.number || "";

playerHeight.value = player.height || "";

playerWeight.value = player.weight || "";

batHand.value = player.bats || "";

throwHand.value = player.throws || "";

secondaryPosition1.value =
player.secondaryPosition1 || "";

secondaryPosition2.value =
player.secondaryPosition2 || "";

secondaryPosition3.value =
player.secondaryPosition3 || "";

clutch.value = player.clutch || "";

armAccuracy.value =
player.armAccuracy || "";

steal.value = player.steal || "";

reactionForward.value =
player.reactionForward || "";

reactionBackward.value =
player.reactionBackward || "";

reactionLeft.value =
player.reactionLeft || "";

reactionRight.value =
player.reactionRight || "";

deletePlayer(index);

showTab("roster");

}



//////////////////////////////////////////////////////
// PLAYER SELECTOR
//////////////////////////////////////////////////////

function refreshPlayerSelector(){

playerSelector.innerHTML = "";

franchise.players.forEach((player,index)=>{

playerSelector.innerHTML +=

`

<option value="${index}">
${player.name}
</option>

`;

});

}

//////////////////////////////////////////////////////
// FUTURE VALUE
//////////////////////////////////////////////////////

function calculateFutureValue(player){

let ageScore = 0;

if(player.age <= 23){
ageScore = 100;
}
else if(player.age <= 27){
ageScore = 90;
}
else if(player.age <= 30){
ageScore = 75;
}
else if(player.age <= 33){
ageScore = 60;
}
else{
ageScore = 40;
}

let hittingScore = (

(player.contactL || 0) +
(player.contactR || 0) +
(player.powerL || 0) +
(player.powerR || 0) +
(player.vision || 0) +
(player.discipline || 0) +
(player.clutch || 0)

) / 7;

let defenseScore = (

(player.fielding || 0) +
(player.arm || 0) +
(player.armAccuracy || 0) +
(player.reactionForward || 0) +
(player.reactionBackward || 0) +
(player.reactionLeft || 0) +
(player.reactionRight || 0)

) / 7;

let runningScore = (

(player.speed || 0) +
(player.steal || 0)

) / 2;

let productionScore = (

((player.avg || 0) * 1000) +
((player.obp || 0) * 100) +
((player.ops || 0) * 100) +
((player.war || 0) * 10)

) / 4;

let positionValue = 5;

switch(player.position){

case "C":
positionValue = 10;
break;

case "SS":
positionValue = 10;
break;

case "CF":
positionValue = 9;
break;

case "2B":
positionValue = 8;
break;

case "3B":
positionValue = 8;
break;

case "RF":
positionValue = 7;
break;

case "LF":
positionValue = 6;
break;

case "1B":
positionValue = 5;
break;

case "DH":
positionValue = 4;
break;

}

let fv =

((player.potential || 0) * .25)

+

(ageScore * .20)

+

(hittingScore * .20)

+

(defenseScore * .10)

+

(runningScore * .05)

+

(productionScore * .10)

+

((player.durability || 0) * .05)

+

((player.controlYears || 0) * .05)

+

(positionValue * 2);

if(isNaN(fv)){
return 0;
}

return Math.round(fv);

}

function calculateCurrentValue(player){

let hittingScore = (

(player.contactL || 0) +

(player.contactR || 0) +

(player.powerL || 0) +

(player.powerR || 0) +

(player.vision || 0) +

(player.discipline || 0)

) / 6;

let defenseScore = (

(player.fielding || 0) +

(player.arm || 0) +

(player.armAccuracy || 0) +

(player.reactionForward || 0) +

(player.reactionBackward || 0) +

(player.reactionLeft || 0) +

(player.reactionRight || 0)

) / 7;

let runningScore = (

(player.speed || 0) +

(player.steal || 0)

) / 2;

let productionScore = (

((player.avg || 0) * 1000) +

((player.obp || 0) * 100) +

((player.ops || 0) * 100) +

((player.war || 0) * 10)

) / 4;

let cv =

(hittingScore * .35)

+

(defenseScore * .15)

+

(runningScore * .10)

+

(productionScore * .30)

+

((player.overall || 0) * .10);

return Math.round(cv);

}


//////////////////////////////////////////////////////
// PLAYER LAB
//////////////////////////////////////////////////////

function evaluateSelectedPlayer(){

const player =
franchise.players[
playerSelector.value
];

if(!player){

playerResults.innerHTML =
"No player selected";

return;

}

const fv =
calculateFutureValue(player);

const cv =
calculateCurrentValue(player);

let recommendation = "";

if(fv >= 90){

recommendation =
"⭐ Franchise Cornerstone";

}
else if(fv >= 80){

recommendation =
"✅ Core Star";

}
else if(fv >= 70){

recommendation =
"⚾ Everyday Starter";

}
else if(fv >= 60){

recommendation =
"🔄 Role Player";

}
else{

recommendation =
"📦 Trade Candidate";

}

let extension = "";

if(player.age <= 29 && fv >= 80){

extension =
"✍ EXTEND IMMEDIATELY";

}
else if(player.age <= 32){

extension =
"📋 EXTEND SHORT TERM";

}
else{

extension =
"🚪 LET WALK";

}

let tradeValue = "";

if(fv >= 90){
tradeValue = "Elite Asset";
}
else if(fv >= 80){
tradeValue = "High Value";
}
else if(fv >= 70){
tradeValue = "Solid Asset";
}
else{
tradeValue = "Low Value";
}

let risk = "";

if(player.age <= 26){
risk = "Low";
}
else if(player.age <= 31){
risk = "Medium";
}
else{
risk = "High";
}

let extensionRecommendation = "";

if(
fv >= 90 &&
player.age <= 29 &&
player.controlYears <= 3
){

extensionRecommendation =
"✍ EXTEND IMMEDIATELY";

}
else if(
fv >= 80 &&
player.age <= 30
){

extensionRecommendation =
"✅ PRIORITY EXTENSION";

}
else if(
fv >= 70 &&
player.age <= 32
){

extensionRecommendation =
"📋 MONITOR";

}
else if(
player.age >= 33
){

extensionRecommendation =
"⚠ SHORT TERM ONLY";

}
else{

extensionRecommendation =
"🚪 LET WALK";

}

let contractValue = "";

let salaryInMillions =
(player.salary || 0) / 1000000;

let valueRatio =
fv - (salaryInMillions * 2);

if(valueRatio >= 75){

contractValue =
"💎 Team Friendly";

}
else if(valueRatio >= 60){

contractValue =
"✅ Fair Contract";

}
else if(valueRatio >= 45){

contractValue =
"⚠ Slight Overpay";

}
else{

contractValue =
"❌ Negative Asset";

} 

let assetGrade = "";

if(fv >= 90){
assetGrade = "💎 Untouchable";
}
else if(fv >= 85){
assetGrade = "💰 Premium Asset";
}
else if(fv >= 75){
assetGrade = "✅ Valuable Asset";
}
else if(fv >= 65){
assetGrade = "⚠ Available";
}
else{
assetGrade = "📦 Trade Block";
}

playerResults.innerHTML = `

<h3>${player.name}</h3>

Current Value:
${cv}

<br><br>

Future Value:
${fv}

<br><br>

Role:
${recommendation}

<br><br>

Trade Asset:
${assetGrade}

<br><br>

Trade Value:
${tradeValue}

<br><br>

Risk:
${risk}

<br><br>

Service Time:
${player.serviceTime}

<br><br>

Control Remaining:
${player.controlYears} years

<br><br>

Extension Recommendation:
${extensionRecommendation}

<br><br>

Contract Value:
${contractValue}

<br><br>

Salary:
$${((player.salary || 0) / 1000000).toFixed(1)}M

`;

}

//////////////////////////////////////////////////////
// ORGANIZATION
//////////////////////////////////////////////////////

function runOrganizationEvaluation(){

let score = 0;

const wins =
Number(teamWins.value);

const payroll =
Number(teamPayroll.value);

const prospects =
Number(farmTop100.value);

const youngCore =
Number(corePlayers.value);

const control =
Number(teamControlYears.value);

const rotation =
Number(rotationOVR.value);

////////////////////////////////////////////////
// WINS
////////////////////////////////////////////////

if(wins >= 100){

score += 30;

}
else if(wins >= 90){

score += 25;

}
else if(wins >= 81){

score += 20;

}
else if(wins >= 70){

score += 10;

}
else{

score += 5;

}

////////////////////////////////////////////////
// YOUNG CORE
////////////////////////////////////////////////

score += youngCore * 3;

////////////////////////////////////////////////
// FARM
////////////////////////////////////////////////

score += prospects * 2;

////////////////////////////////////////////////
// TEAM CONTROL
////////////////////////////////////////////////

score += control * 2;

////////////////////////////////////////////////
// ROTATION
////////////////////////////////////////////////

score += rotation / 2;

////////////////////////////////////////////////
// PAYROLL FLEXIBILITY
////////////////////////////////////////////////

if(payroll < 120){

score += 15;

}
else if(payroll < 180){

score += 10;

}
else if(payroll < 240){

score += 5;

}
else{

score += 2;

}

////////////////////////////////////////////////
// RESULT
////////////////////////////////////////////////

let status = "";

if(score >= 90){

status =
"🏆 Dynasty Window";

}
else if(score >= 75){

status =
"🔥 Championship Window";

}
else if(score >= 60){

status =
"⚾ Playoff Contender";

}
else if(score >= 40){

status =
"📈 Emerging Team";

}
else{

status =
"🔨 Rebuild";

}

organizationResults.innerHTML =

`
Organization Score:
${Math.round(score)}

<br><br>

${status}
`;

}

let score = 0;

const wins =
Number(teamWins.value);

const payroll =
Number(teamPayroll.value);

const prospects =
Number(farmTop100.value);

const youngCore =
Number(corePlayers.value);

const control =
Number(teamControlYears.value);

const rotation =
Number(rotationOVR.value);

if(wins >= 100){
score += 30;
}
else if(wins >= 90){
score += 25;
}
else if(wins >= 81){
score += 20;
}
else{
score += 10;
}

score += youngCore * 3;
score += prospects * 2;
score += control * 2;
score += rotation / 2;

if(payroll < 120){
score += 15;
}
else if(payroll < 180){
score += 10;
}
else{
score += 5;
}

let status = "";

if(score >= 90){
status = "🏆 Dynasty Window";
}
else if(score >= 75){
status = "🔥 Championship Window";
}
else if(score >= 60){
status = "⚾ Playoff Contender";
}
else if(score >= 40){
status = "📈 Emerging Team";
}
else{
status = "🔨 Rebuild";
}

organizationResults.innerHTML =

`

Organization Score:
${Math.round(score)}

<br><br>

${status}

`;



//////////////////////////////////////////////////////
// PROSPECT LAB
//////////////////////////////////////////////////////

function evaluateProspect(){

let readiness =

(

Number(prospectOVR.value)

+

Number(prospectPotential.value)

+

Number(prospectProduction.value)

)

/

3;

let eta = "";

if(readiness >= 90){

eta = "MLB Ready";

}
else if(readiness >= 80){

eta = "1 Year";

}
else if(readiness >= 70){

eta = "2 Years";

}
else{

eta = "3+ Years";

}

let bustRisk =

100 -
Number(prospectPotential.value);

let starChance =

Math.round(
Number(prospectPotential.value)
* .85
);

prospectResults.innerHTML =

`

Readiness:
${Math.round(readiness)}%

<br><br>

ETA:
${eta}

<br><br>

Star Probability:
${starChance}%

<br><br>

Bust Risk:
${bustRisk}%

`;

}

//////////////////////////////////////////////////////
// TRADES
//////////////////////////////////////////////////////

function evaluateTrade(){

let score =

Number(incomingFV.value)

-

Number(outgoingFV.value)

+

Number(payrollImpact.value);

let result = "";

if(score >= 15){

result =
"✅ STRONGLY APPROVE";

}
else if(score >= 5){

result =
"✅ APPROVE";

}
else if(score >= -5){

result =
"⚠ REVIEW";

}
else{

result =
"❌ REJECT";

}

tradeResults.innerHTML = result;

}

//////////////////////////////////////////////////////
// DRAFT ROOM
//////////////////////////////////////////////////////

function evaluateDraft(){

let grade =

(

Number(draftPotential.value) * .40

+

Number(draftContact.value) * .20

+

Number(draftPower.value) * .15

+

Number(draftDiscipline.value) * .15

+

Number(draftDefense.value) * .10

);

let tier = "";

if(grade >= 90){

tier = "Generational";

}
else if(grade >= 80){

tier = "Elite Prospect";

}
else if(grade >= 70){

tier = "1st Round Grade";

}
else{

tier = "Development Project";

}

draftResults.innerHTML =

`

Grade:
${Math.round(grade)}

<br><br>

${tier}

`;

}

//////////////////////////////////////////////////////
// CONTRACTS
//////////////////////////////////////////////////////

function evaluateContract(){

const age =
Number(contractAge.value);

const fv =
Number(contractFV.value);

let result = "";

if(age <= 29 && fv >= 80){

result =
"✍ EXTEND IMMEDIATELY";

}
else if(age <= 32){

result =
"📋 SHORT TERM ONLY";

}
else{

result =
"🚪 LET WALK";

}

contractResults.innerHTML =
result;

}

//////////////////////////////////////////////////////
// PAYROLL
//////////////////////////////////////////////////////

function evaluatePayroll(){

const current =
Number(currentPayroll.value);

const future =
Number(futurePayroll.value);

let result = "";

if(current < 150000000){

result =
"A Financial Health";

}
else if(current < 220000000){

result =
"B Financial Health";

}
else{

result =
"C Payroll Risk";

}

payrollResults.innerHTML = result;

}

//////////////////////////////////////////////////////
// OWNER
//////////////////////////////////////////////////////

function evaluateOwner(){

let score =

(Number(wins.value) * .4)

+

(Number(development.value) * .25)

+

(Number(farmGradeScore.value) * .2)

+

(Number(payrollEfficiency.value) * .15);

let result = "";

if(score >= 90){

result =
"A+ Elite Executive";

}
else if(score >= 80){

result =
"A Strong Standing";

}
else if(score >= 70){

result =
"B Secure";

}
else if(score >= 60){

result =
"C Warm Seat";

}
else{

result =
"F Hot Seat";

}

ownerResults.innerHTML =
result;

}

//////////////////////////////////////////////////////
// DASHBOARD
//////////////////////////////////////////////////////

function updateDashboard(){

orgHealth.innerHTML =
franchise.players.length * 5;

competitiveWindow.innerHTML =
franchise.players.length >= 15
? "Playoff Contender"
: "Rebuild";

ownerApproval.innerHTML =
"85%";

payrollGrade.innerHTML =
"A";

farmGrade.innerHTML =
"B+";

topProspect.innerHTML =
franchise.prospects.length
? franchise.prospects[0].name
: "--";

}

//////////////////////////////////////////////////////
// HISTORY SAVE
//////////////////////////////////////////////////////

setInterval(()=>{

if(historyNotes){

franchise.historyNote =
historyNotes.value;

saveData();

}

},2000);

//////////////////////////////////////////////////////
// STARTUP
//////////////////////////////////////////////////////

loadData();

renderRoster();

refreshPlayerSelector();

updateDashboard();

showTab("dashboard");

if(
historyNotes &&
franchise.historyNote
){

historyNotes.value =
franchise.historyNote;

}

function deletePlayer(index){

franchise.players.splice(index,1);

saveData();

renderRoster();

refreshPlayerSelector();

updateDashboard();

}

function clearRoster(){

franchise.players = [];

saveData();

renderRoster();

refreshPlayerSelector();

updateDashboard();

}

</script>

</body>

</html>
