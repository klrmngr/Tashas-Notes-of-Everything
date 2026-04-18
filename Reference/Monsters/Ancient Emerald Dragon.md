---
type: pc
race: "Dragon (gem)"
class:
 - "Ancient Emerald Dragon"
subClass:
 - "CR 21"
cover: "Ancient Emerald Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/21
  - source/ftd
---
###### Ancient Emerald Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ancient Emerald Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (gem) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 332 (19d20 + 133) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 12 | 25 | 20 | 18 | 20 |
| **Mod** | +7 | +1 | +7 | +5 | +4 | +5 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 28
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +8, Con +14, Wis +11, Cha +12
**Skills:** Arcana +12, Deception +12, Perception +18, Stealth +8
**Damage Resistances:** fire; psychic

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and can leave a 20-foot-diameter tunnel in its wake.

**Warp Perception (1/Day).** The dragon can cast mirage arcane, requiring no spell components and using Intelligence as the spellcasting ability.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 18 (2d10 + 7) piercing damage plus 10 (3d6) psychic damage.

**Claw.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage.

**Disorienting Breath (Recharge 5–6).** The dragon exhales a wave of psychic dissonance in a 90-foot cone. Each creature in that area must make a DC 22 Intelligence saving throw. On a failed save, the creature takes 56 (16d6) psychic damage, and until the end of its next turn, when the creature makes an attack roll or an ability check, it must roll a d8 and reduce the total by the number rolled. On a successful save, the creature takes half as much damage with no additional effects.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one Claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Emerald Embers (Costs 3 Actions).** The dragon creates a dancing mote of green flame around a creature it can see within 60 feet of it. The target must succeed on a DC 20 Dexterity saving throw or take 42 (12d6) fire damage.


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