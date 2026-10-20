<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Китайский: повторение слов и грамматики</title>
<style>
:root{--paper:#f4f6f3;--card:#fff;--ink:#17233b;--mute:#5d6b7e;--jade:#14806a;--jadebg:#dff1ec;--seal:#b8322a;--sealbg:#f8e3e1;--line:#cfd8d2}
@media (prefers-color-scheme:dark){:root{--paper:#121a24;--card:#1b2634;--ink:#e8eef5;--mute:#9aa9bb;--jade:#4cc3a6;--jadebg:#173a35;--seal:#ff8a80;--sealbg:#3d2327;--line:#2f3d4f}}
*{box-sizing:border-box}
body{margin:0;background:var(--paper);color:var(--ink);font:16px/1.5 system-ui,-apple-system,"Segoe UI","PingFang SC","Noto Sans SC",sans-serif}
main{max-width:720px;margin:0 auto;padding:20px 16px 60px}
h1{font:700 26px/1.2 Georgia,"Songti SC","Noto Serif SC",serif;margin:8px 0 4px}
.sub{color:var(--mute);margin:0 0 18px}
.tabs{display:flex;gap:8px;margin-bottom:16px}
button{font:inherit;color:inherit;cursor:pointer}
button:focus-visible,input:focus-visible{outline:3px solid var(--jade);outline-offset:2px}
.tab,.chip,.opt,.go{border:2px solid var(--line);background:var(--card);border-radius:10px;padding:9px 14px}
.tab{flex:1;font-weight:600}
.tab[aria-selected=true],.chip[aria-pressed=true]{background:var(--ink);color:var(--paper);border-color:var(--ink)}
.row{display:flex;flex-wrap:wrap;gap:8px;margin:6px 0 14px}
.lab{font-size:14px;color:var(--mute);margin-top:10px}
.card{background:var(--card);border:2px solid var(--line);border-radius:16px;padding:22px 18px}
.prog{height:6px;background:var(--line);border-radius:3px;margin-bottom:18px}
.prog i{display:block;height:100%;background:var(--jade);border-radius:3px}
.tag{font-size:14px;color:var(--mute);margin-bottom:6px}
.q{font:600 34px/1.3 "Songti SC","Noto Serif SC",serif;margin:4px 0 4px;text-align:center}
.q.ru{font:600 24px/1.3 Georgia,serif}
.py{text-align:center;color:var(--mute);min-height:24px}
.opts{display:grid;gap:10px;margin:18px 0}
@media(min-width:560px){.opts.two{grid-template-columns:1fr 1fr}}
.opt{text-align:left;font-size:18px;min-height:48px}
.opt:hover:not(:disabled){border-color:var(--jade)}
.opt.ok{background:var(--jadebg);border-color:var(--jade)}
.opt.bad{background:var(--sealbg);border-color:var(--seal)}
.zh{font-family:"Songti SC","Noto Serif SC",serif;font-size:22px}
input[type=text]{width:100%;font:inherit;font-size:20px;padding:12px;border:2px solid var(--line);border-radius:10px;background:var(--paper);color:var(--ink);margin:16px 0 8px}
.go{background:var(--jade);border-color:var(--jade);color:#fff;font-weight:600}
@media (prefers-color-scheme:dark){.go{color:#06201b}}
.fb{border-radius:10px;padding:12px 14px;margin:8px 0 14px}
.fb.ok{background:var(--jadebg)}.fb.bad{background:var(--sealbg)}
.slot{min-height:56px;border:2px dashed var(--line);border-radius:10px;padding:8px;display:flex;flex-wrap:wrap;gap:8px;margin:10px 0}
.slot .chip,.bank .chip{font-family:"Songti SC","Noto Serif SC",serif;font-size:22px}
.bank{display:flex;flex-wrap:wrap;gap:8px;margin:10px 0}
.score{font:700 44px Georgia,serif;text-align:center;margin:6px 0}
ul{padding-left:20px}
.back{border:0;background:none;color:var(--mute);padding:6px 0;margin-bottom:8px}
.menu{display:grid;gap:10px;margin-top:6px}
.item{display:block;width:100%;text-align:left;border:2px solid var(--line);background:var(--paper);border-radius:12px;padding:12px 14px}
.item:hover{border-color:var(--jade)}
.item b{display:block;font-size:17px}.item span{color:var(--mute);font-size:14px}
.scroll{overflow-x:auto}table{border-collapse:collapse;width:100%}
th,td{text-align:left;padding:7px 8px;border-bottom:1px solid var(--line);vertical-align:top}th{font-size:14px;color:var(--mute)}
</style>
</head>
<body>
<main>
<h1>Китайский: повторение</h1>
<p class="sub">Уроки 12–15: слова и грамматика — 9 разделов</p>
<section id="app"></section>
</main>
<script>
const RAW=`12|告诉|gàosu|говорить, сообщать
12|忘|wàng|забывать
12|听说|tīngshuō|слышать, говорят, что…
12|马路|mǎlù|дорога, улица
12|宾馆|bīnguǎn|гостиница
12|天气|tiānqì|погода
12|交通|jiāotōng|транспорт, движение
12|有意思|yǒu yìsi|интересный
12|新|xīn|новый
12|冷|lěng|холодный
12|热|rè|горячий, жаркий
12|累|lèi|уставший
12|干净|gānjìng|чистый
12|方便|fāngbiàn|удобный
12|高兴|gāoxìng|радостный, довольный
12|认识|rènshi|знать (человека)
12|几|jǐ|несколько
12|但是|dànshì|но, однако
12|如果|rúguǒ|если
12|长城|Chángchéng|Великая Китайская стена
13|刚才|gāngcái|только что
13|钥匙|yàoshi|ключ
13|书店|shūdiàn|книжный магазин
13|银行|yínháng|банк
13|教室|jiàoshì|класс, аудитория
13|桌子|zhuōzi|стол
13|口袋|kǒudai|карман
13|包|bāo|сумка, рюкзак
13|外文|wàiwén|иностранный язык
13|自己|zìjǐ|сам, себя
13|上|shàng|на, сверху
13|下|xià|под, снизу
13|旁边|pángbiān|рядом, около
13|对面|duìmiàn|напротив
13|说|shuō|говорить
13|丢|diū|терять
13|锁|suǒ|запирать на замок
13|找到|zhǎodào|найти
13|糊涂|hútu|запутанный, рассеянный
13|糟糕|zāogāo|ужасный, плохой
13|就|jiù|именно, тут же
13|快|kuài|быстро, скорее
13|真|zhēn|действительно, правда
13|那|nà|тогда, в таком случае
13|啊|a|ах (усиливающая частица)
14|博物馆|bówùguǎn|музей
14|市中心|shì zhōngxīn|центр города
14|挺|tǐng|довольно, очень
14|远|yuǎn|далёкий
14|近|jìn|близкий
14|路|lù|дорога, маршрут
14|公共汽车|gōnggòng qìchē|автобус
14|地铁|dìtiě|метро
14|先|xiān|сначала
14|然后|ránhòu|затем, потом
14|换|huàn|менять, пересаживаться
14|票|piào|билет
14|站|zhàn|остановка, станция
14|叫|jiào|звать, называть
14|师傅|shīfu|мастер, водитель
14|售票员|shòupiàoyuán|кондуктор
14|行人|xíngrén|пешеход
14|前面|qiánmiàn|впереди
14|后面|hòumiàn|сзади, позади
14|右边|yòubian|справа
14|左边|zuǒbian|слева
14|往|wǎng|в направлении, к
14|走|zǒu|идти
14|拐|guǎi|поворачивать
14|到|dào|прибывать, добираться
14|路口|lùkǒu|перекрёсток
14|遍|biàn|раз (счётное слово)
14|不好意思|bù hǎoyìsi|извините, неловко
14|错|cuò|неправильный
15|一般|yìbān|обычно
15|总是|zǒngshì|всегда
15|常常|chángcháng|часто
15|有时候|yǒu shíhou|иногда
15|很少|hěnshǎo|редко
15|从来不|cónglái bù|никогда не
15|逛街|guàng jiē|ходить по магазинам
15|听音乐|tīng yīnyuè|слушать музыку
15|聊天儿|liáo tiānr|болтать, общаться
15|跳舞|tiào wǔ|танцевать
15|唱歌|chàng gē|петь
15|打车|dǎ chē|ловить такси
15|骑|qí|ехать на велосипеде
15|走着去|zǒuzhe qù|идти пешком
15|开|kāi|открывать; водить
15|请|qǐng|угощать, приглашать
15|附近|fùjìn|поблизости, рядом
15|歌厅|gētīng|караоке
15|舞厅|wǔtīng|танцзал
15|酒吧|jiǔbā|бар
15|以前|yǐqián|раньше, до
15|以后|yǐhòu|после, потом
+|记性|jìxìng|память
+|找不到|zhǎo bu dào|не мочь найти
+|还是|háishi|всё ещё, или`;
const WORDS=RAW.split('\n').map(l=>{const[a,b,c,d]=l.split('|');return{lv:a,h:b,p:c,r:d}});
const $app=document.getElementById('app');
const sh=a=>{a=[...a];for(let i=a.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[a[i],a[j]]=[a[j],a[i]]}return a};
const el=(t,c,x)=>{const n=document.createElement(t);if(c)n.className=c;if(x!=null)n.textContent=x;return n};
const strip=s=>s.replace(/[。？！，、….,?!\s]/g,'');
let cfg={lv:'all'};
const pool=()=>WORDS.filter(w=>cfg.lv==='all'||w.lv===cfg.lv);
const backBtn=()=>{const b=el('button','back','← К разделам');b.onclick=home;return b};

function run(make){
const items=make();let i=0,score=0,miss=[];
$app.innerHTML='';$app.append(backBtn());
const card=el('div','card');$app.append(card);
function step(){
card.innerHTML='';
if(i>=items.length)return end();
const p=el('div','prog'),b=el('i');b.style.width=(i/items.length*100)+'%';p.append(b);card.append(p);
const box=el('div');card.append(box);
items[i].draw(box,(ok,text)=>{
if(ok)score++;else miss.push(items[i].label);
const f=el('div','fb '+(ok?'ok':'bad'),(ok?'Верно. ':'Неверно. ')+(text||''));
const n=el('button','go',i+1<items.length?'Дальше':'Результат');n.onclick=()=>{i++;step()};
box.append(f,n);n.focus();
});
}
function end(){
card.append(el('div','tag','Результат'),el('div','score',score+' из '+items.length));
if(miss.length){card.append(el('p',null,'Повторите:'));const u=el('ul');miss.forEach(m=>u.append(el('li',null,m)));card.append(u)}
else card.append(el('p',null,'Без ошибок.'));
const r=el('button','go','Ещё раз');r.onclick=()=>run(make);card.append(r);
}
step();
}
function choice(box,prompt,cls,sub,opts,info,done,zh){
box.append(el('div','q '+cls,prompt),el('div','py',sub||''));
const g=el('div','opts '+(zh||opts.length<3?'two':''));
sh(opts).forEach(o=>{
const b=el('button','opt'+(zh?' zh':''),o.t);
b.onclick=()=>{[...g.children].forEach(x=>{x.disabled=true;if(x.dataset.ok)x.classList.add('ok')});if(!o.ok)b.classList.add('bad');done(o.ok,info)};
if(o.ok)b.dataset.ok=1;g.append(b);
});
box.append(g);
}
function build(box,tag,ru,chips,ans,done){
box.append(el('div','tag',tag),el('div','q ru',ru));
const slot=el('div','slot'),bank=el('div','bank'),b=el('button','go','Проверить');
sh(chips).forEach(w=>{const c=el('button','chip',w);let on=0;c.dataset.w=w;
c.onclick=()=>{if(b.disabled)return;on=!on;(on?slot:bank).append(c)};bank.append(c)});
b.onclick=()=>{b.disabled=true;const got=[...slot.children].map(x=>x.dataset.w).join('');
done(ans.some(a=>strip(a)===got),'Правильно: '+ans[0])};
box.append(slot,bank,b);
}

/* Конструкторы заданий */
const C=(tag,q,sub,ans,wrong,e)=>({label:tag+': '+q,draw:(box,done)=>{box.append(el('div','tag',tag));
choice(box,q,'',sub,[{t:ans,ok:1},...wrong.map(t=>({t}))],e,done,true)}});
const O=(ru,ok,bad,e)=>({label:ru+' → '+ok,draw:(box,done)=>{box.append(el('div','tag','Выберите правильный порядок слов'));
choice(box,ru,'ru','',[{t:ok,ok:1},...bad.map(t=>({t}))],e,done,true)}});
const T=(ru,ans,extra)=>({label:ru+' → '+ans[0],draw:(box,done)=>{
const chips=[...new Set(strip(ans[0]).split('|'))];
build(box,'Переведите на китайский — соберите предложение',ru,ans[2]?ans[2]:[],ans.slice(0,2),done)}});

const wordItem=mode=>w=>{
const info=w.h+' — '+w.p+' — '+w.r,label=info;
if(mode==='type')return{label,draw:(box,done)=>{
box.append(el('div','tag','Напишите иероглифами'),el('div','q ru',w.r));
const py=el('div','py'),hb=el('button','chip','Подсказка: пиньинь');hb.onclick=()=>{py.textContent=w.p;hb.disabled=true};
const inp=el('input');inp.type='text';inp.autocomplete='off';
const b=el('button','go','Проверить');
const chk=()=>{if(b.disabled)return;b.disabled=inp.disabled=true;done(strip(inp.value)===strip(w.h),info)};
b.onclick=chk;inp.onkeydown=e=>{if(e.key==='Enter')chk()};
box.append(py,hb,inp,b);inp.focus();
}};
const oth=sh(WORDS.filter(x=>x.h!==w.h&&x.r!==w.r)).slice(0,3);
return{label,draw:(box,done)=>choice(box,w.h,'',w.p,[{t:w.r,ok:1},...oth.map(x=>({t:x.r}))],info,done)};
};

const D={
order:[
['Он в классе.','他在教室里。',['他教室里在。','在他教室里。','教室里他在。'],'Кто/что + 在 + место.'],
['Парк напротив гостиницы.','公园在宾馆对面。',['公园宾馆对面在。','宾馆对面在公园。','在公园宾馆对面。'],'Кто/что + 在 + место.'],
['Напротив гостиницы есть парк.','宾馆对面有一个公园。',['有宾馆对面一个公园。','一个公园有宾馆对面。','宾馆对面一个公园有。'],'Место + 有 + кто/что.'],
['В классе три студента.','教室里有三个学生。',['有教室里三个学生。','三个学生有教室里。','教室里三个学生有。'],'Место + 有 + кто/что.'],
['Одежда на кровати.','衣服在床上。',['衣服床上在。','床上在衣服。','在衣服床上。'],'Кто/что + 在 + место.'],
['В комнате довольно много людей.','房间里有不少人。',['有房间里不少人。','房间里不少人有。','不少人有房间里。'],'Место + 有 + кто/что.'],
['Ключ на столе.','钥匙在桌子上。',['钥匙桌子上在。','桌子上在钥匙。','在钥匙桌子上。'],'Кто/что + 在 + место.'],
['В сумке есть ключ.','包里有钥匙。',['有包里钥匙。','钥匙有包里。','包里钥匙有。'],'Место + 有 + кто/что.']],
place:[
['教室___','в классе','里',['上','下','对面'],'教室里'],
['桌子___','под столом','下',['上','里','外'],'桌子下(面)'],
['床___','на кровати','上',['下','里','对面'],'床上'],
['教室的___','снаружи класса','外边',['里边','下面','旁边'],'教室(的)外边'],
['银行的___','напротив банка','对面',['旁边','里面','上面'],'银行(的)对面'],
['食堂的___','рядом со столовой','旁边',['对面','外边','下面'],'食堂(的)旁边'],
['口袋___','в кармане','里',['上','下','外'],'口袋里'],
['学校___','рядом со школой','旁边',['里','上','下'],'学校旁边']],
gram:[
['这个房间___小。','комната немного маловата (недовольство)','有点儿',['一点儿','几','过'],'有点儿 + прил. — небольшой недостаток.'],
['他今天___不舒服。','сегодня он немного нездоров','有点儿',['了','的','往'],'他今天有点儿不舒服。'],
['那儿的东西___贵。','вещи там немного дороговаты','有点儿',['几','过','跟'],'有点儿 + прил.'],
['昨天我在超市买___四斤苹果。','действие завершено','了',['过','的','着'],'V + 了 + Obj. — акцент на объекте.'],
['昨天我们去超市___，我买了食品。','мы ходили в супермаркет','了',['过','的','着'],'了 показывает завершённость.'],
['你（是）在哪儿买___？','где купил — известный факт','的',['了','过','吗'],'是……的 уточняет место/время/способ.'],
['她（是）昨天来___。','когда приехала','的',['了','过','吗'],'是……的: время действия.'],
['我是跟朋友一起去___。','с кем ходил','的',['过','着','呢'],'是……的: способ/спутник.'],
['___房间里休息。','отдыхать в комнате','在',['给','从','往'],'在 — «в, на»; ставится перед глаголом.'],
['我晚上___你打电话。','позвоню тебе','给',['从','往','在'],'给 — «для, кому-то».'],
['我昨天___商店去买了东西。','ходил в магазин','到',['从','给','往'],'到 — «до, в».'],
['你___哪儿来？','откуда пришёл','从',['给','到','往'],'从 — «из, от».'],
['我是___朋友一起去的。','вместе с другом','跟',['给','从','往'],'跟 — «с».'],
['请___左拐。','поверните налево','往',['从','跟','给'],'往 — «в направлении».']],
freq:[
['我___去舞厅。','никогда не хожу на танцы','从来不',['总是','常常','很少'],'从来不 — никогда.'],
['他周末___在房间看书。','по выходным всегда','总是',['从来不','很少','有时候'],'总是 — всегда.'],
['他___去酒吧。','часто ходит в бар','常常',['总是','从来不','很少'],'常常 — часто.'],
['我___逛街。','иногда гуляю по магазинам','有时候',['总是','常常','从来不'],'有时候 — иногда.'],
['我___听音乐。','редко слушаю музыку','很少',['总是','常常','有时候'],'很少 — редко.']],
guo:[
['我以前来___这儿。','утверждение: раньше бывал здесь','过',['了','的','着'],'V + 过 — опыт в прошлом.'],
['我以前___学过汉语。','отрицание: раньше не учил китайский','没',['不','别','了'],'Отрицание: 没 + V + 过.'],
['我没去___北京，很想去。','не был в Пекине','过',['了','的','着'],'没去过北京。'],
['Ты когда-нибудь был в Пекине?','вопрос','你去过北京吗？',['你去了过北京吗？','你过去北京吗？','你去北京过吗？'],'Ещё: 你去过北京没有？ / 你去没去过北京？'],
['你去过北京___？','вопрос с 没有','没有',['不有','没了','别'],'你去过北京没有？'],
['你去___去过北京？','вопрос: был / не был','没',['不','有','了'],'你去没去过北京？'],
['Мы этот иероглиф не проходили.','отрицание','这个字我们没学过。',['这个字我们不学过。','这个字我们没学了。','这个字我们学没过。'],'没 + V + 过.']],
tr:[
['Вчера я купил яблоки.',['昨天我买了苹果。'],['昨天','我','买','了','苹果','过']],
['Он сегодня немного нездоров.',['他今天有点儿不舒服。'],['他','今天','有点儿','不','舒服','很']],
['Когда ты приехал?',['你是什么时候来的？','你什么时候来的？'],['你','是','什么时候','来','的','了']],
['Он в классе.',['他在教室里。','他在教室。'],['他','在','教室','里','有']],
['В комнате есть три студента.',['房间里有三个学生。'],['房间','里','有','三个','学生','在']],
['Я никогда не был в Пекине.',['我从来没去过北京。'],['我','从来','没','去','过','北京','不']],
['По выходным он всегда читает в комнате.',['他周末总是在房间看书。'],['他','周末','总是','在','房间','看书','常常']],
['Вечером я тебе позвоню.',['我晚上给你打电话。'],['我','晚上','给','你','打电话','跟']],
['Повторите, пожалуйста, ещё раз.',['请再说一遍。'],['请','再','说','一','遍','个']],
['Напротив гостиницы есть парк.',['宾馆对面有一个公园。'],['宾馆','对面','有','一个','公园','在']],
['Куда ты только что ходил?',['刚才你去哪儿了？'],['刚才','你','去','哪儿','了','过']],
['Я не знаю этот иероглиф.',['这个字我不认识。'],['这个字','我','不','认识','没']]]
};
const cs=a=>a.map(x=>C('',x[0],x[1],x[2],x[3],x[4]));
const pk=(a,n)=>sh(a).slice(0,n);

const S=[
{n:'Выбор перевода',d:'Китайское слово и четыре варианта ответа',f:()=>run(()=>pk(pool(),10).map(wordItem('tr')))},
{n:'Восстановление слов',d:'Перевод на русском — введите иероглифы',f:()=>run(()=>pk(pool(),10).map(wordItem('type')))},
{n:'Конструкции 在 и 有',d:'Выбор правильного порядка слов',f:()=>run(()=>pk(D.order,8).map(x=>O(...x)))},
{n:'Выражения места',d:'上、下、里、外、旁边、对面 и другие',f:()=>run(()=>pk(D.place,8).map(x=>C('Выражения места',x[0],x[1],x[2],x[3],x[4])))},
{n:'Грамматика',d:'有点儿、了、是……的 и предложные конструкции',f:()=>run(()=>pk(D.gram,10).map(x=>C('Грамматика',x[0],x[1],x[2],x[3],x[4])))},
{n:'Наречия частоты',d:'От 总是 («всегда») до 从来不 («никогда не»)',f:()=>run(()=>[...D.freq.map(x=>C('Наречия частоты',x[0],x[1],x[2],x[3],x[4])),
{label:'Порядок наречий',draw:(box,done)=>build(box,'Наречия частоты','Расставьте от «всегда» до «никогда»',['从来不','总是','很少','常常','有时候'],['总是常常有时候很少从来不'],done)}])},
{n:'Частица 过',d:'Утверждения, отрицания и вопросы об опыте',f:()=>run(()=>pk(D.guo,7).map(x=>x[0].includes('___')?C('Частица 过',x[0],x[1],x[2],x[3],x[4]):O(x[0],x[2],x[3],x[4])))},
{n:'Перевод предложений',d:'С русского на китайский — с проверкой ответов',f:()=>run(()=>pk(D.tr,8).map(x=>({label:x[0]+' → '+x[1][0],draw:(box,done)=>build(box,'Соберите предложение по-китайски',x[0],x[2],x[1],done)})))}
];

function list(){
$app.innerHTML='';$app.append(backBtn());
const c=el('div','card');$app.append(c);
const r=el('div','row');lvChips(r,list);c.append(r);
c.append(el('div','tag','Слов: '+pool().length));
const wrap=el('div','scroll'),t=el('table');
t.innerHTML='<tr><th>Иероглифы</th><th>Пиньинь</th><th>Перевод</th></tr>';
pool().forEach(w=>{const tr=el('tr');[w.h,w.p,w.r].forEach((x,i)=>tr.append(el('td',i?'':'zh',x)));t.append(tr)});
wrap.append(t);c.append(wrap);
}
function lvChips(r,re){
[['all','Все уроки'],['12','Урок 12'],['13','Урок 13'],['14','Урок 14'],['15','Урок 15'],['+','Доп.']].forEach(([k,t])=>{
const b=el('button','chip',t);b.setAttribute('aria-pressed',cfg.lv===k);b.onclick=()=>{cfg.lv=k;re()};r.append(b)});
}
function home(){
$app.innerHTML='';
const c=el('div','card');$app.append(c);
c.append(el('div','lab','Слова — урок:'));const r=el('div','row');lvChips(r,home);c.append(r);
const m=el('div','menu');
const first=el('button','item');first.append(el('b',null,'Список слов'),el('span',null,'Иероглифы, пиньинь и переводы с фильтром по урокам'));first.onclick=list;m.append(first);
S.forEach(s=>{const b=el('button','item');b.append(el('b',null,s.n),el('span',null,s.d));b.onclick=s.f;m.append(b)});
c.append(m);
}
home();
</script>
</body>
</html>
