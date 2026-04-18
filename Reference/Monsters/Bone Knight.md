---
type: pc
race: "Humanoid (any race)"
class:
 - "Bone Knight"
subClass:
 - "CR 5"
cover: "Bone Knight.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/erlw
---
###### Bone Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Bone Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral Chaotic Evil |
> | :FasShield: AC | 20 (bonecraft armor) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 14 | 12 | 14 | 16 |
| **Mod** | +4 | +1 | +2 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** any one language (usually Common)
**Saving Throws:** Wis +5, Cha +6
**Skills:** Athletics +7, Deception +6, Intimidation +6
**Damage Resistances:** necrotic; poison

---

### Traits

**Commander of Bones.** As a bonus action, the knight can target one skeleton or zombie it can see within 30 feet of it. The target must make a DC 14 Wisdom saving throw. On a failed save, the target must obey the knight's commands until the knight dies or until the knight releases it as a bonus action. The knight can command up to twelve undead at a time this way.

**Master of the Pallid Banner.** While within 60 feet of the knight, any undead ally of the knight has advantage on saving throws against any effect that turns undead.


---

### Actions

**Multiattack.** The knight attacks twice with one of its weapons.

**Greatsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 5 (1d8 + 1) piercing damage.


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