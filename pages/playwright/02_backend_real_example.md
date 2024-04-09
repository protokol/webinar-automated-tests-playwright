# Real example:

```typescript
const apiResponseCreateCollection = await request.post(`collections`, {
    data: {
        name: "Test Collection",
    },
})

expect(apiResponseCreateCollection.ok()).toBeTruthy();

const {idCollection} = await apiResponseCreateCollection.json();

const apiResponseCreateToken = await request.post(`token`, {
    data: {
        name: "Test Token",
        idCollection,
    }
})
expect(apiResponseCreateToken.ok()).toBeTruthy();

// Remember to replace `request` with a fixture that includes auth out of the box
// e.g. playwright.request.newContext() that includes the `Authorization: Bearer XXX` header
```
