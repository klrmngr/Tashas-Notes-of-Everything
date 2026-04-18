---
type: pc
race: "Undead"
class:
 - "Nightwalker"
subClass:
 - "CR 20"
cover: "Nightwalker.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/20
  - source/mtf
---
###### Nightwalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Nightwalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 297 (22d12 + 154) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 19 | 24 | 6 | 9 | 8 |
| **Mod** | +6 | +4 | +7 | -2 | -1 | -1 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 9
**Languages:** —
**Saving Throws:** Con +13
**Damage Resistances:** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Annihilating Aura.** Any creature that starts its turn within 30 feet of the nightwalker must succeed on a DC 21 Constitution saving throw or take 14 (4d6) necrotic damage and grant the nightwalker advantage on attack rolls against it until the start of the creature's next turn. Undead are immune to this aura.

**Life Eater.** A creature reduced to 0 hit points from damage dealt by the nightwalker dies and can't be revived by any means short of a wish spell.


---

### Actions

**Multiattack.** The nightwalker uses Enervating Focus twice, or it uses Enervating Focus and Finger of Doom, if available.

**Enervating Focus.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 28 (5d8 + 6) necrotic damage. The target must succeed on a DC 21 Constitution saving throw or its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest.

**Finger of Doom (Recharge 6).** The nightwalker points at one creature it can see within 300 feet of it. The target must succeed on a DC 21 Wisdom saving throw or take 26 (4d12) necrotic damage and become frightened until the end of the nightwalker's next turn. While frightened in this way, the creature is also paralyzed. If a target's saving throw is successful, the target is immune to the nightwalker's Finger of Doom for the next 24 hours.


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