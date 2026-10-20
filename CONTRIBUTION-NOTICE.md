# Contribution copyright and attribution

This branch is derived from MOD Audio mod-host and the Blokas MODEP fork.
Original authors retain their copyrights; existing notices and GPL-3.0-or-later
source headers remain applicable. The local changes add shared MIDI inputs,
per-binding Follow/Reverse/Toggle modes, observational capture, atomic input-list
replacement and Toggle eligibility for persistent two-state controls.

Changes were recovered by Robert on 2026-10-20 from the deployed build stage.
The MODEP variant matches the deployed native source; the MOD variant is a clean
cherry-pick onto current MOD master and has not been built or runtime-tested
against that upstream version. The corresponding UI/backend protocol work is
in the separate mod-ui integration branch. No personal boards, plugin artwork,
media, compiled binaries or machine settings are included in this contribution.
