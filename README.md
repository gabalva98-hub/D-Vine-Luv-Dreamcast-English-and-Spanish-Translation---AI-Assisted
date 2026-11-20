# D+VINE [LUV] — English & Spanish Fan Translation

An unofficial, free English and Latin American Spanish fan translation of **D+VINE [LUV]** for the **Sega Dreamcast**, presented by **Gyasuke & Wakabayashy Workshop**.

The translation is distributed through an **offline HTML patcher for Android and PC**. **The game itself is not included.** You must provide your own clean Japanese Dreamcast game files.

**Current build:** 0.7.0 V63 — experimental, cumulative  
**Updated:** November 20, 2026  
**Game languages:** English and Latin American Spanish  
**Game interface:** English in the EN version; Latin American Spanish in the ES version, where editable text is available  
**Text embedded in graphics:** English in both versions

## About the game

**D+VINE [LUV]** is an action RPG with visual novel elements. It follows **Hyde**, a young adventurer exploring the mysterious ruins near **Arvil**. Dungeon exploration, monster battles, equipment upgrades, and encounters with the town's inhabitants gradually reveal more about the world and its secrets.

## Changes in V63

- Corrected word wrapping in **36 English and 36 Spanish story records** containing timing or other special script controls.
- Fixed the reported Sakura narration overflow in **SCN366**, where the game split a word across two lines.
- Preserved the original pause, color, and script commands, without adding unverified dialogue-page sequences.
- Retained V62's dialogue presentation changes, including removal of decorative opening/closing quotation marks and broader line-layout revisions.
- Retained all previous fixes to character labels, translated menus, English graphics, and combat.

**Important:** V63 does **not** finish the global line-layout audit. More than 800 potentially problematic timed-text segments were identified across both languages; these are **risks to investigate, not 800 confirmed visual defects**.

## What's included

- English and Latin American Spanish story translations, including narration, conversations, and character dialogue.
- Translated names, menus, system messages, item names and descriptions, magic and equipment-related text, with continuing editorial review.
- Edited **English-language graphics shared by both versions**, including Configuration and location-name plates.
- Revised in-game menu choice alignment, including the Adventurers' Guild menu with five separate options.
- Revised character/contact labels sourced from multiple game resources.
- A fix for the **ITEM.DAT integrity value**, which previously prevented the player from damaging enemies when item text was modified.
- A standalone HTML patcher with the **Gyasuke & Wakabayashy Workshop** logo, a bilingual patcher interface, and a separate choice of game language.
- **Offline patching:** game files are processed on your device, not uploaded to a server.

**Language distinction:** The patcher's display language and the translation applied to the game are separate choices. Editable in-game interface text follows the selected EN/ES translation. Text drawn into graphical assets remains in English in both variants.

## Installation

1. **Back up** your clean Japanese game files and any existing save data.
2. Obtain `DVINE_LUV_0.7.0 PARCHEADOR_ANDROID_PC_V63.html` and open it in a current browser on **Android or PC**. An internet connection is not required.
3. Select the original, unmodified Japanese Dreamcast **v1.002** `track03.bin` from your own `.gdi` disc set.
4. Choose the **patcher interface language** (English or Español). This does **not** change the language of the game.
5. Choose the **game translation**: English or Español latinoamericano.
6. Click **Verify and prepare translation**. When verification is complete, download the translated `track03.bin` using the link shown by the patcher.
7. Put the resulting `track03.bin` into a **copy** of your disc folder, alongside its corresponding `.gdi` and other, unchanged original tracks. Do **not** overwrite your clean original.
8. Open the copied `.gdi` in **Flycast** or another compatible Dreamcast setup and check the game.

**Required input:** Japanese Dreamcast v1.002 `track03.bin`, **1,185,760,800 bytes**. The PC patcher checks the original's SHA-256:

`098bd3f027696c9846d826141c4dfc54c1449798ce0a1cc38efffcb4e65622ae`

**Important:** Start from the original track **every time**. Builds are cumulative; do not apply V63 over V62 or any previously translated copy. A `.chd`, `.cdi`, `.iso`, or `.gdi` file is not a substitute for the required clean `track03.bin` input.

### Android and large-file handling

The output is approximately **1.19 GB**. Make sure your device has enough free storage and your browser can handle a file this large. Keep the browser tab open while processing. On Android, use the generated download link once the patch has finished; if your browser cannot complete the operation, use the PC package.

## Testing and project status

**V63 is an experimental test build, not a final, fully playtested release.**

### Confirmed gameplay results

- Verified in **Flycast** that the fix introduced in V57 restores damage dealt to enemies while keeping translated item data.
- Confirmed that the edited Configuration and inn-name graphics display correctly and that combat remained functional in those tests.
- Confirmed that the **five choices in the Adventurers' Guild menu** display separately after the V60 menu-alignment correction.

### Current-build validation

The V63 patcher generated complete English and Spanish tracks from the clean Japanese disc. Binary checks verified script records, menu structures, replacement-sector checksums, and the preservation of earlier non-dialogue modifications. **This technical validation does not establish that every dialogue box looks correct in gameplay.**

## Known limitations and bug reports

- **Dialogue wrapping is still under review.** Approximately 808 timed-text segments across EN and ES were flagged for further investigation; some may need additional page capacity or engine-specific fixes.
- V63's newest reflow changes still require **visual confirmation in Flycast**, particularly narration, timed pauses, and newly arranged pages.
- Some **selected Configuration values** can still appear in Japanese in an overlaid text layer; this issue is being investigated separately from the translated background graphics.
- Contact-name fixes introduced in V61 and other less common scenes may need further in-game confirmation.
- Untranslated text, text clipping, inconsistent terminology, and other issues may still occur. Passing a patcher integrity check is not equivalent to completing a playthrough.

If you encounter a problem, please send a report containing, where possible:

- The **patch build (V63)** and the selected **game language (EN/ES)**.
- Your emulator and version, or other Dreamcast setup.
- The location, scene, and steps needed to reproduce the issue.
- The affected dialogue, menu, or graphic, ideally with a screenshot or short video.
- For a crash, any available error details and whether it also happens with clean Japanese data.

Back up your save before investigating. **Do not send copyrighted game dumps with bug reports.**

## Credits

- **Project, translation work, technical modifications, and patch presentation:** Gyasuke & Wakabayashy Workshop.

Thank you to everyone helping improve the English and Spanish versions through testing and detailed reports.

## Legal notice and distribution

This is an **unofficial, free, non-commercial fan translation**. It is not affiliated with, sponsored by, or endorsed by the game's developer, publisher, or any rights holder. The original game, characters, artwork, music, and trademarks remain the property of their respective owners.

**This patch must remain free. It must not be sold or placed behind a paywall. If someone charges you for it, the project has not authorized that sale.**

**No Dreamcast game image, BIOS, music, or other original game files are included.** The patcher contains modification data only. Users are responsible for obtaining and using their own game files in accordance with applicable laws.

---

Thank you for playing **D+VINE [LUV]** in English or Spanish!
