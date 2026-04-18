---
type: pc
race: "Giant"
class:
 - "Ice Troll"
subClass:
 - "CR 8"
cover: "Ice Troll.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/8
  - source/idrotf
---
###### Ice Troll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Ice Troll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 115 (10d10 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 8 | 22 | 7 | 9 | 7 |
| **Mod** | +4 | -1 | +6 | -2 | -1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Giant
**Skills:** Perception +2
**Damage Immunities:** cold

---

### Traits

**Cold Aura.** While it's alive, the troll generates an aura of bitter cold that fills the area within 10 feet of it. At the start of the troll's turn, all nonmagical flames in the aura are extinguished. Any creature that starts its turn within 10 feet of the troll takes 10 (3d6) cold damage.

**Keen Smell.** The ice troll has advantage on Wisdom (Perception) checks that rely on smell.

**Regeneration.** The ice troll regains 10 hit points at the start of its turn. If the troll takes acid or fire damage, this trait doesn't function at the start of the troll's next turn. The ice troll dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The troll makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 9 (2d8) cold damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 9 (2d8) cold damage. If the target takes any of the cold damage, the target must succeed on a DC 15 Constitution saving throw or have disadvantage on its attack rolls until the end of its next turn.


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