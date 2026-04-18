---
type: pc
race: "Construct"
class:
 - "Fiendish Flesh Golem"
subClass:
 - "CR 8"
cover: "Fiendish Flesh Golem.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/8
  - source/bgdia
---
###### Fiendish Flesh Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Fiendish Flesh Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 210 (20d10 + 100) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 9 | 20 | 7 | 10 | 5 |
| **Mod** | +5 | -1 | +5 | -2 | +0 | -3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Resistances:** cold; fire
**Damage Immunities:** lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine or silvered
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Berserk.** Whenever the golem starts its turn with 100 hit points or fewer, roll a d6. On a 6, the golem goes berserk. On each of its turns while berserk, the golem attacks the nearest creature it can see. If no creature is near enough to move to and attack, the golem attacks an object, with preference for an object smaller than itself. Once the golem goes berserk, it continues to do so until it is destroyed or regains all its hit points. If the golem's creator is within 60 feet of the berserk golem, the creator can try to calm it by speaking firmly and persuasively. The golem must be able to hear its creator, who must take an action to make a DC 15 Charisma (Persuasion) check. If the check succeeds, the golem ceases being berserk. If it takes damage while still at 100 hit points or fewer, the golem might go berserk again.

**Immutable Form.** The golem is immune to any spell or effect that would alter its form.

**Lightning Absorption.** Whenever the golem is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

**Magic Resistance.** The golem has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The golem's weapon attacks are magical.


---

### Actions

**Multiattack.** The golem makes two slam attacks.

**Slam.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) bludgeoning damage.


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