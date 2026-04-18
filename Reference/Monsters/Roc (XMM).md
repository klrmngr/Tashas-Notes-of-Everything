---
type: pc
race: "Monstrosity"
class:
 - "Roc"
subClass:
 - "CR 11"
cover: "Roc.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/11
  - source/xmm
---
###### Roc
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Roc.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 248 (16d20 + 80) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 10 | 20 | 3 | 10 | 9 |
| **Mod** | +9 | +0 | +5 | -4 | +0 | -1 |

**Speed:** 20 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** —
**Saving Throws:** Dex +4, Wis +4
**Skills:** Perception +8

---

### Actions

**Multiattack.** The roc makes two Beak attacks. It can replace one attack with a Talons attack.

**Beak.** m +13, reach 10 ft. *Hit:* 28 (3d12 + 9) Piercing damage.

**Talons.** m +13, reach 5 ft. *Hit:* 23 (4d6 + 9) Slashing damage. If the target is a Huge or smaller creature, it has the Grappled condition (escape DC 19) from both talons, and it has the Restrained condition until the grapple ends.


---

### Bonus Actions

**Swoop (Recharge 5–6).** If the roc has a creature Grappled, the roc flies up to half its Fly Speed without provoking Opportunity Attacks and drops that creature.


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