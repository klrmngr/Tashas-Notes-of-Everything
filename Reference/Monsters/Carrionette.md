---
type: pc
race: "Construct"
class:
 - "Carrionette"
subClass:
 - "CR 1"
cover: "Carrionette.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1
  - source/vrgr
---
###### Carrionette
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Carrionette.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 12 | 8 | 14 | 14 |
| **Mod** | +0 | +2 | +1 | -1 | +2 | +2 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** understands the languages of its creator
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**False Object.** If the carrionette is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the carrionette move or act, that creature must succeed on a DC 15 Wisdom (Perception) check to discern that the carrionette is animate.

**Unusual Nature.** The carrionette doesn't require air, food, drink, or sleep.


---

### Actions

**Silver Needle.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 1 piercing damage plus 3 (1d6) necrotic damage, and the target must succeed on a DC 12 Charisma saving throw or become cursed for 1 minute. While cursed in this way, the target's speed is reduced by 10 feet, and it must roll a 1d4 and subtract the number rolled from each ability check or attack roll it makes.

**Soul Swap.** The carrionette targets a creature it can see within 15 feet of it that is cursed by its Silver Needle. Unless the target is protected by a protection from evil and good spell, it must succeed on a DC 12 Charisma saving throw or have its consciousness swapped with the carrionette. The carrionette gains control of the target's body, and the target is unconscious for 1 hour, after which it gains control of the carrionette's body. While controlling the target's body, the carrionette retains its Intelligence, Wisdom, and Charisma scores. It otherwise uses the controlled body's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.
If the carrionette's body is destroyed, both the carrionette and the target die. A protection from evil and good spell cast on the controlled body drives the carrionette out and returns the consciousness of both creatures to their original bodies. The swap is also undone if the controlled body takes damage from the carrionette's Silver Needle.


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