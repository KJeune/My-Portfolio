<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kathiana | Web &amp; Accessible Design Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <a class="skip-link" href="#main-content">Skip to main content</a>

  <header class="site-header">
    <div class="container header-inner">
      <a class="brand-link" href="index.html">Kathiana Portfolio</a>
      <nav aria-label="Primary navigation">
        <ul class="nav-list">
          <li><a class="nav-link active" href="index.html" aria-current="page">Home</a></li>
          <li><a class="nav-link" href="projects.html">Projects</a></li>
          <li><a class="nav-link" href="about.html">About &amp; Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main-content" class="container">
    <section class="hero" aria-labelledby="hero-heading">
      <p class="eyebrow">Web Development &amp; Visual Design</p>
      <h1 id="hero-heading">Building clear, accessible, and intentional web experiences.</h1>
      <p class="hero-copy">
        I am Kathiana, a developer and designer focused on semantic HTML, accessible interfaces,
        WCAG AA contrast, and structured visual layouts.
      </p>
      <div class="hero-actions">
        <a class="btn btn-primary" href="projects.html">View Projects</a>
        <a class="btn btn-secondary" href="about.html">Get in Touch</a>
      </div>
    </section>

    <section class="section" aria-labelledby="featured-heading">
      <div class="section-header">
        <h2 id="featured-heading">Featured Work</h2>
        <p class="section-subtitle">Selected projects demonstrating accessible structure and visual clarity.</p>
      </div>

      <div class="card-grid">
        <article class="card">
          <span class="badge">Accessibility</span>
          <h3>Accessible Course Portal</h3>
          <p>
            Refactored page landmarks, form labels, and keyboard focus states to eliminate
            navigation barriers and improve screen reader clarity.
          </p>
          <a class="text-link" href="projects.html#project-portal">Read case summary →</a>
        </article>

        <article class="card">
          <span class="badge">Visual Design</span>
          <h3>Gestalt Layout System</h3>
          <p>
            Applied proximity, alignment, and similarity across responsive cards and typographic
            hierarchies for effortless scanning.
          </p>
          <a class="text-link" href="projects.html#project-gestalt">Read case summary →</a>
        </article>

        <article class="card">
          <span class="badge">Agile &amp; UX</span>
          <h3>Sprint Planning Tracker</h3>
          <p>
            Organized user stories, acceptance criteria, and milestone deliverables into a clear,
            prioritized workflow for team execution.
          </p>
          <a class="text-link" href="projects.html#project-sprint">Read case summary →</a>
        </article>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <p>&copy; 2026 Kathiana. Built with semantic HTML, CSS, and JavaScript.</p>
      <nav aria-label="Footer navigation">
        <ul class="footer-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="projects.html">Projects</a></li>
          <li><a href="about.html">About &amp; Contact</a></li>
        </ul>
      </nav>
    </div>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projects | Kathiana Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <a class="skip-link" href="#main-content">Skip to main content</a>

  <header class="site-header">
    <div class="container header-inner">
      <a class="brand-link" href="index.html">Kathiana Portfolio</a>
      <nav aria-label="Primary navigation">
        <ul class="nav-list">
          <li><a class="nav-link" href="index.html">Home</a></li>
          <li><a class="nav-link active" href="projects.html" aria-current="page">Projects</a></li>
          <li><a class="nav-link" href="about.html">About &amp; Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main-content" class="container">
    <section class="page-intro" aria-labelledby="projects-heading">
      <p class="eyebrow">Portfolio Archive</p>
      <h1 id="projects-heading">Projects &amp; Design Work</h1>
      <p class="section-subtitle">
        Each project below emphasizes semantic markup, readable contrast, and clear visual grouping.
      </p>
    </section>

    <section class="section" aria-label="Project list">
      <div class="card-grid">
        <article id="project-portal" class="card">
          <span class="badge">HTML &amp; WCAG AA</span>
          <h2>Accessible Course Portal</h2>
          <p>
            Audited landmarks, heading levels, and interactive controls so keyboard and screen
            reader users can move through modules without confusion.
          </p>
          <ul class="detail-list">
            <li><strong>Focus:</strong> Semantic landmarks &amp; contrast</li>
            <li><strong>Outcome:</strong> Zero WAVE contrast or label errors</li>
          </ul>
        </article>

        <article id="project-gestalt" class="card">
          <span class="badge">Visual Design</span>
          <h2>Gestalt Layout System</h2>
          <p>
            Structured multi-column cards using consistent spacing (proximity) and matching
            visual components (similarity) across screen sizes.
          </p>
          <ul class="detail-list">
            <li><strong>Focus:</strong> Proximity &amp; similarity principles</li>
            <li><strong>Outcome:</strong> Faster visual scanning across views</li>
          </ul>
        </article>

        <article id="project-sprint" class="card">
          <span class="badge">Project Planning</span>
          <h2>Sprint Planning Tracker</h2>
          <p>
            Structured sprint goals, task priorities, and milestone checkpoints to keep team
            deliverables clear, testable, and on schedule.
          </p>
          <ul class="detail-list">
            <li><strong>Focus:</strong> Deliverable clarity &amp; structure</li>
            <li><strong>Outcome:</strong> Clear milestone tracking &amp; handoffs</li>
          </ul>
        </article>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <p>&copy; 2026 Kathiana. Built with semantic HTML, CSS, and JavaScript.</p>
      <nav aria-label="Footer navigation">
        <ul class="footer-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="projects.html">Projects</a></li>
          <li><a href="about.html">About &amp; Contact</a></li>
        </ul>
      </nav>
    </div>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About &amp; Contact | Kathiana Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <script src="form.js" defer></script>
