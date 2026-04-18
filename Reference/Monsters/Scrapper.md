---
type: pc
race: "Construct"
class:
 - "Scrapper"
subClass:
 - "CR 8"
cover: "Scrapper.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/8
  - source/mismv1
---
###### Scrapper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MisMV1
___

> [!infobox|no-t right]
> ![[Scrapper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 126 (12d10 + 60) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MisMV1 |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 20 | 3 | 10 | 1 |
| **Mod** | +5 | +0 | +5 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** understands the languages of its creator but can't speak
**Skills:** Perception +6
**Damage Resistances:** lightning
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Electrified Chassis.** A creature that hits the scrapper with a melee attack while within 5 feet of it takes 19 (3d12) lightning damage.


---

### Actions

**Multiattack.** The scrapper makes two Spike Punch attacks. It can replace one of those with a Wires attack.

**Spike Punch.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage plus 5 (1d10) piercing damage.

**Wires.** Melee Weapon Attack: +8 to hit, reach 20 ft., one Large or smaller creature. *Hit:* The target has the grappled condition (escape DC 16) and must succeed on a DC 16 Strength saving throw or be pulled into an unoccupied space within 5 feet of the scrapper and take 19 (3d12) lightning damage. The scrapper can have only one creature grappled in this way at a time.

**Eye Beam (Recharge 5–6).** The scrapper shoots a magical beam from its extended eye at one creature it can see within 120 feet of itself. The target must make a DC 16 Dexterity saving throw, taking 44 (8d10) force damage on a failed save, or half as much damage on a successful one.


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