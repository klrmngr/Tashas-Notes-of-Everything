---
type: pc
race: "Dragon (gem)"
class:
 - "Adult Crystal Dragon"
subClass:
 - "CR 12"
cover: "Adult Crystal Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/12
  - source/ftd
---
###### Adult Crystal Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Adult Crystal Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Dragon (gem) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 21 | 18 | 15 | 19 |
| **Mod** | +5 | +1 | +5 | +4 | +2 | +4 |

**Speed:** 40 ft., burrow 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 20
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +5, Con +9, Wis +6, Cha +8
**Skills:** Perception +10, Stealth +9, Survival +6
**Damage Resistances:** cold; radiant

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 4 (1d8) radiant damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage.

**Scintillating Breath (Recharge 5–6).** The dragon exhales a burst of brilliant radiance in a 60-foot cone. Each creature in that area must make a DC 17 Constitution saving throw, taking 40 (9d8) radiant damage on a failed save, or half as much damage on a successful one. The dragon then gains 15 temporary hit points by absorbing a portion of the radiant energy.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one Claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Starlight Strike (Costs 3 Actions).** The dragon releases a searing beam of starlight at a creature that it can see within 60 feet of it. The target must succeed on a DC 17 Dexterity saving throw or take 31 (9d6) radiant damage.


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