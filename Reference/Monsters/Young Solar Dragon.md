---
type: pc
race: "Dragon"
class:
 - "Young Solar Dragon"
subClass:
 - "CR 9"
cover: "Young Solar Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/9
  - source/bam
---
###### Young Solar Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Young Solar Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 178 (17d10 + 85) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 20 | 13 | 14 | 12 |
| **Mod** | +5 | +2 | +5 | +1 | +2 | +1 |

**Speed:** 20 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 20
**Languages:** Draconic
**Saving Throws:** Dex +6, Con +9, Wis +6, Cha +5
**Skills:** Perception +10, Stealth +6
**Damage Immunities:** radiant
**Condition Immunities:** blinded

---

### Traits

**Flyby.** The dragon doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage plus 7 (2d6) radiant damage.

**Tail.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 8 (1d6 + 5) bludgeoning damage.

**Photonic Breath (Recharge 5–6).** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 120 feet of itself, then blossoms into a 20-foot-radius sphere centered on that point. Each creature in the sphere must make a DC 17 Constitution saving throw, taking 44 (8d10) radiant damage on a failed save, or half as much damage on a successful one.


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