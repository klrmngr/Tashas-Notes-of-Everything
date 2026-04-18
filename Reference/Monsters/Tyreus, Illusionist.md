---
type: pc
race: "Humanoid (human)"
class:
 - "Tyreus, Illusionist"
subClass:
 - "CR 13"
cover: "Tyreus, Illusionist.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/aitfr-fcd
---
###### Tyreus, Illusionist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-FCD
___

> [!infobox|no-t right]
> ![[Tyreus, Illusionist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 156 (24d8 + 48) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | AitFR-FCD |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 14 | 20 | 15 | 16 |
| **Mod** | +0 | +3 | +2 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Deep Speech, Draconic, Primordial, Sylvan
**Saving Throws:** Int +10, Wis +7
**Skills:** Arcana +12, Deception +8, History +10, Perception +7
**Damage Resistances:** ; nonmagical bludgeoning, piercing, slashing (from stoneskin)

---

### Traits

**Legendary Resistance (3/Day).** If Tyreus fails a saving throw, he can choose to succeed instead.

**Illusory Reality.** When Tyreus casts an illusion spell of 1st level or higher, he can choose one inanimate, nonmagical object that is part of the illusion and make that object real. He can do this on his turn as a bonus action while the spell is ongoing.
The object remains real for 1 minute. The object can't deal damage or otherwise directly harm anyone.

**Displacement (Recharges after Tyreus Casts an Illusion Spell of 1st Level or Higher).** As a bonus action, Tyreus projects an illusion that makes him appear to be standing a few inches from his actual location, causing any creature to have disadvantage on attack rolls against Tyreus. The effect ends if Tyreus takes damage, he is incapacitated, or his speed becomes 0.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Modify Illusion.** When Tyreus casts an illusion spell that has a duration of 1 minute or longer, he can use his action to change the nature of that illusion (using the spell's normal parameters for the illusion), provided that he can see the illusion.


---

### Legendary Actions

### 

**Scrutinize.** Tyreus makes an Intelligence (Investigation) or Wisdom (Perception) check.

**Cast Cantrip.** Tyreus casts a cantrip from his spell list.

**Cast Spell (Costs 1-3 Actions).** Tyreus uses a spell slot to cast a 1st-, 2nd-, or 3rd-level spell that he has prepared. Doing so costs 1 legendary action per level of the spell.


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