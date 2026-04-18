---
type: pc
race: "Aberration"
class:
 - "Encephalon Gemmule"
subClass:
 - "CR 3"
cover: "Encephalon Gemmule.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/3
  - source/pabtso
---
###### Encephalon Gemmule
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Encephalon Gemmule.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 54 (12d4 + 24) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 18 | 14 | 5 | 12 | 7 |
| **Mod** | -5 | +4 | +2 | -3 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (can't see beyond this radius), passive Perception 11
**Languages:** —
**Damage Resistances:** psychic
**Condition Immunities:** blinded

---

### Traits

**Encephalon Progeny.** The gemmule matures into an encephalon cluster if not killed within 30 (4d12 + 4) days of its creation.

**Magic Resistance.** The gemmule has advantage on saving throws against spells and other magical effects.


---

### Actions

**Psychic Slam.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 16 (3d10) psychic damage.


---

### Bonus Actions

**Leech.** The gemmule targets one creature within 5 feet of itself and forces the target to make a DC 14 Dexterity saving throw. On a failed save, the gemmule enters the target's space and attaches to the target. While the gemmule is attached, the target takes 7 (3d4) piercing damage at the start of each of its turns, and the gemmule can't use Leech again until it detaches. It can detach itself by spending 5 feet of its movement. As an action, the target or a creature within 5 feet of the target can detach the gemmule by succeeding on a DC 15 Strength check.


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