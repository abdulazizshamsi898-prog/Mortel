<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#062E29">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-title" content="مُرَتِّل">
<meta name="format-detection" content="telephone=no">
<title>مُرَتِّل — المصحف المدني وتصحيح التلاوة</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Amiri+Quran&family=Amiri:wght@400;700&family=Aref+Ruqaa:wght@400;700&family=IBM+Plex+Sans+Arabic:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
/* ═══════════════════════════════════════════════════════════════
   مُرَتِّل 12 — الهوية: ليل زمرّدي، ورق عاجي، ذهب قديم
   ═══════════════════════════════════════════════════════════════ */
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}

:root{
  --bg:#EFEADB; --bg-soft:#E6DFC9; --surface:#FFFCF3; --surface-2:#F7F1E0;
  --ink:#0E1F1B; --ink-2:#435750; --ink-3:#7D8F88;
  --line:rgba(14,60,50,.12); --line-strong:rgba(14,60,50,.26);
  --primary:#0A6A5D; --primary-2:#19B5A0; --primary-soft:#DAEFE9;
  --gold:#A57A10; --gold-soft:#F2E4B9;
  --ok:#057A55; --ok-bg:rgba(5,122,85,.13);
  --bad:#B42318; --bad-bg:rgba(180,35,24,.11);
  --mushaf-bg:#FCF6E2; --mushaf-line:#B08A1E;
  --shadow-1:0 1px 3px rgba(14,31,27,.08);
  --shadow-2:0 18px 50px rgba(14,31,27,.18);
  --r-s:12px; --r-m:18px; --r-l:28px;
  --quran-fs:30px;
  --dock-h:110px;
  --ease:cubic-bezier(.22,.8,.3,1);
  --ui:'IBM Plex Sans Arabic','Amiri',sans-serif;
  --display:'Aref Ruqaa','Amiri',serif;
}
body.dark{
  --bg:#060E0C; --bg-soft:#0E1A17; --surface:#0F1C19; --surface-2:#0A1512;
  --ink:#EAF2EF; --ink-2:#A4B7B0; --ink-3:#6F827C;
  --line:rgba(120,230,210,.13); --line-strong:rgba(120,230,210,.3);
  --primary:#34E0C8; --primary-2:#7FF3E0; --primary-soft:#11322C;
  --gold:#E6BF5A; --gold-soft:#33290E;
  --ok:#3DDC97; --ok-bg:rgba(61,220,151,.16);
  --bad:#FF7B72; --bad-bg:rgba(255,123,114,.16);
  --mushaf-bg:#0E1B17; --mushaf-line:#D4AC3C;
  --shadow-1:0 1px 3px rgba(0,0,0,.45);
  --shadow-2:0 18px 50px rgba(0,0,0,.6);
}

html{-webkit-text-size-adjust:100%;scroll-padding-top:140px}
html,body{min-height:100%;overflow-x:hidden}
body{
  font-family:var(--ui);
  background:var(--bg);color:var(--ink);line-height:1.6;
  -webkit-font-smoothing:antialiased;
  background-image:
    radial-gradient(900px 420px at 85% -8%,rgba(25,181,160,.14),transparent 60%),
    radial-gradient(700px 400px at 0% 35%,rgba(176,138,30,.09),transparent 60%);
  background-attachment:fixed;
}
button{font-family:inherit;cursor:pointer;color:inherit;border:none;background:none}
button:focus-visible,select:focus-visible,input:focus-visible,a:focus-visible,[tabindex]:focus-visible{outline:3px solid var(--primary-2);outline-offset:2px}

