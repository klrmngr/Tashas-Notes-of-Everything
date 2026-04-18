---
type: pc
race: "Fiend (demon)"
class:
 - "Demogorgon"
subClass:
 - "CR 26"
cover: "Demogorgon.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/26
  - source/mpmm
---
###### Demogorgon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Demogorgon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 464 (32d12 + 256) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 26 | 20 | 17 | 25 |
| **Mod** | +9 | +2 | +8 | +5 | +3 | +7 |

**Speed:** 50 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 29
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +10, Con +16, Wis +11, Cha +15
**Skills:** Insight +11, Perception +19
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Demogorgon fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Demogorgon has advantage on saving throws against spells and other magical effects.

**Two Heads.** Demogorgon has advantage on saving throws against being blinded, deafened, stunned, or knocked unconscious.


---

### Actions

**Multiattack.** Demogorgon makes two Tentacle attacks. He can replace one attack with a use of Gaze.

**Tentacle.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 28 (3d12 + 9) force damage. If the target is a creature, it must succeed on a DC 23 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

**Gaze.** Demogorgon turns his magical gaze toward one creature he can see within 120 feet of him. The target must succeed on a DC 23 Wisdom saving throw or suffer one of the following effects (choose one or roll a d6):
- **1–2: Beguiling Gaze.** The target is stunned until the start of Demogorgon's next turn or until Demogorgon is no longer within line of sight.
- **3–4: Confusing Gaze.** The target suffers the effect of the confusion spell without making a saving throw. The effect lasts until the start of Demogorgon's next turn. Demogorgon doesn't need to concentrate on the spell.
- **5–6: Hypnotic Gaze.** The target is charmed by Demogorgon until the start of Demogorgon's next turn. Demogorgon chooses how the charmed target uses its action, reaction, and movement.


---

### Legendary Actions

### 

**Gaze.** Demogorgon uses Gaze and must use either Beguiling Gaze or Confusing Gaze.

**Tail.** Melee Weapon Attack: +17 to hit, reach 15 ft., one target. *Hit:* 20 (2d10 + 9) bludgeoning damage plus 11 (2d10) necrotic damage.

**Cast a Spell (Costs 2 Actions).** Demogorgon uses Spellcasting.


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