---
type: pc
race: "Dragon"
class:
 - "Adult Moonstone Dragon"
subClass:
 - "CR 15"
cover: "Adult Moonstone Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/ftd
---
###### Adult Moonstone Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Adult Moonstone Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 195 (17d12 + 85) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 18 | 20 | 22 | 20 | 23 |
| **Mod** | +5 | +4 | +5 | +6 | +5 | +6 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 20
**Languages:** Common, Draconic, Elvish, Gnomish, Sylvan
**Saving Throws:** Int +11, Wis +10, Cha +11
**Skills:** Perception +10, Persuasion +11, Stealth +9
**Condition Immunities:** charmed

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 7 (2d6) radiant damage.

**Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.

**Tail.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 9 (1d8 + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC 18 Strength saving throw or be knocked prone.

**Breath Weapon (Recharge 5–6).** The dragon uses one of the following breath weapons:
- **Dream Breath.** The dragon exhales mist in a 90-foot cone. Each creature in that area must succeed on a DC 18 Constitution saving throw or fall unconscious for 10 minutes. This effect ends for a creature if the creature takes damage or someone uses an action to wake it.
- **Moonlight Breath.** The dragon exhales a beam of moonlight in a 90-foot line that is 10 feet wide. Each creature in that area must make a DC 18 Dexterity saving throw, taking 49 (9d10) radiant damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Tail.** The dragon makes one Tail attack.

**Cast a Spell (Costs 2 Actions).** The dragon uses Spellcasting.


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