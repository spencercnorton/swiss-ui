# Changelog

Versions follow [semantic versioning](https://semver.org/); each release is a
tag on `main`.

## v1.3.2 — screenshots

- The library animation and game detail still now show a poster pack in use:
  nine illustrated covers drawn for the fictitious demonstration titles,
  rendered by the real poster pipeline (focus scaling, depth, retained art),
  instead of the generated fallback cards.

## v1.3.1 — screenshots

- The Home animation is re-cut on the rotations: the loop now walks Library,
  Source, System and back to Library, instead of opening on four idle seconds
  and cutting off mid-turn.

## v1.3.0 — screenshots

- The README now shows the interface: an animated capture of the Home cube
  turning between its four faces, the game library, and the game detail
  screen.
- Captured from a demonstration card built for the purpose — nine fictitious
  titles with generated cover art — so nothing in frame is anyone's real
  library or third-party artwork. The animations are APNG, which GitHub
  renders in a README like any image.

## v1.2.0 — first public release

The first published release of the interface rebuild. Everything below is what
this tag contains rather than a list of changes against an earlier public
version; the upstream Swiss history it is built on is at
[emukidid/swiss-gc](https://github.com/emukidid/swiss-gc).

- **Home**: an animated four-face cube, one face per destination, with
  device state carried through the rotation.
- **Library**: a retained poster grid over the device's games, with a saved
  selection that survives a return to Home.
- **Game details**: a per-title surface with artwork, region and format
  information, and the boot options for that title.
- **Cheats**: a presentation pass over the cheat browser, with clearer
  per-cheat state and safer runtime handling.
- **Settings and System**: rebuilt surfaces with consistent controller
  navigation shared across every screen.
- Interface work only: device handlers, the patch engine and the loader are
  upstream Swiss.
