# 🌐 R and A Legacies — Responsive Web Design Journey

This project is part of my ongoing journey to master **Responsive Web Design**, and it's being built from scratch as a real-world practice webpage called **R and A Legacies**. The goal is to make this layout work seamlessly across devices: phones, tablets, laptops, and desktops.

---

## Day One — 28th July

### What I Worked On

Today, I laid the foundation for the site and began building out the structure for responsiveness. Specifically, I focused on:

- **Logo section** (`#navbar`) — ensured it scales and sits properly across all screen sizes
- **Banner image** (`#banner`) — adjusted height via media queries (`100px` up to `350px`) for various devices
- **About section** (`#about`) — built a two-column layout that collapses vertically on mobile and aligns side-by-side on larger screens using `flex-direction`
- **Job Opportunities section** — created:
  - A **card view** (visible on mobile)
  - A **responsive table** (visible from medium devices and up) using `@media` queries

### Challenge Faced

> **Tracking CSS layout changes across different screen sizes**

Switching between views (mobile, tablet, desktop) to verify layout consistency takes time and attention. It's easy to miss how a small change (like `padding` or `font-size`) affects components across breakpoints. I'm learning to organize my CSS cleanly, keep units consistent (`rem`, `%`), and label sections clearly.

---

## Tech/Concepts Used

- HTML5 (semantic structure)
- CSS3 (mobile-first design)
- Responsive units (`rem`, `em`, `%`)
- `@media` queries for:
  - `576px` (tablet)
  - `768px` (laptop)
  - `992px+` (desktop)
- Fonts: [Roboto](https://fonts.google.com/specimen/Roboto), [Inter](https://fonts.google.com/specimen/Inter)


---

## Learning Resource

- FreeCodeCamp Youtube Tutorial: [Web Development with HTML & CSS - Full course for Begginers]

---