/* ─── الشاشة الافتتاحية ─── */
#splash{position:fixed;inset:0;z-index:2000;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:16px;
  background:radial-gradient(circle at 50% 35%,#13897B,#074D45 60%,#03211D);color:#fff;transition:opacity .7s var(--ease);padding:24px;text-align:center}
#splash.hide{opacity:0;pointer-events:none}
.splash-title{font-family:var(--display);font-size:78px;font-weight:700;text-shadow:0 8px 34px rgba(0,0,0,.4);animation:fadeUp 1s var(--ease) both}
.splash-verse{font-family:'Amiri Quran','Amiri',serif;font-size:20px;line-height:2.1;max-width:340px;color:#F6E7B4;animation:fadeUp 1.2s .2s var(--ease) both}
.splash-spin{width:34px;height:34px;border-radius:50%;border:3px solid rgba(255,255,255,.25);border-top-color:#F6E7B4;animation:spin .9s linear infinite;margin-top:8px}
@keyframes spin{to{transform:rotate(360deg)}}
@keyframes fadeUp{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}

/* ─── الشريط العلوي ─── */
.topbar{position:sticky;top:0;z-index:200;display:flex;align-items:center;gap:10px;
  padding:calc(8px + env(safe-area-inset-top)) 12px 10px;
  background:color-mix(in srgb,var(--surface) 78%,transparent);backdrop-filter:blur(22px) saturate(170%);-webkit-backdrop-filter:blur(22px) saturate(170%);
  border-bottom:1px solid var(--line)}
.readbar{position:absolute;inset-inline:0;bottom:-1px;height:2px;background:transparent;overflow:hidden}
.readbar i{display:block;height:100%;width:0;background:linear-gradient(270deg,var(--gold),var(--primary-2));transition:width .5s var(--ease);float:right}
.icon-btn{width:44px;height:44px;border-radius:50%;display:grid;place-items:center;border:1px solid var(--line);background:color-mix(in srgb,var(--surface) 70%,transparent);
  color:var(--ink-2);font-size:18px;transition:background .2s,color .2s,transform .15s;box-shadow:var(--shadow-1)}
.icon-btn:hover{background:var(--primary-soft);color:var(--primary)}
.icon-btn:active{transform:scale(.92)}
.icon-btn[aria-pressed="true"]{background:var(--primary);color:#fff;border-color:var(--primary)}
.burger{flex-direction:column;gap:4.5px;display:flex;align-items:center;justify-content:center}
.burger i{display:block;width:19px;height:2.4px;border-radius:2px;background:currentColor}
.brand{display:flex;flex-direction:column;line-height:1.1;margin-inline-end:auto}
.brand b{font-family:var(--display);font-size:28px;background:linear-gradient(120deg,var(--primary),var(--gold));-webkit-background-clip:text;background-clip:text;color:transparent}
.brand small{font-size:11px;color:var(--ink-3)}
.top-actions{display:flex;gap:6px}

/* ─── التنقل ─── */
.navbar{display:flex;flex-wrap:wrap;gap:8px;align-items:center;padding:14px 12px 4px;max-width:860px;margin:0 auto}
.field{display:flex;align-items:center;gap:6px;flex:1 1 150px;min-width:0}
.field label{font-size:12px;font-weight:600;color:var(--ink-2);white-space:nowrap}
select,.num-input{font-family:inherit;font-size:14px;font-weight:600;color:var(--ink);background-color:var(--surface);border:1px solid var(--line);
  border-radius:14px;padding:10px 12px;min-width:0;flex:1}
select{appearance:none;-webkit-appearance:none;padding-inline-end:30px;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'%3E%3Cpath fill='%2385928D' d='M6 8.5 1.5 4h9z'/%3E%3C/svg%3E");
  background-repeat:no-repeat;background-position:left 12px center}
.font-ctrl{display:flex;gap:6px}
.chip-btn{min-width:42px;height:42px;padding:0 10px;border-radius:50%;border:1px solid var(--line);background:var(--surface);font-weight:700;font-size:14px;color:var(--ink-2)}
.chip-btn:hover{border-color:var(--primary);color:var(--primary)}

/* ─── الإحصاءات ─── */
.stats{display:flex;background:var(--surface);border:1px solid var(--line);border-radius:999px;padding:6px;margin:12px 0;box-shadow:var(--shadow-1)}
.stat{flex:1;text-align:center;padding:3px 2px}
.stat+.stat{border-inline-start:1px solid var(--line)}
.stat b{display:block;font-family:var(--display);font-size:22px;color:var(--primary);line-height:1.2}
.stat span{font-size:11px;color:var(--ink-3);font-weight:600}

main{max-width:860px;margin:0 auto;padding:6px 12px calc(var(--dock-h) + 24px + env(safe-area-inset-bottom))}
.notice{display:none;margin:10px 0;padding:12px 16px;border-radius:var(--r-s);background:var(--bad-bg);color:var(--bad);font-size:14px;font-weight:600}
.notice.on{display:block}

/* ─── المنقّل ─── */
.pager{display:flex;align-items:center;gap:10px;margin:8px 0}
.pg-btn{width:48px;height:48px;border-radius:50%;background:linear-gradient(145deg,var(--primary),var(--primary-2));color:#fff;display:grid;place-items:center;
  box-shadow:0 8px 20px rgba(10,106,93,.3);transition:transform .15s,opacity .2s;flex-shrink:0}
.pg-btn:active{transform:scale(.92)}
.pg-btn:disabled{opacity:.3;box-shadow:none;cursor:not-allowed}
.pg-btn svg{width:22px;height:22px;stroke:currentColor;fill:none;stroke-width:2.6;stroke-linecap:round;stroke-linejoin:round}
.pg-mid{flex:1;display:flex;flex-direction:column;gap:4px;min-width:0}
.pg-label{display:flex;justify-content:space-between;align-items:baseline;font-size:12px;color:var(--ink-2);font-weight:600}
.pg-label button{font-family:var(--display);font-size:21px;color:var(--ink);padding:0 6px;border-bottom:2px dotted var(--gold)}
input[type=range]{width:100%;height:28px;accent-color:var(--gold);direction:rtl;background:transparent}

/* ─── صفحة المصحف ─── */
.mushaf{position:relative;border-radius:22px;padding:30px 20px 22px;margin:14px 6px;min-height:60vh;overflow:hidden;touch-action:pan-y;
  background:radial-gradient(circle at 50% 0,rgba(255,255,255,.6),transparent 60%),
    repeating-linear-gradient(0deg,rgba(176,138,30,.03) 0 2px,transparent 2px 5px),var(--mushaf-bg);
  box-shadow:0 0 0 1px var(--mushaf-line),0 0 0 7px var(--mushaf-bg),0 0 0 8px var(--mushaf-line),0 26px 60px rgba(120,90,10,.2)}
body.dark .mushaf{background:radial-gradient(circle at 50% 0,rgba(52,224,200,.07),transparent 60%),var(--mushaf-bg);
  box-shadow:0 0 0 1px var(--mushaf-line),0 0 0 7px var(--mushaf-bg),0 0 0 8px var(--mushaf-line),0 26px 60px rgba(0,0,0,.6)}
.mushaf::before{content:'';position:absolute;inset:10px;border:1px dashed var(--mushaf-line);opacity:.35;border-radius:14px;pointer-events:none}
.mushaf.turn-next{animation:turnNext .34s var(--ease)}
.mushaf.turn-prev{animation:turnPrev .34s var(--ease)}
@keyframes turnNext{from{opacity:0;transform:translateX(-26px)}to{opacity:1;transform:none}}
@keyframes turnPrev{from{opacity:0;transform:translateX(26px)}to{opacity:1;transform:none}}
.page-head,.page-foot{display:flex;justify-content:space-between;align-items:center;font-family:var(--display);color:var(--mushaf-line);font-size:17px}
.page-head{padding-bottom:10px;margin-bottom:12px;border-bottom:1.5px solid var(--mushaf-line)}
.page-foot{justify-content:center;margin-top:16px;font-size:21px;letter-spacing:2px}
.page-foot::before,.page-foot::after{content:'';width:48px;height:1px;background:var(--mushaf-line);margin:0 12px;opacity:.6}
.surah-banner{position:relative;text-align:center;font-family:var(--display);font-size:1.3em;color:var(--mushaf-line);margin:18px 4px 8px;padding:12px;
  border:1.5px solid var(--mushaf-line);border-radius:14px;
  background:linear-gradient(90deg,transparent,color-mix(in srgb,var(--mushaf-line) 20%,transparent),transparent)}
.surah-banner::before,.surah-banner::after{content:'✦';position:absolute;top:50%;transform:translateY(-50%);font-size:16px}
.surah-banner::before{inset-inline-start:16px}.surah-banner::after{inset-inline-end:16px}
.bismillah{text-align:center;font-family:'Amiri Quran','Amiri',serif;font-size:calc(var(--quran-fs) * .95);color:var(--gold);padding:8px 0 4px;line-height:2}
.flow{font-family:'Amiri Quran','Amiri',serif;font-size:var(--quran-fs);line-height:2.5;text-align:justify;text-align-last:center;color:var(--ink)}
.flow.tail{text-align-last:start}
.word{display:inline;padding:2px 3px;border-radius:9px;cursor:pointer;transition:color .18s,background .18s}
.word:hover{background:color-mix(in srgb,var(--primary-2) 12%,transparent)}
.word.correct{color:var(--ok);text-shadow:0 0 18px var(--ok-bg)}
.word.wrong{color:var(--bad);background:var(--bad-bg);border-bottom:2px wavy var(--bad)}
.word.next{background:linear-gradient(transparent 72%,color-mix(in srgb,var(--gold) 55%,transparent) 72%);animation:caret 1.1s ease-in-out infinite}
@keyframes caret{50%{background-color:color-mix(in srgb,var(--primary-2) 16%,transparent)}}
.memorize .word:not(.correct):not(.wrong){color:transparent;background:var(--gold-soft);box-shadow:inset 0 0 0 1px var(--line-strong);text-shadow:none}
.memorize .word.next{box-shadow:inset 0 0 0 2px var(--primary-2)}
.ayah-no{display:inline-grid;place-items:center;min-width:34px;height:34px;padding:0 6px;margin:0 4px;border-radius:50%;
  font-size:14px;font-weight:700;color:var(--mushaf-line);vertical-align:middle;line-height:1;font-family:var(--display);text-align-last:center;
  background:radial-gradient(circle,var(--mushaf-bg) 55%,transparent 56%),conic-gradient(var(--mushaf-line),var(--gold-soft),var(--mushaf-line),var(--gold-soft),var(--mushaf-line));
  box-shadow:0 0 0 1px var(--mushaf-line) inset}
.ayah-no.done{background:radial-gradient(circle,var(--ok) 57%,transparent 58%),conic-gradient(var(--ok),var(--ok-bg),var(--ok));color:#fff}
.ayah-no.miss{background:radial-gradient(circle,var(--bad) 57%,transparent 58%),conic-gradient(var(--bad),var(--bad-bg),var(--bad));color:#fff}
.skeleton{display:grid;gap:14px;padding:30px 6px}
.skeleton i{height:22px;border-radius:8px;background:linear-gradient(90deg,var(--bg-soft),var(--surface),var(--bg-soft));background-size:200% 100%;animation:shimmer 1.3s linear infinite}
@keyframes shimmer{to{background-position:-200% 0}}
.hint-bar{font-size:13px;color:var(--ink-2);text-align:center;margin:8px 0 2px}

/* ─── الأسفل الثابت ─── */
.dock{position:fixed;inset-inline:0;bottom:0;z-index:300;pointer-events:none}
.dock>*{pointer-events:auto}
.player{display:none;margin:0 10px 8px;background:color-mix(in srgb,var(--surface) 88%,transparent);backdrop-filter:blur(24px);-webkit-backdrop-filter:blur(24px);
  border:1px solid var(--line);border-radius:26px;box-shadow:var(--shadow-2);padding:10px 14px}
.player.on{display:block}
.player-row{display:flex;align-items:center;gap:8px;max-width:860px;margin:0 auto}
.player-title{flex:1;min-width:0;font-weight:600;font-size:14px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.player-title small{display:block;font-weight:400;font-size:11.5px;color:var(--ink-3)}
.pl-btn{width:38px;height:38px;border-radius:50%;display:grid;place-items:center;color:var(--ink-2);font-size:15px}
.pl-btn:hover{background:var(--primary-soft);color:var(--primary)}
.pl-play{width:46px;height:46px;background:linear-gradient(145deg,var(--primary),var(--primary-2));color:#fff;font-size:17px}
.pl-play:hover{background:linear-gradient(145deg,var(--primary),var(--primary-2));color:#fff;filter:brightness(1.08)}
.pl-seek{display:flex;align-items:center;gap:8px;max-width:860px;margin:4px auto 0;font-size:11.5px;color:var(--ink-3);direction:ltr}
.pl-seek input{flex:1;direction:ltr}
.mic-bar{margin:0 10px calc(10px + env(safe-area-inset-bottom));border:1px solid var(--line);border-radius:32px;padding:10px 12px;
  background:color-mix(in srgb,var(--surface) 84%,transparent);backdrop-filter:blur(24px) saturate(170%);-webkit-backdrop-filter:blur(24px) saturate(170%);box-shadow:var(--shadow-2)}
.mic-inner{max-width:860px;margin:0 auto;display:flex;align-items:center;gap:12px}
.mic-btn{position:relative;width:64px;height:64px;border-radius:50%;flex-shrink:0;color:#fff;display:grid;place-items:center;
  background:radial-gradient(circle at 30% 25%,var(--primary-2),var(--primary) 72%);box-shadow:0 10px 26px rgba(10,106,93,.45),inset 0 2px 6px rgba(255,255,255,.35);transition:transform .15s}
.mic-btn:active{transform:scale(.93)}
.mic-btn.rec{background:radial-gradient(circle at 30% 25%,#FF8A8A,#D92D2D 72%);box-shadow:0 10px 28px rgba(220,38,38,.45),inset 0 2px 6px rgba(255,255,255,.3)}
.mic-btn.rec::after,.mic-btn.rec::before{content:'';position:absolute;inset:-6px;border-radius:50%;border:2px solid #E23B3B;animation:ring 1.6s ease-out infinite}
.mic-btn.rec::before{animation-delay:.6s}
@keyframes ring{0%{transform:scale(.92);opacity:.8}100%{transform:scale(1.4);opacity:0}}
.mic-btn svg{width:27px;height:27px;fill:none;stroke:currentColor;stroke-width:2.2;stroke-linecap:round;stroke-linejoin:round}
.mic-info{flex:1;min-width:0}
.m-status{font-size:14.5px;font-weight:600;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.m-live{font-family:'Amiri',serif;font-size:16px;color:var(--primary);white-space:nowrap;overflow:hidden;text-overflow:ellipsis;min-height:1.5em}
.wave{display:none;gap:3px;align-items:center;height:18px}
.mic-bar.live .wave{display:flex}
.wave i{width:3px;border-radius:2px;background:var(--primary-2);height:4px;animation:eq 1s ease-in-out infinite}
.wave i:nth-child(2n){animation-delay:.15s}.wave i:nth-child(3n){animation-delay:.3s}.wave i:nth-child(4n){animation-delay:.45s}
@keyframes eq{0%,100%{height:4px}50%{height:17px}}
.reset-btn{width:44px;height:44px;border-radius:50%;border:1px solid var(--line-strong);background:var(--surface);font-size:20px;color:var(--ink-2);flex-shrink:0;display:grid;place-items:center}
.reset-btn:hover{border-color:var(--primary);color:var(--primary)}

/* ─── القائمة الجانبية ─── */
.scrim{position:fixed;inset:0;z-index:700;background:rgba(4,14,12,.55);backdrop-filter:blur(4px);opacity:0;pointer-events:none;transition:opacity .25s}
.scrim.on{opacity:1;pointer-events:auto}
.drawer{position:fixed;top:0;bottom:0;inset-inline-start:0;z-index:800;width:min(330px,88vw);background:var(--surface);
  box-shadow:var(--shadow-2);transform:translateX(100%);transition:transform .32s var(--ease);display:flex;flex-direction:column;padding-top:env(safe-area-inset-top)}
.drawer.on{transform:none}
.sheet-head{display:flex;align-items:center;justify-content:space-between;padding:16px 18px;border-bottom:1px solid var(--line)}
.sheet-head h2{font-family:var(--display);font-size:26px;color:var(--primary)}
.drawer-body{padding:16px;overflow-y:auto;flex:1;display:grid;gap:12px;align-content:start}
.sec-title{font-size:12px;font-weight:600;color:var(--ink-3);margin:4px 2px 8px}
.reciter-card{display:flex;align-items:center;gap:12px;width:100%;text-align:start;padding:14px;border-radius:var(--r-m);border:1px solid var(--line-strong);
  background:linear-gradient(135deg,var(--primary-soft),var(--surface));transition:transform .15s,border-color .2s}
.reciter-card:hover{border-color:var(--primary)}
.reciter-card:active{transform:scale(.985)}
.avatar{width:50px;height:50px;border-radius:50%;display:grid;place-items:center;flex-shrink:0;font-family:var(--display);font-size:28px;font-weight:700;color:#fff;
  background:linear-gradient(135deg,var(--primary),var(--gold))}
.reciter-card b{display:block;font-size:17px}
.reciter-card small{color:var(--ink-2);font-size:12.5px}

/* ─── بطاقة سورة طه ─── */
.taha-hero{position:relative;overflow:hidden;width:100%;display:flex;align-items:center;gap:14px;text-align:start;padding:18px;border-radius:26px;color:#fff;
  background:radial-gradient(circle at 88% 0,rgba(230,191,90,.45),transparent 55%),linear-gradient(135deg,#064E45,#0A6A5D 60%,#12907F);box-shadow:0 16px 38px rgba(6,78,69,.4);transition:transform .15s}
.taha-hero:active{transform:scale(.985)}
.taha-hero .big{font-family:var(--display);font-size:56px;line-height:1;color:#F6E7B4}
.taha-hero b{display:block;font-size:17px}
.taha-hero small{opacity:.88;font-size:12.5px}
.taha-hero .go{margin-inline-start:auto;width:48px;height:48px;border-radius:50%;background:#F6E7B4;color:#064E45;display:grid;place-items:center;font-size:18px;flex-shrink:0}
.taha-tools{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:14px}
.pill-link{display:inline-flex;align-items:center;gap:6px;padding:9px 14px;border-radius:999px;border:1px solid var(--line-strong);font-size:13px;font-weight:600;color:var(--primary);background:var(--surface);text-decoration:none}
.pill-link:hover{background:var(--primary-soft)}
.custom-url{display:none;gap:8px;margin-bottom:14px}
.custom-url.on{display:flex}
.custom-url input{flex:1;direction:ltr;font-size:13px}
.custom-url button{padding:0 16px;border-radius:14px;background:var(--primary);color:#fff;font-weight:600;font-size:13px}

/* ─── لوحة القارئ ─── */
.sheet{position:fixed;inset:0;z-index:900;background:radial-gradient(800px 400px at 50% -10%,rgba(25,181,160,.16),transparent 60%),var(--bg);display:flex;flex-direction:column;transform:translateY(100%);visibility:hidden;
  transition:transform .35s var(--ease),visibility 0s .35s;padding-top:env(safe-area-inset-top)}
.sheet.on{transform:none;visibility:visible;transition:transform .35s var(--ease),visibility 0s}
.sheet-body{flex:1;overflow-y:auto;padding:14px 14px calc(140px + env(safe-area-inset-bottom));max-width:760px;width:100%;margin:0 auto}
.src-row{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:14px}
.seg{flex:1 1 140px;padding:10px 12px;border-radius:14px;border:1px solid var(--line-strong);background:var(--surface);font-size:13px;font-weight:600;color:var(--ink-2);text-align:center}
.seg[aria-pressed="true"]{background:var(--primary);border-color:var(--primary);color:#fff}
.seg small{display:block;font-weight:400;font-size:11px;opacity:.85}
.featured{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:14px}
.star-btn{display:flex;align-items:center;gap:8px;padding:10px 16px;border-radius:999px;background:var(--gold-soft);color:var(--gold);font-weight:600;font-size:15px;border:1px solid color-mix(in srgb,var(--gold) 40%,transparent)}
.search{width:100%;margin-bottom:12px;padding:12px 14px}
.surah-list{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:8px}
.s-item{display:flex;align-items:center;gap:10px;padding:10px 12px;border-radius:16px;background:var(--surface);border:1px solid var(--line);transition:border-color .2s,background .2s}
.s-item:hover{border-color:var(--primary)}
.s-item.playing{background:var(--primary-soft);border-color:var(--primary)}
.s-num{width:34px;height:34px;border-radius:50%;display:grid;place-items:center;background:var(--bg-soft);font-size:13px;font-weight:700;color:var(--ink-2);flex-shrink:0}
.s-item.playing .s-num{background:var(--primary);color:#fff}
.s-name{flex:1;min-width:0;font-weight:600;font-size:15px}
.s-name small{display:block;font-weight:400;color:var(--ink-3);font-size:11.5px}
.s-read{font-size:12px;color:var(--primary);font-weight:600;padding:5px 10px;border-radius:999px;border:1px solid var(--line-strong)}
.s-read:hover{background:var(--primary-soft)}
.s-item[hidden]{display:none}
.s-main{display:flex;align-items:center;gap:10px;flex:1;min-width:0;text-align:start}

/* ─── الإعدادات ─── */
.modal{position:fixed;inset:0;z-index:900;display:none;align-items:flex-end;justify-content:center;background:rgba(4,14,12,.55);backdrop-filter:blur(4px)}
.modal.on{display:flex}
.modal-card{width:100%;max-width:520px;background:var(--surface);border-radius:var(--r-l) var(--r-l) 0 0;padding:20px 20px calc(24px + env(safe-area-inset-bottom));max-height:88vh;overflow-y:auto;animation:rise .3s var(--ease)}
@keyframes rise{from{transform:translateY(40px);opacity:0}to{transform:none;opacity:1}}
.row{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:14px 0;border-bottom:1px solid var(--line)}
.row:last-child{border-bottom:none}
.row b{font-size:15px}
.row small{display:block;color:var(--ink-3);font-size:12px}
.toggle{position:relative;width:54px;height:32px;border-radius:16px;background:var(--line-strong);flex-shrink:0;transition:background .25s}
.toggle::after{content:'';position:absolute;top:4px;inset-inline-start:4px;width:24px;height:24px;border-radius:50%;background:#fff;box-shadow:0 2px 6px rgba(0,0,0,.25);transition:transform .25s var(--ease)}
.toggle[aria-checked="true"]{background:var(--primary)}
.toggle[aria-checked="true"]::after{transform:translateX(-22px)}
.seg-group{display:flex;gap:6px}
.seg-group .seg{flex:none;padding:8px 12px}
.goto-input{width:100%;font-size:22px;text-align:center;padding:12px;margin:10px 0}

.toast{position:fixed;left:50%;bottom:calc(var(--dock-h) + 18px + env(safe-area-inset-bottom));transform:translate(-50%,20px);z-index:1000;
  padding:11px 22px;border-radius:999px;background:var(--ink);color:var(--bg);font-size:14px;font-weight:600;opacity:0;pointer-events:none;
  transition:opacity .28s,transform .28s var(--ease);max-width:92vw;text-align:center}
.toast.on{opacity:1;transform:translate(-50%,0)}
.toast.ok{background:var(--ok);color:#fff}
.toast.bad{background:var(--bad);color:#fff}

.finish{position:fixed;inset:0;z-index:1100;display:none;flex-direction:column;align-items:center;justify-content:center;gap:16px;text-align:center;padding:30px;background:color-mix(in srgb,var(--bg) 96%,transparent);backdrop-filter:blur(20px)}
.finish.on{display:flex}
.finish h2{font-family:var(--display);font-size:36px;color:var(--primary)}
.finish .big{font-family:var(--display);font-size:72px;color:var(--ok);line-height:1}
.primary-btn{padding:14px 38px;border-radius:999px;background:linear-gradient(145deg,var(--primary),var(--primary-2));color:#fff;font-weight:600;font-size:15px;box-shadow:0 8px 22px rgba(10,106,93,.3)}

@media (max-width:640px){
  .brand small{display:none}
  .mushaf{padding:24px 12px 16px}
  .stat b{font-size:19px}
  .mic-btn{width:58px;height:58px}
  .pl-btn{width:34px;height:34px}
}
@media (prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms!important;transition-duration:.01ms!important}}
</style>
</head>
<body>

<div id="splash" role="status" aria-label="جارٍ التحميل">
  <div class="splash-title">مُرَتِّل</div>
  <div class="splash-verse">﴿ وَلَقَدْ يَسَّرْنَا الْقُرْآنَ لِلذِّكْرِ فَهَلْ مِن مُّدَّكِرٍ ﴾</div>
  <div class="splash-spin"></div>
</div>

<header class="topbar">
  <button class="icon-btn burger" id="burger" aria-label="فتح القائمة" aria-expanded="false" aria-controls="drawer">
    <i></i><i></i><i></i>
  </button>
  <div class="brand"><b>مُرَتِّل</b><small>المصحف المدني · طباعة مجمع الملك فهد</small></div>
  <div class="top-actions">
    <button class="icon-btn" id="btn-memorize" aria-pressed="false" title="وضع الحفظ" aria-label="وضع الحفظ">📖</button>
    <button class="icon-btn" id="btn-theme" title="الوضع الليلي" aria-label="تبديل الوضع الليلي">🌙</button>
    <button class="icon-btn" id="btn-settings" title="الإعدادات" aria-label="الإعدادات">⚙️</button>
  </div>
  <div class="readbar" aria-hidden="true"><i id="readbar"></i></div>
</header>

<div class="scrim" id="scrim"></div>
<aside class="drawer" id="drawer" aria-hidden="true" aria-label="القائمة">
  <div class="sheet-head">
    <h2>القائمة</h2>
    <button class="icon-btn" data-close="drawer" aria-label="إغلاق">✕</button>
  </div>
  <div class="drawer-body">
    <div class="sec-title">القرّاء</div>
    <button class="reciter-card" id="open-ayyub">
      <span class="avatar" aria-hidden="true">أ</span>
      <span><b>الشيخ محمد أيوب</b><small>إمام المسجد النبوي — رحمه الله</small></span>
    </button>
    <button class="taha-hero" id="drawer-taha">
      <span class="big">طه</span>
      <span><b>سورة طه · الشيخ محمد أيوب</b><small>استمع الآن</small></span>
      <span class="go">▶</span>
    </button>
  </div>
</aside>

<section class="sheet" id="ayyub-sheet" aria-hidden="true" aria-label="تلاوات الشيخ محمد أيوب">
  <div class="sheet-head">
    <h2>الشيخ محمد أيوب</h2>
    <button class="icon-btn" data-close="sheet" aria-label="إغلاق">✕</button>
  </div>
  <div class="sheet-body">
    <button class="taha-hero" id="taha-hero" style="margin-bottom:12px">
      <span class="big">طه</span>
      <span><b>قراءة محمد أيوب · سورة طه</b><small>الأكثر طلباً · تشغيل مباشر</small></span>
      <span class="go">▶</span>
    </button>
    <div class="taha-tools">
      <a class="pill-link" id="yt-link" target="_blank" rel="noopener">▶ أشهر مقاطع طه على يوتيوب</a>
      <button class="pill-link" id="taha-custom-toggle">🔗 رابط صوتي لطه</button>
    </div>
    <div class="custom-url" id="custom-url">
      <input class="num-input" id="taha-url" type="url" placeholder="https://…/020.mp3" aria-label="رابط ملف صوتي لسورة طه">
      <button id="taha-url-save">حفظ</button>
    </div>
    <div class="sec-title">مصدر التلاوة</div>
    <div class="src-row" id="src-row"></div>
    <div class="sec-title">من أبدع تلاواته</div>
    <div class="featured" id="featured"></div>
    <input class="num-input search" id="surah-search" type="search" placeholder="ابحث عن سورة…" aria-label="ابحث عن سورة" autocomplete="off">
    <div class="surah-list" id="surah-list"></div>
  </div>
</section>

<nav class="navbar" aria-label="التنقل في المصحف">
  <div class="field"><label for="sel-surah">السورة</label><select id="sel-surah"></select></div>
  <div class="field"><label for="sel-juz">الجزء</label><select id="sel-juz"></select></div>
  <div class="font-ctrl">
    <button class="chip-btn" id="font-dec" aria-label="تصغير الخط">أ−</button>
    <button class="chip-btn" id="font-inc" aria-label="تكبير الخط">أ+</button>
  </div>
</nav>

<main>
  <div class="notice" id="notice" role="alert"></div>

  <div class="stats" aria-live="polite">
    <div class="stat"><b id="st-ok">٠</b><span>صحيحة</span></div>
    <div class="stat"><b id="st-att">٠</b><span>محاولات</span></div>
    <div class="stat"><b id="st-acc">—</b><span>الدقة</span></div>
    <div class="stat"><b id="st-page">—</b><span>الصفحة</span></div>
  </div>

  <div class="pager" id="pager-top">
    <button class="pg-btn" data-page="prev" aria-label="الصفحة السابقة"><svg viewBox="0 0 24 24"><path d="M9 6l6 6-6 6"/></svg></button>
    <div class="pg-mid">
      <div class="pg-label"><span>صفحة</span><button id="pg-open" aria-label="الانتقال إلى صفحة">١</button><span>من ٦٠٤</span></div>
      <input type="range" id="pg-slider" min="1" max="604" value="1" aria-label="اختيار الصفحة">
    </div>
    <button class="pg-btn" data-page="next" aria-label="الصفحة التالية"><svg viewBox="0 0 24 24"><path d="M15 6l-6 6 6 6"/></svg></button>
  </div>

  <div class="hint-bar" id="hint-bar">اضغط أي كلمة لتبدأ منها، أو ابدأ القراءة وسيتعرّف التطبيق على موضعك</div>

  <article class="mushaf" id="mushaf" aria-live="off"></article>

  <div class="pager" id="pager-bottom">
    <button class="pg-btn" data-page="prev" aria-label="الصفحة السابقة"><svg viewBox="0 0 24 24"><path d="M9 6l6 6-6 6"/></svg></button>
    <div class="pg-mid" style="text-align:center;font-size:13px;color:var(--ink-2)">اسحب الصفحة لليمين للتالية أو استخدم الأسهم</div>
    <button class="pg-btn" data-page="next" aria-label="الصفحة التالية"><svg viewBox="0 0 24 24"><path d="M15 6l-6 6 6 6"/></svg></button>
  </div>
</main>

<div class="dock" id="dock">
  <div class="player" id="player" aria-label="مشغّل التلاوة">
    <div class="player-row">
      <button class="pl-btn" id="pl-prev" aria-label="السورة السابقة">⏭</button>
      <button class="pl-btn pl-play" id="pl-play" aria-label="تشغيل / إيقاف">▶</button>
      <button class="pl-btn" id="pl-next" aria-label="السورة التالية">⏮</button>
      <div class="player-title" id="pl-title">—<small id="pl-sub"></small></div>
      <button class="pl-btn" id="pl-speed" aria-label="سرعة التشغيل" style="font-size:12px;font-weight:700">1×</button>
      <button class="pl-btn" id="pl-read" aria-label="اقرأ السورة في المصحف" title="افتح السورة في المصحف">📖</button>
      <button class="pl-btn" id="pl-close" aria-label="إغلاق المشغّل">✕</button>
    </div>
    <div class="pl-seek"><span id="pl-cur">0:00</span><input type="range" id="pl-seek" min="0" max="1000" value="0" aria-label="موضع التشغيل"><span id="pl-dur">0:00</span></div>
  </div>
  <div class="mic-bar" id="mic-bar">
    <div class="mic-inner">
      <button class="mic-btn" id="mic-btn" aria-label="ابدأ التلاوة">
        <svg id="mic-svg" viewBox="0 0 24 24"><rect x="9" y="2" width="6" height="11" rx="3"/><path d="M5 10a7 7 0 0 0 14 0M12 19v3M8 22h8"/></svg>
      </button>
      <div class="mic-info">
        <div class="m-status" id="m-status" aria-live="polite">اضغط المايكروفون وابدأ القراءة</div>
        <div class="wave" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div>
        <div class="m-live" id="m-live" dir="rtl"></div>
      </div>
      <button class="reset-btn" id="btn-reset" aria-label="إعادة التلاوة من جديد" title="إعادة">↺</button>
    </div>
  </div>
</div>

<div class="toast" id="toast" role="status"></div>

<div class="modal" id="settings" aria-hidden="true">
  <div class="modal-card" role="dialog" aria-label="الإعدادات">
    <div class="sheet-head" style="padding:0 0 12px">
      <h2>الإعدادات</h2>
      <button class="icon-btn" data-close="modal" aria-label="إغلاق">✕</button>
    </div>
    <div class="row"><div><b>الوضع الليلي</b><small>مريح للعين في الظلام</small></div><button class="toggle" id="tg-dark" role="switch" aria-checked="false" aria-label="الوضع الليلي"></button></div>
    <div class="row"><div><b>وضع الحفظ</b><small>إخفاء الكلمات حتى تتلوها صحيحة</small></div><button class="toggle" id="tg-memorize" role="switch" aria-checked="false" aria-label="وضع الحفظ"></button></div>
    <div class="row"><div><b>تقليب الصفحة تلقائياً</b><small>عند إتمام الصفحة أثناء التلاوة</small></div><button class="toggle" id="tg-auto" role="switch" aria-checked="true" aria-label="تقليب الصفحة تلقائياً"></button></div>
    <div class="row"><div><b>دقة التصحيح</b><small>متساهل يناسب الأجهزة ذات الميكروفون الضعيف</small></div>
      <div class="seg-group" id="strict-group">
        <button class="seg" data-strict="lenient" aria-pressed="false">متساهل</button>
        <button class="seg" data-strict="normal" aria-pressed="true">متوسط</button>
        <button class="seg" data-strict="strict" aria-pressed="false">صارم</button>
      </div></div>
  </div>
</div>

<div class="modal" id="goto" aria-hidden="true">
  <div class="modal-card" role="dialog" aria-label="الانتقال إلى صفحة">
    <div class="sheet-head" style="padding:0 0 4px">
      <h2>الانتقال إلى صفحة</h2>
      <button class="icon-btn" data-close="modal" aria-label="إغلاق">✕</button>
    </div>
    <input class="num-input goto-input" id="goto-input" type="number" inputmode="numeric" min="1" max="604" placeholder="١ – ٦٠٤" aria-label="رقم الصفحة">
    <div style="text-align:center"><button class="primary-btn" id="goto-go">انتقال</button></div>
  </div>
</div>

<div class="finish" id="finish">
  <div style="font-size:72px">⭐</div>
  <h2>ما شاء الله! أتممت المصحف</h2>
  <div class="big" id="fin-acc">—</div>
  <div style="color:var(--ink-2)">دقة التلاوة الكلية</div>
  <button class="primary-btn" id="fin-close">حسناً</button>
</div>

<script>
'use strict';

/* ═══════════════════════════════════════════════════════════════
   1) الإعدادات والبيانات المرجعية
   ═══════════════════════════════════════════════════════════════ */

const CFG = Object.freeze({
  API: 'https://api.alquran.cloud/v1/page/',
  EDITION: 'quran-uthmani',
  TOTAL_PAGES: 604,
  WINDOW: 56,
  PREFS_KEY: 'murattil.v12',
  CACHE_PREFIX: 'murattil.p.'
});

const SURAHS = [
  [1,'الفاتحة',7,1],[2,'البقرة',286,2],[3,'آل عمران',200,50],[4,'النساء',176,77],[5,'المائدة',120,106],
  [6,'الأنعام',165,128],[7,'الأعراف',206,151],[8,'الأنفال',75,177],[9,'التوبة',129,187],[10,'يونس',109,208],
  [11,'هود',123,221],[12,'يوسف',111,235],[13,'الرعد',43,249],[14,'إبراهيم',52,255],[15,'الحجر',99,262],
  [16,'النحل',128,267],[17,'الإسراء',111,282],[18,'الكهف',110,293],[19,'مريم',98,305],[20,'طه',135,312],
  [21,'الأنبياء',112,322],[22,'الحج',78,332],[23,'المؤمنون',118,342],[24,'النور',64,350],[25,'الفرقان',77,359],
  [26,'الشعراء',227,367],[27,'النمل',93,377],[28,'القصص',88,385],[29,'العنكبوت',69,396],[30,'الروم',60,404],
  [31,'لقمان',34,411],[32,'السجدة',30,415],[33,'الأحزاب',73,418],[34,'سبأ',54,428],[35,'فاطر',45,434],
  [36,'يس',83,440],[37,'الصافات',182,446],[38,'ص',88,453],[39,'الزمر',75,458],[40,'غافر',85,467],
  [41,'فصلت',54,477],[42,'الشورى',53,483],[43,'الزخرف',89,489],[44,'الدخان',59,496],[45,'الجاثية',37,499],
  [46,'الأحقاف',35,502],[47,'محمد',38,507],[48,'الفتح',29,511],[49,'الحجرات',18,515],[50,'ق',45,518],
  [51,'الذاريات',60,520],[52,'الطور',49,523],[53,'النجم',62,526],[54,'القمر',55,528],[55,'الرحمن',78,531],
  [56,'الواقعة',96,534],[57,'الحديد',29,537],[58,'المجادلة',22,542],[59,'الحشر',24,545],[60,'الممتحنة',13,549],
  [61,'الصف',14,551],[62,'الجمعة',11,553],[63,'المنافقون',11,554],[64,'التغابن',18,556],[65,'الطلاق',12,558],
  [66,'التحريم',12,560],[67,'الملك',30,562],[68,'القلم',52,564],[69,'الحاقة',52,566],[70,'المعارج',44,568],
  [71,'نوح',28,570],[72,'الجن',28,572],[73,'المزمل',20,574],[74,'المدثر',56,575],[75,'القيامة',40,577],
  [76,'الإنسان',31,578],[77,'المرسلات',50,580],[78,'النبأ',40,582],[79,'النازعات',46,583],[80,'عبس',42,585],
  [81,'التكوير',29,586],[82,'الانفطار',19,587],[83,'المطففين',36,587],[84,'الانشقاق',25,589],[85,'البروج',22,590],
  [86,'الطارق',17,591],[87,'الأعلى',19,591],[88,'الغاشية',26,592],[89,'الفجر',30,593],[90,'البلد',20,594],
  [91,'الشمس',15,595],[92,'الليل',21,595],[93,'الضحى',11,596],[94,'الشرح',8,596],[95,'التين',8,597],
  [96,'العلق',19,597],[97,'القدر',5,598],[98,'البينة',8,598],[99,'الزلزلة',8,599],[100,'العاديات',11,599],
  [101,'القارعة',11,600],[102,'التكاثر',8,600],[103,'العصر',3,601],[104,'الهمزة',9,601],[105,'الفيل',5,601],
  [106,'قريش',4,602],[107,'الماعون',7,602],[108,'الكوثر',3,602],[109,'الكافرون',6,603],[110,'النصر',3,603],
  [111,'المسد',5,603],[112,'الإخلاص',4,604],[113,'الفلق',5,604],[114,'الناس',6,604]
].map(([n, name, ayahs, page]) => Object.freeze({ n, name, ayahs, page }));

const JUZ_PAGES = [1,22,42,62,82,102,121,142,162,182,201,222,242,262,282,302,322,342,362,382,402,422,442,462,482,502,522,542,562,582];
const FEATURED_SURAHS = [20, 27, 6, 35];
const TAHA = 20;

/** مصادر صوت الشيخ محمد أيوب */
const AUDIO_SOURCES = [
  { id: 'taraweeh', label: 'تراويح المسجد النبوي', note: 'صلاة التراويح · OGG',
    url: n => `https://archive.org/download/192--kb------by---traweeh--mushaf----by----mohammad----ayyob--by--sada---soot_12/${n}.ogg` },
  { id: 'mumayyaza', label: 'تلاوة مميزة', note: 'MP3Quran · حفص',
    url: n => `https://server16.mp3quran.net/ayyoub2/Rewayat-Hafs-A-n-Assem/${n}.mp3` },
  { id: 'murattal', label: 'المصحف المرتل', note: 'MP3Quran · حفص',
    url: n => `https://server8.mp3quran.net/ayyub/${n}.mp3` }
];

/* ═══════════════════════════════════════════════════════════════
   2) أدوات عامة
   ═══════════════════════════════════════════════════════════════ */

const $ = (sel, root = document) => root.querySelector(sel);
const $$ = (sel, root = document) => Array.from(root.querySelectorAll(sel));
const clamp = (v, lo, hi) => Math.min(hi, Math.max(lo, v));
const pad3 = n => String(n).padStart(3, '0');
const toAr = n => String(n).replace(/\d/g, d => '٠١٢٣٤٥٦٧٨٩'[d]);
const surahOf = n => SURAHS[n - 1];

const Store = {
  read() { try { return JSON.parse(localStorage.getItem(CFG.PREFS_KEY)) || {}; } catch (e) { return {}; } },
  write(patch) { try { localStorage.setItem(CFG.PREFS_KEY, JSON.stringify(Object.assign(this.read(), patch))); } catch (e) { /* التخزين غير متاح */ } },
  getCache(k) { try { return JSON.parse(localStorage.getItem(CFG.CACHE_PREFIX + k)); } catch (e) { return null; } },
  setCache(k, v) { try { localStorage.setItem(CFG.CACHE_PREFIX + k, JSON.stringify(v)); } catch (e) { /* ممتلئ */ } }
};

let toastTimer = 0;
function toast(msg, kind = '') {
  const el = $('#toast');
  el.textContent = msg;
  el.className = 'toast on ' + kind;
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => el.classList.remove('on'), 2400);
  if (kind === 'ok' && navigator.vibrate) { try { navigator.vibrate(40); } catch (e) { /* */ } }
}
function showNotice(msg) {
  const el = $('#notice');
  el.textContent = msg || '';
  el.classList.toggle('on', !!msg);
}

/* ═══════════════════════════════════════════════════════════════
   3) معالجة النص العربي ومحرّك المطابقة
   ═══════════════════════════════════════════════════════════════ */

const MARKS_RE = /[\u0610-\u061A\u0640\u064B-\u065F\u0670\u06D6-\u06ED\u08D3-\u08FF\u200B-\u200F\u061C\uFEFF]/g;

function norm(s) {
  return String(s)
    .replace(MARKS_RE, '')
    .replace(/[\u0671\u0622\u0623\u0625\u0672\u0673\u0675]/g, '\u0627')
    .replace(/[\u0649\u06CC\u0626]/g, '\u064A')
    .replace(/\u0629/g, '\u0647')
    .replace(/\u0624/g, '\u0648')
    .replace(/\u06A9/g, '\u0643')
    .replace(/[^\u0627-\u064A]/g, '');
}

function skeleton(n) { return n ? n[0] + n.slice(1).replace(/[\u0627\u0648\u064A]/g, '') : ''; }

const FOLD = { 'ض':'ز','ظ':'ز','ذ':'ز','ص':'س','ث':'س','ط':'ت','ق':'ك','ح':'ه','ة':'ه' };
function fold(s) { return s.replace(/[ضظذصثطقحة]/g, c => FOLD[c]); }

function makeWord(text) {
  const n = norm(text);
  const k = skeleton(n);
  return { n, k, f: fold(k) };
}

function lev(a, b) {
  const m = a.length, n = b.length;
  if (!m) return n;
  if (!n) return m;
  let prev = new Array(n + 1), cur = new Array(n + 1);
  for (let j = 0; j <= n; j++) prev[j] = j;
  for (let i = 1; i <= m; i++) {
    cur[0] = i;
    for (let j = 1; j <= n; j++) {
      const c = a.charCodeAt(i - 1) === b.charCodeAt(j - 1) ? 0 : 1;
      cur[j] = Math.min(prev[j] + 1, cur[j - 1] + 1, prev[j - 1] + c);
    }
    const t = prev; prev = cur; cur = t;
  }
  return prev[n];
}
const simStr = (a, b) => {
  if (a === b) return 1;
  const m = Math.max(a.length, b.length);
  return m ? 1 - lev(a, b) / m : 0;
};

function wordSim(x, y) {
  if (!x.n || !y.n) return 0;
  if (x.n === y.n) return 1;
  let s = simStr(x.n, y.n);
  if (x.k.length >= 2 && y.k.length >= 2) {
    if (x.k === y.k) s = Math.max(s, 0.97);
    else s = Math.max(s, 0.96 * simStr(x.k, y.k));
    if (x.f === y.f) s = Math.max(s, 0.93);
    else s = Math.max(s, 0.9 * simStr(x.f, y.f));
  }
  return s;
}

/* عتبات أكثر تسامحاً مع اختلاف نطق الميكروفونات */
const THRESHOLDS = { lenient: 0.56, normal: 0.66, strict: 0.78 };

function isMatch(sim, x, y, T) {
  const len = Math.min(x.n.length, y.n.length);
  return sim >= (len <= 3 ? Math.max(T, 0.95) : T);
}

const COST = { skip: 1.2, insert: 0.6 };

/**
 * محاذاة الكلام المُتعرَّف عليه مع الكلمات المتوقعة.
 * status: 0 لم يُحكم عليها، 1 صحيحة، 2 خاطئة/متروكة
 */
function align(spoken, exp, opts = {}) {
  const T = opts.T != null ? opts.T : THRESHOLDS.normal;
  const isFinal = opts.final !== false;
  const n = spoken.length, m = exp.length;
  const NEG = -1e9;
  const dp = Array.from({ length: n + 1 }, () => new Float64Array(m + 1).fill(NEG));
  const bp = Array.from({ length: n + 1 }, () => new Uint8Array(m + 1));
  const simCache = new Map();
  const simAt = (i, j) => {
    const key = i * 4096 + j;
    let v = simCache.get(key);
    if (v === undefined) { v = wordSim(spoken[i], exp[j]); simCache.set(key, v); }
    return v;
  };
  const matchAt = (i, j) => isMatch(simAt(i, j), spoken[i], exp[j], T);
  const mergedCache = [];
  const mergedAt = j => mergedCache[j] || (mergedCache[j] = makeWord(exp[j].n + exp[j + 1].n));

  dp[0][0] = 0;
  for (let i = 0; i <= n; i++) {
    for (let j = 0; j <= m; j++) {
      const cur = dp[i][j];
      if (cur === NEG) continue;
      if (i < n && j < m) {
        const s = simAt(i, j);
        const gain = matchAt(i, j) ? 1 + s : -1.2 + s;
        if (cur + gain > dp[i + 1][j + 1]) { dp[i + 1][j + 1] = cur + gain; bp[i + 1][j + 1] = 1; }
      }
      if (j < m && cur - COST.skip > dp[i][j + 1]) { dp[i][j + 1] = cur - COST.skip; bp[i][j + 1] = 2; }
      if (i < n && cur - COST.insert > dp[i + 1][j]) { dp[i + 1][j] = cur - COST.insert; bp[i + 1][j] = 3; }
      if (i < n && j + 1 < m) {
        const merged = mergedAt(j);
        const s = wordSim(spoken[i], merged);
        if (s >= Math.max(T, 0.9) && isMatch(s, spoken[i], merged, T) && cur + 1.6 + s > dp[i + 1][j + 2]) { dp[i + 1][j + 2] = cur + 1.6 + s; bp[i + 1][j + 2] = 4; }
      }
      if (i + 1 < n && j < m) {
        const joined = makeWord(spoken[i].n + spoken[i + 1].n);
        const s = wordSim(joined, exp[j]);
        if (s >= Math.max(T, 0.9) && isMatch(s, joined, exp[j], T) && cur + 0.8 + s > dp[i + 2][j + 1]) { dp[i + 2][j + 1] = cur + 0.8 + s; bp[i + 2][j + 1] = 5; }
      }
    }
  }

  let bestJ = 0, bestScore = NEG;
  for (let j = 0; j <= m; j++) if (dp[n][j] >= bestScore) { bestScore = dp[n][j]; bestJ = j; }

  const status = new Uint8Array(m);
  let i = n, j = bestJ, matched = 0;
  const ops = [];
  while (i > 0 || j > 0) {
    const op = bp[i][j];
    if (!op) break;
    ops.push([op, i, j]);
    if (op === 1) { i--; j--; }
    else if (op === 2) { j--; }
    else if (op === 3) { i--; }
    else if (op === 4) { i--; j -= 2; }
    else { i -= 2; j--; }
  }
  ops.reverse();
  for (const [op, ii, jj] of ops) {
    if (op === 1) {
      const ok = matchAt(ii - 1, jj - 1);
      status[jj - 1] = ok ? 1 : 2;
      if (ok) matched++;
    } else if (op === 2) status[jj - 1] = 2;
    else if (op === 4) { status[jj - 1] = 1; status[jj - 2] = 1; matched += 2; }
    else if (op === 5) { status[jj - 1] = 1; matched++; }
  }
  let end = bestJ;
  if (!isFinal && ops.length) {
    const last = ops[ops.length - 1];
    if (last[0] === 1 && status[last[2] - 1] === 2) { status[last[2] - 1] = 0; end = last[2] - 1; }
  }
  return { status, end, score: bestScore, matched };
}

function locate(spoken, exp, opts = {}) {
  const T = opts.T != null ? opts.T : THRESHOLDS.normal;
  const k = Math.min(4, spoken.length);
  const need = k >= 4 ? 3 : k;
  if (k < 2) return -1;
  let best = -1, bestHits = 0, bestSim = 0;
  for (let p = 0; p + need <= exp.length; p++) {
    let hits = 0, sim = 0, miss = 0;
    for (let q = 0; q < k && p + q < exp.length; q++) {
      const s = wordSim(spoken[q], exp[p + q]);
      if (isMatch(s, spoken[q], exp[p + q], T)) { hits++; sim += s; }
      else if (++miss > 1) break;
    }
    if (hits > bestHits || (hits === bestHits && sim > bestSim)) { best = p; bestHits = hits; bestSim = sim; }
  }
  return bestHits >= need ? best : -1;
}

const BISMILLAH = 'بسماللهالرحمنالرحيم';
function stripLeadingBismillah(spoken) {
  if (spoken.length >= 4) {
    const joined = spoken.slice(0, 4).map(w => w.n).join('');
    if (simStr(joined, BISMILLAH) >= 0.8) return spoken.slice(4);
  }
  return spoken;
}

function toSpoken(text) {
  return String(text).split(/\s+/).map(makeWord).filter(w => w.n);
}

/* ═══════════════════════════════════════════════════════════════
   4) بيانات المصحف
   ═══════════════════════════════════════════════════════════════ */

const Quran = {
  pages: new Map(),
  inflight: new Map(),

  async load(no) {
    if (this.pages.has(no)) return this.pages.get(no);
    if (this.inflight.has(no)) return this.inflight.get(no);
    const task = (async () => {
      let raw = Store.getCache(no);
      if (!raw) {
        let lastErr = null;
        for (let attempt = 0; attempt < 3; attempt++) {
          try {
            const ctl = new AbortController();
            const t = setTimeout(() => ctl.abort(), 12000);
            const res = await fetch(`${CFG.API}${no}/${CFG.EDITION}`, { signal: ctl.signal });
            clearTimeout(t);
            const json = await res.json();
            if (json.code !== 200) throw new Error('API ' + json.code);
            raw = json.data.ayahs.map(a => [a.surah.number, a.numberInSurah, a.text, a.juz]);
            Store.setCache(no, raw);
            lastErr = null;
            break;
          } catch (e) { lastErr = e; await new Promise(r => setTimeout(r, 400 * (attempt + 1))); }
        }
        if (!raw) throw lastErr || new Error('تعذّر التحميل');
      }
      const page = this.build(no, raw);
      this.pages.set(no, page);
      return page;
    })();
    this.inflight.set(no, task);
    try { return await task; } finally { this.inflight.delete(no); }
  },

  build(no, raw) {
    const ayahs = [], words = [];
    for (const [s, n, text0, juz] of raw) {
      let toks = text0.trim().split(/\s+/);
      if (n === 1 && s !== 1 && s !== 9 && toks.length > 4 && norm(toks.slice(0, 4).join('')) === BISMILLAH) toks = toks.slice(4);
      const first = words.length;
      for (const tk of toks) {
        const w = makeWord(tk);
        if (!w.n) {
          if (words.length > first) words[words.length - 1].t += '\u00A0' + tk;
          continue;
        }
        words.push(Object.assign({}, w, { t: tk, ayah: ayahs.length }));
      }
      ayahs.push({ s, n, juz, first, last: words.length - 1 });
    }
    return { no, ayahs, words, status: new Uint8Array(words.length) };
  },

  prefetch(no) {
    for (const p of [no + 1, no - 1, no + 2]) {
      if (p >= 1 && p <= CFG.TOTAL_PAGES && !this.pages.has(p)) this.load(p).catch(() => {});
    }
  }
};

/* ═══════════════════════════════════════════════════════════════
   5) العرض
   ═══════════════════════════════════════════════════════════════ */

const View = {
  page: 1,
  data: null,
  els: [],
  markers: [],
  lastScroll: 0,

  escape(s) { return s.replace(/&/g, '&amp;').replace(/</g, '&lt;').replace(/>/g, '&gt;'); },

  skeleton() {
    $('#mushaf').innerHTML = '<div class="skeleton" aria-label="جارٍ تحميل الصفحة"><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div>';
  },

  render(data, dir) {
    this.data = data; this.page = data.no;
    const first = data.ayahs[0];
    let html = `<div class="page-head"><span>الجزء ${toAr(first.juz)}</span><span>سورة ${surahOf(first.s).name}</span></div>`;
    let open = false;
    const close = () => { if (open) { html += '</p>'; open = false; } };
    data.ayahs.forEach((a, ai) => {
      if (a.n === 1) {
        close();
        html += `<div class="surah-banner">سورة ${surahOf(a.s).name}</div>`;
        if (a.s !== 1 && a.s !== 9) html += '<div class="bismillah">بِسْمِ ٱللَّهِ ٱلرَّحْمَـٰنِ ٱلرَّحِيمِ</div>';
      }
      if (!open) { html += '<p class="flow">'; open = true; }
      for (let i = a.first; i <= a.last; i++) html += `<span class="word" data-i="${i}">${this.escape(data.words[i].t)}</span> `;
      html += `<span class="ayah-no" data-a="${ai}">${toAr(a.n)}</span> `;
    });
    close();
    html += `<div class="page-foot">${toAr(data.no)}</div>`;
    const el = $('#mushaf');
    el.innerHTML = html;
    el.classList.toggle('memorize', State.memorize);
    el.classList.remove('turn-next', 'turn-prev');
    if (dir) { void el.offsetWidth; el.classList.add(dir > 0 ? 'turn-next' : 'turn-prev'); }
    this.els = $$('.word', el);
    this.markers = $$('.ayah-no', el);
    const flows = $$('.flow', el); if (flows.length) flows[flows.length - 1].classList.add('tail');
    this.paintAll();
  },

  paintWord(i) {
    const el = this.els[i]; if (!el) return;
    const s = this.data.status[i];
    el.classList.toggle('correct', s === 1);
    el.classList.toggle('wrong', s === 2);
  },
  paintAll() {
    if (!this.data) return;
    for (let i = 0; i < this.els.length; i++) this.paintWord(i);
    this.paintMarkers();
    this.paintCursor();
  },
  paintMarkers() {
    const d = this.data; if (!d) return;
    d.ayahs.forEach((a, ai) => {
      let done = true, bad = false;
      for (let i = a.first; i <= a.last; i++) {
        if (!d.status[i]) { done = false; break; }
        if (d.status[i] === 2) bad = true;
      }
      const m = this.markers[ai]; if (!m) return;
      m.classList.toggle('done', done && !bad);
      m.classList.toggle('miss', done && bad);
    });
  },
  paintCursor() {
    $$('.word.next', $('#mushaf')).forEach(e => e.classList.remove('next'));
    const p = Tracker.cursorHint || Tracker.pos;
    if (!(p && this.data && p.page === this.data.no && this.els[p.i])) return;
    const el = this.els[p.i];
    el.classList.add('next');
    /* أبقِ الكلمة الحالية ظاهرة أثناء التلاوة */
    if (Mic.on && Date.now() - this.lastScroll > 400) {
      const r = el.getBoundingClientRect();
      if (r.top < 150 || r.bottom > window.innerHeight - 200) {
        this.lastScroll = Date.now();
        el.scrollIntoView({ behavior: 'smooth', block: 'center' });
      }
    }
  }
};

/* ═══════════════════════════════════════════════════════════════
   6) الحالة والتنقل
   ═══════════════════════════════════════════════════════════════ */

const State = {
  page: 1, fs: 30, memorize: false, dark: false, autoTurn: true, strict: 'normal',
  stats: { ok: 0, att: 0 },
  navSeq: 0
};

const Nav = {
  async go(no, opts = {}) {
    const dir = opts.dir || 0, keepTracking = !!opts.keepTracking;
    no = clamp(Math.round(no) || 1, 1, CFG.TOTAL_PAGES);
    const seq = ++State.navSeq;
    showNotice('');
    let data = Quran.pages.get(no);
    if (!data) {
      View.skeleton();
      try { data = await Quran.load(no); }
      catch (e) {
        if (seq !== State.navSeq) return;
        showNotice('تعذّر تحميل الصفحة. تحقق من الإنترنت ثم أعد المحاولة.');
        $('#mushaf').innerHTML = '<div class="hint-bar" style="padding:60px 10px">⚠️ لم تُحمَّل الصفحة</div>';
        return;
      }
    }
    if (seq !== State.navSeq) return;
    State.page = no;
    if (!keepTracking && Tracker.pos && Tracker.pos.page !== no) { Tracker.clearProvisional(); Tracker.pos = null; Tracker.cursorHint = null; }
    View.render(data, dir || (no > View.page ? 1 : -1));
    this.sync(data);
    Quran.prefetch(no);
    Store.write({ page: no });
    if (!keepTracking) window.scrollTo({ top: 0, behavior: 'smooth' });
  },
  next() { return this.go(State.page + 1, { dir: 1 }); },
  prev() { return this.go(State.page - 1, { dir: -1 }); },

  sync(data) {
    const no = data.no, a0 = data.ayahs[0];
    $('#pg-open').textContent = toAr(no);
    $('#pg-slider').value = no;
    $('#st-page').textContent = toAr(no);
    $('#sel-surah').value = a0.s;
    $('#sel-juz').value = a0.juz;
    $('#readbar').style.width = (no / CFG.TOTAL_PAGES * 100) + '%';
    $$('[data-page="prev"]').forEach(b => { b.disabled = no <= 1; });
    $$('[data-page="next"]').forEach(b => { b.disabled = no >= CFG.TOTAL_PAGES; });
  }
};

function refreshStats(provOk = 0, provAtt = 0) {
  const ok = State.stats.ok + provOk, att = State.stats.att + provAtt;
  $('#st-ok').textContent = toAr(ok);
  $('#st-att').textContent = toAr(att);
  $('#st-acc').textContent = att ? toAr(Math.round((ok / att) * 100)) + '٪' : '—';
}

/* ═══════════════════════════════════════════════════════════════
   7) المتتبّع
   ═══════════════════════════════════════════════════════════════ */

const Tracker = {
  pos: null,
  touched: [],
  cursorHint: null,

  reset() {
    this.pos = null; this.touched = []; this.cursorHint = null;
    Quran.pages.forEach(p => p.status.fill(0));
    State.stats = { ok: 0, att: 0 };
    refreshStats();
    View.paintAll();
  },

  setPos(page, i) {
    this.clearProvisional();
    this.cursorHint = null;
    this.pos = { page, i };
    View.paintCursor();
  },

  windowFrom(pos, len = CFG.WINDOW) {
    const out = [];
    let pg = Quran.pages.get(pos.page), i = pos.i;
    while (pg && out.length < len) {
      while (i < pg.words.length && out.length < len) { out.push({ page: pg.no, i, w: pg.words[i] }); i++; }
      pg = Quran.pages.get(pg.no + 1); i = 0;
    }
    return out;
  },

  clearProvisional() {
    for (let k = this.touched.length - 1; k >= 0; k--) {
      const { page, i, prev } = this.touched[k];
      const pg = Quran.pages.get(page);
      if (pg) { pg.status[i] = prev; if (View.data && View.data.no === page) View.paintWord(i); }
    }
    this.touched = [];
  },

  atSurahStart() {
    const p = this.pos; if (!p) return false;
    const pg = Quran.pages.get(p.page); if (!pg) return false;
    const w = pg.words[p.i]; if (!w) return false;
    const a = pg.ayahs[w.ayah];
    return !!a && a.n === 1 && a.first === p.i && a.s !== 1 && a.s !== 9;
  },

  /** final=true حكم نهائي. النص الجزئي لا يُظهر الأخطاء أبداً (يمنع الوميض الأحمر الكاذب) */
  feed(spokenWords, opts) {
    const final = !!(opts && opts.final);
    if (!spokenWords.length) return null;
    const T = THRESHOLDS[State.strict];
    this.clearProvisional();
    this.cursorHint = null;

    if (!this.pos) {
      const pg = View.data; if (!pg) return null;
      const at = locate(spokenWords, pg.words, { T });
      if (at < 0) return null;
      this.pos = { page: pg.no, i: at };
    }
    let spoken = spokenWords;
    if (this.atSurahStart()) spoken = stripLeadingBismillah(spoken);
    if (!spoken.length) return null;

    let win = this.windowFrom(this.pos);
    if (!win.length) return null;
    let res = align(spoken, win.map(x => x.w), { T, final });

    if (spoken.length >= 4 && res.matched / spoken.length < 0.35) {
      const cands = new Set([View.page, this.pos.page, this.pos.page + 1].filter(p => Quran.pages.has(p)));
      let bestAt = null;
      for (const pno of cands) {
        const pg = Quran.pages.get(pno);
        const at = locate(spoken.slice(-Math.min(6, spoken.length)), pg.words, { T });
        if (at >= 0) { bestAt = { page: pno, i: at }; break; }
      }
      if (bestAt) {
        const tail = spoken.slice(-Math.min(6, spoken.length));
        const w2 = this.windowFrom(bestAt);
        const r2 = align(tail, w2.map(x => x.w), { T, final });
        if (r2.matched > res.matched) { this.pos = bestAt; win = w2; res = r2; spoken = tail; }
      }
    }

    let okCount = 0, attCount = 0;
    for (let k = 0; k < res.status.length; k++) {
      let s = res.status[k];
      if (!s) continue;
      if (!final && s === 2) continue;           // لا أخطاء أثناء الكلام
      const { page, i } = win[k];
      const pg = Quran.pages.get(page);
      if (!final) this.touched.push({ page, i, prev: pg.status[i] });
      pg.status[i] = s;
      if (s === 1) okCount++;
      attCount++;
      if (View.data && View.data.no === page) View.paintWord(i);
    }
    if (final) {
      State.stats.ok += okCount; State.stats.att += attCount;
      const last = win[Math.min(res.end, win.length) - 1];
      if (res.end > 0 && last) this.pos = { page: last.page, i: last.i + 1 };
      this.normalizePos();
      this.touched = [];
      refreshStats();
    } else {
      refreshStats(okCount, attCount);
      if (res.end > 0 && win[res.end - 1]) this.cursorHint = { page: win[res.end - 1].page, i: win[res.end - 1].i + 1 };
    }
    View.paintMarkers();
    this.afterProgress(final);
    return res;
  },

  normalizePos() {
    const p = this.pos; if (!p) return;
    const pg = Quran.pages.get(p.page);
    if (pg && p.i >= pg.words.length) {
      if (p.page >= CFG.TOTAL_PAGES) { this.pos = null; App.onFinish(); return; }
      this.pos = { page: p.page + 1, i: 0 };
    }
  },

  afterProgress(final) {
    const target = (!final && this.cursorHint) ? this.cursorHint : this.pos;
    if (target && State.autoTurn && target.page !== State.page) {
      const from = Quran.pages.get(State.page);
      if (from && from.words.length) {
        let done = 0, ok = 0;
        for (const s of from.status) { if (s) done++; if (s === 1) ok++; }
        if (done / from.words.length > 0.9) toast(`اكتملت الصفحة ${toAr(from.no)} · ${toAr(Math.round(ok / from.words.length * 100))}٪`, 'ok');
      }
      Nav.go(target.page, { dir: target.page > State.page ? 1 : -1, keepTracking: true });
    } else View.paintCursor();
  }
};

/* ═══════════════════════════════════════════════════════════════
   8) التعرّف على الصوت
   ═══════════════════════════════════════════════════════════════ */

const Mic = {
  rec: null, on: false,
  processed: 0,
  lastFinal: [],
  pendingInterim: [],
  restartDelay: 250,
  lock: null,

  supported() { return window.SpeechRecognition || window.webkitSpeechRecognition; },

  toggle() { if (this.on) this.stop(); else this.start(); },

  start() {
    const SR = this.supported();
    if (!SR) { showNotice('متصفحك لا يدعم التعرّف على الصوت. استخدم Chrome أو Safari.'); return; }
    if (!View.data) { toast('انتظر تحميل الصفحة'); return; }
    Player.pause();
    showNotice('');
    this.on = true;
    this.beginSession(SR);
    UI.micState(true);
    this.keepAwake(true);
  },

  beginSession(SR) {
    this.processed = 0; this.lastFinal = []; this.pendingInterim = [];
    const r = new SR();
    r.lang = 'ar-SA';
    r.continuous = true;
    r.interimResults = true;
    r.maxAlternatives = 3;
    r.onstart = () => { this.restartDelay = 250; $('#m-status').textContent = '🔴 أستمع إليك…'; };
    r.onresult = e => this.onResult(e);
    r.onerror = e => {
      if (e.error === 'no-speech' || e.error === 'aborted') return;
      if (e.error === 'not-allowed' || e.error === 'service-not-allowed') { showNotice('اسمح للتطبيق باستخدام المايكروفون من إعدادات المتصفح.'); this.stop(); }
      else if (e.error === 'audio-capture') { showNotice('لم أجد مايكروفون يعمل.'); this.stop(); }
      else if (e.error === 'network') toast('انقطع الاتصال بخدمة الصوت…', 'bad');
    };
    r.onend = () => {
      this.flushInterim();
      if (!this.on) return;
      setTimeout(() => { if (this.on) { try { this.beginSession(SR); } catch (e) { /* */ } } }, this.restartDelay);
      this.restartDelay = Math.min(this.restartDelay * 2, 2000);
    };
    this.rec = r;
    try { r.start(); } catch (e) { /* بدأ بالفعل */ }
  },

  stop() {
    this.on = false;
    const r = this.rec; this.rec = null;
    if (r) { r.onend = null; try { r.stop(); } catch (e) { /* */ } }
    this.flushInterim();
    UI.micState(false);
    this.keepAwake(false);
  },

  async keepAwake(on) {
    try {
      if (on && 'wakeLock' in navigator) this.lock = await navigator.wakeLock.request('screen');
      else if (this.lock) { await this.lock.release(); this.lock = null; }
    } catch (e) { /* غير مدعوم */ }
  },

  flushInterim() {
    if (this.pendingInterim.length) { Tracker.feed(this.pendingInterim, { final: true }); this.pendingInterim = []; }
    $('#m-live').textContent = '';
  },

  bestAlternative(result, T) {
    let best = null, bestScore = -Infinity;
    const count = Math.min(3, result.length);
    for (let a = 0; a < count; a++) {
      const words = toSpoken(result[a].transcript);
      if (!words.length) continue;
      if (!Tracker.pos) { if (!best) best = words; continue; }
      const win = Tracker.windowFrom(Tracker.pos).map(x => x.w);
      if (!win.length) { if (!best) best = words; continue; }
      const r = align(words, win, { T, final: true });
      const score = r.score + (a === 0 ? 0.4 : 0);
      if (score > bestScore) { bestScore = score; best = words; }
    }
    return best || [];
  },

  dedupe(words) {
    const prev = this.lastFinal;
    if (prev.length >= 3 && words.length > prev.length) {
      let same = true;
      for (let i = 0; i < prev.length; i++) if (prev[i].n !== words[i].n) { same = false; break; }
      if (same) return words.slice(prev.length);
    }
    return words;
  },

  onResult(e) {
    const T = THRESHOLDS[State.strict];
    for (let r = Math.max(this.processed, 0); r < e.results.length; r++) {
      const res = e.results[r];
      if (!res.isFinal) break;
      const words = this.bestAlternative(res, T);
      const fresh = this.dedupe(words);
      this.lastFinal = words.slice();
      this.processed = r + 1;
      this.pendingInterim = [];
      if (fresh.length) Tracker.feed(fresh, { final: true });
    }
    let interim = '';
    for (let r = this.processed; r < e.results.length; r++) if (!e.results[r].isFinal) interim += ' ' + e.results[r][0].transcript;
    interim = interim.trim();
    $('#m-live').textContent = interim;
    if (interim) {
      const words = this.dedupe(toSpoken(interim));
      this.pendingInterim = words;
      Tracker.feed(words, { final: false });
    }
  }
};

/* ═══════════════════════════════════════════════════════════════
   9) مشغّل صوت الشيخ محمد أيوب
   ═══════════════════════════════════════════════════════════════ */

const Player = {
  audio: new Audio(),
  surah: null,
  srcIdx: 0,
  speeds: [0.75, 1, 1.25, 1.5],
  speedIdx: 1,
  triedFallback: new Set(),
  customTried: false,

  init() {
    const a = this.audio;
    a.preload = 'none';
    const canOgg = !!a.canPlayType && a.canPlayType('audio/ogg; codecs="vorbis"') !== '';
    const saved = Store.read().audioSrc;
    const idx = AUDIO_SOURCES.findIndex(s => s.id === saved);
    this.srcIdx = idx >= 0 ? idx : (canOgg ? 0 : 1);
    a.addEventListener('timeupdate', () => this.tick());
    a.addEventListener('loadedmetadata', () => this.tick());
    a.addEventListener('play', () => this.paintPlay());
    a.addEventListener('pause', () => this.paintPlay());
    a.addEventListener('ended', () => { if (this.surah < 114) this.play(this.surah + 1); else this.paintPlay(); });
    a.addEventListener('error', () => this.onError());
    $('#pl-play').onclick = () => { if (a.paused) a.play().catch(() => {}); else a.pause(); };
    $('#pl-prev').onclick = () => { if (this.surah) this.play(Math.max(1, this.surah - 1)); };
    $('#pl-next').onclick = () => { if (this.surah) this.play(Math.min(114, this.surah + 1)); };
    $('#pl-close').onclick = () => this.close();
    $('#pl-read').onclick = () => { if (this.surah) { Nav.go(surahOf(this.surah).page); UI.closeAll(); } };
    $('#pl-speed').onclick = () => {
      this.speedIdx = (this.speedIdx + 1) % this.speeds.length;
      a.playbackRate = this.speeds[this.speedIdx];
      $('#pl-speed').textContent = this.speeds[this.speedIdx] + '×';
    };
    $('#pl-seek').oninput = e => { if (a.duration) a.currentTime = (e.target.value / 1000) * a.duration; };
  },

  get source() { return AUDIO_SOURCES[this.srcIdx]; },

  customUrl(n) { return n === TAHA ? (Store.read().tahaUrl || '') : ''; },

  setSource(idx) {
    this.srcIdx = idx;
    Store.write({ audioSrc: AUDIO_SOURCES[idx].id });
    this.triedFallback.clear();
    if (this.surah) this.play(this.surah, { keepTime: true });
    UI.paintSources();
  },

  play(n, opts = {}) {
    if (Mic.on) Mic.stop();
    const a = this.audio;
    const t = opts.keepTime ? a.currentTime : 0;
    if (n !== this.surah) { this.triedFallback.clear(); this.customTried = false; }
    this.surah = n;
    const custom = this.customUrl(n);
    const useCustom = !!custom && !this.customTried;
    a.src = useCustom ? custom : this.source.url(pad3(n));
    a.playbackRate = this.speeds[this.speedIdx];
    if (t) a.addEventListener('loadedmetadata', () => { a.currentTime = t; }, { once: true });
    a.play().catch(() => {});
    $('#player').classList.add('on');
    $('#pl-title').firstChild.nodeValue = `سورة ${surahOf(n).name}`;
    $('#pl-sub').textContent = `الشيخ محمد أيوب · ${useCustom ? 'رابطك الخاص' : this.source.label}`;
    this.syncDock(); UI.paintPlaying(); this.mediaSession(n);
  },

  pause() { if (!this.audio.paused) this.audio.pause(); },

  close() {
    this.audio.pause(); this.audio.removeAttribute('src'); this.audio.load();
    this.surah = null;
    $('#player').classList.remove('on');
    this.syncDock(); UI.paintPlaying();
  },

  onError() {
    if (!this.surah) return;
    if (this.customUrl(this.surah) && !this.customTried) {
      this.customTried = true;
      toast('تعذّر رابطك الخاص — جرّبت مصدراً آخر', 'bad');
      this.play(this.surah);
      return;
    }
    this.triedFallback.add(this.srcIdx);
    const next = AUDIO_SOURCES.findIndex((_, i) => !this.triedFallback.has(i));
    if (next >= 0) {
      toast(`تعذّر «${this.source.label}» — جرّبت مصدراً آخر`, 'bad');
      this.srcIdx = next;
      this.play(this.surah);
      UI.paintSources();
    } else toast(this.surah === TAHA ? 'تعذّر التشغيل. جرّب زر يوتيوب أو الصق رابطاً خاصاً.' : 'تعذّر تشغيل هذه السورة. تحقق من الإنترنت.', 'bad');
  },

  paintPlay() { $('#pl-play').textContent = this.audio.paused ? '▶' : '⏸'; },

  tick() {
    const a = this.audio, d = a.duration || 0;
    $('#pl-cur').textContent = this.fmt(a.currentTime);
    $('#pl-dur').textContent = this.fmt(d);
    if (d && document.activeElement !== $('#pl-seek')) $('#pl-seek').value = Math.round((a.currentTime / d) * 1000);
  },
  fmt(s) {
    if (!isFinite(s)) return '0:00';
    s = Math.floor(s);
    const h = Math.floor(s / 3600), m = Math.floor((s % 3600) / 60), x = s % 60;
    return (h ? h + ':' + String(m).padStart(2, '0') : m) + ':' + String(x).padStart(2, '0');
  },

  mediaSession(n) {
    if (!('mediaSession' in navigator) || typeof MediaMetadata === 'undefined') return;
    try {
      navigator.mediaSession.metadata = new MediaMetadata({ title: `سورة ${surahOf(n).name}`, artist: 'الشيخ محمد أيوب', album: 'مُرَتِّل' });
      navigator.mediaSession.setActionHandler('play', () => this.audio.play());
      navigator.mediaSession.setActionHandler('pause', () => this.audio.pause());
      navigator.mediaSession.setActionHandler('nexttrack', () => { if (this.surah < 114) this.play(this.surah + 1); });
      navigator.mediaSession.setActionHandler('previoustrack', () => { if (this.surah > 1) this.play(this.surah - 1); });
    } catch (e) { /* */ }
  },

  syncDock() {
    requestAnimationFrame(() => document.documentElement.style.setProperty('--dock-h', ($('#dock').offsetHeight + 12) + 'px'));
  }
};

/* ═══════════════════════════════════════════════════════════════
   10) الواجهة
   ═══════════════════════════════════════════════════════════════ */

const UI = {
  lastFocus: null,

  init() {
    const ss = $('#sel-surah'), sj = $('#sel-juz');
    SURAHS.forEach(s => ss.add(new Option(`${toAr(s.n)}. ${s.name}`, s.n)));
    JUZ_PAGES.forEach((p, i) => sj.add(new Option(`الجزء ${toAr(i + 1)}`, i + 1)));
    ss.onchange = () => Nav.go(surahOf(+ss.value).page);
    sj.onchange = () => Nav.go(JUZ_PAGES[+sj.value - 1]);

    $$('[data-page]').forEach(b => { b.onclick = () => (b.dataset.page === 'next' ? Nav.next() : Nav.prev()); });
    const slider = $('#pg-slider');
    slider.oninput = () => { $('#pg-open').textContent = toAr(slider.value); };
    slider.onchange = () => Nav.go(+slider.value);
    $('#pg-open').onclick = () => { this.openModal('goto'); setTimeout(() => $('#goto-input').focus(), 60); };
    const go = () => {
      const v = parseInt($('#goto-input').value, 10);
      if (v >= 1 && v <= CFG.TOTAL_PAGES) { this.closeAll(); Nav.go(v); } else toast('أدخل رقماً بين ١ و ٦٠٤', 'bad');
    };
    $('#goto-go').onclick = go;
    $('#goto-input').onkeydown = e => { if (e.key === 'Enter') go(); };

    $('#font-inc').onclick = () => this.setFont(State.fs + 2);
    $('#font-dec').onclick = () => this.setFont(State.fs - 2);

    $('#burger').onclick = () => this.openDrawer();
    $('#scrim').onclick = () => this.closeAll();
    $$('[data-close]').forEach(b => { b.onclick = () => this.closeAll(); });
    $('#btn-theme').onclick = () => this.setDark(!State.dark);
    $('#tg-dark').onclick = () => this.setDark(!State.dark);
    $('#btn-memorize').onclick = () => this.setMemorize(!State.memorize);
    $('#tg-memorize').onclick = () => this.setMemorize(!State.memorize);
    $('#tg-auto').onclick = () => { State.autoTurn = !State.autoTurn; $('#tg-auto').setAttribute('aria-checked', String(State.autoTurn)); Store.write({ autoTurn: State.autoTurn }); };
    $('#btn-settings').onclick = () => this.openModal('settings');
    $$('#strict-group .seg').forEach(b => { b.onclick = () => this.setStrict(b.dataset.strict); });

    $('#mic-btn').onclick = () => Mic.toggle();
    $('#btn-reset').onclick = () => {
      if (Mic.on) Mic.stop();
      Tracker.reset();
      $('#m-status').textContent = 'اضغط المايكروفون وابدأ القراءة';
      toast('أُعيدت التلاوة من جديد');
    };
    $('#fin-close').onclick = () => $('#finish').classList.remove('on');

    $('#open-ayyub').onclick = () => this.openSheet();
    $('#drawer-taha').onclick = () => { this.closeAll(); Player.play(TAHA); };
    this.buildAyyub();

    $('#mushaf').addEventListener('click', e => {
      const w = e.target.closest('.word'); if (!w || !View.data) return;
      Tracker.setPos(View.data.no, +w.dataset.i);
      toast('ستبدأ المتابعة من هذه الكلمة');
    });

    let x0 = 0, y0 = 0, t0 = 0;
    const m = $('#mushaf');
    m.addEventListener('touchstart', e => { x0 = e.touches[0].clientX; y0 = e.touches[0].clientY; t0 = Date.now(); }, { passive: true });
    m.addEventListener('touchend', e => {
      const dx = e.changedTouches[0].clientX - x0, dy = e.changedTouches[0].clientY - y0;
      if (Math.abs(dx) > 70 && Math.abs(dx) > Math.abs(dy) * 1.8 && Date.now() - t0 < 600) { if (dx > 0) Nav.next(); else Nav.prev(); }
    }, { passive: true });

    document.addEventListener('keydown', e => {
      if (e.key === 'Escape') { this.closeAll(); return; }
      const tag = document.activeElement.tagName;
      if (['INPUT', 'SELECT', 'TEXTAREA'].includes(tag)) return;
      if (e.key === 'ArrowLeft') Nav.next();
      else if (e.key === 'ArrowRight') Nav.prev();
      else if (e.code === 'Space' && tag !== 'BUTTON') { e.preventDefault(); Mic.toggle(); }
    });

    document.addEventListener('visibilitychange', () => { if (document.visibilityState === 'visible' && Mic.on) Mic.keepAwake(true); });

    if ('ResizeObserver' in window) new ResizeObserver(() => Player.syncDock()).observe($('#dock'));
    Player.syncDock();
  },

  micState(on) {
    $('#mic-btn').classList.toggle('rec', on);
    $('#mic-bar').classList.toggle('live', on);
    $('#mic-btn').setAttribute('aria-label', on ? 'إيقاف التلاوة' : 'ابدأ التلاوة');
    $('#mic-svg').innerHTML = on ? '<rect x="6" y="6" width="12" height="12" rx="2"/>'
      : '<rect x="9" y="2" width="6" height="11" rx="3"/><path d="M5 10a7 7 0 0 0 14 0M12 19v3M8 22h8"/>';
    $('#m-status').textContent = on ? '🔴 أستمع إليك…' : 'اضغط للاستئناف';
    if (!on) $('#m-live').textContent = '';
  },

  setFont(v) {
    State.fs = clamp(v, 20, 48);
    document.documentElement.style.setProperty('--quran-fs', State.fs + 'px');
    Store.write({ fs: State.fs });
  },
  setDark(on) {
    State.dark = on; document.body.classList.toggle('dark', on);
    $('#btn-theme').textContent = on ? '☀️' : '🌙';
    $('#tg-dark').setAttribute('aria-checked', String(on));
    $('meta[name=theme-color]').content = on ? '#060E0C' : '#062E29';
    Store.write({ dark: on });
  },
  setMemorize(on) {
    State.memorize = on;
    $('#mushaf').classList.toggle('memorize', on);
    $('#btn-memorize').setAttribute('aria-pressed', String(on));
    $('#tg-memorize').setAttribute('aria-checked', String(on));
    Store.write({ memorize: on });
  },
  setStrict(v) {
    State.strict = v;
    $$('#strict-group .seg').forEach(b => b.setAttribute('aria-pressed', String(b.dataset.strict === v)));
    Store.write({ strict: v });
  },

  openDrawer() {
    this.lastFocus = document.activeElement;
    $('#drawer').classList.add('on'); $('#drawer').setAttribute('aria-hidden', 'false');
    $('#scrim').classList.add('on'); $('#burger').setAttribute('aria-expanded', 'true');
    setTimeout(() => $('#open-ayyub').focus(), 120);
  },
  openSheet() {
    $('#drawer').classList.remove('on'); $('#drawer').setAttribute('aria-hidden', 'true'); $('#burger').setAttribute('aria-expanded', 'false');
    $('#scrim').classList.remove('on');
    $('#ayyub-sheet').classList.add('on'); $('#ayyub-sheet').setAttribute('aria-hidden', 'false');
    this.paintSources(); this.paintPlaying();
  },
  openModal(id) {
    this.lastFocus = document.activeElement;
    $('#' + id).classList.add('on'); $('#' + id).setAttribute('aria-hidden', 'false');
  },
  closeAll() {
    $('#drawer').classList.remove('on'); $('#drawer').setAttribute('aria-hidden', 'true'); $('#burger').setAttribute('aria-expanded', 'false');
    $('#scrim').classList.remove('on');
    $('#ayyub-sheet').classList.remove('on'); $('#ayyub-sheet').setAttribute('aria-hidden', 'true');
    $$('.modal').forEach(m => { m.classList.remove('on'); m.setAttribute('aria-hidden', 'true'); });
    if (this.lastFocus && this.lastFocus.focus) { try { this.lastFocus.focus(); } catch (e) { /* */ } }
  },

  buildAyyub() {
    /* بطاقة طه + يوتيوب + رابط خاص */
    $('#taha-hero').onclick = () => Player.play(TAHA);
    $('#yt-link').href = 'https://www.youtube.com/results?search_query=' + encodeURIComponent('قراءة محمد أيوب سورة طه');
    const box = $('#custom-url'), inp = $('#taha-url');
    inp.value = Store.read().tahaUrl || '';
    if (inp.value) box.classList.add('on');
    $('#taha-custom-toggle').onclick = () => box.classList.toggle('on');
    $('#taha-url-save').onclick = () => {
      const v = inp.value.trim();
      if (v && !/^https?:\/\//i.test(v)) { toast('الرابط يجب أن يبدأ بـ https://', 'bad'); return; }
      Store.write({ tahaUrl: v });
      toast(v ? 'حُفظ رابط طه' : 'حُذف الرابط الخاص', 'ok');
    };

    const feat = $('#featured');
    FEATURED_SURAHS.forEach(n => {
      const b = document.createElement('button');
      b.className = 'star-btn'; b.textContent = '★ ' + surahOf(n).name;
      b.onclick = () => Player.play(n);
      feat.appendChild(b);
    });
    const list = $('#surah-list');
    list.innerHTML = SURAHS.map(s => `
      <div class="s-item" data-n="${s.n}" data-name="${s.name}">
        <button class="s-main" data-play="${s.n}" aria-label="تشغيل سورة ${s.name}">
          <span class="s-num">${toAr(s.n)}</span>
          <span class="s-name">${s.name}<small>${toAr(s.ayahs)} آية · صفحة ${toAr(s.page)}</small></span>
        </button>
        <button class="s-read" data-read="${s.n}" aria-label="اقرأ سورة ${s.name} في المصحف">اقرأ</button>
      </div>`).join('');
    list.onclick = e => {
      const p = e.target.closest('[data-play]'), r = e.target.closest('[data-read]');
      if (p) Player.play(+p.dataset.play);
      else if (r) { Nav.go(surahOf(+r.dataset.read).page); this.closeAll(); }
    };
    $('#surah-search').oninput = e => {
      const q = norm(e.target.value);
      $$('.s-item', list).forEach(it => { it.hidden = !!q && !norm(it.dataset.name).includes(q) && it.dataset.n !== e.target.value.trim(); });
    };
  },
  paintSources() {
    const row = $('#src-row');
    row.innerHTML = '';
    AUDIO_SOURCES.forEach((s, i) => {
      const b = document.createElement('button');
      b.className = 'seg'; b.setAttribute('aria-pressed', String(i === Player.srcIdx));
      b.innerHTML = `${s.label}<small>${s.note}</small>`;
      b.onclick = () => Player.setSource(i);
      row.appendChild(b);
    });
  },
  paintPlaying() {
    $$('.s-item').forEach(it => it.classList.toggle('playing', +it.dataset.n === Player.surah));
  }
};

/* ═══════════════════════════════════════════════════════════════
   11) الإقلاع
   ═══════════════════════════════════════════════════════════════ */

const App = {
  onFinish() {
    Mic.stop();
    const { ok, att } = State.stats;
    $('#fin-acc').textContent = att ? toAr(Math.round((ok / att) * 100)) + '٪' : '—';
    $('#finish').classList.add('on');
  },

  async boot() {
    const p = Store.read();
    UI.init();
    Player.init();
    UI.setFont(p.fs || 30);
    UI.setDark(!!p.dark);
    UI.setMemorize(!!p.memorize);
    UI.setStrict(p.strict || 'normal');
    State.autoTurn = p.autoTurn !== false;
    $('#tg-auto').setAttribute('aria-checked', String(State.autoTurn));
    refreshStats();
    try { await Nav.go(p.page || 1); } catch (e) { showNotice('حدث خطأ غير متوقع. أعد تحميل الصفحة.'); }
    setTimeout(() => {
      const s = $('#splash'); s.classList.add('hide'); setTimeout(() => s.remove(), 800);
    }, 900);
  }
};

App.boot();
</script>
</body>
</html>
