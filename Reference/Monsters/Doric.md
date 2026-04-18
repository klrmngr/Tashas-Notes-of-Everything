---
type: pc
race: "Humanoid (druid)"
class:
 - "Doric"
subClass:
 - "CR 5"
cover: "Doric.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/hat-tg
---
###### Doric
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Honor Among Thieves: Thieves' Gallery
___

> [!infobox|no-t right]
> ![[Doric.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (druid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Humanoid (druid) |
> | :FasBook: Source | Honor Among Thieves: Thieves' Gallery |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 16 | 19 | 10 |
| **Mod** | +1 | +3 | +2 | +3 | +4 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Common, Druidic, Elvish, Infernal, Sylvan
**Saving Throws:** Int +6, Wis +7
**Skills:** Insight +7, Nature +6, Perception +7, Survival +7
**Damage Resistances:** fire

---

### Actions

**Multiattack.** Doric makes two Shaped Claw or Sling attacks. She can replace one attack with a use of Spellcasting.

**Shaped Claw.** Melee Spell Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage.

**Sling.** Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. *Hit:* 8 (2d4 + 3) bludgeoning damage.


---

### Bonus Actions

**Change Shape (5/Day).** Doric magically transforms into a Beast with a challenge rating of 3 or less or into an owlbear (see the Monster Manual).
Doric can remain in that form for up to 2 hours. She can choose whether her equipment falls to the ground, melds with her new form, or is worn by the new form. Doric reverts to her true form if she is incapacitated or dies. She can revert to her true form using a bonus action.
While Doric is transformed, her stat block is replaced by the stat block of that form, except she keeps her current hit points, her hit point maximum, this bonus action, her alignment, and her Intelligence, Wisdom, and Charisma scores.


---

### Reactions

**Fiery Rebuke (3/Day).** When Doric is damaged by a creature that she can see within 60 feet of herself, she magically engulfs the creature in flames. The creature must make a DC 15 Dexterity saving throw, taking 16 (3d10) fire damage on failed save, or half as much damage on a successful one.


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