---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Suldil Baldoriel"
subClass:
 - "CR 10"
cover: "Suldil Baldoriel.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/mabjov
---
###### Suldil Baldoriel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Suldil Baldoriel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 137 (25d8 + 25) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 12 | 14 | 20 |
| **Mod** | +0 | +2 | +1 | +1 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Celestial, Common, Draconic, Elvish
**Saving Throws:** Con +5, Cha +9
**Skills:** Arcana +9, Deception +9, Persuasion +9
**Damage Resistances:** lightning

---

### Traits

**Young Bronze Dragon.** Suldil is accompanied by a young bronze dragon. The dragon allows Suldil to use him as a mount.


---

### Actions

**Bronze Bolt.** Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 21 (3d10 + 5) lightning damage.

**Explosion (1/Day).** Suldil discharges a burst of energy in a 60-foot-radius. Each creature in that area must make a DC 17 Dexterity saving throw, taking 44 (8d10) lightning damage on failed save, half as much damage on a successful save.


---

### Bonus Actions

**Mounted.** If Suldil isn't mounted, she can use a bonus action to magically teleport onto her young bronze dragon mount, provided Suldil and the young bronze dragon are on the same plane of existence. When she teleports, Suldil appears astride the young bronze dragon along with any equipment she is wearing or carrying. While mounted and not incapacitated, Suldil can't be surprised, and both her and her mount gain advantage on Dexterity saving throws.


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