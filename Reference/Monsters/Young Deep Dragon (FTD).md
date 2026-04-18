---
type: pc
race: "Dragon"
class:
 - "Young Deep Dragon"
subClass:
 - "CR 5"
cover: "Young Deep Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/5
  - source/ftd
---
###### Young Deep Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Deep Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 12 | 14 | 16 |
| **Mod** | +4 | +1 | +3 | +1 | +2 | +3 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 150 ft., passive Perception 15
**Languages:** Common, Draconic, Undercommon
**Saving Throws:** Dex +4, Con +6, Wis +5, Cha +6
**Skills:** Perception +5, Persuasion +6, Stealth +7
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 3 (1d6) poison damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Nightmare Breath (Recharge 5–6).** The dragon exhales a cloud of spores in a 30-foot cone. Each creature in that area must make a DC 14 Wisdom saving throw. On a failed save, the creature takes 22 (4d10) psychic damage, and it is frightened of the dragon for 1 minute. On a successful save, the creature takes half as much damage with no additional effects. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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