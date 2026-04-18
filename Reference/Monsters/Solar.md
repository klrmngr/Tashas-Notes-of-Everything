---
type: pc
race: "Celestial"
class:
 - "Solar"
subClass:
 - "CR 21"
cover: "Solar.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/21
  - source/mm
---
###### Solar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Solar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 243 (18d10 + 144) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 22 | 26 | 25 | 25 | 30 |
| **Mod** | +8 | +6 | +8 | +7 | +7 | +10 |

**Speed:** 50 ft., fly 150 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +14, Wis +14, Cha +17
**Skills:** Perception +14
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Angelic Weapons.** The solar's weapon attacks are magical. When the solar hits with any weapon, the weapon deals an extra 6d8 radiant damage (included in the attack).

**Divine Awareness.** The solar knows if it hears a lie.

**Magic Resistance.** The solar has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The solar makes two greatsword attacks.

**Greatsword.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 22 (4d6 + 8) slashing damage plus 27 (6d8) radiant damage.

**Slaying Longbow.** Ranged Weapon Attack: +13 to hit, range 150/600 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage plus 27 (6d8) radiant damage. If the target is a creature that has 100 hit points or fewer, it must succeed on a DC 15 Constitution saving throw or die.

**Flying Sword.** The solar releases its greatsword to hover magically in an unoccupied space within 5 feet of it. If the solar can see the sword, the solar can mentally command it as a bonus action to fly up to 50 feet and either make one attack against a target or return to the solar's hands. If the hovering sword is targeted by any effect, the solar is considered to be holding it. The hovering sword falls if the solar dies.

**Healing Touch (4/Day).** The solar touches another creature. The target magically regains 40 (8d8 + 4) hit points and is freed from any curse, disease, poison, blindness, or deafness.


---

### Legendary Actions

### 

**Teleport.** The solar magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.

**Searing Burst (Costs 2 Actions).** The solar emits magical, divine energy. Each creature of its choice in a 10-foot radius must make a DC 23 Dexterity saving throw, taking 14 (4d6) fire damage plus 14 (4d6) radiant damage on a failed save, or half as much damage on a successful one.

**Blinding Gaze (Costs 3 Actions).** The solar targets one creature it can see within 30 feet of it. If the target can see it, the target must succeed on a DC 15 Constitution saving throw or be blinded until magic such as the lesser restoration spell removes the blindness.


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