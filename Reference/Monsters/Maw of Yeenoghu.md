---
type: pc
race: "Fiend (demon)"
class:
 - "Maw of Yeenoghu"
subClass:
 - "CR 10"
cover: "Maw of Yeenoghu.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/10
  - source/bgg
---
###### Maw of Yeenoghu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Maw of Yeenoghu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 161 (14d12 + 70) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 8 | 14 | 10 |
| **Mod** | +6 | +0 | +5 | -1 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Abyssal, Giant
**Saving Throws:** Con +9, Cha +4
**Skills:** Perception +6

---

### Traits

**Magic Resistance.** The maw has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The maw makes two Bite or Fang Fling attacks.

**Bite.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 19 (2d12 + 6) piercing damage.

**Fang Fling.** Ranged Weapon Attack: +10 to hit, range 30/90 ft., one target. *Hit:* 11 (1d10 + 6) piercing damage.

**Gorging Charge (Recharge 5–6).** The maw moves up to its speed without provoking opportunity attacks and can move through the spaces of Large or smaller creatures. Each time the maw enters a creature's space for the first time during this move, that creature must succeed on a DC 18 Strength saving throw or take 25 (3d12 + 6) piercing damage and have the grappled condition (escape DC 16); if a creature is already grappled this way, it has the prone condition. Until this grapple ends, the target has the restrained condition. The maw can have only one creature grappled in this way at a time.


---

### Reactions

**Fanged Rebuke.** In response to taking damage, the maw makes one Bite attack against a random creature within 10 feet of itself. If no creature is within reach, the maw can make two Fang Fling attacks.


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