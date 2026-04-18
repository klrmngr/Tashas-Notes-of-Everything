---
type: pc
race: "Plant"
class:
 - "Assassin Vine"
subClass:
 - "CR 3"
cover: "Assassin Vine.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/3
  - source/toa
---
###### Assassin Vine
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Assassin Vine.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 16 | 1 | 10 | 1 |
| **Mod** | +4 | +0 | +3 | -5 | +0 | -5 |

**Speed:** 5 ft., climb 5 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** cold; fire
**Condition Immunities:** blinded; deafened; exhaustion; prone

---

### Traits

**False Appearance.** While the assassin vine remains motionless, it is indistinguishable from a normal plant.


---

### Actions

**Constrict.** Melee Weapon Attack: +6 to hit, reach 20 ft., one creature. *Hit:* The target takes 11 (2d6 + 4) bludgeoning damage, and it is grappled (escape DC 14). Until this grapple ends, the target is restrained, and it takes 21 (6d6) poison damage at the start of each of its turns. The vine can constrict only one target at a time.

**Entangling Vines.** The assassin vine can animate normal vines and roots on the ground in a 15-foot square within 30 feet of it. These plants turn the ground in that area into 3. A creature in that area when the effect begins must succeed on a DC 13 Strength saving throw or be restrained by entangling vines and roots. A creature restrained by the plants can use its action to make a DC 13 Strength (Athletics) check, freeing itself on a successful check. The effect ends after 1 minute or when the assassin vine dies or uses Entangling Vines again.


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