---
type: pc
race: "Fiend"
class:
 - "Daemogoth"
subClass:
 - "CR 10"
cover: "Daemogoth.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/10
  - source/scc
---
###### Daemogoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Daemogoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Fiend |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 157 (15d12 + 60) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 19 | 21 | 14 | 18 |
| **Mod** | +4 | +2 | +4 | +5 | +2 | +4 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 16
**Languages:** Abyssal, Infernal, telepathy 120 ft.
**Saving Throws:** Int +9, Wis +6, Cha +8
**Skills:** Arcana +13, Deception +12, History +9, Perception +6
**Damage Immunities:** psychic
**Condition Immunities:** frightened

---

### Traits

**Pact of Pain.** Using a 10-minute ritual, the daemogoth can forge a magical bond with a willing creature it touches throughout the ritual. The creature becomes bound by the pact until it dies, the daemogoth dies, or the pact is broken by any effect that can remove a curse.
The daemogoth chooses one spell from the level=0;1;2;3. The bound creature can cast that spell using this pact, requiring no material components and using Intelligence as the spellcasting ability. When it casts the spell, the creature takes 7 (2d6) psychic damage, which can't break the creature's concentration on a spell. Once the bound creature casts the spell in this way, it can't do so again until it finishes a long rest.


---

### Actions

**Multiattack.** The daemogoth makes three Agonizing Burst attacks. It can use Terrify, if available, in place of one of the attacks.

**Agonizing Burst.** Melee or Ranged Spell Attack: +9 to hit, reach 10 ft. or range 120 ft., one target. *Hit:* 11 (2d10) force damage. If the target is a creature, the daemogoth regains 5 hit points.

**Terrify (Recharge 4–6).** The daemogoth targets one creature it can see within 120 feet of itself. The target must make a DC 17 Wisdom saving throw. On a failed save, the target takes 33 (6d10) psychic damage and is frightened of the daemogoth until the end of the daemogoth's next turn, and the daemogoth regains 5 hit points. On a successful save, the target takes half as much damage and isn't frightened, and the daemogoth doesn't heal.


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