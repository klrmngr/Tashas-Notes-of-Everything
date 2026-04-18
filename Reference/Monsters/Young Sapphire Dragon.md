---
type: pc
race: "Dragon (gem)"
class:
 - "Young Sapphire Dragon"
subClass:
 - "CR 9"
cover: "Young Sapphire Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/9
  - source/ftd
---
###### Young Sapphire Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Sapphire Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Dragon (gem) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 157 (15d10 + 75) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 14 | 20 | 16 | 15 | 16 |
| **Mod** | +5 | +2 | +5 | +3 | +2 | +3 |

**Speed:** 40 ft., burrow 20 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 20
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +6, Con +9, Wis +6, Cha +7
**Skills:** History +7, Perception +10, Persuasion +11, Stealth +6
**Damage Resistances:** lightning; thunder
**Condition Immunities:** frightened

---

### Traits

**Spider Climb.** The dragon can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and can leave a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 4 (1d8) thunder damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage.

**Debilitating Breath (Recharge 5–6).** The dragon exhales a pulse of high-pitched, nearly inaudible sound in a 30-foot cone. Each creature in that area must make a DC 17 Constitution saving throw. On a failed save, the creature takes 33 (6d10) thunder damage and is incapacitated until the end of its next turn. On a successful save, the creature takes half as much damage and isn't incapacitated.


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