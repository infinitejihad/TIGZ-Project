<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>TI Gadget Zone — Smart Gadgets. Better Life.</title>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@500;600;700;800&family=DM+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#f4f6f3;--bg2:#ffffff;--card:#ffffff;--line:#dfe4dd;--tx:#14201a;--mut:#5e6b63;--gold:#0b6b2e;--gold2:#08561f;--choc:#eaf1e7;--on:#ffffff;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 90px);scroll-behavior:smooth}
*,*:before,*:after{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--tx);font:15px/1.55 'DM Sans',system-ui,sans-serif;overflow-x:hidden}
h1,h2,h3{font-family:'Plus Jakarta Sans',system-ui,sans-serif;font-weight:700;margin:0;line-height:1.12;letter-spacing:-.02em}
a{color:inherit;text-decoration:none}button{font:inherit;cursor:pointer;color:inherit}
:focus-visible{outline:2px solid var(--gold);outline-offset:2px}
.wrap{max-width:1180px;margin:0 auto;padding:0 20px}
.btn{border:0;border-radius:10px;padding:12px 22px;font-weight:600;background:linear-gradient(135deg,var(--gold),var(--gold2));color:var(--on);transition:transform .2s,filter .2s;display:inline-block;text-align:center}
.btn:hover{filter:brightness(1.08);transform:translateY(-1px)}
.btn.ghost{background:transparent;border:1px solid var(--line);color:var(--tx)}
.btn.sm{padding:8px 14px;font-size:13px}.btn.full{width:100%}
.eyebrow{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--gold);font-weight:600}
header{position:sticky;top:0;z-index:30;background:rgba(255,255,255,.92);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
.hd{display:flex;align-items:center;gap:18px;height:68px}
.brand{display:flex;align-items:center;gap:10px;font-family:'Plus Jakarta Sans',sans-serif;font-weight:700;letter-spacing:.04em}
.brand img,.brand svg{height:36px;width:36px;object-fit:contain}
nav.main{display:flex;gap:26px;margin:0 auto;color:var(--mut);font-weight:500}
nav.main a:hover,nav.main a.on{color:var(--tx)}
.hd-r{display:flex;align-items:center;gap:10px}
.search{background:var(--card);border:1px solid var(--line);border-radius:10px;padding:9px 12px;color:var(--tx);width:210px;font:inherit}
.ic{position:relative;background:none;border:0;padding:6px;display:grid;place-items:center}
.ic svg{width:22px;height:22px;stroke:currentColor;fill:none;stroke-width:1.8}
.badge{position:absolute;top:-2px;right:-4px;background:var(--gold);color:var(--on);font-size:11px;font-weight:700;border-radius:99px;min-width:18px;height:18px;display:grid;place-items:center}
section{padding:64px 0}
.hero{position:relative;overflow:hidden;background:linear-gradient(120deg,#e9f0e6,#f6f3ec);border-bottom:1px solid var(--line)}
.slides{position:relative;min-height:520px}
.slide{position:absolute;inset:0;display:grid;grid-template-columns:1.05fr 1fr;align-items:center;gap:30px;opacity:0;visibility:hidden;transition:opacity .7s,visibility .7s}
.slide.on{opacity:1;visibility:visible}
.slide h1{font-size:clamp(38px,5.6vw,68px);margin:14px 0}
.slide p{color:var(--mut);max-width:460px;margin:0 0 18px}
.price{display:flex;align-items:baseline;gap:10px;margin-bottom:22px}
.price b{font-size:28px;color:var(--gold);font-family:'Plus Jakarta Sans',sans-serif}.old{color:var(--mut);text-decoration:line-through}
.sale{background:var(--gold);color:var(--on);font-size:11px;font-weight:700;padding:3px 9px;border-radius:99px}
.art{aspect-ratio:1/1;width:100%;max-width:470px;margin:0 auto;border-radius:28px;background:radial-gradient(circle at 50% 38%,#f4f2ed,#e2dfd8 78%);display:grid;place-items:center;padding:6%}
.art svg{width:100%;height:100%;filter:drop-shadow(0 16px 20px #0003)}
.ctl{position:absolute;bottom:18px;left:0;right:0;display:flex;justify-content:center;align-items:center;gap:14px;z-index:3}
.dot{width:9px;height:9px;border-radius:9px;border:0;background:var(--line);padding:0;transition:width .3s,background .3s}.dot.on{width:26px;background:var(--gold)}
.arr{background:var(--card);border:1px solid var(--line);border-radius:50%;width:36px;height:36px}
.sh{margin-bottom:28px}.sh h2{font-size:clamp(28px,3.6vw,42px);margin-top:8px}.sh p{color:var(--mut);margin:8px 0 0}
.cats{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.cat{background:#fff;border:1px solid var(--line);border-radius:14px;display:flex;overflow:hidden;min-height:150px;transition:transform .25s,border-color .25s}
.cat:hover{transform:translateY(-3px);border-color:var(--gold2)}
.cat .art{border-radius:0;padding:9%;max-width:none;width:44%;aspect-ratio:auto;flex:none}.cat .txt{flex:1;padding:22px;display:flex;flex-direction:column;justify-content:center;gap:6px}
.cat b{font-size:18px;font-family:'Plus Jakarta Sans',sans-serif}.cat span{color:var(--gold);font-weight:600;font-size:14px}.shr{display:flex;justify-content:space-between;align-items:flex-end;gap:12px}.vall{color:var(--gold);font-weight:600;white-space:nowrap}#cats{background:var(--bg);border-bottom:1px solid var(--line)}#col{background:#fff}.btn:disabled{opacity:.5;cursor:default;transform:none}.wrap{max-width:1240px}
.tabs{display:flex;gap:10px;overflow-x:auto;padding-bottom:6px;margin-bottom:26px;scrollbar-width:none}
.tab{white-space:nowrap;background:#fff;border:1px solid var(--line);border-radius:99px;padding:9px 18px;color:var(--mut)}
.tab.on{background:var(--gold);color:var(--on);border-color:var(--gold);font-weight:600}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.pc{background:var(--card);border:1px solid var(--line);border-radius:18px;overflow:hidden;display:flex;flex-direction:column;transition:transform .25s,box-shadow .25s}
.pc:hover{transform:translateY(-4px);box-shadow:0 14px 30px #0006}
.pc .art{border-radius:0;max-width:none;aspect-ratio:4/3.4;position:relative}
.pc .sale{position:absolute;top:12px;left:12px}
.heart{position:absolute;top:10px;right:10px;width:34px;height:34px;border-radius:50%;background:#ffffffdd;border:0;display:grid;place-items:center}
.heart svg{width:18px;height:18px;stroke:var(--tx);fill:none;stroke-width:1.8}.heart.on svg{fill:var(--gold);stroke:var(--gold)}
.pb{padding:16px;display:flex;flex-direction:column;gap:6px;flex:1}
.pb small{color:var(--mut)}.pb h3{font-size:19px}.pb .price{margin:4px 0 10px}.pb .price b{font-size:21px}.pb .btn{margin-top:auto}
.promo{background:linear-gradient(120deg,#e6efe2,#f3efe6);border:1px solid var(--line);border-radius:24px;padding:44px;display:grid;grid-template-columns:1.2fr 1fr;gap:30px;align-items:center}
.promo h2{font-size:clamp(28px,3.4vw,40px);margin:10px 0 18px}
.cta{text-align:center}.cta h2{font-size:clamp(28px,4vw,46px);margin-bottom:12px}.cta p{color:var(--mut);margin:0 auto 22px;max-width:520px}
footer{background:#10261b;color:#fff;--mut:#a9bdb0;--line:#27402f;padding:46px 0 24px;margin-top:40px}
.ft{display:flex;justify-content:space-between;gap:30px;flex-wrap:wrap}.ft p{color:var(--mut);margin:6px 0}
.fl{display:flex;gap:22px;flex-wrap:wrap;color:var(--mut);align-items:flex-start}.fl a:hover{color:#7fd19b}footer .brand svg{filter:brightness(1.7) saturate(1.2)}
.copy{margin-top:30px;padding-top:18px;border-top:1px solid var(--line);color:var(--mut);font-size:13px}
.pd{display:grid;grid-template-columns:1fr 1fr;gap:44px;padding-top:40px}
.pd h1{font-size:clamp(30px,4vw,44px);margin:10px 0}
.sw{display:flex;gap:10px;margin:10px 0 18px;flex-wrap:wrap}
.swb{display:flex;align-items:center;gap:8px;border:1px solid var(--line);background:none;border-radius:99px;padding:6px 14px 6px 8px}.swb.on{border-color:var(--gold)}
.swb i{width:18px;height:18px;border-radius:50%;border:1px solid #fff4}
.qty{display:inline-flex;align-items:center;border:1px solid var(--line);border-radius:10px}.qty button{background:none;border:0;width:38px;height:40px;font-size:18px}.qty span{min-width:30px;text-align:center}
.row{display:flex;gap:12px;flex-wrap:wrap;align-items:center}
ul.ft2{padding-left:18px;color:var(--mut)}
.box{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:22px}
.ci{display:grid;grid-template-columns:76px 1fr auto;gap:14px;align-items:center;padding:14px 0;border-bottom:1px solid var(--line)}
.ci .art{border-radius:10px;padding:8%}
.two{display:grid;grid-template-columns:1.5fr 1fr;gap:26px;align-items:start}
.sum div{display:flex;justify-content:space-between;padding:6px 0;color:var(--mut)}.sum .t{color:var(--tx);font-weight:700;font-size:18px;border-top:1px solid var(--line);margin-top:8px;padding-top:12px}
label{display:block;font-size:13px;color:var(--mut);margin:12px 0 5px}
input,select,textarea{width:100%;background:var(--bg);border:1px solid var(--line);color:var(--tx);border-radius:10px;padding:11px 12px;font:inherit}
.tl{list-style:none;margin:20px 0 0;padding:0}.tl li{display:flex;gap:14px;padding:0 0 22px;position:relative;color:var(--mut)}
.tl li:before{content:"";width:16px;height:16px;border-radius:50%;border:2px solid var(--line);flex:none;background:var(--bg);z-index:1}
.tl li:after{content:"";position:absolute;left:7px;top:18px;bottom:0;width:2px;background:var(--line)}.tl li:last-child:after{display:none}
.tl li.d{color:var(--tx)}.tl li.d:before{background:var(--gold);border-color:var(--gold)}
/* admin */
.adm{display:grid;grid-template-columns:230px 1fr;min-height:100vh;background:var(--bg)}
.side{background:#fff;border-right:1px solid var(--line);padding:20px 14px;display:flex;flex-direction:column;gap:4px;position:sticky;top:0;height:100vh}
.side a{padding:10px 12px;border-radius:10px;color:var(--mut);display:block}.side a.on{background:#e6f0e8;color:var(--gold);font-weight:600}.side a:hover{color:var(--tx)}
.side .sp{flex:1}
.am{padding:22px 30px 50px;min-width:0}
.top{display:flex;justify-content:space-between;align-items:center;color:var(--mut);margin-bottom:24px}
.av{width:34px;height:34px;border-radius:50%;background:var(--gold);color:var(--on);display:grid;place-items:center;font-weight:700}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;margin:22px 0}
.stat b{display:block;font-size:34px;font-family:'Plus Jakarta Sans',sans-serif}.stat span{color:var(--mut)}
.tw{overflow-x:auto}table{width:100%;border-collapse:collapse;min-width:620px}th,td{text-align:left;padding:11px 10px;border-bottom:1px solid var(--line);vertical-align:middle}th{color:var(--mut);font-weight:500;font-size:13px}
td .art{width:46px;padding:6px;border-radius:8px}
.modal{position:fixed;inset:0;background:#0a1a1088;z-index:60;display:grid;place-items:center;padding:16px;animation:f .2s}
.mc{background:var(--bg2);border:1px solid var(--line);border-radius:18px;padding:24px;width:min(560px,100%);max-height:90vh;overflow:auto;animation:u .25s}
@keyframes f{from{opacity:0}}@keyframes u{from{transform:translateY(14px);opacity:0}}
.f2{display:grid;grid-template-columns:1fr 1fr;gap:12px}.chk{display:flex;gap:18px;margin:14px 0}.chk label{display:flex;align-items:center;gap:8px;margin:0;color:var(--tx)}.chk input{width:auto}
.toast{position:fixed;bottom:20px;left:50%;transform:translateX(-50%);background:var(--gold);color:var(--on);padding:10px 18px;border-radius:10px;font-weight:600;z-index:80;animation:u .25s}
.empty{text-align:center;color:var(--mut);padding:40px 0}
@media(max-width:960px){.cats{grid-template-columns:repeat(2,1fr)}.grid{grid-template-columns:repeat(2,1fr)}.stats{grid-template-columns:repeat(2,1fr)}.promo,.two,.pd{grid-template-columns:1fr}}
@media(max-width:760px){.adm{grid-template-columns:1fr}.side{position:static;height:auto;flex-direction:row;flex-wrap:wrap}.side .sp{display:none}.am{padding:18px 14px}
.hd{flex-wrap:wrap;height:auto;padding:10px 0;gap:8px}nav.main{order:3;width:100%;margin:0;justify-content:space-between;gap:10px;font-size:14px}.hd-r{margin-left:auto}.search{width:130px}.brand span{display:none}
.slides{min-height:700px}.slide{grid-template-columns:1fr;align-content:center;padding-bottom:50px;gap:10px}.slide .art{max-width:240px;order:-1}.slide p{display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;overflow:hidden}
section{padding:44px 0}.promo{padding:26px}.f2{grid-template-columns:1fr}}
@media(max-width:560px){.grid{grid-template-columns:repeat(2,1fr);gap:12px}.pb{padding:11px}.pb h3{font-size:15px}.pb .price b{font-size:17px}.cats{grid-template-columns:1fr}.pb .btn{padding:9px 6px;font-size:13px}.stats{grid-template-columns:1fr 1fr}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<div id="app"></div>
<script>
const COL={Black:'#2a2a2e',White:'#ece8e2',Blue:'#3b6fd8',Pink:'#e58ab4',Purple:'#8b5cf6',Green:'#3fa66b',Red:'#d6453d',Gray:'#8a8f98','Mint Green':'#8fdcc0'};
const CATS=[['headphones','Headphones','🎧'],['speakers','Speakers','🔊'],['earbuds','Earbuds & TWS','🎵'],['neckbands','Neckbands','📻'],['accessories','Accessories','⚡']];
const TYPE={headphones:'hp',speakers:'sp',earbuds:'tw',neckbands:'nb',accessories:'ac'};
const slug=s=>s.toLowerCase().replace(/[^a-z0-9]+/g,'-').replace(/^-|-$/g,'');
const mk=(name,category,price,oldPrice,colors,extra={})=>({id:slug(name),name,slug:slug(name),category,price,oldPrice,discount:Math.round((1-price/oldPrice)*100),images:[],colors,description:`${name} brings clear sound and all-day comfort at a price that makes sense. Ready to ship from TI Gadget Zone.`,features:['Bluetooth wireless connection','Rich, balanced sound','Long-lasting battery','Warranty support from TIGZ'],stock:25,featured:false,sale:true,createdAt:Date.now(),...extra});
const DEF={
products:[mk('P9 Pro Max Headphone','headphones',430,599,['Black','White','Blue','Pink'],{featured:true,stock:40}),mk('CAT STN 28 Headphone','headphones',480,799,['Pink','Purple','Green']),mk('JBL 881A Wireless Headphone','headphones',630,1199,['Black','Blue','White'],{featured:true}),mk('P9 Plus Headphone','headphones',480,799,['Blue','Red','Green']),mk('Greatnice Speaker','speakers',480,799,['Gray','Blue','Red','Pink']),mk('K12 Bluetooth Speaker','speakers',480,799,['Blue','Pink','White']),mk('X-922 Speaker','speakers',600,899,['Black','Blue','Mint Green']),mk('Robot Speaker','speakers',600,899,['Black','Pink','Green'],{featured:true}),mk('E9 Pro Earbuds','earbuds',780,1149,['White']),mk('KFG Wireless TWS','earbuds',650,999,['Black']),mk('NAX NX-400 Neckband','neckbands',520,799,['Black'])],
banners:[
{id:'b1',title:'P9 Pro Max Headphone',subtitle:'Wireless sound with deep bass. Four colors, one great price.',image:'',linkedProduct:'p9-pro-max-headphone',buttonText:'Shop now',active:true,order:1},
{id:'b2',title:'Robot Speaker',subtitle:'Big, punchy sound in a compact body that fits any room.',image:'',linkedProduct:'robot-speaker',buttonText:'Shop now',active:true,order:2},
{id:'b3',title:'JBL 881A Wireless Headphone',subtitle:'Comfortable all-day listening, now at nearly half price.',image:'',linkedProduct:'jbl-881a-wireless-headphone',buttonText:'Shop now',active:true,order:3}],
settings:{name:'TI Gadget Zone',tagline:'Smart Gadgets. Better Life.',phone:'',whatsapp:'',email:'',address:'Barishal, Bangladesh',social:'',currency:'৳'},
logos:[],activeLogo:-1,cart:[],orders:[],wish:[]};
let S;try{S=JSON.parse(localStorage.getItem('tigz2'))}catch(e){}S=S||DEF;
const save=()=>{try{localStorage.setItem('tigz2',JSON.stringify(S))}catch(e){}};
const $=s=>document.querySelector(s),money=n=>S.settings.currency+Number(n).toLocaleString('en-US');
const esc=s=>String(s??'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const prod=s=>S.products.find(p=>p.slug===s);
const catName=id=>(CATS.find(c=>c[0]===id)||[0,id])[1];
function svg(t,c){c=c||'#0b6b2e';const d='#0007';return {
hp:`<svg viewBox="0 0 200 200"><path d="M42 124V96a58 58 0 0 1 116 0v28" fill="none" stroke="${c}" stroke-width="13" stroke-linecap="round"/><rect x="28" y="112" width="38" height="62" rx="16" fill="${c}"/><rect x="134" y="112" width="38" height="62" rx="16" fill="${c}"/><rect x="38" y="124" width="18" height="38" rx="9" fill="${d}"/><rect x="144" y="124" width="18" height="38" rx="9" fill="${d}"/></svg>`,
sp:`<svg viewBox="0 0 200 200"><rect x="52" y="26" width="96" height="148" rx="28" fill="${c}"/><circle cx="100" cy="70" r="16" fill="${d}"/><circle cx="100" cy="124" r="30" fill="${d}"/><circle cx="100" cy="124" r="14" fill="#fff3"/></svg>`,
tw:`<svg viewBox="0 0 200 200"><rect x="50" y="86" width="100" height="84" rx="30" fill="${c}"/><path d="M50 118h100" stroke="${d}" stroke-width="4"/><circle cx="76" cy="52" r="20" fill="${c}"/><rect x="68" y="60" width="12" height="40" rx="6" fill="${c}"/><circle cx="124" cy="52" r="20" fill="${c}"/><rect x="120" y="60" width="12" height="40" rx="6" fill="${c}"/></svg>`,
nb:`<svg viewBox="0 0 200 200"><path d="M52 56C44 150 156 150 148 56" fill="none" stroke="${c}" stroke-width="14" stroke-linecap="round"/><circle cx="52" cy="48" r="13" fill="${c}"/><circle cx="148" cy="48" r="13" fill="${c}"/><rect x="82" y="128" width="36" height="22" rx="8" fill="${d}"/></svg>`,
ac:`<svg viewBox="0 0 200 200"><path d="M112 24 56 112h40l-10 64 58-92h-40z" fill="${c}"/></svg>`}[t]||''}
function art(p,c){if(p.images&&p.images[0])return `<div class="art"><img src="${p.images[0]}" alt="${esc(p.name)}" style="width:100%;height:100%;object-fit:contain"></div>`;
const col=COL[c||p.colors[0]]||'#0b6b2e';return `<div class="art" role="img" aria-label="${esc(p.name)}">${svg(TYPE[p.category],col==='#2a2a2e'?'#4a4a52':col)}</div>`}
const heart=(id)=>`<button class="heart ${S.wish.includes(id)?'on':''}" data-a="wish" data-id="${id}" aria-label="Wishlist"><svg viewBox="0 0 24 24"><path d="M12 20s-7-4.4-9-9a5 5 0 0 1 9-3 5 5 0 0 1 9 3c-2 4.6-9 9-9 9z"/></svg></button>`;
function card(p){return `<article class="pc"><a href="#/product/${p.slug}" style="position:relative;display:block">${art(p)}${p.sale?'<span class="sale">SALE</span>':''}</a>${heart(p.id)}<div class="pb"><small>${catName(p.category)}</small><a href="#/product/${p.slug}"><h3>${esc(p.name)}</h3></a><div class="price"><b>${money(p.price)}</b><span class="old">${money(p.oldPrice)}</span></div><button class="btn" data-a="add" data-id="${p.id}">Add to cart</button></div></article>`}
const logoHTML=()=>{const l=S.logos[S.activeLogo];return l?`<img src="${l}" alt="TIGZ logo">`:`<svg viewBox="0 0 40 40"><path d="M14 14v-3a6 6 0 0 1 12 0v3" fill="none" stroke="#0b6b2e" stroke-width="3"/><rect x="5" y="14" width="30" height="22" rx="7" fill="#0b6b2e"/><path d="M13 21h14M20 21v10" stroke="#ffffff" stroke-width="3.2" stroke-linecap="round"/></svg>`};
const cartN=()=>S.cart.reduce((a,i)=>a+i.qty,0);
const ICO={u:'<svg viewBox="0 0 24 24"><circle cx="12" cy="8" r="4"/><path d="M4 21c1-5 15-5 16 0"/></svg>',c:'<svg viewBox="0 0 24 24"><path d="M3 4h3l2.4 11h10l2-8H7"/><circle cx="10" cy="19.5" r="1.4"/><circle cx="17" cy="19.5" r="1.4"/></svg>'};
function header(r){return `<header><div class="wrap hd"><a class="brand" href="#/">${logoHTML()}<span>TI GADGET ZONE</span></a><nav class="main"><a href="#/products" class="${r=='products'?'on':''}">Shop All</a><a href="#/categories">Categories</a><a href="#/featured">Featured</a><a href="#/track">Track order</a></nav><div class="hd-r"><input class="search" id="q" placeholder="Search products" aria-label="Search products"><a class="ic" href="#/admin" aria-label="Account">${ICO.u}</a><a class="ic" href="#/cart" aria-label="Cart">${ICO.c}<span class="badge" id="cn">${cartN()}</span></a></div></div></header>`}
function footer(){return `<footer><div class="wrap"><div class="ft"><div><div class="brand">${logoHTML()}<span>TI GADGET ZONE</span></div><p>${esc(S.settings.tagline)}</p><p>${esc(S.settings.address)} ${S.settings.phone?'· '+esc(S.settings.phone):''}</p></div><div class="fl"><a href="#/products">Shop All</a><a href="#/categories">Categories</a><a href="#/featured">Featured</a><a href="#/contact">Contact</a><a href="#/track">Order Tracking</a></div></div><div class="copy">© TI Gadget Zone. All rights reserved.</div></div></footer>`}
let cur=0,timer;
function hero(){const bs=S.banners.filter(b=>b.active).sort((a,b)=>a.order-b.order);if(!bs.length)return '';
return `<div class="hero"><div class="wrap"><div class="slides" id="sl">${bs.map((b,i)=>{const p=prod(b.linkedProduct)||S.products[0];return `<div class="slide ${i==0?'on':''}"><div><span class="eyebrow">The smart gadget edit</span><h1>${esc(b.title)}</h1><p>${esc(b.subtitle)}</p><div class="price"><b>${money(p.price)}</b><span class="old">${money(p.oldPrice)}</span><span class="sale">SALE −${p.discount}%</span></div><div class="row"><a class="btn" href="#/product/${p.slug}">${esc(b.buttonText)} →</a><button class="btn ghost" data-a="buy" data-id="${p.id}">Buy now</button></div></div>${b.image?`<div class="art"><img src="${b.image}" alt="" style="width:100%;height:100%;object-fit:contain"></div>`:art(p)}</div>`}).join('')}<div class="ctl"><button class="arr" data-a="sl" data-d="-1" aria-label="Previous">‹</button>${bs.map((_,i)=>`<button class="dot ${i==0?'on':''}" data-a="sl" data-i="${i}" aria-label="Slide ${i+1}"></button>`).join('')}<button class="arr" data-a="sl" data-d="1" aria-label="Next">›</button></div></div></div></div>`}
function go(i){const s=[...document.querySelectorAll('.slide')],d=[...document.querySelectorAll('.dot')];if(!s.length)return;cur=(i+s.length)%s.length;s.forEach((e,k)=>e.classList.toggle('on',k==cur));d.forEach((e,k)=>e.classList.toggle('on',k==cur))}
function startAuto(){clearInterval(timer);timer=setInterval(()=>{const h=$('#sl');if(h&&!h.matches(':hover'))go(cur+1)},5000);const h=$('#sl');if(h){let x=0;h.ontouchstart=e=>x=e.touches[0].clientX;h.ontouchend=e=>{const dx=e.changedTouches[0].clientX-x;if(Math.abs(dx)>40){go(cur+(dx<0?1:-1));startAuto()}}}}
let flt='all';
function grid(list){return list.length?`<div class="grid">${list.map(card).join('')}</div>`:'<div class="empty">No products in this category yet.</div>'}
function tabs(){return `<div class="tabs">${[['all','All products'],...CATS.map(c=>[c[0],c[1]])].map(t=>`<button class="tab ${flt==t[0]?'on':''}" data-a="flt" data-id="${t[0]}">${t[1]}</button>`).join('')}</div>`}
const fl=()=>S.products.filter(p=>flt=='all'||p.category==flt);
function home(){const f=S.products.filter(p=>p.featured)[0]||S.products[0];
return hero()+`<section id="cats"><div class="wrap"><div class="sh shr"><div><span class="eyebrow">Discover your next favorite</span><h2>Shop by category</h2></div><a href="#/categories" class="vall">View all →</a></div><div class="cats">${CATS.map(c=>{const p=S.products.find(x=>x.category==c[0])||{category:c[0],colors:[],name:c[1],images:[]};return `<a class="cat" href="#/products/${c[0]}"><div class="txt"><b>${c[2]} ${c[1]}</b><span>Explore →</span></div>${art(p)}</a>`}).join('')}</div></div></section>
<section id="col"><div class="wrap"><div class="sh"><span class="eyebrow">The TIGZ collection</span><h2>The right gadgets, all in one place.</h2><p>Find the tech you need for music, entertainment and everyday life.</p></div>${tabs()}<div id="pg">${grid(fl())}</div></div></section>
<section id="feat"><div class="wrap"><div class="promo"><div><span class="eyebrow">Featured</span><h2>${esc(f.name)}</h2><div class="price"><b>${money(f.price)}</b><span class="old">${money(f.oldPrice)}</span><span class="sale">SALE −${f.discount}%</span></div><a class="btn" href="#/product/${f.slug}">Shop now →</a></div>${art(f)}</div></div></section>
<section class="cta"><div class="wrap"><h2>Smart Gadgets. Better Life.</h2><p>Cash on delivery across Bangladesh. Track every order from confirmation to your door.</p><a class="btn" href="#/products">Explore products →</a></div></section>`}
function shop(c){if(c)flt=c;return `<section><div class="wrap"><div class="sh"><span class="eyebrow">The TIGZ collection</span><h2>Shop all gadgets</h2></div>${tabs()}<div id="pg">${grid(fl())}</div></div></section>`}
function detail(slg){const p=prod(slg);if(!p)return '<section><div class="wrap empty">Product not found. <a href="#/products" style="color:var(--gold)">Back to shop</a></div></section>';
window._c=p.colors[0];window._q=1;const rel=S.products.filter(x=>x.category==p.category&&x.id!=p.id).slice(0,3);
return `<div class="wrap"><div class="pd"><div id="pa">${art(p)}</div><div><span class="eyebrow">${catName(p.category)}</span><h1>${esc(p.name)}</h1><div class="price"><b>${money(p.price)}</b>${p.sale?`<span class="old">${money(p.oldPrice)}</span><span class="sale">SALE −${p.discount}%</span>`:''}</div><p style="color:var(--mut)">${esc(p.description)}</p><label>Color</label><div class="sw">${p.colors.map((c,i)=>`<button class="swb ${i==0?'on':''}" data-a="col" data-c="${c}" data-id="${p.id}"><i style="background:${COL[c]||'#999'}"></i>${c}</button>`).join('')}</div><div class="row"><div class="qty"><button data-a="q" data-d="-1">−</button><span id="qv">1</span><button data-a="q" data-d="1">+</button></div><button class="btn" data-a="addq" data-id="${p.id}">Add to cart</button><button class="btn ghost" data-a="buyq" data-id="${p.id}">Buy now</button></div><p style="color:${p.stock>0?'#6fcf97':'#e57373'}">${p.stock>0?`In stock (${p.stock} available)`:'Out of stock'}</p><h3 style="font-size:18px;margin-top:20px">Key features</h3><ul class="ft2">${p.features.map(f=>`<li>${esc(f)}</li>`).join('')}</ul></div></div></div><section><div class="wrap"><div class="sh"><h2>Related products</h2></div>${grid(rel)}</div></section>`}
function cartV(){const sub=S.cart.reduce((a,i)=>a+(prod(i.id)?.price||0)*i.qty,0);
if(!S.cart.length)return `<section><div class="wrap empty"><h2>Your cart is empty</h2><p>Pick a few gadgets to get started.</p><a class="btn" href="#/products">Continue shopping</a></div></section>`;
return `<section><div class="wrap"><div class="sh"><h2>Your cart</h2></div><div class="two"><div class="box">${S.cart.map((i,k)=>{const p=prod(i.id);return `<div class="ci">${art(p,i.color)}<div><b>${esc(p.name)}</b><div style="color:var(--mut);font-size:13px">Color: ${i.color} · ${money(p.price)} each</div><div class="row" style="margin-top:8px"><div class="qty"><button data-a="cq" data-k="${k}" data-d="-1">−</button><span>${i.qty}</span><button data-a="cq" data-k="${k}" data-d="1">+</button></div><button class="btn ghost sm" data-a="rm" data-k="${k}">Remove</button></div></div><b>${money(p.price*i.qty)}</b></div>`}).join('')}</div>${summary(sub)}</div></div></section>`}
const DEL=60;
function summary(sub,btn=true){return `<div class="box sum"><div><span>Subtotal</span><span>${money(sub)}</span></div><div><span>Delivery charge</span><span>${money(DEL)}</span></div><div class="t"><span>Grand total</span><span>${money(sub+DEL)}</span></div>${btn?`<a class="btn full" href="#/checkout" style="margin-top:14px">Proceed to checkout</a><a class="btn ghost full" href="#/products" style="margin-top:10px">Continue shopping</a>`:''}</div>`}
function checkout(){if(!S.cart.length)return cartV();const sub=S.cart.reduce((a,i)=>a+prod(i.id).price*i.qty,0);
return `<section><div class="wrap"><div class="sh"><h2>Checkout</h2></div><div class="two"><div class="box"><h3 style="font-size:20px">Customer information</h3><label>Full name</label><input id="cn1"><div class="f2"><div><label>Phone number</label><input id="cp" inputmode="tel"></div><div><label>Email (optional)</label><input id="ce"></div></div><h3 style="font-size:20px;margin-top:22px">Delivery</h3><label>Full address</label><textarea id="ca" rows="2"></textarea><div class="f2"><div><label>City / area</label><input id="cc"></div><div><label>Postal code (optional)</label><input id="cz"></div></div><h3 style="font-size:20px;margin-top:22px">Payment</h3><label style="display:flex;gap:10px;align-items:center;color:var(--tx)"><input type="radio" checked style="width:auto"> Cash on Delivery</label><p id="er" style="color:#e57373"></p><button class="btn full" data-a="place">Place Order</button></div><div>${summary(sub,false)}<div class="box" style="margin-top:14px">${S.cart.map(i=>`<div class="sum"><div><span>${esc(prod(i.id).name)} × ${i.qty}</span><span>${money(prod(i.id).price*i.qty)}</span></div></div>`).join('')}</div></div></div></div></section>`}
function done(id){return `<section><div class="wrap cta"><h2>Order placed</h2><p>Thank you! Your order ID is <b style="color:var(--gold)">${id}</b>. Keep it to track your delivery.</p><a class="btn" href="#/track/${id}">Track order</a> <a class="btn ghost" href="#/products">Continue shopping</a></div></section>`}
const STEPS=['Order placed','Confirmed','Processing','Shipped','Out for delivery','Delivered'];
function track(id){const o=id&&S.orders.find(o=>o.id.toLowerCase()==id.toLowerCase()||o.phone==id);
return `<section><div class="wrap" style="max-width:640px"><div class="sh"><h2>Track your order</h2><p>Enter your order ID or phone number.</p></div><div class="row"><input id="tq" value="${esc(id||'')}" placeholder="TIGZ-1001 or 01XXXXXXXXX" style="flex:1"><button class="btn" data-a="trk">Track</button></div>${id?(o?`<div class="box" style="margin-top:20px"><b>${o.id}</b> · ${money(o.total)}<ul class="tl">${STEPS.map((s,i)=>`<li class="${i<=o.status?'d':''}">${s}</li>`).join('')}</ul></div>`:'<p class="empty">No order found. Check the ID or phone number and try again.</p>'):''}</div></section>`}
function search(q){const l=S.products.filter(p=>(p.name+' '+catName(p.category)+' '+p.category+' '+p.colors.join(' ')).toLowerCase().includes(q.toLowerCase()));return `<section><div class="wrap"><div class="sh"><h2>Results for “${esc(q)}”</h2></div>${grid(l)}</div></section>`}
function info(t,m){return `<section><div class="wrap cta"><h2>${t}</h2><p>${m}</p><a class="btn" href="#/products">Explore products →</a></div></section>`}
/* ADMIN */
const AN=[['','Overview'],['products','Products'],['banners','Banners'],['logos','Logos'],['settings','Settings']];
function admin(sub){let b='';
if(sub==''){b=`<h1>Store Overview</h1><p style="color:var(--mut)">Your storefront at a glance</p><div class="stats">${[['Products',S.products.length],['Banners',S.banners.length],['Categories',CATS.length],['Orders',S.orders.length]].map(s=>`<div class="box stat"><span>${s[0]}</span><b>${s[1]}</b></div>`).join('')}</div><div class="box"><h3 style="font-size:20px;margin-bottom:14px">Store content</h3><div class="row"><a class="btn sm" href="#/admin/products">Manage products</a><a class="btn ghost sm" href="#/admin/banners">Edit banners</a><a class="btn ghost sm" href="#/admin/logos">Edit logos</a></div></div><div class="box tw" style="margin-top:18px"><h3 style="font-size:20px;margin-bottom:10px">Recent orders</h3>${S.orders.length?`<table><tr><th>Order</th><th>Customer</th><th>Total</th><th>Status</th></tr>${S.orders.map((o,k)=>`<tr><td>${o.id}</td><td>${esc(o.name)} · ${esc(o.phone)}</td><td>${money(o.total)}</td><td><select data-a="ost" data-k="${k}">${STEPS.map((s,i)=>`<option value="${i}" ${o.status==i?'selected':''}>${s}</option>`).join('')}</select></td></tr>`).join('')}</table>`:'<div class="empty">No orders yet. Orders placed on the storefront appear here.</div>'}</div>`}
if(sub=='products'){const q=(window._aq||'').toLowerCase();const l=S.products.filter(p=>p.name.toLowerCase().includes(q)&&(!window._ac||p.category==window._ac));b=`<div class="row" style="justify-content:space-between;margin-bottom:16px"><h1>Products</h1><button class="btn sm" data-a="pe" data-id="">+ Add product</button></div><div class="row" style="margin-bottom:14px"><input id="aq" placeholder="Search products" value="${esc(window._aq||'')}" style="max-width:260px"><select id="ac" style="max-width:200px"><option value="">All categories</option>${CATS.map(c=>`<option value="${c[0]}" ${window._ac==c[0]?'selected':''}>${c[1]}</option>`).join('')}</select></div><div class="box tw"><table><tr><th></th><th>Name</th><th>Category</th><th>Price</th><th>Stock</th><th>Tags</th><th></th></tr>${l.map(p=>`<tr><td>${art(p)}</td><td>${esc(p.name)}</td><td>${catName(p.category)}</td><td>${money(p.price)} <span class="old">${money(p.oldPrice)}</span></td><td>${p.stock}</td><td>${p.featured?'★ ':''}${p.sale?'Sale':''}</td><td style="white-space:nowrap"><button class="btn ghost sm" data-a="pe" data-id="${p.id}">Edit</button> <button class="btn ghost sm" data-a="pd" data-id="${p.id}">Delete</button></td></tr>`).join('')}</table></div>`}
if(sub=='banners'){const bs=[...S.banners].sort((a,b)=>a.order-b.order);b=`<div class="row" style="justify-content:space-between;margin-bottom:16px"><h1>Banners</h1><button class="btn sm" data-a="be" data-id="">+ Add banner</button></div>${bs.map((x,i)=>`<div class="box row" style="margin-bottom:12px;justify-content:space-between"><div><b>${esc(x.title)}</b><div style="color:var(--mut);font-size:13px">${esc(x.subtitle)}<br>Links to: ${esc(prod(x.linkedProduct)?.name||'—')} · ${x.active?'Active':'Disabled'}</div></div><div class="row"><button class="btn ghost sm" data-a="bmv" data-id="${x.id}" data-d="-1" ${i==0?'disabled':''}>↑</button><button class="btn ghost sm" data-a="bmv" data-id="${x.id}" data-d="1" ${i==bs.length-1?'disabled':''}>↓</button><button class="btn ghost sm" data-a="btg" data-id="${x.id}">${x.active?'Disable':'Enable'}</button><button class="btn ghost sm" data-a="be" data-id="${x.id}">Edit</button><button class="btn ghost sm" data-a="bd" data-id="${x.id}">Delete</button></div></div>`).join('')}`}
if(sub=='logos'){b=`<h1>Logos</h1><p style="color:var(--mut)">Upload a logo and set it as active.</p><div class="box" style="margin:18px 0"><input type="file" id="lf" accept="image/*"></div><div class="stats">${S.logos.map((l,i)=>`<div class="box"><img src="${l}" alt="" style="height:80px;max-width:100%;object-fit:contain;display:block;margin-bottom:10px"><div class="row"><button class="btn sm" data-a="lact" data-k="${i}" ${S.activeLogo==i?'disabled':''}>${S.activeLogo==i?'Active':'Set active'}</button><button class="btn ghost sm" data-a="ldel" data-k="${i}">Remove</button></div></div>`).join('')}</div>${S.logos.length?'':'<div class="empty">No custom logo uploaded. The default TIGZ mark is in use.</div>'}${S.activeLogo>=0?'<button class="btn ghost sm" data-a="lact" data-k="-1">Use default logo</button>':''}`}
if(sub=='settings'){const s=S.settings;b=`<h1>Settings</h1><div class="box" style="margin-top:18px;max-width:640px"><div class="f2">${[['name','Store name'],['tagline','Store tagline'],['phone','Phone number'],['whatsapp','WhatsApp number'],['email','Email'],['address','Address'],['social','Social links'],['currency','Currency']].map(f=>`<div><label>${f[1]}</label><input data-s="${f[0]}" value="${esc(s[f[0]])}"></div>`).join('')}</div><button class="btn" style="margin-top:18px" data-a="ss">Save changes</button></div>`}
return `<div class="adm"><aside class="side"><div class="brand" style="padding:6px 10px 18px">${logoHTML()}<span>TIGZ Admin</span></div>${AN.map(a=>`<a href="#/admin${a[0]?'/'+a[0]:''}" class="${sub==a[0]?'on':''}">${a[1]}</a>`).join('')}<div class="sp"></div><a href="#/">View storefront</a><a href="#/" data-a="out">Sign out</a></aside><main class="am"><div class="top"><span>Store / ${AN.find(a=>a[0]==sub)[1]}</span><div class="av">T</div></div>${b}</main></div>`}
function modal(h){const m=document.createElement('div');m.className='modal';m.innerHTML=`<div class="mc">${h}</div>`;m.onclick=e=>{if(e.target==m)m.remove()};document.body.appendChild(m);return m}
function toast(t){const e=document.createElement('div');e.className='toast';e.textContent=t;document.body.appendChild(e);setTimeout(()=>e.remove(),1800)}
const fileURL=f=>new Promise(r=>{const x=new FileReader;x.onload=()=>r(x.result);x.readAsDataURL(f)});
const AUTH_H='f0547d197020eaf05a5bd2b155c0e6dad21a8c90af8c8cbd50bd4591adf4364b';
const isAuth=()=>{try{return sessionStorage.getItem('tigz_auth')==='1'}catch(e){return window._au===1}};
async function sha(x){const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(x));return[...new Uint8Array(b)].map(n=>n.toString(16).padStart(2,'0')).join('')}
function loginV(){return `<div style="min-height:100vh;display:grid;place-items:center;padding:20px;background:var(--bg)"><div class="box" style="width:min(400px,100%)"><div class="brand" style="margin-bottom:18px">${logoHTML()}<span style="display:inline">TIGZ Admin</span></div><h2 style="font-size:26px;margin-bottom:6px">Sign in</h2><p style="color:var(--mut);margin:0 0 6px">Enter your admin email and password.</p><label>Email</label><input id="le" type="email" autocomplete="username"><label>Password</label><input id="lp" type="password" autocomplete="current-password"><p id="ler" style="color:#c0392b;min-height:20px;margin:8px 0"></p><button class="btn full" data-a="login">Sign in</button><a href="#/" style="display:block;text-align:center;margin-top:14px;color:var(--mut)">← Back to store</a></div></div>`}
/* router */
function render(){const h=location.hash.replace('#','')||'/';const [,r,a]=h.split('/');const isA=r=='admin';
let v='';
if(isA)v=isAuth()?admin(a||''):loginV();
else{let b='';
if(!r)b=home();else if(r=='products')b=shop(a);else if(r=='product')b=detail(a);else if(r=='cart')b=cartV();else if(r=='checkout')b=checkout();else if(r=='done')b=done(a);else if(r=='track')b=track(a);else if(r=='search')b=search(decodeURIComponent(a||''));else if(r=='categories'){b=home().split('<section id="col">')[0].split('</div></div></div>').pop();b=`<section><div class="wrap"><div class="sh"><span class="eyebrow">Discover your next favorite</span><h2>Shop by category</h2></div><div class="cats">${CATS.map(c=>{const p=S.products.find(x=>x.category==c[0])||{category:c[0],colors:[],name:c[1],images:[]};return `<a class="cat" href="#/products/${c[0]}"><div class="txt"><b>${c[2]} ${c[1]}</b><span>Explore →</span></div>${art(p)}</a>`}).join('')}</div></div></section>`}
else if(r=='featured')b=`<section><div class="wrap"><div class="sh"><span class="eyebrow">Featured</span><h2>Our top picks</h2></div>${grid(S.products.filter(p=>p.featured))}</div></section>`;
else if(r=='contact')b=info('Contact us',`${esc(S.settings.address)}${S.settings.phone?' · '+esc(S.settings.phone):''}${S.settings.email?' · '+esc(S.settings.email):''}`);
else b=home();
v=header(r)+b+footer()}
$('#app').innerHTML=v;cur=0;if(!isA&&!r)startAuto();window.scrollTo(0,0);
const lp=$('#lp');if(lp)lp.onkeydown=e=>{if(e.key=='Enter')document.querySelector('[data-a=login]').click()};
const q=$('#q');if(q)q.onkeydown=e=>{if(e.key=='Enter'&&q.value.trim())location.hash='/search/'+encodeURIComponent(q.value.trim())};
const aq=$('#aq');if(aq)aq.oninput=()=>{window._aq=aq.value;const p=aq.selectionStart;render();const n=$('#aq');n.focus();n.setSelectionRange(p,p)};
const ac=$('#ac');if(ac)ac.onchange=()=>{window._ac=ac.value;render()};
const lf=$('#lf');if(lf)lf.onchange=async()=>{S.logos.push(await fileURL(lf.files[0]));S.activeLogo=S.logos.length-1;save();render();toast('Logo uploaded')}}
function addCart(id,color,qty){const p=prod(id);const e=S.cart.find(i=>i.id==id&&i.color==color);if(e)e.qty+=qty;else S.cart.push({id,color,qty});save();const b=$('#cn');if(b)b.textContent=cartN()}
function prodForm(p){p=p||{name:'',category:'headphones',price:'',oldPrice:'',description:'',colors:[],stock:10,featured:false,sale:true,images:[]};
const m=modal(`<h3 style="font-size:24px;margin-bottom:10px">${p.id?'Edit':'Add'} product</h3><label>Product name</label><input id="fn" value="${esc(p.name)}"><div class="f2"><div><label>Category</label><select id="fc">${CATS.map(c=>`<option value="${c[0]}" ${p.category==c[0]?'selected':''}>${c[1]}</option>`).join('')}</select></div><div><label>Stock</label><input id="fs" type="number" value="${p.stock}"></div><div><label>Price</label><input id="fp" type="number" value="${p.price}"></div><div><label>Old price</label><input id="fo" type="number" value="${p.oldPrice}"></div></div><label>Colors (comma separated)</label><input id="fcl" value="${esc(p.colors.join(', '))}"><label>Description</label><textarea id="fd" rows="3">${esc(p.description)}</textarea><label>Product image</label><input type="file" id="fi" accept="image/*"><div class="chk"><label><input type="checkbox" id="ff" ${p.featured?'checked':''}> Featured</label><label><input type="checkbox" id="fsl" ${p.sale?'checked':''}> On sale</label></div><div class="row"><button class="btn" id="fsv">Save product</button><button class="btn ghost" onclick="this.closest('.modal').remove()">Cancel</button></div>`);
m.querySelector('#fsv').onclick=async()=>{const g=i=>m.querySelector(i);const name=g('#fn').value.trim(),price=+g('#fp').value,old=+g('#fo').value||price;if(!name||!price){toast('Enter a name and price');return}
const o={...p,name,category:g('#fc').value,price,oldPrice:old,discount:Math.round((1-price/old)*100),stock:+g('#fs').value,colors:g('#fcl').value.split(',').map(s=>s.trim()).filter(Boolean),description:g('#fd').value,featured:g('#ff').checked,sale:g('#fsl').checked};
if(g('#fi').files[0])o.images=[await fileURL(g('#fi').files[0])];
if(p.id){S.products[S.products.findIndex(x=>x.id==p.id)]=o}else{o.id=o.slug=slug(name)+'-'+Date.now().toString(36);o.createdAt=Date.now();o.features=['Bluetooth wireless connection','Warranty support from TIGZ'];if(!o.colors.length)o.colors=['Black'];S.products.push(o)}
save();m.remove();render();toast('Saved')}}
function banForm(b){b=b||{title:'',subtitle:'',image:'',linkedProduct:S.products[0]?.slug,buttonText:'Shop now',active:true};
const m=modal(`<h3 style="font-size:24px;margin-bottom:10px">${b.id?'Edit':'Add'} banner</h3><label>Title</label><input id="bt" value="${esc(b.title)}"><label>Subtitle</label><input id="bs" value="${esc(b.subtitle)}"><label>Button text</label><input id="bb" value="${esc(b.buttonText)}"><label>Linked product</label><select id="bl">${S.products.map(p=>`<option value="${p.slug}" ${p.slug==b.linkedProduct?'selected':''}>${esc(p.name)}</option>`).join('')}</select><label>Banner image (optional)</label><input type="file" id="bi" accept="image/*"><div class="chk"><label><input type="checkbox" id="ba" ${b.active?'checked':''}> Active</label></div><div class="row"><button class="btn" id="bsv">Save banner</button><button class="btn ghost" onclick="this.closest('.modal').remove()">Cancel</button></div>`);
m.querySelector('#bsv').onclick=async()=>{const g=i=>m.querySelector(i);const o={...b,title:g('#bt').value,subtitle:g('#bs').value,buttonText:g('#bb').value||'Shop now',linkedProduct:g('#bl').value,active:g('#ba').checked};if(g('#bi').files[0])o.image=await fileURL(g('#bi').files[0]);
if(b.id)S.banners[S.banners.findIndex(x=>x.id==b.id)]=o;else{o.id='b'+Date.now();o.order=S.banners.length+1;S.banners.push(o)}save();m.remove();render();toast('Saved')}}
document.addEventListener('click',async e=>{const t=e.target.closest('[data-a]');if(!t)return;const a=t.dataset.a,id=t.dataset.id,k=+t.dataset.k,d=+t.dataset.d;
if(a=='sl'){go(t.dataset.i!==undefined?+t.dataset.i:cur+d);startAuto()}
else if(a=='flt'){flt=id;document.querySelectorAll('.tab').forEach(x=>x.classList.toggle('on',x.dataset.id==flt));$('#pg').innerHTML=grid(fl())}
else if(a=='wish'){const i=S.wish.indexOf(id);i<0?S.wish.push(id):S.wish.splice(i,1);save();t.classList.toggle('on')}
else if(a=='add'){const p=prod(id);addCart(id,p.colors[0],1);toast('Added to cart')}
else if(a=='buy'){const p=prod(id);addCart(id,p.colors[0],1);location.hash='/cart'}
else if(a=='col'){window._c=t.dataset.c;document.querySelectorAll('.swb').forEach(x=>x.classList.toggle('on',x==t));$('#pa').innerHTML=art(prod(id),t.dataset.c)}
else if(a=='q'){window._q=Math.max(1,window._q+d);$('#qv').textContent=window._q}
else if(a=='addq'){addCart(id,window._c,window._q);toast('Added to cart')}
else if(a=='buyq'){addCart(id,window._c,window._q);location.hash='/cart'}
else if(a=='cq'){S.cart[k].qty=Math.max(1,S.cart[k].qty+d);save();render()}
else if(a=='rm'){S.cart.splice(k,1);save();render()}
else if(a=='place'){const v=i=>$(i).value.trim();if(!v('#cn1')||!v('#cp')||!v('#ca')||!v('#cc')){$('#er').textContent='Fill in your name, phone, address and city.';return}
const total=S.cart.reduce((x,i)=>x+prod(i.id).price*i.qty,0)+DEL;const oid='TIGZ-'+(1001+S.orders.length);
S.orders.unshift({id:oid,name:v('#cn1'),phone:v('#cp'),address:v('#ca')+', '+v('#cc'),total,status:0,items:S.cart});S.cart=[];save();location.hash='/done/'+oid}
else if(a=='trk'){location.hash='/track/'+encodeURIComponent($('#tq').value.trim())}
else if(a=='ost'){}
else if(a=='login'){const h=await sha($('#le').value.trim().toLowerCase()+'|'+$('#lp').value);if(h===AUTH_H){try{sessionStorage.setItem('tigz_auth','1')}catch(e){}window._au=1;render()}else $('#ler').textContent='Wrong email or password.'}
else if(a=='out'){try{sessionStorage.removeItem('tigz_auth')}catch(e){}window._au=0}
else if(a=='pe')prodForm(id?S.products.find(p=>p.id==id):null);
else if(a=='pd'){if(confirm('Delete this product?')){S.products=S.products.filter(p=>p.id!=id);save();render()}}
else if(a=='be')banForm(id?S.banners.find(b=>b.id==id):null);
else if(a=='bd'){if(confirm('Delete this banner?')){S.banners=S.banners.filter(b=>b.id!=id);save();render()}}
else if(a=='btg'){const b=S.banners.find(b=>b.id==id);b.active=!b.active;save();render()}
else if(a=='bmv'){const l=[...S.banners].sort((x,y)=>x.order-y.order),i=l.findIndex(b=>b.id==id),j=i+d;[l[i],l[j]]=[l[j],l[i]];l.forEach((b,n)=>b.order=n+1);save();render()}
else if(a=='lact'){S.activeLogo=k;save();render()}
else if(a=='ldel'){S.logos.splice(k,1);if(S.activeLogo>=S.logos.length)S.activeLogo=S.logos.length-1;save();render()}
else if(a=='ss'){document.querySelectorAll('[data-s]').forEach(i=>S.settings[i.dataset.s]=i.value);save();toast('Settings saved')}
});
document.addEventListener('change',e=>{const t=e.target;if(t.dataset&&t.dataset.a=='ost'){S.orders[+t.dataset.k].status=+t.value;save();toast('Status updated')}});
window.addEventListener('hashchange',render);render();
</script>
</body>
</html>


