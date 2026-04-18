---
type: pc
race: "Humanoid (human)"
class:
 - "Flamewrath"
subClass:
 - "CR 6"
cover: "Flamewrath.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/pota
---
###### Flamewrath
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Flamewrath.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 16 | 11 | 10 | 16 |
| **Mod** | +0 | +2 | +3 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Ignan
**Skills:** Arcana +3, Religion +3
**Damage Immunities:** fire

---

### Traits

**Wreathed in Flame.** For the flamewrath, the warm version of the fire shield spell has a duration of "until dispelled." The fire shield burns for 10 minutes after the flamewrath dies, consuming its body.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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