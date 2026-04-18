---
type: pc
race: "Elemental"
class:
 - "Dust Hulk"
subClass:
 - "CR 5"
cover: "Dust Hulk.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/5
  - source/bgg
---
###### Dust Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Dust Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 19 | 16 | 10 | 12 | 8 |
| **Mod** | +2 | +4 | +3 | +0 | +1 | -1 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Giant, Terran
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; restrained

---

### Traits

**Air Form.** The dust hulk can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch without squeezing.

**Death Burst.** When the dust hulk dies, it explodes in a burst of dust that fills a 10-foot-radius sphere centered on itself. Each creature in that area must succeed on a DC 14 Constitution saving throw or have the blinded condition for 1 minute. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Actions

**Multiattack.** The dust hulk makes three Slam attacks. It can replace one of these attacks with Stinging Dust.

**Slam.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage.

**Stinging Dust.** One creature of the dust hulk's choice inside its space must make a DC 14 Constitution saving throw. On a failed save, the creature takes 10 (3d6) bludgeoning damage and has the blinded condition until the end of its next turn. On a successful save, the creature takes half as much damage only.


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