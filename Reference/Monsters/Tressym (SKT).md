---
type: pc
race: "Monstrosity"
class:
 - "Tressym"
subClass:
 - "CR 0"
cover: "Tressym.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/0
  - source/skt
---
###### Tressym
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Tressym.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 5 (2d4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 15 | 10 | 11 | 12 | 12 |
| **Mod** | -4 | +2 | +0 | +0 | +1 | +1 |

**Speed:** 40 ft., climb 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** understands Common but can't speak
**Skills:** Perception +5, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Detect Invisibility.** Within 60 feet of the tressym, magical invisibility fails to conceal anything from the tressym's sight.

**Keen Smell.** The tressym has advantage on Wisdom (Perception) checks that rely on smell.

**Poison Sense.** The tressym can detect whether a substance is poisonous by taste, touch, or smell.

**Familiar.** With the DM's permission, a person who casts the find familiar spell can choose to conjure a tressym instead of a normal cat.


---

### Actions

**Claws.** Melee Weapon Attack: +0 to hit, reach 5 ft., one target. *Hit:* 1 slashing damage.


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