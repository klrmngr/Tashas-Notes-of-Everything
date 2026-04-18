---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Dagryn"
subClass:
 - "CR 4"
cover: "Dagryn.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/mabjov
---
###### Dagryn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Dagryn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (splint, shield) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 8 | 14 | 14 | 13 | 17 |
| **Mod** | +1 | -1 | +2 | +2 | +1 | +3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Common, Draconic, Dwarvish, Undercommon
**Skills:** Deception +5, Performance +5, Persuasion +5
**Damage Resistances:** poison
**Damage Immunities:** acid

---

### Traits

**Draconic Transformation.** When Dagryn drops to 0 hit points, instead of falling unconscious, he transforms into his dragon form. He immediately gains all the statistics of an adult black dragon with the exception that his size is Medium, and has the stunned condition. At the start of his next turn, he grows to Large size, but remains stunned. At the start of his subsequent turn, Dagryn grows to Huge size and is no longer stunned. Dagryn remains in his dragon form for 24 hours whereupon he reverts to this stat block.

**Dwarven Resilience.** Dagryn has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.


---

### Actions

**Club.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) bludgeoning damage.

**Eruption.** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 14 (2d10 + 3) acid damage.


---

### Bonus Actions

**Invisibility (Recharges after a Short or Long Rest).** Dagryn magically turns invisible for 1 hour or until he attacks or casts a spell. Any equipment Dagryn wears or carries turns invisible with him.


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