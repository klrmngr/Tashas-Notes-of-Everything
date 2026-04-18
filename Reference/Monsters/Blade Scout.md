---
type: pc
race: "Construct (warforged)"
class:
 - "Blade Scout"
subClass:
 - "CR 7"
cover: "Blade Scout.png"
campaign:
locations:
tags:
  - race/warforged
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/7
  - source/veor
---
###### Blade Scout
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Blade Scout.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Construct (warforged) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Construct (warforged) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 20 | 16 | 10 | 19 | 10 |
| **Mod** | +2 | +5 | +3 | +0 | +4 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common
**Saving Throws:** Dex +8, Wis +7
**Skills:** Acrobatics +8, Perception +7, Stealth +8
**Damage Resistances:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Pack Tactics.** The scout has advantage on an attack roll against a creature if at least one of the scout's allies is within 5 feet of the creature and the ally doesn't have the incapacitated condition.


---

### Actions

**Multiattack.** The scout makes three Armblade or Bolt Launcher attacks. It can replace one of the attacks with a use of Snare Trap.

**Armblade.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.

**Bolt Launcher.** Ranged Weapon Attack: +8 to hit, range 80/320 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage.

**Snare Trap (1/Day).** The scout deploys a Tiny mechanical trap on a solid surface within 5 feet of itself. The trap is hidden, requiring a successful DC 17 Intelligence (Investigation) check to find. The trap lasts for 1 minute. Whenever an enemy enters a space within 10 feet of the trap or starts its turn there, it must succeed on a DC 16 Dexterity saving throw or take 21 (6d6) piercing damage and have the prone condition. A creature makes this saving throw only once per turn.


---

### Bonus Actions

**Dash.** The scout moves up to its speed without provoking opportunity attacks.


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