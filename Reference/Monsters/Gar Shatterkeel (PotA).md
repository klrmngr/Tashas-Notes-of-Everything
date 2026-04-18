---
type: pc
race: "Humanoid (human)"
class:
 - "Gar Shatterkeel"
subClass:
 - "CR 9"
cover: "Gar Shatterkeel.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/pota
---
###### Gar Shatterkeel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Gar Shatterkeel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 97 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 15 | 16 | 12 | 18 | 13 |
| **Mod** | +2 | +2 | +3 | +1 | +4 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Aquan, Common
**Skills:** Nature +9, Survival +8
**Damage Resistances:** cold

---

### Traits

**Amphibious.** Gar can breathe air and water.

**Legendary Resistance (2/Day).** If Gar fails a saving throw, he can choose to succeed instead.

**Water Walk.** Gar can stand and move on liquid surfaces as if they were solid ground.

**Watery Fall.** When Gar drops to 0 hit points, his body collapses into a pool of inky water that rapidly disperses. Anything he was wearing or carrying is left behind.


---

### Actions

**Multiattack.** Gar makes two melee attacks, one with his claw and one with Drown.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) bludgeoning damage, and the target is grappled (escape DC 13). Until the grapple ends, Gar can't attack other creatures with his claw.

**Drown.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 4 (1d8) cold damage.


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