---
type: pc
race: "Monstrosity"
class:
 - "Draconian Dreadnought"
subClass:
 - "CR 4"
cover: "Draconian Dreadnought.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/ftd
---
###### Draconian Dreadnought
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Draconian Dreadnought.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 57 (6d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 18 | 10 | 10 | 10 |
| **Mod** | +4 | +0 | +4 | +0 | +0 | +0 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic
**Saving Throws:** Str +6, Wis +2

---

### Traits

**Death Throes.** When the draconian is reduced to 0 hit points, it bursts into flames and is reduced to ashes. Each creature in a 10-foot-radius sphere centered on the draconian must succeed on a DC 13 Dexterity saving throw or take 10 (3d6) fire damage.


---

### Actions

**Multiattack.** The draconian makes two Serrated Sword attacks and one Tail attack.

**Serrated Sword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Tail.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 14 Strength saving throw or be knocked prone.


---

### Reactions

**Shape Theft.** After the draconian kills a Medium or smaller Humanoid, the draconian can magically transform itself to look and feel like that creature while retaining its game statistics (other than its size). This transformation lasts until the draconian dies or uses an action to end it.


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