# Advanced techniques

<v-clicks>

1. Use isolated environments
    1. automated testing VS manual testing
    2. previous test runs should not affect current test runs
2. Don't be *too* specific with assertions (avoid Brittle tests)
    1. Assertions should check the bare minimum
    2. Avoid using long-tail XPath selectors (or `body > div > div > p`)
    3. Avoid using position-based selectors (to left of, to right of, below, etc.)
3. Leverage all supported browsers to spot cross-browser issues
    1. Some of your fancy UI libraries might be using browser-specific CSS
4. Avoid scattering test suite for UI and API

</v-clicks>

<!--
1. Hard isolation VS soft isolation
3. Moz and webkit prefixes
4. Postman for API testing; and something else for UI testing
-->
