---
type: pc
race: "Aberration"
class:
 - "Hashalaq Quori"
subClass:
 - "CR 9"
cover: "Hashalaq Quori.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/9
  - source/erlw
---
###### Hashalaq Quori
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Hashalaq Quori.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 13 | 18 | 16 | 18 |
| **Mod** | +1 | +2 | +1 | +4 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Quori
**Saving Throws:** Wis +7, Cha +8
**Skills:** Arcana +12, History +12, Insight +11, Persuasion +8
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The quori uses its Mind Thrust twice.

**Idyllic Touch.** Melee Spell Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) force damage. If the target is a creature, it must succeed on a DC 16 Wisdom saving throw or fall prone in a fit of laughter.

**Mind Thrust.** The quori targets a creature it can see within 60 feet of it. The target must make a DC 16 Wisdom saving throw, taking 18 (4d8) psychic damage on a failed save, or half as much damage on a successful one.

**Possession (Recharge 6).** One humanoid that the quori can see within 5 feet of it must succeed on a DC 16 Charisma saving throw or be possessed by the quori; the quori then disappears, and the target is incapacitated and loses control of its body. The quori now controls the body but doesn't deprive the target of awareness. The quori can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being charmed and frightened. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.
The possession lasts until the body drops to 0 hit points, the quori ends it as a bonus action, or the quori is forced out by an effect like the dispel evil and good spell. When the possession ends, the quori reappears in an unoccupied space within 5 feet of the body. The target is immune to this quori's Possession for 24 hours after succeeding on the saving throw or after the possession ends.


---

### Reactions

**Empathic Feedback.** When the quori takes damage from a creature it can see within 60 feet of it, the quori can force that creature to succeed on a DC 16 Intelligence saving throw or take 11 (2d10) psychic damage.


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