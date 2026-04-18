---
type: pc
race: "Monstrosity"
class:
 - "Behir"
subClass:
 - "CR 11"
cover: "Behir.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/11
  - source/xmm
---
###### Behir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Behir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 168 (16d12 + 64) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 18 | 7 | 14 | 12 |
| **Mod** | +6 | +3 | +4 | -2 | +2 | +1 |

**Speed:** 50 ft., climb 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 90 ft., passive Perception 16
**Languages:** Draconic
**Skills:** Perception +6, Stealth +7
**Damage Immunities:** lightning

---

### Actions

**Multiattack.** The behir makes one Bite attack and uses Constrict.

**Bite.** m +10, reach 10 ft. *Hit:* 19 (2d12 + 6) Piercing damage plus 11 (2d10) Lightning damage.

**Constrict.** str DC 18, one Large or smaller creature the behir can see within 5 feet.  28 (5d8 + 6) Bludgeoning damage. The target has the Grappled condition (escape DC 16), and it has the Restrained condition until the grapple ends.

**Lightning Breath (Recharge 5–6).** dex DC 16, each creature in a 90-foot-long, 5-foot-wide Line.  66 (12d10) Lightning damage.  Half damage.


---

### Bonus Actions

**Swallow.** dex DC 18, one Large or smaller creature Grappled by the behir (the behir can have only one creature swallowed at a time).  The behir swallows the target, which is no longer Grappled. While swallowed, a creature has the Blinded and Restrained conditions, has Total Cover against attacks and other effects outside the behir, and takes 21 (6d6) Acid damage at the start of each of the behir's turns.
If the behir takes 30 damage or more on a single turn from the swallowed creature, the behir must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate the creature, which falls in a space within 10 feet of the behir and has the Prone condition. If the behir dies, a swallowed creature is no longer Restrained and can escape from the corpse by using 15 feet of movement, exiting Prone.


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