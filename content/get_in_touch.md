---
title: "Get in touch"
---

If you’re working on **ML, AI tooling, data, or finance-related products** and think I could be a good fit, I’d be happy to connect.

Whether it’s a potential role, a side project, or just a technical conversation, feel free to reach out.

---

<div class="about-actions">
  <button type="button" class="btn-primary" id="copy-email-btn">
    📧 Copy email
  </button>
  <a class="btn-ghost" href="https://www.linkedin.com/in/harshmalik98/" target="_blank" rel="noopener noreferrer">
    Connect on LinkedIn
  </a>
  <a class="btn-ghost" href="https://github.com/godhunter98" target="_blank" rel="noopener noreferrer">
    View GitHub
  </a>
  <a class="btn-ghost"
   href="/Portfolio-Website/Harsh_Malik_Resume_2025.pdf"
   target="_blank"
   rel="noopener noreferrer">
  📄 View Résumé
  </a> 
  
</div>

---

### What to reach out about

- Roles at the intersection of **ML / AI** and **finance / data**  
- Ideas for **AI tools**, internal automations, or analyst workflows  
- Feedback on my projects or suggestions for what to build next  

I usually reply fastest on **email** and **LinkedIn**.



<!-- The script to copy email to clipboard! -->
<script>
  (function () {
    const btn = document.getElementById("copy-email-btn");
    if (!btn) return;

    const email = "harshworkspace@gmail.com";

    btn.addEventListener("click", async () => {
      try {
        await navigator.clipboard.writeText(email);
        const originalText = btn.textContent;
        btn.textContent = "Copied!";
        setTimeout(() => {
          btn.textContent = originalText;
        }, 1500);
      } catch (err) {
        console.error("Clipboard error:", err);
        alert("Could not copy email. Please copy manually: " + email);
      }
    });
  })();
</script>