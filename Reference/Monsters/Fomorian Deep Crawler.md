---
type: pc
race: "Giant"
class:
 - "Fomorian Deep Crawler"
subClass:
 - "CR 10"
cover: "Fomorian Deep Crawler.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/10
  - source/bgg
---
###### Fomorian Deep Crawler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fomorian Deep Crawler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 184 (16d12 + 80) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 20 | 9 | 17 | 6 |
| **Mod** | +6 | +2 | +5 | -1 | +3 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Giant, Undercommon
**Skills:** Perception +7, Stealth +6

---

### Traits

**Contortionist.** The fomorian can enter a space large enough for a Large creature without squeezing.

**Crawling Stance.** While the fomorian has the prone condition, crawling does not cost it extra movement. In addition, the prone condition does not grant advantage on attack rolls against the fomorian.

**Spider Climb.** The fomorian can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The fomorian makes two Slam attacks and uses Crawling Hex if it is available.

**Slam.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 22 (3d10 + 6) bludgeoning damage.

**Crawling Hex (Recharge 4–6).** The fomorian targets one creature it can see within 60 feet of itself. The target must succeed on a DC 15 Wisdom saving throw or take 31 (7d8) psychic damage, have the prone condition, and become cursed for 1 hour. While cursed this way, the target can't stand up and end the prone condition on itself.


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