---
type: pc
race: "Giant"
class:
 - "Borborygmos"
subClass:
 - "CR 18"
cover: "Borborygmos.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/18
  - source/ggr
---
###### Borborygmos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Borborygmos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 270 (20d12 + 140) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 11 | 24 | 8 | 17 | 16 |
| **Mod** | +7 | +0 | +7 | -1 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** tremorsense 60 ft., passive Perception 13
**Languages:** Common, Giant
**Saving Throws:** Str +13, Con +13, Wis +9
**Skills:** Athletics +13, Insight +9, Survival +9
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (3/Day).** If Borborygmos fails a saving throw, he can choose to succeed instead.

**Poor Depth Perception.** Borborygmos has disadvantage on any attack roll against a target more than 30 feet away.

**Siege Monster.** Borborygmos deals double damage to objects and structures.


---

### Actions

**Multiattack.** Borborygmos can use his Frightful Presence. He also makes two attacks: one with his maul and one with his stomp.

**Maul.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 28 (6d6 + 7) bludgeoning damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be knocked prone.

**Stomp.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 18 (2d10 + 7) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +13 to hit, range 30/120 ft., one target. *Hit:* 29 (4d10 + 7) bludgeoning damage.

**Frightful Presence.** Each creature of Borborygmos's choice that is within 60 feet of him and can see or hear him must succeed on a DC 17 Wisdom saving throw or become frightened of him for 1 minute. The frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Borborygmos's Frightful Presence for the next 24 hours.


---

### Legendary Actions

### 

**Attack.** Borborygmos makes a weapon attack.

**Bellow (Costs 2 Actions).** Borborygmos yells menacingly at one creature he can see within 60 feet of him. That creature must succeed on a DC 17 Wisdom saving throw or become frightened of him for 1 minute. If the creature is already frightened, it becomes stunned instead. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Borborygmos's Bellow for the next 24 hours.

**Wide Berth (Costs 3 Actions).** Borborygmos moves up to half his speed and can move through the space of any creature smaller than Huge. The first time Borborygmos enters a creature's space during this move, the creature must make a DC 21 Dexterity saving throw. If the saving throw succeeds, the creature is pushed 5 feet away from Borborygmos. If the saving throw fails, that creature is knocked prone, and Borborygmos can make a stomp attack against it.


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