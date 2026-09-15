<!DOCTYPE html>

<html lang="de">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">

<title>Abfahrtstafel</title>

<style>

&#x20; /\* ==========================================================================

&#x20;    Abfahrtstafel Widget

&#x20;    Kompatibilitaet: Chrome 86+, Tizen 6.5+ (Samsung Signage), aufwaertskompatibel

&#x20;    - Kein CSS Grid, kein flex "gap", kein clamp()

&#x20;    - Kein optional chaining, kein fetch() -> XMLHttpRequest

&#x20;    ========================================================================== \*/



&#x20; html, body {

&#x20;   margin: 0;

&#x20;   padding: 0;

&#x20;   width: 100%;

&#x20;   height: 100%;

&#x20;   overflow: hidden;

&#x20;   background: #0b5f7a;

&#x20;   font-family: "Arial", "Helvetica Neue", Helvetica, sans-serif;

&#x20;   -webkit-font-smoothing: antialiased;

&#x20; }



&#x20; \* { box-sizing: border-box; }



&#x20; #board {

&#x20;   width: 100%;

&#x20;   height: 100%;

&#x20;   display: -webkit-box;

&#x20;   display: -webkit-flex;

&#x20;   display: flex;

&#x20;   -webkit-box-orient: vertical;

&#x20;   -webkit-flex-direction: column;

&#x20;   flex-direction: column;

&#x20;   color: #ffffff;

&#x20; }



&#x20; /\* ---------- Header ---------- \*/

&#x20; #board-header {

&#x20;   display: -webkit-box;

&#x20;   display: -webkit-flex;

&#x20;   display: flex;

&#x20;   -webkit-box-align: center;

&#x20;   -webkit-align-items: center;

&#x20;   align-items: center;

&#x20;   background: #0a5872;

&#x20;   padding: calc(1.1vh \* var(--scale, 1)) calc(1.6vh \* var(--scale, 1));

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 auto;

&#x20;   flex: 0 0 auto;

&#x20;   border-bottom: 2px solid rgba(255,255,255,0.08);

&#x20; }



&#x20; #clock-wrap {

&#x20;   width: calc(7.5vh \* var(--scale, 1));

&#x20;   height: calc(7.5vh \* var(--scale, 1));

&#x20;   margin-right: calc(1.6vh \* var(--scale, 1));

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 auto;

&#x20;   flex: 0 0 auto;

&#x20; }



&#x20; #clock-wrap svg { width: 100%; height: 100%; display: block; }



&#x20; #station-name {

&#x20;   margin: 0;

&#x20;   font-size: calc(4.4vh \* var(--scale, 1));

&#x20;   font-weight: 700;

&#x20;   letter-spacing: 0.5px;

&#x20;   white-space: nowrap;

&#x20;   overflow: hidden;

&#x20;   text-overflow: ellipsis;

&#x20; }



&#x20; /\* ---------- Column headers ---------- \*/

&#x20; #col-headers {

&#x20;   display: -webkit-box;

&#x20;   display: -webkit-flex;

&#x20;   display: flex;

&#x20;   -webkit-box-align: center;

&#x20;   -webkit-align-items: center;

&#x20;   align-items: center;

&#x20;   background: #0b6480;

&#x20;   padding: calc(1.0vh \* var(--scale, 1)) calc(1.6vh \* var(--scale, 1));

&#x20;   font-size: calc(1.9vh \* var(--scale, 1));

&#x20;   font-weight: 700;

&#x20;   text-transform: none;

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 auto;

&#x20;   flex: 0 0 auto;

&#x20; }



&#x20; .col-linie   { width: 15%; -webkit-box-flex: 0; -webkit-flex: 0 0 15%; flex: 0 0 15%; }

&#x20; .col-abfahrt { width: 12%; -webkit-box-flex: 0; -webkit-flex: 0 0 12%; flex: 0 0 12%; }

&#x20; .col-gleis   { width: 10%; -webkit-box-flex: 0; -webkit-flex: 0 0 10%; flex: 0 0 10%; }

&#x20; .col-ziel    { -webkit-box-flex: 1; -webkit-flex: 1 1 auto; flex: 1 1 auto; }

&#x20; .col-hinweis { width: 14%; text-align: right; -webkit-box-flex: 0; -webkit-flex: 0 0 14%; flex: 0 0 14%; }



