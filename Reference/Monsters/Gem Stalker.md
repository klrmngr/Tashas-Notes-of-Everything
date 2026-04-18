---
type: pc
race: "Monstrosity"
class:
 - "Gem Stalker"
subClass:
 - "CR 5"
cover: "Gem Stalker.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/ftd
---
###### Gem Stalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Gem Stalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 67 (9d10 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 14 | 15 | 10 | 6 |
| **Mod** | +3 | +2 | +2 | +2 | +0 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** telepathy 60 ft. understands Draconic but can't speak
**Saving Throws:** Dex +5, Int +5
**Skills:** Perception +3, Stealth +5
**Damage Resistances:** psychic

---

### Traits

**Spider Climb.** The gem stalker can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Unusual Nature.** The gem stalker doesn't require food or drink.


---

### Actions

**Multiattack.** The gem stalker makes four Claw attacks.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage.


---

### Bonus Actions

**Crystal Dart.** Ranged Spell Attack: +5 to hit, range 30 ft., one target. *Hit:* 7 (1d10 + 2) force damage, and one of the following effects occurs, determined by the kind of dragon that created the gem stalker:

**Amethyst.** The gem stalker can teleport to an unoccupied space it can see within 30 feet of it.

**Crystal.** The gem stalker gains a number of temporary hit points equal to the damage dealt.

**Emerald.** The target must roll a d4 and subtract the number rolled from the next attack roll it makes before the start of the gem stalker's next turn.

**Sapphire.** The target must succeed on a DC 13 Strength saving throw or be pushed horizontally up to 10 feet away from the gem stalker and be knocked prone.

**Topaz.** The target must succeed on a DC 13 Constitution saving throw or be poisoned until the start of the gem stalker's next turn.


---

### Reactions

**Protective Link.** When another creature the gem stalker can see within 30 feet of it is about to take damage, the gem stalker reduces that damage by 10 (3d6). The gem stalker then takes damage equal to that amount.


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