---
type: pc
race: "Monstrosity"
class:
 - "Tlincalli"
subClass:
 - "CR 5"
cover: "Tlincalli.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/mpmm
---
###### Tlincalli
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Tlincalli.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 16 | 8 | 12 | 8 |
| **Mod** | +3 | +1 | +3 | -1 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Tlincalli
**Skills:** Perception +4, Stealth +4, Survival +4

---

### Actions

**Multiattack.** The tlincalli makes one Longsword or Spiked Chain attack and one Sting attack.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.

**Spiked Chain.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, and the target is grappled (escape DC 11) if it is a Large or smaller creature. Until this grapple ends, the target is restrained, and the tlincalli can't use the spiked chain against another target.

**Sting.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 6 (1d6 + 3) piercing damage plus 14 (4d6) poison damage, and the target must succeed on a DC 14 Constitution saving throw or be poisoned for 1 minute. If it fails the saving throw by 5 or more, the target is also paralyzed while poisoned. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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