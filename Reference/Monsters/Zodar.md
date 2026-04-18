---
type: pc
race: "Aberration"
class:
 - "Zodar"
subClass:
 - "CR 16"
cover: "Zodar.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/16
  - source/bam
---
###### Zodar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Zodar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 200 (16d8 + 128) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 10 | 26 | 12 | 15 | 18 |
| **Mod** | +10 | +0 | +8 | +1 | +2 | +4 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 12
**Languages:** see Disembodied Voice below
**Saving Throws:** Con +13, Int +6, Wis +7, Cha +9
**Damage Immunities:** acid; fire; poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; petrified; poisoned

---

### Traits

**Disembodied Voice.** Up to three times in its life, the zodar can cause a message of up to twenty-five words to issue from the air around it. It speaks only when it has something profoundly important to say, and the message can be understood by any creature that has an Intelligence score of 2 or higher.

**Legendary Resistance (3/Day).** If the zodar fails a saving throw, it can choose to succeed instead.

**Transport Inhibitor.** The zodar can't be teleported or sent to any plane of existence against its will.

**Unusual Nature.** The zodar doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The zodar makes two Crushing Fist attacks. Before or after these attacks, the zodar uses Forced Teleport.

**Crushing Fist.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 21 (2d10 + 10) force damage.

**Forced Teleport.** The zodar magically warps space around one creature it can see within 60 feet of itself. The target must make a DC 21 Constitution saving throw. On a failed save, the target takes 22 (4d10) force damage, and the zodar teleports it, along with any equipment it's wearing or carrying, up to 60 feet to an unoccupied space that the zodar can see and that can support the target. On a successful save, the target takes half as much damage and isn't teleported.


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