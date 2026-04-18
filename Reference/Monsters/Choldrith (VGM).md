---
type: pc
race: "Monstrosity"
class:
 - "Choldrith"
subClass:
 - "CR 3"
cover: "Choldrith.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/vgm
---
###### Choldrith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Choldrith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 12 | 11 | 14 | 10 |
| **Mod** | +1 | +3 | +1 | +0 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Undercommon
**Skills:** Athletics +5, Religion +2, Stealth +5

---

### Traits

**Fey Ancestry.** The choldrith has advantage on saving throws against being charmed, and magic can't put the choldrith to sleep.

**Spider Climb.** The choldrith can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Sensitivity.** While in sunlight, the choldrith has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Web Sense.** While in contact with a web, the choldrith knows the exact location of any other creature in contact with the same web.

**Web Walker.** The choldrith ignores movement restrictions caused by webbing.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 10 (3d6) poison damage.

**Web (Recharge 5–6).** Ranged Weapon Attack: +5 to hit, range 30/60 ft., one Large or smaller creature. *Hit:* The target is restrained by webbing. As an action, the restrained target can make a DC 11 Strength check, bursting the webbing on a success. The webbing can also be attacked and destroyed (AC 10; 5 hit points; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage).


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