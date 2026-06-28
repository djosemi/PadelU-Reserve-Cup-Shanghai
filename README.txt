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
