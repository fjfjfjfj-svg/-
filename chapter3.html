<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080b18">
<title>Дело № 003 — За пределами архива</title>
<style>
:root{
  --bg:#080b18;--panel:rgba(17,23,46,.78);--line:rgba(178,190,255,.22);
  --text:#f4f2ff;--muted:#a8aecb;--gold:#e8cf9b;--violet:#b8a5ff;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;min-height:100vh;color:var(--text);
  background:radial-gradient(ellipse at 50% 0%,#20264c 0%,#10152d 36%,#080b18 76%);
  font-family:Georgia,"Times New Roman",serif;overflow-x:hidden;
}
#stars{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.star{position:absolute;width:2px;height:2px;background:#fff;border-radius:50%;opacity:.5;animation:twinkle 3s ease-in-out infinite alternate}
@keyframes twinkle{from{opacity:.15;transform:scale(.7)}to{opacity:.9;transform:scale(1.4)}}
.aurora{position:fixed;width:50vw;height:50vw;max-width:560px;max-height:560px;border-radius:50%;filter:blur(90px);opacity:.11;pointer-events:none;z-index:0;background:#7d69ff;left:-20%;top:30%;animation:float 14s ease-in-out infinite alternate}
@keyframes float{to{transform:translate(65vw,15vh) scale(1.2)}}
main{position:relative;z-index:1;width:min(760px,100%);margin:0 auto;padding:30px 18px 70px}
header{text-align:center;padding:35px 10px 24px;animation:rise 1s ease both}
.kicker{font:11px/1.5 Arial,sans-serif;letter-spacing:.32em;color:var(--gold);text-transform:uppercase}
h1{font-size:clamp(30px,7vw,48px);font-weight:normal;letter-spacing:.04em;margin:15px 0 8px}
.subtitle{color:var(--muted);font:12px Arial,sans-serif;letter-spacing:.18em;text-transform:uppercase}
.rule{width:90px;height:1px;background:linear-gradient(90deg,transparent,var(--gold),transparent);margin:24px auto}
.panel{border:1px solid var(--line);background:linear-gradient(145deg,rgba(27,34,66,.82),rgba(9,13,29,.82));border-radius:18px;padding:clamp(20px,5vw,34px);box-shadow:0 18px 70px #0003;backdrop-filter:blur(10px);margin:18px 0;animation:rise .7s ease both}
@keyframes rise{from{opacity:0;transform:translateY(18px)}to{opacity:1;transform:translateY(0)}}
.panel h2{font-weight:normal;font-size:24px;margin:0 0 12px}
p{line-height:1.8;color:#e1e2f3;font-size:16px}
.muted{color:var(--muted)}
.small-label{font:10px Arial,sans-serif;letter-spacing:.2em;color:var(--gold);text-transform:uppercase;margin-bottom:12px}
button,.choice{
  font:14px Arial,sans-serif;letter-spacing:.04em;color:var(--text);
  border:1px solid rgba(184,165,255,.38);background:rgba(117,99,191,.12);
  padding:14px 18px;border-radius:11px;cursor:pointer;transition:transform .2s,border-color .2s,background .2s;
}
button:hover,.choice:hover{transform:translateY(-2px);border-color:var(--gold);background:rgba(117,99,191,.22)}
button:focus-visible,.choice:focus-visible{outline:2px solid var(--gold);outline-offset:3px}
.primary{border-color:rgba(232,207,155,.6);color:var(--gold);margin-top:10px}
.choices{display:grid;gap:10px;margin-top:20px}
.choice{text-align:left;width:100%;line-height:1.5}
.choice.correct{border-color:#a7d8bd;background:rgba(81,151,111,.16)}
.choice.wrong{animation:shake .28s}
@keyframes shake{25%,75%{transform:translateX(-4px)}50%{transform:translateX(4px)}}
.feedback{min-height:25px;color:var(--gold);font:13px Arial,sans-serif;margin-top:12px}
.hidden{display:none!important}
.progress-wrap{height:3px;background:#ffffff12;border-radius:10px;overflow:hidden;margin:18px 0 25px}
.progress{height:100%;width:0;background:linear-gradient(90deg,var(--violet),var(--gold));transition:width .7s ease}
.symbol{font-size:36px;color:var(--gold);text-align:center;margin:0 0 10px}
.center{text-align:center}
.final-gate{padding:35px 20px;text-align:center}
.lock{font-size:48px;display:block;margin:0 auto 18px;filter:drop-shadow(0 0 20px #b8a5ff55);animation:lockGlow 3s ease-in-out infinite}
@keyframes lockGlow{50%{filter:drop-shadow(0 0 25px #e8cf9b88);transform:translateY(-3px)}}
#letterSection{margin-top:34px}
.envelope-stage{height:190px;display:flex;align-items:center;justify-content:center;perspective:900px;overflow:hidden}
.envelope{position:relative;width:160px;height:108px;background:linear-gradient(145deg,#e8d8b2,#bca475);border-radius:4px;box-shadow:0 0 45px #e8cf9b22;transform:translateY(30px) scale(.8);opacity:0}
.envelope.show{animation:envelopeArrive 1.2s cubic-bezier(.2,.8,.2,1) forwards}
@keyframes envelopeArrive{to{opacity:1;transform:translateY(0) scale(1)}}
.envelope:before{content:"";position:absolute;inset:0;background:linear-gradient(32deg,transparent 49%,#9c8359 50%,transparent 51%),linear-gradient(-32deg,transparent 49%,#b19a6c 50%,transparent 51%);opacity:.65}
.flap{position:absolute;left:0;top:0;width:0;height:0;border-left:80px solid transparent;border-right:80px solid transparent;border-top:62px solid #f0e2c2;transform-origin:top;z-index:2;filter:drop-shadow(0 2px 2px #6c5836)}
.envelope.open .flap{animation:openFlap .9s ease forwards}
@keyframes openFlap{to{transform:rotateX(180deg);z-index:0}}
.seal{position:absolute;z-index:3;left:calc(50% - 15px);top:40px;width:30px;height:30px;border-radius:50%;background:#783b4d;color:#f8dfc7;display:grid;place-items:center;font-size:15px;box-shadow:0 2px 8px #4a2530}
.envelope.open .seal{animation:sealFade .5s .25s forwards}
@keyframes sealFade{to{opacity:0;transform:scale(.4)}}
.letter-card{position:relative;overflow:hidden;border:1px solid #d9c49a66;border-radius:16px;background:linear-gradient(145deg,#f0e5ce,#dfcfad);color:#332a28;padding:clamp(23px,6vw,43px);box-shadow:0 20px 80px #0005;opacity:0;transform:translateY(25px);max-height:0}
.letter-card.reveal{animation:letterReveal 1s ease forwards;max-height:3000px}
@keyframes letterReveal{to{opacity:1;transform:translateY(0)}}
.letter-card:before{content:"";position:absolute;inset:10px;border:1px solid #8d75554a;border-radius:9px;pointer-events:none}
.letter-head{font:10px Arial,sans-serif;letter-spacing:.2em;text-transform:uppercase;color:#806b50;text-align:center;margin:0 0 25px}
.letter-card h3{font-weight:normal;text-align:center;font-size:clamp(21px,5vw,28px);line-height:1.35;margin:0 0 24px;color:#352929}
.letter-card p{position:relative;color:#433532;font-size:clamp(15px,3.8vw,17px);line-height:1.85;margin:0 0 18px;opacity:0;transform:translateY(10px)}
.letter-card p.visible{animation:paragraphIn .75s ease forwards}
@keyframes paragraphIn{to{opacity:1;transform:translateY(0)}}
.letter-card strong{color:#6b3945;font-weight:normal;font-style:italic}
.signature{text-align:right!important;margin-top:26px!important;color:#6b3945!important;font-style:italic}
.end-note{text-align:center;color:var(--muted);font:11px Arial,sans-serif;letter-spacing:.1em;margin-top:30px;line-height:1.8}
.footer{text-align:center;color:#6e7597;font:10px Arial,sans-serif;letter-spacing:.16em;margin-top:50px}
@media(max-width:480px){
 main{padding:14px 13px 45px}
 header{padding-top:26px}
 .panel{border-radius:14px}
 p{font-size:15px}
 .envelope-stage{height:160px}
}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{animation-duration:.01ms!important;animation-iteration-count:1!important;scroll-behavior:auto!important;transition-duration:.01ms!important}}
</style>
</head>
<body>
<div id="stars" aria-hidden="true"></div><div class="aurora" aria-hidden="true"></div>
<main>
<header>
  <div class="kicker">секретный архив · дело № 003</div>
  <h1>За пределами архива</h1>
  <div class="subtitle">последняя глава расследования</div>
  <div class="rule"></div>
  <p class="muted">Некоторые тайны существуют не для того, чтобы их раскрыли сразу. Иногда к ответу ведут детали, которые легко пропустить.</p>
</header>
<div class="progress-wrap" aria-label="Прогресс расследования"><div class="progress" id="progress"></div></div>

<section class="panel" id="intro">
  <div class="small-label">входящее сообщение · неизвестный источник</div>
  <h2>Ты дошла до последнего дела</h2>
  <p>В предыдущих главах ты находила знаки, читала между строк и собирала подсказки. Теперь осталось выяснить, что на самом деле скрывается за этим расследованием.</p>
  <p class="muted">Не спеши. Здесь нет таймера, а правильный ответ не обязательно лежит на поверхности.</p>
  <div class="center"><button class="primary" id="startBtn">начать расследование →</button></div>
</section>

<section class="panel hidden" id="step1">
  <div class="small-label">файл 01 · наблюдение</div>
  <div class="symbol">⌕</div>
  <h2>Что остаётся между строк?</h2>
  <p>Иногда человек говорит совсем немного, но его поступки, внимание к мелочам и время, которое он тратит, могут сказать больше длинных объяснений.</p>
  <p><strong>Какой способ лучше всего помогает понять искренность намерений?</strong></p>
  <div class="choices">
    <button class="choice" data-answer="wrong">Красивые обещания, которые звучат убедительно</button>
    <button class="choice" data-answer="right">Поступки, которые подтверждают слова</button>
    <button class="choice" data-answer="wrong">Попытка угадать чужие мысли без разговора</button>
  </div>
  <div class="feedback" aria-live="polite"></div>
</section>

<section class="panel hidden" id="step2">
  <div class="small-label">файл 02 · зашифрованный вопрос</div>
  <div class="symbol">☾</div>
  <h2>След неизвестного автора</h2>
  <p>Автор оставил короткую подсказку:</p>
  <blockquote style="border-left:1px solid var(--gold);padding-left:18px;color:var(--gold);font-style:italic;line-height:1.8">«Именно это заставляет искать смысл там, где другие видят лишь обычные детали»</blockquote>
  <p>Как называется желание узнавать больше, задавать вопросы и открывать неизвестное?</p>
  <div class="choices">
    <button class="choice" data-answer="wrong">Равнодушие</button>
    <button class="choice" data-answer="right">Интерес</button>
    <button class="choice" data-answer="wrong">Привычка</button>
  </div>
  <div class="feedback" aria-live="polite"></div>
</section>

<section class="panel hidden" id="step3">
  <div class="small-label">файл 03 · последняя проверка</div>
  <div class="symbol">✦</div>
  <h2>Самая важная деталь</h2>
  <p>Ты собрала все подсказки. Но последнее сообщение звучит иначе:</p>
  <blockquote style="border-left:1px solid var(--gold);padding-left:18px;color:var(--gold);font-style:italic;line-height:1.8">«Не всё, что имеет значение, можно доказать загадкой. Иногда честнее всего — просто сказать это своими словами»</blockquote>
  <p>Что должен сделать человек, если хочет, чтобы ему поверили?</p>
  <div class="choices">
    <button class="choice" data-answer="wrong">Найти идеальные слова и больше ничего не делать</button>
    <button class="choice" data-answer="wrong">Требовать, чтобы ему поверили сразу</button>
    <button class="choice" data-answer="right">Быть искренним и подтверждать слова поступками</button>
  </div>
  <div class="feedback" aria-live="polite"></div>
</section>

<section class="panel hidden final-gate" id="gate">
  <span class="lock">⌑</span>
  <div class="small-label">доступ разрешён</div>
  <h2>Расследование завершено</h2>
  <p>Ты нашла ответы, но главное сообщение не было спрятано в шифре. Оно ждало момента, когда загадки закончатся.</p>
  <p class="muted">Следующий файл отличается от остальных. В нём нет вопросов и не нужно ничего доказывать. Только письмо, которое автор решил оставить лично.</p>
  <button class="primary" id="openLetterBtn">открыть последнее сообщение ✉</button>
</section>

<section class="hidden" id="letterSection">
  <div class="panel center" id="letterIntro">
    <div class="small-label">личное сообщение · без шифра</div>
    <h2>Для тебя</h2>
    <p class="muted">Это письмо не было частью расследования. Оно появилось здесь потому, что некоторые мысли заслуживают отдельной страницы.</p>
  </div>
  <div class="envelope-stage"><div class="envelope" id="envelope"><div class="flap"></div><div class="seal">✦</div></div></div>
  <article class="letter-card" id="letter">
    <div class="letter-head">последняя страница · от неизвестного автора</div>
    <h3>письмо, которое не было частью расследования</h3>
    <p>если ты дошла до этой страницы, значит, пора ненадолго оставить загадки и сказать кое-что от себя</p>
    <p>я не знаю, существуют ли слова, способные описать человека, который прекрасен не только внешностью, но и тем особенным ощущением, которое оставляет после себя</p>
    <p>но, говоря о тебе, мне кажется, что даже самых красивых слов будет недостаточно</p>
    <p>ты первая, для кого я решил создать нечто подобное, собрать маленькую историю из загадок, деталей и скрытых смыслов, и, если честно, мне бы хотелось, чтобы ты осталась единственной, для кого я когда-либо создам историю именно такого рода</p>
    <p>не потому, что жду чего-то взамен, а потому, что некоторые вещи хочется делать для кого-то особенного</p>
    <p><strong>но есть кое-что ещё</strong></p>
    <p>возможно, ты знаешь меня не с самой лучшей стороны, и, возможно, у тебя уже сложилось обо мне определённое мнение</p>
    <p>я не стану пытаться изменить его красивыми словами, ведь слова сами по себе ничего не доказывают</p>
    <p><strong>но прошлое — это ещё не вся история о человеке</strong></p>
    <p>я не прошу тебя смотреть на меня иначе лишь потому, что я создал этот сайт, мне бы хотелось, чтобы, если ты когда-нибудь увидишь во мне что-то хорошее, то это было благодаря моим поступкам, а не обещаниям</p>
    <p>ведь самое ценное — не казаться лучше в чьих-то глазах, а действительно становиться человеком, которого не нужно оправдывать словами</p>
    <p>а почему главной героиней этой истории стала именно ты?</p>
    <p>потому что ты действительно прекрасна, и мне захотелось сказать тебе об этом не обычным сообщением, которое затеряется среди других, а чем-то, что запомнится хотя бы небольшой тёплой эмоцией</p>
    <p>и если ты улыбнулась хотя бы раз, значит, всё это было не зря</p>
    <p class="signature">с теплом, твой пока ещё неизвестный автор</p>
  </article>
  <div class="end-note hidden" id="endNote">ДЕЛО № 003 ЗАКРЫТО<br>но у каждой истории остаётся продолжение — в памяти</div>
</section>

<div class="footer">АРХИВ · ДОСЬЕ 003 · КОНЕЦ ЗАПИСИ</div>
</main>
<script>
(function(){
  const starRoot=document.getElementById('stars');
  for(let i=0;i<95;i++){
    const s=document.createElement('i');s.className='star';
    s.style.left=(Math.random()*100)+'%';s.style.top=(Math.random()*100)+'%';
    s.style.animationDelay=(Math.random()*4)+'s';
    s.style.animationDuration=(2+Math.random()*4)+'s';
    s.style.opacity=(.15+Math.random()*.55).toFixed(2);
    starRoot.appendChild(s);
  }
  const progress=document.getElementById('progress');
  const sections=['intro','step1','step2','step3','gate'];
  function show(id){document.getElementById(id).classList.remove('hidden');setTimeout(()=>document.getElementById(id).scrollIntoView({behavior:'smooth',block:'center'}),100)}
  function setProgress(n){progress.style.width=(n/5*100)+'%'}
  document.getElementById('startBtn').addEventListener('click',()=>{document.getElementById('intro').classList.add('hidden');show('step1');setProgress(1)});
  document.querySelectorAll('.choices').forEach(group=>{
    group.querySelectorAll('.choice').forEach(btn=>{
      btn.addEventListener('click',()=>{
        if(group.dataset.done)return;
        const feedback=group.parentElement.querySelector('.feedback');
        if(btn.dataset.answer==='right'){
          group.dataset.done='true';btn.classList.add('correct');
          group.querySelectorAll('button').forEach(b=>b.disabled=true);
          feedback.textContent='Ответ принят. Файл расшифрован.';
          const current=group.closest('section').id;
          const next={step1:'step2',step2:'step3',step3:'gate'}[current];
          const count={step1:2,step2:3,step3:4}[current];
          setProgress(count);
          setTimeout(()=>{if(next)show(next)},700);
        }else{
          btn.classList.remove('wrong');void btn.offsetWidth;btn.classList.add('wrong');
          feedback.textContent='Это не совсем то. Попробуй ещё раз.';
        }
      });
    });
  });
  document.getElementById('openLetterBtn').addEventListener('click',()=>{
    document.getElementById('gate').classList.add('hidden');
    show('letterSection');setProgress(1);
    const env=document.getElementById('envelope');
    const letter=document.getElementById('letter');
    setTimeout(()=>env.classList.add('show'),250);
    setTimeout(()=>env.classList.add('open'),1450);
    setTimeout(()=>{
      letter.classList.add('reveal');
      const paragraphs=[...letter.querySelectorAll('p')];
      paragraphs.forEach((p,i)=>setTimeout(()=>p.classList.add('visible'),850+i*430));
      setTimeout(()=>{
        document.getElementById('endNote').classList.remove('hidden');
        progress.style.width='100%';
      },850+paragraphs.length*430+500);
    },2100);
  });
})();
</script>
</body>
</html>
