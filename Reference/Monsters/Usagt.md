---
type: pc
race: "Aberration (shapeshifter)"
class:
 - "Usagt"
subClass:
 - "CR 5"
cover: "Usagt.png"
campaign:
locations:
tags:
  - race/shapeshifter
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/5
  - source/aitfr-thp
---
###### Usagt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-THP
___

> [!infobox|no-t right]
> ![[Usagt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Aberration (shapeshifter) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 97 (13d8 + 39) |
> | :FasUserGroup: Race | Aberration (shapeshifter) |
> | :FasBook: Source | AitFR-THP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 16 | 15 | 20 | 12 |
| **Mod** | +0 | +2 | +3 | +2 | +5 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 100 ft., passive Perception 18
**Languages:** all, telepathy 30 ft.
**Saving Throws:** Int +5, Wis +8, Cha +4
**Skills:** History +5, Insight +8, Perception +8, Performance +7, Stealth +5
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Invisibility.** The usagt's true form is invisible.

**Shapechanger.** The usagt can use its action to polymorph into a Small, Medium, or Large humanoid it has seen in person or telepathically, or back into its true form. Its statistics, other than its size, are the same in each form. While polymorphed, the usagt is not invisible. Its new form appears to wear clothes, carry equipment, and even wield weapons, but these are all parts of the usagt itself; they vanish if dropped or removed from the creature. It can't activate, use, wield, or otherwise benefit from any of its apparent equipment. It reverts to its true form if it dies.


---

### Actions

**Multiattack.** The usagt makes two attacks with its claws.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) slashing damage plus 11 (2d6 + 4) psychic damage.

**Personal Insight.** The usagt targets one creature it can see within 30 feet of it. The target must contest its Charisma (Deception) check against the usagt's Wisdom (Insight) check.
The target has advantage on the roll if it is immune to being charmed. A target can choose to fail this check.
If the usagt wins, it magically learns the identity of a creature from the target's past, someone the target wishes it could speak to again or with whom the target has left something unsaid. If somehow no such creature exists in the target's past, the usagt learns that instead.


---

### Reactions

**Invisibility Response (Recharges When the Usagt Uses Its Shapechanger Ability).** When the usagt takes damage, it can choose to revert to its default, invisible form and move up to 15 feet without provoking opportunity attacks.


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