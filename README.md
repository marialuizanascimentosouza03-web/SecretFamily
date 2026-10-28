<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Amigo Secreto · Família Souza</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,600;9..144,800&family=Nunito:wght@400;600;700&display=swap">
<style>
:root{--bg:#fbf5ec;--card:#fffdf8;--ink:#2b2a26;--mute:#7a7467;--green:#1f5d46;--green2:#2f7d5f;--red:#c63d3d;--line:#eadfcd;--soft:#f3ead9;--shadow:0 10px 30px rgba(60,40,10,.10);color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#141a17;--card:#1c2420;--ink:#f1ece2;--mute:#a79f90;--green:#5fc29a;--green2:#3f9d78;--red:#ef6b6b;--line:#2b3731;--soft:#242f29;--shadow:0 10px 30px rgba(0,0,0,.4);color-scheme:dark}}
:root[data-theme="dark"]{--bg:#141a17;--card:#1c2420;--ink:#f1ece2;--mute:#a79f90;--green:#5fc29a;--green2:#3f9d78;--red:#ef6b6b;--line:#2b3731;--soft:#242f29;--shadow:0 10px 30px rgba(0,0,0,.4);color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:'Nunito',system-ui,-apple-system,'Segoe UI',sans-serif;min-height:100vh;overflow-x:hidden}
.snow{position:fixed;inset:0;pointer-events:none;overflow:hidden;z-index:0}
.snow i{position:absolute;top:-20px;color:var(--green);opacity:.18;animation:fall linear infinite;font-style:normal}
@keyframes fall{to{transform:translateY(110vh) rotate(360deg)}}
@media (prefers-reduced-motion:reduce){.snow{display:none}}
main{position:relative;z-index:1;max-width:620px;margin:0 auto;padding:28px 18px 60px}
header{text-align:center;margin-bottom:22px}
header .tree{font-size:44px}
h1{font-family:'Fraunces',Georgia,serif;font-weight:800;font-size:clamp(28px,7vw,38px);margin:4px 0;color:var(--green)}
header p{color:var(--mute);margin:0}
.card{background:var(--card);border:1px solid var(--line);border-radius:22px;padding:22px;box-shadow:var(--shadow);margin-bottom:16px}
h2{font-family:'Fraunces',Georgia,serif;font-size:21px;margin:0 0 4px}
.sub{color:var(--mute);font-size:14px;margin:0 0 16px}
.tabs{display:flex;background:var(--soft);padding:5px;border-radius:14px;gap:4px;margin-bottom:18px}
.tabs button{flex:1;border:0;background:none;padding:10px;border-radius:10px;font:700 15px 'Nunito',sans-serif;color:var(--mute);cursor:pointer}
.tabs button.on{background:var(--card);color:var(--green);box-shadow:0 2px 8px rgba(0,0,0,.08)}
label{display:block;font-weight:700;font-size:13px;margin:12px 0 5px}
input,select,textarea{width:100%;padding:13px 14px;border-radius:12px;border:1.5px solid var(--line);background:var(--bg);color:var(--ink);font:600 16px 'Nunito',sans-serif;outline:none}
input:focus,select:focus{border-color:var(--green2)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:6px;border:0;border-radius:12px;padding:13px 18px;font:800 15px 'Nunito',sans-serif;cursor:pointer;background:var(--green);color:#fff;width:100%;margin-top:16px}
:root[data-theme="dark"] .btn{color:#10201a}
.btn.ghost{background:var(--soft);color:var(--ink);width:auto;margin:0;padding:9px 14px;font-size:13px}
.btn.sm{width:auto;margin:0;padding:12px 18px}
.err{color:var(--red);font-weight:700;font-size:14px;margin-top:10px;min-height:18px}
.top{display:flex;justify-content:space-between;align-items:center;margin-bottom:14px;gap:10px}
.hi{font-family:'Fraunces',Georgia,serif;font-size:22px;font-weight:800;color:var(--green)}
.nav{display:flex;gap:8px;margin-bottom:16px}
.nav button{flex:1;padding:12px;border-radius:14px;border:1.5px solid var(--line);background:var(--card);font:800 14px 'Nunito',sans-serif;color:var(--mute);cursor:pointer}
.nav button.on{background:var(--green);border-color:var(--green);color:#fff}
:root[data-theme="dark"] .nav button.on{color:#10201a}
.gift{display:flex;gap:12px;align-items:flex-start;padding:14px;border:1px solid var(--line);border-radius:16px;background:var(--bg);margin-top:10px}
.gift .em{font-size:24px}
.gift .t{font-weight:800;word-break:break-word}
.gift .n{color:var(--mute);font-size:14px;margin-top:2px;word-break:break-word}
.gift a{color:var(--green2);font-weight:800;font-size:14px;text-decoration:none;word-break:break-all}
.gift a:hover{text-decoration:underline}
.gift .x{margin-left:auto;background:none;border:0;color:var(--red);font-size:18px;cursor:pointer}
.row{display:flex;gap:10px}.row>*{flex:1}
.empty{text-align:center;color:var(--mute);padding:22px 8px}
.pill{display:inline-block;background:var(--soft);padding:6px 12px;border-radius:99px;font-weight:800;font-size:13px;color:var(--green)}
.hide{display:none!important}
.note{font-size:12.5px;color:var(--mute);text-align:center;margin-top:18px;line-height:1.5}
</style>
</head>
<body>
<div class="snow" id="snow" aria-hidden="true"></div>
<main>
<header><div class="tree">🎄</div><h1>Amigo Secreto Souza</h1><p>Natal em família, do jeitinho que a gente gosta</p></header>
<div id="app"><div class="card empty">Carregando…</div></div>
<p class="note">🤫 Ninguém vê quem você tirou nem o que você comprou.<br>Anote bem sua senha: ela não pode ser recuperada.</p>
</main>
<script>
setTimeout(function(){var a=document.getElementById('app');if(a&&a.textContent.indexOf('Carregando')>-1)a.innerHTML='<div class="card empty">Não consegui conectar. Confira se o Firestore foi criado no Firebase, se a internet está ok e se algum bloqueador de anúncios ou VPN está ativo. Depois recarregue a página.</div>'},12000);
</script>
<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/13.1.0/firebase-app.js";
import { initializeFirestore, collection, doc, getDoc, setDoc, updateDoc, deleteDoc, onSnapshot } from "https://www.gstatic.com/firebasejs/13.1.0/firebase-firestore.js";
const firebaseConfig = {
  apiKey: "AIzaSyAdnEepk8LWW8HdXDzKzdwZDD_Zi63l2Qw",
  authDomain: "secretfamily-1950f.firebaseapp.com",
  projectId: "secretfamily-1950f",
  storageBucket: "secretfamily-1950f.firebasestorage.app",
  messagingSenderId: "989791446393",
  appId: "1:989791446393:web:642d46eb24f42117577ba8"
};
const db = initializeFirestore(initializeApp(firebaseConfig),{experimentalAutoDetectLongPolling:true});
const $=s=>document.querySelector(s);
const esc=s=>String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const slug=n=>n.normalize('NFD').replace(/[\u0300-\u036f]/g,'').toLowerCase().trim().replace(/[^a-z0-9]+/g,'-').replace(/^-|-$/g,'');
async function hash(p,salt){const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(salt+':'+p));return [...new Uint8Array(b)].map(x=>x.toString(16).padStart(2,'0')).join('')}
const safeUrl=u=>{u=(u||'').trim();if(!u)return'';if(!/^https?:\/\//i.test(u))u='https://'+u;try{const x=new URL(u);return /^https?:$/.test(x.protocol)?x.href:''}catch(e){return''}};
// neve
(()=>{const s=$('#snow');for(let i=0;i<18;i++){const e=document.createElement('i');e.textContent='❄';e.style.left=Math.random()*100+'%';e.style.fontSize=(10+Math.random()*16)+'px';e.style.animationDuration=(10+Math.random()*14)+'s';e.style.animationDelay=(-Math.random()*20)+'s';s.appendChild(e)}})();

let people=[],me=null,view='mine',tab='login',draw=null,err='';
const ss={get(k){try{return sessionStorage.getItem(k)}catch(e){return null}},set(k,v){try{sessionStorage.setItem(k,v)}catch(e){}},del(k){try{sessionStorage.removeItem(k)}catch(e){}}};

function showErr(e){const c=(e&&e.code)||'';let m='Não consegui conectar ao banco de dados.';if(c==='permission-denied')m='O Firestore bloqueou o acesso. Confira as regras do banco (modo de teste).';else if(c==='failed-precondition'||c==='not-found')m='O banco Firestore ainda não foi criado neste projeto.';$('#app').innerHTML='<div class="card empty">'+m+'<br><small>'+esc(c||String(e&&e.message||e))+'</small></div>'}
function init(){
  onSnapshot(collection(db,'people'),s=>{
    people=s.docs.map(x=>({id:x.id,...x.data()}));
    const sid=ss.get('me');me=sid?people.find(p=>p.id===sid)||null:null;if(!me)ss.del('me');
    loadDraw().then(()=>{const t=document.activeElement&&document.activeElement.tagName;if(t==='INPUT'||t==='SELECT')return;render()});
  },showErr);
}
async function loadDraw(){
  draw=null;if(!me)return;
  try{const s=await getDoc(doc(db,'draws',me.id));if(s.exists())draw=s.data().target}catch(e){}
}
function render(){
  const a=$('#app');
  if(!me){
    a.innerHTML=`<div class="card"><div class="tabs"><button class="${tab==='login'?'on':''}" data-t="login">Entrar</button><button class="${tab==='reg'?'on':''}" data-t="reg">Cadastrar</button></div>
    <h2>${tab==='login'?'Que bom te ver! 👋':'Bem-vindo(a) à família 🎅'}</h2>
    <p class="sub">${tab==='login'?'Entre com seu nome e senha.':'Crie seu cadastro para montar sua lista de presentes.'}</p>
    <label>Seu nome</label><input id="nm" autocomplete="username" placeholder="Ex: Maria Souza">
    <label>Senha</label><input id="pw" type="password" autocomplete="${tab==='login'?'current-password':'new-password'}" placeholder="Pelo menos 4 caracteres">
    <div class="err" id="err">${esc(err)}</div>
    <button class="btn" id="go">${tab==='login'?'Entrar':'Criar meu cadastro'}</button></div>`;
    a.querySelectorAll('[data-t]').forEach(b=>b.onclick=()=>{tab=b.dataset.t;err='';render()});
    $('#go').onclick=tab==='login'?login:register;
    a.querySelectorAll('input').forEach(i=>i.onkeydown=e=>{if(e.key==='Enter')$('#go').click()});
    return;
  }
  const first=esc(me.name.split(' ')[0]);
  a.innerHTML=`<div class="top"><div class="hi">Olá, ${first}! ✨</div><button class="btn ghost" id="out">Sair</button></div>
  <div class="nav"><button data-v="mine" class="${view==='mine'?'on':''}">🎁 Minha lista</button><button data-v="drawn" class="${view==='drawn'?'on':''}">🤫 Quem eu tirei</button></div>
  <div id="pane"></div>`;
  $('#out').onclick=()=>{ss.del('me');me=null;draw=null;err='';render()};
  a.querySelectorAll('[data-v]').forEach(b=>b.onclick=()=>{view=b.dataset.v;render()});
  view==='mine'?mine():drawn();
}
function giftHtml(g,i,del){
  const u=safeUrl(g.url);
  return `<div class="gift"><div class="em">🎁</div><div><div class="t">${esc(g.title)}</div>${g.note?`<div class="n">${esc(g.note)}</div>`:''}${u?`<a href="${esc(u)}" target="_blank" rel="noopener noreferrer">Abrir link ↗</a>`:''}</div>${del?`<button class="x" data-i="${i}" title="Remover" aria-label="Remover">✕</button>`:''}</div>`;
}
function mine(){
  const gifts=me.gifts||[];
  $('#pane').innerHTML=`<div class="card"><h2>O que eu quero ganhar</h2><p class="sub">Adicione links ou ideias. Quem te tirou vai ver essa lista.</p>
  <label>Presente</label><input id="gt" placeholder="Ex: Fone de ouvido bluetooth">
  <label>Link (opcional)</label><input id="gu" inputmode="url" placeholder="https://...">
  <label>Detalhe (opcional)</label><input id="gn" placeholder="Cor, tamanho, número…">
  <div class="err" id="err">${esc(err)}</div>
  <button class="btn" id="add">Adicionar à lista</button></div>
  <div class="card"><h2>Minha lista <span class="pill">${gifts.length}</span></h2>
  ${gifts.length?gifts.map((g,i)=>giftHtml(g,i,true)).join(''):'<div class="empty">Sua lista está vazia. Que tal adicionar o primeiro desejo? 🎅</div>'}</div>`;
  $('#add').onclick=addGift;
  document.querySelectorAll('.x').forEach(b=>b.onclick=()=>delGift(+b.dataset.i));
}
function drawn(){
  const others=people.filter(p=>p.id!==me.id).sort((a,b)=>a.name.localeCompare(b.name,'pt'));
  const t=draw&&people.find(p=>p.id===draw);
  if(!t){
    $('#pane').innerHTML=`<div class="card"><h2>Quem você tirou?</h2><p class="sub">Escolha o nome. Só você vai saber dessa escolha. 🤐</p>
    ${others.length?`<select id="pick"><option value="">Selecione…</option>${others.map(p=>`<option value="${esc(p.id)}">${esc(p.name)}</option>`).join('')}</select><button class="btn" id="ok">Confirmar</button>`:'<div class="empty">Ainda não tem mais ninguém cadastrado. Chame a família! 👨‍👩‍👧‍👦</div>'}</div>`;
    if($('#ok'))$('#ok').onclick=async()=>{const v=$('#pick').value;if(!v)return;draw=v;try{await setDoc(doc(db,'draws',me.id),{target:v})}catch(e){}render()};
    return;
  }
  const g=t.gifts||[];
  $('#pane').innerHTML=`<div class="card"><div class="top" style="margin:0"><div><span class="pill">Você tirou</span><h2 style="margin-top:8px;font-size:26px">${esc(t.name)} 🎅</h2></div><button class="btn ghost" id="chg">Trocar</button></div>
  <p class="sub" style="margin-top:6px">Ninguém mais sabe disso. Boas compras!</p>
  ${g.length?g.map((x,i)=>giftHtml(x,i,false)).join(''):`<div class="empty">${esc(t.name.split(' ')[0])} ainda não cadastrou presentes. Volte mais tarde! ⏳</div>`}</div>`;
  $('#chg').onclick=async()=>{if(!confirm('Trocar a pessoa que você tirou?'))return;draw=null;try{await deleteDoc(doc(db,'draws',me.id))}catch(e){}render()};
}
async function register(){document.activeElement&&document.activeElement.blur();
  const name=$('#nm').value.trim().replace(/\s+/g,' '),pw=$('#pw').value,id=slug(name);
  if(name.length<2||!id){err='Digite seu nome.';return render()}
  if(pw.length<4){err='A senha precisa ter pelo menos 4 caracteres.';return render()}
  try{
    const ref=doc(db,'people',id);
    if((await getDoc(ref)).exists()){err='Esse nome já está cadastrado. Use outro (ex: com sobrenome) ou entre.';return render()}
    const salt=crypto.getRandomValues(new Uint32Array(2)).join('');
    await setDoc(ref,{name,salt,pass:await hash(pw,salt),gifts:[]});
    ss.set('me',id);err='';view='mine';
  }catch(e){err='Não consegui cadastrar. Tente de novo em instantes.';render()}
}
async function login(){document.activeElement&&document.activeElement.blur();
  const name=$('#nm').value.trim(),pw=$('#pw').value,p=people.find(x=>x.id===slug(name));
  if(!p||(await hash(pw,p.salt))!==p.pass){err='Nome ou senha incorretos.';return render()}
  ss.set('me',p.id);err='';view='mine';me=p;await loadDraw();render();
}
async function saveGifts(g){try{await updateDoc(doc(db,'people',me.id),{gifts:g})}catch(e){err='Não foi possível salvar.';render()}}
async function addGift(){document.activeElement&&document.activeElement.blur();
  const title=$('#gt').value.trim(),url=$('#gu').value.trim(),note=$('#gn').value.trim();
  if(!title&&!url){err='Informe o presente ou um link.';return mine()}
  if(url&&!safeUrl(url)){err='Esse link não parece válido.';return mine()}
  err='';await saveGifts([...(me.gifts||[]),{title:title||'Presente',url:url?safeUrl(url):'',note}]);
}
async function delGift(i){const g=[...(me.gifts||[])];g.splice(i,1);await saveGifts(g)}
init();
</script>
</body>
</html>
