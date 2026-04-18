---
type: pc
race: "Dragon (gem)"
class:
 - "Ancient Crystal Dragon"
subClass:
 - "CR 19"
cover: "Ancient Crystal Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/19
  - source/ftd
---
###### Ancient Crystal Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ancient Crystal Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (gem) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 222 (12d20 + 96) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 12 | 26 | 20 | 16 | 21 |
| **Mod** | +7 | +1 | +8 | +5 | +3 | +5 |

**Speed:** 40 ft., burrow 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 25
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +7, Con +14, Wis +9, Cha +11
**Skills:** Perception +15, Stealth +13, Survival +9
**Damage Resistances:** cold; radiant

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 18 (2d10 + 7) piercing damage plus 9 (2d8) radiant damage.

**Claw.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage.

**Scintillating Breath (Recharge 5–6).** The dragon exhales a burst of brilliant radiance in a 90-foot cone. Each creature in that area must make a DC 22 Constitution saving throw, taking 49 (11d8) radiant damage on a failed save, or half as much damage on a successful one. The dragon then gains 25 temporary hit points by absorbing a portion of the radiant energy.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one Claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Starlight Strike (Costs 3 Actions).** The dragon releases a searing beam of starlight at a creature that it can see within 60 feet of it. The target must succeed on a DC 19 Dexterity saving throw or take 38 (11d6) radiant damage.


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