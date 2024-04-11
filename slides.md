---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1516110833967-0b5716ca1387?q=80&w=3774&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
# some information about your slides, markdown enabled
title: Automated Testing
info: |
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# Automated Testing

Why fix something in 5 mins,<br/> if you can automate it in 5 hours?

---
transition: slide-up
---

# Agenda

1. Playwright overview
    1. Actions and Assertions
    2. Frontend testing
    3. Backend (API) testing
2. Creating your first E2E test
3. Advanced techniques

---
transition: slide-left
src: ./pages/playwright/00_frontend.md
---

---
src: ./pages/playwright/01_backend.md
---

---
transition: slide-down
src: ./pages/playwright/02_backend_real_example.md
---

---
src: ./pages/first-test/00_playwright_setup.md
---

---
src: ./pages/first-test/01_playwright_setup.md
---

---
src: ./pages/first-test/03_write_first_test.md
layout: two-cols
---

---
src: ./pages/first-test/04_playwright_codegen.md
---

---
src: ./pages/advanced/00_tips.md
---

---
src: ./pages/end.md
layout: end
---
