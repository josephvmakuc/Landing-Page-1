<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="IT Career Portfolio for Joe Makuc: IT Support Specialist & Aspiring System Administrator. Features 600+ hours hands-on hardware/networking training at Per Scholas, healthcare IT experience at CHOP, 10+ years customer satisfaction experience, and data architecture expertise.">
  <meta name="author" content="Joe Makuc">
  <meta name="robots" content="index, follow">

  <!-- Open Graph / Social Media SEO -->
  <meta property="og:title" content="Joe Makuc | IT Career Portfolio & System Administration Roadmap">
  <meta property="og:description" content="IT Career Portfolio demonstrating Tier 1/2 technical support expertise, network fundamentals, healthcare IT communications, and a path toward Systems Administration.">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://josephvmakuc.github.io/">

  <title>Joe Makuc | IT Career Portfolio & System Administration Roadmap</title>

  <!-- Schema.org Structured Data (SEO Person Schema) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Joe Makuc",
    "jobTitle": "Helpdesk Specialist & Aspiring System Administrator",
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
      "Helpdesk Support",
      "Endpoint Troubleshooting",
      "Systems Administration",
      "Windows 10/11",
      "Ubuntu Linux",
      "TCP/IP Networking",
      "DHCP & DNS",
      "Healthcare IT Support",
      "Data Architecture",
      "Active Directory",
      "WCAG Accessibility"
    ]
  }
  </script>

  <style>
    /* CSS Custom Properties for Minimalist Dark Aesthetic (GitHub Palette) */
    :root {
      --bg-color: #0d1117;
      --card-bg: #161b22;
      --border-color: #30363d;
      --text-main: #f0f6fc;
      --text-muted: #8b949e;
      --accent-color: #58a6ff;
      --accent-hover: #79c0ff;
      --tag-bg: #21262d;
      --focus-ring: #1f6beb;
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
      top: -40px;
      left: 0;
      background: var(--accent-color);
      color: #000;
      padding: 8px 16px;
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
      outline: 3px solid var(--accent-hover);
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
      border-bottom: 1px solid var(--border-color);
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
      text-underline-offset: 3px;
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
      font-weight: 500;
      font-size: 0.95rem;
      color: var(--text-muted);
    }

    nav a:hover, nav a:focus {
      color: var(--accent-color);
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
      padding: 0.25rem 0.75rem;
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
      padding: 0.5rem 1rem;
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      color: var(--text-main);
      text-decoration: none;
      border-radius: 6px;
      font-size: 0.9rem;
      font-weight: 500;
      transition: background-color 0.2s ease, border-color 0.2s ease;
    }

    .btn:hover, .btn:focus {
      background-color: var(--tag-bg);
      border-color: var(--text-muted);
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
      color: var(--text-muted);
      font-size: 0.8rem;
      padding: 0.2rem 0.55rem;
      border-radius: 4px;
    }

    /* Timeline & Experience Items */
    .timeline-item {
      margin-bottom: 1.75rem;
      padding-left: 1rem;
      border-left: 2px solid var(--border-color);
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

  <!-- Accessible Skip Link for Screen Readers & Keyboard Users -->
  <a href="#main" class="skip-link">Skip to main content</a>

  <!-- Top Navigation -->
  <nav aria-label="Main Navigation">
    <ul>
      <li><a href="#summary">Summary</a></li>
      <li><a href="#skills">Technical Skills</a></li>
      <li><a href="#roadmap">Career Roadmap</a></li>
      <li><a href="#experience">Institutional Experience</a></li>
      <li><a href="#education">Education & Credentials</a></li>
    </ul>
  </nav>

  <!-- Hero Header -->
  <header>
    <span class="hero-badge">CompTIA A+ Certified | Helpdesk &amp; Endpoint Technician</span>
    <h1>Joe Makuc</h1>
    <p class="muted-text">
      Helpdesk Specialist &amp; Aspiring System Administrator | Philadelphia, PA
    </p>
    <p>
      Success-driven IT technician with CompTIA A+ certification, 600+ hours of hands-on training at Per Scholas, and 10+ years of customer service experience. Combines Tier 1/2 endpoint troubleshooting acumen with healthcare IT support experience at Children's Hospital of Philadelphia and data architecture expertise, building toward advanced system administration.
    </p>
    
    <div class="social-links">
      <a href="https://www.linkedin.com/in/joe-makuc/" class="btn" target="_blank" rel="noopener noreferrer" aria-label="Joe Makuc's LinkedIn Profile (opens in a new tab)">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-.5 15.5v-5.3a3.26 3.26 0 0 0-3.26-3.26c-.85 0-1.84.52-2.28 1.3v-1.11h-2.79v8.37h2.79v-4.93c0-.77.62-1.4 1.39-1.4a1.4 1.4 0 0 1 1.4 1.4v4.93h2.75M6.88 8.56a1.68 1.68 0 0 0 1.68-1.68c0-.93-.75-1.69-1.68-1.69a1.69 1.69 0 0 0-1.69 1.69c0 .93.76 1.68 1.69 1.68m1.39 9.94v-8.37H5.5v8.37h2.77z"/></svg>
        LinkedIn Profile
      </a>
      <a href="https://github.com/josephvmakuc" class="btn" target="_blank" rel="noopener noreferrer" aria-label="Joe Makuc's GitHub Repository (opens in a new tab)">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2A10 10 0 0 0 2 12c0 4.42 2.87 8.17 6.84 9.5.5.08.66-.23.66-.5v-1.69c-2.77.6-3.36-1.34-3.36-1.34-.46-1.16-1.11-1.47-1.11-1.47-.91-.62.07-.6.07-.6 1 .07 1.53 1.03 1.53 1.03.87 1.52 2.34 1.07 2.91.83.1-.65.35-1.09.63-1.34-2.22-.25-4.55-1.11-4.55-4.92 0-1.11.38-2 1.03-2.71-.1-.25-.45-1.29.1-2.64 0 0 .84-.27 2.75 1.02.79-.22 1.65-.33 2.5-.33.85 0 1.71.11 2.5.33 1.91-1.29 2.75-1.02 2.75-1.02.55 1.35.2 2.39.1 2.64.65.71 1.03 1.6 1.03 2.71 0 3.82-2.34 4.66-4.57 4.91.36.31.69.92.69 1.85V21c0 .27.16.59.67.5C19.14 20.16 22 16.42 22 12A10 10 0 0 0 12 2z"/></svg>
        GitHub Repositories
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
      <h2 id="heading-summary">Professional Profile</h2>
      <p>
        My goal is to deliver reliable, empathetic technical support at the helpdesk and endpoint support levels while systematically advancing into <strong>Systems Administration and Infrastructure Operations</strong>. Having authored technical documentation for six organizations and supported over 1,400 users with a 95% satisfaction rating, I connect technical troubleshooting with exceptional customer care, technical writing, and compliance.
      </p>
    </section>

    <!-- Technical Skills Matrix -->
    <section id="skills" aria-labelledby="heading-skills">
      <h2 id="heading-skills">Technical Core Competencies</h2>
      <div class="grid">
        <article class="card">
          <h3>Hardware &amp; Endpoint Support</h3>
          <p class="muted-text">Break/fix repair, peripheral installation, cable management, ESD prevention, printer deployment, BIOS/UEFI configuration, desktop component diagnostics.</p>
          <div class="tag-container">
            <span class="tag">PC Repair</span>
            <span class="tag">BIOS/UEFI</span>
            <span class="tag">ESD Safety</span>
            <span class="tag">Break/Fix</span>
          </div>
        </article>

        <article class="card">
          <h3>Operating Systems &amp; Software</h3>
          <p class="muted-text">Windows 10/11, Ubuntu Linux, macOS, Android, Active Directory Domain Services, ServiceNow ITSM, Google Suite, Microsoft Office, Zoom.</p>
          <div class="tag-container">
            <span class="tag">Windows 11</span>
            <span class="tag">Ubuntu Linux</span>
            <span class="tag">Active Directory</span>
            <span class="tag">ServiceNow</span>
          </div>
        </article>

        <article class="card">
          <h3>Networking &amp; Infrastructure</h3>
          <p class="muted-text">Cloud management, DHCP, DNS, IP addressing, VPN, WAN/LAN technology, TCP/IP, NAS hardware data migration.</p>
          <div class="tag-container">
            <span class="tag">DNS/DHCP</span>
            <span class="tag">TCP/IP</span>
            <span class="tag">NAS Migration</span>
            <span class="tag">VPN</span>
          </div>
        </article>

        <article class="card">
          <h3>Data Security &amp; Documentation</h3>
          <p class="muted-text">Healthcare information security, technical writing across 6 organizations, web archiving, data architecture, HTML/CSS, WCAG accessibility.</p>
          <div class="tag-container">
            <span class="tag">Info Security</span>
            <span class="tag">Tech Writing</span>
            <span class="tag">HTML/CSS</span>
            <span class="tag">WCAG 2.1</span>
          </div>
        </article>
      </div>
    </section>

    <!-- Career Roadmap -->
    <section id="roadmap" aria-labelledby="heading-roadmap">
      <h2 id="heading-roadmap">Career Progression Strategy</h2>
      <p>
        Building upon a foundation of user-facing helpdesk and endpoint support, my developmental trajectory bridges endpoint troubleshooting with systems administration:
      </p>
      
      <div class="timeline-item">
        <h3>Phase 1: Helpdesk &amp; Endpoint Technician Role</h3>
        <p class="timeline-meta">Current Focus | Entry Horizon</p>
        <p>Mastering Tier 1/2 ticket resolution using CompTIA Troubleshooting Methodology, maintaining hardware break/fix accuracy, managing Active Directory user accounts and group permissions, and writing clear end-user technical documentation.</p>
      </div>

      <div class="timeline-item">
        <h3>Phase 2: Systems &amp; Network Administration</h3>
        <p class="timeline-meta">Target Trajectory | Mid-Term Horizon</p>
        <p>Expanding capabilities in Windows Server/Linux server environment management, deployment automation tools, cloud infrastructure maintenance, group policies (GPOs), and network security protocol implementation.</p>
      </div>
    </section>

    <!-- Institutional Experience & Technical Accomplishments -->
    <section id="experience" aria-labelledby="heading-experience">
      <h2 id="heading-experience">Institutional Experience &amp; Technical Accomplishments</h2>
      <p class="muted-text">
        Demonstrated technical support, customer satisfaction, data management, and public-facing communication skills across prominent healthcare, educational, and cultural institutions:
      </p>

      <!-- Per Scholas -->
      <article class="timeline-item">
        <h3>Per Scholas Philadelphia | AI-Powered IT Support Trainee &amp; Cohort Vice President</h3>
        <p class="timeline-meta">Philadelphia, PA | Anticipated October 2026</p>
        <ul>
          <li>Completing 600+ hours of intensive hands-on technical training covering PC maintenance, networking, and security.</li>
          <li>Earned <strong>CompTIA A+</strong> certification; performed break/fix support for personal and desktop computers, developing comprehensive asset inventory records.</li>
          <li>Coordinated colleagues as cohort Vice President, practicing ITIL-based processes for Incident, Problem, Change, and Service Request Management.</li>
          <li>Reference: <a href="https://perscholas.org/" target="_blank" rel="noopener noreferrer">Per Scholas Official Website</a></li>
        </ul>
      </article>

      <!-- Tutor.com -->
      <article class="timeline-item">
        <h3>Tutor.com | Tutor</h3>
        <p class="timeline-meta">Remote | July 2023 – May 2026</p>
        <ul>
          <li>Tutored professional writing and supported 1,400 users with technical issues to a 95% satisfaction rating.</li>
          <li>Reference: <a href="https://www.tutor.com/" target="_blank" rel="noopener noreferrer">Tutor.com Official Website</a></li>
        </ul>
      </article>

      <!-- Pennsylvania Horticultural Society -->
      <article class="timeline-item">
        <h3>Pennsylvania Horticultural Society | Special Project Coordinator</h3>
        <p class="timeline-meta">Philadelphia, PA | January 2021 – March 2023</p>
        <ul>
          <li>Planned and hosted technical workshops that established enduring relationships with 25 clients.</li>
          <li>Scraped websites to form a web archive, organizing 100% of the mid-sized organization's web assets.</li>
          <li>Reference: <a href="https://phsonline.org/" target="_blank" rel="noopener noreferrer">Pennsylvania Horticultural Society</a></li>
        </ul>
      </article>

      <!-- Children's Hospital of Philadelphia (CHOP) -->
      <article class="timeline-item">
        <h3>Children's Hospital of Philadelphia (CHOP) | Research Assistant</h3>
        <p class="timeline-meta">Philadelphia, PA | June 2021 – July 2022</p>
        <ul>
          <li>Explained audiovisual and digital technology issues to non-technical staff in a clinical healthcare setting, resolving end-user problems efficiently.</li>
          <li>Handled customer and patient problems while maintaining strict information security standards and data confidentiality.</li>
          <li>Reference: <a href="https://www.chop.edu/" target="_blank" rel="noopener noreferrer">Children's Hospital of Philadelphia</a></li>
        </ul>
      </article>

      <!-- Monterey Library / Berkshire Oral History Center -->
      <article class="timeline-item">
        <h3>Monterey Library &amp; Berkshire Oral History Center | Oral Historian</h3>
        <p class="timeline-meta">Monterey, MA | May 2017 – August 2021</p>
        <ul>
          <li>Designed and implemented local data architecture, accelerating digital operations by 50%.</li>
          <li>Migrated archival data from hard drive to Network-Attached Storage (NAS) and performed 100% of network troubleshooting.</li>
          <li>Reference: <a href="https://www.montereylibrary.org/" target="_blank" rel="noopener noreferrer">Monterey Library</a></li>
        </ul>
      </article>

      <!-- Elfreth's Alley Museum -->
      <article class="timeline-item">
        <h3>Elfreth's Alley Museum | Museum Operations Assistant</h3>
        <p class="timeline-meta">Philadelphia, PA | 2020</p>
        <ul>
          <li>Cleaned, validated, and synthesized donor and marketing data across distinct platforms to support operational transitions.</li>
          <li>Devised digital accessibility and SEO tactics; authored and produced an educational podcast reaching the top 50% of podcasts by listens.</li>
          <li>Reference: <a href="https://www.elfrethsalley.org/" target="_blank" rel="noopener noreferrer">Elfreth's Alley Association</a></li>
        </ul>
      </article>

      <!-- American Philosophical Society -->
      <article class="timeline-item">
        <h3>American Philosophical Society | Historical Meteorological Fellow</h3>
        <p class="timeline-meta">Remote / Philadelphia, PA | 2020</p>
        <ul>
          <li>Transcribed, cleaned, and validated historical climate measurement datasets stored in standardized formats.</li>
          <li>Curated a virtual exhibit adhering strictly to WCAG alt-text accessibility standards and detailed dataset documentation.</li>
          <li>Reference: <a href="https://www.amphilsoc.org/" target="_blank" rel="noopener noreferrer">American Philosophical Society</a></li>
        </ul>
      </article>

      <!-- Philip and Muriel Berman Museum of Art -->
      <article class="timeline-item">
        <h3>Philip and Muriel Berman Museum of Art | Museum Assistant</h3>
        <p class="timeline-meta">Collegeville, PA | August 2018 – May 2019</p>
        <ul>
          <li>Maintained and audited collection inventory records for over 8,500 contemporary artworks in digital databases under an accreditation deadline.</li>
          <li>Managed main phone line, answered end-user inquiries, and provided prompt customer service for high-volume visitors.</li>
          <li>Reference: <a href="https://www.ursinus.edu/berman/" target="_blank" rel="noopener noreferrer">Berman Museum of Art</a></li>
        </ul>
      </article>

      <!-- Bidwell House Museum -->
      <article class="timeline-item">
        <h3>Bidwell House Museum | Docent &amp; Educational Content Author</h3>
        <p class="timeline-meta">Monterey, MA | July 2010 – April 2019</p>
        <ul>
          <li>Revised the museum's docent training manual, trained incoming docents, and maintained environmental standards for exhibition collections care.</li>
          <li>Reference: <a href="https://www.bidwellhousemuseum.org/" target="_blank" rel="noopener noreferrer">Bidwell House Museum</a></li>
        </ul>
      </article>

      <!-- Visual Element Container -->
      <figure>
        <svg width="100%" height="120" viewBox="0 0 600 120" role="img" aria-label="Diagram displaying career transition from Helpdesk and Endpoint Support to System Administration and Infrastructure Engineering">
          <rect x="10" y="20" width="260" height="80" rx="6" fill="#161b22" stroke="#30363d" stroke-width="2"/>
          <text x="140" y="55" fill="#f0f6fc" font-family="sans-serif" font-size="14" font-weight="bold" text-anchor="middle">Helpdesk &amp; Endpoint Support</text>
          <text x="140" y="75" fill="#8b949e" font-family="sans-serif" font-size="11" text-anchor="middle">Break/Fix | Active Directory | Customer Service</text>

          <path d="M 280 60 L 310 60" stroke="#58a6ff" stroke-width="3" marker-end="url(#arrow)"/>
          <defs>
            <marker id="arrow" viewBox="0 0 10 10" refX="5" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
              <path d="M 0 0 L 10 5 L 0 10 z" fill="#58a6ff" />
            </marker>
          </defs>

          <rect x="320" y="20" width="270" height="80" rx="6" fill="#161b22" stroke="#58a6ff" stroke-width="2"/>
          <text x="455" y="55" fill="#f0f6fc" font-family="sans-serif" font-size="14" font-weight="bold" text-anchor="middle">Systems Administration Trajectory</text>
          <text x="455" y="75" fill="#79c0ff" font-family="sans-serif" font-size="11" text-anchor="middle">Networking | NAS/Server Ops | Infrastructure</text>
        </svg>
        <figcaption>Figure 1: Strategic roadmap from Helpdesk &amp; Endpoint excellence to Systems Administration.</figcaption>
      </figure>
    </section>

    <!-- Education Section -->
    <section id="education" aria-labelledby="heading-education">
      <h2 id="heading-education">Education &amp; Professional Development</h2>

      <div class="timeline-item">
        <h3>Temple University | Master of Arts (MA) in Public History</h3>
        <p class="timeline-meta">Philadelphia, PA | Graduated May 2021</p>
        <p>Thesis: <em>Growing Open Data: A Guide to Making Open Historic Data for Community Gardens</em> (Focused on open historic data standards and dataset access).</p>
        <p>Selected Coursework: Archives and Manuscripts, Digital History.</p>
        <p>Reference: <a href="https://www.temple.edu/" target="_blank" rel="noopener noreferrer">Temple University Official Site</a></p>
      </div>

      <div class="timeline-item">
        <h3>Ursinus College | Bachelor of Arts (BA) in History</h3>
        <p class="timeline-meta">Collegeville, PA | Graduated May 2019</p>
        <p>Selected Coursework: Introduction to Computer Science, Digital Entrepreneurship.</p>
        <p>Reference: <a href="https://www.ursinus.edu/" target="_blank" rel="noopener noreferrer">Ursinus College Official Site</a></p>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Joe Makuc. Built with minimalist, semantic HTML5 &amp; WCAG 2.1 AAA accessible CSS.</p>
    <p>
      Connect via <a href="https://www.linkedin.com/in/joe-makuc/" target="_blank" rel="noopener noreferrer">LinkedIn</a> or view code on <a href="https://github.com/josephvmakuc" target="_blank" rel="noopener noreferrer">GitHub</a>.
    </p>
  </footer>

</body>
</html>
