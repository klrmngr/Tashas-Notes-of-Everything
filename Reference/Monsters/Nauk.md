---
type: pc
race: "Humanoid (half-orc)"
class:
 - "Nauk"
subClass:
 - "CR 9"
cover: "Nauk.png"
campaign:
locations:
tags:
  - race/half-orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mabjov
---
###### Nauk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Nauk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 170 (20d8 + 80) |
> | :FasUserGroup: Race | Humanoid (half-orc) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 18 | 10 | 12 | 14 |
| **Mod** | +5 | +1 | +4 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Goblin, Orc, Undercommon
**Saving Throws:** Str +9, Dex +5, Con +8
**Skills:** Intimidation +10, Persuasion +6

---

### Traits

**Potion Mishap.** When Nauk uses the Imbibe Potion action more than once in an hour, roll 1d4 for what happens:
- 1. The potion works normally.
- 2. The potion works normally. In addition, Nauk turns invisible for 1 minute or until Nauk attacks or casts a spell.
- 3. The potion has no effect.
- 4. Instead of the normal effect, the potion causes fire to explode out of Nauk's mouth in a 15 foot cone. Nauk and any creature in the cone take 21 (6d6) fire damage.

**Relentless.** When Nauk is reduced to 0 hit points but not killed outright, he can drop to 1 hit point instead. He can't use this feature again for 24 hours

**Special Items.** Nauk wears adamantine plate armor. He wields a +1 maul and a +1 heavy crossbow which is already factored into his stats. He has 2 potions of resistance (cold), 2 potions of resistance (fire), 2 potions of resistance (lightning). He has 2 potions of heroism and 4 potions of superior healing.


---

### Actions

**Multiattack.** Nauk makes three Magic Maul attacks. Nauk may substitute one of those attacks for the Imbibe Potion action.

**Magic Maul.** Melee Weapon Attack: +10 to hit, reach 5 ft., one creature. *Hit:* 13 (2d6 + 6) bludgeoning damage.

**Heavy Crossbow.** Ranged Weapon Attack: +6 to hit, ranged 100/400 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.

**Imbibe Potion.** Nauk drinks a potion from the following list:
- Potion of heroism: Nauk gains 10 temporary hit points for 1 hour. For the same duration, Nauk is under the effect of the bless spell (no concentration required).
- Potion of resistance: Nauk gains resistance from one damage type for 1 hour. Nauk chooses from one of these damage types: cold, fire, lightning.
- Potion of superior healing: Nauk regains 28 hit points.


---

### Reactions

**Parry.** Nauk adds 4 to his AC against one melee attack that would hit him. To do so, Nauk must see the attacker and be wielding a melee weapon.


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