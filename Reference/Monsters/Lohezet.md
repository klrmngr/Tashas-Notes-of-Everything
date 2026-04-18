---
type: pc
race: "Humanoid (human, wizard)"
class:
 - "Lohezet"
subClass:
 - "CR 12"
cover: "Lohezet.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/dsotdq
---
###### Lohezet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Lohezet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 137 (25d8 + 25) |
> | :FasUserGroup: Race | Humanoid (human, wizard) |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 12 | 20 | 14 | 11 |
| **Mod** | -1 | +2 | +1 | +5 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Dwarvish, Elvish, Infernal
**Saving Throws:** Con +5, Wis +6
**Skills:** Arcana +9, History +9, Medicine +6
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Toxic Mastery.** Lohezet ignores a creature's resistance to poison damage.


---

### Actions

**Multiattack.** Lohezet makes three Withering Blast attacks and uses Miasma if it's available. He can replace one of the attacks with a use of Spellcasting.

**Withering Blast.** Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 18 (2d12 + 5) necrotic damage.

**Miasma (Recharge 4–6).** Lohezet magically conjures a billowing cloud of purple fog in a 20-foot-radius sphere centered on a point within 120 feet of himself. The area within the sphere is heavily obscured, and when a creature starts its turn in the sphere or enters the sphere for the first time on a turn, it must make a DC 17 Constitution saving throw. On a failed save, the creature takes 39 (6d12) poison damage and is poisoned until the start of its next turn. On a successful save, the creature takes half as much damage and isn't poisoned. The cloud lasts for 1 minute, until Lohezet ends it early (no action required), or until Lohezet uses this action again. A strong wind disperses the cloud.


---

### Reactions

**Noxious Rebuke (3/Day).** When a creature within 60 feet of Lohezet damages him, Lohezet magically retaliates with a spray of foul, purple mist. The creature must make a DC 17 Constitution saving throw, taking 16 (2d10 + 5) poison damage on a failed save, or half as much damage on a successful one.


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