---
type: pc
race: "Giant"
class:
 - "Dire Troll"
subClass:
 - "CR 13"
cover: "Dire Troll.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/13
  - source/mpmm
---
###### Dire Troll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Dire Troll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 15 | 21 | 9 | 11 | 5 |
| **Mod** | +6 | +2 | +5 | -1 | +0 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Giant
**Saving Throws:** Wis +5, Cha +2
**Skills:** Perception +5
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** frightened; poisoned

---

### Traits

**Regeneration.** The troll regains 10 hit points at the start of its turn. If the troll takes acid or fire damage, it regains only 5 hit points at the start of its next turn. The troll dies only if it is hit by an attack that deals 10 or more acid or fire damage while the troll has 0 hit points.


---

### Actions

**Multiattack.** The troll makes one Bite attack and four Claw attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 10 (1d8 + 6) piercing damage plus 5 (1d10) poison damage.

**Claws.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) slashing damage.

**Whirlwind of Claws (Recharge 5–6).** Each creature within 10 feet of the troll must make a DC 19 Dexterity saving throw, taking 44 (8d10) slashing damage on a failed save, or half as much damage on a successful one.


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