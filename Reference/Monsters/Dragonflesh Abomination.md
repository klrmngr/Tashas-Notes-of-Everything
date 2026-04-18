---
type: pc
race: "Monstrosity"
class:
 - "Dragonflesh Abomination"
subClass:
 - "CR 6"
cover: "Dragonflesh Abomination.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/6
  - source/ftd
---
###### Dragonflesh Abomination
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragonflesh Abomination.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 66 (7d12 + 21) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 17 | 5 | 12 | 6 |
| **Mod** | +4 | +2 | +3 | -3 | +1 | -2 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** understands Common and Draconic but can't speak
**Saving Throws:** Str +7, Con +6
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Cloying Miasma.** The abomination is surrounded by a noxious stench. At the start of the abomination's turn, any creature within 5 feet of it must succeed on a DC 14 Constitution saving throw or be poisoned until the start of the abomination's next turn.

**Regeneration.** The abomination regains 10 hit points at the start of its turns if it has at least 1 hit point.


---

### Actions

**Multiattack.** The abomination makes three attacks using Claw, Acidic Spit, or a combination of them. It can replace one of the attacks with a Tail attack.

**Claw.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 5 (1d10) poison damage.

**Tail.** Melee Weapon Attack: +7 to hit, reach 15 ft., one target. *Hit:* 10 (1d12 + 4) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.

**Acidic Spit.** Ranged Weapon Attack: +5 to hit, range 60 ft., one target. *Hit:* 10 (3d6) acid damage.

**Acid Belch (Recharge 5–6).** The abomination belches forth a cloud of acidic gas in a 30-foot cone. Each creature in that area must make a DC 14 Constitution saving throw, taking 28 (8d6) acid damage on a failed save, or half as much damage on a successful one.


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