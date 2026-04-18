---
type: pc
race: "Humanoid (elf)"
class:
 - "Shadar-kai Gloom Weaver"
subClass:
 - "CR 9"
cover: "Shadar-kai Gloom Weaver.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mpmm
---
###### Shadar-kai Gloom Weaver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Shadar-kai Gloom Weaver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Burden of Time.** Beasts and Humanoids (except elves) have disadvantage on saving throws while within 10 feet of the shadar-kai.

**Fey Ancestry.** The shadar-kai has advantage on saving throws against being charmed, and magic can't put it to sleep.


---

### Actions

**Multiattack.** The shadar-kai makes three Shadow Spear attacks. It can replace one attack with a use of Spellcasting.

**Shadow Spear.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 30/120, one target. *Hit:* 7 (1d6 + 4) piercing damage plus 26 (4d12) necrotic damage. The spear magically returns to the shadar-kai's hand immediately after a ranged attack.


---

### Reactions

**Misty Escape (Recharge 6).** When the shadar-kai takes damage, it turns invisible and teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see. It remains invisible until the start of its next turn or until it attacks or casts a spell.


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