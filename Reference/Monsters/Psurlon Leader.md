---
type: pc
race: "Aberration"
class:
 - "Psurlon Leader"
subClass:
 - "CR 6"
cover: "Psurlon Leader.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/bam
---
###### Psurlon Leader
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Psurlon Leader.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (mage armor) |
> | :FasHeart: HP | 127 (17d8 + 51) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 20 | 11 | 7 |
| **Mod** | +3 | +2 | +3 | +5 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 16
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Wis +3, Cha +1
**Skills:** Perception +6
**Damage Resistances:** psychic
**Condition Immunities:** blinded; charmed

---

### Traits

**Aberrant Mind.** Magic can't read the psurlon's thoughts or put the psurlon to sleep.

**Two Heads.** The psurlon has advantage on saving throws it makes to avoid or end the frightened, stunned, or unconscious condition on itself. While one of the psurlon's heads is asleep, its other head is awake.


---

### Actions

**Multiattack.** The psurlon makes two Bite attacks and two Claw attacks. It can also use Pacify (if available) or Psychic Crush.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 7 (1d8 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) slashing damage.

**Pacify (Recharge 5–6).** The psurlon targets one creature it can see within 120 feet of itself. The target must succeed on a DC 16 Wisdom saving throw or fall unconscious for 10 minutes. The condition ends if the target takes any damage or if another creature uses its action to shake the target awake.

**Psychic Crush.** The psurlon targets one creature it can see within 120 feet of itself. The target must make a DC 16 Wisdom saving throw, taking 21 (3d10 + 5) psychic damage on a failed save, or half as much damage on a successful one.


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