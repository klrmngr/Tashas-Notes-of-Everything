---
type: pc
race: "Giant"
class:
 - "Hundred-Handed One"
subClass:
 - "CR 15"
cover: "Hundred-Handed One.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/15
  - source/mot
---
###### Hundred-Handed One
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Hundred-Handed One.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 243 (18d12 + 126) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 15 | 25 | 14 | 16 | 16 |
| **Mod** | +8 | +2 | +7 | +2 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Giant
**Saving Throws:** Con +12, Wis +8
**Skills:** Intimidation +8, Perception +8
**Condition Immunities:** frightened

---

### Traits

**Reactive.** The giant can take one reaction on every turn in a combat.

**Vigilant.** The giant can't be surprised.


---

### Actions

**Multiattack.** The giant makes four longsword attacks or two rock attacks.

**Longsword.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 21 (3d8 + 8) slashing damage.

**Rock.** Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be knocked prone.


---

### Reactions

**Deflect Attack.** The giant adds 5 to its AC against one weapon attack that would hit it. To do so, the giant must see the attacker and be wielding a melee weapon.


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