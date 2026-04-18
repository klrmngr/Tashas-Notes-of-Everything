---
type: pc
race: "Undead"
class:
 - "Devourer"
subClass:
 - "CR 13"
cover: "Devourer.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/13
  - source/mpmm
---
###### Devourer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Devourer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 20 | 13 | 10 | 16 |
| **Mod** | +5 | +1 | +5 | +1 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Abyssal, telepathy 120 ft.
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Unusual Nature.** A devourer doesn't require air, drink, or sleep.


---

### Actions

**Multiattack.** The devourer makes two Claw attacks and can use either Imprison Soul or Soul Rend, if available.

**Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 21 (6d6) necrotic damage.

**Imprison Soul.** The devourer chooses a living Humanoid with 0 hit points that it can see within 30 feet of it. That creature is teleported inside the devourer's ribcage and imprisoned there. While imprisoned in this way, the creature is restrained and has disadvantage on death saving throws. If the creature dies while imprisoned, the devourer regains 25 hit points and immediately recharges Soul Rend. Additionally, at the start of its next turn, the devourer regurgitates the slain creature as a bonus action, and the creature becomes an undead. If the victim had 2 or fewer Hit Dice, it becomes a zombie. If it had 3 to 5 Hit Dice, it becomes a ghoul. Otherwise, it becomes a wight. A devourer can imprison only one creature at a time.

**Soul Rend (Recharge 6).** The devourer creates a vortex of life-draining energy in a 20-foot radius centered on itself. Each creature in that area must make a DC 18 Constitution saving throw, taking 44 (8d10) necrotic damage on a failed save, or half as much damage on a successful one.


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