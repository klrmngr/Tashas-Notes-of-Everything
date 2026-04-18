---
type: pc
race: "Humanoid (cleric, human)"
class:
 - "Kansaldi Fire-Eyes"
subClass:
 - "CR 11"
cover: "Kansaldi Fire-Eyes.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/dsotdq
---
###### Kansaldi Fire-Eyes
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Kansaldi Fire-Eyes.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric, human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 172 (23d8 + 69) |
> | :FasUserGroup: Race | Humanoid (cleric, human) |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 17 | 16 | 19 | 16 |
| **Mod** | +4 | +0 | +3 | +3 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Wis +8, Cha +7
**Skills:** Insight +12, Perception +8, Religion +7
**Damage Immunities:** fire

---

### Traits

**Special Equipment.** Kansaldi has a glowing ruby embedded in her left eye socket. The gem functions as her eye and grants her truesight (included above). The gem can't be removed while Kansaldi is alive. When she dies, a creature can remove the gem as an action. The gem then functions as a gem of seeing.


---

### Actions

**Multiattack.** Kansaldi makes two Pike attacks and uses Flame Burst.

**Pike.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 16 (3d10) radiant damage.

**Flame Burst.** Kansaldi hurls magical flames at a creature she can see within 60 feet of herself. The target must make a DC 16 Dexterity saving throw. On a failed save, the target takes 11 (2d10) fire damage and catches fire; until a creature takes an action to put out the fire, the target takes 5 (1d10) fire damage at the start of each of its turns. On a successful save, the target takes half as much damage and doesn't catch fire.


---

### Bonus Actions

**Dragon Queen's Favor.** Kansaldi or one creature she can see within 60 feet of herself magically regains 17 (2d12 + 4) hit points.


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