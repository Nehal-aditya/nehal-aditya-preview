---
title: "My Cool App"
date: 2024-08-23T10:30:00+05:30
tags: ["web development", "javascript", "react"]
---

**My Cool App** is a responsive web application designed for...

---

{{< details title="Project Features" >}}
Here's a list of the key features:

- Feature 1: A brief description.
- Feature 2: Another brief description.
{{< /details >}}

---

### The Stack

{{< cards >}}
  {{< card title="Frontend" subtitle="React" icon="react.svg" >}}
  {{< card title="Backend" subtitle="Node.js" icon="nodejs.svg" >}}
{{< /cards >}}

---

### Screenshots and Diagrams

You can add images here by placing them in the `static` directory and linking to them.

{{< mermaid >}}
graph TD
    A[User] --> B{Login};
    B --> C{Authenticated?};
    C -- Yes --> D[Dashboard];
    C -- No --> B;
{{< /mermaid >}}
