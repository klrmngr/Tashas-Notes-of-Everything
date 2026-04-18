---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Krenko"
subClass:
 - "CR 1"
cover: "Krenko.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/kkw
---
###### Krenko
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: KKW
___

> [!infobox|no-t right]
> ![[Krenko.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (chain shirt, shield) |
> | :FasHeart: HP | 21 (6d6) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | KKW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 10 | 10 | 8 | 14 |
| **Mod** | +0 | +2 | +0 | +0 | -1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Goblin
**Skills:** Stealth +6, Deception +4, Persuasion +4

---

### Traits

**Nimble Escape.** Krenko can take the Disengage or Hide action as a bonus action on each of his turns.


---

### Actions

**Multiattack.** Krenko makes two attacks with his scimitar.

**Scimitar.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage plus 2 (1d4) poison damage..

**Light Crossbow.** Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


---

### Reactions

**Redirect Attack.** When a creature Krenko can see targets him with an attack, Krenko chooses another goblin within 5 feet of him. The two goblins swap places, and the chosen goblin becomes the target instead.


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