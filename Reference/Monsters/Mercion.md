---
type: pc
race: "Humanoid (cleric, human)"
class:
 - "Mercion"
subClass:
 - "CR 3"
cover: "Mercion.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/wbtw
---
###### Mercion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Mercion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric, human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 (plate armor) |
> | :FasHeart: HP | 31 (9d8 - 9) |
> | :FasUserGroup: Race | Humanoid (cleric, human) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 9 | 12 | 17 | 17 |
| **Mod** | +2 | +0 | -1 | +1 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Dwarvish
**Saving Throws:** Wis +5, Cha +5
**Skills:** Insight +5, Medicine +5

---

### Traits

**Special Equipment.** Mercion wields a +1 quarterstaff.


---

### Actions

**Multiattack.** Mercion makes one Divine Radiance attack and one +1 Quarterstaff attack. She can replace one of these attacks with a use of Spellcasting.

**Divine Radiance.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 13 (3d8) radiant damage.

**+1 Quarterstaff.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage, or 7 (1d8 + 3) bludgeoning damage when used with two hands.

**Radiant Fire (Recharge 5–6).** Mercion creates a magical explosion of fiery radiance centered on a point she can see within 120 feet of her. Each creature in a 20-foot-radius sphere centered on that point must make a DC 13 Dexterity saving throw, taking 28 (8d6) radiant damage on a failed save, or half as much damage on a successful one.


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