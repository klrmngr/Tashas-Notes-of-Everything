---
type: pc
race: "Humanoid"
class:
 - "Dragonborn of Bahamut"
subClass:
 - "CR 8"
cover: "Dragonborn of Bahamut.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/ftd
---
###### Dragonborn of Bahamut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragonborn of Bahamut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (half plate, shield) |
> | :FasHeart: HP | 93 (11d8 + 44) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 18 | 12 | 14 | 17 |
| **Mod** | +4 | +1 | +4 | +1 | +2 | +3 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Draconic
**Saving Throws:** Con +7, Int +4, Wis +5, Cha +6
**Skills:** Athletics +7, Perception +5, Persuasion +6
**Condition Immunities:** frightened

---

### Traits

**Legendary Resistance (1/Day).** If the dragonborn fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragonborn makes three Longsword attacks.

**Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands, plus 13 (3d8) radiant damage. The dragonborn can cause the sword to flare with bright light, and the target must succeed on a DC 14 Constitution saving throw or be blinded until the start of the dragonborn's next turn. The sword can flare in this way only once per turn.

**Healing Touch (1/Day).** The dragonborn touches another creature within 5 feet of it. The target magically regains 40 hit points. In addition, all diseases and poisons affecting the target are removed.

**Radiant Breath (Recharge 6).** The dragonborn exhales fiery radiance in a 30-foot cone. Each creature in that area must make a DC 15 Dexterity saving throw, taking 44 (8d10) radiant damage on a failed save, or half as much damage on a successful one. When the dragonborn uses this action, it can choose up to three creatures in the cone. These creatures take no damage from the radiance and instead regain 22 (4d10) hit points each.


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