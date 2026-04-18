---
type: pc
race: "Humanoid (human)"
class:
 - "Borivik Windheim"
subClass:
 - "CR 10"
cover: "Borivik Windheim.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/mabjov
---
###### Borivik Windheim
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Borivik Windheim.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (studded leather) |
> | :FasHeart: HP | 195 (30d8 + 60) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 20 | 14 | 11 | 16 | 11 |
| **Mod** | +0 | +5 | +2 | +0 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 21
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Dex +9, Wis +7
**Skills:** Nature +8, Perception +11, Stealth +13, Survival +11

---

### Traits

**Bolts of Undead Slaying.** Borivik has a half-dozen bolts of undead slaying. If he strikes an Undead creature with one of these magic bolts, it must make a DC 17 Constitution saving throw, taking an extra 33 (6d10) piercing damage on a failed save, or half as much extra damage on a successful one.


---

### Actions

**Multiattack.** Borivik makes two Shortsword attacks or two Heavy Crossbow attacks.

**Shortsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage.

**Heavy Crossbow.** Ranged Weapon Attack: +9 to hit, ranged 100/400 ft., one target. *Hit:* 10 (1d10 + 5) piercing damage.


---

### Bonus Actions

**Crossbow Expert.** Borivik adds 1d10 to his next attack or damage roll with his Heavy Crossbow attack.

**Nimble Escape.** Borivik can take the Disengage or Hide action.


---

### Reactions

**Enduring Response.** When Borivik takes acid, cold, fire, lightning, or thunder damage, he gains immunity to that damage type until the start of his next turn. Also, the first time he hits with a Shortsword attack on his next turn, the target takes an extra 10 (3d6) of the triggering damage type.


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