---
type: pc
race: "Giant (wizard)"
class:
 - "Fomorian Noble"
subClass:
 - "CR 15"
cover: "Fomorian Noble.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/15
  - source/bgg
---
###### Fomorian Noble
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fomorian Noble.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Giant (wizard) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14; 17 with mage armor |
> | :FasHeart: HP | 253 (22d12 + 110) |
> | :FasUserGroup: Race | Giant (wizard) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 18 | 20 | 19 | 14 | 16 |
| **Mod** | +6 | +4 | +5 | +4 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Giant plus any three languages
**Saving Throws:** Int +9, Wis +7, Cha +8
**Skills:** Arcana +14, Perception +7, Stealth +9
**Condition Immunities:** charmed

---

### Actions

**Multiattack.** The fomorian makes three Rod attacks.

**Rod.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage plus 11 (2d10) force damage.


---

### Bonus Actions

**Beguiling Presence.** The fomorian targets a creature it can see within 60 feet of itself. The target must succeed on a DC 17 Wisdom saving throw or have the charmed condition for 1 minute. An affected target can repeat the saving throw at the end of each of its turns and whenever it takes damage, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target becomes immune to all fomorians' Beguiling Presence for the next 24 hours.


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