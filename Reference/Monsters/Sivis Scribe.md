---
type: pc
race: "Humanoid (gnome)"
class:
 - "Sivis Scribe"
subClass:
 - "CR 3"
cover: "Sivis Scribe.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/efa
---
###### Sivis Scribe
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Sivis Scribe.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 56 (16d6) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 10 | 16 | 12 | 11 |
| **Mod** | +0 | +2 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Common, Gnomish plus three other languages
**Saving Throws:** Wis +3
**Skills:** Arcana +5, Sleight Of Hand +4

---

### Traits

**Words of Reason.** Allies in a 10-foot Emanation originating from the scribe have Advantage on saving throws to avoid or end the Charmed or Frightened condition. This trait doesn't function if the scribe has the Incapacitated condition.


---

### Actions

**Multiattack.** The scribe makes two Bursting Sigil attacks.

**Bursting Sigil.** m,r +5, reach 5 ft. or range 60 ft. *Hit:* 13 (3d6 + 3) Radiant damage.


---

### Reactions

**Word of Stasis (Recharge 5–6).** con DC 13, each creature in a 20-foot-radius Sphere centered on a point the scribe can see within 60 feet.  The target has the Incapacitated condition until the start of the scribe's next turn. While the target is Incapacitated, its Speed is 0 and can't increase.


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