&#x20; /\* ---------- Rows ---------- \*/

&#x20; #rows {

&#x20;   -webkit-box-flex: 1;

&#x20;   -webkit-flex: 1 1 auto;

&#x20;   flex: 1 1 auto;

&#x20;   display: -webkit-box;

&#x20;   display: -webkit-flex;

&#x20;   display: flex;

&#x20;   -webkit-box-orient: vertical;

&#x20;   -webkit-flex-direction: column;

&#x20;   flex-direction: column;

&#x20;   overflow: hidden;

&#x20; }



&#x20; .row {

&#x20;   -webkit-box-flex: 1;

&#x20;   -webkit-flex: 1 1 0%;

&#x20;   flex: 1 1 0%;

&#x20;   display: -webkit-box;

&#x20;   display: -webkit-flex;

&#x20;   display: flex;

&#x20;   -webkit-box-align: center;

&#x20;   -webkit-align-items: center;

&#x20;   align-items: center;

&#x20;   padding: 0 calc(1.6vh \* var(--scale, 1));

&#x20;   border-bottom: 1px solid rgba(255,255,255,0.06);

&#x20;   min-height: 0;

&#x20; }



&#x20; .row-a { background: #0e7396; }

&#x20; .row-b { background: #0a5872; }



&#x20; .cell-linie {

&#x20;   width: 15%;

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 15%;

&#x20;   flex: 0 0 15%;

&#x20;   display: -webkit-box;

&#x20;   display: -webkit-flex;

&#x20;   display: flex;

&#x20;   -webkit-box-align: center;

&#x20;   -webkit-align-items: center;

&#x20;   align-items: center;

&#x20;   min-width: 0;

&#x20; }



&#x20; .icon {

&#x20;   width: calc(2.6vh \* var(--scale, 1));

&#x20;   height: calc(2.6vh \* var(--scale, 1));

&#x20;   margin-right: calc(0.8vh \* var(--scale, 1));

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 auto;

&#x20;   flex: 0 0 auto;

&#x20;   fill: #ffffff;

&#x20;   opacity: 0.9;

&#x20; }



&#x20; .badge {

&#x20;   display: inline-block;

&#x20;   background: #ffffff;

&#x20;   color: #0a5872;

&#x20;   font-weight: 800;

&#x20;   font-size: calc(2.1vh \* var(--scale, 1));

&#x20;   padding: calc(0.35vh \* var(--scale, 1)) calc(0.9vh \* var(--scale, 1));

&#x20;   border-radius: calc(0.4vh \* var(--scale, 1));

&#x20;   white-space: nowrap;

&#x20;   overflow: hidden;

&#x20;   text-overflow: ellipsis;

&#x20;   max-width: 100%;

&#x20;   vertical-align: middle;

&#x20; }



&#x20; .cell-abfahrt {

&#x20;   width: 12%;

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 12%;

&#x20;   flex: 0 0 12%;

&#x20;   font-size: calc(2.4vh \* var(--scale, 1));

&#x20;   font-weight: 600;

&#x20;   white-space: nowrap;

&#x20; }



&#x20; .cell-gleis {

&#x20;   width: 10%;

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 10%;

&#x20;   flex: 0 0 10%;

&#x20;   font-size: calc(2.0vh \* var(--scale, 1));

&#x20;   font-weight: 600;

&#x20;   opacity: 0.85;

&#x20;   white-space: nowrap;

&#x20; }



&#x20; .cell-ziel {

&#x20;   -webkit-box-flex: 1;

&#x20;   -webkit-flex: 1 1 auto;

&#x20;   flex: 1 1 auto;

&#x20;   font-size: calc(2.4vh \* var(--scale, 1));

&#x20;   font-weight: 700;

&#x20;   white-space: nowrap;

&#x20;   overflow: hidden;

&#x20;   text-overflow: ellipsis;

&#x20;   padding-right: calc(1vh \* var(--scale, 1));

&#x20; }



&#x20; .cell-hinweis {

&#x20;   width: 16%;

&#x20;   -webkit-box-flex: 0;

&#x20;   -webkit-flex: 0 0 16%;

&#x20;   flex: 0 0 16%;

&#x20;   text-align: right;

&#x20;   font-size: calc(2.0vh \* var(--scale, 1));

&#x20;   font-weight: 700;

&#x20;   white-space: nowrap;

