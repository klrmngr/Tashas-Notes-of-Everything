---
type: pc
race: "Humanoid"
class:
 - "Vampire Familiar"
subClass:
 - "CR 3"
cover: "Vampire Familiar.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/xmm
---
###### Vampire Familiar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Vampire Familiar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 15 | 10 | 10 | 14 |
| **Mod** | +3 | +3 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Common plus one other language
**Saving Throws:** Dex +5, Wis +2
**Skills:** Perception +4, Persuasion +4, Stealth +7
**Damage Resistances:** necrotic
**Condition Immunities:** (except from its vampire master)

---

### Traits

**Vampiric Connection.** While the familiar and its vampire master are on the same plane of existence, the vampire can communicate with the familiar telepathically, and the vampire can perceive through the familiar's senses.


---

### Actions

**Multiattack.** The familiar makes two Umbral Dagger attacks.

**Umbral Dagger.** m,r +5, reach 5 ft. or range 20/60 ft. *Hit:* 5 (1d4 + 3) Piercing damage plus 7 (3d4) Necrotic damage. If the target is reduced to 0 Hit Points by this attack, the target becomes Stable but has the Poisoned condition for 1 hour. While it has the Poisoned condition, the target has the Paralyzed condition.


---

### Bonus Actions

**Deathless Agility.** The familiar takes the Dash or Disengage action.


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