---
type: pc
race: "Monstrosity"
class:
 - "Giant Strider"
subClass:
 - "CR 1"
cover: "Giant Strider.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/1
  - source/vgm
---
###### Giant Strider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Giant Strider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 22 (3d10 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 14 | 4 | 12 | 6 |
| **Mod** | +4 | +1 | +2 | -3 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —
**Damage Immunities:** fire

---

### Traits

**Fire Absorption.** Whenever the giant strider is subjected to fire damage, it takes no damage and regains a number of hit points equal to half the fire damage dealt.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Fire Burst (Recharge 5–6).** The giant strider hurls a gout of flame at a point it can see within 60 feet of it. Each creature in a 10-foot-radius sphere centered on that point must make a DC 12 Dexterity saving throw, taking 14 (4d6) fire damage on a failed save, or half as much damage on a successful one. The fire spreads around corners, and it ignites flammable objects in that area that aren't being worn or carried.


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