---
type: pc
race: "Humanoid"
class:
 - "Grung Wildling"
subClass:
 - "CR 1"
cover: "Grung Wildling.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/mpmm
---
###### Grung Wildling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Grung Wildling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 27 (5d6 + 10) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Water Dependency.** If the grung isn't immersed in water for at least 1 hour during a day, it suffers 1 level of exhaustion at the end of that day. The grung can recover from this exhaustion only through magic or by immersing itself in water for at least 1 hour.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 5 (2d4) poison damage.

**Shortbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 5 (2d4) poison damage.


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