&#x20; }



&#x20; .delay { color: #ffb84d; }

&#x20; .cancelled { color: #ff6b6b; text-decoration: line-through; }

&#x20; .cancelled-tag { color: #ff6b6b; }



&#x20; /\* ---------- Status / footer ---------- \*/

&#x20; #status-bar {

&#x20;   position: absolute;

&#x20;   right: calc(1vh \* var(--scale, 1));

&#x20;   bottom: calc(0.6vh \* var(--scale, 1));

&#x20;   font-size: calc(1.3vh \* var(--scale, 1));

&#x20;   color: rgba(255,255,255,0.45);

&#x20; }



&#x20; #status-bar.error { color: #ff6b6b; }



&#x20; #empty-msg {

&#x20;   -webkit-box-flex: 1;

&#x20;   -webkit-flex: 1 1 auto;

&#x20;   flex: 1 1 auto;

&#x20;   display: -webkit-box;

&#x20;   display: -webkit-flex;

&#x20;   display: flex;

&#x20;   -webkit-box-align: center;

&#x20;   -webkit-align-items: center;

&#x20;   align-items: center;

&#x20;   -webkit-box-pack: center;

&#x20;   -webkit-justify-content: center;

&#x20;   justify-content: center;

&#x20;   font-size: calc(2.4vh \* var(--scale, 1));

&#x20;   opacity: 0.7;

&#x20;   text-align: center;

&#x20;   padding: 2vh;

&#x20; }

</style>

</head>

<body>

&#x20; <div id="board">

&#x20;   <header id="board-header">

&#x20;     <div id="clock-wrap">

&#x20;       <svg viewBox="0 0 100 100">

&#x20;         <circle cx="50" cy="50" r="47" fill="#ffffff" stroke="#0a5872" stroke-width="2"></circle>

&#x20;         <g id="clock-ticks"></g>

&#x20;         <line id="hand-hour" x1="50" y1="50" x2="50" y2="28" stroke="#0a5872" stroke-width="5" stroke-linecap="round"></line>

&#x20;         <line id="hand-min" x1="50" y1="50" x2="50" y2="16" stroke="#0a5872" stroke-width="3.5" stroke-linecap="round"></line>

&#x20;         <line id="hand-sec" x1="50" y1="58" x2="50" y2="12" stroke="#e2001a" stroke-width="1.5" stroke-linecap="round"></line>

&#x20;         <circle cx="50" cy="50" r="3" fill="#e2001a"></circle>

&#x20;       </svg>

&#x20;     </div>

&#x20;     <h1 id="station-name">\&nbsp;</h1>

&#x20;   </header>



&#x20;   <div id="col-headers">

&#x20;     <div class="col-linie">Linie</div>

&#x20;     <div class="col-abfahrt">Abfahrt</div>

&#x20;     <div class="col-gleis">Gleis</div>

&#x20;     <div class="col-ziel">Richtung / Ziel</div>

&#x20;     <div class="col-hinweis">Hinweis</div>

&#x20;   </div>



&#x20;   <div id="rows"></div>

&#x20; </div>



&#x20; <div id="status-bar"></div>



<script>

