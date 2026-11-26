# Kashaf (كشّاف)

A free browser lab for practicing medical device repair. Open a virtual hospital device, inspect parts, measure test points, find the hidden fault and replace the right part. Wasted steps and unsafe actions cost points.

**Live:** https://yousefkhames.github.io/kashaf/

**Training game with fictional values. Not a service manual. Not for real repair or clinical decisions.**

## Features
- 6 cases: infusion pump, patient monitor, defibrillator, suction pump, ECG machine, neonatal incubator
- Lockout step first (opening a live device costs points), digital multimeter display, hints, stars, case of the day
- Service report at the end that you can copy
- English and Arabic (RTL), language switch keeps your progress in the case
- Mobile first layout, keyboard and screen reader friendly (real buttons, live regions, skip link)
- Installable and works offline (PWA). Progress is saved in localStorage. No backend, no tracking.

## Add a case
Edit `cases.js`. Each case has `comps` (parts), one `fault` id, and bilingual `insp` (inspect) and `meter` (measure) texts. Parts that read normal are red herrings.

## Run locally
`python3 -m http.server` then open http://localhost:8000

## Credits
Idea space and related open projects: open-vent-sim, vent-sim, Infirmary Integrated.

MIT License.
