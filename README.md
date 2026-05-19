[newsletter-june-2026.html](https://github.com/user-attachments/files/27985348/newsletter-june-2026.html)
# news-letter-june-26<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Acorn City Kids — June 2026 Newsletter</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:ital,wght@0,400;0,600;0,700;1,400&family=Nunito+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  background: #F2EDE6;
  font-family: 'Nunito Sans', sans-serif;
  color: #1C1410;
  line-height: 1.6;
  padding: 2rem 1rem 4rem;
}

/* ── OUTER WRAPPER ── */
.wrapper {
  max-width: 660px;
  margin: 0 auto;
}

/* ── HEADER ── */
.nl-header {
  background: linear-gradient(135deg, #6B3009 0%, #C4621D 50%, #E8873F 100%);
  border-radius: 18px 18px 0 0;
  padding: 2.5rem 2rem 2rem;
  text-align: center;
  color: #fff;
  position: relative;
  overflow: hidden;
}
.nl-header::before {
  content: '';
  position: absolute;
  top: -60px; right: -60px;
  width: 200px; height: 200px;
  background: rgba(255,255,255,0.06);
  border-radius: 50%;
}
.nl-header::after {
  content: '';
  position: absolute;
  bottom: -50px; left: -40px;
  width: 160px; height: 160px;
  background: rgba(0,0,0,0.07);
  border-radius: 50%;
}
.nl-logo {
  font-family: 'Fredoka One', cursive;
  font-size: 30px;
  font-weight: 400;
  position: relative;
  letter-spacing: .3px;
}
.nl-logo span { color: #FFE0B2; }
.nl-edition {
  position: relative;
  display: inline-block;
  background: rgba(255,255,255,0.18);
  border: 1px solid rgba(255,255,255,0.3);
  border-radius: 999px;
  padding: 4px 16px;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: .08em;
  text-transform: uppercase;
  margin: 10px 0 14px;
}
.nl-headline {
  position: relative;
  font-family: 'Fredoka One', cursive;
  font-size: clamp(22px, 5vw, 34px);
  font-weight: 400;
  line-height: 1.2;
  margin-bottom: 8px;
}
.nl-sub {
  position: relative;
  font-size: 14px;
  opacity: 0.88;
  max-width: 480px;
  margin: 0 auto;
}

/* ── BODY CONTAINER ── */
.nl-body {
  background: #FFFFFF;
  padding: 0;
  border-radius: 0 0 18px 18px;
  overflow: hidden;
}

/* ── KIND STRIP ── */
.kind-strip {
  background: #FDF0E6;
  border-top: 3px solid #E8873F;
  padding: 12px 24px;
  text-align: center;
  font-size: 13px;
  font-weight: 700;
  color: #9B4A10;
  letter-spacing: .03em;
}
.kind-strip span { margin: 0 6px; }

/* ── WELCOME NOTE ── */
.welcome-note {
  padding: 1.75rem 2rem 1.25rem;
  border-bottom: 1px solid rgba(100,60,20,0.1);
}
.welcome-note p {
  font-size: 14.5px;
  color: #4A3728;
  line-height: 1.75;
}
.welcome-note p + p { margin-top: 10px; }
.welcome-note .sig {
  margin-top: 14px;
  font-family: 'Nunito', sans-serif;
  font-style: italic;
  font-size: 14px;
  color: #C4621D;
}

/* ── SECTION LABELS ── */
.section {
  padding: 1.5rem 2rem;
  border-bottom: 1px solid rgba(100,60,20,0.08);
}
.section:last-child { border-bottom: none; }

.section-label {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 1.1rem;
}
.section-label-icon {
  width: 36px; height: 36px;
  border-radius: 10px;
  display: flex; align-items: center; justify-content: center;
  font-size: 18px;
  flex-shrink: 0;
}
.icon-green  { background: #E5F4ED; }
.icon-orange { background: #FDF0E6; }
.icon-purple { background: #EDEAFC; }
.icon-sky    { background: #E3F1FB; }
.icon-amber  { background: #FDF3DC; }
.icon-pink   { background: #FBEAF0; }

.section-label h2 {
  font-family: 'Fredoka One', cursive;
  font-size: 18px;
  font-weight: 400;
  letter-spacing: .2px;
}
.section-label h2.green  { color: #1E6B46; }
.section-label h2.orange { color: #9B4A10; }
.section-label h2.purple { color: #3D2D8C; }
.section-label h2.sky    { color: #1A5F8A; }
.section-label h2.amber  { color: #8A5610; }
.section-label h2.pink   { color: #882245; }

/* ── EVENT CARDS ── */
.event-list { display: flex; flex-direction: column; gap: 12px; }

.event-card {
  border: 1px solid rgba(100,60,20,0.12);
  border-radius: 12px;
  padding: 14px 16px;
  display: flex;
  gap: 14px;
  align-items: flex-start;
  transition: box-shadow .15s;
}
.event-card:hover { box-shadow: 0 3px 14px rgba(100,60,20,0.1); }

.event-date-block {
  flex-shrink: 0;
  width: 52px;
  text-align: center;
  background: #FDF0E6;
  border-radius: 10px;
  padding: 8px 4px;
  border: 1px solid rgba(196,98,29,0.2);
}
.event-date-block .month {
  font-size: 10px;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: .08em;
  color: #C4621D;
}
.event-date-block .day {
  font-family: 'Fredoka One', cursive;
  font-size: 22px;
  font-weight: 400;
  color: #1C1410;
  line-height: 1.1;
}
.event-date-block .dow {
  font-size: 9px;
  font-weight: 700;
  text-transform: uppercase;
  color: #A8998F;
  letter-spacing: .06em;
}

.event-info { flex: 1; min-width: 0; }
.event-title {
  font-family: 'Nunito', sans-serif;
  font-size: 14.5px;
  font-weight: 700;
  color: #1C1410;
  margin-bottom: 3px;
  line-height: 1.3;
}
.event-meta {
  font-size: 12px;
  color: #A8998F;
  margin-bottom: 5px;
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  align-items: center;
}
.event-meta span { display: flex; align-items: center; gap: 3px; }
.event-desc { font-size: 13px; color: #6B5C52; line-height: 1.55; }
.event-tags { display: flex; flex-wrap: wrap; gap: 5px; margin-top: 7px; }
.etag {
  font-size: 10.5px;
  font-weight: 700;
  padding: 2px 9px;
  border-radius: 999px;
  letter-spacing: .01em;
}
.etag-free    { background: #E5F4ED; color: #1E6B46; }
.etag-low     { background: #FDF3DC; color: #8A5610; }
.etag-sn      { background: #EDEAFC; color: #3D2D8C; }
.etag-nature  { background: #E5F4ED; color: #1E6B46; }
.etag-outdoor { background: #E3F1FB; color: #1A5F8A; }
.etag-art     { background: #FBEAF0; color: #882245; }
.etag-music   { background: #FDF3DC; color: #8A5610; }
.etag-animals { background: #FFF3E0; color: #8A4B00; }

/* ── WORKSHOP CARDS ── */
.workshop-card {
  background: linear-gradient(135deg, #FEFCF8, #FDF0E6);
  border: 1.5px solid rgba(196,98,29,0.2);
  border-radius: 12px;
  padding: 16px 18px;
  margin-bottom: 12px;
}
.workshop-card:last-child { margin-bottom: 0; }
.workshop-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 10px;
  margin-bottom: 8px;
}
.workshop-title {
  font-family: 'Nunito', sans-serif;
  font-size: 14.5px;
  font-weight: 700;
  color: #1C1410;
  line-height: 1.3;
}
.workshop-badge {
  flex-shrink: 0;
  font-size: 10.5px;
  font-weight: 800;
  padding: 3px 10px;
  border-radius: 999px;
  text-transform: uppercase;
  letter-spacing: .05em;
}
.wb-free { background: #E5F4ED; color: #1E6B46; }
.wb-low  { background: #FDF3DC; color: #8A5610; }

.workshop-meta {
  font-size: 12px;
  color: #A8998F;
  margin-bottom: 6px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
.workshop-desc { font-size: 13px; color: #6B5C52; line-height: 1.55; }

/* ── ACTIVITY CHECKLIST ── */
.checklist { list-style: none; display: flex; flex-direction: column; gap: 10px; }
.checklist li {
  display: flex;
  align-items: flex-start;
  gap: 12px;
  font-size: 13.5px;
  color: #4A3728;
  line-height: 1.55;
}
.check-icon {
  width: 26px; height: 26px;
  border-radius: 8px;
  display: flex; align-items: center; justify-content: center;
  font-size: 14px;
  flex-shrink: 0;
  margin-top: 1px;
}
.ci-green  { background: #E5F4ED; }
.ci-orange { background: #FDF0E6; }
.ci-sky    { background: #E3F1FB; }
.ci-purple { background: #EDEAFC; }
.ci-amber  { background: #FDF3DC; }

/* ── SN SPOTLIGHT ── */
.sn-spotlight {
  background: linear-gradient(135deg, #F5F3FE, #EDEAFC);
  border-radius: 12px;
  border: 1.5px solid #C8C2F0;
  padding: 16px 18px;
  margin-bottom: 12px;
}
.sn-spotlight:last-child { margin-bottom: 0; }
.sn-title {
  font-family: 'Nunito', sans-serif;
  font-size: 14.5px;
  font-weight: 700;
  color: #3D2D8C;
  margin-bottom: 5px;
}
.sn-details {
  font-size: 12px;
  color: #7B6FBA;
  margin-bottom: 6px;
  font-weight: 600;
}
.sn-desc { font-size: 13px; color: #5A5090; line-height: 1.55; }

/* ── KIND CORNER ── */
.kind-corner {
  background: linear-gradient(135deg, #FFF8F0, #FDF0E6);
  border-radius: 12px;
  border: 1.5px solid rgba(196,98,29,0.25);
  padding: 18px 20px;
  text-align: center;
}
.kind-corner .kc-emoji { font-size: 32px; margin-bottom: 8px; display: block; }
.kind-corner h3 {
  font-family: 'Fredoka One', cursive;
  font-size: 17px;
  font-weight: 400;
  color: #9B4A10;
  margin-bottom: 8px;
}
.kind-corner p { font-size: 13.5px; color: #6B5C52; line-height: 1.65; }
.kind-corner .kc-quote {
  font-family: 'Nunito', sans-serif;
  font-style: italic;
  font-size: 15px;
  color: #C4621D;
  font-weight: 700;
  margin-top: 12px;
  display: block;
}

/* ── DIVIDER ── */
.divider {
  height: 1px;
  background: rgba(100,60,20,0.08);
  margin: 0 2rem;
}

/* ── FOOTER ── */
.nl-footer {
  background: #3C1F0A;
  border-radius: 0 0 18px 18px;
  padding: 1.75rem 2rem;
  text-align: center;
  color: rgba(255,255,255,0.65);
  font-size: 12px;
  line-height: 1.8;
}
.nl-footer .footer-brand {
  font-family: 'Fredoka One', cursive;
  font-size: 20px;
  font-weight: 400;
  color: #FFD599;
  margin-bottom: 6px;
}
.nl-footer a { color: #FFB870; text-decoration: none; }
.nl-footer a:hover { text-decoration: underline; }
.nl-footer .unsub {
  margin-top: 12px;
  font-size: 11px;
  opacity: 0.5;
}

/* ── APP CTA BANNER ── */
.app-cta {
  background: linear-gradient(135deg, #1B4332, #2D6A4F, #40916C);
  border-radius: 14px;
  padding: 1.5rem 1.75rem;
  margin: 1.5rem 2rem 0;
  display: flex;
  align-items: center;
  gap: 16px;
  color: #fff;
  text-decoration: none;
  transition: opacity .15s, transform .15s;
}
.app-cta:hover { opacity: .93; transform: translateY(-1px); }
.app-cta-icon { font-size: 38px; flex-shrink: 0; }
.app-cta-text h3 {
  font-family: 'Fredoka One', cursive;
  font-size: 17px;
  font-weight: 400;
  margin-bottom: 4px;
  letter-spacing: .2px;
}
.app-cta-text p { font-size: 13px; opacity: .88; line-height: 1.5; }
.app-cta-arrow {
  margin-left: auto;
  flex-shrink: 0;
  background: rgba(255,255,255,0.2);
  border-radius: 999px;
  width: 36px; height: 36px;
  display: flex; align-items: center; justify-content: center;
  font-size: 18px;
}
@media (max-width: 500px) {
  .app-cta { flex-wrap: wrap; margin: 1.25rem 1.25rem 0; }
  .app-cta-arrow { display: none; }
}

/* ── PRINT / SHARE BAR ── */
.share-bar {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin: 1.5rem 0 0;
  flex-wrap: wrap;
}
.share-btn {
  padding: 8px 18px;
  border-radius: 999px;
  font-size: 12px;
  font-family: 'Nunito Sans', sans-serif;
  font-weight: 700;
  cursor: pointer;
  border: none;
  display: inline-flex;
  align-items: center;
  gap: 6px;
  transition: opacity .15s;
}
.share-btn:hover { opacity: .85; }
.btn-print  { background: #9B4A10; color: #fff; }
.btn-copy   { background: #2D6A4F; color: #fff; }

@media (max-width: 500px) {
  .nl-header { padding: 2rem 1.25rem 1.75rem; border-radius: 14px 14px 0 0; }
  .nl-footer { border-radius: 0 0 14px 14px; }
  .nl-body { border-radius: 0 0 14px 14px; }
  .section { padding: 1.25rem 1.25rem; }
  .welcome-note { padding: 1.25rem 1.25rem 1rem; }
  .event-card { flex-direction: column; }
  .event-date-block { width: 100%; display: flex; gap: 8px; align-items: center; justify-content: center; padding: 6px 12px; }
  .event-date-block .day { font-size: 18px; }
}
</style>
</head>
<body>

<div class="wrapper">

  <!-- HEADER -->
  <div class="nl-header">
    <div class="nl-logo">🌰 Acorn City <span>Kids</span></div>
    <div class="nl-edition">June 2026 Newsletter</div>
    <div class="nl-headline">Summer is Here — Let's Explore! 🌞</div>
    <p class="nl-sub">Free events, workshops, nature activities &amp; inclusive programs for Raleigh-area families this June</p>
  </div>

  <div class="nl-body">

    <!-- BE KIND STRIP -->
    <div class="kind-strip">
      🤝 <span>Be Kind to People</span> · 🐾 <span>Be Kind to Animals</span> · 🌿 <span>Be Kind to Nature</span> · 💛 <span>Be Kind to Yourself</span>
    </div>

    <!-- WELCOME NOTE -->
    <div class="welcome-note">
      <p>Hey Acorn City families! 🌰 Summer officially kicks off this month and the Raleigh area is absolutely packed with free and affordable things to do. From free outdoor concerts and nature workshops to Juneteenth celebrations and library summer reading — June 2026 is one of the best months of the year for families.</p>
      <p>We've rounded up the very best events, workshops, and weekly activities so you don't miss a thing. As always, we spotlight inclusive and special needs friendly programs because <strong>every child deserves a summer full of joy.</strong></p>
      <p>👉 Don't forget — you can always browse <strong>all 28+ free &amp; affordable activities</strong> anytime at <a href="https://acorncitykids.com" style="color:#C4621D;font-weight:700;">AcornCityKids.com</a>. Filter by category, cost, or special needs in seconds.</p>
      <p class="sig">— With love, The Acorn City Kids Team 🌿</p>
    </div>

    <!-- ══ SECTION 1: FEATURED EVENTS ══ -->
    <div class="section">
      <div class="section-label">
        <div class="section-label-icon icon-orange">🎉</div>
        <h2 class="orange">Featured June Events</h2>
      </div>
      <div class="event-list">

        <div class="event-card">
          <div class="event-date-block">
            <div class="month">Jun</div>
            <div class="day">12</div>
            <div class="dow">Fri</div>
          </div>
          <div class="event-info">
            <div class="event-title">MOSAIC Summer Concert Series — Free Outdoor Music</div>
            <div class="event-meta">
              <span>📍 MOSAIC at Chatham Park, Pittsboro</span>
              <span>🕖 7:00 PM</span>
            </div>
            <div class="event-desc">Bring your lawn chairs and blankets for a free family-friendly outdoor concert on the event lawn. Food and drinks available for purchase. Also on <strong>June 26</strong> — save both dates!</div>
            <div class="event-tags">
              <span class="etag etag-free">Free</span>
              <span class="etag etag-outdoor">Outdoor</span>
              <span class="etag etag-music">Live Music</span>
            </div>
          </div>
        </div>

        <div class="event-card">
          <div class="event-date-block">
            <div class="month">Jun</div>
            <div class="day">19</div>
            <div class="dow">Fri</div>
          </div>
          <div class="event-info">
            <div class="event-title">Juneteenth Celebration — Historic Stagville Free Tours</div>
            <div class="event-meta">
              <span>📍 Historic Stagville, Durham</span>
              <span>🕙 Times vary</span>
            </div>
            <div class="event-desc">In honor of Juneteenth (June 19, 2026), Historic Stagville offers free Emancipation Tours — a powerful, moving journey through stories of resilience, family, and freedom in 1865 NC. Educational and age-appropriate for older kids and families.</div>
            <div class="event-tags">
              <span class="etag etag-free">Free</span>
              <span class="etag etag-outdoor">Outdoor + Indoor</span>
            </div>
          </div>
        </div>

        <div class="event-card">
          <div class="event-date-block">
            <div class="month">Jun</div>
            <div class="day">19</div>
            <div class="dow">Fri</div>
          </div>
          <div class="event-info">
            <div class="event-title">Meet on Main — Downtown Wendell Free Concert</div>
            <div class="event-meta">
              <span>📍 Downtown Wendell, NC</span>
              <span>🕔 5:00–10:00 PM</span>
            </div>
            <div class="event-desc">Live music, a kids' zone, food truck rodeo, and beer/wine available. A lively outdoor evening for the whole family right here in our own backyard! Happens monthly — also on <strong>April 17, May 15, Sept 16.</strong></div>
            <div class="event-tags">
              <span class="etag etag-free">Free</span>
              <span class="etag etag-music">Live Music</span>
              <span class="etag etag-outdoor">Outdoor</span>
            </div>
          </div>
        </div>

        <div class="event-card">
          <div class="event-date-block">
            <div class="month">Jun</div>
            <div class="day">3</div>
            <div class="dow">Wed</div>
          </div>
          <div class="event-info">
            <div class="event-title">Summer Concert Series at Waverly Place — Cary</div>
            <div class="event-meta">
              <span>📍 Waverly Place, 575 New Waverly Pl, Cary</span>
              <span>🕔 5:30–8:30 PM · Wednesdays</span>
            </div>
            <div class="event-desc">Free Wednesday evening concerts in Cary every week June 3–24. Great midweek outing with kids — stroll the shops before the music starts. Also returns in September for the Sunset Concert Series.</div>
            <div class="event-tags">
              <span class="etag etag-free">Free</span>
              <span class="etag etag-music">Live Music</span>
            </div>
          </div>
        </div>

        <div class="event-card">
          <div class="event-date-block">
            <div class="month">Jun</div>
            <div class="day">5</div>
            <div class="dow">Thu</div>
          </div>
          <div class="event-info">
            <div class="event-title">Live After 5 — Downtown Raleigh Music Series</div>
            <div class="event-meta">
              <span>📍 Moore Square / Raleigh Union Station / Seaboard Station</span>
              <span>🕖 7:00 PM · Every other Thursday through Aug 13</span>
            </div>
            <div class="event-desc">Six free Thursday night concerts across downtown Raleigh featuring NC artists spanning Asheville jam, country, R&B, soul, and indie rock. Bring the whole family — open air and free!</div>
            <div class="event-tags">
              <span class="etag etag-free">Free</span>
              <span class="etag etag-outdoor">Outdoor</span>
              <span class="etag etag-music">Live Music</span>
            </div>
          </div>
        </div>

        <div class="event-card">
          <div class="event-date-block">
            <div class="month">Jun</div>
            <div class="day">1</div>
            <div class="dow">Mon</div>
          </div>
          <div class="event-info">
            <div class="event-title">Raleigh Summer Concert Series — Sundays at Pullen &amp; Fletcher Parks</div>
            <div class="event-meta">
              <span>📍 Fletcher Park &amp; Pullen Park, Raleigh</span>
              <span>🕕 6:00–8:00 PM · Select Sundays May 31–Aug 23</span>
            </div>
            <div class="event-desc">Free Sunday evening concerts at two beloved Raleigh parks. Pack a picnic, lay out a blanket, and enjoy live music in the park. Perfect for all ages including little ones.</div>
            <div class="event-tags">
              <span class="etag etag-free">Free</span>
              <span class="etag etag-outdoor">Outdoor</span>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- ══ SECTION 2: FREE WORKSHOPS ══ -->
    <div class="section">
      <div class="section-label">
        <div class="section-label-icon icon-sky">🎨</div>
        <h2 class="sky">Free &amp; Low-Cost Workshops</h2>
      </div>

      <div class="workshop-card">
        <div class="workshop-header">
          <div class="workshop-title">☀️ Wake County Library Summer Reading Program Kickoff</div>
          <span class="workshop-badge wb-free">Free</span>
        </div>
        <div class="workshop-meta">
          <span>📅 Starts June 7, 2026 — runs through Aug 15</span>
          <span>📍 All Wake County Library Branches</span>
        </div>
        <div class="workshop-desc">The beloved Summer Reading Program returns! All kids and teens are invited — any reading counts, including audiobooks, magazines, and even following a recipe. Branches offer weekly activities, STEAM programs, crafts, storytimes, and special events all summer long. <strong>No cost, no registration required at most branches.</strong> Visit <a href="https://library.wakegov.com" style="color:#1A5F8A">library.wakegov.com</a> for your local branch schedule.</div>
      </div>

      <div class="workshop-card">
        <div class="workshop-header">
          <div class="workshop-title">🌱 Garden Storytime at Raleigh City Farm</div>
          <span class="workshop-badge wb-low">$5/child</span>
        </div>
        <div class="workshop-meta">
          <span>📅 Saturday mornings, June</span>
          <span>📍 Raleigh City Farm</span>
        </div>
        <div class="workshop-desc">A magical outdoor storytime in the garden! Families hear picture books read aloud surrounded by growing vegetables and flowers. Kids learn about plants, soil, and where food comes from. Adults attend free — only $5 per child. Perfect for ages 2–8.</div>
      </div>

      <div class="workshop-card">
        <div class="workshop-header">
          <div class="workshop-title">🎨 Art Cart in the Park — Free Drop-In Art Making</div>
          <span class="workshop-badge wb-free">Free</span>
        </div>
        <div class="workshop-meta">
          <span>📅 Select dates, June 2026</span>
          <span>📍 Downtown Cary Park, 319 S. Academy St., Cary</span>
        </div>
        <div class="workshop-desc">Let your creativity bloom! The Art Cart rolls into Cary's gorgeous new park for free drop-in art workshops. Kids can explore drawing, painting, and mixed media with all materials provided. No sign-up needed — just show up and make something beautiful.</div>
      </div>

      <div class="workshop-card">
        <div class="workshop-header">
          <div class="workshop-title">🌿 Nature Education Programs — Durant Nature Preserve</div>
          <span class="workshop-badge wb-free">Free</span>
        </div>
        <div class="workshop-meta">
          <span>📅 Ongoing throughout June</span>
          <span>📍 Durant Nature Preserve, 8305 Camp Durant Rd, Raleigh</span>
        </div>
        <div class="workshop-desc">Raleigh's 237-acre Durant Nature Preserve offers free nature programs for families all summer. Explore hardwood and pine forests, spot wildlife at two lakes, and learn about local ecosystems. The preserve also has a sensory and nature play area. <strong>Inclusion Services available — call 919-996-2147.</strong></div>
      </div>

      <div class="workshop-card">
        <div class="workshop-header">
          <div class="workshop-title">🌽 Yates Mill Corn Grinding Tours &amp; Demos</div>
          <span class="workshop-badge wb-low">$3–$5</span>
        </div>
        <div class="workshop-meta">
          <span>📅 Every Saturday &amp; Sunday through November</span>
          <span>📍 Historic Yates Mill County Park, Raleigh</span>
        </div>
        <div class="workshop-desc">Watch NC's last operating water-powered gristmill grind corn the old-fashioned way. Costumed guides bring history to life along a beautiful 0.8-mile trail around Yates Mill Pond. Admission to the park is free — only $3–$5 for the mill tour. Finish with ice cream at NC State's Howling Cow across the road!</div>
      </div>

    </div>

    <!-- ══ SECTION 3: NATURE & ANIMALS ══ -->
    <div class="section">
      <div class="section-label">
        <div class="section-label-icon icon-green">🌳</div>
        <h2 class="green">Nature, Animals &amp; Outdoor Adventures</h2>
      </div>
      <ul class="checklist">
        <li>
          <div class="check-icon ci-green">🦋</div>
          <div><strong>Walnut Creek Wetland Park</strong> — Free guided wetland walks throughout June. Spot herons, turtles, dragonflies, and native wildflowers along peaceful boardwalk trails in southeast Raleigh. Great sensory experience for all ages.</div>
        </li>
        <li>
          <div class="check-icon ci-orange">🌸</div>
          <div><strong>JC Raulston Arboretum at NC State</strong> — One of the nation's top gardens, completely free to visit. June brings roses, summer blooms, and a beautiful shaded canopy perfect for family strolls. Look for families of rabbits near the pavilion!</div>
        </li>
        <li>
          <div class="check-icon ci-sky">🐟</div>
          <div><strong>Bass Lake Park, Holly Springs</strong> — Open daily 8am–sunset, free admission. Fish from the banks, explore the environmental education center, and hike forested trails. Kids love spotting great blue herons and beaver activity at the lake's edge.</div>
        </li>
        <li>
          <div class="check-icon ci-amber">🌻</div>
          <div><strong>Dorothea Dix Sunflower Field</strong> — Raleigh's beloved annual sunflower bloom is back! Free to visit, free to explore, and wonderful for photos and picnics. Check the Dix Park social media for exact bloom peak dates in June.</div>
        </li>
        <li>
          <div class="check-icon ci-purple">🦎</div>
          <div><strong>Umstead State Park Nature Hikes</strong> — Pack water and hit the trails! June mornings are the best time before the heat. The Sal's Branch trail (3.4 miles, easy) is ideal for families. Free parking at the Crabtree Creek entrance.</div>
        </li>
        <li>
          <div class="check-icon ci-green">🐦</div>
          <div><strong>Bands, Bites &amp; Boats — Bond Park Boathouse, Cary</strong> — Free first-Friday concert series (June 6!) on the lake. Bring lawn chairs, enjoy live music, grab food from a truck, and watch kayakers on the water. All ages welcome.</div>
        </li>
      </ul>
    </div>

    <!-- ══ SECTION 4: SPECIAL NEEDS SPOTLIGHT ══ -->
    <div class="section">
      <div class="section-label">
        <div class="section-label-icon icon-purple">♿</div>
        <h2 class="purple">Special Needs &amp; Inclusive Spotlight 💜</h2>
      </div>

      <div class="sn-spotlight">
        <div class="sn-title">🎵 Dance Class for Kids with Developmental Special Needs</div>
        <div class="sn-details">📍 Downtown Cary Park Nest Pavilion · 📅 Ongoing, June · 💰 Low cost</div>
        <div class="sn-desc">A joyful, inclusive dance class designed especially to empower young children with developmental special needs. Trained instructors create a safe, welcoming space where every child moves, expresses, and belongs. Contact Fun 4 Raleigh Kids for registration details.</div>
      </div>

      <div class="sn-spotlight">
        <div class="sn-title">♿ Durant Nature Preserve — Sensory &amp; Nature Play Area</div>
        <div class="sn-details">📍 Durant Nature Preserve, 8305 Camp Durant Rd · 📅 Open daily · 💰 Free</div>
        <div class="sn-desc">Durant features a dedicated sensory and nature play area designed for children with sensory differences. Loose parts, natural textures, water elements, and quiet spaces make this a wonderful summer destination. The park's Inclusion Services team can assist with accommodations — call 919-996-2147 or email ParksInclusion@raleighnc.gov.</div>
      </div>

      <div class="sn-spotlight">
        <div class="sn-title">🏅 Special Olympics Wake County — Summer Sports</div>
        <div class="sn-details">📍 Various Raleigh locations · 📅 Year-round including June · 💰 Free for athletes</div>
        <div class="sn-desc">Year-round training and competition for individuals with intellectual disabilities — completely free for athletes. Summer sports are in full swing! Visit specialolympicsnc.org to register or volunteer.</div>
      </div>

      <div class="sn-spotlight">
        <div class="sn-title">🌟 No-Cost Respite Saturday — SNCI</div>
        <div class="sn-details">📍 Wake County · 📅 Monthly Saturdays · 🕙 9:30 AM–12:30 PM · 💰 Free</div>
        <div class="sn-desc">Free respite for families of children with special needs ages 2–16. Every child is matched with their own caring "buddy" for crafts, games, movement, and fun. Caregivers get 3 hours of well-deserved rest. Visit snci-nc.org to register for June's session.</div>
      </div>

      <div class="sn-spotlight">
        <div class="sn-title">📚 Wake County Library — Programs for Kids with Disabilities</div>
        <div class="sn-details">📍 Countywide branches · 📅 All summer · 💰 Free</div>
        <div class="sn-desc">As part of the Summer Reading Program, many branches offer specially designed sessions for children with disabilities including adapted storytimes, sensory-friendly spaces, and one-on-one reading support. Call your local branch or visit wake.gov/libraries for details.</div>
      </div>

    </div>

    <!-- ══ SECTION 5: WEEKLY THINGS TO DO ══ -->
    <div class="section">
      <div class="section-label">
        <div class="section-label-icon icon-amber">📅</div>
        <h2 class="amber">Every Week in June — Always Free</h2>
      </div>
      <ul class="checklist">
        <li>
          <div class="check-icon ci-orange">📖</div>
          <div><strong>Mon, Tues, Fri — Storytime at Wake County Libraries</strong> · Baby, toddler, and family storytimes at all 23 branches. Check your nearest branch for exact times. Free, drop-in friendly.</div>
        </li>
        <li>
          <div class="check-icon ci-green">🥕</div>
          <div><strong>Every Wednesday — Pay What You Want Farmstand &amp; Wine &amp; Weeds</strong> at Raleigh City Farm. Connect to the earth, grab fresh produce, and let kids explore an urban farm. Free to attend.</div>
        </li>
        <li>
          <div class="check-icon ci-sky">🎪</div>
          <div><strong>Every Thursday 6:30–9PM — Live in the District Music</strong> at Park West Village, Morrisville. Free outdoor concert series every single Thursday all summer. Great for a relaxed family evening.</div>
        </li>
        <li>
          <div class="check-icon ci-amber">🏇</div>
          <div><strong>Weekends — StoryWalk® Trails</strong> at multiple Wake County parks. Follow pages of a children's picture book posted along a nature trail. Find locations at wake.gov/parks. Free &amp; family-loved.</div>
        </li>
        <li>
          <div class="check-icon ci-purple">🎨</div>
          <div><strong>Every Sat, Sun, Mon morning — Artspace Story Time</strong> · Children's booksellers read favorite picture books at Artspace Gallery, downtown Raleigh. Free. A lovely little tradition.</div>
        </li>
      </ul>
    </div>

    <!-- ══ KIND CORNER ══ -->
    <div class="section">
      <div class="section-label">
        <div class="section-label-icon icon-orange">💛</div>
        <h2 class="orange">The Kind Corner</h2>
      </div>
      <div class="kind-corner">
        <span class="kc-emoji">🌿🐾💛</span>
        <h3>This Month's Kindness Challenge for Families</h3>
        <p>This June, we challenge every Acorn City Kids family to pick up one piece of litter on your next park visit, say hello to a family you've never met on the trail, and if you see a child struggling — be the adult who steps in with a smile. Small acts of kindness ripple outward in big ways. And when your kids see you doing it, they learn it too.</p>
        <p style="margin-top:10px">Animals need our kindness too — remind little ones to observe wildlife from a distance, never feed wildlife human food, and always leave natural spaces better than you found them. 🌱</p>
        <span class="kc-quote">"Be kind whenever possible. It is always possible." — Dalai Lama</span>
      </div>
    </div>

    <!-- APP CTA BANNER -->
    <a class="app-cta" href="https://acorncitykids.com" target="_blank" rel="noopener" aria-label="Open the Acorn City Kids activity finder app">
      <div class="app-cta-icon">🌰</div>
      <div class="app-cta-text">
        <h3>Explore 28+ Activities in Our Free App</h3>
        <p>Search parks, museums, inclusive programs, and more — filter by cost, category, or special needs. Updated regularly for Raleigh-area families.</p>
      </div>
      <div class="app-cta-arrow">→</div>
    </a>

  </div><!-- /.nl-body -->

  <!-- FOOTER -->
  <div class="nl-footer">
    <div class="footer-brand">🌰 Acorn City Kids</div>
    <p>Your guide to free &amp; affordable family fun in the greater Raleigh, NC area</p>
    <p style="margin-top:10px">
      <a href="https://acorncitykids.com">🌐 AcornCityKids.com</a>
      &nbsp;·&nbsp;
      <a href="https://acorncitykids.com">📱 Open the Activity Finder App</a>
      &nbsp;·&nbsp;
      <a href="mailto:acorncitykids@gmail.com">✉️ Email Us</a>
    </p>
    <p style="margin-top:8px">
      Serving Raleigh · Cary · Wake Forest · Holly Springs · Morrisville &amp; Beyond
    </p>
    <p class="unsub">You're receiving this because you subscribed at AcornCityKids.com · <a href="#">Unsubscribe</a></p>
  </div>

  <!-- PRINT / SHARE BAR -->
  <div class="share-bar">
    <button class="share-btn btn-print" onclick="window.print()">🖨️ Print Newsletter</button>
    <button class="share-btn btn-copy" onclick="copyLink()">🔗 Copy Link to Share</button>
    <a class="share-btn" href="https://acorncitykids.com" target="_blank" style="background:#C4621D;color:#fff;text-decoration:none;">🌰 Open the App</a>
  </div>

</div><!-- /.wrapper -->

<script>
function copyLink() {
  navigator.clipboard.writeText(window.location.href).then(() => {
    const btn = document.querySelector('.btn-copy');
    btn.textContent = '✅ Link Copied!';
    setTimeout(() => { btn.innerHTML = '🔗 Copy Link to Share'; }, 2500);
  });
}
</script>
</body>
</html>
