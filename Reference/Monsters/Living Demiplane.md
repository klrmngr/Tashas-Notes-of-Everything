---
type: pc
race: "Construct"
class:
 - "Living Demiplane"
subClass:
 - "CR 0"
cover: "Living Demiplane.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/0
  - source/idrotf
---
###### Living Demiplane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Living Demiplane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 10 | 10 | 1 | 10 | 1 |
| **Mod** | -5 | +0 | +0 | -5 | +0 | -5 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned; unconscious

---

### Traits

**Dimensional Form.** The living spell can enter another creature's space and vice versa, and it can move through a space as narrow as 1 inch wide without squeezing. The living spell can't detach from a solid surface, such as a wall, ceiling, or floor. If it has no surface to attach to, the living spell is destroyed (see "Planar Destruction" below).

**Extradimensional Chamber.** When the living spell enters another creature's space (or vice versa) for the first time on a turn, the other creature must succeed on a DC 10 Dexterity saving throw or be pulled into the living spell's extradimensional space, an unfurnished stone chamber 30 feet in every dimension. A creature too big to fit in this space succeeds on the saving throw automatically. Creatures in the chamber never run out of breathable air. Magic that enables transit between planes, such as plane shift, can be used to escape the chamber, which has no exits otherwise. Creatures trapped inside the extradimensional chamber can't see, target, or deal damage to the living spell; however, they can damage the room around them. Each 5-foot-square section of ceiling, wall, and floor in the chamber has AC 17, 50 hit points, immunity to poison and psychic damage, and immunity to bludgeoning, piercing, and slashing damage that is nonmagical. If any section is reduced to 0 hit points, the living spell and its chamber are destroyed (see "Planar Destruction" below).

**Magic Resistance.** The living spell has advantage on saving throws against spells and other magical effects.

**Planar Destruction.** The living spell is destroyed when it or a 5-foot-square section of its extradimensional chamber is reduced to 0 hit points, or when the living spell has no surface to attach to. When the living spell is destroyed, the contents of its extradimensional chamber are expelled, appearing as close to the living spell's previous location as possible. Each expelled creature appears in a randomly determined unoccupied space, along with whatever it is wearing or carrying.

**Unusual Nature.** The living spell doesn't require air, food, drink, or sleep.


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