---
type: pc
race: "Fiend (demon)"
class:
 - "Juiblex"
subClass:
 - "CR 23"
cover: "Juiblex.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/23
  - source/mtf
---
###### Juiblex
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Juiblex.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 350 (28d12 + 168) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 10 | 23 | 20 | 20 | 16 |
| **Mod** | +7 | +0 | +6 | +5 | +5 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +7, Con +13, Wis +12
**Skills:** Perception +12
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned; unconscious

---

### Traits

**Foul.** Any creature, other than an ooze, that starts its turn within 10 feet of Juiblex must succeed on a DC 21 Constitution saving throw or be poisoned until the start of the creature's next turn.

**Legendary Resistance (3/Day).** If Juiblex fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Juiblex has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Juiblex's weapon attacks are magical.

**Regeneration.** Juiblex regains 20 hit points at the start of its turn. If it takes fire or radiant damage, this trait doesn't function at the start of its next turn. Juiblex dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Spider Climb.** Juiblex can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** Juiblex makes three acid lash attacks.

**Acid Lash.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 21 (4d6 + 7) acid damage. Any creature killed by this attack is drawn into Juiblex's body, and the corpse is obliterated after 1 minute.

**Eject Slime (Recharge 5–6).** Juiblex spews out a corrosive slime, targeting one creature that it can see within 60 feet of it. The target must make a DC 21 Dexterity saving throw. On a failure, the target takes 55 (10d10) acid damage. Unless the target avoids taking any of this damage, any metal armor worn by the target takes a permanent −1 penalty to the AC it offers, and any metal weapon it is carrying or wearing takes a permanent −1 penalty to damage rolls. The penalty worsens each time a target is subjected to this effect. If the penalty on an object drops to −5, the object is destroyed.


---

### Legendary Actions

### 

**Acid Splash.** Juiblex casts acid splash.

**Attack.** Juiblex makes one acid lash attack.

**Corrupting Touch (Costs 2 Actions).** Melee Weapon Attack: +14 to hit, reach 10 ft., one creature. *Hit:* 21 (4d6 + 7) poison damage, and the target is slimed. Until the slime is scraped off with an action, the target is poisoned, and any creature, other than an ooze, is poisoned while within 10 feet of the target.


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