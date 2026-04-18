---
type: pc
race: "Monstrosity (lizardfolk)"
class:
 - "Ssurran Poisoner"
subClass:
 - "CR 1/2"
cover: "Ssurran Poisoner.png"
campaign:
locations:
tags:
  - race/lizardfolk
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-2
  - source/bam
---
###### Ssurran Poisoner
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Ssurran Poisoner.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (lizardfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor, shield) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Monstrosity (lizardfolk) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 12 | 13 | 12 | 12 | 7 |
| **Mod** | +1 | +1 | +1 | +1 | +1 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Draconic
**Skills:** Perception +3, Stealth +3, Survival +3

---

### Traits

**Hold Breath.** The ssurran can hold its breath for 15 minutes.


---

### Actions

**Multiattack.** The ssurran makes two Claw attacks.

**Claw.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) slashing damage.

**Javelin.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage plus 4 (1d8) poison damage.

**Poison Bomb.** The ssurran throws a tangerine-sized bomb at a point up to 60 feet away, where it explodes, releasing a 10-foot-radius sphere of poisonous gas that disperses quickly. Each creature in the sphere must make a DC 11 Constitution saving throw, taking 10 (3d6) poison damage on a failed save, or half as much damage on a successful one. After the ssurran throws a bomb, roll a d6; on a roll of 4 or lower, the ssurran has no more bombs to throw.


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