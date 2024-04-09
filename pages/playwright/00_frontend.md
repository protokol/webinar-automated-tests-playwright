<div class="grid grid-cols-2 gap-4">
<div>

### Interaction (UI)

```typescript
// Emulate typing in the browser address bar + Enter
await page.goto('https://playwright.dev/');

// Type in a text field
await page.fill('input[name="search"]', 'Playwright');

// Select a checkbox
await page.getByLabel('I agree to the terms above')
    .check();

// Select dropdown option
await page.getByLabel('Choose a color')
    .selectOption('blue');

// Focus on a field (e.g. to trigger validators)
await page.getByLabel('Password').focus();
```

</div>
<div>

### Assertions (UI)

```typescript
// Assert against the <title> tag
await expect(page).toHaveTitle(/Playwright/);

// Wait for <h1>Get started</h1> to appear on the page
await expect(page)
    .toHaveSelector('h1', {text: 'Get started'});

// Wait for checkbox to appear and be checked
await expect(page.getByLabel('Remember me'))
    .toBeChecked();
```

</div>
</div>
