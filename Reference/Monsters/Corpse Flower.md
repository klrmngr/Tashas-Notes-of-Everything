---
type: pc
race: "Plant"
class:
 - "Corpse Flower"
subClass:
 - "CR 8"
cover: "Corpse Flower.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/8
  - source/mpmm
---
###### Corpse Flower
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Corpse Flower.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 16 | 7 | 15 | 3 |
| **Mod** | +2 | +2 | +3 | -2 | +2 | -4 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 12
**Languages:** —
**Condition Immunities:** blinded; deafened; poisoned

---

### Traits

**Corpses.** When first encountered, a corpse flower contains the corpses of 1d6 + 3 Humanoids. A corpse flower can hold the remains of up to nine Humanoids. These remains have 3 against attacks and other effects outside the corpse flower. If the corpse flower dies, the corpses within it can be pulled free.

**Spider Climb.** The corpse flower can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Stench of Death.** Each creature that starts its turn within 10 feet of the corpse flower or one of its zombies must make a DC 14 Constitution saving throw, unless the creature is a Construct or an Undead. On a failed save, the creature is poisoned until the start of its next turn. On a successful save, the creature is immune to the Stench of Death of all corpse flowers for 24 hours.


---

### Actions

**Multiattack.** The corpse flower makes three Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 9 (2d6 + 2) bludgeoning damage plus 10 (3d6) poison damage.

**Harvest the Dead.** The corpse flower swallows one unsecured Humanoid corpse within 10 feet of it, along with any equipment the corpse is wearing or carrying.


---

### Bonus Actions

**Digest.** The corpse flower digests one corpse in its body and instantly regains 11 (2d10) hit points. Nothing of the digested corpse remains. Any equipment on the corpse is expelled from the corpse flower in its space.

**Reanimate.** The corpse flower animates one corpse in its body, turning it into a zombie. The zombie appears in an unoccupied space within 5 feet of the corpse flower and acts immediately after it in the initiative order. The zombie acts as an ally of the corpse flower but isn't under its control, and the flower's stench clings to it (see Stench of Death).


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