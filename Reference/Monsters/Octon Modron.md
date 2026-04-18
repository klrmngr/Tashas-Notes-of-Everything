---
type: pc
race: "Construct"
class:
 - "Octon Modron"
subClass:
 - "CR 11"
cover: "Octon Modron.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/11
  - source/mpp
---
###### Octon Modron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Octon Modron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 187 (22d10 + 66) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 17 | 17 | 16 | 14 |
| **Mod** | +4 | +2 | +3 | +3 | +3 | +2 |

**Speed:** 30 ft., fly 30 ft. ((hover)), swim 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** Modron, telepathy 120 ft.
**Saving Throws:** Int +7, Wis +7
**Skills:** Perception +11
**Damage Resistances:** psychic

---

### Traits

**Axiomatic Mind.** The octon can't be compelled to act in a manner contrary to its nature or its instructions.

**Combat Ready.** The octon has advantage on initiative checks.

**Disintegration.** If the octon dies, its body disintegrates into dust, leaving behind anything it was carrying.


---

### Actions

**Multiattack.** The octon makes three Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 14 (3d6 + 4) bludgeoning damage plus 9 (2d8) lightning damage.

**Whirlwind of Tentacles (Recharge 5–6).** The octon rapidly extends and spins its ring of tentacles. Each creature within 20 feet of the octon must succeed on a DC 16 Strength saving throw or be pulled up to 10 feet in a straight line toward the octon. Then, the octon makes two Tentacle attacks against each creature within 10 feet of itself.


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