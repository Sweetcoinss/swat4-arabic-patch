SWAT 4 - Arabic Localization Patch (Low-End Optimized)
=====================================================

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

Arabic:
  - Font: Noto Sans Arabic (iPhone-style), Kerning=1.
  - Text: reshape+bidi (presentation forms + RTL), UTF-16 LE+BOM.
  - Translated: Main Menu, Campaign, Custom, Loadout, MP, Settings, popups.

Low-End PC Optimization (Intel T2050 / weak PCs):
  - Resolution: 800x600 (fullscreen/windowed), menu 640x480.
  - Textures: Low (interface/terrain/weapon/player/world/rendermap/lightmap).
  - Effects: Decals/Coronas/DecoLayers/Projectors/ScreenFlashes disabled.
  - Dynamic lights: disabled; NoLighting enabled.
  - DetailTextures: disabled; Trilinear/ Cubemaps disabled.
  - 16-bit textures enabled (saves VRAM).
  - Audio: LowQualitySound, 16 channels.
  - MinDesiredFrameRate: 20.
  - BestGuessDefaultRenderDetail: 1 (lowest).
Notes:
  - SwatGui.ini must remain UTF-16 LE with BOM.
  - If text still missing on weak PCs, ensure MenuViewport/Resolution not too high.
"