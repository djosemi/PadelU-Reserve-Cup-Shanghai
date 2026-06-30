PadelU Reserve Cup Playoff Manager v5

Updates included:
- Tournament visual identity using PadelU logo, Reserve Cup logo, poster background and tournament colors.
- Team logos included for Jiuguang, Sifec, One East, Taikoo Hui, Xijiao Bailian and Anken.
- Placeholder logos included for Capital Square and Moho because those specific logos were not provided.
- Manual Quarterfinal bracket selection.
- Set-by-set padel score input for every level and every leg.
- Automatic match winner detection from sets.
- Automatic home/away point calculation.
- Automatic QF -> SF -> Final bracket updates.
- Visual World Cup-style bracket preview.
- Export bracket as PNG.
- Export bracket as PDF using browser-based html2canvas + jsPDF.
- Export/import JSON backup.

Upload this folder to GitHub Pages. The main file is index.html.

V6 updates:
- Team logos are zoomed/cropped for stronger visibility inside the image boxes.
- Reserve Cup logo now uses a transparent background in the app header/export.
- Added consolation bracket: QF losers play Consolation Semifinals and a Consolation Final.
- Consolation games use the same set-by-set input and home/away point calculation as the main bracket.
- Bracket PNG/PDF export now includes the consolation bracket below the main playoff bracket.


v7 update:
- Captains updated:
  Anken: Xiu
  Sifec: Dàyú
  Moho: Yun
  Capital Square: Allen
  Jiuguang: Yidane
  Taikoo Hui: Josemi
  Xijiao Bailian: Jacob
  One East: Michael
- Moho, Jiuguang, Capital Square and Taikoo Hui logos enlarged/tighter inside the logo boxes.
- Uses a new localStorage key so old captain data does not override the new list.


v8 update:
- All team logos rebuilt on the same square canvas.
- Each logo is maximized inside the same standard square margin.
- No logo is scaled outside its frame, so letters and icons are not cut off.
- Moho, Jiuguang, Capital Square and Taikoo Hui now use tighter crops while preserving all text and icon elements.


v9 Firebase update:
- Connected to Firebase project padelu-reserve-cup.
- Firestore path: tournaments / reserve-cup-2026.
- Public visitors can read the live bracket without login.
- Admin email djosemi@gmail.com can login with Google and edit/save online.
- Added Admin Login / Logout / Save Online Now.
- Keeps PNG/PDF export.
- Keeps JSON backup.
- Uses localStorage only as offline fallback/cache.
- Upload the full folder to GitHub Pages, including assets/.


v10 mobile update:
- On mobile, the public bracket and match details are shown before admin setup panels.
- Header is no longer sticky on small screens, avoiding overlap with content.
- Header actions wrap into a clean two-column mobile layout.
- Bracket and score cards are more compact and easier to read on phones.
- Admin setup/team/manual bracket panels are moved below the main public bracket content.


v11 round export update:
- Added round-specific detailed image export buttons next to each result-entry section.
- Quarterfinals can export a detailed results image.
- Semifinals can export a detailed results image.
- Final can export a detailed results image.
- Consolation bracket can export a detailed results image.
- Each export includes team logos, points, legs, level scores and winners in a tournament-branded image.


v12 update:
- Taikoo Hui is now displayed everywhere as HKRI Taikoo Hui, the official venue name.


v13 update:
- HKRI Taikoo Hui is now enforced everywhere, including if old Firebase or localStorage data still contains Taikoo Hui.
- The app normalizes the team name by team id on every render and export.


v14 update:
- Quarterfinal bracket is now locked and cannot be edited manually.
- Manual QF bracket admin panel has been removed.
- Fixed QF pairings:
  QF1: Xijiao Bailian vs HKRI Taikoo Hui
  QF2: Anken vs Moho
  QF3: Jiuguang vs Capital Square
  QF4: SIFEC vs One East
- The app enforces these QF pairings even if older Firebase/local data still contains the previous bracket.
