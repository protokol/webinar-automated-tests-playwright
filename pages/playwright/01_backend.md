<div class="grid grid-cols-2 gap-4">
<div>

### Interaction (API)

```typescript
const response = await request.post(`auth/login`, {
    data: {
        email: 'example@example.com',
        password: 'GottaL0veBall000n$',
    },
});
```

</div>
<div>

### Assertions (API)

```typescript
// Expect a 200 status code
expect(response.ok()).toBeTruthy();

// Assert for fields of the response
const body = await response.json();
expect(body).toHaveProperty("token");
```

</div>
</div>
