<!DOCTYPE html>
<html lang="am">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>ሴኒያ ቢዝነስ</title>
<script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Ethiopic:wght@300;400;600;700;800&display=swap');

*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent;}

:root{
  --bg:#07070e;
  --card:#10101a;
  --card2:#181826;
  --card3:#1e1e2e;
  --gold:#e8b84b;
  --gold2:#f5d070;
  --gold3:#b08828;
  --gold-glow:rgba(232,184,75,0.18);
  --green:#22c55e;
  --red:#f05050;
  --blue:#60a5fa;
  --text:#f0ebe0;
  --muted:#7a7490;
  --border:#22223a;
  --radius:18px;
  --radius-sm:12px;
  --font:18px;
  --shadow:0 8px 32px rgba(0,0,0,0.45);
  --shadow-gold:0 4px 24px rgba(232,184,75,0.22);
}

html{font-size:var(--font);}
body{
  background:var(--bg);
  color:var(--text);
  font-family:'Noto Sans Ethiopic',sans-serif;
  min-height:100vh;
  overflow-x:hidden;
  -webkit-font-smoothing:antialiased;
}

::-webkit-scrollbar{width:4px;}
::-webkit-scrollbar-track{background:transparent;}
::-webkit-scrollbar-thumb{background:var(--gold3);border-radius:2px;}

/* ===== SPLASH ===== */
.splash{
  position:fixed;inset:0;
  background:radial-gradient(ellipse at 50% 40%,#16101a 0%,#07070e 70%);
  display:flex;flex-direction:column;align-items:center;justify-content:center;
  z-index:9999;transition:opacity 0.9s ease;
}
.splash.hide{opacity:0;pointer-events:none;}
.splash-arabic{
  font-size:26px;color:var(--gold2);
  direction:rtl;letter-spacing:3px;
  text-shadow:0 0 40px rgba(232,184,75,0.5);
  margin-bottom:6px;
}
.splash-arabic2{font-size:13px;color:var(--muted);direction:rtl;margin-bottom:28px;}
.splash-logo{
  width:90px;height:90px;
  border-radius:26px;
  background:linear-gradient(135deg,var(--gold),var(--gold3));
  display:flex;align-items:center;justify-content:center;
  font-size:44px;margin-bottom:20px;
  box-shadow:0 0 60px rgba(232,184,75,0.35),var(--shadow);
}
.splash-title{font-size:28px;font-weight:800;color:var(--gold2);letter-spacing:1px;}
.splash-sub{font-size:14px;color:var(--muted);margin-top:6px;}
.splash-bar{width:200px;height:3px;background:var(--border);border-radius:2px;margin-top:36px;overflow:hidden;}
.splash-fill{height:100%;background:linear-gradient(90deg,var(--gold3),var(--gold2),var(--gold3));border-radius:2px;animation:splashFill 2.2s ease forwards;}
@keyframes splashFill{from{width:0}to{width:100%}}

/* ===== APP SHELL ===== */
.app{max-width:480px;margin:0 auto;min-height:100vh;display:flex;flex-direction:column;position:relative;}

/* ===== HEADER ===== */
.header{
  background:var(--card);
  border-bottom:1px solid var(--border);
  padding:16px 18px 14px;
  position:sticky;top:0;z-index:100;
  backdrop-filter:blur(10px);
}
.header-top{display:flex;align-items:center;gap:12px;}
.logo-box{
  width:44px;height:44px;border-radius:13px;
  background:linear-gradient(135deg,var(--gold),var(--gold3));
  display:flex;align-items:center;justify-content:center;
  font-size:22px;flex-shrink:0;
  box-shadow:var(--shadow-gold);
}
.header-title{font-size:18px;font-weight:800;color:var(--gold2);}
.header-arabic{font-size:11px;color:var(--muted);direction:rtl;}
.header-right{margin-left:auto;text-align:right;}
.header-role{font-size:11px;color:var(--muted);}
.header-name{font-size:14px;font-weight:700;color:var(--gold);}
.offline-badge{background:#7f1d1d;color:#fca5a5;font-size:11px;padding:3px 10px;border-radius:20px;}
.online-badge{background:#14532d;color:#86efac;font-size:11px;padding:3px 10px;border-radius:20px;}

/* ===== CONTENT ===== */
.content{flex:1;padding:14px 14px 96px;overflow-y:auto;}

/* ===== BOTTOM NAV ===== */
.bottom-nav{
  position:fixed;bottom:0;left:50%;transform:translateX(-50%);
  width:100%;max-width:480px;
  background:var(--card);
  border-top:1px solid var(--border);
  display:flex;z-index:100;
  padding-bottom:env(safe-area-inset-bottom);
  box-shadow:0 -8px 32px rgba(0,0,0,0.4);
}
.nav-btn{
  flex:1;background:none;border:none;cursor:pointer;
  padding:10px 0 8px;display:flex;flex-direction:column;
  align-items:center;gap:3px;color:var(--muted);transition:color 0.2s;
}
.nav-btn.active{color:var(--gold);}
.nav-icon{font-size:22px;}
.nav-label{font-size:10px;font-weight:700;}
.nav-dot{width:5px;height:5px;border-radius:3px;background:var(--gold);margin-top:1px;}

/* ===== CARDS ===== */
.card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius);
  padding:18px;
  box-shadow:var(--shadow);
}
.card+.card{margin-top:12px;}
.card-title{
  font-size:12px;color:var(--muted);font-weight:700;
  margin-bottom:14px;text-transform:uppercase;letter-spacing:0.8px;
}

/* ===== STATS ===== */
.stats-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:12px;}
.stat-card{
  background:var(--card);border:1px solid var(--border);
  border-radius:var(--radius);padding:18px;
  box-shadow:var(--shadow);
  transition:transform 0.15s;
}
.stat-card:active{transform:scale(0.97);}
.stat-icon{font-size:26px;margin-bottom:8px;}
.stat-val{font-size:18px;font-weight:800;line-height:1.1;}
.stat-label{font-size:11px;color:var(--muted);margin-top:4px;}

/* ===== INPUTS ===== */
.inp{
  width:100%;
  background:var(--card2);
  border:1.5px solid var(--border);
  border-radius:var(--radius-sm);
  padding:14px 16px;
  color:var(--text);
  font-family:inherit;
  font-size:16px;
  outline:none;
  transition:border-color 0.2s,box-shadow 0.2s;
}
.inp:focus{border-color:var(--gold);box-shadow:0 0 0 3px var(--gold-glow);}
.inp::placeholder{color:var(--muted);}
.lbl{font-size:13px;color:var(--muted);margin-bottom:7px;display:block;font-weight:600;}
.field{margin-bottom:14px;}
select.inp{-webkit-appearance:none;}

