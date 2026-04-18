---
type: pc
race: "Construct"
class:
 - "Living Doll"
subClass:
 - "CR 2"
cover: "Living Doll.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/2
  - source/wbtw
---
###### Living Doll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Living Doll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 28 (8d4 + 8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 11 | 13 | 10 | 10 | 7 |
| **Mod** | -4 | +0 | +1 | +0 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** Common
**Saving Throws:** Int +2, Wis +2, Cha +0
**Damage Immunities:** poison
**Condition Immunities:** paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** If the doll is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the doll move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the doll is animate.

**Regeneration.** The doll regains 5 hit points at the start of its turn. If the doll takes fire or psychic damage, this trait doesn't function at the start of the doll's next turn. The doll is destroyed only if it starts its turn with 0 hit points and doesn't regenerate.

**Unusual Nature.** The doll doesn't require air, food, drink, or sleep.


---

### Actions

**Grabby Hands.** Melee Weapon Attack: +2 to hit, reach 5 ft., one creature. *Hit:* The target is grappled (escape DC 6) and takes 11 (2d10) psychic damage at the start of each of its turns until this grapple ends. The doll can grapple only one creature at a time.


---

### Bonus Actions

**Cackle (Recharge 4–6).** The doll cackles as it targets one or two creatures it can see within 30 feet of it. Each target that can hear the doll's cackling must make a DC 11 Wisdom saving throw, succeeding automatically if it has an Intelligence of 4 or lower. On a failed saving throw, the creature takes 5 (2d4) psychic damage and is incapacitated for 1 minute as it is overcome by a fit of laughter. At the end of each of its turns, the creature can repeat the saving throw, ending the effect on itself on a success. A creature that succeeds on this saving throw is immune to this doll's Cackle for 24 hours.


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