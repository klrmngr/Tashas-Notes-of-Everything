---
type: pc
race: "Celestial"
class:
 - "Barachiel"
subClass:
 - "CR 13"
cover: "Barachiel.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/13
  - source/coa
---
###### Barachiel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Barachiel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 18 | 11 | 14 | 20 |
| **Mod** | +4 | +1 | +4 | +0 | +2 | +5 |

**Speed:** 30 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Celestial, Common, Infernal
**Saving Throws:** Con +9, Wis +7
**Damage Resistances:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; poisoned

---

### Actions

**Multiattack.** Barachiel makes three Greatsword attacks.

**Greatsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 22 (5d8) radiant damage.

**Purifying Flames (Recharge 4–6).** Barachiel wreathes his sword in white flame, then makes a Greatsword attack. On a hit, the target takes an additional 45 (7d12) fire damage plus 45 (7d12) radiant damage. The target must succeed on a DC 18 Charisma saving throw or have the stunned condition until the end of their next turn.


---

### Reactions

**Parry.** Barachiel adds 5 to his AC against one attack. To do so, Barachiel must see the attacker and be wielding a melee weapon.


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