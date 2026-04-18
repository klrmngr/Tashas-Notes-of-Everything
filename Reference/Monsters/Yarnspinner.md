---
type: pc
race: "Fey (archfey)"
class:
 - "Yarnspinner"
subClass:
 - "CR 10"
cover: "Yarnspinner.png"
campaign:
locations:
tags:
  - race/archfey
  - affinity/hostile
  - type/fey
  - size/huge
  - cr/10
  - source/dod
---
###### Yarnspinner
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DoD
___

> [!infobox|no-t right]
> ![[Yarnspinner.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Fey (archfey) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Fey (archfey) |
> | :FasBook: Source | DoD |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 16 | 21 | 18 | 21 | 19 |
| **Mod** | +7 | +3 | +5 | +4 | +5 | +4 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** Common, Druidic, Sylvan
**Saving Throws:** Con +9, Wis +9, Cha +8
**Skills:** Perception +13, Stealth +7
**Condition Immunities:** charmed; frightened

---

### Traits

**Fey Rebirth.** If Yarnspinner dies in his Domain of Delight, he revives with all his hit points 1d4 days later in a safe location in that domain.

**Legendary Resistance (3/Day).** If Yarnspinner fails a saving throw, he can choose to succeed instead.

**Spider Climb.** Yarnspinner can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Walker.** Yarnspinner ignores movement restrictions caused by webbing.

**Web Weaver (3/Day).** Yarnspinner can take 1 minute to craft one of the following structures out of webbing:
- A 3-inch-thick, opaque wall of webbing consisting of up to three 10-foot-square sections, each of which must be anchored on at least two sides by other walls or surfaces. Each section has AC 12; 20 hit points; vulnerability to fire damage; and immunity to bludgeoning, poison, and psychic damage.
- A hut small enough to fit in a 10-foot cube. The hut comes with a closable door and a comfortable bed made of webbing, sized for a Tiny, Small, or Medium creature.
- A message consisting of no more than twenty-five characters, anchored at various points so it hangs in the air.


---

### Actions

**Multiattack.** Yarnspinner makes two Bite attacks and uses Spellcasting or Web once.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (3d6 + 7) piercing damage plus 11 (2d10) poison damage.

**Web.** Yarnspinner shoots webbing at one creature he can see within 120 feet of himself. The target must succeed on a DC 17 Strength saving throw or be restrained for 1 hour. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success.


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