---
permalink: /program/
title: "Program - SQAI 2026"
author_profile: true
---

<style>
/* Main Program Page Styles */
.program-container {
  margin-bottom: 1rem;
}

.program-header-image {
  width: 100%;
  max-width: 100%;
  border-radius: 8px;
  margin-bottom: 0.3rem;
}

.image-caption {
  text-align: center;
  font-size: 0.8rem;
  color: #666;
  margin-bottom: 1rem;
}

.program-notice {
  background-color: transparent;
  border-left: 3px solid #98d4dc;
  padding: 0.7rem;
  margin: 0.8rem 0;
  border-radius: 0;
}

/* Timeline Design */
.timeline-container {
  background: transparent;
  border-radius: 0;
  padding: 0.5rem 0;
  margin-bottom: 1rem;
}

.timeline-header {
  border-bottom: 1px solid #f0f0f0;
  padding-bottom: 0.5rem;
  margin-bottom: 0.8rem;
  color: #333;
  font-weight: 600;
}

.event-card {
  display: flex;
  border-left: 3px solid;
  padding: 0.6rem 0.8rem;
  margin-bottom: 0.7rem;
  background: transparent;
  border-radius: 0 6px 6px 0;
}

.taipei-event { border-color: #98d4dc; }
.dc-event { border-color: #98d4dc; }
.virtual-event { border-color: #98d4dc; }

.event-details {
  flex-grow: 1;
}

.event-location {
  display: inline-block;
  font-size: 0.8rem;
  font-weight: 600;
  padding: 0.15rem 0.5rem;
  border-radius: 999px;
  margin-bottom: 0.3rem;
}

.location-taipei { background-color: transparent; border: 1px solid #98d4dc; color: #98d4dc; }
.location-dc { background-color: transparent; border: 1px solid #98d4dc; color: #98d4dc; }
.location-virtual { background-color: transparent; border: 1px solid #98d4dc; color: #98d4dc; }

.event-time {
  font-size: 0.85rem;
  color: #555;
}

.event-name {
  font-weight: 500;
  margin-bottom: 0.2rem;
}

/* Removed navigation button styles in favor of text links */

/* Program Sections */
.program-section {
  margin: 1.5rem 0;
  padding: 0.8rem 0;
  background: transparent;
  border-radius: 0;
}

.section-title {
  position: relative;
  padding-bottom: 0.5rem;
  margin-bottom: 1rem;
  font-size: 1.4rem;
  font-weight: 700;
  color: #222;
}

.section-title:after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100px;
  height: 3px;
  background-color: #98d4dc;
  border-radius: 3px;
}

.program-feature {
  display: flex;
  align-items: flex-start;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #f0f0f0;
}

.program-feature:last-child {
  margin-bottom: 0;
  padding-bottom: 0;
  border-bottom: none;
}

.feature-icon {
  flex-shrink: 0;
  width: 40px;
  height: 40px;
  margin-right: 0.8rem;
  background: transparent;
  border: 1px solid #98d4dc;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.3rem;
  color: #98d4dc;
}

.feature-content {
  flex-grow: 1;
}

.feature-title {
  font-size: 1.1rem;
  font-weight: 500;
  margin-bottom: 0.3rem;
  color: #333;
}

.feature-description {
  color: #555;
  line-height: 1.4;
  font-size: 0.95rem;
}

.location-tag {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.3rem 0.7rem;
  font-size: 0.85rem;
  font-weight: 600;
  border-radius: 5px;
  margin-left: 0.6rem;
  vertical-align: middle;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.location-taipei-tag { 
  background-color: #2196f3; 
  background: linear-gradient(135deg, #2196f3, #1976d2);
  color: white; 
  text-shadow: 0 1px 1px rgba(0,0,0,0.3);
  border: none;
}
.location-dc-tag { 
  background-color: #00bcd4; 
  background: linear-gradient(135deg, #00bcd4, #0097a7);
  color: white; 
  text-shadow: 0 1px 1px rgba(0,0,0,0.3);
  border: none;
}
.location-virtual-tag { 
  background-color: #009688; 
  background: linear-gradient(135deg, #009688, #00796b);
  color: white; 
  text-shadow: 0 1px 1px rgba(0,0,0,0.3);
  border: none;
}

/* Responsive */
@media (max-width: 768px) {
  .program-feature {
    flex-direction: column;
  }
  
  .feature-icon {
    margin-bottom: 1rem;
  }
}

/* Add space above iframe */
.schedule-iframe-container {
  margin-top: 0.8rem;
}

/* Section Separator */
.section-separator {
  height: 1px;
  background: linear-gradient(to right, transparent, #98d4dc, transparent);
  margin: 1.5rem 0;
  border: none;
}
</style>

<div class="program-container">
  <img src="/images/quantumlaser.jpg" alt="Quantum Laser" class="program-header-image">
  <div class="image-caption">
    Source: <a href="https://www.quantum.gov/quantum-image-gallery/" target="_blank">quantum.gov</a> - Laser beam passes through a vapor cell of rubidium atoms to measure microwave fields
  </div>

  <div class="program-notice">
    <strong>Note:</strong> The program is subject to change. Final schedule will be announced by 12/31/2025.
  </div>

  <!-- Program Navigation -->
  <div style="background-color: #f5f5f5; padding: 10px; margin-bottom: 20px; text-align: center;">
    <strong>Navigate the Program<br></strong> 
    <a href="#sqai-a">🎓 SQAI-A</a> | 
    <a href="#sqai-b">💼 SQAI-B</a> | 
    <a href="#sqai-c">🏛️ SQAI-C</a> | 
    <a href="#sqai-d">🌐 SQAI-D</a>
  </div>

  <hr class="section-separator">

  <!-- SQAI-A Academic Conference -->
  <div id="sqai-a" class="program-section">
    <h2 class="section-title">SQAI-A (Academic Conference) <span class="location-tag location-taipei-tag">Taipei</span></h2>
    
    <p style="margin-bottom:0.8rem;">
      The academic conference will be held in Taipei on June 26-27, 2026 (UTC+8). Our 2026 target is 50 outstanding research papers, featuring keynote speeches, technical presentations, demos, and poster sessions.
    </p>
    
    <div class="program-feature">
      <div class="feature-icon">🗓️</div>
      <div class="feature-content">
        <h3 class="feature-title">Conference Schedule</h3>
        <p class="feature-description">
          View our complete academic conference schedule for all events and sessions. This schedule is regularly updated.
        </p>
        <div class="schedule-iframe-container" style="overflow-x: auto; -webkit-overflow-scrolling: touch; width: 100%;">
          <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSokOukw8E-OhH-E1xESJ0ooLVc2bcdySVJRVE9f1knAyAXZ8CXudRQB1JZiKrf0l8PDHFSltB0zzya/pubhtml?gid=0&single=true&widget=true" width="100%" height="500" style="border:none;max-width:100%;display:block;"></iframe>
        </div>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">🎤</div>
      <div class="feature-content">
        <h3 class="feature-title">Keynote Speakers</h3>
        <p class="feature-description">
          Distinguished leaders from academia and industry will present cutting-edge research and insights on quantum computing, artificial intelligence, and their intersection. Each keynote is designed to inspire and inform attendees about the latest advancements and future directions in these fields.
        </p>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">📝</div>
      <div class="feature-content">
        <h3 class="feature-title">Technical Sessions</h3>
        <p class="feature-description">
          Peer-reviewed research papers on quantum algorithms, quantum-enhanced AI, optimization, and hybrid architectures. Sessions include Q&A and are designed for researchers and advanced practitioners. All accepted papers will be presented in either oral or poster formats.
        </p>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">📊</div>
      <div class="feature-content">
        <h3 class="feature-title">Poster Sessions</h3>
        <p class="feature-description">
          Interactive sessions showcasing emerging research and innovative projects. Presenters will be available to discuss their work in detail, providing an excellent opportunity for in-depth technical discussions and feedback.
        </p>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">☕</div>
      <div class="feature-content">
        <h3 class="feature-title">Networking Breaks</h3>
        <p class="feature-description">
          Catered lunches and coffee breaks provide informal networking opportunities throughout the conference. These breaks are strategically scheduled to encourage discussions and collaborations among attendees.
        </p>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">🏆</div>
      <div class="feature-content">
        <h3 class="feature-title">Best Paper Award Ceremony</h3>
        <p class="feature-description">
          Our closing ceremony brings both communities together at the conclusion of SQAI-A.<br>
          Winners will be honored and invited to give short remarks or lightning talks. The ceremony will recognize outstanding contributions to the field of quantum AI and celebrate the achievements of researchers from around the world. The ceremony will be held in person in Taipei and simultaneously streamed for virtual participants.
        </p>
      </div>
    </div>
  </div>

  <hr class="section-separator">

  <!-- SQAI-B Business Expo -->
  <div id="sqai-b" class="program-section">
    <h2 class="section-title">SQAI-B (Business Expo) <span class="location-tag location-taipei-tag">Taipei</span></h2>
    
    <p style="margin-bottom:0.8rem;">
      The Business Expo will be held in Taipei on June 28, 2026 (UTC+8), 10:00-18:00, following SQAI-A. SQAI's sponsors will be given access to a booth, and exhibitors will be allowed to roam around to talk to the company or institute of their choosing.
    </p>
    
    <div class="program-feature">
      <div class="feature-icon">🖥️</div>
      <div class="feature-content">
        <h3 class="feature-title">Tech Business Exhibition & Demos</h3>
        <p class="feature-description">
          A showcase of cutting-edge quantum and AI technologies from leading companies and startups. Attendees can experience hands-on demonstrations of the latest tools, platforms, and applications at the intersection of quantum computing and artificial intelligence.
        </p>
      </div>
    </div>
    
    <div class="program-feature">
      <div class="feature-icon">💡</div>
      <div class="feature-content">
        <h3 class="feature-title">Innovation Showcase</h3>
        <p class="feature-description">
          Selected companies and research institutes will present their latest innovations in quantum computing and AI technologies. This showcase highlights practical applications and commercial solutions that are shaping the future of these fields.
        </p>
      </div>
    </div>
    
    <div class="program-feature">
      <div class="feature-icon">🤝</div>
      <div class="feature-content">
        <h3 class="feature-title">Industry Networking</h3>
        <p class="feature-description">
          Dedicated time for attendees to connect with industry leaders, investors, and potential collaborators. This structured networking opportunity aims to foster business relationships and explore potential partnerships in the quantum AI ecosystem.
        </p>
      </div>
    </div>
  </div>

  <hr class="section-separator">

  <!-- SQAI-C Capitol Summit -->
  <div id="sqai-c" class="program-section">
    <h2 class="section-title">SQAI-C (Capitol Summit) <span class="location-tag location-dc-tag">DC</span></h2>
    
    <div class="america250-special">
      <div style="display: flex; align-items: center; margin-bottom: 8px;">
        <i class="fas fa-flag-usa" style="font-size: 1.5em; margin-right: 10px;"></i>
        <h3 style="margin: 0; font-size: 1.3em; font-weight: bold;">America's 250th Anniversary</h3>
      </div>
      <p style="margin: 0; line-height: 1.4;">
        The 2026 Capitol Summit proudly coincides with America's semiquincentennial celebration. Join us in honoring 250 years of American innovation while shaping the next 250 years through the lens of quantum technology.
      </p>
    </div>
    
    <p style="margin-bottom:0.8rem;">
      The Capitol Summit will be held in Washington, D.C. on June 27, 2026 (UTC−4), 08:30-16:30, starting immediately after SQAI-A. SQAI-C will feature keynote speeches and discussion panels from civic and corporate leaders, along with a networking event.
    </p>
    
    <div class="program-feature">
      <div class="feature-icon">🗓️</div>
      <div class="feature-content">
        <h3 class="feature-title">Capitol Summit Schedule</h3>
        <p class="feature-description">
          View the detailed schedule for the SQAI-C Capitol Summit in Washington, D.C.
        </p>
        <div class="schedule-iframe-container">
          <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSokOukw8E-OhH-E1xESJ0ooLVc2bcdySVJRVE9f1knAyAXZ8CXudRQB1JZiKrf0l8PDHFSltB0zzya/pubhtml?gid=1931629340&single=true" width="100%" height="500" style="border:none;overflow:auto;"></iframe>
        </div>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">🎤</div>
      <div class="feature-content">
        <h3 class="feature-title">Keynote Speakers</h3>
        <p class="feature-description">
          Distinguished leaders from government agencies and industry will present insights on quantum policy, national initiatives, and strategic directions. These keynotes will highlight the governmental perspective on quantum computing and AI integration.
        </p>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">🤝</div>
      <div class="feature-content">
        <h3 class="feature-title">"Quantum Meets AI" Networking Event</h3>
        <p class="feature-description">
          A parallel networking session to the Taipei event, designed specifically for Washington, D.C. attendees. This event focuses on connecting policy makers, government representatives, industry leaders, and researchers in the U.S. capital.
        </p>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">🏛️</div>
      <div class="feature-content">
        <h3 class="feature-title">Government & Industry Panel</h3>
        <p class="feature-description">
          A regionally focused panel with public institutions, startups, and major tech companies. Topics include policy, commercialization, and international collaboration. Held live in DC and streamed to Taipei.
        </p>
      </div>
    </div>

    <div class="program-feature">
      <div class="feature-icon">☕</div>
      <div class="feature-content">
        <h3 class="feature-title">Networking Breaks</h3>
        <p class="feature-description">
          Catered lunches and coffee breaks provide informal networking opportunities. These breaks are designed to facilitate discussions between government officials, industry representatives, and researchers.
        </p>
      </div>
    </div>
  </div>

  <hr class="section-separator">

  <!-- SQAI-D Digital Access -->
  <div id="sqai-d" class="program-section">
    <h2 class="section-title">SQAI-D (Digital Access) <span class="location-tag location-virtual-tag">Virtual</span></h2>
    
    <p style="margin-bottom:0.8rem;">
      Digital Access will be provided for all registrants, including both Zoom sessions and recordings for SQAI-A, SQAI-B, and SQAI-C throughout the conference period.
    </p>

    <div class="program-feature">
      <div class="feature-icon">🌐</div>
      <div class="feature-content">
        <h3 class="feature-title">Virtual Participation</h3>
        <p class="feature-description">
          Select sessions from SQAI-A, SQAI-B, and SQAI-C will be streamed live for virtual attendees. This hybrid format ensures global accessibility and participation in SQAI 2026, regardless of physical location.
        </p>
      </div>
    </div>
    
    <div class="program-feature">
      <div class="feature-icon">🎥</div>
      <div class="feature-content">
        <h3 class="feature-title">Session Recordings</h3>
        <p class="feature-description">
          All keynote presentations, technical sessions, and panel discussions will be recorded and made available to registered participants. This allows attendees to catch up on sessions they may have missed or to revisit content of particular interest.
        </p>
      </div>
    </div>
    
    <div class="program-feature">
      <div class="feature-icon">💬</div>
      <div class="feature-content">
        <h3 class="feature-title">Virtual Q&A</h3>
        <p class="feature-description">
          Interactive Q&A sessions enable virtual participants to engage with presenters and panelists in real-time. Questions can be submitted through our conference platform and will be addressed during live sessions.
        </p>
      </div>
    </div>
  </div>
</div>

<!-- You can add a detailed schedule, speaker list, or session breakdown below -->
