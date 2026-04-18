---
type: pc
race: "Dragon"
class:
 - "Adult Red Dragon"
subClass:
 - "CR 17"
cover: "Adult Red Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/17
  - source/mm
---
###### Adult Red Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Adult Red Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 256 (19d12 + 133) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 25 | 16 | 13 | 21 |
| **Mod** | +8 | +0 | +7 | +3 | +1 | +5 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 23
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Con +13, Wis +7, Cha +11
**Skills:** Perception +13, Stealth +6
**Damage Immunities:** fire

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 19 (2d10 + 8) piercing damage plus 7 (2d6) fire damage.

**Claw.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 15 (2d6 + 8) slashing damage.

**Tail.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 17 (2d8 + 8) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 19 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Fire Breath (Recharge 5–6).** The dragon exhales fire in a 60-foot cone. Each creature in that area must make a DC 21 Dexterity saving throw, taking 63 (18d6) fire damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Detect.** The dragon makes a Wisdom (Perception) check.

**Tail Attack.** The dragon makes a tail attack.

**Wing Attack (Costs 2 Actions).** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 22 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning damage and be knocked prone. The dragon can then fly up to half its flying speed.


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