---
layout: single
title: "[보수교육] 통증의 신경과학 — 3강 시리즈 (6/9 · 6/16 · 6/23)"
date: 2026-06-08 12:00:00 -0800
categories: [education]
tags: [보수교육, 통증, 신경과학, 신경생리학, 신경가소성, 줌강의]
excerpt: "통증의 신경생리학부터 예측하는 뇌와 신경 가소성까지 — 김대유 원장의 3강 시리즈. 매주 화요일 오후 7–9시 (BC Time) · 회원 무료"
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&family=Black+Han+Sans&display=swap');

.pn {
  font-family: 'Noto Sans KR', 'Apple SD Gothic Neo', sans-serif;
  color: #1a1a1a;
  line-height: 1.7;
}

/* ── Hero ── */
.pn-hero {
  background: linear-gradient(150deg, #0f1f3d 0%, #1a3057 45%, #0d2640 100%);
  color: #f0f4ff;
  padding: 3.5rem 2rem 3rem;
  margin-bottom: 1.8rem;
  position: relative;
  overflow: hidden;
  border-radius: 14px;
}

.pn-hero::before {
  content: '神經';
  position: absolute;
  right: -0.5rem;
  top: -1.5rem;
  font-size: 11rem;
  font-family: 'Noto Sans KR', serif;
  font-weight: 900;
  color: rgba(100,160,255,0.05);
  pointer-events: none;
  line-height: 1;
  letter-spacing: -0.05em;
}

.pn-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: rgba(100,160,255,0.15);
  border: 1px solid rgba(100,160,255,0.35);
  color: #7eb8ff;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.18em;
  padding: 0.3rem 0.85rem;
  border-radius: 3px;
  margin-bottom: 1.4rem;
  text-transform: uppercase;
}

.pn-hero h1 {
  font-family: 'Black Han Sans', 'Noto Sans KR', sans-serif;
  font-size: clamp(1.8rem, 5vw, 2.6rem);
  font-weight: 900;
  color: #ffffff;
  line-height: 1.25;
  margin: 0 0 0.6rem;
  letter-spacing: -0.02em;
}

.pn-hero h1 em {
  font-style: normal;
  color: #7eb8ff;
}

.pn-hero-sub {
  font-size: 0.95rem;
  color: rgba(240,244,255,0.7);
  margin: 0;
  font-weight: 300;
}

.pn-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 1.5rem;
}

.pn-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  background: rgba(255,255,255,0.1);
  border: 1px solid rgba(255,255,255,0.2);
  color: #f0f4ff;
  font-size: 0.75rem;
  font-weight: 500;
  padding: 0.28rem 0.75rem;
  border-radius: 20px;
}

/* ── Theme Card ── */
.pn-theme {
  background: #f5f8ff;
  border-left: 4px solid #3a6fd8;
  border-radius: 0 10px 10px 0;
  padding: 1.4rem 1.6rem;
  margin-bottom: 2rem;
}

.pn-theme-label {
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  color: #3a6fd8;
  text-transform: uppercase;
  margin-bottom: 0.4rem;
}

.pn-theme h2 {
  font-family: 'Black Han Sans', 'Noto Sans KR', sans-serif;
  font-size: 1.6rem;
  font-weight: 900;
  color: #0f1f3d;
  margin: 0 0 0.2rem;
}

.pn-theme-sub {
  font-size: 0.85rem;
  color: #5a6a82;
  margin: 0;
}

/* ── Lecture Cards ── */
.pn-lectures {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-bottom: 2.5rem;
}

.pn-lecture {
  background: #ffffff;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  padding: 1.4rem 1.6rem;
  display: flex;
  gap: 1.2rem;
  align-items: flex-start;
  box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  transition: box-shadow 0.2s;
}

.pn-lecture:hover {
  box-shadow: 0 4px 16px rgba(58,111,216,0.12);
}

