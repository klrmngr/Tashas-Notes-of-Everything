---
type: pc
race: "Undead"
class:
 - "Sea Lich"
subClass:
 - "CR 9 / 12 / 14"
cover: "The Drowned Eternal.png"
campaign: "THE DROWNED CROWN"
locations:
  - "[[Tomb of Sand]]"
tags:
  - race/undead
  - affinity/hostile
  - campaign/theDrownedCrown
---
###### The Drowned Eternal
:FasPerson: Boss &nbsp; | &nbsp; :FasMapLocationDot: [[Tomb of Sand]]
___

> [!infobox|no-t right]
> ![[The Drowned Eternal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 → 12 → 14 |
> | :RiSwordFill: Type | Sea Lich (Necromancer) |
> | :FasShield: AC | 12 (15 with mage armor) |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Undead |

> [!quote|no-t]
> An ancient Sea Lich mid-ritual in the central pool of the [[Tomb of Sand]]. Its phylactery — a barnacle-covered nautilus shell — sits on the altar. Three-phase boss fight; grows increasingly desperate as the phases progress.

---

## Phase 1 — The Tide Rises *(CR 9)*

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 12 | 18 | 12 | 10 |
| **Mod** | -1 | +2 | +1 | +4 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** Common, Elvish, Abyssal, Aquan
**Saving Throws:** Int +8, Wis +5
**Skills:** Arcana +12, History +8, Perception +5, Stealth +6
**Damage Resistances:** Necrotic; bludgeoning/piercing/slashing from non-magical attacks
**Condition Immunities:** Charmed, exhaustion, frightened, paralyzed, poisoned

---

### Traits

**Undead Fortitude.** If damage reduces it to 0 HP, it makes a Con save (DC = 5 + damage dealt) unless the damage is radiant or a critical hit. On success, it drops to 1 HP instead.

**Spellcasting.** Intelligence, spell save DC 16, +8 to hit. Slots: 1st ×4, 2nd ×3, 3rd ×3, 4th ×3, 5th ×1.
- Cantrips: *chill touch, mage hand, minor illusion*
- 1st: *false life, magic missile, shield*
- 2nd: *blindness/deafness, misty step*
- 3rd: *animate dead, counterspell, vampiric touch*
- 4th: *blight, dimension door*
- 5th: *cloudkill*

---

### Actions

**Withering Touch.** *Melee:* +6 to hit, reach 5 ft. *Hit:* 14 (4d6) necrotic damage.

**Indomitable.** Rerolls a failed save. Must use new roll.

---

### Phase 1 Minions

| Creature | Count | Notes |
|---|---|---|
| Skeleton (temple guard) | 4–6 | Active from round 1 |
| Ghoul | 2 | Rise from water, **start of round 2** |
| Ghost | 1 | Phases through walls periodically |

**Phase transition:** At half HP, the lich shatters the ritual pool — the floor floods with ankle-deep cursed water. *Difficult terrain everywhere.*

---

## Phase 2 — The Phylactery Revealed *(CR 12)*

True form: barnacle-encrusted skeleton, glowing deep-sea blue eye sockets.

> [!warning] Phylactery
> A barnacle-covered nautilus shell on the altar. **40 HP · AC 15.** Visible with a DC 13 Perception or Arcana check. Must be destroyed to stop regeneration.

**New stats boost:**
- **Legendary Resistance (2/day).** If it fails a saving throw, it can choose to succeed instead.
- **Paralyzing Touch.** Replaces Withering Touch. *Melee:* +6 to hit. *Hit:* 10 (3d6) cold damage + DC 14 Con save or **paralyzed until end of next turn.**
- **Legendary Actions (3/turn):**
  - **Cantrip (1).** Casts a cantrip.
  - **Drift (1).** Moves up to its speed without provoking opportunity attacks.
  - **Cast (2).** Casts a spell of 3rd level or lower.

**New Hazard:** Cursed water deals **1d6 necrotic** to any creature (not undead) that ends its turn standing in it.

---

## Phase 3 — The Deep Awakens *(CR 14)*

Triggers at **25% HP** or when the phylactery is destroyed.

**Additional abilities:**
- Casts **Bestow Curse** or **Blight** as a bonus action *(once per phase)*
- **2 [[Undead Merrow|Undead Merrows]]** drop from the ceiling
- Prioritizes **downed players** with Paralyzing Touch to prevent revives
- If phylactery is still intact: **regenerates 20 HP** at the start of each of its turns

**Rising Water:** Water rises **1 foot per round** — pressure clock for the party.

---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```
