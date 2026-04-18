---
type: pc
race: "Fiend (demon)"
class:
 - "Marilith"
subClass:
 - "CR 16"
cover: "Marilith.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/16
  - source/mm
---
###### Marilith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Marilith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 20 | 20 | 18 | 16 | 20 |
| **Mod** | +4 | +5 | +5 | +4 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 13
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +9, Con +10, Wis +8, Cha +10
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The marilith has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The marilith's weapon attacks are magical.

**Reactive.** The marilith can take one reaction on every turn in combat.


---

### Actions

**Multiattack.** The marilith can make seven attacks: six with its longswords and one with its tail.

**Longsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Tail.** Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. *Hit:* 15 (2d10 + 4) bludgeoning damage. If the target is Medium or smaller, it is grappled (escape DC 19). Until this grapple ends, the target is restrained, the marilith can automatically hit the target with its tail, and the marilith can't make tail attacks against other targets.

**Teleport.** The marilith magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.


---

### Reactions

**Parry.** The marilith adds 5 to its AC against one melee attack that would hit it. To do so, the marilith must see the attacker and be wielding a melee weapon.


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