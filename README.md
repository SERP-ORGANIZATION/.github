<!-- 🔥 Waving CSS Animations Setup -->
<style>
  /* 🌊 Title එක Wave වෙන්න (Floating Effect) */
  .floating-title {
    animation: wave-text 3s ease-in-out infinite alternate;
    font-size: 2.5em;
    font-weight: bold;
    color: #58a6ff;
    text-align: center;
    margin-bottom: 5px;
  }

  /* 🖼️ Hero Image/Banner එක Wave වෙන්න */
  .waving-hero {
    animation: wave-image 6s ease-in-out infinite alternate;
    border-radius: 12px;
    box-shadow: 0 8px 24px rgba(0,0,0,0.2);
    width: 100%;
  }

  /* Keyframes for Text Floating */
  @keyframes wave-text {
    0% { transform: translateY(0px) rotate(0deg); }
    100% { transform: translateY(-8px) rotate(0.5deg); }
  }

  /* Keyframes for Hero Smooth Waving */
  @keyframes wave-image {
    0% { transform: translateY(0px) scale(1); }
    50% { transform: translateY(-6px) scale(1.01) skewX(0.5deg); }
    100% { transform: translateY(0px) scale(1); }
  }
</style>

<!-- 🎯 Title Area with Animating Waving Effect -->
<div class="floating-title">
  Supervision Technology (PVT) LTD 👋
</div>
<p align="center" style="font-size: 1.2em; color: #8b949e; font-style: italic; text-align: center;">
  Turning visions into high-performance reality
</p>

<!-- 🖼️ Animating Hero Banner -->
<p align="center">
  <img class="waving-hero" src="https://via.placeholder.com/1200x400.png?text=Supervision+Technology" alt="Supervision Technology Banner">
</p>

---

### 🌟 About Us
Engineering scalable multi-tenant ERP platforms and secure high-performance business automation software for 100+ thriving enterprise clients. We specialize in transforming corporate workflows through custom software engineering, automated payroll solutions, and robust data-driven infrastructures.

---

### 🛠️ Tech Stack & Ecosystem
We utilize a modern, high-performance set of technologies to power our enterprise solutions:

*   **Backend & Core**: PHP (Native & MVC Architecture)
*   **Database Management**: MS SQL Server (MSSQL), Prisma ORM
*   **Web & Frontend**: Next.js, TypeScript, Tailwind CSS, JavaScript
*   **Reporting & Analytics**: Stimulsoft Reports Engine
*   **Infrastructure & DevOps**: Docker, Firebase, GitHub Actions CI/CD

---

### 📬 Get in Touch
*   **Website**: [supervision.lk](https://supervision.lk)
*   **Email**: info@supervision.lk
*   **LinkedIn**: [company/supervisiontechnology-pvt-ltd](https://www.linkedin.com/company/supervisiontechnology-pvt-ltd/)
