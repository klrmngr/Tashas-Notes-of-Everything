---
type: pc
race: "Fiend"
class:
 - "Relentless Impaler"
subClass:
 - "CR 15"
cover: "Relentless Impaler.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/15
  - source/veor
---
###### Relentless Impaler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Relentless Impaler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 184 (16d10 + 96) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 22 | 12 | 15 | 18 |
| **Mod** | +6 | +3 | +6 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** understands all languages but can't speak
**Saving Throws:** Str +11, Dex +8, Cha +9
**Skills:** Athletics +11, Perception +7, Survival +7
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Bloodheart Stake.** The impaler is magically bound to the ceremonial stake and the sacrificed corpse the ritual caster used to create it. If the impaler is reduced to 0 hit points, it disappears, then re-forms 1d8 hours later in the nearest unoccupied space to the stake and regains all its hit points. The impaler dies only if it is reduced to 0 hit points while either the ceremonial stake is removed from the sacrifice's corpse or the impaler is on a different plane of existence from that corpse.

**Legendary Resistance (3/Day).** If the impaler fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The impaler makes one Spike attack and two Wicked Spear attacks.

**Spike.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage, and the target's speed is halved until the start of the impaler's next turn.

**Wicked Spear.** Melee or Ranged Weapon Attack: +11 to hit, reach 10 ft. or range 20/40 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage plus 13 (3d8) necrotic damage.

**Spike Burst (Recharge 5–6).** Twisted, spectral spikes shoot out from the impaler's body. Each creature within 30 feet of the impaler must make a DC 19 Dexterity saving throw, taking 40 (9d8) force damage on a failed save or half as much damage on a successful one.


---

### Legendary Actions

### 

**Speed Spike.** The impaler teleports up to 30 feet to an unoccupied space it can see. It can then make a Spike attack.

**Deepen Wounds (Costs 2 Actions).** Each creature whose speed is currently reduced by the impaler's Spike attack takes 18 (4d8) necrotic damage.


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