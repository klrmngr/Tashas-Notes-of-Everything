---
type: pc
race: "Monstrosity (shapechanger)"
class:
 - "Dread Doppelganger"
subClass:
 - "CR 5"
cover: "Dread Doppelganger.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/5
  - source/mabjov
---
###### Dread Doppelganger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Dread Doppelganger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Monstrosity (shapechanger) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 22 | 14 | 17 | 14 | 15 |
| **Mod** | +0 | +6 | +2 | +3 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common
**Skills:** Deception +8, Stealth +9
**Condition Immunities:** charmed

---

### Traits

**Ambusher.** The dread doppelganger has advantage on attack rolls against any creature it has surprised.

**Shapechanger.** The dread doppelganger can use its action to polymorph into a Small or Medium Humanoid it has seen, or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Surprise Attack.** If the dread doppelganger surprises a creature and hits it with an attack during the first round of combat, the target takes an extra 17 (5d6) damage from the attack.


---

### Actions

**Multiattack.** The dread doppelganger makes three Slam attacks.

**Slam.** Melee Weapon Attack: +9 to hit, range 5 ft., one target. *Hit:* 10 (1d8 + 6).

**Read Thoughts.** The dread doppelganger magically reads the surface thoughts of one creature within 60 feet of it. The effect can penetrate barriers, but 3 ft. of wood or dirt, 2 feet of stone, 2 inches of metal, or a thin sheet of lead blocks it. While the target is in range, the dread doppelganger can continue reading its thoughts, as long as the dread doppelganger's Concentration isn't broken (as if concentrating on a spell). While reading the target's mind, the doppelganger has advantage on Wisdom (Insight) and Charisma (Deception, Intimidation, and Persuasion) checks against the target.


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