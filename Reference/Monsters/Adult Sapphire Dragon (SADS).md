---
type: pc
race: "Dragon"
class:
 - "Adult Sapphire Dragon"
subClass:
 - "CR 15"
cover: "Adult Sapphire Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/sads
---
###### Adult Sapphire Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SADS
___

> [!infobox|no-t right]
> ![[Adult Sapphire Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 60) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | SADS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 21 | 18 | 17 | 18 |
| **Mod** | +6 | +3 | +5 | +4 | +3 | +4 |

**Speed:** 40 ft., burrow 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 23
**Languages:** telepathy 120 ft., Common, Draconic
**Saving Throws:** Dex +8, Con +10, Wis +8, Cha +9
**Skills:** History +9, Perception +13, Persuasion +14, Stealth +8
**Damage Immunities:** thunder
**Condition Immunities:** frightened

---

### Traits

**Legendary Resistance (2/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Spider Climb.** The dragon can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Tunneler.** The dragon can burrow through solid rock at half its burrow speed and can choose to leave a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The dragon can use its Frightful Presence. It then makes two melee attacks, one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 3 (1d6) thunder damage.

**Claws.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 19 (3d8 + 6) slashing damage.

**Tail.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 17 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Debilitating Breath (Recharge 5–6).** The dragon exhales a pulse of high-pitched, nearly inaudible sound in a 60-foot-cone. Each creature in that cone must make a DC 18 Constitution saving throw. On a failed save, the creature takes 45 (13d6) thunder damage and is incapacitated until the end of its next turn. On a successful save, the creature takes half as much damage and isn't incapacitated.


---

### Legendary Actions

### 

**Tail Attack.** The dragon makes a tail attack.

**Telekinetic Fling.** The dragon chooses a Small or smaller object that isn't being worn or carried that it can see within 60 feet of it, and magically hurls the object at a creature it can see within 60 feet of the object. The target must succeed on a DC 17 Dexterity saving throw or take 15 (4d6) bludgeoning damage.

**Teleport (Costs 2 Actions).** The dragon magically teleports to an unoccupied space it can see within 30 feet of it.


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