</head>
<body>
  <a class="skip-link" href="#main-content">Skip to main content</a>

  <header class="site-header">
    <div class="container header-inner">
      <a class="brand-link" href="index.html">Kathiana Portfolio</a>
      <nav aria-label="Primary navigation">
        <ul class="nav-list">
          <li><a class="nav-link" href="index.html">Home</a></li>
          <li><a class="nav-link" href="projects.html">Projects</a></li>
          <li><a class="nav-link active" href="about.html" aria-current="page">About &amp; Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main-content" class="container">
    <section class="page-intro" aria-labelledby="about-heading">
      <p class="eyebrow">About &amp; Contact</p>
      <h1 id="about-heading">About Kathiana</h1>
      <p class="section-subtitle">
        I create responsive, accessible websites grounded in clean semantic code, thoughtful
        color contrast, and intentional layout structure.
      </p>
    </section>

    <section class="section about-grid" aria-label="Background and contact form">
      <article class="card">
        <span class="badge">Approach</span>
        <h2>How I Build</h2>
        <p>
          Every interface starts with clear hierarchy, keyboard-friendly navigation, and accessible
          form controls. I test pages with accessibility auditing tools and color contrast checks
          to ensure content works for everyone.
        </p>
        <ul class="detail-list">
          <li><strong>Core Stack:</strong> Semantic HTML5, CSS3, JavaScript</li>
          <li><strong>Standards:</strong> WCAG AA contrast &amp; accessible forms</li>
        </ul>
      </article>

      <div class="card">
        <span class="badge">Contact</span>
        <h2>Send a Message</h2>
        <p class="form-intro">
          Fields marked with <span class="required-indicator" aria-hidden="true">*</span>
          <span class="sr-only">an asterisk</span> are required.
        </p>

        <div id="form-status" class="status-banner" role="status" aria-live="polite" hidden></div>

        <form id="contact-form" novalidate>
          <div class="form-group">
            <label for="full-name">Full Name <span class="required-indicator" aria-hidden="true">*</span></label>
            <input
              id="full-name"
              name="fullName"
              type="text"
              autocomplete="name"
              aria-describedby="full-name-error"
              required
            >
            <p id="full-name-error" class="error-text" role="alert" hidden></p>
          </div>

          <div class="form-group">
            <label for="email">Email Address <span class="required-indicator" aria-hidden="true">*</span></label>
            <input
              id="email"
              name="email"
              type="email"
              autocomplete="email"
              aria-describedby="email-error"
              required
            >
            <p id="email-error" class="error-text" role="alert" hidden></p>
          </div>

          <fieldset class="fieldset-group">
            <legend>Reason for Reaching Out <span class="required-indicator" aria-hidden="true">*</span></legend>
            <div class="choice-row">
              <input id="topic-project" name="topic" type="radio" value="Project Collaboration">
              <label for="topic-project">Project Collaboration</label>
            </div>
            <div class="choice-row">
              <input id="topic-feedback" name="topic" type="radio" value="Portfolio Feedback">
              <label for="topic-feedback">Portfolio Feedback</label>
            </div>
            <div class="choice-row">
              <input id="topic-general" name="topic" type="radio" value="General Question">
              <label for="topic-general">General Question</label>
            </div>
            <p id="topic-error" class="error-text" role="alert" hidden></p>
          </fieldset>

          <div class="form-group">
            <label for="message">Message <span class="required-indicator" aria-hidden="true">*</span></label>
            <textarea
              id="message"
              name="message"
              rows="4"
              aria-describedby="message-error"
              required
            ></textarea>
            <p id="message-error" class="error-text" role="alert" hidden></p>
          </div>

          <div class="form-group choice-row">
            <input id="copy-request" name="copyRequest" type="checkbox" value="yes">
            <label for="copy-request">Send me a confirmation summary of my inquiry</label>
          </div>

          <button class="btn btn-primary" type="submit">Submit Message</button>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <p>&copy; 2026 Kathiana. Built with semantic HTML, CSS, and JavaScript.</p>
      <nav aria-label="Footer navigation">
        <ul class="footer-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="projects.html">Projects</a></li>
          <li><a href="about.html">About &amp; Contact</a></li>
        </ul>
      </nav>
    </div>
  </footer>
