---
type: pc
race: "Fiend (demon)"
class:
 - "Pazuzu"
subClass:
 - "CR 25"
cover: "Pazuzu.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/25
  - source/mabjov
---
###### Pazuzu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Pazuzu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 405 (30d10 + 240) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 30 | 27 | 23 | 18 | 27 |
| **Mod** | +6 | +10 | +8 | +6 | +4 | +8 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +18, Con +16, Cha +16
**Skills:** Perception +12, Persuasion +16
**Damage Resistances:** acid; cold; fire
**Damage Immunities:** lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Aura of Servile Avians.** Any evil creature with a natural fly speed and a CR of 20 or less must make a DC 21 Wisdom saving throw if they attempt to attack Pazuzu. A failed save means their action is wasted and the attack fails. On a successful saving throw the target is immune to this effect in the future.

**Legendary Resistance (3/Day).** If Pazuzu fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Pazuzu has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Pazuzu's weapon attacks are magical.


---

### Actions

**Multiattack.** Pazuzu makes two Greatsword or Talon attacks.

**Greatsword.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage plus 7 (2d6) necrotic damage.

**Talon.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 15 (2d8 + 6) slashing damage plus 9 (2d8) poison damage.

**Breath Weapons (Recharge 5–6).** Pazuzu exhales poisonous acid in a 100-foot line that is 5 feet wide. Every creature hit by the acid must make a DC 21 Dexterity saving throw, taking 70 (20d6) acid damage on a failed save, or half as much damage on a successful one. A creature killed by this breath weapon melts and is disintegrated.


---

### Bonus Actions

**Dispel.** Pazuzu casts dispel magic, automatically dispelling any spell of 6th level or lower on the target.

**Hasted Greatsword.** Pazuzu uses his magic greatsword to grant him the following abilities until the start of his next turn. Pazuzu's speed is now doubled, he gains a +2 bonus to AC, has advantage on Dexterity saving throws, and gains one additional Greatsword attack.


---

### Legendary Actions

### 

**Disarm.** Pazuzu attempts to knock a weapon out of a target's hand. He makes a Greatsword attack and if it hits, the target does not take damage but instead must make a DC 22 Strength saving throw. If the target fails the saving throw, the targeted weapon flies 10 feet away in a random direction.

**Lethal Leap.** Pazuzu attacks once with his Greatsword or Talon and then may fly up to 60 feet away. Pazuzu's movement does not provoke opportunity attacks.


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