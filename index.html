<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ผู้ช่วยนักบัญชี v2.1</title>
<link rel="apple-touch-icon" href="icon.png">
<link rel="icon" type="image/png" href="icon.png">
<style>
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:-apple-system,'Sarabun',sans-serif;background:#fffbeb;color:#44403c;padding-bottom:30px}
  header{background:#fbbf24;color:#78350f;padding:14px 18px}
  header h1{font-size:18px}
  header .sub{font-size:12px;opacity:.85;margin-top:2px}
  nav{display:flex;background:#fff;border-bottom:1px solid #fde68a;overflow-x:auto}
  nav button{flex:1;min-width:54px;padding:12px 3px;border:none;background:none;font-size:11px;cursor:pointer;color:#a16207;border-bottom:2px solid transparent;white-space:nowrap}
  nav button.active{color:#f59e0b;border-bottom-color:#f59e0b;font-weight:600}
  main{padding:16px;max-width:720px;margin:0 auto}
  .tab{display:none}.tab.active{display:block}
  .card{background:#fff;border-radius:12px;padding:14px;margin-bottom:12px;box-shadow:0 1px 3px rgba(180,83,9,.08)}
  .card h3{font-size:14px;color:#b45309;margin-bottom:10px;display:flex;justify-content:space-between;align-items:center;gap:8px;flex-wrap:wrap}
  .row{display:flex;justify-content:space-between;align-items:center;padding:7px 0;font-size:14px;border-bottom:1px dashed #fef3c7;gap:8px}
  .row:last-child{border-bottom:none}
  .pos{color:#059669}.neg{color:#dc2626}.warn{color:#d97706}
  .big{font-size:22px;font-weight:700}
  .chat-box{background:#fff;border-radius:12px;height:340px;overflow-y:auto;padding:12px;margin-bottom:10px;border:1px solid #fde68a}
  .msg{margin-bottom:8px;padding:8px 12px;border-radius:12px;font-size:14px;max-width:85%;line-height:1.5}
  .msg.user{background:#f59e0b;color:#fff;margin-left:auto}
  .msg.bot{background:#fef3c7;color:#44403c}
  .input-row{display:flex;gap:8px}
  .input-row input{flex:1;padding:12px;border:1px solid #fde68a;border-radius:10px;font-size:14px;background:#fff}
  .input-row button{padding:12px 18px;background:#f59e0b;color:#fff;border:none;border-radius:10px;font-size:14px;cursor:pointer}
  .chip{display:inline-block;background:#fef3c7;color:#b45309;border-radius:999px;padding:4px 10px;font-size:12px;margin:2px;cursor:pointer}
  .btn-sm{padding:6px 12px;font-size:12px;border:none;border-radius:8px;cursor:pointer;background:#f59e0b;color:#fff}
  .btn-sm.gray{background:#fde68a;color:#78350f}
  .btn-sm.red{background:#fee2e2;color:#dc2626}
  .btn-sm.green{background:#d1fae5;color:#059669}
  .progress{height:10px;background:#fef3c7;border-radius:999px;overflow:hidden;margin:8px 0}
  .progress > div{height:100%;background:#f59e0b;transition:width .3s}
  .progress > div.warn{background:#d97706}
  .progress > div.over{background:#dc2626}
  .progress > div.green{background:#059669}
  .item{background:#fffbeb;border-radius:10px;padding:10px;margin-bottom:8px}
  .badge{display:inline-block;padding:2px 8px;border-radius:999px;font-size:11px}
  .badge.done{background:#d1fae5;color:#059669}
  .badge.due{background:#fef3c7;color:#d97706}
  .badge.over{background:#fee2e2;color:#dc2626}
  small{color:#a16207}
  .stat{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin:10px 0}
  .stat-box{background:#fef3c7;border-radius:10px;padding:12px;text-align:center}
  .stat-box .num{font-size:18px;font-weight:700;color:#b45309}
  .stat-box .lbl{font-size:11px;color:#a16207;margin-top:2px}
  .card-item{background:#fffbeb;border-radius:10px;padding:12px;margin-bottom:10px;border-left:4px solid #f59e0b}
  .card-item.urgent{border-left-color:#dc2626;background:#fef2f2}
  .card-item.soon{border-left-color:#d97706;background:#fffbeb}
  .card-item.safe{border-left-color:#059669;background:#f0fdf4}
  .budget-item{background:#fffbeb;border-radius:10px;padding:12px;margin-bottom:10px}
  .budget-item.over{background:#fef2f2;border-left:4px solid #dc2626}
  .budget-item.warn{background:#fffbeb;border-left:4px solid #d97706}
  .budget-item.ok{background:#f0fdf4;border-left:4px solid #059669}
  .wish-item{background:#fffbeb;border-radius:10px;padding:12px;margin-bottom:10px;border-left:4px solid #a78bfa}
  .wish-item.can-buy{border-left-color:#059669;background:#f0fdf4}
  .wish-item.cant-buy{border-left-color:#dc2626;background:#fef2f2}
  .wish-item.travel{border-left-color:#0891b2;background:#ecfeff}
  .wish-item.wishlist{border-left-color:#a78bfa;background:#f5f3ff}
  .month-select{display:flex;gap:8px;align-items:center;margin-bottom:12px;flex-wrap:wrap}
  .month-select select{padding:8px 12px;border:1px solid #fde68a;border-radius:8px;font-size:14px;background:#fff}
  .chart-container{position:relative;width:100%;max-width:320px;margin:0 auto}
  .legend{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px;justify-content:center}
  .legend-item{display:flex;align-items:center;gap:4px;font-size:12px}
  .legend-dot{width:12px;height:12px;border-radius:3px}
  .bar-chart{display:flex;gap:6px;align-items:flex-end;height:160px;margin-top:12px;padding:0 4px}
  .bar-col{flex:1;display:flex;flex-direction:column;align-items:center;gap:4px}
  .bar{width:100%;max-width:32px;border-radius:4px 4px 0 0;min-height:2px;transition:height .3s}
  .bar-label{font-size:10px;color:#a16207;text-align:center}
</style>
</head>
<body>
<header>
  <h1>🧾 ผู้ช่วยนักบัญชี v2.1</h1>
  <div class="sub" id="cycleLabel">รอบเดือน: —</div>
</header>
<nav>
  <button data-tab="chat" class="active">แชท</button>
  <button data-tab="dash">แดชบอร์ด</button>
  <button data-tab="report">รายงาน</button>
  <button data-tab="budget">งบ</button>
  <button data-tab="wish">Wishlist</button>
  <button data-tab="cards">บัตร</button>
  <button data-tab="install">ผ่อน</button>
  <button data-tab="share">แชร์</button>
  <button data-tab="history">ประวัติ</button>
  <button data-tab="settings">ตั้งค่า</button>
</nav>
<main>

<section id="tab-chat" class="tab active">
  <div class="chat-box" id="chatBox"></div>
  <div class="input-row">
    <input id="chatInput" placeholder="เช่น ข้าวเที่ยง 80 cash" autocomplete="off">
    <button onclick="sendChat()">ส่ง</button>
  </div>
  <div class="card" style="margin-top:12px">
    <h3>ตัวอย่าง (คลิกเพื่อเติม)</h3>
    <span class="chip" onclick="fill('ข้าวเที่ยง 80 cash')">ข้าวเที่ยง 80 cash</span>
    <span class="chip" onclick="fill('Shopee 1200 spaylater')">Shopee 1200 spaylater</span>
    <span class="chip" onclick="fill('สอนพิเศษ 500')">สอนพิเศษ 500</span>
    <span class="chip" onclick="fill('เงินเดือนออก')">เงินเดือนออก</span>
    <span class="chip" onclick="fill('รองเท้า 4500 ซื้อได้ไหม')">รองเท้า 4500 ซื้อได้ไหม</span>
  </div>
</section>

<section id="tab-dash" class="tab">
  <div class="card">
    <h3>สรุปรอบเดือน</h3>
    <div class="row"><span>รายรับจริง</span><span class="pos big" id="d-income">—</span></div>
    <div class="row"><span>รายจ่าย (รวม fixed)</span><span class="neg" id="d-expense">—</span></div>
    <div class="row"><span>โอน/ให้แม่</span><span id="d-transfer">—</span></div>
    <div class="row"><span>ออม (แชร์)</span><span id="d-save">—</span></div>
    <div class="row"><span><b>เงินเหลือ</b></span><span class="big" id="d-left">—</span></div>
  </div>
  <div class="card"><h3>หมวดที่ใช้เยอะสุด</h3><div id="d-topcat">—</div></div>
  <div class="card"><h3>งบที่ใกล้เต็ม/เกิน</h3><div id="d-budget-alert">—</div></div>
  <div class="card"><h3>ยอดผ่อนค้าง (PayLater)</h3><div id="d-bnpl">—</div></div>
</section>

<section id="tab-report" class="tab">
  <div class="card">
    <h3>รายงานรายเดือน</h3>
    <div class="month-select">
      <label style="font-size:13px">เลือกเดือน:</label>
      <select id="monthSelect" onchange="renderReport()"></select>
    </div>
    <div class="stat">
      <div class="stat-box"><div class="num" id="r-income">—</div><div class="lbl">รายรับ</div></div>
      <div class="stat-box"><div class="num" id="r-expense">—</div><div class="lbl">รายจ่าย</div></div>
      <div class="stat-box"><div class="num" id="r-left">—</div><div class="lbl">เหลือ</div></div>
      <div class="stat-box"><div class="num" id="r-top">—</div><div class="lbl">หมวดเยอะสุด</div></div>
    </div>
  </div>
  <div class="card">
    <h3>สัดส่วนรายจ่าย (วงกลม)</h3>
    <div class="chart-container">
      <canvas id="pieChart" width="300" height="300"></canvas>
    </div>
    <div class="legend" id="pieLegend"></div>
  </div>
  <div class="card">
    <h3>รายรับ vs รายจ่าย 6 เดือนย้อนหลัง</h3>
    <div class="bar-chart" id="barChart"></div>
    <div class="legend" style="margin-top:8px">
      <div class="legend-item"><div class="legend-dot" style="background:#059669"></div>รายรับ</div>
      <div class="legend-item"><div class="legend-dot" style="background:#dc2626"></div>รายจ่าย</div>
    </div>
  </div>
  <div class="card">
    <h3>รายละเอียดหมวด (เดือนที่เลือก)</h3>
    <div id="r-catlist">—</div>
  </div>
</section>

<section id="tab-budget" class="tab">
  <div class="card">
    <h3>ภาพรวมงบประมาณ</h3>
    <div class="stat">
      <div class="stat-box"><div class="num" id="b-total">—</div><div class="lbl">งบทั้งหมด</div></div>
      <div class="stat-box"><div class="num" id="b-used">—</div><div class="lbl">ใช้ไปแล้ว</div></div>
      <div class="stat-box"><div class="num" id="b-left">—</div><div class="lbl">เหลือ</div></div>
      <div class="stat-box"><div class="num" id="b-pct">—</div><div class="lbl">% ใช้ไป</div></div>
    </div>
    <button class="btn-sm green" style="width:100%;margin-top:8px" onclick="addBudget()">+ เพิ่มหมวดงบ</button>
  </div>
  <div id="budgetList">—</div>
</section>

<section id="tab-wish" class="tab">
  <div class="card">
    <h3>Wishlist & แผนเที่ยว <button class="btn-sm green" onclick="addWish()">+ เพิ่มรายการ</button></h3>
    <div style="font-size:12px;color:#6b7280;margin-bottom:8px">ระบบจะบอกว่าซื้อได้ไหม และถ้ายังไม่พอ ต้องรออีกกี่เดือน</div>
    <div id="wishList">—</div>
  </div>
</section>

<section id="tab-cards" class="tab">
  <div class="card">
    <h3>ยอดหนี้บัตรทั้งหมด</h3>
    <div class="stat">
      <div class="stat-box"><div class="num" id="c-total">—</div><div class="lbl">ยอดรวมที่ต้องจ่าย</div></div>
      <div class="stat-box"><div class="num" id="c-urgent">—</div><div class="lbl">ใกล้ถึงกำหนด (≤7 วัน)</div></div>
    </div>
  </div>
  <div id="cardsList">—</div>
</section>

<section id="tab-install" class="tab">
  <div class="card">
    <h3>รายการผ่อนทั้งหมด <button class="btn-sm" onclick="openAdd()">+ เพิ่มรายการผ่อน</button></h3>
    <div id="installList">—</div>
  </div>
</section>

<section id="tab-share" class="tab">
  <div class="card">
    <h3>แชร์วง — ความคืบหน้า</h3>
    <div class="stat">
      <div class="stat-box"><div class="num" id="sh-paid">—</div><div class="lbl">ส่งแล้ว (บาท)</div></div>
      <div class="stat-box"><div class="num" id="sh-rounds">—</div><div class="lbl">งวดที่ส่งแล้ว</div></div>
      <div class="stat-box"><div class="num" id="sh-interest">—</div><div class="lbl">ดอกสะสม (บาท)</div></div>
      <div class="stat-box"><div class="num" id="sh-remain">—</div><div class="lbl">เหลืออีก (งวด)</div></div>
    </div>
    <div class="progress"><div id="sh-bar" style="width:0%"></div></div>
    <div style="text-align:center;font-size:13px;color:#6b7280" id="sh-pct">0% ของ 100,000 ฿</div>
    <button class="btn-sm green" style="margin-top:12px;width:100%" onclick="openShareAdd()">+ บันทึกงวดใหม่</button>
  </div>
  <div class="card">
    <h3>ประวัติการส่งงวด <span style="font-size:11px;color:#6b7280;font-weight:400" id="sh-count"></span></h3>
    <div id="shareHistory">—</div>
  </div>
</section>

<section id="tab-history" class="tab">
  <div class="card"><h3>รายการทั้งหมด</h3><div id="historyList">—</div></div>
</section>

<section id="tab-settings" class="tab">
  <div class="card">
    <h3>รายรับ</h3>
    <div class="row"><span>เงินเดือน</span><input id="s-salary" type="number" style="width:110px"></div>
    <div class="row"><span>หัก ปกส.</span><input id="s-ss" type="number" style="width:110px"></div>
    <div class="row"><span>หัก PVD</span><input id="s-pvd" type="number" style="width:110px"></div>
    <button class="btn-sm" style="margin-top:10px" onclick="saveSettings()">บันทึก</button>
  </div>
  <div class="card">
    <h3>ข้อมูล</h3>
    <button class="btn-sm green" onclick="exportJSON()">📤 Export</button>
    <button class="btn-sm red" style="margin-left:6px" onclick="clearAll()">🗑️ ล้างทั้งหมด</button>
  </div>
</section>

</main>

<script>
function buildSeed(){
  var rounds=[]; var start=new Date(2025,8,5);
  for(var i=0;i<30;i++){ var d=new Date(start); d.setDate(d.getDate()+i*15); rounds.push({date:d.toISOString(),amount:2000,interest:0}); }
  if(rounds.length>0) rounds[rounds.length-1].interest=18485;
  return {
    profile:{salary:25000,ss:750,pvd:500},
    budgets:[
      {category:"อาหาร",limit:6000},
      {category:"เดินทาง",limit:2000},
      {category:"ช้อปปิ้ง",limit:3000},
      {category:"บันเทิง",limit:1000},
      {category:"สาธารณูปโภค",limit:1000},
      {category:"สุขภาพ",limit:500}
    ],
    cards:[
      {id:"bay_first",name:"BAY First Choice",statementDay:15,dueDay:5,type:"credit",manualBalance:0},
      {id:"bay_now",name:"BAY Now",statementDay:12,dueDay:2,type:"credit",manualBalance:0},
      {id:"cardx",name:"Card X",statementDay:16,dueDay:6,type:"credit",manualBalance:0},
      {id:"cardx_flex",name:"Card X Flex",statementDay:null,dueDay:2,type:"installment",manualBalance:0},
      {id:"spaylater",name:"S-PayLater",statementDay:null,dueDay:null,type:"bnpl",manualBalance:0}
    ],
    fixedCosts:[
      {name:"ค่าเช่า",amount:5700,category:"ที่อยู่อาศัย"},
      {name:"Internet",amount:200,category:"สาธารณูปโภค"},
      {name:"Netflix",amount:23,category:"บันเทิง"},
      {name:"YouTube Premium",amount:179,category:"บันเทิง"},
      {name:"iCloud",amount:99,category:"ดิจิทัล"},
      {name:"Gmail",amount:69,category:"ดิจิทัล"},
      {name:"AIS Play Asian",amount:99,category:"บันเทิง"},
      {name:"ให้แม่",amount:4000,category:"โอน/ให้แม่",type:"transfer"}
    ],
    installments:[
      {name:"iPhone",total:36,paid:2,monthly:1044,nextDate:"2025-12-01",cardId:"Card X Flex"},
      {name:"Keyboard",total:3,paid:1,monthly:500,nextDate:"2025-12-01",cardId:"S-PayLater"},
      {name:"หนังสือ เล่ม 1",total:5,paid:0,monthly:82.8,nextDate:"2025-12-01",cardId:"S-PayLater"},
      {name:"หนังสือ เล่ม 2",total:5,paid:1,monthly:88.6,nextDate:"2025-12-01",cardId:"S-PayLater"},
      {name:"เสื้อผ้า (379)",total:3,paid:1,monthly:126.33,nextDate:"2025-12-01",cardId:"S-PayLater"},
      {name:"เสื้อผ้า (221)",total:3,paid:1,monthly:73.67,nextDate:"2025-12-01",cardId:"S-PayLater"}
    ],
    share:{principal:100000,totalRounds:50,rounds:rounds},
    wishlist:[
      {id:"w1",name:"รองเท้า",price:4500,type:"wishlist",priority:"กลาง",saved:0,monthlyPlan:0,targetDate:""},
      {id:"w2",name:"เที่ยวเชียงใหม่",price:15000,type:"travel",priority:"สูง",saved:0,monthlyPlan:1500,targetDate:""}
    ],
    transactions:[]
  };
}
var KEY="acct_v21";
function loadDB(){ try{var s=localStorage.getItem(KEY); if(s) return JSON.parse(s);}catch(e){} return buildSeed(); }
function saveDB(){ try{localStorage.setItem(KEY,JSON.stringify(DB));}catch(e){} }
var DB=loadDB(); saveDB();

var CARD_ALIASES={"spaylater":"S-PayLater","shopee":"S-PayLater","flex":"Card X Flex","cardx":"Card X","bay first":"BAY First Choice","first choice":"BAY First Choice","bay now":"BAY Now","krungsri":"BAY Now","now":"BAY Now"};
var ACCT_ALIASES={"cash":"เงินสด","เงินสด":"เงินสด","kbank":"KBank","k+":"KBank","scb":"SCB","make":"Make"};
var CAT_KEYWORDS={
  "อาหาร":["ข้าว","กาแฟ","ชา","น้ำ","ขนม","อาหาร","หมูกระทะ","kfc","mk"],
  "เดินทาง":["bts","mrt","taxi","วิน","น้ำมัน","grab","รถเมล์","bolt"],
  "ช้อปปิ้ง":["shopee","lazada","เสื้อ","กางเกง","รองเท้า","กระเป๋า","หนังสือ"],
  "สาธารณูปโภค":["ค่าไฟ","ค่าน้ำ","internet","เน็ต","ais","true","dtac"],
  "บันเทิง":["netflix","youtube","หนัง","เกม"],
  "สุขภาพ":["ยา","หมอ","โรงพยาบาล","ฟิตเนส"]
};

function parseMessage(text){
  var raw=text.trim(); var t=raw.toLowerCase();
  if(/^(เงินเดือนออก|รับเงินเดือน)$/.test(t)) return {action:"payday"};
  if(/(ซื้อได้ไหม|ซื้อได้มั้ย|ควรซื้อ)/.test(t)) return {action:"canbuy",raw:raw};
  if(/(สอนพิเศษ|แฟนให้|รายรับ)/.test(t)){
    var m0=t.match(/([\d,]+(?:\.\d+)?)/);
    if(!m0) return {error:"ไม่พบจำนวนเงิน"};
    return {action:"income",amount:parseFloat(m0[1].replace(/,/g,"")),desc:raw.replace(m0[0],"").trim()||"รายรับพิเศษ"};
  }
  var amt=t.match(/([\d,]+(?:\.\d+)?)/);
  if(!amt) return {error:"ไม่พบจำนวนเงิน"};
  var amount=parseFloat(amt[1].replace(/,/g,""));
  var channel="เงินสด";
  for(var a in CARD_ALIASES){ if(t.indexOf(a)!==-1){ channel=CARD_ALIASES[a]; break; } }
  if(channel==="เงินสด"){ for(var b in ACCT_ALIASES){ if(t.indexOf(b)!==-1){ channel=ACCT_ALIASES[b]; break; } } }
  var category="อื่นๆ";
  for(var c in CAT_KEYWORDS){
    var arr=CAT_KEYWORDS[c];
    for(var k=0;k<arr.length;k++){ if(t.indexOf(arr[k])!==-1){ category=c; break; } }
    if(category!=="อื่นๆ") break;
  }
  var desc=raw.replace(amt[0],"").replace(/\s+/g," ").trim();
  return {action:"tx",description:desc||"ไม่ระบุ",amount:amount,category:category,channel:channel,date:new Date().toISOString()};
}

function monthRange(d){ d=d||new Date(); return [new Date(d.getFullYear(),d.getMonth(),1),new Date(d.getFullYear(),d.getMonth()+1,0,23,59,59)]; }
function inMonth(iso){ var r=monthRange(); var t=new Date(iso); return t>=r[0]&&t<=r[1]; }
function inMonthOf(iso,y,m){ var s=new Date(y,m,1), e=new Date(y,m+1,0,23,59,59); var t=new Date(iso); return t>=s&&t<=e; }
function fmt(n){ return Number(n||0).toLocaleString("th-TH",{maximumFractionDigits:2}); }
function fmtDate(iso){ if(!iso) return "—"; return new Date(iso).toLocaleDateString("th-TH",{day:"numeric",month:"short",year:"numeric"}); }

function calcDashboard(){
  var tx=DB.transactions.filter(function(x){return inMonth(x.date);});
  var salaryNet=DB.profile.salary-DB.profile.ss-DB.profile.pvd;
  var extra=tx.filter(function(x){return x.type==="income";}).reduce(function(a,b){return a+b.amount;},0);
  var income=salaryNet+extra;
  var exp=tx.filter(function(x){return x.type==="expense"&&x.category!=="โอน/ให้แม่";}).reduce(function(a,b){return a+b.amount;},0);
  exp+=DB.fixedCosts.filter(function(f){return f.type!=="transfer";}).reduce(function(a,b){return a+b.amount;},0);
  var transfer=DB.fixedCosts.filter(function(f){return f.type==="transfer";}).reduce(function(a,b){return a+b.amount;},0);
  var saveAmt=DB.share.rounds.filter(function(r){return inMonth(r.date);}).reduce(function(a,b){return a+(b.amount||0);},0);
  var left=income-exp-transfer-saveAmt;
  var catMap={};
  tx.forEach(function(x){if(x.type==="expense")catMap[x.category]=(catMap[x.category]||0)+x.amount;});
  DB.fixedCosts.forEach(function(f){catMap[f.category]=(catMap[f.category]||0)+f.amount;});
  var top=null,tv=-1; for(var c in catMap){ if(catMap[c]>tv){tv=catMap[c];top=[c,catMap[c]];} }
  return {income:income,expenses:exp,transfer:transfer,saveAmt:saveAmt,left:left,catMap:catMap,top:top};
}

function bnplTotal(){
  var t=0;
  DB.installments.forEach(function(it){ if(it.paid<it.total) t+=(it.total-it.paid)*it.monthly; });
  return t;
}

function bubble(text,who){
  who=who||"bot";
  var box=document.getElementById("chatBox");
  var d=document.createElement("div"); d.className="msg "+who; d.innerHTML=text;
  box.appendChild(d); box.scrollTop=box.scrollHeight;
}
function fill(t){ document.getElementById("chatInput").value=t; document.getElementById("chatInput").focus(); }

function sendChat(){
  var inp=document.getElementById("chatInput"); var text=inp.value.trim(); if(!text) return;
  bubble(text,"user"); inp.value="";
  var r=parseMessage(text);
  if(r.error){ bubble("❌ "+r.error); return; }
  if(r.action==="payday"){
    var c=calcDashboard();
    bubble("💰 <b>เงินเดือนออก!</b><br>รายรับสุทธิ: "+fmt(c.income)+" ฿<br>รายจ่าย+โอน+ออม: "+fmt(c.expenses+c.transfer+c.saveAmt)+" ฿<br>เหลือ: <b>"+fmt(c.left)+" ฿</b>");
    return;
  }
  if(r.action==="canbuy"){
    var m=r.raw.match(/([\d,]+(?:\.\d+)?)/); var price=m?parseFloat(m[1].replace(/,/g,"")):0;
    if(!price){ bubble("ระบุราคาด้วยครับ"); return; }
    var cc=calcDashboard(); var bn=bnplTotal();
    var v,rs=[];
    if(cc.left-price-bn<0){ v="🔴 ยังไม่แนะนำ"; rs.push("เหลือ "+fmt(cc.left)+" ฿ ไม่พอ"); if(bn) rs.push("มี PayLater ค้าง "+fmt(bn)+" ฿"); }
    else if(cc.left-price<1000){ v="🟡 พอซื้อได้ แต่เหลือน้อย"; rs.push("ซื้อแล้วเหลือ "+fmt(cc.left-price)+" ฿"); }
    else { v="🟢 ซื้อได้"; rs.push("หลังซื้อเหลือ "+fmt(cc.left-price)+" ฿"); }
    bubble("<b>"+v+"</b><br>ราคา "+fmt(price)+" ฿<br>"+rs.map(function(x){return "• "+x;}).join("<br>"));
    return;
  }
  if(r.action==="income"){
    DB.transactions.push({type:"income",description:r.desc,amount:r.amount,category:"รายรับพิเศษ",date:new Date().toISOString()});
    saveDB(); bubble("✅ บันทึกรายรับ: <b>"+r.desc+"</b> — "+fmt(r.amount)+" ฿"); renderAll(); return;
  }
  var tx={type:"expense",description:r.description,amount:r.amount,category:r.category,channel:r.channel,date:r.date};
  DB.transactions.push(tx); saveDB();
  bubble("✅ บันทึกแล้ว<br><span style='background:#fff;border-radius:6px;padding:1px 6px;font-size:11px'>"+tx.category+"</span> <span style='background:#fff;border-radius:6px;padding:1px 6px;font-size:11px'>"+tx.channel+"</span><br><b>"+tx.description+"</b> — "+fmt(tx.amount)+" ฿");
  renderAll();
}

function renderAll(){ renderHeader(); renderDash(); renderReport(); renderBudget(); renderWish(); renderCards(); renderInstall(); renderShare(); renderHistory(); renderSettings(); }

function renderHeader(){
  var r=monthRange();
  var f=function(d){return d.toLocaleDateString("th-TH",{day:"numeric",month:"short"});};
  document.getElementById("cycleLabel").textContent="รอบเดือน: "+f(r[0])+" – "+f(r[1]);
}

function renderDash(){
  var c=calcDashboard();
  document.getElementById("d-income").textContent=fmt(c.income)+" ฿";
  document.getElementById("d-expense").textContent=fmt(c.expenses)+" ฿";
  document.getElementById("d-transfer").textContent=fmt(c.transfer)+" ฿";
  document.getElementById("d-save").textContent=fmt(c.saveAmt)+" ฿";
  var l=document.getElementById("d-left");
  l.textContent=fmt(c.left)+" ฿";
  l.className="big "+(c.left<0?"neg":"pos");
  var td=document.getElementById("d-topcat");
  td.innerHTML=c.top?"<div class='row'><span>"+c.top[0]+"</span><span class='neg'>"+fmt(c.top[1])+" ฿</span></div>":"ยังไม่มีข้อมูล";

  var alerts="";
  DB.budgets.forEach(function(b){
    var used=c.catMap[b.category]||0;
    var pct=(used/b.limit)*100;
    if(pct>=100) alerts+="<div class='row'><span>🔴 "+b.category+"</span><span class='neg'>เกินงบ "+fmt(used-b.limit)+" ฿</span></div>";
    else if(pct>=80) alerts+="<div class='row'><span>🟡 "+b.category+"</span><span class='warn'>ใช้ "+pct.toFixed(0)+"%</span></div>";
  });
  document.getElementById("d-budget-alert").innerHTML=alerts||"<small>ทุกหมวดอยู่ในงบ ✅</small>";
  document.getElementById("d-bnpl").textContent=fmt(bnplTotal())+" ฿";
}

function getAvailableMonths(){
  var months={};
  DB.transactions.forEach(function(t){
    var d=new Date(t.date);
    var key=d.getFullYear()+"-"+String(d.getMonth()+1).padStart(2,"0");
    months[key]={year:d.getFullYear(),month:d.getMonth()};
  });
  var now=new Date();
  months[now.getFullYear()+"-"+String(now.getMonth()+1).padStart(2,"0")]={year:now.getFullYear(),month:now.getMonth()};
  var arr=Object.keys(months).sort().reverse();
  return arr.map(function(k){return months[k];});
}

function renderReport(){
  var sel=document.getElementById("monthSelect");
  var months=getAvailableMonths();
  var currentVal=sel.value;
  if(sel.options.length!==months.length){
    sel.innerHTML="";
    months.forEach(function(m){
      var opt=document.createElement("option");
      opt.value=m.year+"-"+m.month;
      opt.textContent=new Date(m.year,m.month,1).toLocaleDateString("th-TH",{month:"long",year:"numeric"});
      sel.appendChild(opt);
    });
    if(currentVal) sel.value=currentVal;
  }
  if(!sel.value && months.length){ sel.value=months[0].year+"-"+months[0].month; }
  var parts=sel.value.split("-");
  var year=parseInt(parts[0]), month=parseInt(parts[1]);

  var tx=DB.transactions.filter(function(x){return inMonthOf(x.date,year,month);});
  var extra=tx.filter(function(x){return x.type==="income";}).reduce(function(a,b){return a+b.amount;},0);
  var salaryNet=DB.profile.salary-DB.profile.ss-DB.profile.pvd;
  var income=salaryNet+extra;
  var expTx=tx.filter(function(x){return x.type==="expense"&&x.category!=="โอน/ให้แม่";}).reduce(function(a,b){return a+b.amount;},0);
  var expFixed=DB.fixedCosts.filter(function(f){return f.type!=="transfer";}).reduce(function(a,b){return a+b.amount;},0);
  var exp=expTx+expFixed;
  var transfer=DB.fixedCosts.filter(function(f){return f.type==="transfer";}).reduce(function(a,b){return a+b.amount;},0);
  var saveAmt=DB.share.rounds.filter(function(r){return inMonthOf(r.date,year,month);}).reduce(function(a,b){return a+(b.amount||0);},0);
  var left=income-exp-transfer-saveAmt;

  var catMap={};
  tx.forEach(function(x){if(x.type==="expense")catMap[x.category]=(catMap[x.category]||0)+x.amount;});
  DB.fixedCosts.forEach(function(f){catMap[f.category]=(catMap[f.category]||0)+f.amount;});
  var top=null,tv=-1; for(var c in catMap){ if(catMap[c]>tv){tv=catMap[c];top=[c,catMap[c]];} }

  document.getElementById("r-income").textContent=fmt(income);
  document.getElementById("r-expense").textContent=fmt(exp);
  document.getElementById("r-left").textContent=fmt(left);
  document.getElementById("r-top").textContent=top?top[0]:"—";

  drawPie(catMap);
  drawBarChart();
  renderCatList(catMap);
}

function drawPie(catMap){
  var canvas=document.getElementById("pieChart");
  var ctx=canvas.getContext("2d");
  var colors=["#f59e0b","#059669","#dc2626","#d97706","#8b5cf6","#0891b2","#ec4899","#6b7280","#10b981","#fbbf24"];
  var entries=Object.keys(catMap).map(function(k){return [k,catMap[k]];}).sort(function(a,b){return b[1]-a[1];});
  var total=entries.reduce(function(a,b){return a+b[1];},0);
  ctx.clearRect(0,0,300,300);
  if(total===0){
    ctx.fillStyle="#a16207"; ctx.font="14px sans-serif"; ctx.textAlign="center";
    ctx.fillText("ยังไม่มีข้อมูล",150,150);
    document.getElementById("pieLegend").innerHTML="";
    return;
  }
  var cx=150, cy=150, r=120;
  var start=-Math.PI/2;
  var legendHtml="";
  entries.forEach(function(e,i){
    var pct=e[1]/total;
    var end=start+pct*Math.PI*2;
    ctx.beginPath();
    ctx.moveTo(cx,cy);
    ctx.arc(cx,cy,r,start,end);
    ctx.closePath();
    ctx.fillStyle=colors[i%colors.length];
    ctx.fill();
    ctx.strokeStyle="#fff"; ctx.lineWidth=2; ctx.stroke();
    start=end;
    legendHtml+="<div class='legend-item'><div class='legend-dot' style='background:"+colors[i%colors.length]+"'></div>"+e[0]+" "+(pct*100).toFixed(0)+"%</div>";
  });
  ctx.beginPath();
  ctx.arc(cx,cy,60,0,Math.PI*2);
  ctx.fillStyle="#fff";
  ctx.fill();
  ctx.fillStyle="#44403c"; ctx.font="bold 16px sans-serif"; ctx.textAlign="center";
  ctx.fillText(fmt(total)+" ฿",cx,cy+5);
  ctx.font="11px sans-serif"; ctx.fillStyle="#a16207";
  ctx.fillText("รวม",cx,cy-15);
  document.getElementById("pieLegend").innerHTML=legendHtml;
}

function drawBarChart(){
  var bar=document.getElementById("barChart");
  var html="";
  var now=new Date();
  var months=[];
  for(var i=5;i>=0;i--){
    var d=new Date(now.getFullYear(),now.getMonth()-i,1);
    months.push({y:d.getFullYear(),m:d.getMonth()});
  }
  var maxVal=0;
  var data=months.map(function(mo){
    var tx=DB.transactions.filter(function(x){return inMonthOf(x.date,mo.y,mo.m);});
    var extra=tx.filter(function(x){return x.type==="income";}).reduce(function(a,b){return a+b.amount;},0);
    var income=(DB.profile.salary-DB.profile.ss-DB.profile.pvd)+extra;
    var expTx=tx.filter(function(x){return x.type==="expense"&&x.category!=="โอน/ให้แม่";}).reduce(function(a,b){return a+b.amount;},0);
    var expFixed=DB.fixedCosts.filter(function(f){return f.type!=="transfer";}).reduce(function(a,b){return a+b.amount;},0);
    var exp=expTx+expFixed;
    if(income>maxVal) maxVal=income;
    if(exp>maxVal) maxVal=exp;
    return {label:(mo.m+1)+"/"+String(mo.y).slice(2),income:income,expense:exp};
  });
  if(maxVal===0) maxVal=1;
  data.forEach(function(d){
    var hI=(d.income/maxVal)*140;
    var hE=(d.expense/maxVal)*140;
    html+="<div class='bar-col'>"+
      "<div style='display:flex;gap:2px;align-items:flex-end;height:140px'>"+
        "<div class='bar' style='height:"+hI+"px;background:#059669' title='รับ "+fmt(d.income)+"'></div>"+
        "<div class='bar' style='height:"+hE+"px;background:#dc2626' title='จ่าย "+fmt(d.expense)+"'></div>"+
      "</div>"+
      "<div class='bar-label'>"+d.label+"</div>"+
    "</div>";
  });
  bar.innerHTML=html;
}

function renderCatList(catMap){
  var box=document.getElementById("r-catlist");
  var entries=Object.keys(catMap).map(function(k){return [k,catMap[k]];}).sort(function(a,b){return b[1]-a[1];});
  var total=entries.reduce(function(a,b){return a+b[1];},0);
  if(!entries.length){ box.innerHTML="<small>ยังไม่มีข้อมูล</small>"; return; }
  var html="";
  entries.forEach(function(e){
    var pct=total>0?(e[1]/total*100):0;
    html+="<div class='row'><span>"+e[0]+"</span><span>"+fmt(e[1])+" ฿ ("+pct.toFixed(0)+"%)</span></div>";
  });
  box.innerHTML=html;
}

function renderBudget(){
  var c=calcDashboard();
  var totalLimit=0, totalUsed=0;
  var html="";
  DB.budgets.forEach(function(b,idx){
    var used=c.catMap[b.category]||0;
    totalLimit+=b.limit; totalUsed+=used;
    var pct=Math.min(100,(used/b.limit)*100);
    var rawPct=(used/b.limit)*100;
    var cls="ok", barCls="";
    if(rawPct>=100){ cls="over"; barCls="over"; }
    else if(rawPct>=80){ cls="warn"; barCls="warn"; }
    var remain=b.limit-used;
    html+="<div class='budget-item "+cls+"'>"+
      "<div class='row' style='border:none;padding:0 0 6px 0'><b>"+b.category+"</b><span>"+fmt(used)+" / "+fmt(b.limit)+" ฿</span></div>"+
      "<div class='progress'><div class='"+barCls+"' style='width:"+pct+"%'></div></div>"+
      "<div class='row' style='border:none;font-size:12px;color:#a16207;padding-top:4px'>"+
        "<span>"+(remain>=0?"เหลือ "+fmt(remain)+" ฿":"เกิน "+fmt(-remain)+" ฿")+"</span>"+
        "<span>"+rawPct.toFixed(0)+"%</span>"+
      "</div>"+
      "<div style='display:flex;gap:6px;margin-top:6px'>"+
        "<button class='btn-sm gray' onclick='editBudget("+idx+")'>แก้ไข</button>"+
        "<button class='btn-sm red' onclick='delBudget("+idx+")'>ลบ</button>"+
      "</div>"+
    "</div>";
  });
  document.getElementById("budgetList").innerHTML=html||"<small>ยังไม่มีงบ</small>";
  document.getElementById("b-total").textContent=fmt(totalLimit);
  document.getElementById("b-used").textContent=fmt(totalUsed);
  document.getElementById("b-left").textContent=fmt(totalLimit-totalUsed);
  var pct=(totalUsed/totalLimit*100);
  document.getElementById("b-pct").textContent=(isNaN(pct)?0:pct).toFixed(0)+"%";
}

function addBudget(){
  var cat=prompt("ชื่อหมวด:");
  if(!cat) return;
  var limit=parseFloat(prompt("งบ (บาท):"));
  if(!limit) return;
  DB.budgets.push({category:cat,limit:limit});
  saveDB(); renderAll();
}

function editBudget(idx){
  var b=DB.budgets[idx];
  var cat=prompt("ชื่อหมวด:",b.category);
  if(cat===null) return;
  var limit=parseFloat(prompt("งบ (บาท):",b.limit));
  if(!limit) return;
  b.category=cat; b.limit=limit;
  saveDB(); renderAll();
}

function delBudget(idx){
  if(!confirm("ลบหมวดงบนี้?")) return;
  DB.budgets.splice(idx,1); saveDB(); renderAll();
}

function addWish(){
  var type=prompt("ประเภท: wishlist (ของ) / travel (เที่ยว)?","wishlist");
  if(type!=="wishlist" && type!=="travel") type="wishlist";
  var name=prompt("ชื่อ:");
  if(!name) return;
  var price=parseFloat(prompt("ราคา/เป้าหมาย (บาท):"));
  if(!price) return;
  var priority=prompt("ความสำคัญ: สูง / กลาง / ต่ำ","กลาง")||"กลาง";
  var monthlyPlan=0;
  if(type==="travel"){
    monthlyPlan=parseFloat(prompt("วางแผนเก็บเดือนละ (บาท, 0 ถ้ายังไม่รู้):","0")||"0");
  }
  DB.wishlist.push({id:"w"+Date.now(),name:name,price:price,type:type,priority:priority,saved:0,monthlyPlan:monthlyPlan,targetDate:""});
  saveDB(); renderAll();
}

function renderWish(){
  var box=document.getElementById("wishList");
  if(!DB.wishlist.length){ box.innerHTML="<small>ยังไม่มีรายการ</small>"; return; }
  var c=calcDashboard();
  var html="";
  DB.wishlist.forEach(function(w,idx){
    var canBuy=c.left>=w.price;
    var cls=w.type==="travel"?"travel":"wishlist";
    if(w.type==="wishlist"){ cls=canBuy?"can-buy":"cant-buy"; }
    var extra="";
    if(w.type==="travel"){
      var pct=w.price>0?Math.min(100,(w.saved/w.price)*100):0;
      var monthsLeft=w.monthlyPlan>0?Math.ceil((w.price-w.saved)/w.monthlyPlan):0;
      extra="<div class='progress'><div class='green' style='width:"+pct+"%'></div></div>"+
        "<div class='row' style='border:none;font-size:12px;color:#a16207'>"+
          "<span>เก็บแล้ว "+fmt(w.saved)+" / "+fmt(w.price)+" ฿</span>"+
          "<span>"+(w.monthlyPlan>0?"อีก ~"+monthsLeft+" เดือน":"ยังไม่ตั้งแผน")+"</span>"+
        "</div>";
    } else {
      extra="<div class='row' style='border:none;font-size:12px;color:#a16207'>"+
        "<span>"+(canBuy?"✅ เงินเหลือพอ":"❌ ยังไม่พอ (ขาด "+fmt(w.price-c.left)+" ฿)")+"</span>"+
        "<span>"+(canBuy?"":"อีก ~"+Math.ceil((w.price-c.left)/1000)+" เดือน")+"</span>"+
      "</div>";
    }
    html+="<div class='wish-item "+cls+"'>"+
      "<div class='row' style='border:none;padding:0 0 6px 0'>"+
        "<b>"+(w.type==="travel"?"✈️ ":"🎁 ")+w.name+"</b>"+
        "<span>"+fmt(w.price)+" ฿</span>"+
      "</div>"+
      "<div class='row' style='border:none;font-size:12px;color:#a16207'>"+
        "<span>ความสำคัญ: "+w.priority+"</span>"+
        "<span>"+(w.type==="travel"?"แผนเที่ยว":"Wishlist")+"</span>"+
      "</div>"+
      extra+
      "<div style='display:flex;gap:6px;margin-top:8px'>"+
        (w.type==="travel"?"<button class='btn-sm green' onclick='addSaved("+idx+")'>+ ออมเพิ่ม</button>":"")+
        "<button class='btn-sm gray' onclick='editWish("+idx+")'>แก้ไข</button>"+
        "<button class='btn-sm red' onclick='delWish("+idx+")'>ลบ</button>"+
      "</div>"+
    "</div>";
  });
  box.innerHTML=html;
}

function addSaved(idx){
  var w=DB.wishlist[idx];
  var v=parseFloat(prompt("จำนวนเงินที่ออมเพิ่ม (บาท):","0"));
  if(!v) return;
  w.saved=(w.saved||0)+v;
  saveDB(); renderAll();
}

function editWish(idx){
  var w=DB.wishlist[idx];
  var name=prompt("ชื่อ:",w.name);
  if(name===null) return;
  var price=parseFloat(prompt("ราคา:",w.price));
  if(!price) return;
  var priority=prompt("ความสำคัญ (สูง/กลาง/ต่ำ):",w.priority)||w.priority;
  w.name=name; w.price=price; w.priority=priority;
  if(w.type==="travel"){
    var mp=parseFloat(prompt("แผนเก็บเดือนละ:",w.monthlyPlan||0)||"0");
    w.monthlyPlan=mp;
  }
  saveDB(); renderAll();
}

function delWish(idx){
  if(!confirm("ลบรายการนี้?")) return;
  DB.wishlist.splice(idx,1); saveDB(); renderAll();
}

function nextDueDate(day){
  var t=new Date();
  var d=new Date(t.getFullYear(),t.getMonth(),day);
  if(d<t) d.setMonth(d.getMonth()+1);
  return d;
}
function daysUntil(d){ return Math.ceil((d-new Date())/86400000); }

function renderCards(){
  var total=0, urgent=0;
  var list=document.getElementById("cardsList");
  var html="";
  DB.cards.forEach(function(c,idx){
    var spent=0;
    DB.transactions.forEach(function(t){
      if(t.channel===c.name && inMonth(t.date) && t.type==="expense") spent+=t.amount;
    });
    var due=c.manualBalance||0;
    var cardTotal=spent+due;
    total+=cardTotal;

    var daysText="—";
    var cls="safe";
    if(c.dueDay){
      var nd=nextDueDate(c.dueDay);
      var dd=daysUntil(nd);
      daysText="อีก "+dd+" วัน ("+fmtDate(nd.toISOString())+")";
      if(dd<=7){ cls="urgent"; urgent+=cardTotal; }
      else if(dd<=15){ cls="soon"; }
    }

    html+="<div class='card-item "+cls+"'>"+
      "<div class='row' style='border:none;padding:0 0 6px 0'><b>"+c.name+"</b><span style='font-size:18px;font-weight:700;color:#dc2626'>"+fmt(cardTotal)+" ฿</span></div>"+
      "<div class='row' style='border:none;font-size:12px;color:#a16207'>"+
        "<span>"+(c.statementDay?"ตัดรอบ "+c.statementDay+" • จ่าย "+c.dueDay:"ไม่มีรอบตัด")+"</span>"+
        "<span>"+daysText+"</span>"+
      "</div>"+
      "<div class='row' style='border:none;font-size:12px;color:#a16207;padding-top:4px'>"+
        "<span>ใช้จ่ายเดือนนี้: "+fmt(spent)+" ฿</span>"+
        "<span>ค้างเดิม: "+fmt(due)+" ฿</span>"+
      "</div>"+
      "<div style='display:flex;gap:6px;margin-top:8px'>"+
        "<button class='btn-sm' onclick='editCardBalance("+idx+")'>+ เพิ่มยอดค้าง</button>"+
        "<button class='btn-sm gray' onclick='editCard("+idx+")'>แก้ไข</button>"+
      "</div>"+
    "</div>";
  });
  list.innerHTML=html;
  document.getElementById("c-total").textContent=fmt(total);
  document.getElementById("c-urgent").textContent=fmt(urgent);
}

function editCardBalance(idx){
  var c=DB.cards[idx];
  var v=prompt("ยอดค้างเดิมของ "+c.name+" (บาท):", c.manualBalance||0);
  if(v===null) return;
  c.manualBalance=parseFloat(v)||0;
  saveDB(); renderAll();
}

function editCard(idx){
  var c=DB.cards[idx];
  var name=prompt("ชื่อบัตร:", c.name);
  if(name===null) return;
  var sd=prompt("วันตัดรอบ (1-31, เว้นว่างถ้าไม่มี):", c.statementDay||"");
  var dd=prompt("วันจ่าย (1-31):", c.dueDay||"");
  var mb=prompt("ยอดค้างเดิม (บาท):", c.manualBalance||0);
  c.name=name;
  c.statementDay=sd?parseInt(sd):null;
  c.dueDay=dd?parseInt(dd):null;
  c.manualBalance=parseFloat(mb)||0;
  saveDB(); renderAll();
}

function renderInstall(){
  var box=document.getElementById("installList");
  if(!DB.installments.length){ box.innerHTML="<small>ยังไม่มีรายการผ่อน</small>"; return; }
  var html="";
  DB.installments.forEach(function(it,idx){
    var remain=it.total-it.paid;
    var pct=(it.paid/it.total)*100;
    html+="<div class='item'>"+
      "<div class='row' style='border:none;padding:0 0 6px 0'><b>"+it.name+"</b><span>"+fmt(it.monthly)+" ฿/งวด</span></div>"+
      "<div class='row' style='border:none;font-size:12px;color:#a16207'><span>"+(it.cardId||"—")+" • งวดถัดไป "+fmtDate(it.nextDate)+"</span><span>"+it.paid+"/"+it.total+" งวด</span></div>"+
      "<div class='progress'><div style='width:"+pct+"%'></div></div>"+
      "<div class='row' style='border:none;padding-top:8px'>"+
        "<span>"+(remain>0?"เหลือ "+remain+" งวด ("+fmt(remain*it.monthly)+" ฿)":"<span class='badge done'>ผ่อนครบแล้ว</span>")+"</span>"+
        "<div style='display:flex;gap:4px'>"+
          (remain>0?"<button class='btn-sm green' onclick='payInstall("+idx+")'>จ่ายงวดนี้</button>":"")+
          "<button class='btn-sm gray' onclick='editInstall("+idx+")'>แก้ไข</button>"+
          "<button class='btn-sm red' onclick='delInstall("+idx+")'>ลบ</button>"+
        "</div>"+
      "</div></div>";
  });
  box.innerHTML=html;
}

function payInstall(idx){
  var it=DB.installments[idx];
  if(it.paid>=it.total) return;
  it.paid++;
  var d=it.nextDate?new Date(it.nextDate):new Date();
  d.setMonth(d.getMonth()+1);
  it.nextDate=d.toISOString().slice(0,10);
  saveDB(); renderAll();
  alert("จ่ายงวด "+it.paid+"/"+it.total+" แล้ว\nงวดถัดไป: "+fmtDate(it.nextDate));
}

function editInstall(idx){
  var it=DB.installments[idx];
  var name=prompt("ชื่อ:",it.name); if(name===null) return;
  var monthly=parseFloat(prompt("งวดละ:",it.monthly)); if(!monthly) return;
  var total=parseInt(prompt("จำนวนงวดทั้งหมด:",it.total)); if(!total) return;
  var paid=parseInt(prompt("จ่ายไปแล้วกี่งวด:",it.paid)||"0");
  var next=prompt("งวดถัดไป (YYYY-MM-DD):",it.nextDate||"")||"";
  var cid=prompt("ช่องทาง (เช่น Card X Flex, S-PayLater):",it.cardId||"")||"";
  it.name=name; it.monthly=monthly; it.total=total; it.paid=paid; it.nextDate=next; it.cardId=cid;
  saveDB(); renderAll();
}

function delInstall(idx){
  if(!confirm("ลบรายการนี้?")) return;
  DB.installments.splice(idx,1); saveDB(); renderAll();
}

function openAdd(){
  var name=prompt("ชื่อรายการผ่อน:");
  if(!name) return;
  var monthly=parseFloat(prompt("งวดละ (บาท):"));
  if(!monthly) return;
  var total=parseInt(prompt("จำนวนงวดทั้งหมด:"));
  if(!total) return;
  var paid=parseInt(prompt("จ่ายไปแล้วกี่งวด (0 ถ้ายังไม่จ่าย):")||"0");
  var next=prompt("งวดถัดไป (YYYY-MM-DD):")||"";
  var cid=prompt("ช่องทาง (เช่น Card X Flex, S-PayLater):","")||"";
  DB.installments.push({name:name,total:total,paid:paid,monthly:monthly,nextDate:next,cardId:cid});
  saveDB(); renderAll();
}

function renderShare(){
  var s=DB.share;
  var paid=0, interest=0;
  s.rounds.forEach(function(r){ paid+=(r.amount||0); interest+=(r.interest||0); });
  var roundsCount=s.rounds.length;
  var remain=s.totalRounds-roundsCount;
  var pct=Math.min(100,(paid/s.principal)*100);

  document.getElementById("sh-paid").textContent=fmt(paid);
  document.getElementById("sh-rounds").textContent=roundsCount+"/"+s.totalRounds;
  document.getElementById("sh-interest").textContent=fmt(interest);
  document.getElementById("sh-remain").textContent=remain;
  document.getElementById("sh-bar").style.width=pct+"%";
  document.getElementById("sh-pct").textContent=pct.toFixed(1)+"% ของ "+fmt(s.principal)+" ฿";
  document.getElementById("sh-count").textContent="("+roundsCount+" รายการ)";

  var hist=document.getElementById("shareHistory");
  if(!s.rounds.length){ hist.innerHTML="<small>ยังไม่มีประวัติ</small>"; return; }
  var html="";
  var sorted=s.rounds.slice().reverse();
  sorted.forEach(function(r){
    var realIdx=s.rounds.indexOf(r);
    html+="<div class='row'><span>📅 "+fmtDate(r.date)+"</span><span>"+fmt(r.amount)+" ฿"+(r.interest?" <span class='pos'>(+"+fmt(r.interest)+")</span>":"")+"</span><button class='btn-sm red' onclick='delShare("+realIdx+")'>ลบ</button></div>";
  });
  hist.innerHTML=html;
}

function openShareAdd(){
  var date=prompt("วันที่ส่ง (YYYY-MM-DD):", new Date().toISOString().slice(0,10));
  if(!date) return;
  var amount=parseFloat(prompt("จำนวนเงิน:","2000"));
  if(!amount) return;
  var interest=parseFloat(prompt("ดอกที่ได้งวดนี้ (0 ถ้าไม่มี):","0")||"0");
  DB.share.rounds.push({date:new Date(date).toISOString(),amount:amount,interest:interest});
  saveDB(); renderAll();
  alert("บันทึกงวดใหม่แล้ว");
}

function delShare(idx){
  if(!confirm("ลบงวดนี้?")) return;
  DB.share.rounds.splice(idx,1); saveDB(); renderAll();
}

function renderHistory(){
  var box=document.getElementById("historyList");
  var tx=DB.transactions.slice().reverse();
  if(!tx.length){ box.innerHTML="<small>ยังไม่มีรายการ</small>"; return; }
  var html="";
  tx.forEach(function(t,i){
    var idx=DB.transactions.length-1-i;
    html+="<div class='row'><span>"+(t.type==="income"?"💰 ":"💸 ")+"<b>"+t.description+"</b><br><small>"+t.category+" • "+(t.channel||"")+" • "+new Date(t.date).toLocaleDateString("th-TH")+"</small></span><span class='"+(t.type==="income"?"pos":"neg")+"'>"+(t.type==="income"?"+":"-")+fmt(t.amount)+" ฿</span><button class='btn-sm red' onclick='delTx("+idx+")'>ลบ</button></div>";
  });
  box.innerHTML=html;
}

function delTx(idx){ DB.transactions.splice(idx,1); saveDB(); renderAll(); }

function renderSettings(){
  document.getElementById("s-salary").value=DB.profile.salary;
  document.getElementById("s-ss").value=DB.profile.ss;
  document.getElementById("s-pvd").value=DB.profile.pvd;
}
function saveSettings(){
  DB.profile.salary=+document.getElementById("s-salary").value;
  DB.profile.ss=+document.getElementById("s-ss").value;
  DB.profile.pvd=+document.getElementById("s-pvd").value;
  saveDB(); renderAll(); alert("บันทึกแล้ว");
}
function exportJSON(){
  var blob=new Blob([JSON.stringify(DB,null,2)],{type:"application/json"});
  var url=URL.createObjectURL(blob);
  var a=document.createElement("a"); a.href=url; a.download="tracker-backup.json"; a.click();
  URL.revokeObjectURL(url);
}
function clearAll(){
  if(!confirm("ล้างข้อมูลทั้งหมด?")) return;
  localStorage.removeItem(KEY); location.reload();
}

document.querySelectorAll("nav button").forEach(function(b){
  b.onclick=function(){
    document.querySelectorAll("nav button").forEach(function(x){x.classList.remove("active");});
    document.querySelectorAll(".tab").forEach(function(x){x.classList.remove("active");});
    b.classList.add("active");
    document.getElementById("tab-"+b.getAttribute("data-tab")).classList.add("active");
    if(b.getAttribute("data-tab")==="report") renderReport();
  };
});
document.getElementById("chatInput").addEventListener("keydown",function(e){ if(e.key==="Enter") sendChat(); });

bubble("สวัสดีครับ! พิมพ์รายการได้เลย เช่น <b>ข้าวเที่ยง 80 cash</b>");
renderAll();
</script>
</body>
</html>
