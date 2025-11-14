:root {
  --bg: #050c1a;
  --bg-alt: #0b1324;
  --card: #101827;
  --accent: #f97316;   /* orange */
  --accent-soft: rgba(249, 115, 22, 0.12);
  --text: #f9fafb;
  --muted: #9ca3af;
  --border-subtle: #1f2933;
  --container-width: 1120px;
  --radius-lg: 18px;
  --shadow-soft: 0 18px 40px rgba(0, 0, 0, 0.45);
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: "Poppins", system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
  background: radial-gradient(circle at top left, #111827 0, #020617 55%);
  color: var(--text);
}

/* Layout helpers */

.container {
  max-width: var(--container-width);
  margin: 0 auto;
  padding: 0 1.5rem;
}

.section {
  padding: 5rem 0;
}

.section-alt {
  background: linear-gradient(180deg, #020617 0, #050c1a 100%);
}

.section-inner {
  display: flex;
  flex-direction: column;
  gap: 2.5rem;
}

.section-header {
  max-width: 640px;
}

.section-header h2 {
  margin: 0 0 0.75rem;
  font-size: 2.1rem;
}

.section-header p {
  margin: 0;
  color: var(--muted);
}

/* Header / Nav */

.site-header {
  position: sticky;
  top: 0;
  z-index: 50;
  backdrop-filter: blur(18px);
  background: rgba(3, 7, 18, 0.85);
  border-bottom: 1px solid rgba(148, 163, 184, 0.12);
}

.header-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 4rem;
}

.logo {
  font-weight: 600;
  letter-spacing: 0.03em;
}

.nav {
  display: flex;
  gap: 1.5rem;
  font-size: 0.95rem;
}

.nav a {
  color: var(--muted);
  text-decoration: none;
  position: relative;
}

.nav a::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -0.3rem;
  width: 0;
  height: 2px;
  background: var(--accent);
  transition: width 0.2s ease-out;
}

.nav a:hover {
  color: var(--text);
}

.nav a:hover::after {
  width: 100%;
}

/* Mobile nav toggle */

.nav-toggle {
  display: none;
  border: none;
  background: none;
  color: var(--text);
  font-size: 1.4rem;
}

/* Hero */

.hero {
  padding: 5rem 0 4rem;
}

.hero-inner {
  display: grid;
  grid-template-columns: minmax(0, 3fr) minmax(0, 2.2fr);
  align-items: center;
  gap: 3.5rem;
}

.hero-text h1 {
  font-size: clamp(2.4rem, 3.3vw, 3.2rem);
  margin: 0 0 1.2rem;
}

.hero-subtitle {
  margin: 0 0 1.8rem;
  color: var(--muted);
  max-width: 560px;
}

.eyebrow {
  text-transform: uppercase;
  font-size: 0.8rem;
  letter-spacing: 0.12em;
  color: var(--accent);
  margin-bottom: 0.7rem;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.9rem;
}

.hero-media {
  display: flex;
  justify-content: center;
}

.hero-image-frame {
  border-radius: 32px;
  overflow: hidden;
  box-shadow: var(--shadow-soft);
  border: 1px solid rgba(148, 163, 184, 0.3);
}

.hero-image-frame img {
  display: block;
  width: 100%;
  height: auto;
}

/* Buttons */

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.75rem 1.6rem;
  border-radius: 999px;
  border: 1px solid transparent;
  font-size: 0.95rem;
  cursor: pointer;
  text-decoration: none;
  transition: transform 0.15s ease-out, box-shadow 0.15s ease-out, background 0.15s ease-out, color 0.15s ease-out;
}

.btn.primary {
  background: var(--accent);
  color: #020617;
  box-shadow: 0 12px 30px rgba(249, 115, 22, 0.5);
}

.btn.primary:hover {
  transform: translateY(-1px);
  box-shadow: 0 16px 40px rgba(249, 115, 22, 0.6);
}

.btn.ghost {
  background: transparent;
  border-color: rgba(148, 163, 184, 0.5);
  color: var(--text);
}

.btn.ghost:hover {
  border-color: var(--accent);
}

