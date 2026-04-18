---
type: pc
race: "Humanoid (any race)"
class:
 - "Rakdos Performer, Fire Eater"
subClass:
 - "CR 1"
cover: "Rakdos Performer, Fire Eater.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/ggr
---
###### Rakdos Performer, Fire Eater
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Rakdos Performer, Fire Eater.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 17 | 12 | 10 | 8 | 15 |
| **Mod** | +1 | +3 | +1 | +0 | -1 | +2 |

**Speed:** 40 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** any one language (usually Common)
**Saving Throws:** Dex +5, Cha +4
**Skills:** Acrobatics +7, Performance +4

---

### Traits

**Nimble.** The performer can take the Disengage action as a bonus action on each of its turns.


---

### Actions

**Multiattack.** The fire eater makes two attacks with its bladed chain.

**Bladed Chain.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Spew Flame (Recharge 4–6).** The fire eater exhales flames. Each creature in a 15-foot cone must make a DC 13 Dexterity saving throw, taking 9 (2d8) fire damage on a failed save, or half as much damage on a successful one.


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