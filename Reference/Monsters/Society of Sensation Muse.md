---
type: pc
race: "Humanoid"
class:
 - "Society of Sensation Muse"
subClass:
 - "CR 3"
cover: "Society of Sensation Muse.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/mpp
---
###### Society of Sensation Muse
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Society of Sensation Muse.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 12 | 15 | 14 | 17 |
| **Mod** | -1 | +3 | +1 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus two more languages
**Saving Throws:** Dex +5, Cha +5
**Skills:** Insight +4, Perception +4, Performance +7, Stealth +5

---

### Actions

**Multiattack.** The muse makes two Beguiling Resonance attacks.

**Beguiling Resonance.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 90 ft., one target. *Hit:* 9 (2d8) psychic damage. If the target is a creature, it must succeed on a DC 13 Charisma saving throw or have disadvantage on the next attack roll it makes until the end of its next turn.


---

### Bonus Actions

**Enchanting Presence.** Each creature within 30 feet of the muse must make a DC 13 Wisdom saving throw. On a failed save, the creature has the charmed condition for 1 minute. On a successful save, the creature becomes immune to any muse's Enchanting Presence for 24 hours.
Whenever the muse deals damage to the charmed creature, the charmed creature can repeat the saving throw, ending the effect on itself on a success.


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