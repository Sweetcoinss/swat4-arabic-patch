SWAT 4 - Arabic Localization Patch
====================================

Files to copy into your SWAT 4 game folder (overwrite existing):

  Content\Textures\SwatFonts.utx   ->  <game>\Content\Textures\SwatFonts.utx
  Content\System\SwatGui.ini       ->  <game>\Content\System\SwatGui.ini
  Content\System\Swat4.ini         ->  <game>\Content\System\Swat4.ini
  Content\System\Default.ini       ->  <game>\Content\System\Default.ini
  Content\System\SwatGUI.ara       ->  <game>\Content\System\SwatGUI.ara (optional)

Steps:
  1. Close SWAT 4.
  2. BACKUP original files (rename to .bak) before overwriting.
  3. Copy the 5 files above into the game folder (overwrite).
  4. Run Swat4.exe.
  5. Dismiss the 'unsupported hardware' dialog with Enter.

Notes:
  - SwatGui.ini must remain UTF-16 LE with BOM.
  - Font: Noto Sans Arabic (iPhone-style), Kerning=1.
  - Arabic text: reshape+bidi (presentation forms + RTL).
  - Translated: Main Menu + Campaign + Custom + Loadout + MP + Settings + popups.
