---
type: pc
race: "Construct"
class:
 - "Oaken Bolter"
subClass:
 - "CR 5"
cover: "Oaken Bolter.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/5
  - source/mtf
---
###### Oaken Bolter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Oaken Bolter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 15 | 3 | 10 | 1 |
| **Mod** | +1 | +4 | +2 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands one language of its creator but can't speak
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Magic Resistance.** The oaken bolter has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The oaken bolter makes two lancing bolt attacks or one lancing bolt attack and one harpoon attack.

**Lancing Bolt.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 100/400 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage.

**Harpoon.** Ranged Weapon Attack: +7 to hit, range 50/200 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage, and the target is grappled (escape DC 12). While grappled in this way, a creature's speed isn't reduced, but it can move only in directions that bring it closer to the oaken bolter. A creature takes 5 (1d10) slashing damage if it escapes from the grapple or if it tries and fails. As a bonus action, the oaken bolter can pull a creature grappled by it 20 feet closer. The oaken bolter can grapple only one creature at a time.

**Explosive Bolt (Recharge 5–6).** The oaken bolter launches an explosive charge at a point within 120 feet. Each creature within 20 feet of that point must make a DC 15 Dexterity saving throw, taking 17 (5d6) fire damage on a failed save, or half as much damage on a successful one.


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