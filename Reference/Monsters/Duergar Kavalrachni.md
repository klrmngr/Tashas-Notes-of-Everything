---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Duergar Kavalrachni"
subClass:
 - "CR 2"
cover: "Duergar Kavalrachni.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mpmm
---
###### Duergar Kavalrachni
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Duergar Kavalrachni.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (scale mail, shield) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 14 | 11 | 10 | 9 |
| **Mod** | +2 | +0 | +2 | +0 | +0 | -1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Dwarvish, Undercommon
**Damage Resistances:** poison

---

### Traits

**Cavalry Training.** When the duergar hits a target with a melee attack while mounted, the mount can use its reaction to make one melee attack against the same target.

**Duergar Resilience.** The duergar has advantage on saving throws against spells and the charmed, paralyzed, and poisoned conditions.

**Sunlight Sensitivity.** While in sunlight, the duergar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The duergar makes two War Pick attacks.

**War Pick.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage plus 5 (2d4) poison damage.

**Heavy Crossbow.** Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage.

**Shared Invisibility (Recharges after a Short or Long Rest).** The duergar magically turns invisible for up to 1 hour or until it attacks, it forces a creature to make a saving throw, or its concentration is broken (as if concentrating on a spell). Any equipment the duergar wears or carries is invisible with it. While the invisible duergar is mounted, the mount is invisible as well. The invisibility ends early on the mount immediately after it attacks.


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