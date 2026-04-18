---
type: pc
race: "Elemental (wizard)"
class:
 - "Charmayne Daymore"
subClass:
 - "CR 10"
cover: "Charmayne Daymore.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/10
  - source/kftgv
---
###### Charmayne Daymore
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Charmayne Daymore.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Elemental (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 123 (19d8 + 38) |
> | :FasUserGroup: Race | Elemental (wizard) |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 15 | 20 | 14 | 16 |
| **Mod** | -1 | +2 | +2 | +5 | +2 | +3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Draconic, Elvish, Ignan
**Saving Throws:** Int +9, Wis +6, Cha +7
**Skills:** Arcana +9, Deception +7, Perception +6
**Damage Immunities:** fire

---

### Traits

**Legendary Resistance (3/Day).** If Charmayne fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** Charmayne makes three Ashen Burst attacks. She can replace one of these attacks with one use of Spellcasting.

**Ashen Burst.** Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 17 (5d6) fire damage.

**Cinder Spite (Recharge 5–6).** Charmayne creates a magical explosion of fire centered on a point she can see within 120 feet of herself. Each creature in a 20-foot-radius sphere centered on that point must make a DC 17 Dexterity saving throw, taking 35 (10d6) fire damage on a failed save, or half as much damage on a successful one. A Humanoid reduced to 0 hit points by this damage dies and is transformed into a Tiny charcoal figurine.


---

### Reactions

**Elemental Rebuke.** In response to being hit by an attack, Charmayne utters a word in Ignan, dealing 10 (3d6) fire damage to the attacker. Charmayne then teleports, along with any equipment she is wearing or carrying, up to 30 feet to an unoccupied space she can see, leaving a harmless cloud of ash and embers in the space she just left.

**Fiery Counterspell.** Charmayne interrupts a creature she can see within 60 feet of herself that is casting a spell. If the spell is 4th level or lower, it fails and has no effect. If the spell is 5th level or higher, Charmayne makes an Intelligence check (DC 10 + the spell's level). On a success, the spell fails and has no effect. Whatever the spell's level, the caster takes 10 (3d6) fire damage if the spell fails.


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