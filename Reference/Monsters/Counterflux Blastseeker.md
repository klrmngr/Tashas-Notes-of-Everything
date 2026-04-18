---
type: pc
race: "Humanoid (any race)"
class:
 - "Counterflux Blastseeker"
subClass:
 - "CR 2"
cover: "Counterflux Blastseeker.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/ggr
---
###### Counterflux Blastseeker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Counterflux Blastseeker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 15 | 18 | 11 | 14 |
| **Mod** | +1 | +3 | +2 | +4 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any one language
**Saving Throws:** Con +4, Wis +2
**Skills:** Arcana +6, Perception +2

---

### Traits

**Counterflux Overcast (Recharge 5–6).** The blastseeker can create an additional effect immediately after casting a spell. Roll a d6 to determine the effect:
- **1–3..** The blastseeker creates a 15-foot-radius invisible sphere centered on itself that lasts until the end of its next turn. Creatures in the sphere have disadvantage on saving throws against spells and other magical effects.
- **4–6..** The blastseeker creates a 15-foot-radius invisible sphere centered on itself that lasts until the end of its next turn. Creatures in the sphere have advantage on saving throws against spells and other magical effects.


---

### Actions

**Rapier.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.


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