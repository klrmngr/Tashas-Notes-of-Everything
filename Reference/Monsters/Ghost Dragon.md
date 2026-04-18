---
type: pc
race: "Undead"
class:
 - "Ghost Dragon"
subClass:
 - "CR 17"
cover: "Ghost Dragon.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/17
  - source/ftd
---
###### Ghost Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ghost Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 324 (24d12 + 168) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 25 | 16 | 15 | 19 |
| **Mod** | +5 | +0 | +7 | +3 | +2 | +4 |

**Speed:** 40 ft., fly 80 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 24
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Con +13, Wis +8, Cha +10
**Skills:** Perception +14, Stealth +12
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** acid; cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The ghost dragon can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Legendary Resistance (3/Day).** If the ghost dragon fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The ghost dragon doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The ghost dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 32 (6d8 + 5) cold damage, and the target's speed is halved until the start of the dragon's next turn.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) necrotic damage.

**Terrifying Breath (Recharge 6).** The ghost dragon exhales shadowy mist in a 90-foot cone. Each creature in that area must make a DC 21 Constitution saving throw. On a failed save, the creature takes 40 (9d8) cold damage and is frightened of the ghost dragon for 1 minute. On a successful save, the creature takes half as much damage and isn't frightened.
While frightened of the ghost dragon, a creature is paralyzed. The frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
If a creature's saving throw is successful or the effect ends for it, the creature is immune to this ghost dragon's Terrifying Breath for the next 24 hours.


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