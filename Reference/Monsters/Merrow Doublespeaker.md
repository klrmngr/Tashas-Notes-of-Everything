---
type: pc
race: "Monstrosity"
class:
 - "Merrow Doublespeaker"
subClass:
 - "CR 4"
cover: "Merrow Doublespeaker.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/lfl
---
###### Merrow Doublespeaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Merrow Doublespeaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 17 | 16 | 12 | 13 | 16 |
| **Mod** | +4 | +3 | +3 | +1 | +1 | +3 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Common, Primordial (Aquan)
**Saving Throws:** Dex +5, Cha +5
**Skills:** Deception +5, Stealth +5

---

### Traits

**Amphibious.** The merrow can breathe air and water.

**Mimicry.** The merrow can mimic voices and animal sounds. A creature that hears the mimicries can tell they are imitations with a successful DC 15 Wisdom (Insight) check.


---

### Actions

**Multiattack.** The merrow makes three Spined Tail attacks. It can replace one of these attacks with a use of Spellcasting to cast Command.

**Spined Tail.** m,r +6, reach 5 ft. or range 20/60 ft. *Hit:* 14 (3d6 + 4) Piercing damage.


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