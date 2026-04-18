---
type: pc
race: "Construct"
class:
 - "Hexton Modron"
subClass:
 - "CR 13"
cover: "Hexton Modron.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/13
  - source/mpp
---
###### Hexton Modron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Hexton Modron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 209 (22d12 + 66) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 17 | 19 | 17 | 15 |
| **Mod** | +4 | +3 | +3 | +4 | +3 | +2 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +9, Wis +8
**Skills:** Perception +13
**Damage Resistances:** lightning; psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Axiomatic Mind.** The hexton can't be compelled to act in a manner contrary to its nature or its instructions.

**Combat Ready.** The hexton has advantage on initiative rolls.

**Disintegration.** If the hexton dies, its body disintegrates into dust, leaving behind anything it was carrying.

**Legendary Resistance (4/Day).** If the hexton fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The hexton makes one Pincer attack and two Tentacle attacks.

**Pincer.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage plus 10 (3d6) force damage. If the target is a creature, it must succeed on a DC 17 Constitution saving throw or have the incapacitated condition until the end of its next turn.

**Tentacle.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 14). Until this grapple ends, the hexton can't use this tentacle against other targets. The hexton has six tentacles, each of which can grapple one target.


---

### Reactions

**Counter Magic.** The hexton attempts to interrupt a creature it can see that is casting a spell. If the spell is 3rd level or lower, it fails and has no effect. If the spell is 4th level or higher, the hexton makes an Intelligence check (DC 10 + the spell's level). On a success, the spell fails and has no effect.

**Lightning Rebuke.** When a creature within 120 feet of the hexton damages it, the hexton magically retaliates with an arc of lightning. The creature must make a DC 17 Dexterity saving throw, taking 11 (2d10) lightning damage on a failed save, or half as much damage on a successful one.


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