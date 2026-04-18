---
type: pc
race: "Monstrosity"
class:
 - "Achaierai"
subClass:
 - "CR 5"
cover: "Achaierai.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/mabjov
---
###### Achaierai
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Achaierai.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 10 | 12 | 14 |
| **Mod** | +4 | +2 | +2 | +0 | +1 | +2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Infernal
**Skills:** Perception +4

---

### Traits

**Magic Resistance.** The achaierai has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The achaierai makes two attacks with its Talons and one attack with its Beak.

**Beak.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (3d6 + 4) piercing damage.

**Talons.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage.


---

### Bonus Actions

**Spring Attack.** The achaierai takes the Disengage action.


---

### Reactions

**Defensive Cloud.** After taking damage the achaierai can use its reaction to release a cloud of poisonous gas in a 10-foot-radius. All creatures in the cloud take 7 (2d6) poison damage and must succeed on a DC 15 Constitution saving throw or be poisoned for 1 minute. While poisoned the target is confused as if from a confusion spell. At the end of its turns, the affected target can repeat the Constitution saving throw. If it succeeds the confusion ends. Achaierai are immune to the effects of this cloud.


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