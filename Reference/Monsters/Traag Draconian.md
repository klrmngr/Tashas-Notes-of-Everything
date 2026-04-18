---
type: pc
race: "Monstrosity"
class:
 - "Traag Draconian"
subClass:
 - "CR 5"
cover: "Traag Draconian.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/mcv2dc
---
###### Traag Draconian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Traag Draconian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 17 | 6 | 8 | 9 |
| **Mod** | +5 | +0 | +3 | -2 | -1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Draconic
**Saving Throws:** Str +8, Con +6
**Condition Immunities:** charmed; frightened

---

### Traits

**Blood Frenzy.** The draconian has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Controlled Fall.** If the draconian falls and isn't incapacitated, it subtracts up to 50 feet from the fall when calculating the fall's damage.

**Death Throes.** If the draconian is reduced to 0 hit points, its body erupts into sludge that fills a 10-foot-radius sphere. Each creature within that area must succeed on a DC 14 Dexterity saving throw or be covered in the sludge for 1 minute. While covered in the sludge, a creature's speed is halved. A creature can use its action to scrape the sludge off itself or another creature within 5 feet of itself.


---

### Actions

**Multiattack.** The draconian makes two Claw attacks.

**Claw.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage.

**Flaming Carnage (Recharge 5–6).** The draconian indulges its rage, wreathing itself in fire and moving up to its speed. The draconian can enter creatures' spaces during this move. During this movement, when the draconian enters a creature's space, the creature must make a DC 14 Dexterity saving throw. On a failed save, the creature takes 22 (4d10) fire damage and is knocked prone. On a successful save, the creature takes half as much damage and is pushed to the nearest space out of the draconian's path. A creature can be affected by this draconian's Flaming Carnage only once during a turn.


---

### Reactions

**Violent Retaliation.** If a creature within 10 feet of the draconian hits it with an attack, the draconian can make one Claw attack against that creature. If the Claw attack hits, it deals an additional 4 (1d8) slashing damage.


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