</body>
</html>
:root {
  --bg-page: #F8FAFC;
  --bg-surface: #FFFFFF;
  --text-primary: #0F172A;
  --text-secondary: #334155;
  --accent: #1D4ED8;
  --accent-hover: #1E3A8A;
  --accent-soft: #EFF6FF;
  --border-color: #CBD5E1;
  --error-bg: #FEF2F2;
  --error-text: #991B1B;
  --success-bg: #ECFDF5;
  --success-text: #065F46;
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  line-height: 1.6;
  color: var(--text-primary);
  background-color: var(--bg-page);
}

.container {
  width: min(1100px, 92%);
  margin: 0 auto;
}

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}

.skip-link {
  position: absolute;
  left: -9999px;
  top: 0;
  background: var(--accent);
  color: var(--bg-surface);
  padding: 0.75rem 1rem;
  font-weight: 600;
  text-decoration: none;
  z-index: 1000;
}

.skip-link:focus {
  left: 1rem;
  top: 1rem;
}

:focus-visible {
  outline: 3px solid var(--accent);
  outline-offset: 2px;
}

/* Header & Navigation */
.site-header {
  background-color: var(--bg-surface);
  border-bottom: 1px solid var(--border-color);
  padding: 1rem 0;
}

.header-inner {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
}

.brand-link {
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--text-primary);
  text-decoration: none;
}

.nav-list {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin: 0;
  padding: 0;
}

.nav-link {
  display: inline-block;
  padding: 0.45rem 0.85rem;
  border-radius: 6px;
  color: var(--text-secondary);
  text-decoration: none;
  font-weight: 600;
}

.nav-link:hover {
  background-color: var(--accent-soft);
  color: var(--text-primary);
}

.nav-link.active {
  background-color: var(--accent);
  color: var(--bg-surface);
}

/* Hero & Sections */
.hero,
.page-intro {
  padding: 3rem 0 1.5rem;
}

.eyebrow {
  margin: 0 0 0.5rem;
  font-size: 0.875rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  color: var(--accent);
}

h1 {
  margin: 0 0 1rem;
  font-size: clamp(2rem, 4vw, 2.75rem);
  line-height: 1.2;
  color: var(--text-primary);
}

h2 {
  margin: 0 0 0.5rem;
  font-size: 1.5rem;
  line-height: 1.3;
  color: var(--text-primary);
}

h3 {
  margin: 0.5rem 0;
  font-size: 1.2rem;
  line-height: 1.35;
  color: var(--text-primary);
}

.hero-copy,
.section-subtitle {
  max-width: 65ch;
  margin: 0;
  color: var(--text-secondary);
  font-size: 1.05rem;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-top: 1.5rem;
}

/* Buttons & Links */
.btn {
  display: inline-block;
  padding: 0.7rem 1.25rem;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  border: 2px solid transparent;
  cursor: pointer;
  font-size: 1rem;
}

.btn-primary {
  background-color: var(--accent);
  color: var(--bg-surface);
}

.btn-primary:hover {
  background-color: var(--accent-hover);
}

.btn-secondary {
  background-color: var(--bg-surface);
  color: var(--accent);
  border-color: var(--accent);
}

.btn-secondary:hover {
  background-color: var(--accent-soft);
}

.text-link {
  display: inline-block;
  margin-top: 0.75rem;
  font-weight: 600;
  color: var(--accent);
  text-decoration: underline;
}

.text-link:hover {
  color: var(--accent-hover);
}

/* Cards & Grids (Gestalt Proximity & Similarity) */
.section {
  padding: 1.5rem 0 3rem;
}

.section-header {
  margin-bottom: 1.5rem;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
}

.about-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 1.75rem;
  align-items: start;
}

.card {
  background-color: var(--bg-surface);
  border: 1px solid var(--border-color);
  border-radius: 10px;
  padding: 1.5rem;
}

