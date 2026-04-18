---
type: pc
race: "Humanoid (human)"
class:
 - "Edwin Odesseiron"
subClass:
 - "CR 15"
cover: "Edwin Odesseiron.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/15
  - source/mabjov
---
###### Edwin Odesseiron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Edwin Odesseiron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13; 18 with staff of power and  mage armor |
> | :FasHeart: HP | 195 (30d8 + 60) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 14 | 20 | 15 | 16 |
| **Mod** | +0 | +3 | +2 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Abyssal, Aquan, Auran, Common, Ignan, Infernal, Terran, Thayan
**Saving Throws:** Int +12, Wis +9
**Skills:** Arcana +15, History +15

---

### Traits

**Contingency.** If Edwin has the incapacitated, paralyzed, or stunned condition, a contingency spell triggers, casting dispel magic at 6th level, targeting Edwin. He also has a body created by the clone spell stored in a cavern one mile beneath the city of Baldur's Gate.

**Simulacrum.** Edwin is always accompanied by a simulacrum of himself. The copy is identical to him in all respects except that it has 58 hit points, does not have the staff of power and can only cast the 'at will' spells available in Edwin's Spellcasting feature.

**Special Equipment.** Edwin wields a staff of power. While held the staff grants a +2 bonus to attack and damage rolls made with it, and a +2 bonus to armor class, saving throws, and spell attack rolls (all factored into Edwin's statistics).


---

### Actions

**Multiattack.** Edwin makes a Staff of Power attack or uses Spellcasting or Staff Spellcasting. He then makes two Elemental Blast attacks.

**Staff of Power.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage or 6 (1d8 + 2) bludgeoning damage if wielded with two hands. Edwin can expend one of the staff's charges to deal an extra 14 (4d6) force damage on a hit.

**Elemental Blast.** Ranged Spell Attack: +12 to hit, range 120 ft., one target. *Hit:* 38 (6d10 + 5) acid, cold, lightning, or fire damage.

**Edwin's Choking Cloud (Recharge 6).** Edwin creates a 20-foot-radius sphere of poisonous fog centered on a point within 120 feet. The cloud spreads around corners but lasts only until the start of Edwin's next turn. When a creature enters the cloud's area for the first time on a turn or starts its turn there, that creature must make a DC 18 Constitution saving throw. The creature takes 45 (10d8) poison damage on a failed save, or half as much damage on a successful one. Creatures are affected even if they hold their breath or don't need to breathe.


---

### Bonus Actions

**Summon Hell Hounds.** Edwin magically summons three hell hounds. The summoned hell hounds appear in an unoccupied space within 60 feet of Edwin, and act as Edwin's allies. They remain for 10 minutes, until they or Edwin dies, or until Edwin dismisses them as an action.


---

### Reactions

**Edwin's Evasive Footwork.** As a reaction to taking damage, Edwin teleports up to 30 feet to an unoccupied space that he can see.


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