---
type: pc
race: "Humanoid (shapechanger)"
class:
 - "Deep Scion"
subClass:
 - "CR 3"
cover: "Deep Scion.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/vgm
---
###### Deep Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Deep Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid (shapechanger) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 10 | 12 | 14 |
| **Mod** | +4 | +1 | +3 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Aquan, Common, Thieves' cant
**Saving Throws:** Wis +3, Cha +4
**Skills:** Deception +6, Insight +3, Sleight Of Hand +3, Stealth +3

---

### Traits

**Shapechanger.** The deep scion can use its action to polymorph into a humanoid-piscine hybrid form, or back into its true form. Its statistics, other than its speed, are the same in each form. Any equipment it is wearing or carrying isn't transformed. The deep scion reverts to its true form if it dies.

**Amphibious (Hybrid Form Only).** The deep scion can breathe air and water.


---

### Actions

**Multiattack.** In humanoid form, the deep scion makes two melee attacks. In hybrid form, the deep scion makes three attacks: one with its bite and two with its claws.

**Battleaxe (Humanoid Form Only).** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.

**Bite (Hybrid Form Only).** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 6 (1d4 + 4) piercing damage.

**Claw (Hybrid Form Only).** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Psychic Screech (Hybrid Form Only; Recharges after a Short or Long Rest).** The deep scion emits a terrible scream audible within 300 feet. Creatures within 30 feet of the deep scion must succeed on a DC 13 Wisdom saving throw or be stunned until the end of the deep scion's next turn. In water, the psychic screech also telepathically transmits the deep scion's memories of the last 24 hours to its master, regardless of distance, so long as it and its master are in the same body of water.


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