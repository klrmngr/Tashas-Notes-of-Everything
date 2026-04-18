---
type: pc
race: "Construct"
class:
 - "Gearkeeper Construct"
subClass:
 - "CR 10"
cover: "Gearkeeper Construct.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/10
  - source/egw
---
###### Gearkeeper Construct
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Gearkeeper Construct.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 161 (17d10 + 68) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 18 | 3 | 11 | 1 |
| **Mod** | +5 | +3 | +4 | -4 | +0 | -5 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The gearkeeper is immune to any spell or effect that would alter its form.

**Rapid Shifting.** Opportunity attacks made against the gearkeeper have disadvantage.

**Whirling Blades.** Any creature that starts its turn within 5 feet of the gearkeeper takes 4 (1d8) slashing damage.


---

### Actions

**Multiattack.** The gearkeeper makes two Arm Blade attacks, or one Arm Blade attack and one Spear Launcher attack.

**Arm Blade.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 18 (3d8 + 5) slashing damage.

**Spear Launcher.** Ranged Weapon Attack: +9 to hit, range 90 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage, and the target is knocked prone.

**Shrapnel Blast (Recharge 6).** The gearkeeper jettisons a spray of jagged metal in a 30-foot cone. Each creature in the area must make a DC 15 Dexterity saving throw, taking 21 (6d6) piercing damage on a failed save, or half as much damage on a successful one.


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