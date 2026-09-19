# BrightKeyboard 3.x

The last build of BrightKeyboard under the applicationId `app.lightphonekeyboard`, kept alive so the
people already running it are offered it.

That id belongs to [adam-weber/light-keyboard](https://github.com/adam-weber/light-keyboard), the
project BrightKeyboard is a fork of. The fork kept it, which stopped him shipping his own keyboard
to any phone that had this one. It is going back, and BrightKeyboard now lives at
[gi-os/BrightKeyboard](https://github.com/gi-os/BrightKeyboard) under `com.gios.brightkeyboard`.

**Nothing new ships here.** The whole job of this build is a line above the keys saying the keyboard
has moved, and a provider that hands your settings, your saved words and the touch model it learned
to the new one the first time you open it. The two install side by side, which is the only reason
that handoff works: install the new one, open it once, then remove this.

The source is a frozen copy of `gi-os/BrightKeyboard` at v3.11, with the applicationId left where it
was. It lives in its own repository because the catalogue is keyed on applicationId and two listings
cannot share one repo — the moment 4.0 released, an entry pointing at the main repo rewrote itself
to the new id and the old listing disappeared, taking the only channel that could reach these phones
with it.

This repository goes away once the installs have moved.
