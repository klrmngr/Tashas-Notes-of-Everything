---
type: pc
race: "Humanoid (human)"
class:
 - "Alyxian the Absolved"
subClass:
 - "CR 14"
cover: "Alyxian the Absolved.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/14
  - source/crcotn
---
###### Alyxian the Absolved
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Alyxian the Absolved.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 15 (leather armor, shield) |
> | :FasHeart: HP | 161 (19d8 + 76) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 18 | 13 | 14 | 19 |
| **Mod** | +4 | +2 | +4 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Common, Elvish
**Saving Throws:** Str +9, Con +9, Wis +7
**Skills:** Athletics +9, Insight +7, Perception +7, Persuasion +9

---

### Traits

**Divinely Blessed.** Alyxian can't be surprised and can't be changed into another form against his will.

**Legendary Resistance (2/Day).** If Alyxian fails a saving throw, he can choose to succeed instead.


---

### Actions

**Multiattack.** Alyxian makes two Spear attacks.

**Spear.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing damage when used with two hands to make a melee attack, plus 9 (2d8) radiant damage.

**Force Wave (1/Day).** Alyxian strikes the ground, creating a burst of energy that ripples outward. Each creature he chooses within a 30-foot-radius sphere centered on himself must succeed on a DC 17 Constitution saving throw or take 35 (10d6) force damage and be knocked prone. A creature that succeeds on the saving throw takes half as much damage and isn't knocked prone.


---

### Reactions

**Parry.** Alyxian adds 3 to his AC against one attack roll that would hit him. To do so, Alyxian must see the attacker and be wielding a melee weapon.


---

### Legendary Actions

### 

**Arch Heart's Strike.** Alyxian makes one Spear attack, and all damage from this attack is radiant.

**Change Bringer's Dance.** Alyxian moves up to his speed. This movement doesn't provoke opportunity attacks.

**Moon Weaver's Veil (Costs 2 Actions).** Alyxian becomes invisible until the end of his next turn. Any equipment he is wearing or carrying becomes invisible with him.


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