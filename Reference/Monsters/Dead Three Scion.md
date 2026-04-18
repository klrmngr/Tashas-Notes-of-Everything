---
type: pc
race: "Humanoid"
class:
 - "Dead Three Scion"
subClass:
 - "CR 16"
cover: "Dead Three Scion.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/16
  - source/fraif
---
###### Dead Three Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Dead Three Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 221 (26d8 + 104) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 19 | 18 | 21 | 24 |
| **Mod** | +5 | +2 | +4 | +4 | +5 | +7 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 15
**Languages:** Common
**Saving Throws:** Con +9, Wis +10
**Skills:** Arcana +9, Intimidation +12, Stealth +7
**Damage Immunities:** necrotic
**Condition Immunities:** charmed; frightened

---

### Traits

**Culling Aura.** con DC 20, each Bloodied creature in a 30-foot Emanation originating from the scion at the end of the scion's turn.  The target can't regain Hit Points until the start of the scion's next turn.

**Legendary Resistance (3/Day).** If the scion fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The scion has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The scion makes two attacks, using Death Touch or Mindwrack Bolt in any combination.

**Death Touch.** m +12, reach 5 ft. *Hit:* 25 (4d8 + 7) Necrotic damage.

**Mindwrack Bolt.** r +12, range 120 ft. *Hit:* 21 (6d6) Psychic damage and the target has the Poisoned condition until the start of the scion's next turn.


---

### Legendary Actions

### 

**Attack.** The scion makes a Death Touch or Mindwrack Bolt attack.


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