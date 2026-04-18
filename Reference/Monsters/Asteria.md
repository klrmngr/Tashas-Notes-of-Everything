---
type: pc
race: "Humanoid (human, paladin)"
class:
 - "Asteria"
subClass:
 - "CR 18"
cover: "Asteria.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/18
  - source/bmt
---
###### Asteria
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Asteria.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, paladin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 18 (breastplate, shield) |
> | :FasHeart: HP | 195 (26d8 + 78) |
> | :FasUserGroup: Race | Humanoid (human, paladin) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 21 | 17 | 15 | 11 | 20 |
| **Mod** | +1 | +5 | +3 | +2 | +0 | +5 |

**Speed:** 30 ft., fly 30 ft. ((winged boots)) &nbsp;|&nbsp; **Senses:** passive Perception 22
**Languages:** Common, Druidic
**Saving Throws:** Dex +11, Con +9, Wis +6, Cha +11
**Skills:** Acrobatics +11, Arcana +14, Investigation +8, Perception +12, Persuasion +11, Survival +6
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Guardian Aura.** Whenever a creature of Asteria's choice within 30 feet of her makes a saving throw, Asteria can give the creature advantage on the saving throw (no action required). This trait doesn't function if Asteria has the incapacitated condition.

**Legendary Resistance (3/Day).** If Asteria fails a saving throw, she can choose to succeed instead.

**Special Equipment.** Asteria wears Winged Boots, which grant her a flying speed (included in her statistics). She also carries one half of a pair of Sending Stones; the other half of the pair is held by Euryale.


---

### Actions

**Multiattack.** Asteria makes two Radiant Blade attacks and uses Bursting Benediction.

**Radiant Blade.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage plus 13 (3d8) radiant damage.

**Bursting Benediction.** Asteria causes a burst of magical energy to envelop one creature she can see within 60 feet of herself. The target must make a DC 19 Dexterity saving throw, taking 40 (9d8) force damage on a failed save, or half as much damage on a successful one. Asteria or another creature that she can see within 60 feet of herself then regains 10 hit points.


---

### Bonus Actions

**Empowering Aegis (Recharge 4–6).** Asteria summons a spectral version of her shield, which orbits and bolsters one creature of Asteria's choice that she can see within 60 feet of herself. The spectral shield lasts until the start of Asteria's next turn. While the shield is orbiting the creature, the creature has 3, is immune to the frightened condition, and makes weapon attack rolls with advantage.


---

### Legendary Actions

### 

**Brazen Strike.** Asteria makes one Radiant Blade attack.

**Nimble Sprint.** Asteria moves up to her speed. This movement doesn't provoke opportunity attacks.

**Cast a Spell (Costs 2 Actions).** Asteria uses Spellcasting.


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