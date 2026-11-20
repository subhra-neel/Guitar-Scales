# Guitar Chords & Scales Trainer

Daily practice app for acoustic guitar (steel or nylon) that listens through the microphone: live tuner, chord check, graded scale play-along with wait-for-me mode, rhythm-switch timing, auto-counted one-minute changes, strumming patterns, song progressions with automatic capo, notes and CAGED chord shapes across the whole neck, an adaptive daily plan with milestones, a practice recorder, a capo setting that listening follows, jam sessions over a backing band, chord estimation with slow-down and A-B loop for your own audio files, chord sheets with transpose and easy-capo, a chord namer, progress charts, note finder, ear training and analogy-led lessons.

Open **https://subhra-neel.github.io/Guitar-Scales/** on phone or tablet and install it (Chrome: ⋮ → Install app; iPhone Safari: Share → Add to Home Screen). It works offline. Run Settings → Calibrate timing once per device.

Everything lives in `index.html`; there is no build step.

To release an update: change `VERSION` in `sw.js`, `APP_VERSION` in `index.html` and `version` in `version.json`. Installed copies show an Update banner.
