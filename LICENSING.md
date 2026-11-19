# Licensing

TruckPlay is a derivative work of WestPlay (GPL-3.0-or-later) and is distributed under the same
license. The complete corresponding source is the project repository on branch `truckplay-product`
(commit recorded in SOURCE.txt), including the WebClient HTML and build files.

TruckPlay does **not** ship WestPlay's UI files, maps, plugin DLL, models, brand assets or Spotify/
YouTube/Apple Music marks: it uses the user's installed WestPlay at runtime. It does not ship the SCS
SDK (the installed WestPlay plugin links it; that distribution's own notices apply to WestPlay).

Third-party Rust crates and their licenses are listed in THIRD-PARTY-NOTICES.md; all are compatible
with GPLv3 (MIT/Apache-2.0/BSD style).

Before distributing binaries to third parties you must: publish the corresponding GPL source for the
exact binary, keep copyright/license notices, and resolve WestPlay's own outstanding release blockers
(SCS SDK notice, embedded Kedi739 asset permission, service marks) in the combined distribution.
Local personal use of this build does not redistribute WestPlay assets.
