# Profile artwork

`habit-header-light.svg` and `habit-header-dark.svg` share the same geometry
and differ only in color. Both have a transparent background; the light
version is the fallback when theme-aware picture sources are unsupported.

- The companion figure is habit's own drawing, with its traced outline smoothed.
- The `habit` lettering is original: one continuous round-capped stroke drawn
  from custom vector paths, not a font or outlined glyphs. The ring over the
  `i` is the only separate mark. Apple's handwritten “hello” inspired the
  flowing single-stroke direction only; no Apple artwork, font, or
  third-party asset was copied.
- The lettering writes itself on once using embedded CSS. Each file is
  self-contained: no script, SMIL, fonts, or external resources. With reduced
  motion, or where CSS animation is unsupported, the finished lettering is
  shown immediately.
