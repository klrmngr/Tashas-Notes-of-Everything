---
type: pc
race: "Plant"
class:
 - "Aartuk Starhorror"
subClass:
 - "CR 2"
cover: "Aartuk Starhorror.png"
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
###### Aartuk Starhorror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Aartuk Starhorror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 14 | 13 | 16 | 10 |
| **Mod** | +1 | +0 | +2 | +1 | +3 | +0 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Aartuk
**Skills:** Stealth +4

---

### Traits

**Spider Climb.** The aartuk can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The aartuk makes two Branch attacks, two Radiant Pellet attacks, or one of each.

**Branch.** Melee Weapon Attack: +3 to hit, reach 10 ft., one target. *Hit:* 8 (2d6 + 1) bludgeoning damage.

**Radiant Pellet.** Ranged Spell Attack: +2 to hit, range 60 ft., one target. *Hit:* 7 (3d4) radiant damage.


---

### Bonus Actions

**Rally the Troops (1/Day).** The aartuk magically ends the charmed and frightened conditions on itself and each creature of its choice that it can see within 30 feet of itself.

**Tongue (Recharge 6).** The aartuk tries to use its gooey tongue to snare one Medium or smaller creature it can see within 30 feet of itself. The target must make a DC 12 Dexterity saving throw. On a failed save, the target is grappled by the tongue (escape DC 11) and pulled up to 25 feet toward the aartuk. The tongue can grapple one creature at a time.


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