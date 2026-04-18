---
type: pc
race: "Humanoid (human)"
class:
 - "Durnan"
subClass:
 - "CR 9"
cover: "Durnan.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/wdh
---
###### Durnan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Durnan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (elven chain) |
> | :FasHeart: HP | 144 (17d8 + 68) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 18 | 13 | 12 | 10 |
| **Mod** | +4 | +2 | +4 | +1 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Dwarvish
**Saving Throws:** Str +8, Con +8
**Skills:** Athletics +8, Perception +5

---

### Traits

**Special Equipment.** Durnan wields a sword of sharpness (greatsword) called Grimvault. He wears boots of striding and springing, elven chain, and a ring of spell turning.

**Indomitable (Recharges after a Long Rest).** Durnan can reroll a saving throw that he fails. He must use the new roll.

**Spell Turning.** While wearing his ring of spell turning, Durnan has advantage on saving throws against any spell that targets only him (not in an area of effect). If Durnan rolls a 20 for the save and the spell is 7th level or lower, the spell has no effect on him and instead targets the caster, using the slot level, spell save DC, attack bonus, and spellcasting ability of the caster.


---

### Actions

**Multiattack.** Durnan makes four melee weapon attacks.

**Grimvault.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage. If the target is an object, the hit instead deals 16 slashing damage. If the target is a creature and Durnan rolls a 20 on the d20 for the attack roll, the target takes an extra 14 slashing damage, and Durnan rolls another d20. On a roll of 20, he lops off one of the target's limbs, or some other part of its body if it is limbless.

**Double Crossbow.** Ranged Weapon Attack: +6 to hit, range 60/240 ft., one target. *Hit:* 13 (2d10 + 2) piercing damage.


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