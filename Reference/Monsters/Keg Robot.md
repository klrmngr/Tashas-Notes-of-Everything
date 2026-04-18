---
type: pc
race: "Construct"
class:
 - "Keg Robot"
subClass:
 - "CR 2"
cover: "Keg Robot.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/2
  - source/ai
---
###### Keg Robot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Keg Robot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 15 | 6 | 8 | 5 |
| **Mod** | +3 | +3 | +2 | -2 | -1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** understands Common but can't speak
**Skills:** Perception +1
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Customizable Storage.** A keg robot can hold up to three types of liquid payload totaling 12 gallons within its hollow, barrel-shaped body. A full keg robot can make one liquid attack per gallon before the liquid must be refilled. Filling a keg robot takes 2 rounds per gallon. Differing payloads can alter the keg robot's attacks from those presented here.


---

### Actions

**Fist.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage.

**Acid Squirt.** Ranged Weapon Attack: +5 to hit, range 20/40 ft., one target. *Hit:* 7 (1d8 + 3) acid damage.

**Beer Shower.** The keg robot spews an unnaturally potent beer in a 15-foot cone or in a 30-foot line that is 5 feet wide. Each creature in the area must succeed on a DC 13 Constitution saving throw or be poisoned. While poisoned in this way, a creature has its speed halved by exposure to the potent brew. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
Additionally, the beer shower extinguishes any fires or open flames in its area.

**Hot Oil Spray (Recharge 5–6).** The keg robot sprays hot oil in a 15-foot cone or in a 30-foot line that is 5 feet wide. Each creature in the area must make a DC 13 Dexterity saving throw. On a failed save, a creature takes 7 (1d8 + 3) fire damage and falls prone. On a successful save, a creature takes half as much damage and doesn't fall prone.
Any creature affected by the hot oil spray that takes fire damage before the oil dries (after 1 minute) takes an additional 3 (1d6) fire damage, and the oil burns away.
If the oil that remains in the area of the spray is lit, it burns for 1d4 rounds and deals 3 (1d6) fire damage to any creature that enters the area for the first time on a turn or ends its turn there.


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