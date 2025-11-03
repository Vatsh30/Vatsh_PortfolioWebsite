// =========================================
// Yash Vinaykumar Patel - Portfolio Script
// Handles mobile navigation & contact form
// =========================================

document.addEventListener('DOMContentLoaded', () => {

  // ----- Mobile navigation toggle -----
  const navToggle = document.getElementById('nav-toggle');
  const nav = document.getElementById('nav');

  if (navToggle && nav) {
    navToggle.addEventListener('click', () => {
      nav.classList.toggle('show');
    });
  }

  // Handle alternate toggle IDs if needed
  const navToggle2 = document.getElementById('nav-toggle-2');
  const nav2 = document.getElementById('nav-2');
  if (navToggle2 && nav2) {
    navToggle2.addEventListener('click', () => {
      nav2.classList.toggle('show');
    });
  }

  // ----- Contact form handler -----
  const form = document.getElementById('contact-form');
  if (form) {
    form.addEventListener('submit', e => {
      e.preventDefault();
      const name = form.name.value.trim();
      const email = form.email.value.trim();
      const msg = form.message.value.trim();

      if (!name || !email || !msg) {
        alert("Please fill out all fields before submitting.");
        return;
      }

      // Demo confirmation only (no backend on GitHub Pages)
      alert(`Thank you, ${name}! Your message has been received.`);
      form.reset();
    });
  }
});
