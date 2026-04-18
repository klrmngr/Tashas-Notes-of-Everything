---
type: pc
race: "Dragon (gem)"
class:
 - "Adult Emerald Dragon"
subClass:
 - "CR 14"
cover: "Adult Emerald Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/14
  - source/ftd
---
###### Adult Emerald Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Adult Emerald Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Dragon (gem) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 21 | 18 | 16 | 18 |
| **Mod** | +6 | +1 | +5 | +4 | +3 | +4 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 23
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +6, Con +10, Wis +8, Cha +9
**Skills:** Arcana +9, Deception +9, Perception +13, Stealth +6
**Damage Resistances:** fire; psychic

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Shift Perception (1/Day).** The dragon can cast hallucinatory terrain, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 17).

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and can leave a 15-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 7 (2d6) psychic damage.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) slashing damage.

**Disorienting Breath (Recharge 5–6).** The dragon exhales a wave of psychic dissonance in a 60-foot cone. Each creature in that area must make a DC 18 Intelligence saving throw. On a failed save, the creature takes 42 (12d6) psychic damage, and until the end of its next turn, when the creature makes an attack roll or an ability check, it must roll a d6 and reduce the total by the number rolled. On a successful save, the creature takes half as much damage with no additional effects.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one Claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Emerald Embers (Costs 3 Actions).** The dragon creates a dancing mote of green flame around a creature it can see within 60 feet of it. The target must succeed on a DC 17 Dexterity saving throw or take 31 (9d6) fire damage.


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