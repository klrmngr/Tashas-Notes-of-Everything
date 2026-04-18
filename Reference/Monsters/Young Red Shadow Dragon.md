---
type: pc
race: "Dragon"
class:
 - "Young Red Shadow Dragon"
subClass:
 - "CR 13"
cover: "Young Red Shadow Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/13
  - source/mm
---
###### Young Red Shadow Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Young Red Shadow Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 178 (17d10 + 85) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 14 | 11 | 19 |
| **Mod** | +6 | +0 | +5 | +2 | +0 | +4 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Con +10, Wis +5, Cha +9
**Skills:** Perception +10, Stealth +10
**Damage Resistances:** necrotic
**Damage Immunities:** fire

---

### Traits

**Living Shadow.** While in dim light or darkness, the dragon has resistance to damage that isn't force, psychic, or radiant.

**Shadow Stealth.** While in dim light or darkness, the dragon can take the Hide action as a bonus action.

**Sunlight Sensitivity.** While in sunlight, the dragon has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The dragon makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 3 (1d6) necrotic damage.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Shadow Breath (Recharge 5–6).** The dragon exhales shadowy fire in a 30-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking 56 (16d6) necrotic damage on a failed save, or half as much damage on a successful one. A humanoid reduced to 0 hit points by this damage dies, and an undead shadow rises from its corpse and acts immediately after the dragon in the initiative count. The shadow is under the dragon's control.


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