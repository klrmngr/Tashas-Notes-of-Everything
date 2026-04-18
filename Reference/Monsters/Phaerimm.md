---
type: pc
race: "Aberration"
class:
 - "Phaerimm"
subClass:
 - "CR 15"
cover: "Phaerimm.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/15
  - source/mabjov
---
###### Phaerimm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Phaerimm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 170 (20d10 + 60) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 16 | 19 | 20 | 23 |
| **Mod** | +5 | +1 | +3 | +4 | +5 | +6 |

**Speed:** 15 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 15
**Languages:** Undercommon, understands Common, telepathy 100 ft.
**Saving Throws:** Int +9, Cha +11
**Skills:** Arcana +9, Insight +10
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** petrified

---

### Traits

**Arcane Sight.** The phaerimm discerns the location of all magical auras within sight and knows which creatures within 60 feet are spellcasters.

**Extended Concentration.** The phaerimm can concentrate on two different spells at the same time. If concentration is broken, then both spells fade immediately.

**Immutable Form.** The phaerimm is immune to any spell or effect that would alter its form.

**Magic Resistance.** The phaerimm has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The phaerimm makes four Claw attacks and then makes a Bite or Stinger attack. Alternatively, it uses Spellcasting and then makes two Claw attacks.

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 18 (2d12 + 5) piercing damage.

**Claw.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.

**Stinger.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage. If the target fails a DC 18 Constitution saving throw, they have the paralyzed condition for 1 minute. The phaerimm's poison forces the paralyzed target to float 5 feet above the ground. The target may repeat the saving throw at the end of each of it's turns.

**Implant.** The phaerimm makes a Stinger attack against a paralyzed target. If the stinger hits, an egg is implanted in the target. This egg can only be removed by spells that cure disease, such as lesser restoration. If the egg is not removed within 90 days, the larva emerges, and the host is killed. A phaerimm has a single egg so may only use this ability once.


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