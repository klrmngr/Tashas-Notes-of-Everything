---
type: pc
race: "Aberration"
class:
 - "Nightmare Haunt"
subClass:
 - "CR 5"
cover: "Nightmare Haunt.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/5
  - source/mcv4ec
---
###### Nightmare Haunt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Nightmare Haunt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 13 | 9 | 12 | 17 |
| **Mod** | +2 | +3 | +1 | -1 | +1 | +3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (can't see beyond this radius), passive Perception 11
**Languages:** Deep Speech, telepathy 120 ft.
**Damage Immunities:** psychic
**Condition Immunities:** blinded; charmed; exhaustion; frightened

---

### Traits

**Magic Resistance.** The nightmare haunt has advantage on saving throws against spells and other magical effects.

**Somnophage.** At the start of its turn, the nightmare haunt gains a number of temporary hit points equal to 5 times the number of unconscious creatures within 30 feet of itself.


---

### Actions

**Multiattack.** The nightmare haunt makes two Claw attacks.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage plus 9 (2d8) psychic damage.

**Tendrils of Slumber (Recharge 5–6).** The nightmare haunt creates spectral tendrils that cover the ground in a 20-foot square that it can see within 30 feet of itself for 1 minute or until it uses this action again. When a creature other than the nightmare haunt enters the affected area for the first time or starts its turn there, the creature must succeed on a DC 14 Strength saving throw or take 11 (2d10) necrotic damage and have the restrained condition. The affected ground is also considered difficult terrain for creatures other than the nightmare haunt for the duration of its effect.
A creature that starts its turn in the area and is already restrained by the tendrils must repeat the saving throw. On a failed save, it has the unconscious condition and instead of the restrained condition caused by the tendrils. On a successful save, the effect ends on the creature. An unconscious creature remains asleep until it is no longer in the area with tendrils, takes any damage, or is targeted by a remove curse spell or similar magic.


---

### Bonus Actions

**Shadow Stealth.** While in dim light or darkness, the nightmare haunt takes the Hide action.


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