/* ===== BUTTONS ===== */
.btn{
  width:100%;border:none;
  border-radius:var(--radius-sm);
  padding:16px;
  font-family:inherit;font-size:17px;font-weight:800;
  cursor:pointer;transition:opacity 0.2s,transform 0.1s;
  letter-spacing:0.3px;
}
.btn:active{opacity:0.82;transform:scale(0.98);}
.btn-gold{
  background:linear-gradient(135deg,var(--gold),var(--gold3));
  color:#000;
  box-shadow:var(--shadow-gold);
}
.btn-green{background:linear-gradient(135deg,#22c55e,#16a34a);color:#fff;}
.btn-red{background:linear-gradient(135deg,#f05050,#b91c1c);color:#fff;}
.btn-secondary{background:var(--card2);border:1px solid var(--border);color:var(--text);}
.btn-sm{padding:10px 16px;font-size:14px;width:auto;border-radius:10px;}

/* ===== BADGES ===== */
.badge{display:inline-block;font-size:11px;padding:3px 10px;border-radius:20px;font-weight:700;}
.badge-red{background:#5a1010;color:#fca5a5;}
.badge-green{background:#0d3d1d;color:#86efac;}
.badge-gold{background:#3a2000;color:var(--gold2);}
.badge-blue{background:#0d2a4a;color:#93c5fd;}

/* ===== LIST ITEMS ===== */
.list-item{
  background:var(--card);border:1px solid var(--border);
  border-radius:var(--radius);padding:14px;
  margin-bottom:10px;display:flex;align-items:center;gap:12px;
  box-shadow:0 2px 12px rgba(0,0,0,0.25);
}
.list-item-img{
  width:52px;height:52px;border-radius:13px;
  background:var(--card2);
  display:flex;align-items:center;justify-content:center;
  font-size:24px;flex-shrink:0;
  border:1px solid var(--border);
}
.list-item-img img{width:100%;height:100%;object-fit:cover;border-radius:12px;}

/* ===== PROGRESS ===== */
.progress-bar{height:7px;background:var(--border);border-radius:4px;overflow:hidden;margin:8px 0;}
.progress-fill{height:100%;background:linear-gradient(90deg,var(--green),#16a34a);border-radius:4px;transition:width 0.5s;}

/* ===== ALERTS ===== */
.alert{border-radius:var(--radius);padding:15px 16px;margin-bottom:12px;}
.alert-red{background:#2e0a0a;border:1px solid rgba(240,80,80,0.25);}
.alert-gold{background:#201200;border:1px solid rgba(176,136,40,0.35);}
.alert-green{background:#071a0d;border:1px solid rgba(34,197,94,0.22);}
.alert-blue{background:#071628;border:1px solid rgba(96,165,250,0.22);}

/* ===== ROLE SCREEN ===== */
.role-screen{
  position:fixed;inset:0;
  background:radial-gradient(ellipse at 50% 30%,#15101c 0%,#07070e 70%);
  display:flex;flex-direction:column;align-items:center;justify-content:center;
  padding:28px;z-index:500;
}
.role-card{
  background:var(--card);border:1.5px solid var(--border);
  border-radius:22px;padding:26px;width:100%;max-width:360px;
  cursor:pointer;transition:border-color 0.2s,transform 0.15s,box-shadow 0.2s;
  margin-bottom:14px;box-shadow:var(--shadow);
}
.role-card:active{transform:scale(0.97);}
.role-card:hover{border-color:var(--gold);box-shadow:var(--shadow-gold);}
.role-card-icon{font-size:44px;margin-bottom:14px;}
.role-card-title{font-size:20px;font-weight:800;color:var(--gold2);margin-bottom:8px;}
.role-card-desc{font-size:14px;color:var(--muted);line-height:1.7;}

/* ===== PIN PAD ===== */
.pin-screen{
  position:fixed;inset:0;background:rgba(0,0,0,0.88);
  z-index:600;display:flex;align-items:center;justify-content:center;padding:24px;
  backdrop-filter:blur(6px);
}
.pin-box{
  background:var(--card);border:1px solid var(--border);
  border-radius:26px;padding:32px 24px;width:100%;max-width:340px;
  text-align:center;box-shadow:var(--shadow);
}
.pin-title{font-size:18px;font-weight:800;color:var(--gold2);margin-bottom:6px;}
.pin-sub{font-size:14px;color:var(--muted);margin-bottom:24px;}
.pin-dots{display:flex;justify-content:center;gap:14px;margin-bottom:24px;}
.pin-dot{width:16px;height:16px;border-radius:50%;border:2px solid var(--border);background:transparent;transition:background 0.2s,border-color 0.2s;}
.pin-dot.filled{background:var(--gold);border-color:var(--gold);box-shadow:0 0 10px rgba(232,184,75,0.5);}
.pin-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;}
.pin-key{
  background:var(--card2);border:1.5px solid var(--border);
  border-radius:16px;padding:18px;
  font-size:22px;font-weight:800;color:var(--text);
  cursor:pointer;transition:background 0.15s,transform 0.1s;
}
.pin-key:active{background:var(--gold);color:#000;transform:scale(0.93);}
.pin-key.zero{grid-column:2;}
.pin-key.del{background:#1e0a0a;color:var(--red);font-size:18px;}
.pin-err{color:var(--red);font-size:14px;font-weight:700;margin-top:12px;min-height:22px;}

/* ===== TOAST ===== */
.toast{
  position:fixed;top:84px;left:50%;transform:translateX(-50%);
  background:var(--green);color:#fff;
  padding:12px 28px;border-radius:24px;font-weight:800;
  z-index:9999;font-size:15px;
  box-shadow:0 6px 28px rgba(0,0,0,0.35);
  animation:toastIn 0.3s ease;
  white-space:nowrap;
}
.toast.err{background:var(--red);}
@keyframes toastIn{from{opacity:0;transform:translateX(-50%) translateY(-12px)}to{opacity:1;transform:translateX(-50%) translateY(0)}}

/* ===== CHART ===== */
.chart-bar-wrap{display:flex;align-items:flex-end;gap:8px;height:110px;padding-top:8px;}
.chart-bar{flex:1;border-radius:7px 7px 0 0;min-height:4px;transition:height 0.5s;}
.chart-label{font-size:10px;color:var(--muted);text-align:center;margin-top:6px;}

/* ===== GPS ===== */
.gps-dot{width:10px;height:10px;border-radius:50%;background:var(--green);display:inline-block;margin-right:6px;box-shadow:0 0 0 3px rgba(34,197,94,0.25);animation:gpsPulse 2s infinite;}
@keyframes gpsPulse{0%,100%{box-shadow:0 0 0 3px rgba(34,197,94,0.25)}50%{box-shadow:0 0 0 7px rgba(34,197,94,0.08)}}

/* ===== SETTINGS ===== */
.settings-panel{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:18px;margin-bottom:14px;box-shadow:var(--shadow);}
.settings-title{font-size:15px;font-weight:800;color:var(--gold2);margin-bottom:18px;}
.slider-wrap{display:flex;align-items:center;gap:12px;margin-bottom:16px;}
.slider-wrap input[type=range]{flex:1;accent-color:var(--gold);height:6px;}
.color-swatches{display:flex;gap:12px;flex-wrap:wrap;margin-top:8px;}
.swatch{width:40px;height:40px;border-radius:12px;cursor:pointer;border:3px solid transparent;transition:border-color 0.2s,transform 0.15s;}
.swatch:active{transform:scale(0.88);}
.swatch.active{border-color:#fff;box-shadow:0 0 0 2px var(--gold);}

/* ===== RECEIPT PRINT ===== */
@media print{
  body *{visibility:hidden;}
  .receipt-print,
  .receipt-print *{visibility:visible;}
  .receipt-print{
    position:absolute;left:0;top:0;width:100%;
    font-family:'Noto Sans Ethiopic',monospace;
    font-size:13px;
    color:#000;background:#fff;padding:8px;
  }
}
.receipt-print{
  background:#fff;color:#111;
  border-radius:var(--radius);
  padding:20px;
  font-family:'Noto Sans Ethiopic',monospace;
}
.receipt-divider{border:none;border-top:1px dashed #bbb;margin:10px 0;}
.receipt-row{display:flex;justify-content:space-between;padding:5px 0;font-size:15px;}
.receipt-total{display:flex;justify-content:space-between;padding:8px 0;font-size:18px;font-weight:800;}
.receipt-footer{text-align:center;margin-top:12px;font-size:13px;color:#888;}

/* ===== SUB-TAB SCROLL ===== */
.sub-tab-scroll{display:flex;gap:8px;overflow-x:auto;padding-bottom:10px;margin-bottom:14px;scrollbar-width:none;}
.sub-tab-scroll::-webkit-scrollbar{display:none;}
.sub-tab-btn{
  flex-shrink:0;padding:9px 16px;border-radius:24px;
  border:1.5px solid var(--border);
  background:var(--card);
  color:var(--muted);font-family:inherit;
  font-size:13px;cursor:pointer;font-weight:600;
  transition:all 0.15s;white-space:nowrap;
}
.sub-tab-btn.active{
  border-color:var(--gold);background:var(--card2);
  color:var(--gold2);font-weight:800;
}

/* ===== DIVIDER ===== */
.divider{border:none;border-top:1px solid var(--border);margin:10px 0;}

/* ===== PIN CHANGE ===== */
.pin-change-modal{position:fixed;inset:0;background:rgba(0,0,0,0.88);z-index:700;display:flex;align-items:center;justify-content:center;padding:24px;backdrop-filter:blur(6px);}
.pin-change-box{background:var(--card);border:1px solid var(--border);border-radius:26px;padding:28px;width:100%;max-width:340px;box-shadow:var(--shadow);}
</style>
</head>
<body>
<div id="root"></div>
<script type="text/babel">
const {useState,useEffect,useRef,useCallback}=React;

// ===== DATA SCHEMA VERSION (for migration safety) =====
const SCHEMA_VERSION = 3;

// ===== LOCAL STORAGE DB WITH MIGRATION =====
const DB={
  get:(k)=>{try{return JSON.parse(localStorage.getItem('seniya_'+k)||'null')}catch{return null}},
  set:(k,v)=>{try{localStorage.setItem('seniya_'+k,JSON.stringify(v))}catch{}},
  // Migrate from old keys (no prefix) to new prefixed keys
  migrate(){
    const ver=this.get('schema_version');
    if(ver===SCHEMA_VERSION)return;
    // Copy from old unprefixed keys if they exist
    const keys=['sales','products','debts','expenses','damages','preorders','customers','transport','returns','workers','appSettings'];
    keys.forEach(k=>{
      const old=localStorage.getItem(k);
      if(old&&!localStorage.getItem('seniya_'+k)){
        localStorage.setItem('seniya_'+k,old);
      }
    });
    this.set('schema_version',SCHEMA_VERSION);
  },
  init(){
    this.migrate();
    if(!this.get('sales'))this.set('sales',[]);
    if(!this.get('products'))this.set('products',[
      {id:1,name:'ሸክላ ድስት ትልቅ',price:180,cost:100,qty:20,category:'ሸክላ',image:null},
      {id:2,name:'ሰፌድ አነስተኛ',price:45,cost:25,qty:35,category:'ሰፌድ',image:null},
      {id:3,name:'ሸክላ ሳህን',price:60,cost:35,qty:18,category:'ሸክላ',image:null},
    ]);
    if(!this.get('debts'))this.set('debts',[]);
    if(!this.get('expenses'))this.set('expenses',[]);
    if(!this.get('damages'))this.set('damages',[]);
    if(!this.get('preorders'))this.set('preorders',[]);
    if(!this.get('customers'))this.set('customers',[]);
    if(!this.get('transport'))this.set('transport',[]);
    if(!this.get('returns'))this.set('returns',[]);
    if(!this.get('workers'))this.set('workers',[
      {id:1,name:'ሰራተኛ 1',role:'worker'},
      {id:2,name:'ሰራተኛ 2',role:'worker'},
    ]);
    if(!this.get('appSettings'))this.set('appSettings',{fontSize:18,theme:'gold'});
    if(!this.get('ownerPin'))this.set('ownerPin','2026');
    // Offline queue
    if(!this.get('syncQueue'))this.set('syncQueue',[]);
  }
};
DB.init();

// ===== OFFLINE SYNC QUEUE =====
// When offline: saves to queue. When online: sends queued items to "cloud" (Firebase stub).
// Replace FIREBASE_URL with your actual Firebase Realtime Database URL to enable real sync.
const FIREBASE_URL = ''; // e.g. 'https://your-project.firebaseio.com'

const SyncManager = {
  queue: DB.get('syncQueue') || [],
  addToQueue(action) {
    this.queue.push({...action, _ts: Date.now()});
    DB.set('syncQueue', this.queue);
  },
  async flushQueue(onProgress) {
    if (!FIREBASE_URL || this.queue.length === 0) return;
    const toSend = [...this.queue];
    let sent = 0;
    for (const item of toSend) {
      try {
        await fetch(`${FIREBASE_URL}/seniya/${item.key}.json`, {
          method: 'PUT',
          body: JSON.stringify(item.value),
          headers: {'Content-Type':'application/json'},
        });
        sent++;
        this.queue = this.queue.filter(q => q._ts !== item._ts);
        DB.set('syncQueue', this.queue);
        if(onProgress) onProgress(sent, toSend.length);
      } catch(e) {
        break; // Stop on error, retry next time
      }
    }
  },
  async saveToCloud(key, value) {
    if (!FIREBASE_URL) return;
    try {
      await fetch(`${FIREBASE_URL}/seniya/${key}.json`, {
        method: 'PUT',
        body: JSON.stringify(value),
        headers: {'Content-Type':'application/json'},
      });
    } catch(e) {
      this.addToQueue({key, value});
    }
  }
};

const fmt=(n)=>Number(n||0).toLocaleString('am-ET')+' ብር';
const today=()=>new Date().toISOString().slice(0,10);
const nowTime=()=>new Date().toLocaleTimeString('am',{hour:'2-digit',minute:'2-digit'});

// ===== THEMES =====
const THEMES={
  gold:{
    '--gold':'#e8b84b','--gold2':'#f5d070','--gold3':'#b08828',
    '--gold-glow':'rgba(232,184,75,0.18)',
    '--bg':'#07070e','--card':'#10101a','--card2':'#181826','--card3':'#1e1e2e',
    '--border':'#22223a','--text':'#f0ebe0','--muted':'#7a7490',
    '--green':'#22c55e','--red':'#f05050','--blue':'#60a5fa',
  },
  blue:{
    '--gold':'#60a5fa','--gold2':'#93c5fd','--gold3':'#2563eb',
    '--gold-glow':'rgba(96,165,250,0.18)',
    '--bg':'#04091a','--card':'#080f28','--card2':'#0d1836','--card3':'#101e3e',
    '--border':'#162040','--text':'#e8f0f8','--muted':'#4a6080',
    '--green':'#22c55e','--red':'#f05050','--blue':'#93c5fd',
  },
  green:{
    '--gold':'#4ade80','--gold2':'#86efac','--gold3':'#16a34a',
    '--gold-glow':'rgba(74,222,128,0.18)',
    '--bg':'#04100a','--card':'#081a0e','--card2':'#0d2414','--card3':'#102a18',
    '--border':'#163822','--text':'#e8f5ec','--muted':'#4a6055',
    '--green':'#4ade80','--red':'#f05050','--blue':'#60a5fa',
  },
  purple:{
    '--gold':'#c084fc','--gold2':'#e879f9','--gold3':'#7c3aed',
    '--gold-glow':'rgba(192,132,252,0.18)',
    '--bg':'#07040f','--card':'#100c1c','--card2':'#16102a','--card3':'#1c1436',
    '--border':'#281a45','--text':'#f2eef8','--muted':'#6a5585',
    '--green':'#22c55e','--red':'#f05050','--blue':'#60a5fa',
  },
};
const THEME_LABELS={gold:'🌟 ወርቃማ',blue:'💙 ሰማያዊ',green:'💚 አረንጓዴ',purple:'💜 ወይን'};

function applyTheme(name,fontSize){
  const t=THEMES[name]||THEMES.gold;
  const r=document.documentElement;
  Object.entries(t).forEach(([k,v])=>r.style.setProperty(k,v));
  r.style.setProperty('--font',fontSize+'px');
  r.style.setProperty('--font-size',fontSize+'px');
  document.documentElement.style.fontSize=fontSize+'px';
}

// ===== TOAST =====
function Toast({msg,type}){return msg?<div className={`toast${type==='err'?' err':''}`}>{msg}</div>:null;}

// ===== SPLASH =====
function Splash({onDone}){
  const[hide,setHide]=useState(false);
  useEffect(()=>{
    const t=setTimeout(()=>{setHide(true);setTimeout(onDone,900);},2500);
    return()=>clearTimeout(t);
  },[]);
  return(
    <div className={`splash${hide?' hide':''}`}>
      <div className="splash-arabic">إِنْ شَاءَ اللَّه</div>
      <div className="splash-arabic2">مَا شَاءَ اللَّه</div>
      <div className="splash-logo">🏺</div>
      <div className="splash-title">ሴኒያ ቢዝነስ</div>
      <div className="splash-sub">የሸቀጥ መደብር አስተዳዳሪ</div>
      <div className="splash-bar"><div className="splash-fill"/></div>
    </div>
  );
}

// ===== PIN PAD =====
function PinPad({onSuccess,onCancel,title,subtitle,getPin}){
  const[pin,setPin]=useState('');
  const[err,setErr]=useState('');

  const press=(d)=>{
    if(pin.length>=4)return;
    const next=pin+d;
    setPin(next);setErr('');
    if(next.length===4){
      setTimeout(()=>{
        const correct=getPin();
        if(next===correct){onSuccess(next);}
        else{setErr('❌ ስህተት ቁጥር! እንደገና ሞክር');setPin('');}
      },200);
    }
  };
  const del=()=>{setPin(p=>p.slice(0,-1));setErr('');};

  return(
    <div className="pin-screen">
      <div className="pin-box">
        <div className="pin-title">{title||'👑 ባለቤት መግቢያ'}</div>
        <div className="pin-sub">{subtitle||'4-ዲጂት ሚስጥር ቁጥር ያስገቡ'}</div>
        <div className="pin-dots">
          {[0,1,2,3].map(i=><div key={i} className={`pin-dot${i<pin.length?' filled':''}`}/>)}
        </div>
        <div className="pin-grid">
          {[1,2,3,4,5,6,7,8,9].map(n=>(
            <div key={n} className="pin-key" onClick={()=>press(String(n))}>{n}</div>
          ))}
          <div className="pin-key del" onClick={onCancel}>✕</div>
          <div className="pin-key zero" onClick={()=>press('0')}>0</div>
          <div className="pin-key del" onClick={del}>⌫</div>
        </div>
        <div className="pin-err">{err}</div>
      </div>
    </div>
  );
}

// ===== PIN CHANGE MODAL =====
function PinChangeModal({onClose,showToast}){
  const[step,setStep]=useState('old'); // old | new1 | new2
  const[newPin,setNewPin]=useState('');

  return(
    <div className="pin-change-modal">
      {step==='old'&&(
        <div className="pin-change-box">
          <PinPad
            title="🔑 የቀድሞ ቢን"
            subtitle="የወቅቱን PIN ያስገቡ"
            getPin={()=>DB.get('ownerPin')||'2026'}
            onSuccess={()=>setStep('new1')}
            onCancel={onClose}
          />
        </div>
      )}
      {step==='new1'&&(
        <div className="pin-change-box">
          <div className="pin-box">
            <div className="pin-title">🔐 አዲስ PIN</div>
            <div className="pin-sub">አዲሱን 4-ዲጂት PIN ያስገቡ</div>
            <div style={{display:'flex',justifyContent:'center',gap:14,margin:'20px 0'}}>
              {[0,1,2,3].map(i=><div key={i} className={`pin-dot${i<0?' filled':''}`}/>)}
            </div>
            <div className="pin-grid">
              {[1,2,3,4,5,6,7,8,9].map(n=>(
                <div key={n} className="pin-key" onClick={()=>{
                  const next=newPin+String(n);
                  if(next.length<=4){setNewPin(next);if(next.length===4)setTimeout(()=>setStep('new2'),200);}
                }}>{n}</div>
              ))}
              <div className="pin-key del" onClick={onClose}>✕</div>
              <div className="pin-key zero" onClick={()=>{
                const next=newPin+'0';if(next.length<=4){setNewPin(next);if(next.length===4)setTimeout(()=>setStep('new2'),200);}
              }}>0</div>
              <div className="pin-key del" onClick={()=>setNewPin(p=>p.slice(0,-1))}>⌫</div>
            </div>
            <div style={{display:'flex',justifyContent:'center',gap:14,marginTop:16}}>
              {[0,1,2,3].map(i=><div key={i} className={`pin-dot${i<newPin.length?' filled':''}`}/>)}
            </div>
          </div>
        </div>
      )}
      {step==='new2'&&(
        <div className="pin-change-box">
          <PinPad
            title="✅ PIN አረጋግጥ"
            subtitle="አዲሱን PIN ደግሞ ያስገቡ"
            getPin={()=>newPin}
            onSuccess={(confirmed)=>{
              DB.set('ownerPin',confirmed);
              showToast('PIN ተቀይሯል ✓');
              onClose();
            }}
            onCancel={()=>{setStep('new1');setNewPin('');}}
          />
        </div>
      )}
    </div>
  );
}

// ===== ROLE SELECT =====
function RoleSelect({onSelect}){
  const[showPin,setShowPin]=useState(false);
  return(
    <div className="role-screen">
      {showPin&&(
        <PinPad
          getPin={()=>DB.get('ownerPin')||'2026'}
          onSuccess={()=>onSelect('owner')}
          onCancel={()=>setShowPin(false)}
        />
      )}
      <div style={{textAlign:'center',marginBottom:36}}>
        <div style={{width:80,height:80,borderRadius:24,background:'linear-gradient(135deg,var(--gold),var(--gold3))',display:'flex',alignItems:'center',justifyContent:'center',fontSize:38,margin:'0 auto 16px',boxShadow:'0 0 48px rgba(232,184,75,0.3)'}}>🏺</div>
        <div style={{fontSize:26,fontWeight:800,color:'var(--gold2)'}}>ሴኒያ ቢዝነስ</div>
        <div style={{fontSize:15,color:'var(--muted)',marginTop:6}}>እርስዎ ማን ነዎት?</div>
      </div>
      <div className="role-card" onClick={()=>setShowPin(true)}>
        <div className="role-card-icon">👑</div>
        <div className="role-card-title">ባለቤት / አስተዳዳሪ</div>
        <div className="role-card-desc">ሁሉንም ሪፖርቶች፣ ትርፍ፣ ሰራተኞችን እና ሙሉ ስርዓቱን ያያሉ</div>
      </div>
      <div className="role-card" onClick={()=>onSelect('worker')}>
        <div className="role-card-icon">🧑‍💼</div>
        <div className="role-card-title">ሰራተኛ</div>
        <div className="role-card-desc">ሽያጭ ይመዘግባሉ እና አዲስ ዕቃ ማስገባት ይችላሉ</div>
      </div>
    </div>
  );
}

// ===== SETTINGS PANEL =====
function SettingsPanel({settings,onSettingsChange,showToast}){
  const[showPinChange,setShowPinChange]=useState(false);

  const handleFont=(e)=>{
    const fs=Number(e.target.value);
    onSettingsChange({...settings,fontSize:fs});
    applyTheme(settings.theme,fs);
  };
  const handleTheme=(th)=>{
    onSettingsChange({...settings,theme:th});
    applyTheme(th,settings.fontSize);
  };

  return(
    <div>
      {showPinChange&&<PinChangeModal onClose={()=>setShowPinChange(false)} showToast={showToast}/>}
      <div className="settings-panel">
        <div className="settings-title">⚙️ ቅንጅቶች</div>

        <div className="field">
          <label className="lbl">📝 የፊደል መጠን — {settings.fontSize}px</label>
          <div className="slider-wrap">
            <span style={{fontSize:12,color:'var(--muted)'}}>ትንሽ</span>
            <input type="range" min="14" max="22" step="1" value={settings.fontSize} onChange={handleFont}/>
            <span style={{fontSize:12,color:'var(--muted)'}}>ትልቅ</span>
          </div>
          <div style={{fontSize:settings.fontSize,color:'var(--gold2)',textAlign:'center',padding:'8px',background:'var(--card2)',borderRadius:10,marginTop:6}}>ሴኒያ ቢዝነስ — ናሙና ፊደል</div>
        </div>

        <div className="field">
          <label className="lbl">🎨 ቀለም ምረጥ</label>
          <div className="color-swatches">
            {Object.entries(THEMES).map(([key,th])=>(
              <div key={key} className={`swatch${settings.theme===key?' active':''}`}
                style={{background:`linear-gradient(135deg,${th['--gold']},${th['--gold3']})`}}
                onClick={()=>handleTheme(key)} title={THEME_LABELS[key]}/>
            ))}
          </div>
          <div style={{display:'flex',gap:8,marginTop:10,flexWrap:'wrap'}}>
            {Object.entries(THEME_LABELS).map(([key,label])=>(
              <button key={key} onClick={()=>handleTheme(key)}
                style={{padding:'7px 14px',borderRadius:22,border:`1.5px solid ${settings.theme===key?'var(--gold)':'var(--border)'}`,background:settings.theme===key?'var(--card2)':'transparent',color:settings.theme===key?'var(--gold2)':'var(--muted)',fontFamily:'inherit',fontSize:13,cursor:'pointer',fontWeight:settings.theme===key?800:400}}>
                {label}
              </button>
            ))}
          </div>
        </div>
      </div>

      <div className="settings-panel">
        <div className="settings-title">🔐 ደህንነት</div>
        <p style={{fontSize:14,color:'var(--muted)',marginBottom:16,lineHeight:1.7}}>ባለቤቱ PIN ቁጥሩን ከዚህ ሊቀይሩ ይችላሉ። PIN ቁጥሩ ደህና ቦታ ያስቀምጡ።</p>
        <button className="btn btn-secondary" onClick={()=>setShowPinChange(true)} style={{fontSize:15}}>🔑 PIN ቁጥር ቀይር</button>
      </div>

      <div className="settings-panel">
        <div className="settings-title">☁️ ደመና ማመሳሰያ (Cloud Sync)</div>
        {FIREBASE_URL
          ? <p style={{fontSize:14,color:'var(--green)',lineHeight:1.7}}>✅ Firebase ተያይዟል። ኢንተርኔት ሲኖር መረጃ ወዲያውኑ ወደ ደመና ይሄዳል።</p>
          : <p style={{fontSize:14,color:'var(--muted)',lineHeight:1.7}}>⚠️ Firebase URL አልተቀናበረም። ኮዱ ውስጥ <strong style={{color:'var(--gold2)'}}>FIREBASE_URL</strong> ቦታ ላይ የ Firebase ሊንክዎን ያስገቡ።</p>
        }
        <div style={{marginTop:12,fontSize:13,color:'var(--muted)'}}>
          {(DB.get('syncQueue')||[]).length>0
            ? `📤 ${(DB.get('syncQueue')||[]).length} ያልተላኩ ሪከርዶች በመጠባበቅ ላይ`
            : '✅ ሁሉም ተሰናድቷል'
          }
        </div>
      </div>

      <div className="settings-panel">
        <div className="settings-title">ℹ️ ስለ አፑ</div>
        <div style={{fontSize:14,color:'var(--muted)',lineHeight:1.9}}>
          <div>📱 ሴኒያ ቢዝነስ v2.0</div>
          <div>🌐 ሙሉ በሙሉ ኦፍላይን ይሰራል</div>
          <div>💾 ሁሉም ዳታ ስልክ ላይ ደህና ነው</div>
          <div>🔄 ኮዱ ሲቀየር ዳታ አይጠፋም</div>
        </div>
      </div>
    </div>
  );
}

// ===== MAIN APP =====
function App(){
  const savedSettings=DB.get('appSettings')||{fontSize:18,theme:'gold'};
  const[splash,setSplash]=useState(true);
  const[role,setRole]=useState(null);
  const[tab,setTab]=useState('dashboard');
  const[toast,setToast]=useState(null);
  const[online,setOnline]=useState(navigator.onLine);
  const[settings,setSettings]=useState(savedSettings);
  const[data,setData]=useState({
    sales:DB.get('sales')||[],
    products:DB.get('products')||[],
    debts:DB.get('debts')||[],
    expenses:DB.get('expenses')||[],
    damages:DB.get('damages')||[],
    preorders:DB.get('preorders')||[],
    customers:DB.get('customers')||[],
    transport:DB.get('transport')||[],
    returns:DB.get('returns')||[],
    workers:DB.get('workers')||[],
  });

  useEffect(()=>{applyTheme(savedSettings.theme,savedSettings.fontSize);},[]);

  useEffect(()=>{
    const on=()=>{
      setOnline(true);
      // Flush offline queue when back online
      SyncManager.flushQueue();
    };
    const off=()=>setOnline(false);
    window.addEventListener('online',on);
    window.addEventListener('offline',off);
    return()=>{window.removeEventListener('online',on);window.removeEventListener('offline',off);};
  },[]);

  const save=(key,val)=>{
    DB.set(key,val);
    setData(d=>({...d,[key]:val}));
    // Sync to cloud if online
    if(navigator.onLine){
      SyncManager.saveToCloud(key,val);
    } else {
      SyncManager.addToQueue({key,value:val});
    }
  };

  const handleSettingsChange=(newS)=>{
    setSettings(newS);
    DB.set('appSettings',newS);
  };

  const showToast=(msg,type='ok')=>{
    setToast({msg,type});
    setTimeout(()=>setToast(null),2800);
  };

  if(splash)return<Splash onDone={()=>setSplash(false)}/>;
  if(!role)return<RoleSelect onSelect={(r)=>{setRole(r);setTab(r==='owner'?'dashboard':'sale');}}/>;

  const ownerTabs=[
    {id:'dashboard',icon:'📊',label:'ዳሽቦርድ'},
    {id:'sale',icon:'💰',label:'ሽያጭ'},
    {id:'inventory',icon:'📦',label:'ዕቃ'},
    {id:'debts',icon:'📋',label:'ዱቤ'},
    {id:'more',icon:'⚙️',label:'ተጨማሪ'},
  ];
  const workerTabs=[
    {id:'sale',icon:'💰',label:'ሽያጭ'},
    {id:'inventory',icon:'📦',label:'ዕቃ'},
  ];
  const tabs=role==='owner'?ownerTabs:workerTabs;
  const activeTab=tabs.find(t=>t.id===tab)?tab:tabs[0].id;

  return(
    <div className="app">
      {toast&&<Toast msg={toast.msg} type={toast.type}/>}
      <div className="header">
        <div className="header-top">
          <div className="logo-box">🏺</div>
          <div>
            <div className="header-title">ሴኒያ ቢዝነስ</div>
            <div className="header-arabic">إِنْ شَاءَ اللَّه · مَا شَاءَ اللَّه</div>
          </div>
          <div className="header-right">
            <div className="header-role">{role==='owner'?'👑 ባለቤት':'🧑‍💼 ሰራተኛ'}</div>
            <span className={online?'online-badge':'offline-badge'}>{online?'● Online':'● Offline'}</span>
          </div>
        </div>
      </div>

      <div className="content">
        {activeTab==='dashboard'&&role==='owner'&&<Dashboard data={data} save={save} showToast={showToast} settings={settings} onSettingsChange={handleSettingsChange}/>}
        {activeTab==='sale'&&<SalePage data={data} save={save} showToast={showToast} role={role}/>}
        {activeTab==='inventory'&&<Inventory data={data} save={save} showToast={showToast} role={role}/>}
        {activeTab==='debts'&&role==='owner'&&<Debts data={data} save={save} showToast={showToast}/>}
        {activeTab==='more'&&role==='owner'&&<More data={data} save={save} showToast={showToast} settings={settings} onSettingsChange={handleSettingsChange}/>}
      </div>

      <div className="bottom-nav">
        {tabs.map(t=>(
          <button key={t.id} className={`nav-btn${activeTab===t.id?' active':''}`} onClick={()=>setTab(t.id)}>
            <span className="nav-icon">{t.icon}</span>
            <span className="nav-label">{t.label}</span>
            {activeTab===t.id&&<div className="nav-dot"/>}
          </button>
        ))}
        <button className="nav-btn" onClick={()=>setRole(null)}>
          <span className="nav-icon">🔄</span>
          <span className="nav-label">ቀይር</span>
        </button>
      </div>
    </div>
  );
}

// ===== DASHBOARD =====
function Dashboard({data,save,showToast,settings,onSettingsChange}){
  const todaySales=data.sales.filter(s=>s.date===today()&&s.method!=='ዱቤ').reduce((s,x)=>s+x.total,0);
  const todayDebt=data.sales.filter(s=>s.date===today()&&s.method==='ዱቤ').reduce((s,x)=>s+x.total,0);
  const totalExpenses=data.expenses.filter(e=>e.date===today()).reduce((s,x)=>s+x.amount,0);
  const totalDamages=data.damages.reduce((s,x)=>s+(x.qty*(x.cost||0)),0);
  const outstanding=data.debts.reduce((s,d)=>s+(d.total-d.paid),0);
  const lowStock=data.products.filter(p=>p.qty<=5);
  const todayProfit=data.sales.filter(s=>s.date===today()).reduce((s,x)=>s+(x.total-(x.cost||0)*x.qty),0)-totalExpenses;

  const days=['ሰ','ማ','እ','ሐ','አ','ቅ','እ'];
  const weekSales=Array(7).fill(0).map((_,i)=>{
    const d=new Date();d.setDate(d.getDate()-6+i);
    const dk=d.toISOString().slice(0,10);
    return data.sales.filter(s=>s.date===dk&&s.method!=='ዱቤ').reduce((s,x)=>s+x.total,0);
  });
  const maxW=Math.max(...weekSales,1);

  // Top selling products this week
  const weekProducts=data.sales
    .filter(s=>{const d=new Date();d.setDate(d.getDate()-7);return s.date>=d.toISOString().slice(0,10);})
    .reduce((acc,s)=>{
      if(!acc[s.product])acc[s.product]={name:s.product,qty:0,total:0};
      acc[s.product].qty+=s.qty;acc[s.product].total+=s.total;
      return acc;
    },{});
  const topWeek=Object.values(weekProducts).sort((a,b)=>b.qty-a.qty).slice(0,3);

  return(
    <div>
      <div style={{textAlign:'center',padding:'10px 0 16px',borderBottom:'1px solid var(--border)',marginBottom:16}}>
        <div style={{fontSize:20,color:'var(--gold2)',direction:'rtl',letterSpacing:3}}>بِسْمِ اللَّه الرَّحْمَنِ الرَّحِيم</div>
        <div style={{fontSize:13,color:'var(--muted)',marginTop:5}}>ዛሬ · {new Date().toLocaleDateString('am')} · {nowTime()}</div>
      </div>

      <div className="stats-grid">
        {[
          {icon:'💵',val:fmt(todaySales),label:'ዛሬ ሽያጭ',color:'var(--green)'},
          {icon:'📈',val:fmt(todayProfit),label:'ዛሬ ትርፍ',color:'var(--gold2)'},
          {icon:'💸',val:fmt(outstanding),label:'ያልተሰበሰበ ዱቤ',color:'var(--red)'},
          {icon:'📦',val:data.products.reduce((s,p)=>s+p.qty,0)+' ፍሬ',label:'ዕቃ ክምችት',color:'var(--blue)'},
        ].map((s,i)=>(
          <div key={i} className="stat-card">
            <div className="stat-icon">{s.icon}</div>
            <div className="stat-val" style={{color:s.color}}>{s.val}</div>
            <div className="stat-label">{s.label}</div>
          </div>
        ))}
      </div>

      <div className="card" style={{marginBottom:12}}>
        <div className="card-title">📊 የሳምንቱ ሽያጭ</div>
        <div className="chart-bar-wrap">
          {weekSales.map((v,i)=>(
            <div key={i} style={{flex:1,display:'flex',flexDirection:'column',alignItems:'center'}}>
              <div className="chart-bar" style={{width:'100%',height:(v/maxW)*100+'px',background:i===6?`linear-gradient(var(--gold2),var(--gold3))`:`linear-gradient(var(--blue),#2563eb)`}}/>
              <div className="chart-label">{days[i]}</div>
            </div>
          ))}
        </div>
      </div>

      {topWeek.length>0&&(
        <div className="card" style={{marginBottom:12}}>
          <div className="card-title">🔥 ሳምንቱ ቀዳሚ ሸቁጦች</div>
          {topWeek.map((p,i)=>(
            <div key={p.name} style={{display:'flex',alignItems:'center',gap:12,padding:'9px 0',borderBottom:'1px solid var(--border)'}}>
              <div style={{width:28,height:28,borderRadius:9,background:i===0?'var(--gold)':i===1?'var(--card3)':'var(--card2)',color:i===0?'#000':'var(--muted)',display:'flex',alignItems:'center',justifyContent:'center',fontWeight:800,fontSize:13}}>{i+1}</div>
              <div style={{flex:1}}><div style={{fontSize:15,fontWeight:700}}>{p.name}</div><div style={{fontSize:12,color:'var(--muted)'}}>{p.qty} ፍሬ ተሸጧል</div></div>
              <div style={{fontWeight:800,color:'var(--gold2)',fontSize:14}}>{fmt(p.total)}</div>
            </div>
          ))}
        </div>
      )}

      {lowStock.length>0&&(
        <div className="alert alert-gold" style={{marginBottom:12}}>
          <div style={{fontSize:15,fontWeight:800,color:'var(--gold2)',marginBottom:8}}>⚠️ ዕቃ እያለቀ ነው ({lowStock.length})</div>
          {lowStock.map(p=><div key={p.id} style={{fontSize:14,color:'#fbbf24',marginBottom:2}}>• {p.name} — {p.qty} ፍሬ ቀርቷል</div>)}
        </div>
      )}

      {data.preorders.filter(p=>!p.fulfilled).length>0&&(
        <div className="alert alert-blue" style={{marginBottom:12}}>
          <div style={{fontSize:15,fontWeight:800,color:'#93c5fd',marginBottom:8}}>🔖 ቅድሚያ ትዕዛዞች ({data.preorders.filter(p=>!p.fulfilled).length})</div>
          {data.preorders.filter(p=>!p.fulfilled).slice(0,3).map(p=><div key={p.id} style={{fontSize:13,color:'#bfdbfe',marginBottom:2}}>• {p.customerName} — {p.item} ({fmt(p.deposit)} ቀድሞ)</div>)}
        </div>
      )}

      {data.debts.filter(d=>(d.total-d.paid)>0&&d.dueDate<today()).length>0&&(
        <div className="alert alert-red" style={{marginBottom:12}}>
          <div style={{fontSize:15,fontWeight:800,color:'#fca5a5',marginBottom:8}}>⏰ ቀን ያለፈ ዱቤዎች</div>
          {data.debts.filter(d=>(d.total-d.paid)>0&&d.dueDate<today()).map(d=><div key={d.id} style={{fontSize:13,color:'#fca5a5',marginBottom:2}}>• {d.name} — {fmt(d.total-d.paid)}</div>)}
        </div>
      )}

      <div className="card">
        <div className="card-title">ዛሬ ማጠቃለያ</div>
        {[
          ['ዛሬ ጠቅላላ ሽያጭ',fmt(todaySales+todayDebt),'var(--text)'],
          ['ወጪ',fmt(totalExpenses),'var(--red)'],
          ['ዱቤ ሽያጭ',fmt(todayDebt),'var(--blue)'],
          ['ሰበራ / ኪሳራ',fmt(totalDamages),'var(--red)'],
          ['ተጣራ ትርፍ',fmt(Math.max(0,todayProfit)),'var(--green)'],
        ].map(([l,v,c],i)=>(
          <div key={i} style={{display:'flex',justifyContent:'space-between',padding:'10px 0',borderBottom:'1px solid var(--border)'}}>
            <span style={{fontSize:15,color:'var(--muted)'}}>{l}</span>
            <span style={{fontSize:15,fontWeight:800,color:c}}>{v}</span>
          </div>
        ))}
      </div>

      <div style={{marginTop:14}}>
        <SettingsPanel settings={settings} onSettingsChange={onSettingsChange} showToast={()=>{}}/>
      </div>
    </div>
  );
}

// ===== PROFESSIONAL RECEIPT =====
function Receipt({receipt,onClose}){
  const printReceipt=()=>{
    const w=window.open('','_blank','width=400,height=600');
    w.document.write(`
      <!DOCTYPE html><html><head>
      <meta charset="UTF-8">
      <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Ethiopic:wght@400;700;800&display=swap" rel="stylesheet">
      <style>
        body{font-family:'Noto Sans Ethiopic',monospace;font-size:14px;margin:0;padding:16px;background:#fff;color:#111;max-width:320px;}
        .center{text-align:center;}
        .bold{font-weight:800;}
        .row{display:flex;justify-content:space-between;padding:5px 0;border-bottom:1px dotted #ccc;}
        .total-row{display:flex;justify-content:space-between;padding:10px 0;font-size:18px;font-weight:800;border-top:2px solid #111;border-bottom:2px solid #111;margin:8px 0;}
        .divider{border-top:1px dashed #bbb;margin:10px 0;}
        .footer{text-align:center;margin-top:16px;font-size:12px;color:#888;}
      </style></head><body>
      <div class="center">
        <div style="font-size:28px;margin-bottom:4px">🏺</div>
        <div class="bold" style="font-size:20px">ሴኒያ ቢዝነስ</div>
        <div style="font-size:12px;color:#666">የሸቀጥ መደብር</div>
        <div style="font-size:11px;color:#999">${receipt.date} ${receipt.time}</div>
      </div>
      <div class="divider"></div>
      <div class="row"><span>ዕቃ</span><span class="bold">${receipt.product}</span></div>
      <div class="row"><span>ብዛት</span><span>${receipt.qty} ፍሬ</span></div>
      <div class="row"><span>የዩኒት ዋጋ</span><span>${receipt.unitPrice} ብር</span></div>
      ${receipt.discountAmt>0?`<div class="row"><span>ቅናሽ</span><span style="color:red">- ${receipt.discountAmt} ብር</span></div>`:''}
      <div class="row"><span>ክፍያ</span><span>${receipt.method}</span></div>
      <div class="row"><span>ሰራተኛ</span><span>${receipt.worker}</span></div>
      <div class="total-row"><span>ጠቅላላ</span><span>${receipt.total.toLocaleString()} ብር</span></div>
      <div class="footer">
        <div style="direction:rtl;font-size:14px">شُكْرًا لَكَ</div>
        <div>አመሰግናለሁ — ደህና ይምጡ!</div>
        <div style="margin-top:8px;font-size:10px">ደረሰኝ #${receipt.id}</div>
      </div>
      </body></html>
    `);
    w.document.close();
    setTimeout(()=>w.print(),500);
  };

  return(
    <div>
      <div className="receipt-print" style={{marginBottom:14,borderRadius:18,border:'1px solid var(--border)',overflow:'hidden'}}>
        <div style={{background:'var(--card)',padding:'20px 18px'}}>
          <div style={{textAlign:'center',marginBottom:16}}>
            <div style={{fontSize:36,marginBottom:6}}>🏺</div>
            <div style={{fontSize:22,fontWeight:800,color:'var(--gold2)'}}>ሴኒያ ቢዝነስ</div>
            <div style={{fontSize:13,color:'var(--muted)',marginTop:4}}>ደረሰኝ #{receipt.id}</div>
            <div style={{fontSize:13,color:'var(--muted)'}}>{receipt.date} · {receipt.time}</div>
          </div>

          <hr style={{border:'none',borderTop:'1px dashed var(--border)',margin:'12px 0'}}/>

          {[
            ['🛍 ዕቃ',receipt.product],
            ['📦 ብዛት',receipt.qty+' ፍሬ'],
            ['💵 የዩኒት ዋጋ',receipt.unitPrice+' ብር'],
            ...(receipt.discountAmt>0?[['🎁 ቅናሽ','- '+fmt(receipt.discountAmt)]]:[] ),
            ['💳 ክፍያ ዓይነት',receipt.method],
            ['🧑‍💼 ሰራተኛ',receipt.worker],
          ].map(([l,v],i)=>(
            <div key={i} style={{display:'flex',justifyContent:'space-between',padding:'9px 0',borderBottom:'1px solid var(--border)'}}>
              <span style={{fontSize:15,color:'var(--muted)'}}>{l}</span>
              <span style={{fontSize:15,fontWeight:700}}>{v}</span>
            </div>
          ))}

          <div style={{display:'flex',justifyContent:'space-between',padding:'14px 0',background:'var(--card2)',borderRadius:12,margin:'10px -4px 0',padding:'14px 14px'}}>
            <span style={{fontSize:17,fontWeight:800,color:'var(--gold2)'}}>ጠቅላላ</span>
            <span style={{fontSize:22,fontWeight:800,color:'var(--gold2)'}}>{fmt(receipt.total)}</span>
          </div>

          <div style={{marginTop:14,padding:14,background:'var(--card2)',borderRadius:12,fontSize:14,color:'var(--muted)',direction:'rtl',textAlign:'center'}}>شُكْرًا لَكَ — አመሰግናለሁ</div>
        </div>
      </div>

      <div style={{display:'flex',gap:10}}>
        <button className="btn btn-gold" onClick={printReceipt} style={{flex:1,fontSize:15}}>🖨 ፕሪንት</button>
        <button className="btn btn-secondary" onClick={onClose} style={{flex:1,fontSize:15}}>+ አዲስ ሽያጭ</button>
      </div>
    </div>
  );
}

// ===== SALE PAGE =====
function SalePage({data,save,showToast,role}){
  const[selProduct,setSelProduct]=useState(null);
  const[qty,setQty]=useState(1);
  const[method,setMethod]=useState('ካሽ');
  const[discount,setDiscount]=useState(0);
  const[debtName,setDebtName]=useState('');
  const[debtPhone,setDebtPhone]=useState('');
  const[dueDate,setDueDate]=useState('');
  const[worker,setWorker]=useState('ባለቤት');
  const[gps,setGps]=useState(null);
  const[voiceMemo,setVoiceMemo]=useState('');
  const[receipt,setReceipt]=useState(null);

  const prod=data.products.find(p=>p.id===selProduct);
  const baseTotal=prod?(prod.price*qty):0;
  const discountAmt=discount>0?Math.round(baseTotal*(discount/100)):0;
  const total=baseTotal-discountAmt;

  const getGps=()=>{
    if(navigator.geolocation){
      navigator.geolocation.getCurrentPosition(
        pos=>{setGps({lat:pos.coords.latitude.toFixed(4),lng:pos.coords.longitude.toFixed(4)});showToast('📍 አካባቢ ቀዷል!');},
        ()=>showToast('GPS አልተሰራም','err')
      );
    }
  };

  const recordSale=()=>{
    if(!prod){showToast('ዕቃ ምረጥ!','err');return;}
    if(qty>prod.qty){showToast('ዕቃ በቂ አይደለም!','err');return;}
    if(method==='ዱቤ'&&!debtName){showToast('ደንበኛ ስም ፃፍ!','err');return;}

    const saleId=Date.now();
    const sale={
      id:saleId,product:prod.name,productId:prod.id,
      qty,total,cost:prod.cost,
      method,discount,discountAmt,
      date:today(),time:nowTime(),
      worker,gps,voiceMemo,
    };
    save('sales',[...data.sales,sale]);
    save('products',data.products.map(p=>p.id===prod.id?{...p,qty:p.qty-qty}:p));

    if(method==='ዱቤ'){
      save('debts',[...data.debts,{id:saleId+1,name:debtName,phone:debtPhone,item:prod.name,qty,total,paid:0,dueDate,date:today()}]);
    }

    setReceipt({id:saleId,product:prod.name,qty,total,discountAmt,method,date:today(),time:nowTime(),worker,unitPrice:prod.price});
    setSelProduct(null);setQty(1);setDiscount(0);setDebtName('');setDebtPhone('');setDueDate('');setVoiceMemo('');setGps(null);
    showToast('ሽያጭ ተመዝግቧል ✓ '+fmt(total));
  };

  if(receipt){
    return <Receipt receipt={receipt} onClose={()=>setReceipt(null)}/>;
  }

  return(
    <div>
      <div style={{display:'flex',alignItems:'center',justifyContent:'space-between',marginBottom:14}}>
        <div style={{fontSize:17,fontWeight:800,color:'var(--gold2)'}}>💰 ሽያጭ ምዝገባ</div>
      </div>

      <div className="card">
        <div className="field">
          <label className="lbl">ዕቃ ምረጥ</label>
          <select className="inp" value={selProduct||''} onChange={e=>setSelProduct(Number(e.target.value))}>
            <option value="">— ዕቃ ምረጥ —</option>
            {data.products.map(p=><option key={p.id} value={p.id}>{p.name} ({p.qty} ፍሬ) — {fmt(p.price)}</option>)}
          </select>
        </div>

        <div className="field">
          <label className="lbl">ብዛት</label>
          <div style={{display:'flex',alignItems:'center',gap:16}}>
            <button style={{width:44,height:44,borderRadius:12,background:'var(--card2)',border:'1px solid var(--border)',color:'var(--text)',fontSize:24,cursor:'pointer',flexShrink:0}} onClick={()=>setQty(q=>Math.max(1,q-1))}>−</button>
            <span style={{fontSize:24,fontWeight:800,minWidth:36,textAlign:'center'}}>{qty}</span>
            <button style={{width:44,height:44,borderRadius:12,background:'var(--card2)',border:'1px solid var(--border)',color:'var(--text)',fontSize:24,cursor:'pointer',flexShrink:0}} onClick={()=>setQty(q=>prod?Math.min(prod.qty,q+1):q+1)}>+</button>
          </div>
        </div>

        <div className="field">
          <label className="lbl">ቅናሽ %</label>
          <input className="inp" type="number" placeholder="0" min="0" max="100" value={discount} onChange={e=>setDiscount(Number(e.target.value))}/>
        </div>

        <div style={{background:'var(--card2)',borderRadius:14,padding:'14px 18px',marginBottom:16,display:'flex',justifyContent:'space-between',alignItems:'center',border:'1px solid var(--border)'}}>
          <div>
            <div style={{fontSize:13,color:'var(--muted)'}}>ጠቅላላ</div>
            {discountAmt>0&&<div style={{fontSize:13,color:'var(--red)',textDecoration:'line-through'}}>{fmt(baseTotal)}</div>}
          </div>
          <div style={{fontSize:26,fontWeight:800,color:'var(--gold2)'}}>{fmt(total)}</div>
        </div>

        <div className="field">
          <label className="lbl">የክፍያ ዓይነት</label>
          <div style={{display:'flex',gap:8}}>
            {['ካሽ','ባንክ','ዱቤ'].map(m=>(
              <button key={m} onClick={()=>setMethod(m)} style={{flex:1,padding:'12px 0',borderRadius:12,border:`1.5px solid ${method===m?(m==='ዱቤ'?'var(--red)':'var(--gold)'):'var(--border)'}`,background:method===m?(m==='ዱቤ'?'#2e0a0a':'#2a1200'):'var(--card2)',color:method===m?(m==='ዱቤ'?'#fca5a5':'var(--gold2)'):'var(--muted)',fontFamily:'inherit',fontSize:15,fontWeight:700,cursor:'pointer'}}>
                {m==='ካሽ'?'💵 ካሽ':m==='ባንክ'?'🏦 ባንክ':'📋 ዱቤ'}
              </button>
            ))}
          </div>
        </div>

        {method==='ዱቤ'&&(
          <div style={{background:'#1e0808',border:'1px solid rgba(240,80,80,0.25)',borderRadius:14,padding:14,marginBottom:16}}>
            <div style={{fontSize:14,fontWeight:800,color:'var(--red)',marginBottom:12}}>📋 የዱቤ ዝርዝር</div>
            <div className="field"><label className="lbl">ደንበኛ ስም</label><input className="inp" placeholder="ስም" value={debtName} onChange={e=>setDebtName(e.target.value)}/></div>
            <div className="field"><label className="lbl">ስልክ</label><input className="inp" type="tel" placeholder="09..." value={debtPhone} onChange={e=>setDebtPhone(e.target.value)}/></div>
            <div className="field"><label className="lbl">የቀጠሮ ቀን</label><input className="inp" type="date" value={dueDate} onChange={e=>setDueDate(e.target.value)}/></div>
          </div>
        )}

        <div className="field">
          <label className="lbl">ሰራተኛ</label>
          <select className="inp" value={worker} onChange={e=>setWorker(e.target.value)}>
            <option>ባለቤት</option>
            {data.workers.map(w=><option key={w.id}>{w.name}</option>)}
          </select>
        </div>

        <div style={{display:'flex',alignItems:'center',gap:10,marginBottom:16}}>
          <button onClick={getGps} style={{background:'var(--card2)',border:'1px solid var(--border)',borderRadius:12,padding:'10px 16px',color:gps?'var(--green)':'var(--muted)',fontSize:14,cursor:'pointer',fontFamily:'inherit',fontWeight:600}}>
            {gps?<><span className="gps-dot"/>አካባቢ ቀዷል</>:'📍 GPS ቅዳ'}
          </button>
          {gps&&<span style={{fontSize:12,color:'var(--muted)'}}>{gps.lat}, {gps.lng}</span>}
        </div>

        <div className="field">
          <label className="lbl">🎙 ማስታወሻ</label>
          <input className="inp" placeholder="ዝርዝር ጻፍ..." value={voiceMemo} onChange={e=>setVoiceMemo(e.target.value)}/>
        </div>

        <button className="btn btn-gold" onClick={recordSale}>✓ ሽያጭ ምዝገባ</button>
      </div>

      <div style={{marginTop:16}}>
        <div style={{fontSize:15,fontWeight:700,color:'var(--muted)',marginBottom:10}}>የቅርብ ሽያጮች</div>
        {data.sales.slice(-5).reverse().map(s=>(
          <div key={s.id} className="list-item">
            <div className="list-item-img">📦</div>
            <div style={{flex:1}}>
              <div style={{fontWeight:700,fontSize:15}}>{s.product}</div>
              <div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{s.qty} ፍሬ · {s.method} · {s.worker} · {s.time}</div>
              {s.gps&&<div style={{fontSize:12,color:'var(--green)',marginTop:2}}>📍 {s.gps.lat},{s.gps.lng}</div>}
            </div>
            <div style={{fontWeight:800,color:s.method==='ዱቤ'?'var(--red)':s.method==='ባንክ'?'var(--blue)':'var(--green)',fontSize:14}}>{fmt(s.total)}</div>
          </div>
        ))}
        {data.sales.length===0&&<div style={{textAlign:'center',color:'var(--muted)',padding:40,fontSize:15}}>ሽያጭ አልተመዘገበም</div>}
      </div>
    </div>
  );
}

// ===== INVENTORY =====
function Inventory({data,save,showToast,role}){
  const[search,setSearch]=useState('');
  const[showAdd,setShowAdd]=useState(false);
  const[form,setForm]=useState({name:'',price:'',cost:'',qty:'',category:'ሸክላ',image:null});
  const fileRef=useRef();

  const filtered=data.products.filter(p=>p.name.includes(search)||p.category.includes(search));

  const handleImg=(e)=>{
    const f=e.target.files[0];if(!f)return;
    const r=new FileReader();
    r.onload=()=>setForm(prev=>({...prev,image:r.result}));
    r.readAsDataURL(f);
  };

  const addProduct=()=>{
    if(!form.name||!form.price||!form.qty){showToast('ሁሉ ሙሉ!','err');return;}
    const p={id:Date.now(),...form,price:parseFloat(form.price),cost:parseFloat(form.cost||0),qty:parseInt(form.qty)};
    save('products',[...data.products,p]);
    setForm({name:'',price:'',cost:'',qty:'',category:'ሸክላ',image:null});
    setShowAdd(false);showToast('ዕቃ ተመዝግቧል ✓');
  };

  return(
    <div>
      <div style={{display:'flex',alignItems:'center',justifyContent:'space-between',marginBottom:12}}>
        <div style={{fontSize:16,fontWeight:800,color:'var(--gold2)'}}>📦 ዕቃዎች ({data.products.length})</div>
        <button className="btn btn-gold btn-sm" onClick={()=>setShowAdd(!showAdd)}>{showAdd?'✕ ዝጋ':'+ አዲስ'}</button>
      </div>

      <input className="inp" style={{marginBottom:12}} placeholder="🔍 ዕቃ ፈልግ..." value={search} onChange={e=>setSearch(e.target.value)}/>

      {showAdd&&(
        <div className="card" style={{marginBottom:14,border:'1px solid rgba(232,184,75,0.25)'}}>
          <div style={{fontSize:15,fontWeight:800,color:'var(--gold2)',marginBottom:14}}>አዲስ ዕቃ ምዝገባ</div>
          <div onClick={()=>fileRef.current.click()} style={{height:100,background:'var(--card2)',border:'2px dashed var(--border)',borderRadius:14,display:'flex',alignItems:'center',justifyContent:'center',cursor:'pointer',marginBottom:14,overflow:'hidden'}}>
            {form.image?<img src={form.image} style={{width:'100%',height:'100%',objectFit:'cover'}}/>:<div style={{textAlign:'center',color:'var(--muted)'}}><div style={{fontSize:32}}>📷</div><div style={{fontSize:13,marginTop:4}}>ፎቶ ጨምር</div></div>}
          </div>
          <input ref={fileRef} type="file" accept="image/*" capture="environment" style={{display:'none'}} onChange={handleImg}/>
          {[['ስም','name','text','ሸክላ ድስት'],['ዋጋ (ብር)','price','number','200'],['መግዣ ዋጋ','cost','number','120'],['ብዛት','qty','number','10']].map(([l,k,t,ph])=>(
            <div className="field" key={k}><label className="lbl">{l}</label><input className="inp" type={t} placeholder={ph} value={form[k]} onChange={e=>setForm(f=>({...f,[k]:e.target.value}))}/></div>
          ))}
          <div className="field">
            <label className="lbl">ዓይነት</label>
            <input className="inp" value={form.category} onChange={e=>setForm(f=>({...f,category:e.target.value}))} placeholder="ሸክላ፣ ሰፌድ..."/>
          </div>
          <button className="btn btn-gold" onClick={addProduct}>✓ ምዝገባ</button>
        </div>
      )}

      {filtered.map(p=>(
        <div key={p.id} className="list-item" style={{border:`1px solid ${p.qty<=5?'rgba(232,184,75,0.3)':'var(--border)'}`}}>
          <div className="list-item-img">{p.image?<img src={p.image}/>:'📦'}</div>
          <div style={{flex:1}}>
            <div style={{fontWeight:800,fontSize:16}}>{p.name}</div>
            <div style={{fontSize:12,color:'var(--muted)',marginTop:2}}>{p.category}</div>
            <div style={{display:'flex',gap:10,marginTop:5,flexWrap:'wrap'}}>
              <span style={{fontSize:14,fontWeight:800,color:'var(--green)'}}>{fmt(p.price)}</span>
              {role==='owner'&&<span style={{fontSize:12,color:'var(--muted)'}}>ዋጋ:{fmt(p.cost)}</span>}
              <span style={{fontSize:13,color:p.qty<=5?'var(--gold)':'var(--muted)',fontWeight:p.qty<=5?800:400}}>{p.qty} ፍሬ{p.qty<=5?' ⚠️':''}</span>
            </div>
            {role==='owner'&&<div style={{fontSize:12,color:'var(--blue)',marginTop:3}}>ትርፍ: {fmt(p.price-p.cost)} ({Math.round(((p.price-p.cost)/p.price)*100)}%)</div>}
          </div>
          {role==='owner'&&<button onClick={()=>{save('products',data.products.filter(x=>x.id!==p.id));showToast('ዕቃ ተሰርዟል');}} style={{background:'#2e0a0a',border:'none',borderRadius:10,width:36,height:36,cursor:'pointer',color:'var(--red)',fontSize:15}}>🗑</button>}
        </div>
      ))}
      {filtered.length===0&&<div style={{textAlign:'center',color:'var(--muted)',padding:40,fontSize:15}}>ዕቃ አልተገኘም</div>}
    </div>
  );
}

// ===== DEBTS =====
function Debts({data,save,showToast}){
  const[payId,setPayId]=useState(null);
  const[payAmt,setPayAmt]=useState('');

  const pay=()=>{
    const amt=parseFloat(payAmt);
    if(!amt||amt<=0){showToast('ብር ፃፍ!','err');return;}
    const debt=data.debts.find(d=>d.id===payId);
    if(!debt)return;
    const rem=debt.total-debt.paid;
    if(amt>rem){showToast('ከዕዳ በላይ!','err');return;}
    save('debts',data.debts.map(d=>d.id===payId?{...d,paid:d.paid+amt}:d).filter(d=>d.total-d.paid>0.01));
    setPayId(null);setPayAmt('');
    showToast(fmt(amt)+' ተሰብስቧል ✓');
  };

  const activeDebts=data.debts.filter(d=>(d.total-d.paid)>0);
  const total=activeDebts.reduce((s,d)=>s+(d.total-d.paid),0);

  return(
    <div>
      <div style={{background:'#1e0808',border:'1px solid rgba(240,80,80,0.25)',borderRadius:var(--radius-sm)||16,padding:16,marginBottom:14,display:'flex',justifyContent:'space-between',alignItems:'center'}}>
        <span style={{fontSize:15,color:'var(--muted)'}}>ጠቅላላ ዕዳ</span>
        <span style={{fontSize:22,fontWeight:800,color:'var(--red)'}}>{fmt(total)}</span>
      </div>
      {activeDebts.length===0&&<div style={{textAlign:'center',color:'var(--muted)',padding:60}}><div style={{fontSize:56,marginBottom:14}}>🎉</div><div style={{fontSize:18}}>ዱቤ የለም!</div></div>}
      {activeDebts.map(d=>{
        const rem=d.total-d.paid;
        const pct=(d.paid/d.total)*100;
        const overdue=d.dueDate&&d.dueDate<today();
        return(
          <div key={d.id} className="card" style={{marginBottom:12,border:`1px solid ${overdue?'rgba(240,80,80,0.35)':'var(--border)'}`}}>
            <div style={{display:'flex',justifyContent:'space-between',alignItems:'flex-start',marginBottom:10}}>
              <div>
                <div style={{fontWeight:800,fontSize:17,display:'flex',alignItems:'center',gap:8}}>
                  {d.name}
                  {overdue&&<span className="badge badge-red">ዘግይቷል</span>}
                </div>
                <div style={{fontSize:13,color:'var(--muted)',marginTop:3}}>{d.phone} · {d.item} x{d.qty}</div>
                {d.dueDate&&<div style={{fontSize:12,color:'var(--muted)',marginTop:2}}>ቀጠሮ: {d.dueDate}</div>}
              </div>
              <div style={{fontWeight:800,color:'var(--gold2)',fontSize:16}}>{fmt(d.total)}</div>
            </div>
            <div className="progress-bar"><div className="progress-fill" style={{width:pct+'%'}}/></div>
            <div style={{display:'flex',justifyContent:'space-between',marginBottom:12}}>
              <span style={{fontSize:13,fontWeight:700,color:'var(--green)'}}>የተሰበሰበ: {fmt(d.paid)}</span>
              <span style={{fontSize:13,fontWeight:700,color:'var(--red)'}}>ቀሪ: {fmt(rem)}</span>
            </div>
            <button className="btn btn-green" style={{fontSize:15}} onClick={()=>{setPayId(d.id);setPayAmt('');}}>💵 ክፍያ ተቀበል</button>
          </div>
        );
      })}
      {payId&&(
        <div style={{position:'fixed',inset:0,background:'rgba(0,0,0,0.85)',zIndex:500,display:'flex',alignItems:'flex-end',backdropFilter:'blur(4px)'}}>
          <div style={{background:'var(--card)',width:'100%',maxWidth:480,margin:'0 auto',borderRadius:'22px 22px 0 0',padding:28,boxShadow:'0 -8px 40px rgba(0,0,0,0.5)'}}>
            <div style={{fontWeight:800,fontSize:18,marginBottom:6}}>💵 ክፍያ ተቀበል</div>
            <div style={{fontSize:14,color:'var(--muted)',marginBottom:18}}>ቀሪ: {fmt((data.debts.find(d=>d.id===payId)?.total||0)-(data.debts.find(d=>d.id===payId)?.paid||0))}</div>
            <input className="inp" type="number" placeholder="ብር..." value={payAmt} onChange={e=>setPayAmt(e.target.value)} style={{fontSize:20,fontWeight:800,marginBottom:18}} autoFocus/>
            <div style={{display:'flex',gap:10}}>
              <button onClick={()=>setPayId(null)} className="btn btn-secondary" style={{flex:1,fontSize:15}}>ይቅር</button>
              <button onClick={pay} className="btn btn-green" style={{flex:2,fontSize:16}}>✓ ተቀበልኩ</button>
            </div>
          </div>
        </div>
      )}
    </div>
  );
}

// ===== MORE TAB =====
function More({data,save,showToast,settings,onSettingsChange}){
  const[subTab,setSubTab]=useState('expenses');
  const subTabs=[
    {id:'expenses',label:'💸 ወጪ'},
    {id:'damages',label:'🏺 ሰበራ'},
    {id:'transport',label:'🚚 ትራንስፖርት'},
    {id:'preorders',label:'🔖 ቅድሚያ'},
    {id:'returns',label:'↩️ መልስ'},
    {id:'customers',label:'👥 ደንበኞች'},
    {id:'report',label:'📈 ሪፖርት'},
    {id:'workers',label:'🧑‍💼 ሰራተኞች'},
    {id:'settings',label:'⚙️ ቅንጅቶች'},
  ];
  return(
    <div>
      <div className="sub-tab-scroll">
        {subTabs.map(t=>(
          <button key={t.id} className={`sub-tab-btn${subTab===t.id?' active':''}`} onClick={()=>setSubTab(t.id)}>{t.label}</button>
        ))}
      </div>
      {subTab==='expenses'&&<ExpensesTab data={data} save={save} showToast={showToast}/>}
      {subTab==='damages'&&<DamagesTab data={data} save={save} showToast={showToast}/>}
      {subTab==='transport'&&<TransportTab data={data} save={save} showToast={showToast}/>}
      {subTab==='preorders'&&<PreordersTab data={data} save={save} showToast={showToast}/>}
      {subTab==='returns'&&<ReturnsTab data={data} save={save} showToast={showToast}/>}
      {subTab==='customers'&&<CustomersTab data={data} save={save} showToast={showToast}/>}
      {subTab==='report'&&<ReportTab data={data}/>}
      {subTab==='workers'&&<WorkersTab data={data} save={save} showToast={showToast}/>}
      {subTab==='settings'&&<SettingsPanel settings={settings} onSettingsChange={onSettingsChange} showToast={showToast}/>}
    </div>
  );
}

// ===== EXPENSES =====
function ExpensesTab({data,save,showToast}){
  const[form,setForm]=useState({desc:'',amount:'',category:'ምግብ'});
  const cats=['ምግብ','ሻይ ቡና','ትምህርት','ትራንስፖርት','ሌላ'];
  const add=()=>{
    if(!form.desc||!form.amount){showToast('ሁሉ ሙሉ!','err');return;}
    save('expenses',[...data.expenses,{id:Date.now(),...form,amount:parseFloat(form.amount),date:today()}]);
    setForm({desc:'',amount:'',category:'ምግብ'});showToast('ወጪ ተመዝግቧል ✓');
  };
  const todayTotal=data.expenses.filter(e=>e.date===today()).reduce((s,x)=>s+x.amount,0);
  return(
    <div>
      <div className="card" style={{marginBottom:12}}>
        <div className="field"><label className="lbl">ዝርዝር</label><input className="inp" placeholder="ምን ወጪ?" value={form.desc} onChange={e=>setForm(f=>({...f,desc:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ብር</label><input className="inp" type="number" placeholder="ወጪ ብር" value={form.amount} onChange={e=>setForm(f=>({...f,amount:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ዓይነት</label><select className="inp" value={form.category} onChange={e=>setForm(f=>({...f,category:e.target.value}))}>{cats.map(c=><option key={c}>{c}</option>)}</select></div>
        <button className="btn btn-gold" onClick={add}>+ ወጪ ምዝገባ</button>
      </div>
      <div style={{display:'flex',justifyContent:'space-between',marginBottom:12,padding:'0 4px'}}>
        <span style={{fontSize:15,color:'var(--muted)'}}>ዛሬ ጠቅላላ ወጪ</span>
        <span style={{fontWeight:800,color:'var(--red)',fontSize:16}}>{fmt(todayTotal)}</span>
      </div>
      {data.expenses.slice(-10).reverse().map(e=>(
        <div key={e.id} className="list-item">
          <div className="list-item-img" style={{fontSize:22}}>💸</div>
          <div style={{flex:1}}><div style={{fontWeight:700,fontSize:15}}>{e.desc}</div><div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{e.category} · {e.date}</div></div>
          <div style={{fontWeight:800,color:'var(--red)',fontSize:15}}>{fmt(e.amount)}</div>
        </div>
      ))}
    </div>
  );
}

// ===== DAMAGES =====
function DamagesTab({data,save,showToast}){
  const[form,setForm]=useState({item:'',qty:'',reason:'ጭነት ላይ ተሰበረ',cost:''});
  const add=()=>{
    if(!form.item||!form.qty){showToast('ሙሉ!','err');return;}
    save('damages',[...data.damages,{id:Date.now(),...form,qty:parseInt(form.qty),cost:parseFloat(form.cost||0),date:today()}]);
    setForm({item:'',qty:'',reason:'ጭነት ላይ ተሰበረ',cost:''});showToast('ሰበራ ተመዝግቧል');
  };
  return(
    <div>
      <div className="card" style={{marginBottom:12,border:'1px solid rgba(240,80,80,0.2)'}}>
        <div style={{fontSize:15,fontWeight:800,color:'var(--red)',marginBottom:12}}>🏺 ሰበራ / ብልሽት ምዝገባ</div>
        <div className="field"><label className="lbl">ዕቃ ስም</label><input className="inp" placeholder="ሸክላ ድስት..." value={form.item} onChange={e=>setForm(f=>({...f,item:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ብዛት</label><input className="inp" type="number" value={form.qty} onChange={e=>setForm(f=>({...f,qty:e.target.value}))}/></div>
        <div className="field"><label className="lbl">የዕቃ ዋጋ</label><input className="inp" type="number" value={form.cost} onChange={e=>setForm(f=>({...f,cost:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ምክንያት</label><select className="inp" value={form.reason} onChange={e=>setForm(f=>({...f,reason:e.target.value}))}>{['ጭነት ላይ ተሰበረ','ሽያጭ ወቅት','ሌሎች'].map(r=><option key={r}>{r}</option>)}</select></div>
        <button className="btn btn-red" onClick={add}>ሰበራ ምዝገባ</button>
      </div>
      {data.damages.slice(-8).reverse().map(d=>(
        <div key={d.id} className="list-item">
          <div className="list-item-img">💔</div>
          <div style={{flex:1}}><div style={{fontWeight:700,fontSize:15}}>{d.item} x{d.qty}</div><div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{d.reason} · {d.date}</div></div>
          <div style={{fontWeight:800,color:'var(--red)',fontSize:14}}>{fmt(d.cost*d.qty)}</div>
        </div>
      ))}
    </div>
  );
}

// ===== TRANSPORT =====
function TransportTab({data,save,showToast}){
  const[form,setForm]=useState({from:'ወልቂጤ',to:'ቡሌ ሆራ',vehicle:'ኢሱዙ',cost:'',date:today(),items:''});
  const add=()=>{
    if(!form.cost){showToast('ወጪ ፃፍ!','err');return;}
    save('transport',[...data.transport,{id:Date.now(),...form,cost:parseFloat(form.cost)}]);
    setForm({from:'ወልቂጤ',to:'ቡሌ ሆራ',vehicle:'ኢሱዙ',cost:'',date:today(),items:''});showToast('ትራንስፖርት ተመዝግቧል ✓');
  };
  return(
    <div>
      <div className="card" style={{marginBottom:12}}>
        <div className="field"><label className="lbl">ከ</label><input className="inp" value={form.from} onChange={e=>setForm(f=>({...f,from:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ወደ</label><input className="inp" value={form.to} onChange={e=>setForm(f=>({...f,to:e.target.value}))}/></div>
        <div className="field"><label className="lbl">መኪና</label><select className="inp" value={form.vehicle} onChange={e=>setForm(f=>({...f,vehicle:e.target.value}))}>{['ኢሱዙ','ሚኒ','ሌላ'].map(v=><option key={v}>{v}</option>)}</select></div>
        <div className="field"><label className="lbl">ወጪ (ብር)</label><input className="inp" type="number" value={form.cost} onChange={e=>setForm(f=>({...f,cost:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ዕቃዎች</label><input className="inp" placeholder="ምን ዕቃ?" value={form.items} onChange={e=>setForm(f=>({...f,items:e.target.value}))}/></div>
        <button className="btn btn-gold" onClick={add}>+ ትራንስፖርት ምዝገባ</button>
      </div>
      {data.transport.slice(-6).reverse().map(t=>(
        <div key={t.id} className="list-item">
          <div className="list-item-img">🚚</div>
          <div style={{flex:1}}><div style={{fontWeight:700,fontSize:15}}>{t.from} → {t.to}</div><div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{t.vehicle} · {t.items} · {t.date}</div></div>
          <div style={{fontWeight:800,color:'var(--red)',fontSize:15}}>{fmt(t.cost)}</div>
        </div>
      ))}
    </div>
  );
}

// ===== PREORDERS =====
function PreordersTab({data,save,showToast}){
  const[form,setForm]=useState({customerName:'',phone:'',item:'',qty:'',deposit:'',expectedDate:''});
  const add=()=>{
    if(!form.customerName||!form.item){showToast('ሙሉ!','err');return;}
    save('preorders',[...data.preorders,{id:Date.now(),...form,qty:parseInt(form.qty||1),deposit:parseFloat(form.deposit||0),fulfilled:false,date:today()}]);
    setForm({customerName:'',phone:'',item:'',qty:'',deposit:'',expectedDate:''});showToast('ቅድሚያ ትዕዛዝ ✓');
  };
  return(
    <div>
      <div className="card" style={{marginBottom:12,border:'1px solid rgba(96,165,250,0.2)'}}>
        <div style={{fontSize:15,fontWeight:800,color:'var(--blue)',marginBottom:12}}>🔖 ቅድሚያ ትዕዛዝ</div>
        <div className="field"><label className="lbl">ደንበኛ ስም</label><input className="inp" value={form.customerName} onChange={e=>setForm(f=>({...f,customerName:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ስልክ</label><input className="inp" type="tel" value={form.phone} onChange={e=>setForm(f=>({...f,phone:e.target.value}))}/></div>
        <div className="field"><label className="lbl">የፈለጉት ዕቃ</label><input className="inp" value={form.item} onChange={e=>setForm(f=>({...f,item:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ብዛት</label><input className="inp" type="number" value={form.qty} onChange={e=>setForm(f=>({...f,qty:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ቅድሚያ ክፍያ (ብር)</label><input className="inp" type="number" value={form.deposit} onChange={e=>setForm(f=>({...f,deposit:e.target.value}))}/></div>
        <div className="field"><label className="lbl">እቃ የሚደርስበት ቀን</label><input className="inp" type="date" value={form.expectedDate} onChange={e=>setForm(f=>({...f,expectedDate:e.target.value}))}/></div>
        <button className="btn btn-gold" onClick={add}>+ ምዝገባ</button>
      </div>
      {data.preorders.map(p=>(
        <div key={p.id} className="list-item">
          <div className="list-item-img">🔖</div>
          <div style={{flex:1}}>
            <div style={{fontWeight:700,fontSize:15}}>{p.customerName} — {p.item} x{p.qty}</div>
            <div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{p.phone} · ቅድሚያ: {fmt(p.deposit)}</div>
            {p.expectedDate&&<div style={{fontSize:12,color:'var(--blue)',marginTop:2}}>ይደርሳል: {p.expectedDate}</div>}
          </div>
          <button onClick={()=>save('preorders',data.preorders.map(x=>x.id===p.id?{...x,fulfilled:!x.fulfilled}:x))} style={{background:p.fulfilled?'#0d3d1d':'var(--card2)',border:'none',borderRadius:10,padding:'8px 12px',color:p.fulfilled?'#86efac':'var(--muted)',cursor:'pointer',fontSize:13,fontFamily:'inherit',fontWeight:700}}>{p.fulfilled?'✓ ተፈፀመ':'ምዝገባ'}</button>
        </div>
      ))}
    </div>
  );
}

// ===== RETURNS =====
function ReturnsTab({data,save,showToast}){
  const[form,setForm]=useState({customerName:'',item:'',qty:'',reason:'ተበላሽቷል',refundAmt:''});
  const add=()=>{
    if(!form.customerName||!form.item){showToast('ሙሉ!','err');return;}
    save('returns',[...data.returns,{id:Date.now(),...form,qty:parseInt(form.qty||1),refundAmt:parseFloat(form.refundAmt||0),date:today()}]);
    setForm({customerName:'',item:'',qty:'',reason:'ተበላሽቷል',refundAmt:''});showToast('ተመላሽ ተመዝግቧል');
  };
  return(
    <div>
      <div className="card" style={{marginBottom:12}}>
        <div style={{fontSize:15,fontWeight:800,color:'var(--gold2)',marginBottom:12}}>↩️ ተመላሽ ዕቃ</div>
        <div className="field"><label className="lbl">ደንበኛ ስም</label><input className="inp" value={form.customerName} onChange={e=>setForm(f=>({...f,customerName:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ዕቃ</label><input className="inp" value={form.item} onChange={e=>setForm(f=>({...f,item:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ብዛት</label><input className="inp" type="number" value={form.qty} onChange={e=>setForm(f=>({...f,qty:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ምክንያት</label><select className="inp" value={form.reason} onChange={e=>setForm(f=>({...f,reason:e.target.value}))}>{['ተበላሽቷል','አልፈለኩትም','ሌላ'].map(r=><option key={r}>{r}</option>)}</select></div>
        <div className="field"><label className="lbl">ተመላሽ ብር</label><input className="inp" type="number" value={form.refundAmt} onChange={e=>setForm(f=>({...f,refundAmt:e.target.value}))}/></div>
        <button className="btn btn-gold" onClick={add}>+ ምዝገባ</button>
      </div>
      {data.returns.map(r=>(
        <div key={r.id} className="list-item">
          <div className="list-item-img">↩️</div>
          <div style={{flex:1}}><div style={{fontWeight:700,fontSize:15}}>{r.customerName} — {r.item}</div><div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{r.reason} · {r.date}</div></div>
          <div style={{fontWeight:800,color:'var(--red)',fontSize:14}}>{fmt(r.refundAmt)}</div>
        </div>
      ))}
    </div>
  );
}

// ===== CUSTOMERS =====
function CustomersTab({data,save,showToast}){
  const[form,setForm]=useState({name:'',phone:'',address:''});
  const add=()=>{
    if(!form.name){showToast('ስም ፃፍ!','err');return;}
    save('customers',[...data.customers,{id:Date.now(),...form,date:today()}]);
    setForm({name:'',phone:'',address:''});showToast('ደንበኛ ተመዝግቧል ✓');
  };
  return(
    <div>
      <div className="card" style={{marginBottom:12}}>
        <div className="field"><label className="lbl">ስም</label><input className="inp" value={form.name} onChange={e=>setForm(f=>({...f,name:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ስልክ</label><input className="inp" type="tel" value={form.phone} onChange={e=>setForm(f=>({...f,phone:e.target.value}))}/></div>
        <div className="field"><label className="lbl">አድራሻ</label><input className="inp" value={form.address} onChange={e=>setForm(f=>({...f,address:e.target.value}))}/></div>
        <button className="btn btn-gold" onClick={add}>+ ደንበኛ ምዝገባ</button>
      </div>
      {data.customers.map(c=>(
        <div key={c.id} className="list-item">
          <div className="list-item-img">👤</div>
          <div style={{flex:1}}><div style={{fontWeight:700,fontSize:15}}>{c.name}</div><div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{c.phone} · {c.address}</div></div>
        </div>
      ))}
    </div>
  );
}

// ===== REPORT =====
function ReportTab({data}){
  const totalRevenue=data.sales.filter(s=>s.method!=='ዱቤ').reduce((s,x)=>s+x.total,0);
  const totalCost=data.sales.reduce((s,x)=>s+(x.cost||0)*x.qty,0);
  const totalExpenses=data.expenses.reduce((s,x)=>s+x.amount,0);
  const totalTransport=data.transport.reduce((s,x)=>s+x.cost,0);
  const totalDamages=data.damages.reduce((s,x)=>s+x.qty*(x.cost||0),0);
  const totalProfit=totalRevenue-totalCost-totalExpenses-totalTransport-totalDamages;

  const byWorker={};
  data.sales.forEach(s=>{
    if(!byWorker[s.worker])byWorker[s.worker]={count:0,total:0};
    byWorker[s.worker].count++;byWorker[s.worker].total+=s.total;
  });

  const topProducts=Object.values(data.sales.reduce((acc,s)=>{
    if(!acc[s.product])acc[s.product]={name:s.product,qty:0,total:0};
    acc[s.product].qty+=s.qty;acc[s.product].total+=s.total;
    return acc;
  },{})).sort((a,b)=>b.total-a.total);

  // Monthly trend (last 6 months)
  const monthlyData=Array(6).fill(0).map((_,i)=>{
    const d=new Date();d.setMonth(d.getMonth()-5+i);
    const ym=d.toISOString().slice(0,7);
    const val=data.sales.filter(s=>s.date.startsWith(ym)&&s.method!=='ዱቤ').reduce((s,x)=>s+x.total,0);
    return {month:d.toLocaleDateString('am',{month:'short'}),val};
  });
  const maxM=Math.max(...monthlyData.map(m=>m.val),1);

  return(
    <div>
      <div className="card" style={{marginBottom:12}}>
        <div className="card-title">💰 ጠቅላላ ሂሳብ</div>
        {[
          ['ጠቅላላ ሽያጭ',fmt(totalRevenue),'var(--gold2)'],
          ['የዕቃ ዋጋ',fmt(totalCost),'var(--red)'],
          ['ወጪዎች',fmt(totalExpenses),'var(--red)'],
          ['ትራንስፖርት',fmt(totalTransport),'var(--red)'],
          ['ሰበራ ኪሳራ',fmt(totalDamages),'var(--red)'],
          ['ተጣራ ትርፍ',fmt(Math.max(0,totalProfit)),'var(--green)'],
        ].map(([l,v,c],i)=>(
          <div key={i} style={{display:'flex',justifyContent:'space-between',padding:'11px 0',borderBottom:'1px solid var(--border)'}}>
            <span style={{fontSize:15,color:'var(--muted)'}}>{l}</span>
            <span style={{fontSize:15,fontWeight:800,color:c}}>{v}</span>
          </div>
        ))}
      </div>

      <div className="card" style={{marginBottom:12}}>
        <div className="card-title">📊 ወርሃዊ ሽያጭ</div>
        <div className="chart-bar-wrap">
          {monthlyData.map((m,i)=>(
            <div key={i} style={{flex:1,display:'flex',flexDirection:'column',alignItems:'center'}}>
              <div className="chart-bar" style={{width:'100%',height:(m.val/maxM)*100+'px',background:i===5?`linear-gradient(var(--gold2),var(--gold3))`:`linear-gradient(var(--blue),#2563eb)`}}/>
              <div className="chart-label">{m.month}</div>
            </div>
          ))}
        </div>
      </div>

      <div className="card" style={{marginBottom:12}}>
        <div className="card-title">🏆 ቀዳሚ ሸቁጦች (ሁሉ ጊዜ)</div>
        {topProducts.slice(0,5).map((p,i)=>(
          <div key={p.name} style={{display:'flex',alignItems:'center',gap:12,padding:'10px 0',borderBottom:'1px solid var(--border)'}}>
            <div style={{width:28,height:28,borderRadius:9,background:i===0?'var(--gold)':i===1?'#aaa':i===2?'#b87333':'var(--card2)',color:i<3?'#000':'var(--muted)',display:'flex',alignItems:'center',justifyContent:'center',fontWeight:800,fontSize:13}}>{i+1}</div>
            <div style={{flex:1}}><div style={{fontSize:15,fontWeight:700}}>{p.name}</div><div style={{fontSize:13,color:'var(--muted)'}}>{p.qty} ፍሬ ተሸጧል</div></div>
            <div style={{fontWeight:800,color:'var(--gold2)',fontSize:15}}>{fmt(p.total)}</div>
          </div>
        ))}
        {topProducts.length===0&&<div style={{color:'var(--muted)',fontSize:15,textAlign:'center',padding:24}}>ሽያጭ አልተጀመረም</div>}
      </div>

      <div className="card">
        <div className="card-title">🧑‍💼 በሰራተኛ</div>
        {Object.entries(byWorker).map(([name,v])=>(
          <div key={name} style={{display:'flex',justifyContent:'space-between',padding:'10px 0',borderBottom:'1px solid var(--border)'}}>
            <div><div style={{fontSize:15,fontWeight:700}}>{name}</div><div style={{fontSize:13,color:'var(--muted)'}}>{v.count} ሽያጭ</div></div>
            <div style={{fontWeight:800,color:'var(--gold2)',fontSize:15,alignSelf:'center'}}>{fmt(v.total)}</div>
          </div>
        ))}
        {Object.keys(byWorker).length===0&&<div style={{color:'var(--muted)',fontSize:15,textAlign:'center',padding:24}}>ሽያጭ አልተጀመረም</div>}
      </div>
    </div>
  );
}

// ===== WORKERS =====
function WorkersTab({data,save,showToast}){
  const[form,setForm]=useState({name:'',phone:''});
  const add=()=>{
    if(!form.name){showToast('ስም ፃፍ!','err');return;}
    save('workers',[...data.workers,{id:Date.now(),...form,role:'worker'}]);
    setForm({name:'',phone:''});showToast('ሰራተኛ ተመዝግቧል ✓');
  };
  return(
    <div>
      <div className="card" style={{marginBottom:12}}>
        <div className="field"><label className="lbl">ስም</label><input className="inp" value={form.name} onChange={e=>setForm(f=>({...f,name:e.target.value}))}/></div>
        <div className="field"><label className="lbl">ስልክ</label><input className="inp" type="tel" value={form.phone} onChange={e=>setForm(f=>({...f,phone:e.target.value}))}/></div>
        <button className="btn btn-gold" onClick={add}>+ ሰራተኛ ምዝገባ</button>
      </div>
      {data.workers.map(w=>(
        <div key={w.id} className="list-item">
          <div className="list-item-img">🧑‍💼</div>
          <div style={{flex:1}}><div style={{fontWeight:700,fontSize:15}}>{w.name}</div><div style={{fontSize:13,color:'var(--muted)',marginTop:2}}>{w.phone}</div></div>
          <button onClick={()=>{save('workers',data.workers.filter(x=>x.id!==w.id));showToast('ተሰርዟል');}} style={{background:'#2e0a0a',border:'none',borderRadius:10,width:36,height:36,cursor:'pointer',color:'var(--red)',fontSize:16}}>🗑</button>
        </div>
      ))}
    </div>
  );
}

// ===== RENDER =====
const root=ReactDOM.createRoot(document.getElementById('root'));
root.render(<App/>);
</script>
</body>
</html>
