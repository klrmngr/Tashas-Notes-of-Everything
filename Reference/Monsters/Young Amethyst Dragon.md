---
type: pc
race: "Dragon (gem)"
class:
 - "Young Amethyst Dragon"
subClass:
 - "CR 9"
cover: "Young Amethyst Dragon.png"
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
###### Young Amethyst Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Amethyst Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Dragon (gem) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 168 (16d10 + 80) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 21 | 18 | 15 | 19 |
| **Mod** | +5 | +1 | +5 | +4 | +2 | +4 |

**Speed:** 40 ft., fly 80 ft. ((hover)), swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 20
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +5, Con +9, Wis +6, Cha +8
**Skills:** Arcana +12, Perception +10, Persuasion +8, Stealth +5
**Damage Resistances:** force; psychic
**Condition Immunities:** frightened; prone

---

### Traits

**Amphibious.** The dragon can breathe both air and water.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 4 (1d8) force damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage.

**Singularity Breath (Recharge 5–6).** The dragon creates a shining bead of gravitational force in its mouth, then releases the energy in a 30-foot cone. Each creature in that area must make a DC 17 Strength saving throw. On a failed save, the creature takes 36 (8d8) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


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