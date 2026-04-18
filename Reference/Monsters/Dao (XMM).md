---
type: pc
race: "Elemental (genie)"
class:
 - "Dao"
subClass:
 - "CR 11"
cover: "Dao.png"
campaign:
locations:
tags:
  - race/genie
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/11
  - source/xmm
---
###### Dao
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Dao.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Elemental (genie) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 200 (16d10 + 112) |
> | :FasUserGroup: Race | Elemental (genie) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 24 | 12 | 13 | 18 |
| **Mod** | +6 | +1 | +7 | +1 | +1 | +4 |

**Speed:** 30 ft., burrow 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Primordial (Terran)
**Saving Throws:** Dex +5, Wis +5
**Condition Immunities:** petrified

---

### Traits

**Earth Glide.** The dao can burrow through nonmagical, unworked earth and stone. While doing so, the dao doesn't disturb the material it moves through.

**Elemental Restoration.** If the dao dies outside the Elemental Plane of Earth, its body dissolves into dirt, and it gains a new body in 1d4 days, reviving with all its Hit Points somewhere on the Plane of Earth.

**Magic Resistance.** The dao has Advantage on saving throws against spells and other magical effects.

**Wishes.** The dao has a 30 percent chance of knowing the Wish spell. If the dao knows it, the dao can cast it only on behalf of a non-genie creature who communicates a wish in a way the dao can understand. If the dao casts the spell for the creature, the dao suffers none of the spell's stress. Once the dao has cast it three times, the dao can't do so again for 365 days.


---

### Actions

**Multiattack.** The dao makes three Earthen Maul attacks or two Earth Burst attacks.

**Earthen Maul.** m +10, reach 5 ft. *Hit:* 20 (4d6 + 6) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.

**Earth Burst.** r +10, range 120 ft. *Hit:* 15 (2d8 + 6) Bludgeoning damage. Earth explodes from the target's space, creating the following effect. dex DC 16, each creature in a 10-foot Emanation originating from and including the target.  10 (3d6) Thunder damage.


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