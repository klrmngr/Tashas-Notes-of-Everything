---
type: pc
race: "Construct"
class:
 - "Burnished Hart"
subClass:
 - "CR 2"
cover: "Burnished Hart.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/2
  - source/mot
---
###### Burnished Hart
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Burnished Hart.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 16 | 3 | 15 | 1 |
| **Mod** | +3 | +2 | +3 | -4 | +2 | -5 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** understands one language of its creator but can't speak
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Charge.** If the hart moves at least 20 feet straight toward a target and then hits it with an antlers attack on the same turn, the target takes an extra 7 (2d6) fire damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked prone.

**Heated Body.** A creature that touches the hart or hits it with a melee attack while within 5 feet of it takes 5 (1d10) fire damage.

**Sure-Footed.** The hart has advantage on Strength and Dexterity saving throws made against effects that would knock it prone.


---

### Actions

**Multiattack.** The hart makes two attacks: one with its antlers and one with its hooves.

**Antlers.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.

**Hooves.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage plus 2 (1d4) fire damage.


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