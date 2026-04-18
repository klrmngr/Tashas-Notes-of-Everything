---
type: pc
race: "Plant"
class:
 - "Aartuk Weedling"
subClass:
 - "CR 2"
cover: "Aartuk Weedling.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/2
  - source/bam
---
###### Aartuk Weedling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Aartuk Weedling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 13 | 10 | 13 | 10 |
| **Mod** | +2 | +1 | +1 | +0 | +1 | +0 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Aartuk

---

### Traits

**Spider Climb.** The aartuk can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The aartuk makes two Branch attacks, two Radiant Pellet attacks, or one of each.

**Branch.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 8 (2d6 + 2) bludgeoning damage.

**Radiant Pellet.** Ranged Spell Attack: +3 to hit, range 60 ft., one target. *Hit:* 7 (3d4 + 1) radiant damage.


---

### Bonus Actions

**Tongue (Recharge 6).** The aartuk tries to use its gooey tongue to snare one Medium or smaller creature it can see within 30 feet of itself. The target must make a DC 11 Dexterity saving throw. On a failed save, the target is grappled by the tongue (escape DC 12) and pulled up to 25 feet toward the aartuk. The tongue can grapple one creature at a time.


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