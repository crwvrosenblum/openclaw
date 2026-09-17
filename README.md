# Plugin icon theme proof

Sanitized browser screenshots of the actual OpenClaw Control UI with its standard mock Gateway and one synthetic Sample Plugin.

- before-dark.png: baseline UI source at 4d28246be9e5b99c48e50f450cbe36d9806836ae; dark default glyph loses contrast.
- after-dark.png: candidate UI requests the dark-theme variant; white glyph is visible.
- after-light.png: switched through Appearance settings to Light and returned to Plugins without reloading; dark glyph is visible.

Screenshots contain only synthetic fixture data and no private plugin source or branding. These artifacts support the proposed optional package-icon variants in openclaw/openclaw issue #151219. They are review evidence, not a release or a live-Gateway end-to-end test.
