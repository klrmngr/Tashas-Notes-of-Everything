---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Xardorok Sunblight"
subClass:
 - "CR 5"
cover: "Xardorok Sunblight.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/idrotf
---
###### Xardorok Sunblight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Xardorok Sunblight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 93 (11d8 + 44) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 18 | 12 | 13 | 18 |
| **Mod** | +3 | +0 | +4 | +1 | +1 | +4 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Common, Dwarvish
**Saving Throws:** Wis +4, Cha +7
**Skills:** Arcana +4, Deception +7, Intimidation +7
**Damage Resistances:** poison

---

### Traits

**Duergar Resilience.** Xardorok has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.

**Sunlight Sensitivity.** While in sunlight, Xardorok has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Xardorok attacks twice with a weapon or casts eldritch blast twice.

**Spiked Gauntlet.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage, or 8 (2d4 + 3) piercing damage while Xardorok is enlarged.

**Eldritch Blast (Cantrip).** Ranged Spell Attack: +7 to hit, range 120 ft., one creature. *Hit:* 9 (1d10 + 4) force damage.

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, Xardorok magically increases in size, along with anything he is wearing or carrying. While enlarged, Xardorok is Large, doubles his damage dice on Strength-based weapon attacks (included in his attacks), and makes Strength checks and Strength saving throws with advantage. If Xardorok lacks the room to become Large, he attains the maximum size possible in the space available.

**Invisibility (Recharge 4–6).** Xardorok magically turns invisible until he attacks, he casts a spell, he uses his Enlarge, or his concentration is broken (as if concentrating on a spell). Any equipment Xardorok wears or carries is invisible with him.


---

### Reactions

**Hellish Rebuke (2/Day).** When Xardorok is damaged by a creature within 60 feet of him that he can see, the creature that damaged him is engulfed in hellish flames and must make a DC 15 Dexterity saving throw, taking 16 (3d10) fire damage on a failed save, or half as much damage on a successful one.


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