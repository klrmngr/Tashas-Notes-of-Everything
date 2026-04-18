---
type: pc
race: "Humanoid (warlock)"
class:
 - "Oriq Blood Mage"
subClass:
 - "CR 9"
cover: "Oriq Blood Mage.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/scc
---
###### Oriq Blood Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Oriq Blood Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (blood aegis) |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Humanoid (warlock) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 18 | 20 | 12 | 12 |
| **Mod** | +0 | +2 | +4 | +5 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any four languages
**Saving Throws:** Con +8, Int +9, Wis +5, Cha +5
**Skills:** Deception +9, Medicine +5, Survival +5
**Damage Resistances:** necrotic
**Condition Immunities:** exhaustion

---

### Traits

**Blood Aegis.** The AC of the blood mage includes its Constitution modifier while it isn't wearing armor or wielding a shield.

**Oriq Mask.** The blood mage wears an Oriq mask. While wearing the mask, the blood mage can't be targeted by any divination magic or perceived through magical scrying sensors, and it adds double its proficiency bonus to Charisma (Deception) checks (included above).

**Sanguine Sense.** While the blood mage isn't blinded, it can see any creature that isn't an Undead or a Construct within 60 feet of itself, even through 3, heavily obscured areas, invisibility, or any other phenomena that would prevent sight.


---

### Actions

**Multiattack.** The blood mage makes two Blood Lash attacks.

**Blood Lash.** Melee Spell Attack: +9 to hit, reach 10 ft., one target. *Hit:* 21 (3d10 + 5) necrotic damage. If the target is a creature, it can't regain hit points until the start of the blood mage's next turn.

**Blood Boil (Recharge 4–6).** The blood mage chooses a point within 150 feet of itself, and a 20-foot radius sphere centered on that point fills with a burst of searing, blood-red mist. Each creature of the blood mage's choice that it can see in that area must make a DC 17 Constitution saving throw. On a failed save, a creature takes 38 (7d10) necrotic damage and is incapacitated until the end of its next turn. On a success, a creature takes half as much damage and isn't incapacitated. A creature dies if reduced to 0 hit points by this necrotic damage.


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