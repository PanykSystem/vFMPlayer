# Third-party assets and sources

The new folder guides, configuration examples and MIDI examples are vFM
material. They do not change the rights of the supplied banks, samples or ROMs.

- FITOM: https://sites.google.com/site/fitomproject/home
  Original instrument files are in `midi/banks`; hashes/provenance are in
  `midi/BANKS_SOURCE.json`. FITOM code is LGPL-2.1; bank/sample rights remain
  with their original authors. No bank or sample relicensing is claimed.
- Felucca-Engines: https://github.com/hugelton/Felucca-Engines
  The VFS files select presets of the embedded engines; the engine notice is
  retained in `licenses/Felucca-MIT.txt`.
- DX7 / sloopDX: https://github.com/zvenson/dxsloop
  Preset launchers use the embedded core. Original licensing information and
  GPL text are retained in `licenses`; user-supplied SYX dumps keep their own terms.
- Klattsch: https://github.com/tildearrow/furnace/tree/master/extern/klattsch-cpp
  The original MIT notice is retained in `licenses/Klattsch-MIT.txt`.
- KINROU5: https://sakuramail.net/fswold/music.html#muskin
  Copyright 1996,1997 Keiichi Kuroda / BTO (MuSICA Laboratory).
  The driver, original archive and CP932 notices are retained unchanged in
  `roms`. Original terms require author notification for public redistribution
  and prior permission for embedding in products for sale. Those terms are
  not replaced by the player source license; retain and follow the original notice.
- SPC700 IPL: the 64-byte optional external copy and its original download
  provenance are retained in `roms/spc700.rom.json`. It has separate asset
  rights; no relicensing is claimed. This Teensy firmware already embeds its IPL.

No personal configuration slots, recorded tapes or commercial music collection
are included in this repository fragment. Preserve these notices when publishing.
