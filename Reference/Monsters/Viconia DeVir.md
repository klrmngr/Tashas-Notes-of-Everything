---
type: pc
race: "Humanoid (elf)"
class:
 - "Viconia DeVir"
subClass:
 - "CR 13"
cover: "Viconia DeVir.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/mabjov
---
###### Viconia DeVir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Viconia DeVir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 21 (cloak of protection, plate, shield) |
> | :FasHeart: HP | 135 (30d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 14 | 10 | 14 | 20 | 14 |
| **Mod** | +7 | +2 | +0 | +2 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Celestial, Common, Elvish
**Saving Throws:** Con +5, Wis +10
**Skills:** Insight +10, Persuasion +7, Religion +12
**Damage Resistances:** necrotic

---

### Traits

**Fey Ancestry.** Viconia has advantage on saving throws against being charmed, and magic can't put Viconia to sleep.

**Living Shadow.** While in dim light or darkness, Viconia has resistance to damage that isn't force, psychic, or radiant.

**Special Equipment.** Viconia wears a belt of giant strength (fire) and a cloak of protection and wields a +3 mace. Without the belt, her strength is 12 and her speed is reduced to 20 ft.

**Sunlight Sensitivity.** While in sunlight, Viconia has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Viconia attacks twice with her Magic Mace and uses her Spellcasting action.

**Magic Mace.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 13 (1d6 + 10) bludgeoning damage plus 9 (2d8) necrotic damage.

**Sacred Cleansing (Recharge 4–6).** Each creature in a 10-foot-radius, 40-foot-high cylinder centered on a point within 60 feet must make a DC 18 Dexterity saving throw. A creature takes 28 (8d6) fire damage plus 28 (8d6) radiant damage on a failed save, or half as much damage on a successful one.


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