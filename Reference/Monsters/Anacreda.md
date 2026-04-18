---
type: pc
race: "Fey"
class:
 - "Anacreda"
subClass:
 - "CR 17"
cover: "Anacreda.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/17
  - source/coa
---
###### Anacreda
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Anacreda.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 253 (22d10 + 132) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 16 | 22 | 15 | 16 | 19 |
| **Mod** | +7 | +3 | +6 | +2 | +3 | +4 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 10 ft., passive Perception 19
**Languages:** Common, Giant, Infernal, Sylvan
**Saving Throws:** Con +12, Cha +10
**Skills:** Deception +10, Perception +9
**Damage Immunities:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks

---

### Actions

**Multiattack.** Anacreda makes two Claw attacks. She can replace one of the attacks with a Crushing Hug attack.

**Claw.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 16 (2d8 + 7) slashing damage.

**Crushing Hug.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 51 (8d10 + 7) bludgeoning damage, and if the target is a Large or smaller creature, Anacreda grabs it with both arms. The target has the grappled condition (escape DC 18). Until the grapple ends, the target takes 73 (12d10 + 7) necrotic damage at the start of each of Anacreda's turns. Anacreda can't make attacks while grappling a creature in this way.

**Spinewall.** Anacreda causes a 50-foot-long, 5-foot-wide row of bones to pierce the earth at a point within 120 feet of her. She chooses the direction of the line. The bones rise 10 feet into the air and form a solid wall. A 5-foot section of bone has an AC of 20 and 10 hit points.

**Shattering Shriek (1/Day).** Anacreda shrieks loud enough to shatter stone and bone alike. Each creature within a 50-foot-radius sphere centered on Anacreda must make a DC 18 Constitution saving throw. A creature takes 55 (10d10) thunder damage on a failed save, or half as much damage on a successful one. Unworked stone, exposed bone, and similar materials in the radius are shattered and turned into difficult terrain.


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