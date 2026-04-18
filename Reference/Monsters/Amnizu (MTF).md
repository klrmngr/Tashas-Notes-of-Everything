---
type: pc
race: "Fiend (devil)"
class:
 - "Amnizu"
subClass:
 - "CR 18"
cover: "Amnizu.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/18
  - source/mtf
---
###### Amnizu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Amnizu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 202 (27d8 + 81) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 13 | 16 | 20 | 12 | 18 |
| **Mod** | +0 | +1 | +3 | +5 | +1 | +4 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Common, Infernal, telepathy 1,000 ft.
**Saving Throws:** Dex +7, Con +9, Wis +7, Cha +10
**Skills:** Perception +7
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the amnizu's darkvision.

**Magic Resistance.** The amnizu has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The amnizu uses Poison Mind. It also makes two attacks: one with its whip and one with its Disruptive Touch.

**Taskmaster Whip.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 10 (2d4 + 5) slashing damage plus 33 (6d10) force damage.

**Disruptive Touch.** Melee Spell Attack: +11 to hit, reach 5 ft., one target. *Hit:* 44 (8d10) necrotic damage.

**Poison Mind.** The amnizu targets one or two creatures that it can see within 60 feet of it. Each target must succeed on a DC 19 Wisdom saving throw or take 26 (4d12) necrotic damage and is blinded until the start of the amnizu's next turn.

**Forgetfulness (Recharge 6).** The amnizu targets one creature it can see within 60 feet of it. That creature must make a DC 18 Intelligence saving throw and on a failure the target is stunned for 1 minute. A stunned creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. If the target remains stunned for the full minute, it forgets everything it sensed, experienced, and learned during the last 5 hours.


---

### Reactions

**Instinctive Charm.** When a creature within 60 feet of the amnizu makes an attack roll against it, and another creature is within the attack's range, the attacker must make a DC 19 Wisdom saving throw. On a failed save, the attacker must target the creature that is closest to it, not including the amnizu or itself. If multiple creatures are closest, the attacker chooses which one to target. If the saving throw is successful, the attacker is immune to the amnizu's Instinctive Charm for 24 hours.


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