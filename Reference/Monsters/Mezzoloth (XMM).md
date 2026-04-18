---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Mezzoloth"
subClass:
 - "CR 5"
cover: "Mezzoloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/xmm
---
###### Mezzoloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mezzoloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 16 | 7 | 14 | 10 |
| **Mod** | +4 | +0 | +3 | -2 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 60 ft., passive Perception 15
**Languages:** Abyssal, Infernal; telepathy 60 ft.
**Skills:** Perception +5
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Fiendish Restoration.** If the mezzoloth dies outside Gehenna, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in Gehenna.

**Magic Resistance.** The mezzoloth has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The mezzoloth makes two attacks, using Claws or Mercurial Trident in any combination.

**Claws.** m +7, reach 5 ft. *Hit:* 9 (2d4 + 4) Slashing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from two of four claws, and it has the Restrained condition until the grapple ends.

**Mercurial Trident.** m,r +7, reach 5 ft. or range 20/60 ft. *Hit:* 8 (1d8 + 4) Piercing damage plus 10 (3d6) Force damage. The trident magically returns to the mezzoloth's claw immediately after a ranged attack.


---

### Bonus Actions

**Teleport (Recharge 5–6).** The mezzoloth teleports up to 60 feet to an unoccupied space it can see. It can teleport one creature it is grappling to an unoccupied space within 5 feet of its destination space.


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