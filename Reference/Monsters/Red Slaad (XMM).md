---
type: pc
race: "Aberration"
class:
 - "Red Slaad"
subClass:
 - "CR 5"
cover: "Red Slaad.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/5
  - source/xmm
---
###### Red Slaad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Red Slaad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 16 | 6 | 6 | 7 |
| **Mod** | +3 | +1 | +3 | -2 | -2 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Slaad; telepathy 60 ft.
**Skills:** Perception +1
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Magic Resistance.** The slaad has Advantage on saving throws against spells and other magical effects.

**Regeneration.** The slaad regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point.


---

### Actions

**Multiattack.** The slaad makes three Injecting Claw attacks.

**Injecting Claw.** m +6, reach 10 ft. *Hit:* 10 (2d6 + 3) Piercing damage. If the target is a Humanoid not cursed by a slaad, it is subjected to the following effect. con DC 14.  The target is cursed unawares, and a minuscule slaad egg is implanted in it. Removing the curse destroys the egg.
Over 2d4 × 10 days, the egg gestates. In the final 24 hours, the cursed target feels unwell; its Speed is halved, and it has Disadvantage on D20 Tests. At the end of this time, the egg turns into a Slaad Tadpole, which chews out of the host and kills it.


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