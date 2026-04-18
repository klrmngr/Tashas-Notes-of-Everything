---
type: pc
race: "Construct"
class:
 - "Eldritch Eddy"
subClass:
 - "CR 6"
cover: "Eldritch Eddy.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/6
  - source/nf
---
###### Eldritch Eddy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NF
___

> [!infobox|no-t right]
> ![[Eldritch Eddy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 144 (17d10 + 51) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | NF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 16 | 12 | 9 | 17 |
| **Mod** | +0 | +1 | +3 | +1 | -1 | +3 |

**Speed:** 10 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 9
**Languages:** understands Common plus one other language but can't speak
**Saving Throws:** Dex +4, Int +4, Cha +6
**Damage Resistances:** force
**Damage Immunities:** fire; lightning
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Magic Resistance.** The eddy has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The eddy makes two attacks, using Searing Swipe or Arcane Bolt in any combination.

**Searing Swipe.** m +6, reach 10 ft. *Hit:* 13 (3d6 + 3) Fire or Lightning damage (eddy's choice).

**Arcane Bolt.** r +6, range 120 ft. *Hit:* 14 (2d10 + 3) Force damage.


---

### Reactions

**Eldritch Overload.**  The eddy takes damage. dstr DC 14, each creature of the eddy's choice in a 5-foot Emanation originating from the eddy.  7 (2d6) Force damage, and the target has the Prone condition.


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