---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Ultroloth"
subClass:
 - "CR 13"
cover: "Ultroloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/13
  - source/mm
---
###### Ultroloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Ultroloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 18 | 18 | 15 | 19 |
| **Mod** | +3 | +3 | +4 | +4 | +2 | +4 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** Abyssal, Infernal, telepathy 120 ft.
**Skills:** Intimidation +9, Perception +7, Stealth +8
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Magic Resistance.** The ultroloth has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The ultroloth's weapon attacks are magical.


---

### Actions

**Multiattack.** The ultroloth can use its Hypnotic Gaze and makes three melee attacks.

**Longsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.

**Hypnotic Gaze.** The ultroloth's eyes sparkle with opalescent light as it targets one creature it can see within 30 feet of it. If the target can see the ultroloth, the target must succeed on a DC 17 Wisdom saving throw against this magic or be charmed until the end of the ultroloth's next turn. The charmed target is stunned. If the target's saving throw is successful, the target is immune to the ultroloth's gaze for the next 24 hours.

**Teleport.** The ultroloth magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


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