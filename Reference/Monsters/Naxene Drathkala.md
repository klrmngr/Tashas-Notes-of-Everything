---
type: pc
race: "Humanoid (human)"
class:
 - "Naxene Drathkala"
subClass:
 - "CR —"
cover: "Naxene Drathkala.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Naxene Drathkala
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Naxene Drathkala.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 11 | 11 | 17 | 12 | 11 |
| **Mod** | -1 | +0 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Dwarvish, Elvish
**Skills:** Arcana +5, History +5

---

### Traits

**Roleplaying Information.** Goldenfields' crops are vital Waterdeep's survival, which is why the Watchful Order of Magists and Protectors sent Naxene to make sure the temple-farm is adequately defended. At first she regarded the task as a punishment, but now she appreciates the peace and quiet.
Ideal: "There's no problem that can't be solved with magic."
Bond: "I have great respect for Lady Laeral Silverhand of Waterdeep. She and the Lords' Alliance are going to bring some much-needed order to this lawless land."
Flaw: "I'm too smart to be wrong about anything."


---

### Actions

**Staff.** Melee Weapon Attack: +1 to hit, reach 5 ft., one creature. *Hit:* 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands.


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