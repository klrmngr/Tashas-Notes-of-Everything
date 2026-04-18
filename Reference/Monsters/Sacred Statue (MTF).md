---
type: pc
race: "Construct"
class:
 - "Sacred Statue"
subClass:
 - "CR —"
cover: "Sacred Statue.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/—
  - source/mtf
---
###### Sacred Statue
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Sacred Statue.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 8 | 19 | 14 | 19 | 16 |
| **Mod** | +4 | -1 | +4 | +2 | +4 | +3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** the languages the eidolon knew in life
**Saving Throws:** Wis +8
**Damage Resistances:** acid; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** While the statue remains motionless, it is indistinguishable from a normal statue.

**Ghostly Inhabitant.** The eidolon that enters the sacred statue remains inside it until the statue drops to 0 hit points, the eidolon uses a bonus action to move out of the statue, or the eidolon is turned or forced out by an effect such as the dispel evil and good spell. When the eidolon leaves the statue, it appears in an unoccupied space within 5 feet of the statue.

**Inert.** When not inhabited by an eidolon, the statue is an object.


---

### Actions

**Multiattack.** The statue makes two slam attacks.

**Slam.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 43 (6d12 + 4) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +8 to hit, range 60/240 ft., one target. *Hit:* 37 (6d10 + 4) bludgeoning damage.


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