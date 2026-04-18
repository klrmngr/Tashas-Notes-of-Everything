---
type: pc
race: "Beast"
class:
 - "Two-Headed Crocodile"
subClass:
 - "CR 1"
cover: "Two-Headed Crocodile.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1
  - source/imr
---
###### Two-Headed Crocodile
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Two-Headed Crocodile.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 19 (3d10 + 3) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 13 | 2 | 10 | 5 |
| **Mod** | +2 | +0 | +1 | -4 | +0 | -3 |

**Speed:** 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Skills:** Perception +2, Stealth +2

---

### Traits

**Hold Breath.** The two-headed crocodile can hold its breath for 15 minutes.

**Two Heads.** The two-headed crocodile has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, and knocked unconscious.

**Wakeful.** When one of the crocodile's heads is asleep, its other head is awake.


---

### Actions

**Multiattack.** The two-headed crocodile makes two attacks with its bite.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage, and the target is grappled (escape DC 12). Until this grapple ends, the target is restrained, and that head of the crocodile can't bite another target.


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