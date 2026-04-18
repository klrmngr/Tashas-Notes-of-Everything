---
type: pc
race: "Construct (warforged)"
class:
 - "Glaive"
subClass:
 - "CR 11"
cover: "Glaive.png"
campaign:
locations:
tags:
  - race/warforged
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/11
  - source/veor
---
###### Glaive
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Glaive.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Construct (warforged) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 187 (22d8 + 88) |
> | :FasUserGroup: Race | Construct (warforged) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 19 | 11 | 16 | 9 |
| **Mod** | +5 | +3 | +4 | +0 | +3 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common
**Saving Throws:** Str +9, Dex +7, Wis +7
**Skills:** Athletics +9, Perception +7, Stealth +7, Survival +7
**Damage Resistances:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Heatsink.** When Glaive takes cold damage, her Overdrive immediately recharges.

**Pack Tactics.** Glaive has advantage on attack rolls if at least one ally is within 5 feet of the creature she's attacking and the ally doesn't have the incapacitated condition.


---

### Actions

**Multiattack.** Glaive makes two Spiked Glaive attacks and two Serrated Bolt attacks.

**Spiked Glaive.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) piercing or slashing damage, or 14 (1d10 + 9) piercing or slashing damage if Glaive is in overdrive.

**Serrated Bolt.** Ranged Weapon Attack: +7 to hit, range 60 ft., one target. *Hit:* 13 (3d6 + 3) piercing damage. If Glaive has advantage on the attack roll, the serrated bolt lodges in the target, and the target's speed is reduced by 10 feet until the serrated bolt is removed. A target's speed can be reduced by only one serrated bolt at a time. A creature can use its action to remove a serrated bolt lodged in itself or another creature within its reach; when the bolt is removed from a creature, that creature takes 5 (2d4) slashing damage.


---

### Bonus Actions

**Overdrive (Recharges after Finishing a Short or Long Rest).** Glaive enters a state of overdrive that lasts for 1 minute or until she has the incapacitated condition. While in overdrive, Glaive gains the following benefits:
- Glaive has advantage on Strength checks and Strength saving throws.
- When Glaive makes a melee weapon attack, she gains a +4 bonus to the damage roll.
- Glaive's speed increases to 50 feet.


---

### Reactions

**Self-Preservation.** In response to being hit by a weapon attack, Glaive reduces the damage by 11 (2d10).


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