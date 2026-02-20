---
theme: ./
layout: cover
background: https://images.unsplash.com/photo-1557683316-973673baf926?w=1920&fit=crop
---

# Ember Modern Dark

A dark Slidev theme

---

# Default Slide

Regular content slide with dark background.

- Bullet point one
- Bullet point two
  - Nested bullet
- Bullet point three

---

# Code Example

```ts {all|2|1-6|all}
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

---
layout: two-cols
---

# Two Columns

Left side content

::right::

Right side content

---
layout: section
---

# Section Title

---
layout: statement
---

# Bold Statement

---
layout: fact
---

# 100%
Fact information

---
layout: quote
---

# "Notable quote"
Attribution

---
layout: image
image: https://images.unsplash.com/photo-1557683316-973673baf926?w=1920&fit=crop
---

<div class="h-full flex items-center justify-center">
  <div class="text-center text-white">
    <h1 class="text-6xl">The End</h1>
  </div>
</div>
