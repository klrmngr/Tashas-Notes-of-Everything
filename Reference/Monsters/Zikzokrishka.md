---
type: pc
race: "Undead"
class:
 - "Zikzokrishka"
subClass:
 - "CR 17"
cover: "Zikzokrishka.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/17
  - source/cm
---
###### Zikzokrishka
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Zikzokrishka.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 225 (18d12 + 108) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 23 | 16 | 15 | 19 |
| **Mod** | +7 | +0 | +6 | +3 | +2 | +4 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 24
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Con +12, Wis +8, Cha +10
**Skills:** Perception +14, Stealth +6
**Damage Resistances:** necrotic
**Damage Immunities:** lightning; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Zikzokrishka fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Zikzokrishka has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Zikzokrishka can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 18 (2d10 + 7) piercing damage plus 5 (1d10) lightning damage.

**Claw.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage.

**Tail.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 16 (2d8 + 7) bludgeoning damage.

**Frightful Presence.** Each creature of Zikzokrishka's choice that is within 120 feet of the Zikzokrishka and aware of it must succeed on a DC 18 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the Zikzokrishka's Frightful Presence for the next 24 hours.

**Lightning Breath (Recharge 5–6).** Zikzokrishka exhales lightning in a 90-foot line that is 5 feet wide. Each creature in that line must make a DC 20 Dexterity saving throw, taking 66 (12d10) lightning damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Detect.** Zikzokrishka makes a Wisdom (Perception) check.

**Tail Attack.** Zikzokrishka makes a tail attack.

**Wing Attack (Costs 2 Actions).** Zikzokrishka beats its tattered wings. Each creature within 10 feet of Zikzokrishka must succeed on a DC 21 Dexterity saving throw or take 14 (2d6 + 7) bludgeoning damage and be knocked prone. After beating its wings this way, Zikzokrishka can fly up to half its flying speed.


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