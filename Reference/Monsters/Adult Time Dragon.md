---
type: pc
race: "Dragon"
class:
 - "Adult Time Dragon"
subClass:
 - "CR 18"
cover: "Adult Time Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/18
  - source/mpp
---
###### Adult Time Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Adult Time Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 250 (20d12 + 120) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 14 | 23 | 23 | 16 | 20 |
| **Mod** | +7 | +2 | +6 | +6 | +3 | +5 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 25
**Languages:** all
**Saving Throws:** Dex +8, Con +12, Wis +9, Cha +11
**Skills:** Arcana +12, History +18, Perception +15, Stealth +14

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage plus 7 (2d6) force damage.

**Time Breath (Recharge 5–6).** The dragon exhales a wave of shimmering light in a 60-foot cone. Nonmagical objects and vegetation in that area that aren't being worn or carried crumble to dust. Each creature in that area must make a DC 20 Constitution saving throw. On a failed save, a creature takes 36 (8d8) force damage and is magically weakened as it is desynchronized from the time stream. While the creature is in this state, attack rolls against it have advantage, and it has the poisoned condition. On a successful save, a creature takes half as much damage only. A weakened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself after it succeeds on three of these saves.


---

### Reactions

**Reactive Rend.** After using Legendary Resistance or in response to being hit by an attack roll, the dragon makes one Rend attack.

**Slow Time.** Immediately after a creature the dragon can see ends its turn, the dragon targets a creature it can see within 60 feet of itself that is weakened by its Time Breath. Until the weakened effect ends on the target, its speed becomes 0, and its speed can't increase.

**Time Slip.** The dragon halves the damage it takes from an attack made against it, provided it can see the attacker. The dragon can then immediately teleport, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.


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