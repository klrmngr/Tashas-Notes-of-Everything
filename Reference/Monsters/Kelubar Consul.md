---
type: pc
race: "Fiend"
class:
 - "Kelubar Consul"
subClass:
 - "CR 11"
cover: "Kelubar Consul.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/11
  - source/mabjov
---
###### Kelubar Consul
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Kelubar Consul.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 97 (13d8 + 39) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 17 | 14 | 15 | 18 |
| **Mod** | +5 | +1 | +3 | +2 | +2 | +4 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Abyssal, Common
**Saving Throws:** Str +9, Con +7, Cha +8
**Skills:** Athletics +9, Insight +6, Persuasion +8
**Damage Resistances:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the kelubar's darkvision.

**Freedom of Movement.** The kelubar is unaffected by difficult terrain, and spells and other magical affects don't reduce its speed or cause it to be paralyzed or restrained. If the kelubar spends 5 feet of movement is automatically escapes from nonmagical restraints or a creature that has it grappled. It is also able to move underwater with no movement or attack penalties.

**Keen Smell.** The kelubar has advantage on Wisdom (Perception) checks that rely on smell.

**Magic Resistance.** The kelubar has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The kelubar's weapon attacks are magical.

**Reckless.** At the start of its turn, the kelubar can gain advantage on all melee weapon attack rolls it makes during that turn, but attack rolls against it have advantage until the start of its next turn.

**Sneak Attack (1/Turn).** The kelubar deals an extra 14 (4d6) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 ft. of an ally of the kelubar that isn't incapacitated and the kelubar doesn't have disadvantage on the attack roll.

**Stench.** Any creature that is not a demodand and starts its turn within 30 feet of the kelubar must succeed on a DC 16 Constitution saving throw or or have the poisoned condition for 1 minute. On a successful saving throw, the creature is immune to the stench of this kelubar for 1 hour.


---

### Actions

**Multiattack.** The kelubar makes one Bite attack and three Claws attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage plus 7 (2d6) acid damage.

**Claws.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage plus 7 (2d6) acid damage.


---

### Bonus Actions

**Summon Demodand (1/Day).** The kelubar rolls a d6. A result of 1-2 summons in two allied farastu stalkers, a result of 3-4 summons in one allied kelubar consul.


---

### Reactions

**Impossible Dodge.** When an attacker that the kelubar can see hits it with an attack, the kelubar can use its reaction to halve the attack's damage.


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