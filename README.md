# Jihad Maasarani, Portfolio · RevOps

A single-page, scroll-driven portfolio aimed at RevOps and CRM implementation
roles. No framework and no build step: hand-written HTML, CSS and vanilla
JavaScript with GSAP, ScrollTrigger and Lenis from a CDN.

One of three sibling portfolios sharing a design, deployed separately so each
can target a different kind of role without overwriting the others.

**Live:** _(added after deploy)_

## Running locally

```bash
python .claude/devserver.py 5181
```

The dev server sends `no-store` and implements HTTP Range, which the stdlib
handler does not.

## Notes

- Everything degrades: readable with JavaScript disabled, usable under
  `prefers-reduced-motion`, presentable with every video file removed.
- Animations touch only `transform`, `opacity`, `filter` and `clip-path`.
- Scenes play only while on screen; the preloader gates on real assets.

## Licence

Code is free to learn from. The photography, video, copy and CV are not.
