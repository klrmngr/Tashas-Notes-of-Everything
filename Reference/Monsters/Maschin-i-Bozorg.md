---
type: pc
race: "Construct"
class:
 - "Maschin-i-Bozorg"
subClass:
 - "CR 8"
cover: "Maschin-i-Bozorg.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/8
  - source/qftis
---
###### Maschin-i-Bozorg
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Maschin-i-Bozorg.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 94 (9d10 + 45) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 20 | 2 | 10 | 1 |
| **Mod** | +4 | +3 | +5 | -4 | +0 | -5 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands Gnomish but can't speak
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; deafened; exhaustion; frightened; paralyzed; poisoned; unconscious

---

### Traits

**Overheat.** When the maschin-i-bozorg is reduced to 0 hit points, its power source overloads, briefly superheating its outer shell. Each creature within 10 feet of the maschin-i-bozorg must make a DC 16 Constitution saving throw, taking 7 (2d6) fire damage on a failed save or half as much damage on a successful one.


---

### Actions

**Multiattack.** The maschin-i-bozorg makes two Poison Jab attacks.

**Poison Jab.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 13 (4d4 + 3) piercing damage, and the target must succeed on a DC 16 Constitution saving throw or have the poisoned condition for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Steam Jet (Recharge 5–6).** The maschin-i-bozorg emits scalding steam in a 30-foot cone. Each creature in that area must make a DC 16 Constitution saving throw, taking 28 (8d6) fire damage on a failed save or half as much damage on a successful one.


---

### Bonus Actions

**Crushing Stride.** The maschin-i-bozorg moves up to its speed in a straight line. During this movement, it can enter Medium and smaller creatures' spaces. A creature whose space the maschin-i-bozorg enters must make a DC 15 Dexterity saving throw. On a successful save, the creature is pushed to the nearest unoccupied space out of the maschin-i-bozorg's path. On a failed save, the creature takes 10 (3d6) bludgeoning damage and has the prone condition.
If the maschin-i-bozorg remains in the prone creature's space, the creature also has the restrained condition until it's no longer in the same space as the maschin-i-bozorg. While restrained in this way, the creature, or another creature within 5 feet of it, can use its action to make a DC 15 Strength (Athletics) check. On a successful check, the creature is shunted to an unoccupied space of its choice within 5 feet of the maschin-i-bozorg.


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