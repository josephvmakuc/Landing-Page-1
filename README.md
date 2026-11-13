<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="IT Support Specialist Portfolio for Joe Makuc: Helpdesk Specialist, End-User Technician, and CompTIA A+ Certified IT Professional. Features Tier 1/2 technical support, operating systems, networking, security, and documentation expertise across 10 institutions.">
  <meta name="author" content="Joe Makuc">
  <meta name="robots" content="index, follow">

  <!-- Open Graph / Social Media SEO -->
  <meta property="og:title" content="Joe Makuc | IT Helpdesk & End-User Support Specialist Portfolio">
  <meta property="og:description" content="IT Career Portfolio demonstrating end-user technical support, network fundamentals, operating systems, security compliance, and exceptional customer service skills.">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://josephvmakuc.github.io/">

  <title>Joe Makuc | IT Helpdesk & End-User Support Specialist Portfolio</title>

  <!-- Schema.org Structured Data (SEO Person Schema) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Joe Makuc",
    "jobTitle": "IT Helpdesk & End-User Support Specialist",
    "url": "https://github.com/josephvmakuc",
    "sameAs": [
      "https://www.linkedin.com/in/joe-makuc/",
      "https://github.com/josephvmakuc"
    ],
    "alumniOf": [
      {
        "@type": "EducationalOrganization",
        "name": "Per Scholas",
        "url": "https://perscholas.org/"
      },
      {
        "@type": "EducationalOrganization",
        "name": "Temple University",
        "url": "https://www.temple.edu/"
      },
      {
        "@type": "EducationalOrganization",
        "name": "Ursinus College",
        "url": "https://www.ursinus.edu/"
      }
    ],
    "worksFor": [
      {
        "@type": "Organization",
        "name": "Children's Hospital of Philadelphia",
        "url": "https://www.chop.edu/"
      }
    ],
    "knowsAbout": [
      "IT Helpdesk Support",
      "End-User Technical Support",
      "CompTIA A+",
      "Technical Documentation",
      "Windows 10/11",
      "Ubuntu Linux",
      "Active Directory & IAM",
      "TCP/IP Networking",
      "DHCP & DNS",
      "Healthcare IT Security",
      "Information Security & Compliance",
      "WCAG Accessibility"
    ]
  }
  </script>

  <style>
    /* High Contrast Minimalist Palette (WCAG 2.1 AAA Compliant) */
    :root {
      --bg-color: #0a0d12;
      --card-bg: #121721;
      --border-color: #444c56;
      --text-main: #6e776f;
      --text-muted: #adbac7;
      --accent-color: #71b7ff;
      --accent-hover: #96cbff;
      --tag-bg: #1c212b;
      --focus-ring: #6e776f;
      --font-stack: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }

    /* Accessibility Base Rules */
    *, *::before, *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      font-family: var(--font-stack);
      font-size: 100%;
      line-height: 1.6;
      color: var(--text-main);
      background-color: var(--bg-color);
      scroll-behavior: smooth;
    }

    body {
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem 1.5rem;
    }

    /* Accessible Skip Link */
    .skip-link {
      position: absolute;
      top: -60px;
      left: 0;
      background: var(--accent-color);
      color: #000000;
      padding: 10px 18px;
      z-index: 100;
      text-decoration: none;
      font-weight: bold;
      border-radius: 0 0 4px 0;
      transition: top 0.2s ease;
    }

    .skip-link:focus {
      top: 0;
    }

    /* Focus States for Keyboard Navigation */
    a:focus-visible, button:focus-visible {
      outline: 3px solid var(--focus-ring);
      outline-offset: 3px;
      border-radius: 2px;
    }

    /* Typography & Headers */
    h1, h2, h3 {
      color: var(--text-main);
      line-height: 1.25;
      margin-bottom: 0.75rem;
    }

    h1 {
      font-size: 2.25rem;
      font-weight: 700;
      letter-spacing: -0.02em;
    }

    h2 {
      font-size: 1.5rem;
      font-weight: 600;
      border-bottom: 2px solid var(--border-color);
      padding-bottom: 0.5rem;
      margin-top: 2.5rem;
      margin-bottom: 1.25rem;
    }

    h3 {
      font-size: 1.15rem;
      font-weight: 600;
    }

    p {
      color: var(--text-main);
      margin-bottom: 1rem;
    }

    .muted-text {
      color: var(--text-muted);
    }

    a {
      color: var(--accent-color);
      text-decoration: underline;
      text-underline-offset: 4px;
    }

    a:hover, a:focus {
      color: var(--accent-hover);
    }

    /* Navigation Bar */
    nav {
      margin-bottom: 2rem;
    }

    nav ul {
      display: flex;
      flex-wrap: wrap;
      gap: 1.25rem;
      list-style: none;
      padding: 0;
    }

    nav a {
      text-decoration: none;
      font-weight: 600;
      font-size: 0.95rem;
      color: var(--text-muted);
    }

    nav a:hover, nav a:focus {
      color: var(--accent-color);
      text-decoration: underline;
    }

    /* Header & Hero Section */
    header {
      margin-bottom: 3rem;
    }

    .hero-badge {
      display: inline-block;
      background-color: var(--tag-bg);
      border: 1px solid var(--border-color);
      color: var(--accent-color);
      font-size: 0.85rem;
      font-weight: 600;
      padding: 0.35rem 0.85rem;
      border-radius: 12px;
      margin-bottom: 1rem;
    }

    .social-links {
      display: flex;
      gap: 1rem;
      margin-top: 1.25rem;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      padding: 0.6rem 1.1rem;
      background-color: var(--card-bg);
      border: 1.5px solid var(--border-color);
      color: var(--text-main);
      text-decoration: none;
      border-radius: 6px;
      font-size: 0.9rem;
      font-weight: 600;
      transition: background-color 0.2s ease, border-color 0.2s ease;
    }

    .btn:hover, .btn:focus {
      background-color: var(--tag-bg);
      border-color: var(--accent-color);
      color: var(--text-main);
    }

    /* Section Cards Grid */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.25rem;
      margin-top: 1rem;
    }

    .card {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      padding: 1.25rem;
    }

    .tag-container {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 0.75rem;
    }

    .tag {
      background-color: var(--tag-bg);
      border: 1px solid var(--border-color);
      color: var(--text-main);
      font-size: 0.8rem;
      font-weight: 500;
      padding: 0.25rem 0.6rem;
      border-radius: 4px;
    }

    /* Timeline & Experience Items */
    .timeline-item {
      margin-bottom: 1.75rem;
      padding-left: 1.25rem;
      border-left: 3px solid var(--border-color);
    }

    .timeline-meta {
      font-size: 0.85rem;
      color: var(--text-muted);
      margin-bottom: 0.4rem;
    }

    .timeline-item ul {
      margin-left: 1.25rem;
      margin-top: 0.5rem;
    }

    .timeline-item li {
      margin-bottom: 0.35rem;
    }

    /* Figures & Accessible Media */
    figure {
      margin: 1.5rem 0;
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      padding: 1rem;
    }

    figcaption {
      font-size: 0.85rem;
      color: var(--text-muted);
      margin-top: 0.5rem;
      text-align: center;
    }

    /* Footer */
    footer {
      margin-top: 4rem;
      padding-top: 1.5rem;
      border-top: 1px solid var(--border-color);
      font-size: 0.85rem;
      color: var(--text-muted);
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Accessible Skip Link for Screen Readers & Keyboard Navigation -->
  <a href="#main" class="skip-link">Skip to main content</a>

  <!-- Navigation -->
  <nav aria-label="Main Navigation">
    <ul>
      <li><a href="#summary">Profile</a></li>
      <li><a href="#skills">Technical Skills</a></li>
      <li><a href="#workflow">Support Workflow</a></li>
      <li><a href="#experience">Institutional Experience</a></li>
      <li><a href="#education">Education &amp; Credentials</a></li>
    </ul>
  </nav>

  <!-- Hero Header -->
  <header>
    <span class="hero-badge">CompTIA A+ Certified | Helpdesk &amp; End-User Support Technician</span>
    <h1>Joe Makuc</h1>
    <p class="muted-text">
      IT Helpdesk Specialist &amp; End-User Support Technician | Philadelphia, PA
    </p>
    <p>
      Dedicated IT Technician with CompTIA A+ certification, 600+ hours of hands-on hardware/networking training at Per Scholas, and over 10 years of user support experience across healthcare, academic, and cultural institutions. Specializes in Tier 1/2 endpoint troubleshooting, operating system administration, networking fundamentals, security compliance, and comprehensive technical documentation.
    </p>
    
    <div class="social-links">
      <a href="https://www.linkedin.com/in/joe-makuc/" class="btn" target="_blank" rel="noopener noreferrer" aria-label="Joe Makuc's LinkedIn Profile (opens in a new tab)">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-.5 15.5v-5.3a3.26 3.26 0 0 0-3.26-3.26c-.85 0-1.84.52-2.28 1.3v-1.11h-2.79v8.37h2.79v-4.93c0-.77.62-1.4 1.39-1.4a1.4 1.4 0 0 1 1.4 1.4v4.93h2.75M6.88 8.56a1.68 1.68 0 0 0 1.68-1.68c0-.93-.75-1.69-1.68-1.69a1.69 1.69 0 0 0-1.69 1.69c0 .93.76 1.68 1.69 1.68m1.39 9.94v-8.37H5.5v8.37h2.77z"/></svg>
        LinkedIn Profile
      </a>
      <a href="https://github.com/josephvmakuc" class="btn" target="_blank" rel="noopener noreferrer" aria-label="Joe Makuc's GitHub Repository (opens in a new tab)">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2A10 10 0 0 0 2 12c0 4.42 2.87 8.17 6.84 9.5.5.08.66-.23.66-.5v-1.69c-2.77.6-3.36-1.34-3.36-1.34-.46-1.16-1.11-1.47-1.11-1.47-.91-.62.07-.6.07-.6 1 .07 1.53 1.03 1.53 1.03.87 1.52 2.34 1.07 2.91.83.1-.65.35-1.09.63-1.34-2.22-.25-4.55-1.11-4.55-4.92 0-1.11.38-2 1.03-2.71-.1-.25-.45-1.29.1-2.64 0 0 .84-.27 2.75 1.02.79-.22 1.65-.33 2.5-.33.85 0 1.71.11 2.5.33 1.91-1.29 2.75-1.02 2.75-1.02.55 1.35.2 2.39.1 2.64.65.71 1.03 1.6 1.03 2.71 0 3.82-2.34 4.66-4.57 4.91.36.31.69.92.69 1.85V21c0 .27.16.59.67.5C19.14 20.16 22 16.42 22 12A10 10 0 0 0 12 2z"/></svg>
        GitHub Portfolio
      </a>
      <a href="mailto:josephvmakuc@gmail.com" class="btn" aria-label="Send email to Joe Makuc">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
        Email Contact
      </a>
    </div>
  </header>

  <main id="main">

    <!-- Professional Summary -->
    <section id="summary" aria-labelledby="heading-summary">
      <h2 id="heading-summary">Professional Profile &amp; Objective</h2>
      <p>
        Seeking a dedicated <strong>IT Helpdesk, End-User Support, or Desktop Technician</strong> role. Brings a strong foundation in CompTIA troubleshooting methodologies, hardware diagnostics, and ticketing workflows, paired with a passion for delivering empathetic, high-satisfaction technical support. Combining healthcare IT experience from Children's Hospital of Philadelphia (CHOP) with extensive technical writing background across 6 organizations, my goal is to maximize end-user productivity while upholding organizational security and network integrity.
      </p>
    </section>

    <!-- Full Suite Technical Skills Matrix -->
    <section id="skills" aria-labelledby="heading-skills">
      <h2 id="heading-skills">Certifiable &amp; Endorsed Technical Skills</h2>
      <div class="grid">
        <article class="card">
          <h3>Helpdesk &amp; End-User Support</h3>
          <p class="muted-text">Tier 1/2 ticket triage, remote desktop support, ITIL service management, incident management, user onboarding/offboarding, high-satisfaction user assistance.</p>
          <div class="tag-container">
            <span class="tag">ServiceNow</span>
            <span class="tag">Remote Support</span>
            <span class="tag">ITIL Framework</span>
            <span class="tag">Ticket Triage</span>
          </div>
        </article>

        <article class="card">
          <h3>Operating Systems &amp; Hardware</h3>
          <p class="muted-text">Windows 10/11 troubleshooting, Ubuntu Linux configuration, macOS, Android, PC build/repair, ESD safety, peripherals, BIOS/UEFI deployment.</p>
          <div class="tag-container">
            <span class="tag">Windows 10/11</span>
            <span class="tag">Ubuntu Linux</span>
            <span class="tag">Hardware Repair</span>
            <span class="tag">BIOS/UEFI</span>
          </div>
        </article>

        <article class="card">
          <h3>Networking &amp; Infrastructure</h3>
          <p class="muted-text">TCP/IP protocol suite, DHCP &amp; DNS troubleshooting, Wi-Fi configuration, VPN setup, cabling, NAS migration, local data architecture.</p>
          <div class="tag-container">
            <span class="tag">TCP/IP</span>
            <span class="tag">DHCP / DNS</span>
            <span class="tag">VPN Config</span>
            <span class="tag">NAS Migration</span>
          </div>
        </article>

        <article class="card">
          <h3>Security, IAM &amp; Technical Documentation</h3>
          <p class="muted-text">Active Directory user management, HIPAA/GCP compliance, data privacy, technical manual authoring, WCAG 2.1 accessibility, web archiving.</p>
          <div class="tag-container">
            <span class="tag">Active Directory</span>
            <span class="tag">HIPAA Security</span>
            <span class="tag">Tech Writing</span>
            <span class="tag">WCAG 2.1</span>
          </div>
        </article>
      </div>
    </section>

    <!-- Accessible Visual Diagram: Support Workflow -->
    <section id="workflow" aria-labelledby="heading-workflow">
      <h2 id="heading-workflow">End-User Support &amp; Incident Resolution Workflow</h2>
      <figure>
        <svg width="100%" height="130" viewBox="0 0 600 130" role="img" aria-label="Diagram showing 4-step IT Helpdesk support process: Ticket Intake, Triage & Diagnostics, Resolution & Security Compliance, and User Communication & Documentation">
          <!-- Step 1 -->
          <rect x="10" y="20" width="130" height="90" rx="6" fill="#121721" stroke="#444c56" stroke-width="2"/>
          <text x="75" y="55" fill="#71b7ff" font-family="sans-serif" font-size="12" font-weight="bold" text-anchor="middle">1. Intake</text>
          <text x="75" y="75" fill="#adbac7" font-family="sans-serif" font-size="10" text-anchor="middle">Ticket Logging</text>
          <text x="75" y="90" fill="#adbac7" font-family="sans-serif" font-size="10" text-anchor="middle">&amp; User Contact</text>

          <!-- Arrow 1 -->
          <path d="M 145 65 L 155 65" stroke="#71b7ff" stroke-width="2" marker-end="url(#arrow)"/>

          <!-- Step 2 -->
          <rect x="160" y="20" width="130" height="90" rx="6" fill="#121721" stroke="#444c56" stroke-width="2"/>
          <text x="225" y="55" fill="#71b7ff" font-family="sans-serif" font-size="12" font-weight="bold" text-anchor="middle">2. Triage</text>
          <text x="225" y="75" fill="#adbac7" font-family="sans-serif" font-size="10" text-anchor="middle">OS/Hardware/Net</text>
          <text x="225" y="90" fill="#adbac7" font-family="sans-serif" font-size="10" text-anchor="middle">Diagnostics</text>

          <!-- Arrow 2 -->
          <path d="M 295 65 L 305 65" stroke="#71b7ff" stroke-width="2" marker-end="url(#arrow)"/>

          <!-- Step 3 -->
          <rect x="310" y="20" width="130" height="90" rx="6" fill="#121721" stroke="#444c56" stroke-width="2"/>
          <text x="375" y="55" fill="#71b7ff" font-family="sans-serif" font-size="12" font-weight="bold" text-anchor="middle">3. Resolution</text>
          <text x="375" y="75" fill="#adbac7" font-family="sans-serif" font-size="10" text-anchor="middle">Fix Application</text>
          <text x="375" y="90" fill="#adbac7" font-family="sans-serif" font-size="10" text-anchor="middle">&amp; Sec Check</text>

          <!-- Arrow 3 -->
          <path d="M 445 65 L 455 65" stroke="#71b7ff" stroke-width="2" marker-end="url(#arrow)"/>

          <!-- Step 4 -->
          <rect x="460" y="20" width="130" height="90" rx="6" fill="#121721" stroke="#71b7ff" stroke-width="2"/>
          <text x="525" y="55" fill="#ffffff" font-family="sans-serif" font-size="12" font-weight="bold" text-anchor="middle">4. Document</text>
          <text x="525" y="75" fill="#96cbff" font-family="sans-serif" font-size="10" text-anchor="middle">Knowledge Base</text>
          <text x="525" y="90" fill="#96cbff" font-family="sans-serif" font-size="10" text-anchor="middle">&amp; User Confirmation</text>

          <defs>
            <marker id="arrow" viewBox="0 0 10 10" refX="5" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
              <path d="M 0 0 L 10 5 L 0 10 z" fill="#71b7ff" />
            </marker>
          </defs>
        </svg>
        <figcaption>Figure 1: Structured CompTIA and ITIL-aligned 4-step Incident Triage and Resolution Process.</figcaption>
      </figure>
    </section>

    <!-- Institutional Experience & Technical Accomplishments -->
    <section id="experience" aria-labelledby="heading-experience">
      <h2 id="heading-experience">Institutional Experience &amp; Technical Accomplishments</h2>
      <p class="muted-text">
        Demonstrated end-user support, technical documentation, customer satisfaction, and network/data security skills across prominent healthcare, academic, and cultural organizations:
      </p>

      <!-- 1. Per Scholas -->
      <article class="timeline-item">
        <h3>Per Scholas Philadelphia | AI-Powered IT Support Trainee &amp; Cohort Vice President</h3>
        <p class="timeline-meta">Philadelphia, PA | October 2026</p>
        <ul>
          <li>Completing 600+ hours of intensive hands-on technical training covering hardware disassembly, networking configuration, OS administration, and cybersecurity fundamentals.</li>
          <li>Earned <strong>CompTIA A+</strong> certification; performed physical break/fix support on personal and desktop hardware, establishing hardware asset tracking protocols.</li>
          <li>Elected Cohort Vice President, facilitating peer technical learning and practicing ITIL-based incident triage and customer communication.</li>
          <li>Reference: <a href="https://perscholas.org/" target="_blank" rel="noopener noreferrer">Per Scholas Official Site</a></li>
        </ul>
      </article>

      <!-- 2. Children's Hospital of Philadelphia (CHOP) -->
      <article class="timeline-item">
        <h3>Children's Hospital of Philadelphia (CHOP) | Research Assistant</h3>
        <p class="timeline-meta">Philadelphia, PA | June 2021 – July 2022</p>
        <ul>
          <li>Delivered direct technical assistance and audiovisual troubleshooting for non-technical clinical staff in a fast-paced healthcare environment.</li>
          <li>Resolved end-user technology issues promptly while strictly maintaining HIPAA compliance, data privacy, and hospital information security standards.</li>
          <li>Reference: <a href="https://www.chop.edu/" target="_blank" rel="noopener noreferrer">Children's Hospital of Philadelphia</a></li>
        </ul>
      </article>

      <!-- 3. Tutor.com -->
      <article class="timeline-item">
        <h3>Tutor.com | Tutor</h3>
        <p class="timeline-meta">Remote | July 2023 – May 2026</p>
        <ul>
          <li>Supported over 1,400 users with remote technical and writing guidance, achieving a 95% overall customer satisfaction rating.</li>
          <li>Translated complex technical and formatting concepts into accessible, easy-to-understand end-user instructions.</li>
          <li>Reference: <a href="https://www.tutor.com/" target="_blank" rel="noopener noreferrer">Tutor.com Official Site</a></li>
        </ul>
      </article>

      <!-- 4. Pennsylvania Horticultural Society -->
      <article class="timeline-item">
        <h3>Pennsylvania Horticultural Society | Special Project Coordinator</h3>
        <p class="timeline-meta">Philadelphia, PA | January 2021 – March 2023</p>
        <ul>
          <li>Organized and hosted technical and community workshops, building key client relationships across 25 partner groups.</li>
          <li>Scraped websites to construct a comprehensive web archive, organizing 100% of the mid-sized organization's digital web assets.</li>
          <li>Reference: <a href="https://phsonline.org/" target="_blank" rel="noopener noreferrer">Pennsylvania Horticultural Society</a></li>
        </ul>
      </article>

      <!-- 5. Berkshire Oral History Center / Monterey Library -->
      <article class="timeline-item">
        <h3>Monterey Library &amp; Berkshire Oral History Center | Oral Historian &amp; Tech Administrator</h3>
        <p class="timeline-meta">Monterey, MA | May 2017 – August 2021</p>
        <ul>
          <li>Designed local data storage architecture, accelerating digital retrieval operations by 50%.</li>
          <li>Migrated legacy archival assets to Network-Attached Storage (NAS) hardware and performed 100% of local area network troubleshooting.</li>
          <li>Reference: <a href="https://www.montereylibrary.org/" target="_blank" rel="noopener noreferrer">Monterey Library</a></li>
        </ul>
      </article>

      <!-- 6. Elfreth's Alley Museum -->
      <article class="timeline-item">
        <h3>Elfreth's Alley Museum | Museum Operations Assistant</h3>
        <p class="timeline-meta">Philadelphia, PA | 2020</p>
        <ul>
          <li>Cleansed, validated, and normalized marketing and operational datasets during critical system platform transitions.</li>
          <li>Implemented digital accessibility standards and SEO best practices; authored technical scripts for an educational podcast reaching top-tier listenership.</li>
          <li>Reference: <a href="https://www.elfrethsalley.org/" target="_blank" rel="noopener noreferrer">Elfreth's Alley Museum</a></li>
        </ul>
      </article>

      <!-- 7. American Philosophical Society -->
      <article class="timeline-item">
        <h3>American Philosophical Society | Historical Meteorological Fellow</h3>
        <p class="timeline-meta">Philadelphia, PA | 2020</p>
        <ul>
          <li>Transcribed and structured complex historical datasets into standardized digital formats.</li>
          <li>Designed accessible virtual exhibits incorporating strict WCAG alt-text compliance and metadata documentation.</li>
          <li>Reference: <a href="https://www.amphilsoc.org/" target="_blank" rel="noopener noreferrer">American Philosophical Society</a></li>
        </ul>
      </article>

      <!-- 8. Philip and Muriel Berman Museum of Art -->
      <article class="timeline-item">
        <h3>Philip and Muriel Berman Museum of Art | Museum Assistant</h3>
        <p class="timeline-meta">Collegeville, PA | August 2018 – May 2019</p>
        <ul>
          <li>Audited and updated digital inventory records for over 8,500 collection items in a database system ahead of strict accreditation deadlines.</li>
          <li>Managed end-user communications and phone inquiries, providing clear, courteous customer support to high-volume museum visitors.</li>
          <li>Reference: <a href="https://www.ursinus.edu/berman/" target="_blank" rel="noopener noreferrer">Berman Museum of Art</a></li>
        </ul>
      </article>

      <!-- 9. Bidwell House Museum -->
      <article class="timeline-item">
        <h3>Bidwell House Museum | Docent &amp; Technical Manual Author</h3>
        <p class="timeline-meta">Monterey, MA | July 2010 – April 2019</p>
        <ul>
          <li>Authored and revised the institution's comprehensive docent technical training manual, streamlining staff onboarding and procedural consistency.</li>
          <li>Reference: <a href="https://www.bidwellhousemuseum.org/" target="_blank" rel="noopener noreferrer">Bidwell House Museum</a></li>
        </ul>
      </article>

      <!-- 10. Temple University & Ursinus College Education Summary (Cross-referenced below) -->
    </section>

    <!-- Education Section -->
    <section id="education" aria-labelledby="heading-education">
      <h2 id="heading-education">Education &amp; Academic Background</h2>

      <!-- Temple University -->
      <div class="timeline-item">
        <h3>Temple University | Master of Arts (MA) in Public History</h3>
        <p class="timeline-meta">Philadelphia, PA | Graduated May 2021</p>
        <p>Thesis: <em>Growing Open Data: A Guide to Making Open Historic Data for Community Gardens</em> (Focused on data architecture, dataset accessibility, and open-source documentation).</p>
        <p>Reference: <a href="https://www.temple.edu/" target="_blank" rel="noopener noreferrer">Temple University Official Site</a></p>
      </div>

      <!-- Ursinus College -->
      <div class="timeline-item">
        <h3>Ursinus College | Bachelor of Arts (BA) in History</h3>
        <p class="timeline-meta">Collegeville, PA | Graduated May 2019</p>
        <p>Relevant Coursework: Introduction to Computer Science, Digital Entrepreneurship.</p>
        <p>Reference: <a href="https://www.ursinus.edu/" target="_blank" rel="noopener noreferrer">Ursinus College Official Site</a></p>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Joe Makuc. Built with semantic HTML5 &amp; WCAG 2.1 AAA high-contrast CSS.</p>
    <p>
      Connect via <a href="https://www.linkedin.com/in/joe-makuc/" target="_blank" rel="noopener noreferrer">LinkedIn</a> or review code repositories on <a href="https://github.com/josephvmakuc" target="_blank" rel="noopener noreferrer">GitHub</a>.
    </p>
  </footer>

</body>
</html>

Key Technical & Design Features

    WCAG 2.1 AAA Accessibility Compliance:
