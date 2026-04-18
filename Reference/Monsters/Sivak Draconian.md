---
type: pc
race: "Monstrosity"
class:
 - "Sivak Draconian"
subClass:
 - "CR 4"
cover: "Sivak Draconian.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/dsotdq
---
###### Sivak Draconian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Sivak Draconian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 57 (6d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 18 | 13 | 10 | 10 |
| **Mod** | +4 | +0 | +4 | +1 | +0 | +0 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic
**Saving Throws:** Str +6, Wis +2

---

### Traits

**Death Throes.** When the draconian is reduced to 0 hit points by a creature that is Large or smaller, the draconian crumbles into dust that then forms a spectral, shrieking image of the creature that killed it. The image lasts for 1 minute. Each creature hostile to the draconian within 10 feet of the image must succeed on a DC 14 Wisdom saving throw or be frightened of the spectral image for 1 minute. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Actions

**Multiattack.** The draconian makes two Serrated Sword attacks and one Tail attack.

**Serrated Sword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Tail.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 14 Strength saving throw or be knocked prone.


---

### Reactions

**Shape Theft.** After the draconian kills a Medium or smaller Humanoid, the draconian magically cloaks itself in an illusion to look and feel like that creature while retaining the draconian's game statistics (other than its size). This transformation lasts until the draconian dies or uses a bonus action to end it.


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