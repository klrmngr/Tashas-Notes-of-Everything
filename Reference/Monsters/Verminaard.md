---
type: pc
race: "Humanoid (cleric, human)"
class:
 - "Verminaard"
subClass:
 - "CR 17"
cover: "Verminaard.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/17
  - source/mcv2dc
---
###### Verminaard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Verminaard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric, human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (+2 plate armor) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid (cleric, human) |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 13 | 15 | 16 | 18 | 17 |
| **Mod** | +6 | +1 | +2 | +3 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 26
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Wis +10, Cha +9
**Skills:** Perception +16, Religion +9
**Damage Immunities:** fire
**Condition Immunities:** charmed; frightened

---

### Traits

**Draconic Command.** Whenever a Dragon or a creature with the Draconic Devotion trait within 30 feet of Verminaard makes an attack roll, the creature can roll a d4 and add the number rolled to the attack roll.

**Legendary Resistance (3/Day).** If Verminaard fails a saving throw, he can choose to succeed instead.

**Special Equipment.** Verminaard wears +2 plate armor and wields the mace Nightbringer, which grants him darkvision as well as immunity to fire damage and to the charmed and frightened conditions (included above).


---

### Actions

**Multiattack.** Verminaard makes two Nightbringer attacks and uses Malediction.

**Nightbringer.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 12 (1d6 + 9) bludgeoning damage plus 10 (4d4) radiant damage. If the target is a creature, the target must succeed on a DC 20 Constitution saving throw or be blinded until the start of Verminaard's next turn.

**Malediction.** Verminaard utters an unholy word, causing profane fire to descend on one creature Verminaard can see within 60 feet of himself. The creature must make a DC 18 Dexterity saving throw, taking 11 (2d10) necrotic damage plus 11 (2d10) radiant damage on a failed save or half as much damage on a successful one.


---

### Bonus Actions

**Dragon Queen's Favor (5/Day).** Verminaard or one creature he can see within 60 feet of himself magically regains 17 (2d12 + 4) hit points.


---

### Legendary Actions

### 

**Tactical Movement.** Verminaard moves up to his speed or commands a mount he is riding to move up to its speed. This movement doesn't provoke opportunity attacks.

**Fervent Strike (Costs 2 Actions).** Verminaard makes one Nightbringer attack. If this attack hits, it deals an additional 7 (2d6) bludgeoning damage.

**Cast a Spell (Costs 3 Actions).** Verminaard uses Spellcasting.


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