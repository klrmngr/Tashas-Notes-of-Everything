---
type: pc
race: "Humanoid (elf)"
class:
 - "Brahma Lutier"
subClass:
 - "CR 2"
cover: "Brahma Lutier.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/ai
---
###### Brahma Lutier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Brahma Lutier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 12 | 11 | 13 | 16 |
| **Mod** | +1 | +2 | +1 | +0 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Elvish
**Skills:** Perception +3, Performance +5, Persuasion +5

---

### Traits

**Fey Ancestry.** Brahma has advantage on saving throws against being charmed, and magic can't put her to sleep.

**Taunt (2/Day).** Brahma can use a bonus action to target one creature she can see within 30 feet of her. If the target can hear Brahma, it must succeed on a DC 13 Charisma saving throw or have disadvantage on ability checks, attack rolls, and saving throws until the start of Brahma's next turn.


---

### Actions

**War Lute.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Song of Domination (3/Day).** Brahma targets one creature that can see or hear her, which must succeed on a DC 13 Wisdom saving throw or be charmed by her for 1 minute. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success. It has disadvantage on these saves if being charmed by Brahma is something the target openly or secretly desires. For 1 hour after the charm effect ends, the target has disadvantage on Intelligence, Wisdom, or Charisma checks made as part of a contest with Brahma.


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