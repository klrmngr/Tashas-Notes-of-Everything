---
type: pc
race: "Elemental"
class:
 - "Cinder Hulk"
subClass:
 - "CR 7"
cover: "Cinder Hulk.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/7
  - source/bgg
---
###### Cinder Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cinder Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 84 (8d10 + 40) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 20 | 9 | 14 | 10 |
| **Mod** | +5 | +1 | +5 | -1 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Giant, Ignan
**Saving Throws:** Dex +4, Con +8, Wis +5
**Skills:** Perception +5
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** When the cinder hulk dies, it leaves behind a cloud of cinders and smoke that fills a 10-foot-radius sphere centered on its space. The sphere is heavily obscured. Any creature that moves into the area for the first time on a turn or starts its turn there must succeed on a DC 16 Constitution saving throw or take 10 (3d6) fire damage. The cloud lasts for 1 minute or until it is dispersed by strong wind.


---

### Actions

**Multiattack.** The cinder hulk makes two Slam attacks.

**Slam.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) bludgeoning damage plus 10 (3d6) fire damage.

**Wave of Cinders (Recharge 5–6).** The cinder hulk emits a wave of smoldering ash from its face, hands, or chest in a 30-foot cone. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes 31 (7d8) fire damage and has the blinded condition until the end of its next turn. On a successful save, a creature takes half as much damage only.


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