(function () {

&#x20; "use strict";



&#x20; /\* ---------------------------------------------------------------------

&#x20;    1. Query-Parameter lesen (ohne URLSearchParams, fuer maximale Kompatibilitaet)

&#x20;    --------------------------------------------------------------------- \*/

&#x20; function getParams() {

&#x20;   var params = {};

&#x20;   var qs = window.location.search.substring(1);

&#x20;   if (!qs) { return params; }

&#x20;   var pairs = qs.split("\&");

&#x20;   for (var i = 0; i < pairs.length; i++) {

&#x20;     var pair = pairs\[i].split("=");

&#x20;     var key = decodeURIComponent(pair\[0] || "");

&#x20;     var val = pair.length > 1 ? decodeURIComponent(pair\[1].replace(/\\+/g, " ")) : "";

&#x20;     if (key) { params\[key] = val; }

&#x20;   }

&#x20;   return params;

&#x20; }



&#x20; var qp = getParams();



&#x20; var CONFIG = {

&#x20;   station:   qp.station || "Sargans",                 // Stationsname, z.B. "Sargans"

&#x20;   id:        qp.id || "",                       // exakte Haltestellen-ID (bevorzugt, falls bekannt)

&#x20;   limit:     parseInt(qp.limit, 10) || 5,        // Anzahl Verbindungen

&#x20;   title:     qp.title || "",                     // Titel ueberschreiben statt API-Stationsname

&#x20;   refresh:   Math.max(parseInt(qp.refresh, 10) || 30, 10), // Sekunden zwischen Abfragen, min. 10

&#x20;   clock:     qp.clock !== "0",                   // Uhr anzeigen, default an

&#x20;   scale:     parseFloat(qp.fontscale) || 2.0,       // Skalierungsfaktor Schrift/Elemente

&#x20;   platform:  qp.platform !== "0",                  // Gleis/Perron anzeigen (Spalte), default an

&#x20;   types:     qp.types || ""                       // z.B. "train,bus,tram,ship,cableway"

&#x20; };



&#x20; if (!CONFIG.station \&\& !CONFIG.id) {

&#x20;   document.getElementById("station-name").textContent = "Kein Bahnhof konfiguriert";

&#x20;   document.getElementById("rows").innerHTML = "";

&#x20;   var emptyDiv = document.createElement("div");

&#x20;   emptyDiv.id = "empty-msg";

&#x20;   emptyDiv.textContent = "Bitte URL-Parameter ?station=Ortsname anhaengen, z.B. ?station=Sargans\&limit=6";

&#x20;   document.getElementById("rows").appendChild(emptyDiv);

&#x20;   return;

&#x20; }



&#x20; document.documentElement.style.setProperty("--scale", String(CONFIG.scale));



&#x20; if (CONFIG.title) {

&#x20;   document.getElementById("station-name").textContent = CONFIG.title;

&#x20; }



&#x20; /\* ---------------------------------------------------------------------

&#x20;    2. Analoge Uhr

&#x20;    --------------------------------------------------------------------- \*/

&#x20; if (!CONFIG.clock) {

&#x20;   document.getElementById("clock-wrap").style.display = "none";

&#x20; } else {

&#x20;   var ticksGroup = document.getElementById("clock-ticks");

&#x20;   for (var t = 0; t < 12; t++) {

&#x20;     var angle = (t \* 30) \* Math.PI / 180;

&#x20;     var x1 = 50 + 40 \* Math.sin(angle);

&#x20;     var y1 = 50 - 40 \* Math.cos(angle);

&#x20;     var x2 = 50 + 45 \* Math.sin(angle);

&#x20;     var y2 = 50 - 45 \* Math.cos(angle);

&#x20;     var tick = document.createElementNS("http://www.w3.org/2000/svg", "line");

&#x20;     tick.setAttribute("x1", x1);

&#x20;     tick.setAttribute("y1", y1);

&#x20;     tick.setAttribute("x2", x2);

&#x20;     tick.setAttribute("y2", y2);

&#x20;     tick.setAttribute("stroke", "#0a5872");

&#x20;     tick.setAttribute("stroke-width", "2");

&#x20;     ticksGroup.appendChild(tick);

&#x20;   }



&#x20;   var handHour = document.getElementById("hand-hour");

&#x20;   var handMin = document.getElementById("hand-min");

&#x20;   var handSec = document.getElementById("hand-sec");



&#x20;   function tickClock() {

&#x20;     var now = new Date();

&#x20;     var h = now.getHours() % 12;

&#x20;     var m = now.getMinutes();

&#x20;     var s = now.getSeconds();

&#x20;     var hourDeg = (h \* 30) + (m \* 0.5);

&#x20;     var minDeg = (m \* 6) + (s \* 0.1);

&#x20;     var secDeg = s \* 6;

&#x20;     handHour.setAttribute("transform", "rotate(" + hourDeg + " 50 50)");

&#x20;     handMin.setAttribute("transform", "rotate(" + minDeg + " 50 50)");

&#x20;     handSec.setAttribute("transform", "rotate(" + secDeg + " 50 50)");

&#x20;   }

&#x20;   tickClock();

&#x20;   setInterval(tickClock, 1000);

&#x20; }



&#x20; /\* ---------------------------------------------------------------------

&#x20;    3. Icons pro Verkehrsmittel

&#x20;    --------------------------------------------------------------------- \*/

&#x20; var ICONS = {

&#x20;   train: '<path d="M7 2C4.24 2 2 3 2 6.5V16c0 1.657 1.343 3 3 3l-1.5 1.5v.5h3l1-1h5l1 1h3v-.5L15 19c1.657 0 3-1.343 3-3V6.5C18 3 16 2 12 2H7zM4.5 7h13v6h-13V7zM6.5 15a1.5 1.5 0 110 3 1.5 1.5 0 010-3zm7 0a1.5 1.5 0 110 3 1.5 1.5 0 010-3z"></path>',

&#x20;   bus:   '<path d="M4 5a2 2 0 012-2h8a2 2 0 012 2v11a1 1 0 01-1 1h-1a1 1 0 01-2 0H8a1 1 0 01-2 0H5a1 1 0 01-1-1V5zm2 1v5h10V6H6zm0 7.5a1 1 0 100 2 1 1 0 000-2zm10 0a1 1 0 100 2 1 1 0 000-2z"></path>',

&#x20;   tram:  '<path d="M6 2h10l2 3v10a2 2 0 01-2 2l1 2H5l1-2a2 2 0 01-2-2V5l2-3zm-1 6v5h12V8H5zm2 7a1 1 0 100 2 1 1 0 000-2zm8 0a1 1 0 100 2 1 1 0 000-2zM8 3l-1 2h10l-1-2H8z"></path>',

&#x20;   ship:  '<path d="M4 11l1-6h10l1 6h1l-2 8-3-1-3 1-3-1-3 1-2-8h3zm2-4l-.6 4h9.2L14 7H6zm-1 9.7l1 .3 3-1 3 1 3-1 1-.3.9-3.7H4.1L5 16.7z"></path>',

&#x20;   cableway: '<path d="M3 5l18-2v2L3 7V5zm2 4h3v9H5V9zm11 0h3v9h-3V9zm-6 1h4v8H9v-8z"></path>',

&#x20;   default: '<path d="M7 2C4.24 2 2 3 2 6.5V16c0 1.657 1.343 3 3 3l-1.5 1.5v.5h3l1-1h5l1 1h3v-.5L15 19c1.657 0 3-1.343 3-3V6.5C18 3 16 2 12 2H7zM4.5 7h13v6h-13V7zM6.5 15a1.5 1.5 0 110 3 1.5 1.5 0 010-3zm7 0a1.5 1.5 0 110 3 1.5 1.5 0 010-3z"></path>'

&#x20; };



&#x20; function iconKeyForCategory(cat) {

&#x20;   if (!cat) { return "default"; }

&#x20;   cat = String(cat).toUpperCase();

&#x20;   if (cat === "B" || cat === "BUS" || cat === "NFB") { return "bus"; }

&#x20;   if (cat === "T" || cat === "TRAM" || cat === "STB") { return "tram"; }

&#x20;   if (cat === "BAT" || cat === "SHIP" || cat === "FAE") { return "ship"; }

&#x20;   if (cat === "PB" || cat === "GB" || cat === "FUN") { return "cableway"; }

&#x20;   return "train";

&#x20; }



&#x20; function makeIcon(cat) {

&#x20;   var key = iconKeyForCategory(cat);

&#x20;   var svg = document.createElementNS("http://www.w3.org/2000/svg", "svg");

&#x20;   svg.setAttribute("class", "icon");

&#x20;   svg.setAttribute("viewBox", "0 0 20 22");

&#x20;   svg.innerHTML = ICONS\[key] || ICONS.default;

&#x20;   return svg;

&#x20; }



&#x20; /\* ---------------------------------------------------------------------

&#x20;    4. Zeitformatierung

&#x20;    --------------------------------------------------------------------- \*/

&#x20; function pad2(n) { return (n < 10 ? "0" : "") + n; }



&#x20; function formatTime(isoString) {

&#x20;   if (!isoString) { return "--:--"; }

&#x20;   var d = new Date(isoString);

&#x20;   if (isNaN(d.getTime())) { return "--:--"; }

&#x20;   return pad2(d.getHours()) + ":" + pad2(d.getMinutes());

&#x20; }



&#x20; function delayMinutes(planned, prognosis) {

&#x20;   if (!planned || !prognosis) { return 0; }

&#x20;   var p1 = new Date(planned).getTime();

&#x20;   var p2 = new Date(prognosis).getTime();

&#x20;   if (isNaN(p1) || isNaN(p2)) { return 0; }

&#x20;   var diff = Math.round((p2 - p1) / 60000);

&#x20;   return diff > 0 ? diff : 0;

&#x20; }



&#x20; /\* ---------------------------------------------------------------------

&#x20;    5. Rendering

&#x20;    --------------------------------------------------------------------- \*/

&#x20; var rowsContainer = document.getElementById("rows");

&#x20; var statusBar = document.getElementById("status-bar");

&#x20; var stationNameEl = document.getElementById("station-name");



&#x20; function setStatus(text, isError) {

&#x20;   statusBar.textContent = text;

&#x20;   statusBar.className = isError ? "error" : "";

&#x20; }



&#x20; function render(entries) {

&#x20;   rowsContainer.innerHTML = "";



&#x20;   if (!entries || entries.length === 0) {

&#x20;     var emptyDiv = document.createElement("div");

&#x20;     emptyDiv.id = "empty-msg";

&#x20;     emptyDiv.textContent = "Keine Verbindungen gefunden.";

&#x20;     rowsContainer.appendChild(emptyDiv);

&#x20;     return;

&#x20;   }



&#x20;   for (var i = 0; i < entries.length; i++) {

&#x20;     var e = entries\[i];

&#x20;     var stop = e.stop || {};

&#x20;     var planned = stop.departure;

&#x20;     var prognosis = (stop.prognosis \&\& stop.prognosis.departure) ? stop.prognosis.departure : null;

&#x20;     var cancelled = !planned \&\& !prognosis;



&#x20;     var row = document.createElement("div");

&#x20;     row.className = "row " + (i % 2 === 0 ? "row-a" : "row-b");



&#x20;     // Linie

&#x20;     var cellLinie = document.createElement("div");

&#x20;     cellLinie.className = "cell-linie";

&#x20;     cellLinie.appendChild(makeIcon(e.category));

&#x20;     var badge = document.createElement("span");

&#x20;     badge.className = "badge";

&#x20;     // Kurze Liniennummern (z.B. "IR13", "S12") komplett anzeigen; lange Zugnummern

&#x20;     // (z.B. internationale ICE/EC-Nummern wie "ICE 279") wuerden die Badge sprengen,

&#x20;     // daher dort nur die Kategorie zeigen, wie auf realen Anzeigetafeln ueblich.

&#x20;     var num = e.number || "";

&#x20;     var lineLabel;

&#x20;     if (num \&\& num.length <= 3) {

&#x20;       lineLabel = (e.category || "") + num;

&#x20;     } else {

&#x20;       lineLabel = e.category || num || "";

&#x20;     }

&#x20;     if (!lineLabel \&\& e.name) { lineLabel = String(e.name).replace(/\\s+/g, "").substring(0, 6); }

&#x20;     badge.textContent = lineLabel || "?";

&#x20;     cellLinie.appendChild(badge);

&#x20;     row.appendChild(cellLinie);



&#x20;     // Abfahrt

&#x20;     var cellAbfahrt = document.createElement("div");

&#x20;     cellAbfahrt.className = "cell-abfahrt";

&#x20;     cellAbfahrt.textContent = cancelled ? "--:--" : formatTime(planned);

&#x20;     row.appendChild(cellAbfahrt);



&#x20;     // Gleis

&#x20;     var cellGleis = document.createElement("div");

&#x20;     cellGleis.className = "cell-gleis";

&#x20;     if (CONFIG.platform \&\& stop.platform) {

&#x20;       cellGleis.textContent = stop.platform;

&#x20;     } else {

&#x20;       cellGleis.textContent = "";

&#x20;     }

&#x20;     row.appendChild(cellGleis);



&#x20;     // Ziel

&#x20;     var cellZiel = document.createElement("div");

&#x20;     cellZiel.className = "cell-ziel";

&#x20;     cellZiel.appendChild(document.createTextNode(e.to || ""));

&#x20;     if (cancelled) { cellZiel.className += " cancelled"; }

&#x20;     row.appendChild(cellZiel);



&#x20;     // Hinweis

&#x20;     var cellHinweis = document.createElement("div");

&#x20;     cellHinweis.className = "cell-hinweis";

&#x20;     if (cancelled) {

&#x20;       cellHinweis.className += " cancelled-tag";

&#x20;       cellHinweis.textContent = "Ausfall";

&#x20;     } else {

&#x20;       var delay = delayMinutes(planned, prognosis);

&#x20;       if (delay > 0) {

&#x20;         cellHinweis.className += " delay";

&#x20;         cellHinweis.textContent = "+" + delay + "'";

&#x20;       } else {

&#x20;         cellHinweis.textContent = "";

&#x20;       }

&#x20;     }

&#x20;     row.appendChild(cellHinweis);



&#x20;     rowsContainer.appendChild(row);

&#x20;   }

&#x20; }



&#x20; /\* ---------------------------------------------------------------------

&#x20;    6. Datenabruf (XMLHttpRequest statt fetch fuer max. Kompatibilitaet)

&#x20;    --------------------------------------------------------------------- \*/

&#x20; var API\_BASE = "https://transport.opendata.ch/v1/stationboard";

&#x20; var consecutiveErrors = 0;



&#x20; function buildUrl() {

&#x20;   var url = API\_BASE + "?limit=" + encodeURIComponent(CONFIG.limit);

&#x20;   if (CONFIG.id) {

&#x20;     url += "\&id=" + encodeURIComponent(CONFIG.id);

&#x20;   } else {

&#x20;     url += "\&station=" + encodeURIComponent(CONFIG.station);

&#x20;   }

&#x20;   if (CONFIG.types) {

&#x20;     var typesList = CONFIG.types.split(",");

&#x20;     for (var i = 0; i < typesList.length; i++) {

&#x20;       var tt = typesList\[i].replace(/^\\s+|\\s+$/g, "");

&#x20;       if (tt) { url += "\&transportations\[]=" + encodeURIComponent(tt); }

&#x20;     }

&#x20;   }

&#x20;   return url;

&#x20; }



&#x20; function loadData() {

&#x20;   var xhr = new XMLHttpRequest();

&#x20;   xhr.open("GET", buildUrl(), true);

&#x20;   xhr.timeout = 15000;



&#x20;   xhr.onreadystatechange = function () {

&#x20;     if (xhr.readyState !== 4) { return; }



&#x20;     if (xhr.status >= 200 \&\& xhr.status < 300) {

&#x20;       var data;

&#x20;       try {

&#x20;         data = JSON.parse(xhr.responseText);

&#x20;       } catch (parseErr) {

&#x20;         handleError("Antwort konnte nicht gelesen werden");

&#x20;         return;

&#x20;       }



&#x20;       if (!CONFIG.title) {

&#x20;         var firstEntry = (data.stationboard \&\& data.stationboard\[0]) || null;

&#x20;         var nameFromApi = firstEntry \&\& firstEntry.stop \&\& firstEntry.stop.station

&#x20;           ? firstEntry.stop.station.name

&#x20;           : (data.station ? data.station.name : CONFIG.station || CONFIG.id);

&#x20;         if (nameFromApi) { stationNameEl.textContent = nameFromApi; }

&#x20;         else if (CONFIG.station) { stationNameEl.textContent = CONFIG.station; }

&#x20;       }



&#x20;       render(data.stationboard || \[]);

&#x20;       consecutiveErrors = 0;

&#x20;       var now = new Date();

&#x20;       setStatus("Aktualisiert " + pad2(now.getHours()) + ":" + pad2(now.getMinutes()) + ":" + pad2(now.getSeconds()), false);

&#x20;     } else {

&#x20;       handleError("Fehler beim Laden (HTTP " + xhr.status + ")");

&#x20;     }

&#x20;   };



&#x20;   xhr.ontimeout = function () { handleError("Zeitueberschreitung bei der Abfrage"); };

&#x20;   xhr.onerror = function () { handleError("Verbindungsfehler"); };



&#x20;   xhr.send();

&#x20; }



&#x20; function handleError(msg) {

&#x20;   consecutiveErrors++;

&#x20;   setStatus(msg + " - naechster Versuch in " + CONFIG.refresh + "s", true);

&#x20;   // Bestehende Tafel bleibt sichtbar (kein Leeren bei kurzzeitigen Netzwerkfehlern),

&#x20;   // nur wenn seit Start noch nie Daten geladen wurden, zeigen wir eine Meldung.

&#x20;   if (rowsContainer.children.length === 0) {

&#x20;     render(null);

&#x20;   }

&#x20; }



&#x20; loadData();

&#x20; setInterval(loadData, CONFIG.refresh \* 1000);



})();

</script>

</body>

</html>

