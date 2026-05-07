---
layout: single
title: "[워크샵] 어깨 실전 워크샵 & 간담회 — 임상 5년 차 이하 대상"
date: 2026-05-07 13:00:00 -0800
categories: [education]
tags: [워크샵, 어깨, 드라이니들링, 도침, 실습, 신입회원]
excerpt: "이론은 짧게, 실습은 빡세게! 4:1 밀착 멘토링. 5/23(토) 18:00–20:30 · Greenleaf Clinic, Vancouver · 선착순 12명 · 회원 무료"
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Black+Han+Sans&family=Oswald:wght@400;500;700&family=Noto+Sans+KR:wght@300;400;500;700&display=swap');

:root {
  --bg:      #0f0e12;
  --bg2:     #181620;
  --bg3:     #221f2e;
  --hot:     #f04c1c;
  --amber:   #f5c330;
  --text:    #f0ebe3;
  --muted:   rgba(240,235,227,0.5);
  --border:  rgba(240,235,227,0.09);
}

.sw {
  font-family: 'Noto Sans KR', sans-serif;
  background: var(--bg);
  color: var(--text);
  margin: -0.5rem -1rem;
  padding: 0;
  border-radius: 14px;
  overflow: hidden;
}

/* ── Hero ── */
.sw-hero {
  background: var(--bg);
  padding: 3rem 2rem 2.5rem;
  position: relative;
  overflow: hidden;
}

.sw-hero::before {
  content: '肩';
  position: absolute;
  right: -1rem;
  top: -2rem;
  font-family: 'Black Han Sans', sans-serif;
  font-size: 16rem;
  color: rgba(240, 76, 28, 0.07);
  pointer-events: none;
  line-height: 1;
  letter-spacing: -0.05em;
}

.sw-hero::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 2px;
  background: linear-gradient(90deg, var(--hot), var(--amber), transparent);
}

.sw-tag-row {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  margin-bottom: 1.4rem;
  flex-wrap: wrap;
}

.sw-badge {
  font-family: 'Oswald', sans-serif;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  padding: 0.25rem 0.75rem;
  border-radius: 3px;
}

