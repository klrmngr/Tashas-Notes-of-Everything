---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Duergar Spy"
subClass:
 - "CR 2"
cover: "Duergar Spy.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/tftyp
---
###### Duergar Spy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Duergar Spy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 12 | 12 | 10 | 13 |
| **Mod** | +0 | +3 | +1 | +1 | +0 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Dwarvish, Undercommon
**Skills:** Deception +5, Insight +2, Investigation +5, Perception +4, Persuasion +3, Sleight Of Hand +5, Stealth +7
**Damage Resistances:** poison

---

### Traits

**Cunning Action.** On each of its turns, the spy can use a bonus action to take the Dash, Disengage, or Hide action.

**Duergar Resilience.** The spy has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.

**Sneak Attack.** Once per turn, the spy can deal an extra 7 (2d6) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the spy that isn't incapacitated and the spy doesn't have disadvantage on the attack roll.

**Sunlight Sensitivity.** While in sunlight, the spy has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The spy makes two shortsword attacks.

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, the spy magically increases in size, along with anything it is wearing or carrying. While enlarged, the spy is Large, doubles her damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the spy lacks the room to become Large, it attains the maximum size possible in the space available.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 10 (2d6 + 3) piercing damage while enlarged.

**Hand Crossbow.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Invisibility (Recharges after a Short or Long Rest).** The spy magically turns invisible until it attacks, deals damage, casts a spell, or uses its Enlarge, or until its concentration is broken, up to 1 hour (as if concentrating on a spell). Any equipment the spy wears or carries is invisible with it.


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