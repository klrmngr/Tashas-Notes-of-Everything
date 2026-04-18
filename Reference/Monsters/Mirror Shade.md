---
type: pc
race: "Undead"
class:
 - "Mirror Shade"
subClass:
 - "CR 10"
cover: "Mirror Shade.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/veor
---
###### Mirror Shade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Mirror Shade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 14 | 10 | 13 | 18 |
| **Mod** | -1 | +3 | +2 | +0 | +1 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —
**Saving Throws:** Dex +7, Wis +5
**Skills:** Deception +8, Stealth +7
**Damage Resistances:** acid; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; psychic; radiant
**Condition Immunities:** blinded; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**False Appearance.** If the mirror shade is within 5 feet of a reflective surface—such as a mirror, glass pane, or still water—it has advantage on its initiative roll. If a creature hasn't observed the mirror shade move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the mirror shade isn't the creature's own reflection.

**Mirror Movement.** The mirror shade can move along the surface of reflective or translucent objects, such as mirrors, without provoking opportunity attacks. It can move through translucent objects as if they were difficult terrain.


---

### Actions

**Multiattack.** The mirror shade makes two Phantasmal Strike attacks and uses Reflect Fear.

**Phantasmal Strike.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) radiant damage plus 7 (2d6) psychic damage.

**Reflect Fear.** The mirror shade targets one creature it can see within 60 feet of itself and projects an illusion of that creature's greatest fear. The target must make a DC 16 Wisdom saving throw. On a failed save, the target takes 28 (8d6) psychic damage and has the frightened condition until the start of the mirror shade's next turn. On a successful save, the target takes half as much damage only.


---

### Bonus Actions

**Mirror Stealth.** While within 5 feet of a reflective surface, such as a mirror, the mirror shade takes the Hide action.


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