.card p {
  color: var(--text-secondary);
  margin: 0.5rem 0 0;
}

.badge {
  display: inline-block;
  background-color: var(--accent-soft);
  color: var(--accent);
  border: 1px solid #BFDBFE;
  font-size: 0.8rem;
  font-weight: 700;
  padding: 0.2rem 0.6rem;
  border-radius: 999px;
}

.detail-list {
  margin: 1rem 0 0;
  padding-left: 1.2rem;
  color: var(--text-secondary);
}

.detail-list li {
  margin-bottom: 0.35rem;
}

/* Accessible Form Styles */
.form-intro {
  margin: 0.5rem 0 1rem;
  color: var(--text-secondary);
  font-size: 0.95rem;
}

.required-indicator {
  color: var(--error-text);
  font-weight: 700;
}

.form-group {
  margin-bottom: 1.15rem;
}

label {
  display: block;
  font-weight: 600;
  margin-bottom: 0.35rem;
  color: var(--text-primary);
}

input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 0.65rem 0.75rem;
  font-family: inherit;
  font-size: 1rem;
  color: var(--text-primary);
  background-color: var(--bg-surface);
  border: 1.5px solid #475569;
  border-radius: 6px;
}

input[aria-invalid="true"],
textarea[aria-invalid="true"] {
  border-color: var(--error-text);
  background-color: var(--error-bg);
}

.fieldset-group {
  margin: 0 0 1.25rem;
  padding: 0.9rem 1rem;
  border: 1.5px solid var(--border-color);
  border-radius: 8px;
}

legend {
  padding: 0 0.4rem;
  font-weight: 700;
  color: var(--text-primary);
}

.choice-row {
  display: flex;
  align-items: center;
  gap: 0.55rem;
  margin-bottom: 0.5rem;
}

.choice-row:last-of-type {
  margin-bottom: 0;
}

.choice-row label {
  margin: 0;
  font-weight: 500;
  cursor: pointer;
}

.choice-row input[type="radio"],
.choice-row input[type="checkbox"] {
  width: 1.1rem;
  height: 1.1rem;
  accent-color: var(--accent);
  cursor: pointer;
}

.error-text {
  margin: 0.4rem 0 0;
  padding: 0.4rem 0.6rem;
  border-radius: 6px;
  background-color: var(--error-bg);
  color: var(--error-text);
  font-size: 0.9rem;
  font-weight: 600;
}

.status-banner {
  margin-bottom: 1.25rem;
  padding: 0.85rem 1rem;
  border-radius: 8px;
  font-weight: 600;
}

.status-banner.error {
  background-color: var(--error-bg);
  color: var(--error-text);
  border: 1px solid #FCA5A5;
}

.status-banner.success {
  background-color: var(--success-bg);
  color: var(--success-text);
  border: 1px solid #6EE7B7;
}

/* Footer */
.site-footer {
  background-color: var(--bg-surface);
  border-top: 1px solid var(--border-color);
  padding: 1.5rem 0;
  margin-top: 2rem;
}

.footer-inner {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
}

.footer-inner p {
  margin: 0;
  color: var(--text-secondary);
  font-size: 0.95rem;
}

.footer-links {
  list-style: none;
  display: flex;
  gap: 1.25rem;
  margin: 0;
  padding: 0;
}

.footer-links a {
  color: var(--text-secondary);
  font-weight: 600;
  text-decoration: none;
}

