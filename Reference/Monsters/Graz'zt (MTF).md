---
type: pc
race: "Fiend (demon, shapechanger)"
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
  - source/mtf
---
###### Graz'zt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Graz'zt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon, shapechanger) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 346 (33d10 + 165) |
> | :FasUserGroup: Race | Fiend (demon, shapechanger) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 15 | 21 | 23 | 21 | 26 |
| **Mod** | +6 | +2 | +5 | +6 | +5 | +8 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +12, Wis +12
**Skills:** Deception +15, Insight +12, Perception +12, Persuasion +15
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Shapechanger.** Graz'zt can use his action to polymorph into a form that resembles a Medium humanoid, or back into his true form. Aside from his size, his statistics are the same in each form. Any equipment he is wearing or carrying isn't transformed.

**Legendary Resistance (3/Day).** If Graz'zt fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Graz'zt has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Graz'zt's weapon attacks are magical.


---

### Actions

**Multiattack.** Graz'zt attacks twice with Wave of Sorrow.

**Wave of Sorrow (Greatsword).** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 20 (4d6 + 6) slashing damage plus 10 (3d6) acid damage.

**Teleport.** Graz'zt magically teleports, along with any equipment he is wearing or carrying, up to 120 feet to an unoccupied space he can see.


---

### Legendary Actions

### 

**Attack.** Graz'zt attacks once with Wave of Sorrow.

**Dance, My Puppet.** One creature charmed by Graz'zt that Graz'zt can see must use its reaction to move up to its speed as Graz'zt directs.

**Sow Discord.** Graz'zt casts crown of madness or dissonant whispers.

**Teleport.** Graz'zt uses his Teleport action.


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