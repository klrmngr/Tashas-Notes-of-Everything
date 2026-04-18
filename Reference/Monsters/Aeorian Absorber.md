---
type: pc
race: "Monstrosity"
class:
 - "Aeorian Absorber"
subClass:
 - "CR 10"
cover: "Aeorian Absorber.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/10
  - source/egw
---
###### Aeorian Absorber
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Aeorian Absorber.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 171 (18d10 + 72) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 18 | 18 | 6 | 14 | 8 |
| **Mod** | +5 | +4 | +4 | -2 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** understands Draconic but can't speak
**Saving Throws:** Wis +6, Cha +3
**Skills:** Perception +6, Stealth +8, Survival +6
**Damage Immunities:** necrotic; radiant

---

### Traits

**Magic Resistance.** The absorber has advantage on saving throws against spells and other magical effects.

**Pounce.** If the absorber moves at least 20 feet straight toward a creature and then hits its claws attack on the same turn, that target must succeed on a DC 17 Strength saving throw or be knocked prone. If the target is prone, the absorber can make one bite attack against it as a bonus action.


---

### Actions

**Multiattack.** The absorber makes three attacks: one with its bite or Mind Bolt and two with its claws.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. *Hit:* 10 (1d10 + 5) piercing damage plus 5 (1d10) force damage.

**Claws.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage plus 3 (1d6) force damage.

**Mind Bolt.** Ranged Spell Attack: +8 to hit, range 120 ft., one creature. *Hit:* 22 (4d10) psychic damage.


---

### Reactions

**Tail Ray.** When the absorber takes damage from a spell, the absorber takes only half the triggering damage. If the spellcaster is within 60 feet of the absorber, the absorber can force the caster to make a DC 16 Dexterity saving throw. Unless the save succeeds, the caster takes the other half of the damage.


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