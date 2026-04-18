---
type: pc
race: "Humanoid (human, wizard)"
class:
 - "Tasha the Witch"
subClass:
 - "CR 19"
cover: "Tasha the Witch.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/19
  - source/veor
---
###### Tasha the Witch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Tasha the Witch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 19 (robe of the archmagi) |
> | :FasHeart: HP | 210 (28d8 + 84) |
> | :FasUserGroup: Race | Humanoid (human, wizard) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 17 | 23 | 12 | 22 |
| **Mod** | +0 | +4 | +3 | +6 | +1 | +6 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Abyssal, Celestial, Common, Draconic, Elvish, Infernal, Sylvan
**Saving Throws:** Int +12, Wis +7, Cha +12
**Skills:** Arcana +18, History +12, Persuasion +12
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (3/Day).** If Tasha fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Tasha has advantage on saving throws against spells and other magical effects. (This trait is bestowed by her Robe of the Archmagi.)

**Special Equipment.** Tasha wears a Robe of the Archmagi.


---

### Actions

**Multiattack.** Tasha makes two Caustic Blast attacks and uses Psychic Whip once.

**Caustic Blast.** Melee or Ranged Spell Attack: +14 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 21 (6d4 + 6) acid damage.

**Psychic Whip.** Tasha psychically lashes out at one creature she can see within 90 feet of herself. The target must make a DC 20 Intelligence saving throw. On a failed save, the target takes 21 (6d6) psychic damage and has the stunned condition until the start of Tasha's next turn. On a successful save, the target takes half as much damage only.


---

### Bonus Actions

**Abyssal Visage (2/Day).** For 1 minute, Tasha gains a flying speed of 30 feet, is immune to poison damage and the poisoned condition, and has advantage on attack rolls against any creature that doesn't have all its hit points. These benefits end early if Tasha has the incapacitated condition or if she uses another bonus action to dismiss them.


---

### Reactions

**Arcane Rebuff.** Immediately after Tasha takes damage, she unleashes arcane energy in a 10-foot-radius sphere centered on herself. All other creatures in that area must make a DC 20 Dexterity saving throw, taking 19 (3d12) lightning damage on a failed save or half as much damage on a successful one. Tasha then teleports, along with any equipment she is wearing or carrying, to an unoccupied space she can see within 60 feet of herself.


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