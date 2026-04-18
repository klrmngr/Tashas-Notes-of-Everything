---
type: pc
race: "Humanoid (goblinoid, shapechanger)"
class:
 - "Werebat"
subClass:
 - "CR 2"
cover: "Werebat.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/wdmm
---
###### Werebat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Werebat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid, shapechanger) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 24 (7d6) |
> | :FasUserGroup: Race | Humanoid (goblinoid, shapechanger) |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 10 | 10 | 12 | 8 |
| **Mod** | -1 | +3 | +0 | +0 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Goblin (can't speak in bat form)
**Skills:** Perception +3, Stealth +5
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered

---

### Traits

**Shapechanger.** The werebat can use its action to polymorph into a Medium bat-humanoid hybrid, or into a Large giant bat, or back into its true form, which is humanoid. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Echolocation (Bat or Hybrid Form Only).** The werebat has blindsight out to a range of 60 feet as long as it's not deafened.

**Keen Hearing.** The werebat has advantage on Wisdom (Perception) checks that rely on hearing.

**Nimble Escape (Humanoid Form Only).** The werebat can take the Disengage or Hide action as a bonus action on each of its turns.

**Sunlight Sensitivity.** While in sunlight, the werebat has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack (Humanoid or Hybrid Form Only).** In humanoid form, the werebat makes two scimitar attacks or two shortbow attacks. In hybrid form, it can make one bite attack and one scimitar attack.

**Bite (Bat or Hybrid Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 6 (1d6 + 3) piercing damage, and the werebat gains temporary hit points equal to the damage dealt. If the target is a humanoid, it must succeed on a DC 10 Constitution saving throw or be cursed with werebat lycanthropy.

**Scimitar (Humanoid or Hybrid Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Shortbow (Humanoid or Hybrid Form Only).** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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