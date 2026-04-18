---
type: pc
race: "Aberration"
class:
 - "Gauth"
subClass:
 - "CR 6"
cover: "Gauth.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/vgm
---
###### Gauth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Gauth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 16 | 15 | 15 | 13 |
| **Mod** | +0 | +2 | +3 | +2 | +2 | +1 |

**Speed:** 0 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Deep Speech, Undercommon
**Saving Throws:** Int +5, Wis +5, Cha +4
**Skills:** Perception +5
**Condition Immunities:** prone

---

### Traits

**Stunning Gaze.** When a creature that can see the gauth's central eye starts its turn within 30 feet of the gauth, the gauth can force it to make a DC 14 Wisdom saving throw if the gauth isn't incapacitated and can see the creature. A creature that fails the save is stunned until the start of its next turn, when it can avert its eyes again. If the creature looks at the gauth in the meantime, it must immediately make the save.

**Death Throes.** When the gauth dies, the magical energy within it explodes, and each creature within 10 feet of it must make a DC 14 Dexterity saving throw, taking 13 (3d8) force damage on a failed save, or half as much damage on a successful one.


---

### Actions

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (2d8) piercing damage.

**Eye Rays.** The gauth shoots three of the following magical eye rays at random (reroll duplicates), choosing one to three targets it can see within 120 feet of it:
- The targeted creature must succeed on a DC 14 Dexterity saving throw or have one of its magic items lose all magical properties until the start of the gauth's next turn. If the object is a charged item, it also loses 1d4 charges. Determine the affected item randomly, ignoring single-use items such as potions and scrolls.
- The targeted creature must make a DC 14 Constitution saving throw, taking 18 (4d8) necrotic damage on a failed save, or half as much damage on a successful one.
- The targeted creature must succeed on a DC 14 Strength saving throw or be pushed up to 15 feet directly away from the gauth and have its speed halved until the start of the gauth's next turn.
- The targeted creature must succeed on a DC 14 Dexterity saving throw or take 22 (4d10) fire damage.
- The targeted creature must succeed on a DC 14 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The targeted creature must succeed on a DC 14 Wisdom saving throw or fall asleep and remain unconscious for 1 minute. The target awakens if it takes damage or another creature takes an action to wake it. This ray has no effect on constructs and undead.


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