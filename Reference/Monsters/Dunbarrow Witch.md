---
type: pc
race: "Humanoid (human)"
class:
 - "Dunbarrow Witch"
subClass:
 - "CR 5"
cover: "Dunbarrow Witch.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/mcv4ec
---
###### Dunbarrow Witch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Dunbarrow Witch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 72 (16d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 11 | 16 | 15 | 20 |
| **Mod** | +1 | +2 | +0 | +3 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Sylvan, and any one language
**Saving Throws:** Wis +5, Cha +8
**Skills:** Arcana +6, Nature +6

---

### Actions

**Multiattack.** The witch makes two Poison Dagger attacks. It can replace one of these attacks with Spellcasting.

**Poison Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 21 (6d6) poison damage.

**Polymorph Concoction (1/Day).** The witch hurls a bottle of liquid at a point up to 20 feet away from itself, which shatters into a cloud of magical smoke that fills a 10-foot-radius sphere. Each creature in that area must succeed on a DC 16 Wisdom saving throw or transform into a creature, as if under the effects of a polymorph spell, transforming into one of the following forms (roll a d4): 1, bat; 2, frog; 3, lizard; or 4, rat. This transformation lasts for 1 hour or until the creature drops to 0 hit points in its new form.

**Shattered Shards.** The witch targets a point it can see within 30 feet of itself. The air there magically solidifies into a mirrorlike pane, then shatters in a 15-foot cone originating from that point. Each creature in that area must make a DC 16 Dexterity saving throw, taking 25 (10d4) force damage on a failed save, or half as much damage on a successful one.


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