---
type: pc
race: "Dragon"
class:
 - "Solar Dragon Wyrmling"
subClass:
 - "CR 3"
cover: "Solar Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/3
  - source/bam
---
###### Solar Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Solar Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 51 (6d8 + 24) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 15 | 18 | 11 | 12 | 10 |
| **Mod** | +3 | +2 | +4 | +0 | +1 | +0 |

**Speed:** 20 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Draconic
**Saving Throws:** Dex +4, Con +6, Wis +3, Cha +2
**Skills:** Perception +5, Stealth +4
**Damage Immunities:** radiant
**Condition Immunities:** blinded

---

### Traits

**Flyby.** The dragon doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 3 (1d6) radiant damage.

**Tail.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage.

**Photonic Breath (Recharge 5–6).** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 120 feet of itself, then blossoms into a 10-foot-radius sphere centered on that point. Each creature in the sphere must make a DC 14 Constitution saving throw, taking 22 (4d10) radiant damage on a failed save, or half as much damage on a successful one.


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