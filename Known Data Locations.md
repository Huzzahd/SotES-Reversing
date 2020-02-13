Document with locations and descriptions of data understood at least on a minimal level.

---

sotes.exe - .rdata section
* 0x001CC284 - 0x0027AD34: Unknown.
* 0x0027AD34 - 0x00282660: **Actor Data**, a null-terminated array of data for entities that can fight (Arche, Sana, Stella and all the enemies).
* 0x00282660 - 0x002826C0: *Unknown*, but seems like a null-terminated array and has Character data.
* 0x002826C0 - 0x002907C0: **Ability Data**, a null-terminated array of data of abilities for both player characters and enemies.
* 0x002907C0 - 0x00290B40: **Ability Unlocks Data**, a null-terminated array of data for how player characters unlock abilities.
* 0x00290B40 - 0x00290CA0: **Marks of Heroism Data**, a sequence of data related to Marks of Heroism (level caps, max money).
* 0x00290CA0 - 0x00293848: Unknown.
* 0x00293848 - 0x002940C8: **Area Data**, a null-terminated array of data for "regions" like towns (Tonkiness, Barness, Chartreux), dungeons etc.
* 0x002940C8 - 0x002B6568: **Location Data**, a null-terminated array of data for "screens" where the player moves, talks, fights etc.
* 0x002B6568 - 0x002B6EA8: **Portrait Data**, a null-terminated array of data for portraits/mugshots for dialogue.
* 0x002B6EA8 - 0x002B7EE8: **Character Data**, a null-terminated array of data for characters that have dialogues, portraits, proper names etc.
* 0x002B7EE8 - 0x002C0834: **Message Data**, a null-terminated array of data for mail/messages the player receives.
* 0x002C0834 - 0x002C0CD0: Unknown.
* 0x002C0CD0 - 0x002E79D0: **Item Data**, a null-terminated array of data for items (anything that can go into the inventory).
* 0x002E79D0 - 0x002E7F50: **Shop Data**, a null-terminated array of arrays with data for shops and capsule machines.
* 0x002E7F50 - 0x00450D60: **Book Data**, a null-terminated array of data for books with text (Magical Girl Merrin etc, ability books don't count).
* 0x00450D60 - 0x00454000: Unknown.

sotes.exe - .rsrc section
* DATA directory (general): Map data for locations, stuff like tiles, width/height etc.
* DATA directory (1249): Unknown.
* DATA directory (1392-1399, 1404): Unknown, probably sprites.
* DATA directory (1451): Unknown.
