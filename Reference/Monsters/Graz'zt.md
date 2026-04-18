---
type: pc
race: "Fiend (demon)"
class:
 - "Graz'zt"
subClass:
 - "CR 24"
cover: "Graz'zt.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/24
  - source/mpmm
---
###### Graz'zt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Graz'zt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 346 (33d10 + 165) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 15 | 21 | 23 | 21 | 26 |
| **Mod** | +6 | +2 | +5 | +6 | +5 | +8 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +12, Wis +12
**Skills:** Deception +15, Perception +12, Persuasion +15
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Graz'zt fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Graz'zt has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Graz'zt makes two Wave of Sorrow attacks. He can replace one attack with a use of Spellcasting.

**Wave of Sorrow (Greatsword).** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 20 (4d6 + 6) force damage plus 14 (4d6) acid damage.

**Teleport.** Graz'zt teleports, along with any equipment he is wearing or carrying, up to 120 feet to an unoccupied space he can see.


---

### Bonus Actions

**Change Shape.** Graz'zt transforms into a form that resembles a Medium Humanoid or back into his true form. Aside from his size, his statistics are the same in each form. Any equipment he is wearing or carrying isn't transformed.


---

### Reactions

**Negate Spell (Recharge 5–6).** Graz'zt tries to interrupt a spell he sees a creature casting within 60 feet of him. If the spell is 3rd level or lower, the spell fails and has no effect. If the spell is 4th level or higher, Graz'zt makes a Charisma check against a DC of 10 + the spell's level. On a success, the spell fails and has no effect.


---

### Legendary Actions

### 

**Abyssal Magic.** Graz'zt uses Spellcasting or Teleport.

**Attack.** Graz'zt makes one Wave of Sorrow attack.

**Dance, My Puppet!.** One creature charmed by Graz'zt that Graz'zt can see must use its reaction to move up to its speed as Graz'zt directs.


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