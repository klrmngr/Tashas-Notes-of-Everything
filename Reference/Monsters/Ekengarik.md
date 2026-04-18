---
type: pc
race: "Fiend"
class:
 - "Ekengarik"
subClass:
 - "CR 16"
cover: "Ekengarik.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/16
  - source/coa
---
###### Ekengarik
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Ekengarik.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 231 (22d10 + 110) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 21 | 14 | 17 | 21 |
| **Mod** | +6 | +3 | +5 | +2 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 13
**Languages:** Common, Formian, telepathy 120 ft.
**Saving Throws:** Con +10, Cha +10
**Skills:** Deception +10, Insight +8, Persuasion +10
**Damage Resistances:** acid; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Hive Mind.** All fiendish formians within 1 mile of Ekengarik can telepathically communicate with each other and Ekengarik.

**Regeneration.** Ekengarik regenerates 10 hit points at the start of her turn, unless she took radiant damage in the last round.


---

### Actions

**Multiattack.** Ekengarik makes three Bite attacks. She can replace one of the attacks with an Acid Spray (if available) attack or a use of Spellcasting.

**Bite.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage and the target must make a DC 19 Constitution saving throw. On a failed save, the target's Strength score is reduced by 2 (1d4). The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.

**Acid Spray (Recharge 5–6).** Ekengarik spits acid at one creature within 60 feet of her, or two creatures within 60 feet of her and 5 feet of each other. Targets must make a DC 18 Dexterity saving throw, taking 33 (6d10) acid damage on a failed saving throw, or half as much on a successful one.


---

### Reactions

**Hardened Carapace (Recharge 4–6).** When hit with an attack, Ekengarik temporarily hardens her carapace, reducing her speed to 0 and increasing her AC by 5 until the start of her next turn.


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