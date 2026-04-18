---
type: pc
race: "Humanoid (drow, elf, wizard)"
class:
 - "Galsariad Ardyth (Tier 3)"
subClass:
 - "CR 8"
cover: "Galsariad Ardyth (Tier 3).png"
campaign:
locations:
tags:
  - race/drow
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/crcotn
---
###### Galsariad Ardyth (Tier 3)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Galsariad Ardyth (Tier 3).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (drow, elf, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (deflection) |
> | :FasHeart: HP | 90 (20d8) |
> | :FasUserGroup: Race | Humanoid (drow, elf, wizard) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 20 | 15 | 12 |
| **Mod** | -1 | +2 | +0 | +5 | +2 | +1 |

**Speed:** 30 ft., fly 30 ft. ((hover)), swim 40 ft. ((ring of swimming)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Common, Draconic, Undercommon
**Saving Throws:** Int +8, Wis +5
**Skills:** Arcana +8, Investigation +8, Nature +8

---

### Traits

**Deflection.** Galsariad warps gravity around himself to magically deflect incoming attacks. While Galsariad is wearing no armor and not incapacitated, his AC includes his Intelligence modifier.

**Fey Ancestry.** Galsariad has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Special Equipment.** Galsariad wears a ring of swimming and carries a ruidium dagger (see appendix B). If he rolls a 1 on an attack roll made with the dagger, he must succeed on a DC 20 Charisma saving throw or gain 1 level of exhaustion.


---

### Actions

**Multiattack.** Galsariad makes one Drain Potential attack and one Ruidium Dagger attack.

**Drain Potential.** Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 120 ft., one creature. *Hit:* 22 (4d10) necrotic damage, and Galsariad gains 10 temporary hit points.

**Ruidium Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 7 (2d6) psychic damage.

**Gravity Wave (Recharge 5–6).** Galsariad causes a rippling wave of magical gravity to fill a 30-foot-radius sphere centered on a point he can see within 100 feet of himself. Each creature in that area must make a DC 16 Strength saving throw. On a failed saving throw, the creature takes 42 (12d6) force damage and is restrained for 1 minute. On a successful save, the creature takes half as much damage and isn't restrained. A restrained creature can repeat the save at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Distort Gravity (1/Day).** Galsariad targets himself or one willing creature that he can see within 60 feet of himself, magically distorting gravity around the target. Any creature within 5 feet of the target takes 14 (4d6) force damage. In addition, the target can use a reaction to float upward, up to 20 feet, without provoking opportunity attacks. When this effect ends at the start of Galsariad's next turn, the target floats gently down up to 20 feet.


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