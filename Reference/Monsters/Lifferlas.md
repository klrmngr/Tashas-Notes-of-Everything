---
type: pc
race: "Plant"
class:
 - "Lifferlas"
subClass:
 - "CR —"
cover: "Lifferlas.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/—
  - source/skt
---
###### Lifferlas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Lifferlas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 59 (7d12 + 14) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 6 | 15 | 10 | 10 | 7 |
| **Mod** | +4 | -2 | +2 | +0 | +0 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing

---

### Traits

**False Appearance.** While Lifferlas remains motionless, it is indistinguishable from a normal tree.

**Roleplaying Information.** A druid of the Emerald Enclave awakened the tree Lifferlas with a spell. Goldenfields is his home, its people his friends. Children like to carve their name and initials into his body and hang from his boughs, and he's happy with that.
Ideal: "I exist to protect the people and plants of Goldenfields."
Bond: "Children are wonderful. I would do anything to make them feel happy and safe."
Flaw: "I can't remember people's names and often get them mixed up."


---

### Actions

**Multiattack.** Lifferlas makes two slam attacks.

**Slam.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 14 (3d6 + 4) bludgeoning damage.


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