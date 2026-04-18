---
type: pc
race: "Giant"
class:
 - "Troll Amalgam"
subClass:
 - "CR 17"
cover: "Troll Amalgam.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/gargantuan
  - cr/17
  - source/bgg
---
###### Troll Amalgam
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Troll Amalgam.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Gargantuan Giant |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 217 (14d20 + 70) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 14 | 21 | 9 | 16 | 5 |
| **Mod** | +7 | +2 | +5 | -1 | +3 | -3 |

**Speed:** 60 ft., climb 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** Giant, Undercommon
**Saving Throws:** Con +11, Wis +9
**Skills:** Perception +9
**Damage Resistances:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the amalgam fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The amalgam has advantage on saving throws against spells and other magical effects.

**Regeneration.** The amalgam regains 15 hit points at the start of its turn. If the amalgam takes acid or fire damage, it regains only 5 hit points at the start of its next turn. The amalgam dies only if it takes 20 or more acid or fire damage while it has 0 hit points.


---

### Actions

**Multiattack.** The amalgam makes three Rend attacks.

**Rend.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 25 (4d8 + 7) slashing damage.


---

### Bonus Actions

**Fling Limb (3/Day).** Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. *Hit:* 11 (1d8 + 7) bludgeoning damage. If the limb hits a Medium or smaller creature, that creature has the grappled condition (escape DC 17). The limb has the statistics of a troll amalgam, except for the following: it is Medium, it has 45 hit points, its speed is 30 ft., it doesn't have a challenge rating or Legendary Resistance, and the only action it can take is the Attack action, which it can use only to grapple.
Until this grapple ends, the target has the restrained condition and takes 25 (4d8 + 7) slashing damage at the start of each of its turns. If the limb is not destroyed within 24 hours of being flung, roll a d12; on a roll of 12, the limb regenerates into a troll (see the Monster Manual). Otherwise, the limb withers away.


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