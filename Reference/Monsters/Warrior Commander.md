---
type: pc
race: "Humanoid"
class:
 - "Warrior Commander"
subClass:
 - "CR 10"
cover: "Warrior Commander.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/10
  - source/xmm
---
###### Warrior Commander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Warrior Commander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 161 (19d8 + 76) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 20 | 18 | 14 | 16 | 14 |
| **Mod** | +5 | +5 | +4 | +2 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common plus one other language
**Saving Throws:** Str +9, Dex +9, Con +8, Wis +7
**Skills:** Athletics +9, Insight +7, Perception +7

---

### Actions

**Multiattack.** The warrior makes three attacks, using Greatsword or Longbow in any combination.

**Greatsword.** m +9, reach 5 ft. *Hit:* 19 (4d6 + 5) Slashing damage. The warrior also creates one of the following effects:
- **Sap.** The target has Disadvantage on its next attack roll before the start of the warrior's next turn.
- **Maneuver.** One ally who can see or hear the warrior can take a Reaction to move up to half the ally's Speed without provoking Opportunity Attacks.

**Longbow.** r +9, range 150/600 ft. *Hit:* 18 (3d8 + 5) Piercing damage, and the target's Speed decreases by 10 feet until the end of the target's next turn.


---

### Bonus Actions

**Tactical Charge.** The warrior moves up to half its Speed straight toward an enemy it can see without provoking Opportunity Attacks.


---

### Reactions

**Counterattack.**  The warrior is hit by an attack roll.  The warrior adds 4 to its AC against that attack, possibly causing it to miss. On a miss, the warrior can make one Greatsword or Longbow attack against the attacker.


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