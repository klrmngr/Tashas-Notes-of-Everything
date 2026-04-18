---
type: pc
race: "Celestial"
class:
 - "Lantern Archon"
subClass:
 - "CR 2"
cover: "Lantern Archon.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/small
  - cr/2
  - source/mpp
---
###### Lantern Archon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Lantern Archon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Celestial |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 16 | 12 | 6 | 12 | 13 |
| **Mod** | -5 | +3 | +1 | -2 | +1 | +1 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** all
**Skills:** Perception +3
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; radiant
**Condition Immunities:** exhaustion; grappled; paralyzed; prone; restrained

---

### Traits

**Aura of Menace.** As long as the archon doesn't have the incapacitated condition, each creature of the archon's choice that starts its turn within 20 feet of the archon must make a DC 11 Wisdom saving throw. On a failed save, the creature has the frightened condition until the start of its next turn. On a successful save, the creature is immune to all archons' Aura of Menace for 24 hours.

**Illumination.** The archon sheds bright light in a 30-foot radius and dim light for an additional 30 feet.

**Incorporeal Movement.** The archon can move through creatures and objects as if they were difficult terrain. If it ends its turn inside an object, it takes 5 (1d10) force damage.


---

### Actions

**Multiattack.** The archon makes two Radiant Strike attacks. It can replace one attack with a use of Teleport.

**Radiant Strike.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 6 (1d6 + 3) radiant damage.

**Teleport.** The archon teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself.


---

### Bonus Actions

**Shift Radiance.** The archon reduces its Illumination to shed only dim light in a 5-foot radius, or it returns the light to full intensity.


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