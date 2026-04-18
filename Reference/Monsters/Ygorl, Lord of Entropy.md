---
type: pc
race: "Aberration"
class:
 - "Ygorl, Lord of Entropy"
subClass:
 - "CR 23"
cover: "Ygorl, Lord of Entropy.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/23
  - source/mff
---
###### Ygorl, Lord of Entropy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Ygorl, Lord of Entropy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 325 (26d10 + 182) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 18 | 24 | 20 | 16 | 26 |
| **Mod** | +7 | +4 | +7 | +5 | +3 | +8 |

**Speed:** 40 ft., climb 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 13
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Str +14, Con +14, Cha +15
**Skills:** Arcana +12, Deception +15, Intimidation +15, Persuasion +15
**Damage Resistances:** acid; cold; fire; lightning; thunder
**Damage Immunities:** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Entropic Aura.** Each creature that is not a construct or undead that ends its turn within 15 feet of Ygorl takes 14 (4d6) necrotic damage.

**Legendary Resistance (3/Day).** If Ygorl fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Ygorl has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Ygorl makes three attacks: two with its scythe, and one with its Entropic Touch.

**Scythe.** Melee Weapon Attack: +14 to hit, reach 10 ft., one creature. *Hit:* 18 (2d10 + 7) slashing damage plus 19 (3d12) necrotic damage. Any creature reduced to 0 hit points by this attack dies, with its body and everything it is wearing and carrying, except magic items, exploding into a cloud of ash. The creature can be restored to life only by means of a wish spell.

**Entropic Touch.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 16 (2d8 + 7) necrotic damage, and the target must succeed on a DC 22 Constitution saving throw or gain one level of exhaustion.

**Summon Slaadi (1/Day).** Ygorl summons 1d4 + 1 [[Death Slaad|death slaadi]]. A summoned slaad appears in an unoccupied space within 60 feet of Ygorl, acts as an ally of Ygorl, and can't summon other slaadi. It remains for 1 minute, until it or Ygorl dies, or until Ygorl dismisses it as an action.

**Teleport.** Ygorl teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.


---

### Legendary Actions

### 

**Scythe.** Ygorl makes one attack with its scythe.

**Teleport.** Ygorl uses its Teleport action.

**Call the Void (Costs 3 Actions).** Each creature that is not a construct or undead within 30 feet of Ygorl must make a DC 22 Constitution saving throw against the lord of entropy's attempt to unmake life, taking 42 (12d6) necrotic damage on a failed save, or half as much damage on a successful one. Ygorl then regains a number of hit points equal to half the total damage taken by all affected creatures.


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