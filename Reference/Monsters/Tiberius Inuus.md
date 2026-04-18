---
type: pc
race: "Humanoid (human)"
class:
 - "Tiberius Inuus"
subClass:
 - "CR 9"
cover: "Tiberius Inuus.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mabjov
---
###### Tiberius Inuus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Tiberius Inuus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 170 (20d8 + 80) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 18 | 11 | 11 | 16 |
| **Mod** | +4 | +1 | +4 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Celestial, Common
**Saving Throws:** Con +8, Wis +4
**Skills:** Persuasion +7, Religion +4

---

### Traits

**Brave.** Tiberius Inuus has advantage on saving throws against being frightened.


---

### Actions

**Multiattack.** Tiberius Inuus makes three Flame Tongue attacks.

**Flame Tongue.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 7 (2d6) fire damage.

**Heavy Crossbow.** Ranged Weapon Attack: +5 to hit, range 100/400 ft., one target. *Hit:* 6 (1d10 + 1) piercing damage.

**Touch of Sune.** Tiberius Inuus touches a creature. The target magically regains 40 hit points and is freed from any disease or poison.


---

### Reactions

**Vengeance.** When Tiberius Inuus is hit by an attack he can utter an oath of vengeance against the creature that made the attack. He gains advantage on attack rolls against that creature for 1 minute or until it drops to 0 hit points or falls unconscious.


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