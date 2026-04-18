---
type: pc
race: "Humanoid (goliath, shapechanger)"
class:
 - "Goliath Werebear"
subClass:
 - "CR 8"
cover: "Goliath Werebear.png"
campaign:
locations:
tags:
  - race/goliath
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/idrotf
---
###### Goliath Werebear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Goliath Werebear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (goliath, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 10 in humanoid form; 12 (natural armor) in bear or hybrid form |
> | :FasHeart: HP | 161 (19d8 + 76) |
> | :FasUserGroup: Race | Humanoid (goliath, shapechanger) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 18 | 10 | 15 | 10 |
| **Mod** | +5 | +0 | +4 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common, Giant (can't speak in bear form)
**Skills:** Athletics +8, Perception +8, Survival +5
**Damage Vulnerabilities:** fire
**Damage Resistances:** cold
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered

---

### Traits

**Keen Smell.** The werebear has advantage on Wisdom (Perception) checks that rely on smell.

**Mountain Born.** The werebear is acclimated to high altitude, including elevations above 20,000 feet.

**Powerful Build (Humanoid Form Only).** The werebear counts as one size larger when determining its carrying capacity and the weight it can push, drag, or lift.

**Shapechanger.** The werebear can use its action to polymorph into a Large bear-humanoid hybrid or into a Large polar bear, or back into its goliath form. Its statistics, other than its size and AC, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.


---

### Actions

**Multiattack.** The werebear makes two melee attacks.

**Bite (Bear or Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 16 (2d10 + 5) piercing damage. If the target is a humanoid, it must succeed on a DC 15 Constitution saving throw or be cursed with werebear lycanthropy, as described in the Monster Manual.

**Claw (Bear or Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage.

**Greataxe (Humanoid or Hybrid Form Only).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (1d12 + 5) slashing damage.


---

### Reactions

**Stone's Endurance (Recharges after a Short or Long Rest).** When the werebear takes damage, it reduces the damage taken by 10 (1d12 + 4).


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