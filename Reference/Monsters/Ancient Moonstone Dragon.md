---
type: pc
race: "Dragon"
class:
 - "Ancient Moonstone Dragon"
subClass:
 - "CR 21"
cover: "Ancient Moonstone Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/21
  - source/ftd
---
###### Ancient Moonstone Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ancient Moonstone Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 330 (20d20 + 120) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 18 | 23 | 20 | 22 | 26 |
| **Mod** | +6 | +4 | +6 | +5 | +6 | +8 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +12, Wis +13, Cha +15
**Skills:** Perception +13, Persuasion +15, Stealth +11
**Condition Immunities:** charmed

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 11 (2d10) radiant damage.

**Claw.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Tail.** Melee Weapon Attack: +13 to hit, reach 20 ft., one target. *Hit:* 10 (1d8 + 6) bludgeoning damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be knocked prone.

**Breath Weapon (Recharge 5–6).** The dragon uses one of the following breath weapons:
- **Dream Breath.** The dragon exhales mist in a 90-foot cone. Each creature in that area must succeed on a DC 21 Constitution saving throw or fall unconscious for 10 minutes. This effect ends for a creature if the creature takes damage or someone uses an action to wake it.
- **Moonlight Breath.** The dragon exhales a beam of moonlight in a 120-foot line that is 10 feet wide. Each creature in that area must make a DC 21 Dexterity saving throw, taking 60 (11d10) radiant damage on a failed save, or half as much damage on a successful one.


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