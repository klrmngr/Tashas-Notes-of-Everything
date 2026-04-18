---
type: pc
race: "Monstrosity (lizardfolk)"
class:
 - "Ssurran Defiler"
subClass:
 - "CR 3"
cover: "Ssurran Defiler.png"
campaign:
locations:
tags:
  - race/lizardfolk
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/bam
---
###### Ssurran Defiler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Ssurran Defiler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (lizardfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor, intellect fortress) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Monstrosity (lizardfolk) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 12 | 16 | 15 | 15 | 7 |
| **Mod** | +1 | +1 | +3 | +2 | +2 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Draconic
**Saving Throws:** Con +5, Int +4
**Skills:** Arcana +4, Perception +4, Stealth +3, Survival +4
**Damage Resistances:** necrotic

---

### Traits

**Hold Breath.** The ssurran can hold its breath for 15 minutes.

**Intellect Fortress.** The ssurran's AC includes its Intelligence modifier.


---

### Actions

**Multiattack.** The ssurran makes two Claw attacks and uses Defile (if available).

**Claw.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) slashing damage plus 4 (1d8) necrotic damage.

**Defile (Recharge 6).** Ordinary vegetation within 10 feet of the ssurran withers and dies. In addition, each creature within 10 feet of the ssurran must make a DC 11 Constitution saving throw, taking 22 (4d10) necrotic damage on a failed save, or half as much damage on a successful one. The ssurran regains 5 (1d10) hit points for each creature that fails the saving throw.


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