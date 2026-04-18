---
type: pc
race: "Celestial"
class:
 - "Deathpact Angel"
subClass:
 - "CR 14"
cover: "Deathpact Angel.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/14
  - source/ggr
---
###### Deathpact Angel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Deathpact Angel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 175 (27d8 + 54) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 14 | 19 | 20 | 23 |
| **Mod** | +3 | +4 | +2 | +4 | +5 | +6 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** all
**Saving Throws:** Int +9, Wis +10, Cha +11
**Skills:** Insight +10, Intimidation +11, Perception +10, Persuasion +11
**Damage Resistances:** necrotic; radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Exploitation of the Debtors.** As a bonus action, the angel targets a creature charmed by it that it can see within 30 feet of it. The angel deals 11 (2d10) necrotic damage to the target, and the angel gains temporary hit points equal to the damage dealt.

**Flyby.** The angel doesn't provoke an opportunity attack when it flies out of an enemy's reach.

**Magic Resistance.** The angel has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The angel makes two attacks with its scythe. It can substitute Chains of Obligation for one of these attacks.

**Scythe.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 9 (2d4 + 4) slashing damage plus 27 (6d8) necrotic damage.

**Chains of Obligation.** The angel targets one creature charmed by it that it can see within 90 feet of it. The target must succeed on a DC 19 Charisma saving throw or become paralyzed for 1 minute or until it takes any damage.


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