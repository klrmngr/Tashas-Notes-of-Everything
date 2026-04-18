---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Nycaloth"
subClass:
 - "CR 9"
cover: "Nycaloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/xmm
---
###### Nycaloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Nycaloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend (yugoloth) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 152 (16d10 + 64) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 19 | 12 | 10 | 15 |
| **Mod** | +5 | +0 | +4 | +1 | +0 | +2 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 14
**Languages:** Abyssal, Infernal; telepathy 60 ft.
**Skills:** Perception +4, Stealth +4
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Fiendish Restoration.** If the nycaloth dies outside Gehenna, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in Gehenna.

**Magic Resistance.** The nycaloth has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The nycaloth makes two Mercurial Axe attacks.

**Mercurial Axe.** m,r +9, reach 10 ft. or range 30/90 ft. *Hit:* 18 (2d12 + 5) Slashing damage plus 10 (3d6) Force damage. The axe magically returns to the nycaloth's hand immediately after a ranged attack.


---

### Bonus Actions

**Shadowy Teleport.** The nycaloth has the Invisible condition for 1 minute, and it teleports up to 30 feet to an unoccupied space it can see. The condition ends early immediately after it deals damage.


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