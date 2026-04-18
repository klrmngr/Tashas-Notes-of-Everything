---
type: pc
race: "Humanoid (human, shapechanger)"
class:
 - "Wereraven"
subClass:
 - "CR 2"
cover: "Wereraven.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/vrgr
---
###### Wereraven
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Wereraven.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Humanoid (human, shapechanger) |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 11 | 13 | 15 | 14 |
| **Mod** | +0 | +2 | +0 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common (can't speak in raven form)
**Skills:** Insight +4, Perception +6

---

### Traits

**Shapechanger.** The wereraven can use its action to polymorph into a raven-humanoid hybrid or into a raven, or back into its human form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its human form if it dies.

**Mimicry.** The wereraven can mimic simple sounds it has heard, such as a person whispering, a baby crying, or an animal chittering. A creature that hears the sounds can tell they are imitations with a successful DC 10 Wisdom (Insight) check.

**Regeneration.** The wereraven regains 10 hit points at the start of its turn. If the wereraven takes damage from a silvered weapon or a spell, this trait doesn't function at the start of the wereraven's next turn. The wereraven dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack (Human or Hybrid Form Only).** The wereraven makes two weapon attacks, one of which can be with its hand crossbow.

**Beak (Raven or Hybrid Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage in raven form, or 4 (1d4 + 2) piercing damage in hybrid form. If the target is humanoid, it must succeed on a DC 10 Constitution saving throw or be cursed with wereraven lycanthropy.

**Shortsword (Human or Hybrid Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Hand Crossbow (Human or Hybrid Form Only).** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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