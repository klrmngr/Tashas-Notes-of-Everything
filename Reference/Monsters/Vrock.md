---
type: pc
race: "Fiend (demon)"
class:
 - "Vrock"
subClass:
 - "CR 6"
cover: "Vrock.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/6
  - source/mm
---
###### Vrock
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Vrock.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 104 (11d10 + 44) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 18 | 8 | 13 | 8 |
| **Mod** | +3 | +2 | +4 | -1 | +1 | -1 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Dex +5, Wis +4, Cha +2
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The vrock has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The vrock makes two attacks: one with its beak and one with its talons.

**Beak.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage.

**Talons.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 14 (2d10 + 3) slashing damage.

**Spores (Recharge 6).** A 15-foot-radius cloud of toxic spores extends out from the vrock. The spores spread around corners. Each creature in that area must succeed on a DC 14 Constitution saving throw or become poisoned. While poisoned in this way, a target takes 5 (1d10) poison damage at the start of each of its turns. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Emptying a vial of holy water on the target also ends the effect on it.

**Stunning Screech (1/Day).** The vrock emits a horrific screech. Each creature within 20 feet of it that can hear it and that isn't a demon must succeed on a DC 14 Constitution saving throw or be stunned until the end of the vrock's next turn.


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