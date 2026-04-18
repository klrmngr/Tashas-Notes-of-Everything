---
type: pc
race: "Dragon"
class:
 - "Ancient Dragon Turtle"
subClass:
 - "CR 24"
cover: "Ancient Dragon Turtle.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/24
  - source/ftd
---
###### Ancient Dragon Turtle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ancient Dragon Turtle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 409 (21d20 + 189) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 12 | 29 | 14 | 19 | 15 |
| **Mod** | +9 | +1 | +9 | +2 | +4 | +2 |

**Speed:** 30 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** Aquan, Draconic
**Saving Throws:** Dex +8, Con +16, Wis +11
**Skills:** Perception +11
**Damage Immunities:** cold; fire
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Amphibious.** The dragon turtle can breathe air and water.

**Blessing of the Sea (Recharges after a Short or Long Rest).** If the dragon turtle would be reduced to 0 hit points, its current hit point total instead resets to 350 hit points, and it recharges its Steam Breath. Additionally, the dragon turtle can now use the options in the "Mythic Actions" section for 1 hour. Award a party an additional 62,000 XP (124,000 XP total) for defeating the dragon turtle after its Blessing of the Sea activates.

**Legendary Resistance (3/Day).** If the dragon turtle fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The dragon turtle doesn't require food or drink.


---

### Actions

**Multiattack.** The dragon turtle makes one Bite or Tail attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 15 (1d12 + 9) piercing damage plus 13 (2d12) lightning damage.

**Claw.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 18 (2d8 + 9) slashing damage.

**Tail.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 20 (2d10 + 9) bludgeoning damage. If the target is a creature, it must succeed on a DC 24 Strength saving throw or be knocked prone.

**Steam Breath (Recharge 5–6).** The dragon turtle exhales steam in a 90-foot cone. Each creature in that area must make a DC 24 Constitution saving throw, taking 67 (15d8) fire damage on a failed save, or half as much damage on a successful one. Being underwater doesn't grant resistance against this damage.


---

### Legendary Actions

### 

**Attack.** The dragon turtle makes one Claw or Tail attack.

**Move.** The dragon turtle moves up to its speed. If the dragon turtle is swimming, this movement doesn't provoke opportunity attacks.

**Boiling Aura (Costs 3 Actions).** The dragon turtle radiates intense heat. Until the start of the dragon turtle's next turn, whenever a creature starts its turn within 20 feet of the dragon turtle, that creature must succeed on a DC 24 Constitution saving throw or take 40 (9d8) fire damage. Being underwater doesn't grant resistance against this damage.


---

### Mythic Actions

If the dragon turtle's Blessing of the Sea trait has activated in the last hour, it can use the options below as legendary actions.

### 

**Bite.** The dragon turtle makes one Bite attack.

**Armor of Storms (Costs 2 Actions).** Lightning temporarily surrounds the dragon turtle, and it gains 40 temporary hit points until the start of its next turn. Until all these temporary hit points are gone, any creature that touches the dragon turtle or hits it with a melee attack takes 26 (4d12) lightning damage.


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