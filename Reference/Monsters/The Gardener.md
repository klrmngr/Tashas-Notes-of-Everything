---
type: pc
race: "Fey (archfey, druid)"
class:
 - "The Gardener"
subClass:
 - "CR 12"
cover: "The Gardener.png"
campaign:
locations:
tags:
  - race/archfey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/12
  - source/qftis
---
###### The Gardener
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[The Gardener.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fey (archfey, druid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 209 (22d8 + 110) |
> | :FasUserGroup: Race | Fey (archfey, druid) |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 16 | 20 | 17 | 20 | 18 |
| **Mod** | +5 | +3 | +5 | +3 | +5 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Common, Druidic, Elvish, Sylvan
**Saving Throws:** Dex +7, Con +9, Wis +9, Cha +8
**Skills:** Insight +9, Nature +11, Perception +9, Survival +13
**Damage Resistances:** cold; fire
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Fey Rebirth.** If the Gardener dies in the Eternal Garden, they revive with all their hit points 1d4 days later in a safe location within the garden.

**Legendary Resistance (3/Day).** If the Gardener fails a saving throw, they can choose to succeed instead.

**Unfettered Steps.** The Gardener is unaffected by difficult terrain.


---

### Actions

**Multiattack.** The Gardener makes two Vine attacks and can use Breath of Tranquility if available.

**Vine.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 11 (1d12 + 5) bludgeoning damage plus 9 (2d8) psychic damage, and if the target is a Large or smaller creature, the vine wraps around the target, and the target has the grappled condition (escape DC 17). The vine vanishes when the target is no longer grappled, or when the Gardener wills it to (no action required). A creature reduced to 0 hit points by the vine has the unconscious condition but is stable instead of dying.

**Breath of Tranquility (Recharge 5–6).** The Gardener exhales soporific vapor in a 30-foot cone. Each creature in that area must succeed on a DC 17 Constitution saving throw or have the poisoned condition. A poisoned creature must repeat the saving throw at the end of its next turn. On a failed save, it has the unconscious condition, and on a successful save, the effect ends on it. An unconscious creature is no longer poisoned and remains unconscious for 1 hour, until it takes damage, or until a creature uses an action to shake it awake.


---

### Reactions

**Pacification.** When a creature within 120 feet of the Gardener damages the Gardener, that creature takes 10 (3d6) psychic damage, and the Gardener teleports, along with anything they are wearing or carrying, to an unoccupied space they can see within 15 feet. A creature reduced to 0 hit points by the psychic damage has the unconscious condition and is stable instead of dying.

**Spell Refuge.** When the Gardener or a creature within 30 feet of the Gardener takes damage from a spell, the Gardener chooses up to 5 creatures within 30 feet of themself. The Gardener and the chosen creatures have resistance to all damage from the triggering spell.


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