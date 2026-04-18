---
type: pc
race: "Monstrosity (titan)"
class:
 - "Young Kraken"
subClass:
 - "CR 14"
cover: "Young Kraken.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/14
  - source/lr
---
###### Young Kraken
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LR
___

> [!infobox|no-t right]
> ![[Young Kraken.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Monstrosity (titan) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Monstrosity (titan) |
> | :FasBook: Source | LR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 11 | 20 | 19 | 15 | 17 |
| **Mod** | +7 | +0 | +5 | +4 | +2 | +3 |

**Speed:** 20 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 14
**Languages:** Abyssal, Celestial, Infernal, Primordial, telepathy 60 ft. but can't speak
**Saving Throws:** Str +12, Dex +5, Con +10, Int +9, Wis +7
**Damage Immunities:** lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** frightened; paralyzed

---

### Traits

**Amphibious.** The kraken can breathe air and water.


---

### Actions

**Multiattack.** The kraken makes two tentacle attacks, each of which it can replace with one use of Fling.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 20 (3d8 + 7) piercing damage.
If the target is a Medium or smaller creature grappled by the kraken, that creature is swallowed and the grapple ends. While swallowed, the creature is blinded and restrained, it has 3 against attacks and other effects outside the kraken, and it takes 21 (6d6) acid damage at the start of each of the kraken's turns. One Medium or two smaller creatures can be swallowed at the same time.
If the kraken takes 35 damage or more on a single turn from a creature inside it, the kraken must succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in spaces within 10 feet of the kraken. If the kraken dies, a swallowed creature is no longer restrained by it and can escape from the corpse using 10 feet of movement, exiting prone.

**Tentacle.** Melee Weapon Attack: +12 to hit, reach 20 ft., one target. *Hit:* 17 (3d6 + 7) bludgeoning damage, and the target is grappled (escape DC 20). Until the grapple ends, the target is restrained. The kraken has ten tentacles, each of which can grapple one target.

**Fling.** One Medium or smaller object held or creature grappled by the kraken is thrown up to 40 feet in a random direction and knocked prone. If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 13 Dexterity saving throw or take the same damage and be knocked prone.

**Lightning Strike.** The kraken magically create a bolt of lightning, which can strike a target the kraken can see within 90 feet of it. The target must make a DC 18 Dexterity saving throw, taking 22 (4d10) lightning damage on a failed save, or half as much damage on a successful one.


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