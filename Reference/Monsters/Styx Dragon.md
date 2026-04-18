---
type: pc
race: "Dragon"
class:
 - "Styx Dragon"
subClass:
 - "CR 20"
cover: "Styx Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/20
  - source/coa
---
###### Styx Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Styx Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 296 (16d20 + 128) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 26 | 19 | 20 | 19 |
| **Mod** | +8 | +2 | +8 | +4 | +5 | +4 |

**Speed:** 30 ft., burrow 20 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 21
**Languages:** Draconic, Infernal
**Saving Throws:** Dex +8, Con +14, Wis +11, Cha +10
**Skills:** Athletics +21, Insight +11, Perception +11, Survival +17
**Damage Immunities:** cold; poison
**Condition Immunities:** blinded; poisoned

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Stygian Wasting.** Creatures afflicted with this disease are incapable of regaining hit points in any way until the disease is cured. Additionally, as their flesh starts to rot, a creature with this disease takes 36 (8d8) necrotic damage after each long rest they finish.

**Styx Dweller.** The dragon is immune to all negative effects from the River Styx.


---

### Actions

**Multiattack.** The dragon can use its Frightful Presence. It then makes three attacks using its Bite, Tail, or a combination of the two. It can replace one of the attacks with Constrict.

**Bite.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 19 (2d10 + 8) piercing damage plus 7 (2d6) poison damage, and the target must make a DC 19 Constitution saving throw. On a failed save, the target contracts Stygian Wasting.

**Tail.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 15 (2d6 + 8) bludgeoning damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 22). The dragon can't make a Tail attack while a creature is grappled in this way.

**Constrict.** The dragon tightens its grip on a creature grappled by its tail. The creature takes 27 (3d12 + 8) bludgeoning damage, has the restrained condition until the start of the dragon's next turn, and must make a DC 19 Constitution saving throw. On a failed save, the target contracts Stygian Wasting.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon must succeed on a DC 18 Wisdom saving throw or have the frightened condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Stygian Breath (Recharge 5–6).** The dragon exhales poisonous Styx water in a 60-foot-long, 10-foot-wide line. Each creature in that line must make a DC 19 Dexterity saving throw, taking 54 (12d8) poison damage on a failed save, or half as much on a successful one. Creatures that fail the save contract Stygian Wasting.


---

### Legendary Actions

### 

**Detect.** The dragon makes a Wisdom (Perception) check.

**Tail Attack.** The dragon makes a Tail attack. If a creature is already grappled, the dragon may use Constrict instead.

**Death Throw (Costs 3 Actions).** If the dragon has successfully restrained a creature with the Constrict ability, it may throw them up to 100 feet away. When it lands, the creature takes 21 (6d6) bludgeoning damage and must make a DC 18 Constitution saving throw. On a failed save, the creature has the unconscious condition for 10 minutes.


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