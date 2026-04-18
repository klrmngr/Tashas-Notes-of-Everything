---
type: pc
race: "Fey"
class:
 - "Riverine"
subClass:
 - "CR 12"
cover: "Riverine.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/12
  - source/jttrc
---
###### Riverine
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Riverine.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 204 (24d10 + 72) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 19 | 17 | 12 | 16 | 21 |
| **Mod** | +5 | +4 | +3 | +1 | +3 | +5 |

**Speed:** 30 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 17
**Languages:** Aquan, Common, Sylvan
**Saving Throws:** Int +5, Wis +7, Cha +9
**Skills:** Insight +7, Nature +5, Perception +7
**Damage Resistances:** acid; fire

---

### Traits

**Amphibious.** The riverine can breathe air and water.

**Legendary Resistance (3/Day).** If the riverine fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The riverine makes two Flood Strike attacks.

**Flood Strike.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage plus 10 (3d6) cold damage.


---

### Bonus Actions

**Whirlpool Step.** The riverine magically teleports to an unoccupied space it can see within 30 feet of itself. Both the space it leaves and its destination must be in or on the surface of water.


---

### Legendary Actions

### 

**Whirlpool Rush.** The riverine uses its Whirlpool Step. Immediately after it teleports, each creature within 5 feet of the riverine's destination space takes 5 (1d10) cold damage.

**Raging Deluge (Costs 2 Actions).** The riverine unleashes a torrent of river water in a 30-foot line that is 5 feet wide. Each creature in that area must make a DC 17 Dexterity saving throw. On a failed save, a creature takes 11 (2d10) bludgeoning damage and is knocked prone. On a successful save, a creature takes half as much damage and isn't knocked prone.


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