---
type: pc
race: "Undead"
class:
 - "Sammaster (Dracolich Form)"
subClass:
 - "CR 22"
cover: "Sammaster (Dracolich Form).png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/22
  - source/fraif
---
###### Sammaster (Dracolich Form)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Sammaster (Dracolich Form).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 276 (24d12 + 120) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 21 | 23 | 15 | 21 |
| **Mod** | +7 | +0 | +5 | +6 | +2 | +5 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 26
**Languages:** Common, Draconic, Infernal
**Saving Throws:** Dex +7, Con +12, Int +13, Wis +9
**Skills:** Arcana +20, History +13, Perception +16
**Damage Immunities:** acid; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Sammaster fails a saving throw, he can choose to succeed instead.

**Life Suppression.** Creatures within 60 feet of Sammaster can't regain Hit Points.

**Magic Resistance.** Sammaster has Advantage on saving throws against spells and other magical effects.

**Soul Gem.** Sammaster has a magical soul gem as his dracolich heart. The gem can't be damaged or removed until he is reduced to 0 Hit Points. If Sammaster is reduced to 0 Hit Points, his dracolich form dissolves to dust. After 1d10 days, he appears in an unoccupied space within 5 feet of his soul gem (so long as the gem still exists), using the Sammaster (Lich Form) stat block. The gem is a Tiny object that has AC 20; HP 50; and Immunity to Acid, Necrotic, Poison, and Psychic damage. The gem regains all its Hit Points at the end of every turn, but it turns to dust if reduced to 0 Hit Points.


---

### Actions

**Multiattack.** Sammaster makes three Rend attacks. He can replace one attack with a use of Spellcasting to cast Blight or Ray of Sickness (level 6 version).

**Rend.** m +14, reach 10 ft. *Hit:* 18 (2d10 + 7) Slashing damage plus 18 (4d8) Necrotic damage.

**Corroding Breath (Recharge 5–6).** con DC 20, each creature in a 90-foot Cone.  52 (8d12) Acid or Necrotic damage (Sammaster's choice).  Half damage.


---

### Legendary Actions

### 

**Pounce.** Sammaster moves up to half his Speed, and he makes one Rend attack.

**Sickening Ray.** Sammaster uses Spellcasting to cast Ray of Sickness (level 6 version).

**Terrifying Presence.** wis DC 21, each creature in a 20-foot Emanation originating from Sammaster.  13 (2d12) Psychic damage, and the target has the Frightened condition until the end of its next turn.  Sammaster can't take this action again until the start of his next turn.


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