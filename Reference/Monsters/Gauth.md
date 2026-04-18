---
type: pc
race: "Aberration (beholder)"
class:
 - "Gauth"
subClass:
 - "CR 6"
cover: "Gauth.png"
campaign:
locations:
tags:
  - race/beholder
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/mpmm
---
###### Gauth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Gauth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration (beholder) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Aberration (beholder) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Stunning Gaze.** When a creature that can see the gauth's central eye starts its turn within 30 feet of the gauth, the gauth can force it to make a DC 14 Wisdom saving throw if the gauth isn't incapacitated and can see the creature. A creature that fails the save is stunned until the start of its next turn.
Unless surprised, a creature can avert its eyes at the start of its turn to avoid the saving throw. If the creature does so, it can't see the gauth until the start of its next turn, when it can avert its eyes again. If the creature looks at the gauth in the meantime, it must immediately make the save.

**Death Throes.** When the gauth dies, the magical energy within it explodes, and each creature within 10 feet of it must make a DC 14 Dexterity saving throw, taking 13 (3d8) force damage on a failed save, or half as much damage on a successful one.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 9 (2d8) piercing damage.

**Eye Rays.** The gauth shoots three of the following magical eye rays at random (roll three d6s, and reroll duplicates), targeting one to three creatures it can see within 120 feet of it:
- **1: Devour Magic Ray.** The target must succeed on a DC 14 Dexterity saving throw or have one of its magic items lose all magical properties until the start of the gauth's next turn. If the object is a charged item, it also loses 1d4 charges. Determine the affected item randomly, ignoring single-use items such as potions and scrolls.
- **2: Enervation Ray.** The target must make a DC 14 Constitution saving throw, taking 18 (4d8) necrotic damage on a failed save, or half as much damage on a successful one.
- **3: Fire Ray.** The target must succeed on a DC 14 Dexterity saving throw or take 22 (4d10) fire damage.
- **4: Paralyzing Ray.** The target must succeed on a DC 14 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- **5: Pushing Ray.** The target must succeed on a DC 14 Strength saving throw or be pushed up to 15 feet away from the gauth and have its speed halved until the start of the gauth's next turn.
- **6: Sleep Ray.** The target must succeed on a DC 14 Wisdom saving throw or fall asleep and remain unconscious for 1 minute. The target awakens if it takes damage or another creature takes an action to wake it. This ray has no effect on Constructs and Undead.


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