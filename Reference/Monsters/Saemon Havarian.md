---
type: pc
race: "Humanoid (human)"
class:
 - "Saemon Havarian"
subClass:
 - "CR 10"
cover: "Saemon Havarian.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/mabjov
---
###### Saemon Havarian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Saemon Havarian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14; 17 with mage armor |
> | :FasHeart: HP | 156 (24d8 + 48) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 18 | 14 | 18 | 11 | 14 |
| **Mod** | +4 | +4 | +2 | +4 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Infernal, Undercommon
**Saving Throws:** Str +8, Dex +8, Wis +4
**Skills:** Athletics +8, Deception +6, Intimidation +6

---

### Traits

**Special Equipment.** Saemon wears a quiver of Ehlonna (holding 40 handaxes).


---

### Actions

**Multiattack.** Saemon makes three Handaxe attacks.

**Handaxe.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage plus 3 (1d6) force damage.


---

### Reactions

**Arcane Shield.** Saemon conjures a swirling yellow barrier and until the start of his next turn he adds +5 to his AC, including against the triggering attack, and he takes no damage from magic missile.


---

### Legendary Actions

### 

**Hurl.** Saemon makes a ranged Handaxe attack.

**Cast a Spell (Costs 2 Actions).** Saemon uses Spellcasting.

**Animate Objects (Costs 3 Actions).** Saemon casts animate objects, targeting up to 10 handaxes he has thrown at enemies. If there are not 10 handaxes available, then he provides the remaining handaxes from his quiver of Ehlonna. Handaxes are Tiny objects.


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