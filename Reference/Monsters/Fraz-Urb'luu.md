---
type: pc
race: "Fiend (demon)"
class:
 - "Fraz-Urb'luu"
subClass:
 - "CR 23"
cover: "Fraz-Urb'luu.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/23
  - source/mpmm
---
###### Fraz-Urb'luu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Fraz-Urb'luu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 337 (27d10 + 189) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 12 | 25 | 26 | 24 | 26 |
| **Mod** | +9 | +1 | +7 | +8 | +7 | +8 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +8, Con +14, Int +15, Wis +14
**Skills:** Deception +15, Perception +14, Stealth +8
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Fraz-Urb'luu fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Fraz-Urb'luu has advantage on saving throws against spells and other magical effects.

**Undetectable.** Fraz-Urb'luu can't be targeted by divination magic, perceived through magical scrying sensors, or detected by abilities that sense demons or Fiends.


---

### Actions

**Multiattack.** Fraz-Urb'luu makes one Bite attack and two Fist attacks, and he uses Phantasmal Terror.

**Bite.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 19 (3d6 + 9) force damage.

**Fist.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 22 (3d8 + 9) force damage.

**Phantasmal Terror.** Fraz-Urb'luu targets one creature he can see within 120 feet of him. The target must succeed on a DC 23 Wisdom saving throw, or it takes 16 (3d10) psychic damage and is frightened of Fraz-Urb'luu until the end of its next turn.


---

### Legendary Actions

### 

**Tail.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 20 (2d10 + 9) force damage. If the target is a Large or smaller creature, it is also grappled (escape DC 24), and it is restrained until the grapple ends. Fraz-Urb'luu can grapple only one creature with his tail at a time.

**Terror (Costs 2 Actions).** Fraz-Urb'luu uses Phantasmal Terror.


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