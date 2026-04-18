---
type: pc
race: "Fey"
class:
 - "Deadbark Dryad"
subClass:
 - "CR 13"
cover: "Deadbark Dryad.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/13
  - source/veor
---
###### Deadbark Dryad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Deadbark Dryad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 187 (22d8 + 88) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 18 | 11 | 16 | 18 |
| **Mod** | +3 | +3 | +4 | +0 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 18
**Languages:** Elvish, Sylvan
**Saving Throws:** Con +9, Cha +9
**Skills:** Perception +8, Stealth +8
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Bramble Walk.** Difficult terrain composed of vegetation, such as foliage or thorns, doesn't cost the dryad extra movement.

**Magic Resistance.** The dryad has advantage on saving throws against spells and other magical effects.

**Speak with Beasts and Plants.** The dryad can communicate with Beasts and Plants as if they shared a language.


---

### Actions

**Multiattack.** The dryad makes two Poisonous Thorn attacks and one Sapping Vine attack.

**Poisonous Thorn.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 13 (4d4 + 3) piercing damage plus 10 (3d6) poison damage. If the target is a creature, it must succeed on a DC 17 Constitution saving throw or have the poisoned condition until the start of the dryad's next turn.

**Sapping Vine.** Melee Weapon Attack: +8 to hit, reach 30 ft., one target. *Hit:* The target has the grappled condition (escape DC 16). Until the grapple ends, the target has the restrained condition, and the dryad can't use the same vine on another target. A creature restrained in this way takes 13 (3d8) necrotic damage at the start of its turn.
The dryad has six vines. Each vine can be attacked (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a vine deals no damage to the dryad, but any creature grappled by that vine no longer has the grappled condition. All vines immediately wither and disappear when the dryad is reduced to 0 hit points.


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