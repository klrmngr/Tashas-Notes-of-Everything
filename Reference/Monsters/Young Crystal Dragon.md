---
type: pc
race: "Dragon (gem)"
class:
 - "Young Crystal Dragon"
subClass:
 - "CR 5"
cover: "Young Crystal Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/5
  - source/ftd
---
###### Young Crystal Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Crystal Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Dragon (gem) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 18 | 16 | 14 | 17 |
| **Mod** | +3 | +1 | +4 | +3 | +2 | +3 |

**Speed:** 40 ft., burrow 20 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +7, Wis +5, Cha +6
**Skills:** Perception +8, Stealth +7, Survival +5
**Damage Resistances:** cold; radiant

---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 14 (2d10 + 3) piercing damage plus 4 (1d8) radiant damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Scintillating Breath (Recharge 5–6).** The dragon exhales a burst of brilliant radiance in a 30-foot cone. Each creature in that area must make a DC 15 Constitution saving throw, taking 27 (6d8) radiant damage on a failed save, or half as much damage on a successful one. The dragon then gains 10 temporary hit points by absorbing a portion of the radiant energy.


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