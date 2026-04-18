---
type: pc
race: "Monstrosity (druid, medusa)"
class:
 - "Euryale"
subClass:
 - "CR 18"
cover: "Euryale.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/18
  - source/bmt
---
###### Euryale
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Euryale.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (druid, medusa) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 297 (35d8 + 140) |
> | :FasUserGroup: Race | Monstrosity (druid, medusa) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 16 | 18 | 12 | 20 | 15 |
| **Mod** | +5 | +3 | +4 | +1 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 21
**Languages:** Common, Druidic
**Saving Throws:** Dex +9, Con +10, Int +7, Wis +11
**Skills:** Animal Handling +11, Insight +17, Medicine +11, Nature +13, Perception +11
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; petrified; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Euryale fails a saving throw, she can choose to succeed instead.

**Special Equipment.** Euryale carries one half of a pair of Sending Stones; the other half of the pair is held by Asteria.


---

### Actions

**Multiattack.** Euryale makes three attacks. If she is in serpent form, only one of these attacks can be Constrict.

**Constrict (Serpent Form Only).** Melee Weapon Attack: +11 to hit, reach 15 ft., one Large or smaller creature. *Hit:* 16 (2d10 + 5) bludgeoning damage, and the target has the grappled condition (escape DC 19). Until this grapple ends, the target takes 11 (2d10) bludgeoning damage at the start of each of its turns, and Euryale can't constrict another target.

**Snake Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage, and the target must succeed on a DC 18 Constitution saving throw or have the poisoned condition until the start of Euryale's next turn.

**Verdant Bolt (Medusa Form Only).** Ranged Spell Attack: +11 to hit, range 120 ft., one target. *Hit:* 18 (4d8) acid damage.


---

### Bonus Actions

**Change Shape.** Euryale changes shape into her Huge serpent form or back into her Medium medusa form. Euryale's game statistics are the same in each form except where noted in this stat block. Any equipment she is wearing or carrying isn't transformed. Euryale reverts to her medusa form if she dies.

**Petrifying Gaze (Recharge 4–6).** Euryale unleashes petrifying magic from her eyes in a 30-foot cone. Each creature in that area must make a DC 18 Constitution saving throw if it doesn't have the blinded condition. If the saving throw fails by 5 or more, the creature has the petrified condition. Otherwise, on a failed save, the creature takes 14 (4d6) force damage, begins to turn to stone, and has the restrained condition. The restrained creature must repeat the saving throw at the end of its next turn. On a failed save, it has the petrified condition, and on a successful save, the effect ends on it, The petrification lasts until the creature is freed by the Greater Restoration spell or other magic A creature can use its reaction, if available, to shut its eyes to avoid the saving throw. If the creature does so, it has the blinded condition until the end of its next turn.


---

### Legendary Actions

### 

**Move.** Euryale moves up to her speed.

**Venomous Strike (Costs 2 Actions).** Euryale makes one Snake Bite attack. If the target has the poisoned condition, the attack deals an extra 16 (3d10) poison damage.


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