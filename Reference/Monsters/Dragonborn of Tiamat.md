---
type: pc
race: "Humanoid"
class:
 - "Dragonborn of Tiamat"
subClass:
 - "CR 7"
cover: "Dragonborn of Tiamat.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/ftd
---
###### Dragonborn of Tiamat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragonborn of Tiamat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 85 (10d8 + 40) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 18 | 10 | 12 | 16 |
| **Mod** | +5 | +0 | +4 | +0 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Draconic
**Saving Throws:** Str +8, Con +7, Wis +4, Cha +6
**Skills:** Athletics +8, Intimidation +6, Perception +4
**Condition Immunities:** frightened

---

### Traits

**Legendary Resistance (1/Day).** If the dragonborn fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragonborn makes two Greataxe attacks.

**Greataxe.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (1d12 + 5) slashing damage plus 13 (3d8) necrotic damage.

**Necrotic Breath (Recharge 6).** The dragonborn exhales shadowy fire in a 30-foot cone. Each creature in that area must make a DC 15 Wisdom saving throw. On a failed save, the creature takes 36 (8d8) necrotic damage and is frightened of the dragonborn for 1 minute. On a successful save, the creature takes half as much damage and isn't frightened. A frightened creature can repeat the saving throw at end of each of its turns, ending the effect on itself on a success.


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