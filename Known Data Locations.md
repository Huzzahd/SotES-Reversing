Document with locations and descriptions of data understood at least on a minimal level.

---

### sotes.exe
#### .rdata Section

- 0x001CC284 - 0x0027AD34: Unknown.
- 0x0027AD34 - 0x00282660: __Actor Data__, a null-terminated array of data for entities that can fight (Arche, Sana, Stella and all the enemies).
- 0x00282660 - 0x002826C0: _Unknown_, but seems like a null-terminated array and has Character data.
- 0x002826C0 - 0x002907C0: __Ability Data__, a null-terminated array of data of abilities for both player characters and enemies.
- 0x002907C0 - 0x00290B40: __Ability Unlocks Data__, a null-terminated array of data for how player characters unlock abilities.
- 0x00290B40 - 0x00290CA0: __Marks of Heroism Data__, a sequence of data related to Marks of Heroism (level caps, max money).
- 0x00290CA0 - 0x00293848: Unknown.
- 0x00293848 - 0x002940C8: __Region Data__, a null-terminated array of data for "regions" like towns (Tonkiness, Barness, Chartreux), dungeons etc.
- 0x002940C8 - 0x002B6568: __Location Data__, a null-terminated array of data for "locations", like Arche's room, Sana's house etc.
- 0x002B6568 - 0x002B6EA8: __Portrait Data__, a null-terminated array of data for portraits/mugshots for display in dialogues.
- 0x002B6EA8 - 0x002B7EE8: __Character Data__, a null-terminated array of data for characters that have dialogue, portraits, proper names etc.
- 0x002B7EE8 - 0x002C0834: __Message Data__, a null-terminated array of data for mail/messages the player receives.
- 0x002C0834 - 0x002C0CD0: Unknown.
- 0x002C0CD0 - 0x002E79D0: __Item Data__, a null-terminated array of data for items (anything that can go into the inventory).
- 0x002E79D0 - 0x002E7F50: __Shop Data__, a null-terminated array of arrays with data for shops and capsule machines.
- 0x002E7F50 - 0x00450D60: __Book Data__, a null-terminated array of data for books with text (Magical Girl Merrin etc, ability books don't count).
- 0x00450D60 - 0x00454000: Unknown.

#### .rsrc Section

- DATA directory (Majority of Entries): __Map data__, each entry corresponds to a location and contains stuff like tiles, width/height etc.
- DATA directory (IDs 1392 through 1399, 1404, 1451): __Sprites__, for the main characters and also inventory items.
- DATA directory (IDs 1249): Unknown.

---

### sotesd.dll
#### .rsrc Section

- DATA directory (Majority of Entries): __Sprites__, for everything else in the game not in sotes.exe.
- DATA directory (IDs 1180, 1986, 2014): Unknown
