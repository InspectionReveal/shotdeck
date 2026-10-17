# Assets to create for shotdeck

## logo.png вЂ” 256x256, transparent, dark theme
📸 Neon shield/gear motif matching $shotdeck$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $shotdeck$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Region capture with crosshair, magnifier and size tooltip

## screenshots/settings.png вЂ” 1280x800
Annotator — toolbar with arrow, blur, text, step numbers

## screenshots/results.png вЂ” 1280x800
History deck — filmstrip of recent captures with search

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"