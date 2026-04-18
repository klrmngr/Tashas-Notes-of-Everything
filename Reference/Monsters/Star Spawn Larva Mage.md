---
type: pc
race: "Aberration"
class:
 - "Star Spawn Larva Mage"
subClass:
 - "CR 16"
cover: "Star Spawn Larva Mage.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/16
  - source/mpmm
---
###### Star Spawn Larva Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Star Spawn Larva Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 168 (16d8 + 96) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 23 | 18 | 12 | 16 |
| **Mod** | +3 | +1 | +6 | +4 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Deep Speech
**Saving Throws:** Dex +6, Wis +6, Cha +8
**Skills:** Perception +6
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened; paralyzed; petrified; poisoned; restrained

---

### Traits

**Return to Worms.** When the mage is reduced to 0 hit points, it breaks apart into a [[Swarm Of Insects]] in the same space. Unless the swarm is destroyed, the mage reforms from it 24 hours later.


---

### Actions

**Multiattack.** The mage makes three Slam or Eldritch Bolt attacks.

**Slam.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage, and the target must succeed on a DC 19 Constitution saving throw or be poisoned until the end of its next turn.

**Eldritch Bolt.** Ranged Spell Attack: +8 to hit, range 60 ft., one target. *Hit:* 19 (3d10 + 3) force damage.

**Plague of Worms (Recharge 6).** Each creature other than a star spawn within 10 feet of the mage must succeed on a DC 19 Dexterity saving throw or take 22 (5d8) necrotic damage and be blinded and restrained by masses of swarming worms. The affected creature takes 22 (5d8) necrotic damage at the start of each of the mage's turns. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Reactions

**Feed on Weakness.** When a creature within 20 feet of the mage fails a saving throw, the mage gains 10 temporary hit points.


---

### Legendary Actions

### 

**Slam.** The mage makes one Slam attack.

**Eldritch Bolt (Costs 2 Actions).** The mage makes one Eldritch Bolt attack.

**Feed (Costs 3 Actions).** Each creature restrained by the mage's Plague of Worms takes 13 (3d8) necrotic damage, and the mage gains 6 temporary hit points.


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