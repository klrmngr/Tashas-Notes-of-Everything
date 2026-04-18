---
type: pc
race: "Humanoid (monk)"
class:
 - "Monastic Infiltrator"
subClass:
 - "CR 6"
cover: "Monastic Infiltrator.png"
campaign:
locations:
tags:
  - race/monk
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/crcotn
---
###### Monastic Infiltrator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Monastic Infiltrator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid (monk) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (Unarmored Defense) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (monk) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 20 | 16 | 15 | 17 | 16 |
| **Mod** | +1 | +5 | +3 | +2 | +3 | +3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus three other languages
**Saving Throws:** Dex +8, Wis +6
**Skills:** Acrobatics +8, Deception +9, Perception +6, Stealth +11
**Damage Resistances:** psychic
**Condition Immunities:** charmed

---

### Traits

**Guarded Mind.** Spells and other effects can't read the infiltrator's thoughts or determine if the infiltrator is lying. Creatures can communicate telepathically with the infiltrator only if it allows such contact.

**Unarmored Defense.** While the infiltrator is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The infiltrator makes three Unarmed Strike attacks.

**Unarmed Strike.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) force damage.


---

### Bonus Actions

**Cunning Action.** The infiltrator takes the Dash or Disengage action.


---

### Reactions

**Retaliating Strike.** When a creature within 5 feet of the infiltrator hits or misses the infiltrator with a melee attack, the infiltrator makes one Unarmed Strike attack against the attacker.


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