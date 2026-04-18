---
type: pc
race: "Fiend (devil)"
class:
 - "Geryon"
subClass:
 - "CR 22"
cover: "Geryon.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/22
  - source/mtf
---
###### Geryon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Geryon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (devil) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 300 (24d12 + 144) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 17 | 22 | 19 | 16 | 23 |
| **Mod** | +9 | +3 | +6 | +4 | +3 | +6 |

**Speed:** 30 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +10, Con +13, Wis +10, Cha +13
**Skills:** Deception +13, Intimidation +13, Perception +10
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Geryon fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Geryon has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Geryon's weapon attacks are magical.

**Regeneration.** Geryon regains 20 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Geryon dies only if he starts his turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Geryon makes two attacks: one with his claws and one with his stinger.

**Claws.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 23 (4d6 + 9) slashing damage. If the target is Large or smaller, it is grappled (DC 24) and is restrained until the grapple ends. Geryon can grapple one creature at a time. If the target is already grappled by Geryon, the target takes an extra 27 (6d8) slashing damage.

**Stinger.** Melee Weapon Attack: +16 to hit, reach 20 ft., one creature. *Hit:* 14 (2d4 + 9) piercing damage, and the target must succeed on a DC 21 Constitution saving throw or take 13 (2d12) poison damage and become poisoned until it finishes a short or long rest. The target's hit point maximum is reduced by an amount equal to half the poison damage it takes. If its hit point maximum drops to 0, it dies. This reduction lasts until the poisoned condition is removed.

**Teleport.** Geryon magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.


---

### Legendary Actions

### 

**Infernal Glare.** Geryon targets one creature he can see within 60 feet of him. If the target can see Geryon, the target must succeed on a DC 23 Wisdom saving throw or become frightened of Geryon until the end of its next turn.

**Swift Sting (Costs 2 Actions).** Geryon attacks with his stinger.

**Teleport.** Geryon uses his Teleport action.


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