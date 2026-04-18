---
type: pc
race: "Humanoid (human)"
class:
 - "Faldorn"
subClass:
 - "CR 13"
cover: "Faldorn.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/mabjov
---
###### Faldorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Faldorn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11; 16 with barkskin |
> | :FasHeart: HP | 130 (20d8 + 40) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 12 | 14 | 12 | 20 | 15 |
| **Mod** | +1 | +1 | +2 | +1 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** Common, Druidic, Elvish, Sylvan
**Saving Throws:** Int +6, Wis +10
**Skills:** Medicine +10, Nature +11, Perception +10, Survival +15

---

### Traits

**Staff of the Woodlands.** This staff can be wielded as a magic quarterstaff that grants a +2 bonus to attack and damage rolls made with it and grants Faldorn a +2 bonus to spell attack rolls (already factored into Faldorn's attacks). The staff has 10 charges. It regains 1d6 + 4 expended charges each dawn. Faldorn can use an action to expend 1 or more of the staff's charges to cast one of the following spells from it, with a spell save DC of 14:
- 0 charges: pass without trace
- 1 charge each: animal friendship, speak with animals
- 2 charges each: barkskin, locate animals or plants
- 3 charges: speak with plants
- 5 charges: awaken
- 6 charges: wall of thorns


---

### Actions

**Multiattack.** Faldorn makes two Staff of the Woodlands attacks and uses Spellcasting. Or she uses Spellcasting and then Change Shape if available.

**Staff of the Woodlands.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage, or 7 (1d8 + 3) bludgeoning damage if wielded with two hands plus 7 (2d6) acid damage.

**Shadowlight (Recharge 6).** A beam of dim light emerges from Faldorn in a 5-foot-wide, 300-foot-long line. Each creature in the line must make a Constitution saving throw. On a failed save, a creature takes 27 (6d8) radiant damage and is blinded until Faldorn's next turn. On a successful save, it takes half as much damage and isn't blinded.

**Change Shape (2/Day).** Faldorn magically polymorphs into a Beast or Elemental with a challenge rating of 6 or less, and can remain in this form for up to 9 hours. Faldorn reverts to her true form if she dies or falls unconscious. She can revert to her true form using a bonus action on her turn. While in a new form, Faldorn retains her game statistics and ability to speak, but her AC, movement modes, Strength, and Dexterity are replaced by those of the new form, and she gains any special senses, proficiencies, traits, actions, and reactions (except class features, legendary actions, and lair actions) that the new form has but that she lacks. She can cast her spells with verbal or somatic components in her new form. The new form's attacks count as magical for the purpose of overcoming resistances and immunity to nonmagical attacks.


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