---
type: pc
race: "Celestial"
class:
 - "Archaic"
subClass:
 - "CR 18"
cover: "Archaic.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/gargantuan
  - cr/18
  - source/scc
---
###### Archaic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Archaic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Celestial |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 245 (14d20 + 98) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 24 | 27 | 24 | 20 |
| **Mod** | +7 | +0 | +7 | +8 | +7 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** all
**Saving Throws:** Dex +6, Int +14, Wis +13, Cha +11
**Skills:** Arcana +20, Deception +11, History +20, Perception +13
**Damage Resistances:** force
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Enigmatic Mind.** The archaic's mind can't be read, creatures can communicate telepathically with the archaic only if it allows, and magic can't determine whether the archaic is lying.

**Legendary Resistance (3/Day).** If the archaic fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The archaic doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The archaic makes two Force Strike attacks. It can also use Gravity Shift, if available.

**Force Strike.** Melee or Ranged Spell Attack: +14 to hit, reach 15 ft. or range 120 ft., one target. *Hit:* 19 (2d10 + 8) force damage, and the target is pulled up to 10 feet toward the archaic or pushed 10 feet away from it, as the archaic chooses.

**Gravity Shift (Recharge 5–6).** The archaic reverses gravity for one creature it can see within 100 feet of itself. The creature must succeed on a DC 22 Wisdom saving throw or fall 100 feet upward. If the falling creature encounters a solid object (such as a ceiling) in this fall, it strikes the object just as it would during a downward fall. If the creature reaches the top of the area without striking anything, it hovers there until the start of the archaic's next turn, at which time gravity returns to normal and the creature falls.

**Teleport.** The archaic teleports to an unoccupied space that it can see within 120 feet of itself.


---

### Reactions

**Spell Mimicry (1/Day).** Immediately after a creature the archaic can see casts a spell of 5th level or lower, that creature must succeed on a DC 22 Charisma saving throw, or the archaic immediately casts the same spell at the same level (+14 to hit with spell attacks, spell save DC 22), requiring no material components and choosing the spell's targets.


---

### Legendary Actions

### 

**Strike.** The archaic makes one Force Strike attack.

**Teleport.** The archaic uses Teleport.

**Unravel Magic (Costs 2 Actions).** The archaic targets one creature it can see within 120 feet of itself. The target must succeed on a DC 22 Constitution saving throw or take 35 (10d6) force damage, and each spell of 5th level or lower on the target ends.


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