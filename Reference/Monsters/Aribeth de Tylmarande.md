---
type: pc
race: "Undead"
class:
 - "Aribeth de Tylmarande"
subClass:
 - "CR 10"
cover: "Aribeth de Tylmarande.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/mabjov
---
###### Aribeth de Tylmarande
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Aribeth de Tylmarande.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 10 | 13 | 16 |
| **Mod** | +3 | +2 | +3 | +0 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Elvish, Infernal
**Skills:** Perception +5, Religion +4
**Damage Immunities:** necrotic; bludgeoning, piercing, slashing from nonmagical weapons that aren't silvered
**Condition Immunities:** poisoned

---

### Traits

**Infernal Tracker.** Aribeth knows the distance to and direction of any creature that has broken a pact with Mephistopheles, even if the creature and Aribeth are on different planes of existence.

**Magic Resistance.** Aribeth has advantage on saving throws against spells and other magical effects.

**Nightmare.** Aribeth is accompanied by a [[Nightmare]]. The nightmare allows Aribeth to use it as a mount.

**Regeneration.** Aribeth regains 20 hit points at the start of her turn. If Aribeth takes radiant damage, this trait doesn't function at the start of Aribeth's next turn. Aribeth's body is destroyed only if she starts her turn with 0 hit points and doesn't regenerate.

**Shadows.** Three [[Shadow|shadows]] hide within the saddle of Aribeth's nightmare. These shadows only come out if there is a creature within 30 feet that is at 0 hit points. When that happens, a shadow emerges and attacks the creature in order to make it fail a death saving throw. It continues to do so until the creature is dead.

**Sunlight Sensitivity.** While in sunlight, Aribeth has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Aribeth makes three Void or Unholy Strike attacks.

**Void.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage or 8 (1d10 + 3) slashing damage if used with two hands, plus 7 (2d6) necrotic damage. A creature reduced to 0 hit points from damage dealt by the sword Void dies and can't be revived by any means short of a wish spell.

**Unholy Strike.** Ranged Spell Attack: +7 to hit, range 120 ft., one target. *Hit:* 12 (2d8 + 3) necrotic damage.


---

### Reactions

**Parry.** Aribeth adds 4 to her AC against one melee attack that would hit her. To do so, Aribeth must see the attacker and be wielding a melee weapon.


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