.sw-badge.hot  { background: var(--hot); color: #fff; }
.sw-badge.dim  { background: var(--bg3); color: var(--muted); border: 1px solid var(--border); }
.sw-badge.amber { background: var(--amber); color: #1a1600; }

.sw-hero h1 {
  font-family: 'Black Han Sans', sans-serif;
  font-size: clamp(1.8rem, 5vw, 3.2rem);
  font-weight: 400;
  color: var(--text);
  line-height: 1.15;
  margin: 0 0 0.5rem;
  padding: 0;
  border: none;
}

.sw-hero h1 em {
  color: var(--hot);
  font-style: normal;
}

.sw-hero-sub {
  font-size: 0.9rem;
  color: var(--muted);
  margin: 0;
  font-weight: 300;
}

/* ── Questions ── */
.sw-questions {
  background: var(--bg2);
  padding: 2rem;
  display: flex;
  flex-direction: column;
  gap: 0;
  border-top: 1px solid var(--border);
  border-bottom: 1px solid var(--border);
}

.sw-q {
  display: flex;
  align-items: flex-start;
  gap: 0.9rem;
  padding: 1rem 0;
  border-bottom: 1px solid var(--border);
  opacity: 0;
  animation: fadeUp 0.5s ease forwards;
}

.sw-q:last-child { border-bottom: none; }
.sw-q:nth-child(1) { animation-delay: 0.1s; }
.sw-q:nth-child(2) { animation-delay: 0.25s; }
.sw-q:nth-child(3) { animation-delay: 0.4s; }

@keyframes fadeUp {
  from { opacity: 0; transform: translateY(10px); }
  to   { opacity: 1; transform: translateY(0); }
}

.sw-q-mark {
  font-family: 'Oswald', sans-serif;
  font-size: 1.5rem;
  font-weight: 700;
  color: var(--hot);
  flex-shrink: 0;
  line-height: 1.2;
  margin-top: 0.05rem;
}

.sw-q-text {
  font-size: 0.97rem;
  color: var(--text);
  line-height: 1.65;
  font-weight: 400;
}

/* ── Punchline ── */
.sw-punchline {
  background: linear-gradient(135deg, var(--hot) 0%, #c0320a 100%);
  padding: 1.8rem 2rem;
  display: flex;
  align-items: center;
  gap: 1.2rem;
  flex-wrap: wrap;
}

.sw-punch-icon {
  font-size: 2.5rem;
  flex-shrink: 0;
}

.sw-punch-text {
  font-family: 'Black Han Sans', sans-serif;
  font-size: clamp(1.1rem, 3vw, 1.6rem);
  color: #fff;
  line-height: 1.3;
  margin: 0;
}

.sw-punch-sub {
  font-size: 0.85rem;
  color: rgba(255,255,255,0.75);
  margin: 0.2rem 0 0;
  font-weight: 300;
}

/* ── Info grid ── */
.sw-info {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1px;
  background: var(--border);
  border-top: 1px solid var(--border);
}

.sw-info-cell {
  background: var(--bg2);
  padding: 1.3rem 1.5rem;
  display: flex;
  align-items: flex-start;
  gap: 0.85rem;
}

.sw-info-icon { font-size: 1.3rem; margin-top: 0.05rem; flex-shrink: 0; }

.sw-info-lbl {
  font-family: 'Oswald', sans-serif;
  font-size: 0.63rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--hot);
  margin-bottom: 0.2rem;
}

.sw-info-val {
  font-size: 0.9rem;
  color: var(--text);
  font-weight: 500;
  line-height: 1.45;
}

.sw-info-val a {
  color: var(--amber);
  text-decoration: none;
}

.sw-info-val.free { color: var(--amber); }

/* ── Section title ── */
.sw-stitle {
  font-family: 'Oswald', sans-serif;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--hot);
  padding: 2rem 2rem 0.8rem;
  margin: 0;
  border-bottom: 1px solid var(--border);
}

/* ── Program ── */
.sw-program {
  background: var(--bg2);
  padding: 0 0 1rem;
}

.sw-prog-item {
  display: flex;
  align-items: flex-start;
  gap: 1.2rem;
  padding: 1.1rem 2rem;
  border-bottom: 1px solid var(--border);
  transition: background 0.2s;
}

.sw-prog-item:hover { background: var(--bg3); }
.sw-prog-item:last-child { border-bottom: none; }

.sw-prog-num {
  font-family: 'Oswald', sans-serif;
  font-size: 2rem;
  font-weight: 700;
  color: rgba(240, 76, 28, 0.25);
  flex-shrink: 0;
  line-height: 1;
  min-width: 2.2rem;
  margin-top: 0.1rem;
}

.sw-prog-content {}

.sw-prog-title {
  font-family: 'Noto Sans KR', sans-serif;
  font-size: 0.97rem;
  font-weight: 700;
  color: var(--text);
  margin-bottom: 0.2rem;
  line-height: 1.4;
}

.sw-prog-desc {
  font-size: 0.82rem;
  color: var(--muted);
  line-height: 1.5;
  margin: 0;
}

/* ── Ratio highlight ── */
.sw-ratio {
  background: var(--bg3);
  margin: 0;
  padding: 1.8rem 2rem;
  display: flex;
  align-items: center;
  gap: 2rem;
  border-top: 1px solid var(--border);
  flex-wrap: wrap;
}

.sw-ratio-num {
  font-family: 'Oswald', sans-serif;
  font-size: 5rem;
  font-weight: 700;
  color: var(--amber);
  line-height: 0.9;
  flex-shrink: 0;
}

.sw-ratio-unit {
  font-size: 1.5rem;
  color: var(--muted);
  font-family: 'Oswald', sans-serif;
}

.sw-ratio-text h3 {
  font-family: 'Black Han Sans', sans-serif;
  font-size: 1.2rem;
  color: var(--text);
  margin: 0 0 0.3rem;
  border: none;
}

.sw-ratio-text p {
  font-size: 0.85rem;
  color: var(--muted);
  margin: 0;
  line-height: 1.6;
}

/* ── Limit notice ── */
.sw-limit {
  background: var(--bg2);
  border: 1px solid rgba(245, 195, 48, 0.25);
  border-left: 3px solid var(--amber);
  margin: 0;
  padding: 1.2rem 1.5rem 1.2rem 2rem;
}

.sw-limit-header {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  margin-bottom: 0.5rem;
}

.sw-limit-badge {
  font-family: 'Oswald', sans-serif;
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  background: var(--amber);
  color: #1a1600;
  padding: 0.2rem 0.6rem;
  border-radius: 3px;
}

.sw-limit-title {
  font-size: 0.9rem;
  font-weight: 700;
  color: var(--amber);
}

.sw-limit p {
  font-size: 0.84rem;
  color: var(--muted);
  margin: 0;
  line-height: 1.7;
}

/* ── CTA ── */
.sw-cta {
  background: linear-gradient(135deg, #0f0e12, #1e1c28);
  padding: 2.5rem 2rem;
  text-align: center;
  border-top: 1px solid var(--border);
}

.sw-cta h3 {
  font-family: 'Black Han Sans', sans-serif;
  font-size: 1.5rem;
  color: var(--text);
  margin: 0 0 0.4rem;
  border: none;
}

.sw-cta p {
  font-size: 0.88rem;
  color: var(--muted);
  margin: 0 0 1.5rem;
  line-height: 1.7;
}

.sw-cta-box {
  display: inline-block;
  background: var(--hot);
  color: #fff !important;
  font-family: 'Black Han Sans', sans-serif;
  font-size: 1.1rem;
  padding: 1rem 2.5rem;
  border-radius: 6px;
  text-decoration: none !important;
  transition: background 0.2s, transform 0.2s;
  letter-spacing: 0.02em;
}

.sw-cta-box:hover {
  background: #d63a10;
  transform: translateY(-2px);
  color: #fff !important;
  text-decoration: none !important;
}

.sw-cta-note {
  margin-top: 1rem;
  font-size: 0.78rem;
  color: rgba(240,235,227,0.35);
}

/* ── Responsive ── */
@media (max-width: 560px) {
  .sw-hero::before { display: none; }
  .sw-punchline { flex-direction: column; gap: 0.6rem; }
  .sw-ratio { gap: 1rem; }
  .sw-ratio-num { font-size: 3.5rem; }
}
</style>

<div class="sw">

  <!-- Hero -->
  <div class="sw-hero">
    <div class="sw-tag-row">
      <span class="sw-badge hot">Pilot · 선착순 12명</span>
      <span class="sw-badge dim">임상 5년 차 이하</span>
      <span class="sw-badge amber">회원 무료</span>
    </div>
    <h1>어깨 실전 워크샵<br>&amp; <em>간담회</em></h1>
    <p class="sw-hero-sub">Hands-on · 멘토 1:1 · 드라이니들링 · 도침 · 이학검사</p>
  </div>

  <!-- 3 Questions -->
  <div class="sw-questions">
    <div class="sw-q">
      <span class="sw-q-mark">"</span>
      <span class="sw-q-text">책에서 본 이학검사, 내가 하는 게 맞나?</span>
    </div>
    <div class="sw-q">
      <span class="sw-q-mark">"</span>
      <span class="sw-q-text">드라이니들링 어떻게 하는 거야?</span>
    </div>
    <div class="sw-q">
      <span class="sw-q-mark">"</span>
      <span class="sw-q-text">도침, 어깨에 써보고는 싶은데 겁이 난다면?</span>
    </div>
  </div>

  <!-- Punchline -->
  <div class="sw-punchline">
    <span class="sw-punch-icon">🔥</span>
    <div>
      <p class="sw-punch-text">이론은 짧게, 실습은 빡세게!</p>
      <p class="sw-punch-sub">4인 1조마다 배정된 임상 멘토(선배 한의사)가 여러분의 손끝을 직접 교정해 드립니다.</p>
    </div>
  </div>

  <!-- Info -->
  <div class="sw-info">
    <div class="sw-info-cell">
      <span class="sw-info-icon">📅</span>
      <div>
        <div class="sw-info-lbl">일시</div>
        <div class="sw-info-val">2026년 5월 23일 (토)<br>18:00 – 20:30</div>
      </div>
    </div>
    <div class="sw-info-cell">
      <span class="sw-info-icon">📍</span>
      <div>
        <div class="sw-info-lbl">장소</div>
        <div class="sw-info-val">Greenleaf Acupuncture &amp; Herb Clinic<br>409 Granville St #1455, Vancouver</div>
      </div>
    </div>
    <div class="sw-info-cell">
      <span class="sw-info-icon">💰</span>
      <div>
        <div class="sw-info-lbl">참가비</div>
        <div class="sw-info-val free">회원 무료<br><span style="font-size:0.78rem;color:var(--muted)">파일럿 프로그램</span></div>
      </div>
    </div>
  </div>

  <!-- Program -->
  <div class="sw-program">
    <div class="sw-stitle">프로그램</div>

    <div class="sw-prog-item">
      <div class="sw-prog-num">01</div>
      <div class="sw-prog-content">
        <div class="sw-prog-title">핵심 아나토미 &amp; 이학검사 마스터</div>
        <p class="sw-prog-desc">짧고 정확한 이론 세션 — 어깨 구조와 검사법 핵심만</p>
      </div>
    </div>

    <div class="sw-prog-item">
      <div class="sw-prog-num">02</div>
      <div class="sw-prog-content">
        <div class="sw-prog-title">Dry Needling부터 도침까지 실전 Hands-on</div>
        <p class="sw-prog-desc">이론에서 멈추지 않는 실전 자침 — 테크닉을 내 것으로</p>
      </div>
    </div>

    <div class="sw-prog-item">
      <div class="sw-prog-num">03</div>
      <div class="sw-prog-content">
        <div class="sw-prog-title">파트너 자침 실습 &amp; 멘토 1:1 피드백</div>
        <p class="sw-prog-desc">서로서로 짝이 되어 실습 — 본인도 침을 맞습니다</p>
      </div>
    </div>

    <div class="sw-prog-item">
      <div class="sw-prog-num">04</div>
      <div class="sw-prog-content">
        <div class="sw-prog-title">"협회와 이런 것들을 해보고 싶다" — 운영진과의 간담회</div>
        <p class="sw-prog-desc">여러분의 아이디어를 협회에 직접 전하는 시간</p>
      </div>
    </div>
  </div>

  <!-- 4:1 ratio -->
  <div class="sw-ratio">
    <div>
      <span class="sw-ratio-num">4</span><span class="sw-ratio-unit">:1</span>
    </div>
    <div class="sw-ratio-text">
      <h3>밀착 멘토 케어</h3>
      <p>선배들의 노하우를 그대로 전수받는 4인 1조 멘토 시스템.<br>멘토가 여러분의 손끝을 직접 봐줍니다.</p>
    </div>
  </div>

  <!-- Limit notice -->
  <div class="sw-limit">
    <div class="sw-limit-header">
      <span class="sw-limit-badge">선착순 마감</span>
      <span class="sw-limit-title">최대 12명</span>
    </div>
    <p>멘토 배정 때문에 선착순 12명까지 입니다. 13명부터는 멘토 섭외가 어려울 수 있어 참여가 제한될 수 있습니다. 어깨 진료의 답답함, 한 번에 뚫어드립니다.</p>
  </div>

  <!-- CTA -->
  <div class="sw-cta">
    <h3>지금 바로 신청하세요</h3>
    <p>협회 단톡방에 "신청합니다"라고 남겨주세요.<br>문의: <a href="mailto:komaaofbc@gmail.com" style="color:var(--amber)">komaaofbc@gmail.com</a></p>
    <a href="mailto:komaaofbc@gmail.com" class="sw-cta-box">👇 단톡방 신청</a>
    <div class="sw-cta-note">본인도 침을 맞아야 합니다 — 미리 마음의 준비를 :)</div>
  </div>

</div>