/* About */

.about-inner {
  display: grid;
  grid-template-columns: minmax(0, 2.1fr) minmax(0, 3fr);
  gap: 2.5rem;
  align-items: center;
}

.about-photo img {
  width: 100%;
  border-radius: 28px;
  object-fit: cover;
  border: 1px solid rgba(148, 163, 184, 0.3);
  box-shadow: var(--shadow-soft);
}

.about-text h2 {
  margin-top: 0;
}

.about-text p {
  color: var(--muted);
}

/* Skills */

.skill-grid {
  margin-top: 1.5rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.skill-chip {
  padding: 0.35rem 0.75rem;
  border-radius: 999px;
  background: rgba(15, 23, 42, 0.9);
  border: 1px solid rgba(148, 163, 184, 0.4);
  font-size: 0.8rem;
  color: var(--muted);
}

/* Cards & grids */

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5rem;
}

.card {
  background: radial-gradient(circle at top left, #111827 0, #020617 70%);
  border-radius: var(--radius-lg);
  padding: 1.5rem;
  border: 1px solid var(--border-subtle);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.6);
  position: relative;
  overflow: hidden;
}

.card h3 {
  margin: 0 0 0.5rem;
}

.card p {
  margin: 0 0 0.75rem;
  color: var(--muted);
}

.card-meta {
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.09em;
  color: #9ca3af;
}

.card-link {
  font-size: 0.9rem;
  color: var(--accent);
  text-decoration: none;
}

.card-link:hover {
  text-decoration: underline;
}

/* Services */

.services-grid .service-card ul {
  padding-left: 1.2rem;
  margin: 0.75rem 0 0;
  color: var(--muted);
  font-size: 0.9rem;
}

/* Contact */

.contact-inner {
  max-width: 720px;
}

.contact-form {
  margin-top: 1.5rem;
  background: #020617;
  padding: 1.5rem;
  border-radius: var(--radius-lg);
  border: 1px solid rgba(148, 163, 184, 0.3);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.6);
}

.form-row {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.form-field {
  flex: 1;
  display: flex;
  flex-direction: column;
  margin-bottom: 1rem;
}

.form-field label {
  font-size: 0.85rem;
  color: var(--muted);
  margin-bottom: 0.3rem;
}

.form-field input,
.form-field textarea {
  background: #020617;
  border-radius: 12px;
  border: 1px solid rgba(148, 163, 184, 0.5);
  padding: 0.6rem 0.75rem;
  color: var(--text);
  font-family: inherit;
  font-size: 0.95rem;
}

.form-field input:focus,
.form-field textarea:focus {
  outline: none;
  border-color: var(--accent);
}

.contact-links {
  margin-top: 1.5rem;
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.contact-links a {
  color: var(--muted);
  text-decoration: none;
  font-size: 0.9rem;
}

.contact-links a:hover {
  color: var(--accent);
}

/* Footer */

.site-footer {
  border-top: 1px solid rgba(148, 163, 184, 0.2);
  padding: 1.3rem 0 1.6rem;
  background: #020617;
}

.footer-inner {
  text-align: center;
  font-size: 0.8rem;
  color: var(--muted);
}

/* Responsive */

@media (max-width: 880px) {
  .hero-inner {
    grid-template-columns: 1fr;
  }

  .about-inner {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 720px) {
  .header-inner {
    gap: 0.75rem;
  }

  .nav {
    position: absolute;
    top: 4rem;
    right: 0;
    left: 0;
    padding: 0.75rem 1.5rem 1.4rem;
    flex-direction: column;
    gap: 0.75rem;
    background: rgba(3, 7, 18, 0.97);
    border-bottom: 1px solid rgba(148, 163, 184, 0.2);
    transform: translateY(-150%);
    opacity: 0;
    pointer-events: none;
    transition: transform 0.18s ease-out, opacity 0.18s ease-out;
  }

  .nav.nav-open {
    transform: translateY(0);
    opacity: 1;
    pointer-events: auto;
  }

  .nav-toggle {
    display: block;
  }
}
