---
type: pc
race: "Construct"
class:
 - "Caldron Magen"
subClass:
 - "CR 4"
cover: "Caldron Magen.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/4
  - source/nf
---
###### Caldron Magen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NF
___

> [!infobox|no-t right]
> ![[Caldron Magen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | NF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 10 | 10 | 10 |
| **Mod** | +4 | +1 | +3 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** understands Common plus two other languages but can't speak
**Skills:** Perception +4
**Damage Immunities:** acid; poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Disintegration.** If the magen dies, it disintegrates into dust, leaving behind anything it was wearing or carrying.

**Magic Resistance.** The magen has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The magen makes two attacks, using Extended Fist or Acid Spittle in any combination.

**Extended Fist.** m +6, reach 15 ft. *Hit:* 8 (1d8 + 4) Bludgeoning damage plus 5 (1d10) Acid damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 14) from one of two fists.

**Acid Spittle.** r +6, range 60 ft. *Hit:* 13 (2d8 + 4) Acid damage.


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