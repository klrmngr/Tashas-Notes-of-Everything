---
type: pc
race: "Undead (wizard)"
class:
 - "Sammaster (Lich Form)"
subClass:
 - "CR 22"
cover: "Sammaster (Lich Form).png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/22
  - source/fraif
---
###### Sammaster (Lich Form)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Sammaster (Lich Form).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Medium Undead (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 322 (43d8 + 129) |
> | :FasUserGroup: Race | Undead (wizard) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 16 | 23 | 15 | 21 |
| **Mod** | +1 | +2 | +3 | +6 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 19
**Languages:** Common, Draconic, Infernal
**Saving Throws:** Dex +9, Con +10, Int +13, Wis +9
**Skills:** Arcana +20, History +13, Perception +9
**Damage Resistances:** acid; cold; lightning
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Sammaster fails a saving throw, he can choose to succeed instead.

**Life Suppression.** Creatures within 60 feet of Sammaster can't regain Hit Points.

**Magic Resistance.** Sammaster has Advantage on saving throws against spells and other magical effects.

**Soul Gem.** If Sammaster is reduced to 0 Hit Points while his magical soul gem exists, his lich form dissolves to dust. After 1d10 days, he appears in the space of his soul gem, using the Sammaster (Dracolich Form) stat block. The gem is a Tiny object that has AC 20; HP 50; and Immunity to Acid, Necrotic, Poison, and Psychic damage. The gem regains all its Hit Points at the end of every turn, but it turns to dust if reduced to 0 Hit Points. If the gem is destroyed, Sammaster can create a new one by completing an 8-hour ritual using a gem worth 1,000+ GP, which the ritual consumes, and by expending 5,000 GP.


---

### Actions

**Multiattack.** Sammaster makes three attacks, using Corrosive Burst or Paralyzing Touch in any combination. He can replace two attacks with a use of Spellcasting.

**Corrosive Burst.** m,r +13, reach 5 ft. or range 120 ft. *Hit:* 38 (5d12 + 6) Acid or Necrotic damage (Sammaster's choice).

**Paralyzing Touch.** m +13, reach 5 ft. *Hit:* 16 (3d6 + 6) Cold damage, and the target has the Paralyzed condition until the start of Sammaster's next turn.


---

### Legendary Actions

### 

**Deathly Teleport.** Sammaster teleports up to 60 feet to an unoccupied space he can see, and each creature within 10 feet of the space he left takes 19 (3d12) Necrotic damage.

**Dissolve.** Sammaster makes one Corrosive Burst attack.

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