---
type: pc
race: "Undead (wizard)"
class:
 - "Lich"
subClass:
 - "CR 21"
cover: "Lich.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/21
  - source/xmm
---
###### Lich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Lich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Medium Undead (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 315 (42d8 + 126) |
> | :FasUserGroup: Race | Undead (wizard) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 21 | 14 | 16 |
| **Mod** | +0 | +3 | +3 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 19
**Languages:** all
**Saving Throws:** Dex +10, Con +10, Int +12, Wis +9
**Skills:** Arcana +19, History +12, Insight +9, Perception +9
**Damage Resistances:** cold; lightning
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the lich fails a saving throw, it can choose to succeed instead.

**Spirit Jar.** If destroyed, the lich reforms in 1d10 days if it has a spirit jar, reviving with all its Hit Points. The new body appears in an unoccupied space within the lich's lair.


---

### Actions

**Multiattack.** The lich makes three attacks, using Eldritch Burst or Paralyzing Touch in any combination.

**Eldritch Burst.** m,r +12, reach 5 ft. or range 120 ft. *Hit:* 31 (4d12 + 5) Force damage.

**Paralyzing Touch.** m +12, reach 5 ft. *Hit:* 15 (3d6 + 5) Cold damage, and the target has the Paralyzed condition until the start of the lich's next turn.


---

### Legendary Actions

### 

**Deathly Teleport.** The lich teleports up to 60 feet to an unoccupied space it can see, and each creature within 10 feet of the space it left takes 11 (2d10) Necrotic damage.

**Disrupt Life.** con DC 20, each creature that isn't an Undead in a 20-foot Emanation originating from the lich.  31 (9d6) Necrotic damage.  Half damage.  The lich can't take this action again until the start of its next turn.


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