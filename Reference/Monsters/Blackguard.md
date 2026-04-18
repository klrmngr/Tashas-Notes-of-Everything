---
type: pc
race: "Humanoid (paladin)"
class:
 - "Blackguard"
subClass:
 - "CR 8"
cover: "Blackguard.png"
campaign:
locations:
tags:
  - race/paladin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/mpmm
---
###### Blackguard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Blackguard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (paladin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 119 (14d8 + 56) |
> | :FasUserGroup: Race | Humanoid (paladin) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 18 | 11 | 14 | 15 |
| **Mod** | +4 | +0 | +4 | +0 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** any one language (usually Common)
**Saving Throws:** Wis +5, Cha +5
**Skills:** Athletics +7, Deception +5, Intimidation +5

---

### Actions

**Multiattack.** The blackguard makes three attacks, using Glaive, Shortbow, or both.

**Glaive.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) slashing damage plus 9 (2d8) necrotic damage.

**Shortbow.** Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Dreadful Aspect (Recharges after a Short or Long Rest).** Each enemy within 30 feet of the blackguard must succeed on a DC 13 Wisdom saving throw or be frightened of the blackguard for 1 minute. If a frightened target ends its turn more than 30 feet away from the blackguard, the target can repeat the saving throw, ending the effect on itself on a success.


---

### Bonus Actions

**Smite.** Immediately after the blackguard hits a target with an attack roll, the blackguard can force that target to make a DC 13 Constitution saving throw. On a failed save, the target suffers one of the following effects of the blackguard's choice:

**Blind.** The target is blinded for 1 minute. The blinded target can repeat the save at the end of each of its turns, ending the effect on itself on a success.

**Shove.** The target is pushed up to 10 feet away and knocked prone.


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