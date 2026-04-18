---
type: pc
race: "Celestial"
class:
 - "Aurumach Rilmani"
subClass:
 - "CR 17"
cover: "Aurumach Rilmani.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/17
  - source/mpp
---
###### Aurumach Rilmani
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Aurumach Rilmani.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 285 (30d10 + 120) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 21 | 18 | 21 | 18 | 16 |
| **Mod** | +5 | +5 | +4 | +5 | +4 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +11, Int +11
**Skills:** Arcana +11, History +11, Perception +10
**Damage Resistances:** psychic; bludgeoning, piercing, slashing from nonmagical attacks

---

### Actions

**Multiattack.** The aurumach makes three Manifested Blade or Gleaming Ray attacks.

**Manifested Blade.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 23 (4d8 + 5) force damage.

**Gleaming Ray.** Ranged Spell Attack: +11 to hit, range 120 ft., one target. *Hit:* 24 (3d12 + 5) force damage.


---

### Bonus Actions

**Aura of Blades.** The aurumach manifests a spectral, golden aura of blades around itself. While this aura is manifested, each creature that starts its turn within 10 feet of the aurumach must make a DC 19 Dexterity saving throw, taking 16 (3d10) force damage on a failed save, or half as much damage on a successful one. The aura disappears after 1 minute, when the aurumach has the incapacitated condition or dies, or when the aurumach uses a bonus action to end it.

**Invoke Weakness (Recharge 5–6).** The aurumach attempts to use its magic to weaken the defenses of a creature it can see within 120 feet of itself. The target must succeed on a DC 19 Wisdom saving throw or become cursed until the end of the aurumach's next turn. The next time the aurumach hits the cursed target with a Manifested Blade or Gleaming Ray attack, the target takes an extra 27 (6d8) force damage.


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