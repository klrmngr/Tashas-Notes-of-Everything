---
type: pc
race: "Construct (warforged)"
class:
 - "Blade Lieutenant"
subClass:
 - "CR 9"
cover: "Blade Lieutenant.png"
campaign:
locations:
tags:
  - race/warforged
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/9
  - source/veor
---
###### Blade Lieutenant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Blade Lieutenant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Construct (warforged) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Construct (warforged) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 19 | 14 | 14 | 17 |
| **Mod** | +4 | +1 | +4 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common
**Saving Throws:** Int +6, Cha +7
**Skills:** Insight +6, Intimidation +7, Perception +6
**Damage Resistances:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Pack Tactics.** The lieutenant has advantage on an attack roll against a creature if at least one of the lieutenant's allies is within 5 feet of the creature and the ally doesn't have the incapacitated condition.


---

### Actions

**Multiattack.** The lieutenant makes three Longsword or Javelin Launcher attacks.

**Longsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 17 (3d8 + 4) slashing damage, or 20 (3d10 + 4) slashing damage if used with two hands.

**Javelin Launcher.** Ranged Weapon Attack: +8 to hit, range 30/120 ft., one target. *Hit:* 14 (3d6 + 4) piercing damage, and the target has the prone condition.


---

### Bonus Actions

**Command Ally.** The lieutenant targets one ally it can see within 30 feet of itself. If the target can see or hear the lieutenant, the target can make one melee attack using its reaction, if available, and has advantage on the attack roll.

**Rally the Troops (1/Day).** The lieutenant ends the charmed and frightened conditions on itself and each creature of its choice that it can see within 30 feet of itself.


---

### Reactions

**Parry.** The lieutenant adds 3 to its AC against one melee attack that would hit it. To do so, the lieutenant must see the attacker and be wielding a melee weapon.


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