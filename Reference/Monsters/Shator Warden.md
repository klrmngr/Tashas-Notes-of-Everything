---
type: pc
race: "Fiend"
class:
 - "Shator Warden"
subClass:
 - "CR 14"
cover: "Shator Warden.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/14
  - source/mabjov
---
###### Shator Warden
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Shator Warden.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 11 | 17 | 14 | 16 | 20 |
| **Mod** | +7 | +0 | +3 | +2 | +3 | +5 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Abyssal, Common
**Saving Throws:** Str +12, Con +8, Cha +10
**Skills:** Athletics +12, Insight +8, Persuasion +10
**Damage Resistances:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the shator's darkvision.

**Keen Smell.** The shator has advantage on Wisdom (Perception) checks that rely on smell.

**Magic Resistance.** The shator has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The shator's weapon attacks are magical.


---

### Actions

**Multiattack.** The shator makes one Bite attack or one Poisonous Spit attack (if available) and then makes two Claws attacks.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 16 (2d8 + 7) piercing damage plus 10 (3d6) acid damage.

**Claws.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 11 (1d8 + 7) slashing damage plus 7 (2d6) acid damage.

**Poisonous Spit (Recharge 5–6).** The shator exhales poisonous spit in a 20-foot line that is 5 feet wide. Each creature in that line must make a DC 18 Dexterity saving throw, taking 22 (5d8) acid damage on a failed save and having the paralyzed condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.


---

### Bonus Actions

**Summon Demodand (1/Day).** The shator rolls a d6. A result of 1-2 summons in two allied farastu stalkers, a result of 3-4 summons in one allied shator warden.


---

### Reactions

**Poisonous Slime.** When hit with a melee attack, the shator expels a toxic slime. The attacker must succeed on a DC 18 Dexterity saving throw or have the paralyzed condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.


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