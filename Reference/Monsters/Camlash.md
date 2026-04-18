---
type: pc
race: "Fiend (demon)"
class:
 - "Camlash"
subClass:
 - "CR 19"
cover: "Camlash.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/19
  - source/veor
---
###### Camlash
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Camlash.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 325 (26d12 + 156) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

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

**Death Throes.** Camlash explodes when reduced to 0 hit points, and each creature within 30 feet of Camlash must make a DC 21 Dexterity saving throw, taking 70 (20d6) fire damage on a failed save or half as much damage on a successful one. The explosion ignites flammable objects in that area that aren't being worn or carried.

**Magic Resistance.** Camlash has advantage on saving throws against spells and other magical effects.

**Spider Aura.** Camlash is surrounded by tiny biting spiders that magically appear and disappear from moment to moment. At the start of each of Camlash's turns, each creature within 10 feet of Camlash takes 10 (3d6) poison damage and must succeed on a DC 21 Constitution saving throw or have the paralyzed condition until the start of Camlash's next turn.


---

### Actions

**Multiattack.** Camlash makes one Flaming Whip attack and one Lightning Blade attack. Camlash can replace one of these attacks with Teleport.

**Flaming Whip.** Melee Weapon Attack: +15 to hit, reach 30 ft., one target. *Hit:* 25 (5d6 + 8) fire damage, and if the target is a creature, it must succeed on a DC 21 Strength saving throw or be pulled up to 25 feet toward Camlash.

**Lightning Blade.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) slashing damage plus 13 (3d8) lightning damage.

**Teleport.** Camlash magically teleports, along with any equipment she is wearing or carrying, up to 120 feet to an unoccupied space she can see.


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