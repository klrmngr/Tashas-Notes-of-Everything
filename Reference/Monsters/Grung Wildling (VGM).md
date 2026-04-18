---
type: pc
race: "Humanoid (grung)"
class:
 - "Grung Wildling"
subClass:
 - "CR 1"
cover: "Grung Wildling.png"
campaign:
locations:
tags:
  - race/grung
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/vgm
---
###### Grung Wildling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Grung Wildling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (grung) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13; 16 with barkskin |
> | :FasHeart: HP | 27 (5d6 + 10) |
> | :FasUserGroup: Race | Humanoid (grung) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 16 | 15 | 10 | 15 | 11 |
| **Mod** | -2 | +3 | +2 | +0 | +2 | +0 |

**Speed:** 25 ft., climb 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Grung
**Saving Throws:** Dex +5
**Skills:** Athletics +2, Perception +4, Stealth +5, Survival +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The grung can breathe air and water.

**Poisonous Skin.** Any creature that grapples the grung or otherwise comes into direct contact with the grung's skin must succeed on a DC 12 Constitution saving throw or become poisoned for 1 minute. A poisoned creature no longer in direct contact with the grung can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Standing Leap.** The grung's long jump is up to 25 feet and its high jump is up to 15 feet, with or without a running start.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or take 5 (2d4) poison damage.

**Shortbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or take 5 (2d4) poison damage.


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