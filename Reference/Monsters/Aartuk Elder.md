---
type: pc
race: "Plant"
class:
 - "Aartuk Elder"
subClass:
 - "CR 3"
cover: "Aartuk Elder.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/3
  - source/bam
---
###### Aartuk Elder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Aartuk Elder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 15 | 12 | 14 | 12 |
| **Mod** | +4 | +0 | +2 | +1 | +2 | +1 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Aartuk

---

### Traits

**Spider Climb.** The aartuk can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The aartuk makes two Branch attacks, two Radiant Pellet attacks, or one of each.

**Branch.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Radiant Pellet.** Ranged Spell Attack: +4 to hit, range 60 ft., one target. *Hit:* 10 (4d4) radiant damage.


---

### Bonus Actions

**Tongue (Recharge 6).** The aartuk tries to use its gooey tongue to snare one Large or smaller creature it can see within 30 feet of itself. The target must make a DC 12 Dexterity saving throw. On a failed save, the target is grappled by the tongue (escape DC 14) and pulled up to 25 feet toward the aartuk. The tongue can grapple one creature at a time.


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