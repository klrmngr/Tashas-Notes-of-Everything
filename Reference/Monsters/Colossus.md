---
type: pc
race: "Construct (titan)"
class:
 - "Colossus"
subClass:
 - "CR 25"
cover: "Colossus.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/25
  - source/xmm
---
###### Colossus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Colossus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Gargantuan Construct (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 23 |
> | :FasHeart: HP | 553 (27d20 + 270) |
> | :FasUserGroup: Race | Construct (titan) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 11 | 30 | 3 | 11 | 8 |
| **Mod** | +10 | +0 | +10 | -4 | +0 | -1 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** Truesight 300 ft., passive Perception 10
**Languages:** understands Celestial and Common but can't speak
**Saving Throws:** Dex +8, Wis +8
**Damage Resistances:** necrotic; radiant
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned; unconscious

---

### Traits

**Immutable Form.** The colossus can't shape-shift.

**Legendary Resistance (4/Day).** If the colossus fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The colossus has Advantage on saving throws against spells and other magical effects.

**Siege Monster.** The colossus deals double damage to objects and structures.


---

### Actions

**Multiattack.** The colossus makes three attacks, using Slam or Radiant Ray in any combination.

**Slam.** m +18, reach 20 ft. *Hit:* 32 (4d10 + 10) Bludgeoning damage, and the colossus pushes the target up to 20 feet straight away from itself.

**Radiant Ray.** r +18, range 300 ft. *Hit:* 22 (4d10) Radiant damage. If the target is a Large or smaller creature, it has the Prone condition.

**Divine Beam (Recharge 5–6).** dex DC 26, each creature in a 300-foot-long, 10-foot-wide Line.  65 (10d12) Radiant damage.  Half damage.  A creature reduced to 0 Hit Points by this beam disintegrates into dust, leaving behind any magic items it was wearing or carrying.


---

### Legendary Actions

### 

**Smite.** The colossus makes one Radiant Ray attack.

**Stomp.** The colossus moves up to half its Speed without provoking Opportunity Attacks, and it can make one Slam attack at any point during that move.


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