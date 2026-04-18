---
type: pc
race: "Humanoid"
class:
 - "Athar Null"
subClass:
 - "CR 5"
cover: "Athar Null.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/5
  - source/mpp
---
###### Athar Null
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Athar Null.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 15 | 14 | 10 |
| **Mod** | +1 | +3 | +2 | +2 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus two more languages
**Saving Throws:** Dex +6, Wis +5
**Skills:** Investigation +8, Perception +5, Stealth +6

---

### Traits

**Avoidance.** If the null is subjected to an effect that allows it to make a saving throw to take half as much damage, it instead takes no damage if it succeeds on the saving throw, and half as much damage if it fails.


---

### Actions

**Multiattack.** The null makes two Force Dagger attacks.

**Force Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 13 (3d8) force damage. The dagger magically returns to the null's hand immediately after a ranged attack.


---

### Bonus Actions

**Defier's Whim.** The null takes the Dash, Disengage, or Use an Object action.


---

### Reactions

**Nullify Spell (3/Day).** The null utters a magical word of cancellation to interrupt a creature it can see that is casting a spell. If the spell is 3rd level or lower, it fails and has no effect. If the spell is 4th level or higher, the null makes an Intelligence check (DC 10 + the spell's level). On a successful check, the spell fails and has no effect.


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