---
type: pc
race: "Dragon (gem)"
class:
 - "Adult Sapphire Dragon"
subClass:
 - "CR 15"
cover: "Adult Sapphire Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/ftd
---
###### Adult Sapphire Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Adult Sapphire Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (gem) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 225 (18d12 + 108) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 22 | 18 | 17 | 18 |
| **Mod** | +6 | +2 | +6 | +4 | +3 | +4 |

**Speed:** 40 ft., burrow 30 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 23
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +7, Con +11, Wis +8, Cha +9
**Skills:** History +9, Perception +13, Persuasion +14, Stealth +7
**Damage Resistances:** lightning; thunder
**Condition Immunities:** frightened

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Spider Climb.** The dragon can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and can leave a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 5 (1d10) thunder damage.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) slashing damage.

**Debilitating Breath (Recharge 5–6).** The dragon exhales a pulse of high-pitched, nearly inaudible sound in a 60-foot cone. Each creature in that area must make a DC 19 Constitution saving throw. On a failed save, the creature takes 44 (8d10) thunder damage and is incapacitated until the end of its next turn. On a successful save, the creature takes half as much damage and isn't incapacitated.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one Claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Telekinetic Fling (Costs 3 Actions).** The dragon chooses one Small or smaller object that isn't being worn or carried that it can see within 60 feet of it, and it magically hurls the object at a creature it can see within 60 feet of the object. The target must succeed on a DC 17 Dexterity saving throw or take 31 (9d6) bludgeoning damage.


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