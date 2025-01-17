# Changelog

----

Version numbers apply to "releases".

Until then, its only a log of what I've changed to prepare update info on Nexus.

----

# 2023.06.23 - 0.9b
- Added: Covered topics count
- Fix: Print faster hdtsmp version only once
- Added: AVX detection (skiped CUDA detection, because of false-positives and exe would be over 200mb)
- Improved: Basic version check recomendations for FSMP
- Added: CompressedArchiveStream (Corrupt Texture)
- Added: Mod Count

# 2023.06.22 - 0.9a
- Hotfix: VR crashlog can be read again.

# 2023.06.22 - 0.9
- Removed: lists that also had an according dictionary
- Removed: DLC.esm entries, since I cant disable the DLC from the steam-property 'page' (SSE)
- Improved: Handler for missing SKSE
- Improved: tbbmalloc text, covering SrtCrashFix64.dll now as well.
- Improved: HUD message display (alignment)
- Added: VR, created basic framework
- Added: probably "outside quit" ADR for SkyrimSE
- Added: DynamicCollisionAdjustment
- Added: Modified by (should help to figure wrong load orders)
- Added: Lanterns (LoS II)
- Added: Chance to retrieve FSMP version


# 2023.06.19 - 0.8
- Improved: NiNode & Mesh output, prints fewer lines now (provides a counter for their respective occourences)
- Improved texts for: RaceMenu, NiNode, Mesh, hdtsmp64.dll, cbp.dll
- Added: Message if no SkyrimSE.exe issues were found
- Added: false positive disclaimer for DLC
- Added: tbbmalloc.dll 
- Added: link for Artesian Cloak xml patch
- Added: link for hdt/SMP NPC fix
- Added: link for Faster HDT-SMP
- Fixed: Message display for no_alloc
- Fixed: Parsing of files with 6 or less strings on line "Unhandled Exception" (previously was only handling 0x000000000000 specificly)


# 2023.06.17 - 0.7b
- Improved crashfile reading
- Should fix 2 different kind of reading issues

# 2023.06.16 - 0.7a
- Added: NiNode & Mesh handling
- Added: HUD Keyword

# 2023.06.15 - 0.7
- Initial Release on Nexus