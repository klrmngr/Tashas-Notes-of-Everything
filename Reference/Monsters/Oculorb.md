---
type: pc
race: "Aberration"
class:
 - "Oculorb"
subClass:
 - "CR 9"
cover: "Oculorb.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/9
  - source/pabtso
---
###### Oculorb
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Oculorb.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 17 | 14 | 15 | 19 |
| **Mod** | +1 | +0 | +3 | +2 | +2 | +4 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 20
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Int +6, Wis +6, Cha +8
**Skills:** Investigation +6, Perception +10
**Condition Immunities:** blinded; prone

---

### Traits

**Magic Resistance.** The oculorb has advantage on saving throws against spells and other magical effects.

**Watchful Eyes.** The oculorb has advantage on initiative rolls and can't be surprised.


---

### Actions

**Multiattack.** The oculorb makes two Dreadful Contact attacks or four Eye Beam attacks.

**Dreadful Contact.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 14 (3d6 + 4) psychic damage, or 25 (6d6 + 4) psychic damage if the target has the frightened condition.

**Eye Beam.** Ranged Spell Attack: +8 to hit, range 120 ft., one creature. *Hit:* 14 (3d6 + 4) psychic damage.

**Antipathic Flood (Recharge 5–6).** The oculorb releases a wave of negative emotions, choosing one of the following options:

**Weeping Eyes.** The oculorb weeps, releasing a wave of crushing despair. Each creature within 30 feet of the oculorb must make a DC 16 Constitution saving throw. On a failed save, a creature's speed is reduced to 0 feet until the end of the oculorb's next turn, and if the creature was concentrating, its concentration is broken.

**Withering Glare.** The oculorb's eyes unleash furious scarlet energy in a 60-foot cone. Each creature in that area must make a DC 16 Wisdom saving throw. On a failed save, a creature takes 33 (6d10) necrotic damage and has the frightened condition for 1 minute. On a successful save, a creature takes half as much damage and isn't frightened. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a successful save.


---

### Reactions

**Obsessive Rebuke.** When the oculorb is damaged by a creature it can see within 60 feet of itself, it forces the creature to make a DC 16 Wisdom saving throw. The creature takes 10 (3d6) psychic damage on a failed save, or half as much damage on a successful one.


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