---
type: pc
race: "Aberration"
class:
 - "Tsucora Quori"
subClass:
 - "CR 7"
cover: "Tsucora Quori.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/7
  - source/erlw
---
###### Tsucora Quori
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Tsucora Quori.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 68 (8d8 + 32) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 18 | 14 | 14 | 16 |
| **Mod** | +3 | +2 | +4 | +2 | +2 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Quori
**Saving Throws:** Wis +5, Cha +6
**Skills:** Insight +5, Perception +5
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The quori makes three attacks: one pincer attack, one attack with its claws, and one stinger attack.

**Pincer.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) bludgeoning damage. The target is grappled (escape DC 14) if it is a Large or smaller creature. The quori has two pincers, each of which can grapple one target.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (4d4 + 3) slashing damage.

**Stinger.** Melee Weapon Attack: +6 to hit, reach 10 ft., one creature. *Hit:* 8 (1d10 + 3) piercing damage plus 10 (3d6) psychic damage, and the target must succeed on a DC 14 Wisdom saving throw or be frightened of the quori for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Possession (Recharge 6).** One humanoid that the quori can see within 5 feet of it must succeed on a DC 14 Charisma saving throw or be possessed by the quori; the quori then disappears, and the target is incapacitated and loses control of its body. The quori now controls the body but doesn't deprive the target of awareness. The quori can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being charmed and frightened. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.
The possession lasts until the body drops to 0 hit points, the quori ends it as a bonus action, or the quori is forced out by an effect like the dispel evil and good spell. When the possession ends, the quori reappears in an unoccupied space within 5 feet of the body. The target is immune to this quori's Possession for 24 hours after succeeding on the saving throw or after the possession ends.


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