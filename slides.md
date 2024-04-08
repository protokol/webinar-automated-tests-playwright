---
# try also 'default' to start simple
theme: seriph
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
transition: fade-out
---

# Agenda

1. Playwright base principles
    1. Test cases
    2. Assertions
2. How to write your first test
3. Advanced tips
    1. Use isolated environments
    2. Don't be TOO specific with assertions (avoid Brittle tests)
    3. Leverage the multiple browsers support
    4. Use it for API testing