.footer-links a:hover {
  color: var(--accent);
  text-decoration: underline;
}
document.addEventListener("DOMContentLoaded", () => {
  const form = document.getElementById("contact-form");
  if (!form) return;

  const statusBanner = document.getElementById("form-status");
  const nameInput = document.getElementById("full-name");
  const emailInput = document.getElementById("email");
  const messageInput = document.getElementById("message");
  const topicInputs = Array.from(form.querySelectorAll('input[name="topic"]'));
  const copyCheckbox = document.getElementById("copy-request");

  const nameError = document.getElementById("full-name-error");
  const emailError = document.getElementById("email-error");
  const topicError = document.getElementById("topic-error");
  const messageError = document.getElementById("message-error");

  function setFieldError(input, errorEl, message) {
    if (input) {
      input.setAttribute("aria-invalid", "true");
    }
    errorEl.textContent = message;
    errorEl.hidden = false;
  }

  function clearFieldError(input, errorEl) {
    if (input) {
      input.removeAttribute("aria-invalid");
    }
    errorEl.textContent = "";
    errorEl.hidden = true;
  }

  function isValidEmail(value) {
    return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(value.trim());
  }

  form.addEventListener("submit", (event) => {
    event.preventDefault();

    let firstInvalidElement = null;
    let errorCount = 0;

    // 1. Validate Full Name
    if (!nameInput.value.trim()) {
      setFieldError(nameInput, nameError, "Please enter your full name.");
      if (!firstInvalidElement) firstInvalidElement = nameInput;
      errorCount += 1;
    } else {
      clearFieldError(nameInput, nameError);
    }

    // 2. Validate Email Address
    if (!emailInput.value.trim()) {
      setFieldError(emailInput, emailError, "Please enter your email address.");
      if (!firstInvalidElement) firstInvalidElement = emailInput;
      errorCount += 1;
    } else if (!isValidEmail(emailInput.value)) {
      setFieldError(emailInput, emailError, "Please enter a valid email address (example: name@domain.com).");
      if (!firstInvalidElement) firstInvalidElement = emailInput;
      errorCount += 1;
    } else {
      clearFieldError(emailInput, emailError);
    }

    // 3. Validate Topic Radio Group
    const selectedTopic = topicInputs.find((radio) => radio.checked);
    if (!selectedTopic) {
      setFieldError(null, topicError, "Please select a reason for reaching out.");
      if (!firstInvalidElement) firstInvalidElement = topicInputs[0];
      errorCount += 1;
    } else {
      clearFieldError(null, topicError);
    }

    // 4. Validate Message
    if (!messageInput.value.trim()) {
      setFieldError(messageInput, messageError, "Please enter a message before submitting.");
      if (!firstInvalidElement) firstInvalidElement = messageInput;
      errorCount += 1;
    } else {
      clearFieldError(messageInput, messageError);
    }

    if (errorCount > 0) {
      statusBanner.className = "status-banner error";
      statusBanner.textContent = `Please fix ${errorCount} highlighted ${errorCount === 1 ? "field" : "fields"} below before submitting.`;
      statusBanner.hidden = false;
      if (firstInvalidElement) {
        firstInvalidElement.focus();
      }
      return;
    }

    // Success state in DOM
    const summaryNote = copyCheckbox.checked
      ? " A confirmation summary preference was noted."
      : "";
    statusBanner.className = "status-banner success";
    statusBanner.textContent = `Thank you, ${nameInput.value.trim()}. Your message regarding "${selectedTopic.value}" has been validated and recorded.${summaryNote}`;
    statusBanner.hidden = false;
    statusBanner.focus();

    form.reset();
  });
});
Markdown
# Kathiana Web & Accessible Design Portfolio

This repository contains the three-page portfolio website (`index.html`, `projects.html`, and `about.html`) built for **Project Milestone 3: Accessible & Designed** and published with GitHub Pages.

## WAVE Accessibility Fixes (One Sentence per Fix)

- Added a skip-to-content link and clear `<header>`, `<nav>`, `<main>`, and `<footer>` landmarks on all three pages so keyboard and assistive-technology users can jump directly to main content and navigate landmarks reliably.
- Replaced any missing or decorative image/icon ambiguity with explicit text labels, accessible `<label>` associations on every form input, and `<fieldset>`/`<legend>` groupings so screen readers announce each control's purpose.
- Configured accessible inline DOM validation messages (`role="alert"` and `aria-live="polite"`) instead of browser `alert()` popups so form errors are clearly announced and stay visible next to the relevant fields.

## WCAG AA Color Contrast Verification

All text and background color combinations across `index.html`, `projects.html`, and `about.html` were checked using the **WebAIM Contrast Checker** to meet or exceed **WCAG AA** thresholds (**4.5:1** for normal text and **3:1** for large text/UI components):

- `#0F172A` (primary text/headings) on `#F8FAFC` (page background) and `#FFFFFF` (cards): passes WCAG AA well above 4.5:1.
- `#334155` (body copy/descriptions) on `#F8FAFC` and `#FFFFFF`: passes WCAG AA well above 4.5:1.
- `#1D4ED8` (primary buttons, active navigation pill, links, and badges) paired with `#FFFFFF` text or `#EFF6FF` soft background: passes WCAG AA contrast requirements.
- `#991B1B` (form error text) on `#FEF2F2` (error highlight background): passes WCAG AA contrast for clear error readability.

## Gestalt Principles Applied

- **Proximity**: I used proximity to group related project details and form controls together inside padded cards and fieldsets while separating distinct cards and sections with clear spacing.
- **Similarity**: I used similarity by styling cards, badges, typography, and interactive controls consistently across all three pages so visitors immediately recognize elements with similar roles.
