# A Tokenless SPA: Secure Authentication with the BFF Pattern

**Speaker:** Tore Nestenius · .NET Architect & Technical Trainer, Tore Nestenius DataKonsult AB
**Tech Passion Day 2026** · Wednesday, 10:15 – 10:50

## About the talk

For years, the standard advice for securing Single Page Applications has been to make the SPA an OAuth/OIDC client and store tokens in the browser. This session makes the case for leaving that model behind.

Instead of the SPA handling tokens directly, the **Backend-for-Frontend (BFF)** becomes the OAuth client, and the browser receives nothing but a secure, `HttpOnly` session cookie. No tokens in local storage, no tokens in JavaScript, no tokens to steal via XSS.

**In this talk, we cover:**

- The risks of storing access and refresh tokens in the browser
- How the BFF pattern moves OAuth/OIDC responsibility to the backend
- Building SPAs without any browser-based token storage
- Security essentials: `SameSite` cookies, cookie prefixing, CORS configuration, and CSRF protection
- Implementation best practices, and common mistakes to avoid
- A live, practical demo in ASP.NET Core, including deployment considerations

**Who it's for:** developers and architects working with OpenID Connect and OAuth who want a more secure approach to authentication in modern SPAs.

Read the full session description on the [Tech Passion Day 2026 agenda](https://techpassionday.com/2026/agenda/a-tokenless-spa-secure-authentication-with-the-bff-pattern).

## What's in this folder

- [`Backend-for-Frontend in ASP.NET Core.pdf`](./Backend-for-Frontend%20in%20ASP.NET%20Core.pdf): the session slides

## About the speaker

**Tore Nestenius** is an independent .NET architect and technical trainer with over 23 years of software development experience and more than a decade spent training developers. He specializes in .NET, ASP.NET Core, software architecture, web security, and identity management. Tore is also a Microsoft .NET MVP.

Read more on the [Tech Passion Day 2026 speaker page](https://techpassionday.com/2026/speakers/tore-nestenius).

- Blog: [nestenius.se](https://nestenius.se)
- Website: [tn-data.se](https://tn-data.se)
- LinkedIn: [linkedin.com/in/torenestenius](https://www.linkedin.com/in/torenestenius/)

---

[← Back to all TPD26 sessions](../../README.md)
