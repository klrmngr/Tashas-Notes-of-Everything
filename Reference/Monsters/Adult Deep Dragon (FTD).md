---
type: pc
race: "Dragon"
class:
 - "Adult Deep Dragon"
subClass:
 - "CR 11"
cover: "Adult Deep Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/11
  - source/ftd
---
###### Adult Deep Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Adult Deep Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 147 (14d12 + 56) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 18 | 16 | 16 | 18 |
| **Mod** | +5 | +2 | +4 | +3 | +3 | +4 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 150 ft., passive Perception 17
**Languages:** Common, Draconic, Undercommon
**Saving Throws:** Dex +6, Con +8, Wis +7, Cha +8
**Skills:** Perception +7, Persuasion +12, Stealth +10
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 5 (1d10) poison damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage.

**Tail.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 9 (1d8 + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked prone.

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses its action to end it.

**Nightmare Breath (Recharge 5–6).** The dragon exhales a cloud of spores in a 60-foot cone. Each creature in that area must make a DC 16 Wisdom saving throw. On a failed save, the creature takes 33 (6d10) psychic damage, and it is frightened of the dragon for 1 minute. On a successful save, the creature takes half as much damage with no additional effects. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Commanding Spores.** The dragon releases spores around a creature within 30 feet of it that it can see. The target must succeed on a DC 16 Wisdom saving throw or use its reaction to make a melee weapon attack against a random creature within reach. If no creatures are within reach, or the target can't take a reaction, it takes 5 (1d10) psychic damage.

**Tail.** The dragon makes one Tail attack.

**Spore Salvo (Costs 2 Actions).** The dragon releases poisonous spores around a creature within 30 feet of it that it can see. The target must succeed on a DC 16 Constitution saving throw or take 17 (5d6) poison damage and become poisoned for 1 minute. The poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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