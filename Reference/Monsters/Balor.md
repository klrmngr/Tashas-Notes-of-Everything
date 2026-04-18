---
type: pc
race: "Fiend (demon)"
class:
 - "Balor"
subClass:
 - "CR 19"
cover: "Balor.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/19
  - source/mm
---
###### Balor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Balor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 262 (21d12 + 126) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 15 | 22 | 20 | 16 | 22 |
| **Mod** | +8 | +2 | +6 | +5 | +3 | +6 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 13
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +14, Con +12, Wis +9, Cha +12
**Damage Resistances:** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Death Throes.** When the balor dies, it explodes, and each creature within 30 feet of it must make a DC 20 Dexterity saving throw, taking 70 (20d6) fire damage on a failed save, or half as much damage on a successful one. The explosion ignites flammable objects in that area that aren't being worn or carried, and it destroys the balor's weapons.

**Fire Aura.** At the start of each of the balor's turns, each creature within 5 feet of it takes 10 (3d6) fire damage, and flammable objects in the aura that aren't being worn or carried ignite. A creature that touches the balor or hits it with a melee attack while within 5 feet of it takes 10 (3d6) fire damage.

**Magic Resistance.** The balor has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The balor's weapon attacks are magical.


---

### Actions

**Multiattack.** The balor makes two attacks: one with its longsword and one with its whip.

**Longsword.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) slashing damage plus 13 (3d8) lightning damage. If the balor scores a critical hit, it rolls damage dice three times, instead of twice.

**Whip.** Melee Weapon Attack: +14 to hit, reach 30 ft., one target. *Hit:* 15 (2d6 + 8) slashing damage plus 10 (3d6) fire damage, and the target must succeed on a DC 20 Strength saving throw or be pulled up to 25 feet toward the balor.

**Teleport.** The balor magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.


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