.pn-num {
  width: 2.4rem;
  height: 2.4rem;
  min-width: 2.4rem;
  background: linear-gradient(135deg, #3a6fd8, #1a4aa8);
  color: #fff;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 1rem;
  margin-top: 0.1rem;
}

.pn-lecture-body {
  flex: 1;
}

.pn-lecture-title {
  font-size: 1.05rem;
  font-weight: 700;
  color: #0f1f3d;
  margin: 0 0 0.15rem;
}

.pn-lecture-date {
  font-size: 0.78rem;
  color: #3a6fd8;
  font-weight: 500;
  margin-bottom: 0.6rem;
}

.pn-lecture-desc {
  background: #f5f8ff;
  border-radius: 6px;
  padding: 0.65rem 0.9rem;
  font-size: 0.88rem;
  color: #3a4a5e;
  margin: 0;
  line-height: 1.6;
}

.pn-lecture-desc::before {
  content: '💡 ';
}

/* ── Divider ── */
.pn-divider {
  border: none;
  border-top: 1px solid #e2e8f0;
  margin: 2rem 0;
}

/* ── Instructor ── */
.pn-instructor-label {
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  color: #5a6a82;
  text-transform: uppercase;
  margin-bottom: 1rem;
}

.pn-instructor {
  display: flex;
  align-items: center;
  gap: 1.4rem;
  background: #f9fafb;
  border-radius: 12px;
  padding: 1.4rem 1.6rem;
  margin-bottom: 2rem;
}

.pn-avatar {
  width: 3.8rem;
  height: 3.8rem;
  min-width: 3.8rem;
  background: linear-gradient(135deg, #3a6fd8, #1a4aa8);
  color: #fff;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Black Han Sans', sans-serif;
  font-size: 1.5rem;
  font-weight: 900;
}

.pn-instructor-name {
  font-size: 1.2rem;
  font-weight: 700;
  color: #0f1f3d;
  margin: 0 0 0.15rem;
}

.pn-instructor-title {
  font-size: 0.82rem;
  color: #5a6a82;
  margin-bottom: 0.6rem;
}

.pn-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
}

.pn-tag {
  background: #e8effc;
  color: #2a52a8;
  font-size: 0.72rem;
  font-weight: 600;
  padding: 0.22rem 0.65rem;
  border-radius: 4px;
}

/* ── Info Grid ── */
.pn-info {
  background: #0f1f3d;
  border-radius: 14px;
  padding: 1.8rem 2rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.4rem 2rem;
}

@media (max-width: 480px) {
  .pn-info { grid-template-columns: 1fr; }
}

.pn-info-item {}

.pn-info-icon {
  font-size: 1rem;
  margin-bottom: 0.3rem;
}

.pn-info-label {
  font-size: 0.68rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  color: rgba(240,244,255,0.45);
  text-transform: uppercase;
  margin-bottom: 0.2rem;
}

.pn-info-value {
  font-size: 1.05rem;
  font-weight: 700;
  color: #ffffff;
  margin-bottom: 0.1rem;
}

.pn-info-sub {
  font-size: 0.75rem;
  color: rgba(240,244,255,0.5);
}

.pn-info-value.highlight {
  color: #7eb8ff;
  font-size: 1.15rem;
}
</style>

<div class="pn">

<!-- Flyer Image -->
<div style="margin-bottom:1.8rem;">
  <img src="/assets/images/2026-06-08-pain-neuroscience-flyer.png" alt="6월 KOMAA 보수교육 — 통증의 신경과학 포스터" style="width:100%;border-radius:14px;box-shadow:0 4px 20px rgba(0,0,0,0.15);">
</div>

<!-- Hero -->
<div class="pn-hero">
  <div class="pn-eyebrow">● KOMAA · Continuing Education · June 2026</div>
  <h1>6월 KOMAA 보수 교육<br><em>통증의 신경과학</em></h1>
  <p class="pn-hero-sub">Neuroscience of Pain — 3-Part Lecture Series</p>
  <div class="pn-badges">
    <span class="pn-badge">● 온라인 줌강의</span>
    <span class="pn-badge">● 3강 시리즈</span>
    <span class="pn-badge">● 회원 무료</span>
  </div>
</div>

<!-- Theme -->
<div class="pn-theme">
  <div class="pn-theme-label">이번 달 주제</div>
  <h2>통증의 신경과학</h2>
  <p class="pn-theme-sub">Neuroscience of Pain — 3-Part Lecture Series</p>
</div>

<!-- Lectures -->
<div class="pn-lectures">

  <div class="pn-lecture">
    <div class="pn-num">1</div>
    <div class="pn-lecture-body">
      <div class="pn-lecture-title">통증의 신경생리학</div>
      <div class="pn-lecture-date">Neurophysiology of Pain · 6월 9일</div>
      <p class="pn-lecture-desc">통증에 대한 우리의 기본 인식과 전반적인 이해를 다룹니다</p>
    </div>
  </div>

  <div class="pn-lecture">
    <div class="pn-num">2</div>
    <div class="pn-lecture-body">
      <div class="pn-lecture-title">통증의 해부학</div>
      <div class="pn-lecture-date">Anatomy of Pain · 6월 16일</div>
      <p class="pn-lecture-desc">뇌의 여러 부위(편도체, 전전두엽 등)가 통증을 만드는 원리 — 왜 불안·우울할 때 더 아픈지 해부학적으로 설명</p>
    </div>
  </div>

  <div class="pn-lecture">
    <div class="pn-num">3</div>
    <div class="pn-lecture-body">
      <div class="pn-lecture-title">예측하는 뇌와 신경 가소성</div>
      <div class="pn-lecture-date">Predictive Brain &amp; Neuroplasticity · 6월 23일</div>
      <p class="pn-lecture-desc">만성 통증 = 뇌 회로의 오작동 → 신경 가소성을 이용한 치료적 원리 (명상·인지치료 등)</p>
    </div>
  </div>

</div>

<hr class="pn-divider">

<!-- Instructor -->
<div class="pn-instructor-label">강사 소개</div>
<div class="pn-instructor">
  <div class="pn-avatar">김</div>
  <div>
    <div class="pn-instructor-name">김대유 원장</div>
    <div class="pn-instructor-title">Daeyou Kim, PhD, R.TCMP</div>
    <div class="pn-tags">
      <span class="pn-tag">PhD Biochemistry</span>
      <span class="pn-tag">TCM Practitioner</span>
      <span class="pn-tag">Lifemark Health</span>
      <span class="pn-tag">임상 16년</span>
    </div>
  </div>
</div>

<!-- Info Grid -->
<div class="pn-info">
  <div class="pn-info-item">
    <div class="pn-info-icon">📅</div>
    <div class="pn-info-label">강의 일정</div>
    <div class="pn-info-value">6/9 · 6/16 · 6/23</div>
    <div class="pn-info-sub">매주 화요일</div>
  </div>
  <div class="pn-info-item">
    <div class="pn-info-icon">🕖</div>
    <div class="pn-info-label">시간</div>
    <div class="pn-info-value">오후 7시 – 9시</div>
    <div class="pn-info-sub">BC Time 기준</div>
  </div>
  <div class="pn-info-item">
    <div class="pn-info-icon">💻</div>
    <div class="pn-info-label">형식</div>
    <div class="pn-info-value">온라인 Zoom</div>
    <div class="pn-info-sub">링크 추후 공지</div>
  </div>
  <div class="pn-info-item">
    <div class="pn-info-icon">💰</div>
    <div class="pn-info-label">강의비</div>
    <div class="pn-info-value highlight">회원 무료</div>
    <div class="pn-info-sub">KOMAA Members Only</div>
  </div>
</div>

</div>
