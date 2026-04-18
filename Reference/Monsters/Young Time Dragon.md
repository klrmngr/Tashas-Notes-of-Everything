---
type: pc
race: "Dragon"
class:
 - "Young Time Dragon"
subClass:
 - "CR 11"
cover: "Young Time Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/11
  - source/mpp
---
###### Young Time Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Young Time Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 210 (20d10 + 100) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 20 | 20 | 15 | 17 |
| **Mod** | +5 | +1 | +5 | +5 | +2 | +3 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 20
**Languages:** Draconic plus any four languages
**Saving Throws:** Dex +5, Con +9, Wis +6, Cha +7
**Skills:** Arcana +9, History +13, Perception +10, Stealth +9

---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 7 (2d6) force damage.

**Time Breath (Recharge 5–6).** The dragon exhales a wave of shimmering light in a 30-foot cone. Nonmagical objects and vegetation in that area that aren't being worn or carried crumble to dust. Each creature in that area must make a DC 17 Constitution saving throw. On a failed save, a creature takes 31 (7d8) force damage and is magically weakened as it is desynchronized from the time stream. While the creature is in this state, attack rolls against it have advantage. On a successful save, a creature takes half as much damage only. A weakened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself after it succeeds on two of these saves.


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