---
type: pc
race: "Humanoid (half-dragon)"
class:
 - "Langdedrosa Cyanwrath"
subClass:
 - "CR 4"
cover: "Langdedrosa Cyanwrath.png"
campaign:
locations:
tags:
  - race/half-dragon
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/hotdq
---
###### Langdedrosa Cyanwrath
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Langdedrosa Cyanwrath.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-dragon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (splint armor) |
> | :FasHeart: HP | 57 (6d12 + 18) |
> | :FasUserGroup: Race | Humanoid (half-dragon) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 16 | 10 | 14 | 12 |
| **Mod** | +4 | +1 | +3 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 14
**Languages:** Common, Draconic
**Saving Throws:** Str +6, Con +5
**Skills:** Athletics +6, Intimidation +3, Perception +4
**Damage Resistances:** lightning

---

### Traits

**Action Surge (Recharges on a Short or Long Rest).** On his turn, Langdedrosa can take one additional action.

**Improved Critical.** Langdedrosa's weapon attacks score a critical hit on a roll of 19 or 20.


---

### Actions

**Multiattack.** Langdedrosa attacks twice, either with his greatsword or spear.

**Greatsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Spear.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Lightning Breath (Recharge 5–6).** Langdedrosa breathes lightning in a 30-foot line that is 5 feet wide. Each creature in the line must make a DC 13 Dexterity saving throw, taking 22 (4d10) lightning damage on a failed save, or half as much damage on a successful one.


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