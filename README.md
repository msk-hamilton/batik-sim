# Design a Batik Cloth

An interactive batik studio for the classroom.

- **Pattern studio:** pick a motif (Parang, Kawung, Truntum, Mega mendung) and a traditional or modern dye palette, and read what each motif means.
- **Wax-resist studio:** make a cloth the way batik is really made. Draw wax, dip in dye, add more wax, dip again, then boil out the wax. Includes wax crackle and indigo that turns from green to blue in the air.
- **See it as a scarf:** your finished cloth, repeated across a scarf.

It is a single static page (`index.html`). No build step, no server, and no accounts or data collection.

## Publish on GitHub Pages

1. Create a new **public** repository on GitHub (for example `batik-studio`).
2. Upload `index.html`, `.nojekyll`, and `README.md` to the repository root.
3. Go to **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two, your page is live at `https://YOUR-USERNAME.github.io/batik-studio/`.

## Notes

- The page loads two fonts (Fraunces and Nunito) from Google Fonts. If a student's network blocks Google Fonts, the page still works and uses a fallback font.
- Drawing works best with a mouse, trackpad, or stylus.
