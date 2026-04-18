---
type: pc
race: "Plant"
class:
 - "Tri-flower Frond"
subClass:
 - "CR 1/2"
cover: "Tri-flower Frond.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-2
  - source/toa
---
###### Tri-flower Frond
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Tri-flower Frond.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 12 | 9 | 13 | 9 |
| **Mod** | +2 | +2 | +1 | -1 | +1 | -1 |

**Speed:** 5 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 10
**Languages:** —
**Condition Immunities:** blinded; deafened; exhaustion; prone

---

### Actions

**Multiattack.** The tri-flower frond uses its orange blossom, then its yellow blossom, and then its red blossom.

**Orange Blossom.** The tri-flower frond chooses one creature it can see within 5 feet of it. The target must succeed on a DC 11 Constitution saving throw or be poisoned for 1 hour. While poisoned in this way, the target is unconscious. At the end of each minute, the poisoned target can repeat the saving throw, ending the effect on itself on a success.

**Yellow Blossom.** The tri-flower frond chooses one creature it can see within 5 feet of it. The target must succeed on a DC 11 Dexterity saving throw, or it is covered with corrosive sap and takes 5 acid damage at the start of each of its turns. Dousing the target with water reduces the acid damage by 1 point per pint or flask of water used.

**Red Blossom.** Melee Weapon Attack: +2 to hit, reach 5 ft., one creature. *Hit:* 2 (1d4) piercing damage, and the target is grappled (escape DC 11). Until this grapple ends, the target takes 5 (2d4) poison damage at the start of each of its turns. The red blossom can grapple only one target at a time. Another creature within reach of the tri-flower frond can use its action to end the grapple on the target.


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