<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>MediCare – Medicine Reminder App | Modern Healthcare UI/UX Design Project</title>
  <meta name="description" content="MediCare is a modern, clean and professional mobile app UI/UX design project for medication reminders, adherence tracking, and schedule management.">

  <!-- Google Fonts: Plus Jakarta Sans & Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Plus+Jakarta+Sans:wght@500;600;700;800&display=swap" rel="stylesheet">

  <!-- App Stylesheet -->
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

  <!-- Presentation Studio Shell -->
  <div class="presentation-container">

    <!-- Left Showcase Sidebar (Portfolio & Academic Context) -->
    <aside class="showcase-sidebar">
      <div>
        <div style="display: inline-flex; align-items: center; gap: 8px; background: rgba(13, 148, 136, 0.16); border: 1px solid rgba(20, 184, 166, 0.35); padding: 5px 12px; border-radius: 999px; font-size: 11.5px; font-weight: 700; color: #5EEAD4; margin-bottom: 12px;">
          <span>🩺 Healthcare UI/UX Internship Project</span>
        </div>
        <h1 style="font-size: 24px; font-weight: 800; color: #FFFFFF; line-height: 1.2; letter-spacing: -0.02em;">
          MediCare
        </h1>
        <p style="font-size: 13.5px; color: #94A3B8; margin-top: 4px; font-weight: 500;">
          Medicine Reminder &amp; Schedule App
        </p>
      </div>

      <!-- Quick Screen Navigator Pills -->
      <div>
        <div style="font-size: 11.5px; font-weight: 700; text-transform: uppercase; color: #64748B; letter-spacing: 0.05em; margin-bottom: 10px;">
          Interactive Screens (8/8)
        </div>
        <div style="display: flex; flex-direction: column; gap: 6px;">
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.navigateTo('screen-splash')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">01</span> Splash Screen
          </button>
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.navigateTo('screen-login')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">02</span> Login / Sign Up
          </button>
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.navigateTo('screen-home')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">03</span> Home Dashboard
          </button>
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.navigateTo('screen-add-medicine')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">04</span> Add Medicine Screen
          </button>
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.navigateTo('screen-schedule')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">05</span> Medicine Schedule
          </button>
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.openMedicineDetails('med-4')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">06</span> Medicine Details
          </button>
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.triggerActiveReminder('med-4')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">07</span> Reminder Alarm Screen
          </button>
          <button class="tool-btn" style="width: 100%; justify-content: flex-start; padding: 8px 12px; text-align: left;" onclick="window.medicare.navigateTo('screen-profile')">
            <span style="width: 22px; font-size: 11px; color: #2DD4BF;">08</span> Patient Profile
          </button>
        </div>
      </div>

      <!-- Quick Feature Matrix -->
      <div style="background: rgba(255, 255, 255, 0.03); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 16px; padding: 14px;">
        <div style="font-size: 11.5px; font-weight: 700; color: #5EEAD4; margin-bottom: 8px; text-transform: uppercase;">
          Key UX Features
        </div>
        <ul style="font-size: 12px; color: #94A3B8; padding-left: 16px; line-height: 1.6;">
          <li>Morning / Afternoon / Night time slots</li>
          <li>1-Tap 'Taken' checkbox with audio chime</li>
          <li>Active alarm reminder with Snooze (15m)</li>
          <li>Refill inventory tracker &amp; stock alert</li>
          <li>Emergency medical profile &amp; allergy tags</li>
          <li>Dark / Light clinical theme toggle</li>
        </ul>
      </div>

      <!-- Fullscreen Mode & Standalone Actions -->
      <div style="display: flex; flex-direction: column; gap: 8px;">
        <button class="tool-btn" style="width: 100%; justify-content: center; background: rgba(20, 184, 166, 0.15); border: 1px solid rgba(20, 184, 166, 0.35); color: #5EEAD4; padding: 10px; font-weight: 700;" onclick="window.medicare.toggleFullscreen()">
          <span>⛶</span> Fullscreen Mode
        </button>
        <a href="app.html" target="_blank" class="tool-btn" style="width: 100%; justify-content: center; background: rgba(255, 255, 255, 0.05); border: 1px solid rgba(255, 255, 255, 0.12); color: #FFFFFF; padding: 8px; text-decoration: none;">
          <span>↗</span> Open Standalone App
        </a>
      </div>

      <!-- Portfolio Documentation Trigger -->
      <div style="margin-top: auto; display: flex; flex-direction: column; gap: 8px;">
        <button class="btn-primary" onclick="window.medicare.openCaseStudyModal()" style="font-size: 13.5px; padding: 12px;">
          📖 View UI/UX Documentation
        </button>
        <div style="font-size: 11px; color: #64748B; text-align: center; margin-top: 4px;">
          Patient: Sarah Jenkins (Age 46) &bull; MediCare v2.0
        </div>
      </div>
    </aside>

    <!-- Center Showcase Canvas -->
    <main class="showcase-stage">

      <!-- Floating Device Controls Toolbar -->
      <div class="stage-toolbar">
        <button id="btn-mode-iphone" class="tool-btn tool-device-btn active" onclick="window.medicare.setDeviceMode('iphone')">
          iPhone 16 Pro
        </button>
        <button id="btn-mode-pixel" class="tool-btn tool-device-btn" onclick="window.medicare.setDeviceMode('pixel')">
          Pixel 9
        </button>
        <button id="btn-mode-fullscreen" class="tool-btn tool-device-btn" onclick="window.medicare.toggleFullscreen()">
          <span>⛶</span> Fullscreen
        </button>
        <button id="btn-exit-fullscreen" class="tool-btn exit-fullscreen-badge" onclick="window.medicare.exitFullscreen()" style="background: linear-gradient(135deg, #EF4444, #F43F5E); color: #FFF; font-weight: 700;">
          ✕ Exit Fullscreen
        </button>
        <div style="width: 1px; height: 18px; background: rgba(255, 255, 255, 0.15);"></div>
        <button class="tool-btn" onclick="window.medicare.triggerActiveReminder('med-4')" title="Simulate Alarm Alarm">
          🔔 Test Alarm
        </button>
        <button class="tool-btn" onclick="window.medicare.toggleTheme()" title="Toggle Dark/Light Mode">
          <span id="theme-toggle-icon">🌙</span> Theme
        </button>
        <button class="tool-btn" onclick="window.medicare.toggleSound()" title="Toggle Sound">
          Sound
        </button>
      </div>

      <!-- Smartphone Device Mockup -->
      <div class="device-wrapper">
        <div id="device-frame" class="device-frame">
          <div id="device-screen" class="device-screen" data-theme="light">

            <!-- iOS Dynamic Island -->
            <div id="dynamic-island" class="dynamic-island" onclick="window.medicare.pulseDynamicIsland()">
              <div class="island-camera"></div>
              <div class="island-content-collapsed">
                <span style="color: #14B8A6;">&bull;</span>
                <span>MediCare</span>
              </div>
              <div class="island-content-expanded">
                <div style="display: flex; align-items: center; gap: 8px;">
                  <span style="width: 10px; height: 10px; border-radius: 50%; background: #14B8A6; animation: medLivePulse 1.5s infinite;"></span>
                  <span style="font-size: 11px; font-weight: 700;">Metformin 500mg</span>
                </div>
                <span style="font-size: 11px; color: #5EEAD4;">Due 01:30 PM</span>
              </div>
            </div>

            <!-- iOS Status Bar -->
            <div class="status-bar">
              <span id="status-bar-time">09:41</span>
              <div class="status-bar-icons">
                <svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor">
                  <rect x="2" y="16" width="3" height="6" rx="1"/><rect x="7" y="12" width="3" height="10" rx="1"/><rect x="12" y="8" width="3" height="14" rx="1"/><rect x="17" y="4" width="3" height="18" rx="1"/>
                </svg>
                <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round">
                  <path d="M12 20h.01"/><path d="M8.5 16.429a5 5 0 0 1 7 0"/><path d="M5 12.859a10 10 0 0 1 14 0"/><path d="M1.5 9.288a15 15 0 0 1 21 0"/>
                </svg>
                <svg width="20" height="12" viewBox="0 0 24 12" fill="none" stroke="currentColor" stroke-width="2" rx="3">
                  <rect x="1" y="1" width="19" height="10" rx="2.5"/><rect x="3" y="3" width="12" height="6" rx="1" fill="currentColor"/><path d="M22 4v4" stroke-linecap="round"/>
                </svg>
              </div>
            </div>

            <!-- Toast Container -->
            <div id="toast-container" class="toast-container"></div>

            <!-- Confetti Canvas -->
            <canvas id="confetti-canvas"></canvas>

            <!-- Screens Viewport -->
            <div class="screens-viewport">

              <!-- ==========================================================
                   SCREEN 1: SPLASH SCREEN
                   ========================================================== -->
              <section id="screen-splash" class="app-screen active">
                <div style="flex: 1; display: flex; flex-direction: column; align-items: center; justify-content: center; width: 100%;">
                  <!-- Logo Emblem -->
                  <div class="splash-emblem">
                    <svg width="58" height="58" viewBox="0 0 24 24" fill="none" stroke="#FFFFFF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                      <path d="m10.5 20.5 10-10a4.95 4.95 0 1 0-7-7l-10 10a4.95 4.95 0 1 0 7 7Z"/>
                      <path d="m8.5 8.5 7 7"/>
                    </svg>
                  </div>
                  <h1 style="font-size: 34px; font-weight: 800; letter-spacing: -0.03em; color: #FFFFFF; margin-bottom: 6px;">
                    MediCare
                  </h1>
                  <p style="font-size: 15px; color: #5EEAD4; font-weight: 600; letter-spacing: 0.02em;">
                    Your Health, On Time
                  </p>

                  <div class="splash-progress-bar">
                    <div class="splash-progress-fill"></div>
                  </div>
                </div>

                <div style="width: 100%; margin-top: auto;">
                  <button class="btn-primary" onclick="window.medicare.navigateTo('screen-login')" style="background: rgba(255, 255, 255, 0.15); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.25); box-shadow: none;">
                    Continue to Login &rarr;
                  </button>
                  <p style="font-size: 11.5px; color: #64748B; margin-top: 12px; text-align: center;">
                    Healthcare UI/UX Prototype &bull; v2.0
                  </p>
                </div>
              </section>

              <!-- ==========================================================
                   SCREEN 2: LOGIN / SIGN UP SCREEN
                   ========================================================== -->
              <section id="screen-login" class="app-screen">
                <div class="screen-content" style="justify-content: center; min-height: 100%; padding-top: 20px;">
                  <div style="text-align: center; margin-bottom: 24px;">
                    <div style="width: 60px; height: 60px; border-radius: 18px; background: linear-gradient(135deg, var(--primary-600), var(--secondary-500)); display: inline-flex; align-items: center; justify-content: center; color: #FFFFFF; box-shadow: var(--shadow-md); margin-bottom: 12px;">
                      <svg width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="m10.5 20.5 10-10a4.95 4.95 0 1 0-7-7l-10 10a4.95 4.95 0 1 0 7 7Z"/>
                        <path d="m8.5 8.5 7 7"/>
                      </svg>
                    </div>
                    <h2 class="screen-title" style="font-size: 26px;">Welcome to MediCare</h2>
                    <p class="screen-subtitle">Your personal daily medication companion</p>
                  </div>

                  <!-- 1-Click Auto-Fill Demo Shortcut -->
                  <div style="background: rgba(13, 148, 136, 0.08); border: 1px dashed var(--primary-300); border-radius: var(--radius-md); padding: 12px; font-size: 12px; color: var(--primary-800); display: flex; align-items: center; justify-content: space-between; margin-bottom: 20px;">
                    <div>
                      <strong>Demo User:</strong> Sarah Jenkins (Age 46)
                    </div>
                    <button class="tool-btn" style="padding: 4px 10px; font-size: 11px; background: var(--primary-600); color: #fff;" onclick="window.medicare.fillDemoUser()">
                      Auto-Fill
                    </button>
                  </div>

                  <!-- Auth Form -->
                  <form onsubmit="window.medicare.handleAuthSubmit(event)">
                    <div class="form-group">
                      <label class="form-label" for="auth-email">Email or Phone Number</label>
                      <div class="input-container">
                        <span class="input-icon-left">
                          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/>
                          </svg>
                        </span>
                        <input type="text" id="auth-email" class="form-input" placeholder="e.g. sarah.jenkins@medicare.app" value="sarah.jenkins@medicare.app" required>
                      </div>
                    </div>

                    <div class="form-group">
                      <label class="form-label" for="auth-password">Password</label>
                      <div class="input-container">
                        <span class="input-icon-left">
                          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <rect width="18" height="11" x="3" y="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/>
                          </svg>
                        </span>
                        <input type="password" id="auth-password" class="form-input" placeholder="••••••••••••" value="medicare2026" required>
                        <button type="button" class="input-icon-right" onclick="window.medicare.togglePasswordVisibility()">
                          <span id="pass-toggle-icon">
                            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M2 12s3-7 10-7 10 7 10 7-3 7-10 7-10-7-10-7Z"/><circle cx="12" cy="12" r="3"/></svg>
                          </span>
                        </button>
                      </div>
                    </div>

                    <div style="display: flex; justify-content: flex-end; margin-bottom: 20px;">
                      <a href="javascript:void(0)" onclick="document.getElementById('forgot-password-sheet').classList.add('open');" style="font-size: 12.5px; font-weight: 600; color: var(--primary-600); text-decoration: none;">
                        Forgot Password?
                      </a>
                    </div>

                    <button type="submit" id="auth-submit-btn" class="btn-primary" style="margin-bottom: 16px;">
                      Sign In &rarr;
                    </button>
                  </form>

                  <div style="text-align: center; font-size: 13px; color: var(--text-secondary); margin-top: 10px;">
                    Don't have an account?
                    <a href="javascript:void(0)" onclick="window.medicare.showToast('Sign up registration opened. Please enter your email.');" style="color: var(--primary-600); font-weight: 700; text-decoration: none; margin-left: 4px;">
                      Sign Up
                    </a>
                  </div>
                </div>
              </section>

              <!-- ==========================================================
                   SCREEN 3: HOME SCREEN
                   ========================================================== -->
              <section id="screen-home" class="app-screen">
                <div class="screen-content">
                  <!-- Header: Greeting, Date, Profile Avatar -->
                  <div class="app-header">
                    <div>
                      <div id="home-greeting-text" style="font-size: 22px; font-weight: 800; color: var(--text-main); letter-spacing: -0.02em;">
                        Good Morning, Sarah! ☀️
                      </div>
                      <div id="home-current-date" style="font-size: 13px; color: var(--text-secondary); font-weight: 600; margin-top: 2px;">
                        Wednesday, Oct 1
                      </div>
                    </div>
                    <div style="display: flex; align-items: center; gap: 10px;">
                      <button class="icon-btn" onclick="window.medicare.triggerActiveReminder('med-4')" title="Reminder Alarms">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 8a6 6 0 0 1 12 0c0 7 3 9 3 9H3s3-2 3-9"/><path d="M10.3 21a1.94 1.94 0 0 0 3.4 0"/></svg>
                        <span class="nav-badge-dot"></span>
                      </button>
                      <div onclick="window.medicare.navigateTo('screen-profile')" style="width: 44px; height: 44px; border-radius: 50%; background: linear-gradient(135deg, var(--primary-600), var(--secondary-500)); padding: 2px; cursor: pointer;">
                        <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=240&q=80" alt="Avatar" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;">
                      </div>
                    </div>
                  </div>

                  <!-- 1. Quick Health Summary Widget -->
                  <div style="margin-bottom: 20px;">
                    <div id="home-health-summary-widget" class="app-card">
                      <!-- Rendered by app.js -->
                    </div>
                  </div>

                  <!-- 2. Next Medicine Reminder Card -->
                  <div style="margin-bottom: 20px;">
                    <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px;">
                      <span style="font-size: 13px; font-weight: 700; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 0.04em;">Next Reminder</span>
                      <a href="javascript:void(0)" onclick="window.medicare.navigateTo('screen-schedule')" style="font-size: 12px; font-weight: 700; color: var(--primary-600); text-decoration: none;">Full Schedule</a>
                    </div>
                    <div id="home-next-reminder-card" class="app-card card-interactive next-med-card" onclick="window.medicare.navigateTo('screen-schedule')">
                      <!-- Rendered by app.js -->
                    </div>
                  </div>

                  <!-- 3. Today's Medicine Schedule Preview -->
                  <div style="margin-bottom: 10px;">
                    <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px;">
                      <span style="font-size: 13px; font-weight: 700; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 0.04em;">Today's Medicines</span>
                      <a href="javascript:void(0)" onclick="window.medicare.navigateTo('screen-schedule')" style="font-size: 12px; font-weight: 700; color: var(--primary-600); text-decoration: none;">View All (7)</a>
                    </div>
                    <div id="home-today-schedule-list">
                      <!-- Rendered by app.js -->
                    </div>
                  </div>
                </div>
              </section>

              <!-- ==========================================================
                   SCREEN 4: ADD MEDICINE SCREEN
                   ========================================================== -->
              <section id="screen-add-medicine" class="app-screen">
                <div class="screen-content">
                  <div class="app-header">
                    <div>
                      <h2 class="screen-title">Add Medicine</h2>
                      <p class="screen-subtitle">Create a new medication reminder</p>
                    </div>
                    <button class="icon-btn" onclick="window.medicare.navigateBack()">
                      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6 6 18M6 6l12 12"/></svg>
                    </button>
                  </div>

                  <!-- Quick Presets -->
                  <div style="margin-bottom: 16px;">
                    <div style="font-size: 11.5px; font-weight: 700; color: var(--text-muted); text-transform: uppercase; margin-bottom: 6px;">Common Prescriptions (1-Tap Preset)</div>
                    <div style="display: flex; gap: 6px; overflow-x: auto; padding-bottom: 4px;">
                      <button type="button" class="chip-pill" onclick="window.medicare.quickFillMedicineSuggestion('Metformin', '500 mg', 'pill', 'morning', '08:00 AM')">+ Metformin</button>
                      <button type="button" class="chip-pill" onclick="window.medicare.quickFillMedicineSuggestion('Amoxicillin', '250 mg', 'capsule', 'afternoon', '01:00 PM')">+ Amoxicillin</button>
                      <button type="button" class="chip-pill" onclick="window.medicare.quickFillMedicineSuggestion('Lisinopril', '10 mg', 'pill', 'morning', '08:30 AM')">+ Lisinopril</button>
                      <button type="button" class="chip-pill" onclick="window.medicare.quickFillMedicineSuggestion('Vitamin D3', '1000 IU', 'capsule', 'morning', '09:00 AM')">+ Vitamin D3</button>
                    </div>
                  </div>

                  <!-- Add Form -->
                  <div class="app-card" style="margin-bottom: 24px;">
                    <div class="form-group">
                      <label class="form-label" for="add-med-name">Medicine Name</label>
                      <input type="text" id="add-med-name" class="form-input" style="padding-left: 14px;" placeholder="e.g. Amoxicillin, Metformin">
                    </div>

                    <div class="form-group">
                      <label class="form-label" for="add-med-dosage">Dosage Amount</label>
                      <input type="text" id="add-med-dosage" class="form-input" style="padding-left: 14px;" placeholder="e.g. 500 mg, 1 tablet, 10 ml">
                    </div>

                    <!-- Medicine Form / Type -->
                    <div class="form-group">
                      <label class="form-label">Medicine Form</label>
                      <div class="chip-group">
                        <div id="form-type-pill" class="chip-pill form-type-chip active" onclick="window.medicare.setNewMedForm('pill', 'Tablet')">
                          💊 Tablet
                        </div>
                        <div id="form-type-capsule" class="chip-pill form-type-chip" onclick="window.medicare.setNewMedForm('capsule', 'Capsule')">
                          💊 Capsule
                        </div>
                        <div id="form-type-dropper" class="chip-pill form-type-chip" onclick="window.medicare.setNewMedForm('dropper', 'Liquid')">
                          💧 Liquid / Drops
                        </div>
                        <div id="form-type-syringe" class="chip-pill form-type-chip" onclick="window.medicare.setNewMedForm('syringe', 'Injection')">
                          💉 Injection
                        </div>
                      </div>
                    </div>

                    <!-- Time & Day Period -->
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 12px;">
                      <div class="form-group">
                        <label class="form-label" for="add-med-time">Reminder Time</label>
                        <input type="text" id="add-med-time" class="form-input" style="padding-left: 14px;" value="08:00 AM">
                      </div>
                      <div class="form-group">
                        <label class="form-label" for="add-med-period">Period of Day</label>
                        <select id="add-med-period" class="form-input" style="padding-left: 10px;">
                          <option value="morning">🌅 Morning</option>
                          <option value="afternoon">☀️ Afternoon</option>
                          <option value="night">🌙 Night</option>
                        </select>
                      </div>
                    </div>

                    <!-- Frequency -->
                    <div class="form-group">
                      <label class="form-label" for="add-med-frequency">Frequency</label>
                      <select id="add-med-frequency" class="form-input" style="padding-left: 10px;">
                        <option value="Once Daily">Once Daily (Everyday)</option>
                        <option value="Twice Daily">Twice Daily (Morning &amp; Night)</option>
                        <option value="Every 8 Hours">Every 8 Hours</option>
                        <option value="As Needed">As Needed (PRN)</option>
                      </select>
                    </div>

                    <!-- Meal Relation -->
                    <div class="form-group">
                      <label class="form-label">Meal Instruction</label>
                      <div class="chip-group">
                        <div id="meal-rel-before_meal" class="chip-pill meal-rel-chip" onclick="window.medicare.setNewMedMeal('before_meal', 'Before Meal')">Before Meal</div>
                        <div id="meal-rel-with_meal" class="chip-pill meal-rel-chip" onclick="window.medicare.setNewMedMeal('with_meal', 'With Food')">With Food</div>
                        <div id="meal-rel-after_meal" class="chip-pill meal-rel-chip active" onclick="window.medicare.setNewMedMeal('after_meal', 'After Meal')">After Meal</div>
                      </div>
                    </div>

                    <button type="button" class="btn-primary" style="margin-top: 14px;" onclick="window.medicare.saveNewMedicine()">
                      Save Medicine &rarr;
                    </button>
                  </div>
                </div>
              </section>

              <!-- ==========================================================
                   SCREEN 5: MEDICINE SCHEDULE SCREEN
                   ========================================================== -->
              <section id="screen-schedule" class="app-screen">
                <div class="screen-content">
                  <div class="app-header">
                    <div>
                      <h2 class="screen-title">Medicine Schedule</h2>
                      <p class="screen-subtitle">Organized by time of day</p>
                    </div>
                    <button class="icon-btn" onclick="window.medicare.navigateTo('screen-add-medicine')" title="Add Medicine">
                      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>
                    </button>
                  </div>

                  <!-- Calendar Days Row -->
                  <div style="display: flex; gap: 6px; overflow-x: auto; padding-bottom: 12px; margin-bottom: 8px;">
                    <div class="chip-pill active" style="flex: 1; justify-content: center; padding: 8px 4px; flex-direction: column; gap: 2px;">
                      <span style="font-size: 11px; opacity: 0.85;">TODAY</span>
                      <span style="font-size: 15px; font-weight: 800;">Wed 1</span>
                    </div>
                    <div class="chip-pill" style="flex: 1; justify-content: center; padding: 8px 4px; flex-direction: column; gap: 2px;" onclick="window.medicare.showToast('Viewing Thursday schedule')">
                      <span style="font-size: 11px; color: var(--text-muted);">THU</span>
                      <span style="font-size: 15px; font-weight: 800;">2</span>
                    </div>
                    <div class="chip-pill" style="flex: 1; justify-content: center; padding: 8px 4px; flex-direction: column; gap: 2px;" onclick="window.medicare.showToast('Viewing Friday schedule')">
                      <span style="font-size: 11px; color: var(--text-muted);">FRI</span>
                      <span style="font-size: 15px; font-weight: 800;">3</span>
                    </div>
                    <div class="chip-pill" style="flex: 1; justify-content: center; padding: 8px 4px; flex-direction: column; gap: 2px;" onclick="window.medicare.showToast('Viewing Saturday schedule')">
                      <span style="font-size: 11px; color: var(--text-muted);">SAT</span>
                      <span style="font-size: 15px; font-weight: 800;">4</span>
                    </div>
                  </div>

                  <!-- Morning Section -->
                  <div style="margin-bottom: 18px;">
                    <div style="display: flex; align-items: center; gap: 6px; font-size: 13px; font-weight: 800; color: var(--primary-700); text-transform: uppercase; margin-bottom: 8px;">
                      <span>🌅 Morning (08:00 AM)</span>
                    </div>
                    <div id="schedule-morning-list">
                      <!-- Rendered by app.js -->
                    </div>
                  </div>

                  <!-- Afternoon Section -->
                  <div style="margin-bottom: 18px;">
                    <div style="display: flex; align-items: center; gap: 6px; font-size: 13px; font-weight: 800; color: var(--secondary-600); text-transform: uppercase; margin-bottom: 8px;">
                      <span>☀️ Afternoon (01:30 PM)</span>
                    </div>
                    <div id="schedule-afternoon-list">
                      <!-- Rendered by app.js -->
                    </div>
                  </div>

                  <!-- Night Section -->
                  <div style="margin-bottom: 18px;">
                    <div style="display: flex; align-items: center; gap: 6px; font-size: 13px; font-weight: 800; color: #7C3AED; text-transform: uppercase; margin-bottom: 8px;">
                      <span>🌙 Night (08:30 PM - 10:00 PM)</span>
                    </div>
                    <div id="schedule-night-list">
                      <!-- Rendered by app.js -->
                    </div>
                  </div>
                </div>
              </section>

              <!-- ==========================================================
                   SCREEN 6: MEDICINE DETAILS SCREEN
                   ========================================================== -->
              <section id="screen-details" class="app-screen">
                <div class="screen-content" id="med-details-content">
                  <!-- Rendered dynamically by app.js -->
                </div>
              </section>

              <!-- ==========================================================
                   SCREEN 7: REMINDER SCREEN (ACTIVE ALARM VIEW)
                   ========================================================== -->
              <section id="screen-reminder" class="app-screen">
                <div class="screen-content" id="reminder-screen-content">
                  <!-- Rendered dynamically by app.js -->
                </div>
              </section>

              <!-- ==========================================================
                   SCREEN 8: PROFILE SCREEN
                   ========================================================== -->
              <section id="screen-profile" class="app-screen">
                <div class="screen-content">
                  <div class="app-header">
                    <div>
                      <h2 class="screen-title">Patient Profile</h2>
                      <p class="screen-subtitle">Personal health records &amp; contacts</p>
                    </div>
                    <button class="icon-btn" onclick="window.medicare.openSettingsModal()" title="Settings">
                      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12.22 2h-.44a2 2 0 0 0-2 2v.18a2 2 0 0 1-1 1.73l-.43.25a2 2 0 0 1-2 0l-.15-.08a2 2 0 0 0-2.73.73l-.22.38a2 2 0 0 0 .73 2.73l.15.1a2 2 0 0 1 1 1.72v.51a2 2 0 0 1-1 1.74l-.15.09a2 2 0 0 0-.73 2.73l.22.38a2 2 0 0 0 2.73.73l.15-.08a2 2 0 0 1 2 0l.43.25a2 2 0 0 1 1 1.73V20a2 2 0 0 0 2 2h.44a2 2 0 0 0 2-2v-.18a2 2 0 0 1 1-1.73l.43-.25a2 2 0 0 1 2 0l.15.08a2 2 0 0 0 2.73-.73l.22-.39a2 2 0 0 0-.73-2.73l-.15-.08a2 2 0 0 1-1-1.74v-.5a2 2 0 0 1 1-1.74l.15-.09a2 2 0 0 0 .73-2.73l-.22-.38a2 2 0 0 0-2.73-.73l-.15.08a2 2 0 0 1-2 0l-.43-.25a2 2 0 0 1-1-1.73V4a2 2 0 0 0-2-2z"/>
                        <circle cx="12" cy="12" r="3"/>
                      </svg>
                    </button>
                  </div>

                  <div id="profile-content-wrap">
                    <!-- Rendered by app.js -->
                  </div>
                </div>
              </section>

            </div>

            <!-- Floating Bottom Navigation Bar -->
            <nav id="bottom-nav" class="bottom-nav hidden-nav">
              <button id="nav-home" class="nav-item active" onclick="window.medicare.navigateTo('screen-home')">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round">
                  <path d="m3 9 9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/>
                  <polyline points="9 22 9 12 15 12 15 22"/>
                </svg>
                <span>Home</span>
              </button>

              <button id="nav-schedule" class="nav-item" onclick="window.medicare.navigateTo('screen-schedule')">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round">
                  <rect width="18" height="18" x="3" y="4" rx="2" ry="2"/>
                  <line x1="16" x2="16" y1="2" y2="6"/>
                  <line x1="8" x2="8" y1="2" y2="6"/>
                  <line x1="3" x2="21" y1="10" y2="10"/>
                </svg>
                <span>Schedule</span>
              </button>

              <!-- Center Add FAB -->
              <button class="nav-fab-btn" onclick="window.medicare.navigateTo('screen-add-medicine')" title="Add Medicine">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
                  <line x1="12" y1="5" x2="12" y2="19"/>
                  <line x1="5" y1="12" x2="19" y2="12"/>
                </svg>
              </button>

              <button id="nav-alarm" class="nav-item" onclick="window.medicare.triggerActiveReminder('med-4')">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round">
                  <path d="M6 8a6 6 0 0 1 12 0c0 7 3 9 3 9H3s3-2 3-9"/>
                  <path d="M10.3 21a1.94 1.94 0 0 0 3.4 0"/>
                </svg>
                <span>Reminder</span>
              </button>

              <button id="nav-profile" class="nav-item" onclick="window.medicare.navigateTo('screen-profile')">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round">
                  <path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2"/>
                  <circle cx="12" cy="7" r="4"/>
                </svg>
                <span>Profile</span>
              </button>
            </nav>

            <!-- iOS Home Indicator -->
            <div id="home-indicator" class="home-indicator"></div>

            <!-- ==========================================================
                 MODALS / BOTTOM SHEETS
                 ========================================================== -->

            <!-- Edit Medicine Bottom Sheet -->
            <div id="edit-medicine-sheet" class="modal-overlay" onclick="if(event.target === this) window.medicare.closeModal('edit-medicine-sheet')">
              <div class="modal-sheet">
                <div class="sheet-handle"></div>
                <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 14px;">
                  <h3 style="font-size: 18px; font-weight: 800; color: var(--text-main);">Edit Prescription</h3>
                  <button class="icon-btn" onclick="window.medicare.closeModal('edit-medicine-sheet')" style="width: 32px; height: 32px;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6 6 18M6 6l12 12"/></svg>
                  </button>
                </div>

                <input type="hidden" id="edit-med-id">

                <div class="form-group">
                  <label class="form-label">Medicine Name</label>
                  <input type="text" id="edit-med-name" class="form-input" style="padding-left: 14px;">
                </div>

                <div class="form-group">
                  <label class="form-label">Dosage</label>
                  <input type="text" id="edit-med-dosage" class="form-input" style="padding-left: 14px;">
                </div>

                <div class="form-group">
                  <label class="form-label">Reminder Time</label>
                  <input type="text" id="edit-med-time" class="form-input" style="padding-left: 14px;">
                </div>

                <button class="btn-primary" style="margin-top: 14px;" onclick="window.medicare.saveEditedMedicine()">
                  Save Changes
                </button>
              </div>
            </div>

            <!-- Edit Profile Bottom Sheet -->
            <div id="edit-profile-sheet" class="modal-overlay" onclick="if(event.target === this) window.medicare.closeModal('edit-profile-sheet')">
              <div class="modal-sheet">
                <div class="sheet-handle"></div>
                <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 14px;">
                  <h3 style="font-size: 18px; font-weight: 800; color: var(--text-main);">Edit Patient Information</h3>
                  <button class="icon-btn" onclick="window.medicare.closeModal('edit-profile-sheet')" style="width: 32px; height: 32px;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6 6 18M6 6l12 12"/></svg>
                  </button>
                </div>

                <div class="form-group">
                  <label class="form-label">Patient Name</label>
                  <input type="text" id="edit-profile-name" class="form-input" style="padding-left: 14px;">
                </div>

                <div class="form-group">
                  <label class="form-label">Age</label>
                  <input type="number" id="edit-profile-age" class="form-input" style="padding-left: 14px;">
                </div>

                <div class="form-group">
                  <label class="form-label">Known Drug Allergies</label>
                  <input type="text" id="edit-profile-allergies" class="form-input" style="padding-left: 14px;">
                </div>

                <div class="form-group">
                  <label class="form-label">Emergency Contact Info</label>
                  <input type="text" id="edit-profile-contact" class="form-input" style="padding-left: 14px;">
                </div>

                <button class="btn-primary" style="margin-top: 14px;" onclick="window.medicare.saveProfileChanges()">
                  Update Profile
                </button>
              </div>
            </div>

            <!-- Settings Sheet -->
            <div id="settings-sheet" class="modal-overlay" onclick="if(event.target === this) window.medicare.closeModal('settings-sheet')">
              <div class="modal-sheet">
                <div class="sheet-handle"></div>
                <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 14px;">
                  <h3 style="font-size: 18px; font-weight: 800; color: var(--text-main);">Application Settings</h3>
                  <button class="icon-btn" onclick="window.medicare.closeModal('settings-sheet')" style="width: 32px; height: 32px;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6 6 18M6 6l12 12"/></svg>
                  </button>
                </div>

                <div style="display: flex; flex-direction: column; gap: 12px;">
                  <div style="display: flex; justify-content: space-between; align-items: center; padding: 12px; background: var(--bg-input); border-radius: var(--radius-sm);">
                    <div>
                      <div style="font-size: 14px; font-weight: 700; color: var(--text-main);">Dark Mode</div>
                      <div style="font-size: 11.5px; color: var(--text-secondary);">Toggle high-contrast OLED theme</div>
                    </div>
                    <button class="tool-btn" style="background: var(--primary-600); color: #fff; padding: 6px 14px;" onclick="window.medicare.toggleTheme()">
                      Toggle
                    </button>
                  </div>

                  <div style="display: flex; justify-content: space-between; align-items: center; padding: 12px; background: var(--bg-input); border-radius: var(--radius-sm);">
                    <div>
                      <div style="font-size: 14px; font-weight: 700; color: var(--text-main);">Medical Audio Chimes</div>
                      <div style="font-size: 11.5px; color: var(--text-secondary);">Synthesized haptic chimes &amp; alarms</div>
                    </div>
                    <button class="tool-btn" style="background: var(--primary-600); color: #fff; padding: 6px 14px;" onclick="window.medicare.toggleSound()">
                      Toggle
                    </button>
                  </div>

                  <div style="display: flex; justify-content: space-between; align-items: center; padding: 12px; background: var(--bg-input); border-radius: var(--radius-sm);">
                    <div>
                      <div style="font-size: 14px; font-weight: 700; color: var(--text-main);">Caregiver Notification Sync</div>
                      <div style="font-size: 11.5px; color: var(--text-secondary);">Alerts family upon missed doses</div>
                    </div>
                    <span class="badge badge-success">Enabled</span>
                  </div>
                </div>

                <button class="btn-secondary" style="margin-top: 18px;" onclick="window.medicare.closeModal('settings-sheet')">
                  Close Settings
                </button>
              </div>
            </div>

            <!-- Forgot Password Sheet -->
            <div id="forgot-password-sheet" class="modal-overlay" onclick="if(event.target === this) window.medicare.closeModal('forgot-password-sheet')">
              <div class="modal-sheet">
                <div class="sheet-handle"></div>
                <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 14px;">
                  <h3 style="font-size: 18px; font-weight: 800; color: var(--text-main);">Account Recovery</h3>
                  <button class="icon-btn" onclick="window.medicare.closeModal('forgot-password-sheet')" style="width: 32px; height: 32px;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6 6 18M6 6l12 12"/></svg>
                  </button>
                </div>
                <p style="font-size: 13px; color: var(--text-secondary); margin-bottom: 16px;">
                  Enter your registered email address or phone number to receive a secure login code.
                </p>
                <div class="form-group">
                  <label class="form-label">Email or Phone</label>
                  <input type="text" class="form-input" style="padding-left: 14px;" value="sarah.jenkins@medicare.app">
                </div>
                <button class="btn-primary" onclick="window.medicare.closeModal('forgot-password-sheet'); window.medicare.showToast('Recovery instructions sent via SMS & Email!')">
                  Send Recovery Link
                </button>
              </div>
            </div>

          </div>
        </div>
      </div>
    </main>
  </div>

  <!-- ==========================================================
       CASE STUDY & DOCUMENTATION MODAL (FULL PORTFOLIO SHOWCASE)
       ========================================================== -->
  <div id="case-study-modal" class="doc-modal" onclick="if(event.target === this) window.medicare.closeModal('case-study-modal')">
    <div class="doc-modal-content">
      <div class="doc-header">
        <div>
          <span style="font-size: 11px; font-weight: 700; color: #5EEAD4; text-transform: uppercase; letter-spacing: 0.05em;">Academic Internship UI/UX Portfolio</span>
          <h2 style="font-size: 20px; font-weight: 800; color: #FFFFFF; margin: 0;">
            MediCare – Medicine Reminder App UI/UX Case Study
          </h2>
        </div>
        <button class="icon-btn" onclick="window.medicare.closeModal('case-study-modal')" style="background: rgba(255, 255, 255, 0.08); color: #FFFFFF; border-color: rgba(255, 255, 255, 0.15);">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6 6 18M6 6l12 12"/></svg>
        </button>
      </div>

      <div class="doc-body">
        <!-- 1. Project Title & Objective -->
        <section>
          <h2>🎯 1. Project Title &amp; Objective</h2>
          <p>
            <strong>Project Title:</strong> MediCare – Medicine Reminder App<br>
            <strong>Objective:</strong> To design a modern, clean, and accessible mobile healthcare companion that combats medication non-adherence, streamlines complex prescription schedules into natural circadian periods, and empowers patients and caregivers with reliable reminders and effortless logging.
          </p>
        </section>

        <!-- 2. Problem Statement -->
        <section>
          <h2>⚠️ 2. Problem Statement</h2>
          <div style="background: rgba(13, 148, 136, 0.1); border-left: 4px solid #14B8A6; padding: 14px 18px; border-radius: 0 12px 12px 0; margin: 16px 0;">
            According to the <strong>World Health Organization (WHO)</strong>, over 50% of patients with chronic diseases (such as hypertension, diabetes, and heart disease) fail to adhere to their prescribed medical regimens. Non-adherence leads to avoidable hospital readmissions, exacerbated health complications, and increased healthcare costs.
          </div>
          <ul style="font-size: 13px; color: #CBD5E1; padding-left: 18px; line-height: 1.8;">
            <li><strong>Complex Dosing:</strong> Patients juggling 3+ medications struggle with contradictory instructions (e.g., *"with meal"* vs. *"before bedtime"*).</li>
            <li><strong>Memory &amp; Fatigue:</strong> As the day progresses, patients forget whether they took their morning or afternoon dose.</li>
            <li><strong>Cluttered Clinical Interfaces:</strong> Existing reminder tools suffer from intrusive ads, sterile visual design, and cumbersome multi-step logging flows.</li>
          </ul>
        </section>

        <!-- 3. Target Users -->
        <section>
          <h2>👥 3. Target Users</h2>
          <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 14px; margin: 16px 0;">
            <div style="background: rgba(255, 255, 255, 0.04); padding: 16px; border-radius: 14px; border: 1px solid rgba(255, 255, 255, 0.08);">
              <h4 style="color: #5EEAD4; margin-bottom: 6px;">1. Chronic Condition Patients</h4>
              <p style="font-size: 12.5px; color: #94A3B8;">Individuals with hypertension, diabetes, or cholesterol imbalances who depend on precise daily prescriptions.</p>
            </div>
            <div style="background: rgba(255, 255, 255, 0.04); padding: 16px; border-radius: 14px; border: 1px solid rgba(255, 255, 255, 0.08);">
              <h4 style="color: #5EEAD4; margin-bottom: 6px;">2. Elderly Adults</h4>
              <p style="font-size: 12.5px; color: #94A3B8;">Users requiring high contrast, large touch targets (&ge; 44px), legible typography, and straightforward 1-tap confirmation.</p>
            </div>
            <div style="background: rgba(255, 255, 255, 0.04); padding: 16px; border-radius: 14px; border: 1px solid rgba(255, 255, 255, 0.08);">
              <h4 style="color: #5EEAD4; margin-bottom: 6px;">3. Family Caregivers</h4>
              <p style="font-size: 12.5px; color: #94A3B8;">Adult children and nurses tracking elderly parents' medication schedules remotely to ensure timely compliance.</p>
            </div>
          </div>
        </section>

        <!-- 4. Key Features -->
        <section>
          <h2>⭐ 4. Key Features</h2>
          <ol style="font-size: 13px; color: #CBD5E1; padding-left: 20px; line-height: 1.8;">
            <li><strong>Circadian Partitioning:</strong> Automatically categorizes doses into <em>Morning</em>, <em>Afternoon</em>, and <em>Night</em> sections.</li>
            <li><strong>Next Medicine Highlight:</strong> Prominently displays the imminent next dose with a countdown timer.</li>
            <li><strong>1-Tap 'Taken' Confirmation:</strong> Checkbox interaction completes logging in under 1.5 seconds.</li>
            <li><strong>Active Alarm &amp; Snooze:</strong> Fullscreen alarm modal with "Taken" celebration and 15-minute "Remind Me Later" snooze.</li>
            <li><strong>Refill &amp; Inventory Alerts:</strong> Visual pill stock progress bars alerting users when stock drops below 7 doses.</li>
            <li><strong>Emergency Health Profile:</strong> Instant access to blood group, allergy warnings, and physician contacts.</li>
          </ol>
        </section>

        <!-- 5. UI/UX Design Approach -->
        <section>
          <h2>🎨 5. UI/UX Design Approach</h2>
          <p>
            The interface follows human-computer interaction (HCI) best practices for digital healthcare, prioritizing clarity, trust, and psychological calm:
          </p>

          <h3>Color Palette</h3>
          <div class="color-swatch-grid">
            <div class="color-swatch">
              <div class="swatch-preview" style="background: #0D9488;"></div>
              <div style="font-size: 12px; font-weight: 700;">Clinical Teal</div>
              <div style="font-size: 11px; color: #94A3B8;">#0D9488 &bull; Primary</div>
            </div>
            <div class="color-swatch">
              <div class="swatch-preview" style="background: #14B8A6;"></div>
              <div style="font-size: 12px; font-weight: 700;">Vibrant Cyan</div>
              <div style="font-size: 11px; color: #94A3B8;">#14B8A6 &bull; Active</div>
            </div>
            <div class="color-swatch">
              <div class="swatch-preview" style="background: #0284C7;"></div>
              <div style="font-size: 12px; font-weight: 700;">Medical Blue</div>
              <div style="font-size: 11px; color: #94A3B8;">#0284C7 &bull; Secondary</div>
            </div>
            <div class="color-swatch">
              <div class="swatch-preview" style="background: #10B981;"></div>
              <div style="font-size: 12px; font-weight: 700;">Emerald Taken</div>
              <div style="font-size: 11px; color: #94A3B8;">#10B981 &bull; Success</div>
            </div>
            <div class="color-swatch">
              <div class="swatch-preview" style="background: #F8FAFC; border: 1px solid #E2E8F0;"></div>
              <div style="font-size: 12px; font-weight: 700; color: #CBD5E1;">Soft Mint Slate</div>
              <div style="font-size: 11px; color: #94A3B8;">#F8FAFC &bull; Canvas</div>
            </div>
          </div>

          <h3>Visual Ergonomics &amp; Hierarchy</h3>
          <ul style="font-size: 12.5px; color: #CBD5E1; padding-left: 18px; line-height: 1.7;">
            <li><strong>Physical Form Cues:</strong> Distinct vector iconography for Tablets, Capsules, Liquids, and Injections to eliminate pill confusion.</li>
            <li><strong>Positive Reinforcement:</strong> Gentle audio chimes and celebratory micro-animations reward patients for maintaining their daily health habit.</li>
            <li><strong>Fitts' Law Optimization:</strong> Critical actions (Take Medicine, Save, Add) are positioned in the comfortable bottom-thumb zone.</li>
          </ul>
        </section>

        <!-- 6. Tools and Technologies Used -->
        <section>
          <h2>💻 6. Tools and Technologies Used</h2>
          <ul style="font-size: 13px; color: #CBD5E1; padding-left: 18px; line-height: 1.7;">
            <li><strong>Front-End Architecture:</strong> Semantic HTML5 &amp; Modern Mobile-First CSS3 Grid/Flexbox.</li>
            <li><strong>Theming &amp; Design Tokens:</strong> Pure CSS Custom Properties with light and OLED dark mode.</li>
            <li><strong>Reactive Engine:</strong> Vanilla JavaScript ES6+ State Controller (zero external dependencies).</li>
            <li><strong>Haptic Sound Synthesizer:</strong> Web Audio API (real-time synthesized sine and triangle oscillators).</li>
            <li><strong>Iconography:</strong> Standalone inline Scalable Vector Graphics (SVG).</li>
            <li><strong>Hardware Simulation:</strong> iPhone 16 Pro Titanium chassis with interactive Dynamic Island.</li>
          </ul>
        </section>

        <!-- 7. Conclusion -->
        <section>
          <h2>🎉 7. Conclusion</h2>
          <p style="font-size: 13px; color: #CBD5E1; line-height: 1.8;">
            <strong>MediCare</strong> showcases how empathetic mobile UI/UX design can transform a tedious medical obligation into a calming, effortless daily routine. By reducing cognitive load through natural time-of-day partitioning, immediate 1-tap logging, and thoughtful visual affordances, MediCare serves as a presentation-ready academic internship project that bridges medical prescription rigor with everyday human habit formation.
          </p>
        </section>
      </div>
    </div>
  </div>

  <!-- Application Scripts -->
  <script src="js/icons.js"></script>
  <script src="js/data.js"></script>
  <script src="js/app.js"></script>
</body>
</html>
