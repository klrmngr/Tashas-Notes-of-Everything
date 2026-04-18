---
type: pc
race: "Humanoid (elf)"
class:
 - "Gloom Weaver"
subClass:
 - "CR 9"
cover: "Gloom Weaver.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mtf
---
###### Gloom Weaver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Gloom Weaver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14; 17 with mage armor |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 15 | 12 | 18 |
| **Mod** | +0 | +4 | +2 | +2 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Elvish
**Saving Throws:** Dex +8, Con +6
**Damage Immunities:** necrotic
**Condition Immunities:** charmed; exhaustion

---

### Traits

**Burden of Time.** Beasts and humanoids, other than shadar-kai, have disadvantage on saving throws while within 10 feet of the gloom weaver.

**Fey Ancestry.** The gloom weaver has advantage on saving throws against being charmed, and magic can't put it to sleep.


---

### Actions

**Multiattack.** The gloom weaver makes two spear attacks and casts one spell that takes 1 action to cast.

**Shadow Spear.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 26 (4d12) necrotic damage, or 8 (1d8 + 4) piercing damage plus 26 (4d12) necrotic damage if used with two hands.


---

### Reactions

**Misty Escape (Recharges after a Short or Long Rest).** When the gloom weaver takes damage, it turns invisible and teleports up to 60 feet to an unoccupied space it can see. It remains invisible until the start of its next turn or until it attacks or casts a spell.


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