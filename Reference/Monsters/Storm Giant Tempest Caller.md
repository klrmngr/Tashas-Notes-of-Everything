---
type: pc
race: "Giant (sorcerer)"
class:
 - "Storm Giant Tempest Caller"
subClass:
 - "CR 20"
cover: "Storm Giant Tempest Caller.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/20
  - source/bgg
---
###### Storm Giant Tempest Caller
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Storm Giant Tempest Caller.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Huge Giant (sorcerer) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 310 (27d12 + 135) |
> | :FasUserGroup: Race | Giant (sorcerer) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 20 | 21 | 18 | 25 |
| **Mod** | +9 | +2 | +5 | +5 | +4 | +7 |

**Speed:** 50 ft., fly 50 ft. ((hover)), swim 50 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** Common, Giant, Primordial
**Saving Throws:** Str +15, Con +11, Wis +10, Cha +13
**Skills:** Arcana +17, Athletics +15, Perception +10
**Damage Resistances:** cold
**Damage Immunities:** lightning; thunder

---

### Traits

**Alert.** The giant can't be surprised, and it has advantage on initiative rolls.

**Amphibious.** The giant can breathe air and water.

**Legendary Resistance (3/Day).** If the giant fails a saving throw, it can choose to succeed instead.

**Scrying (Requires Storm Rune).** The giant can use its crystal ball to cast the scrying spell (save DC 17).

**Storm Rune.** The giant has a storm rune inscribed on a crystal ball. While the object bearing the rune is embedded in its body, the giant can use its Tempest Call action and its Scrying trait.
The object bearing the storm rune has AC 17; 50 hit points; and immunity to necrotic, poison, and psychic damage. The object regains all its hit points at the end of every turn, but it turns to dust if reduced to 0 hit points or when the giant dies. If the rune is destroyed, the giant can inscribe a storm rune on another crystal ball in its possession when it finishes a short or long rest.


---

### Actions

**Multiattack.** The giant makes three Lightning Blade or Lightning Lance attacks.

**Lightning Blade.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 22 (3d8 + 9) slashing damage plus 16 (3d10) lightning damage.

**Lightning Lance.** Ranged Spell Attack: +13 to hit, range 500 ft., one target. *Hit:* 39 (5d12 + 7) lightning damage.

**Tempest Call (Requires Storm Rune).** The giant creates an elemental vortex that fills a 60-foot-radius sphere centered on itself. Each creature in that area other than the giant must make a DC 21 Dexterity saving throw. On a failed save, a creature takes 43 (8d8 + 7) damage of a type of the giant's choosing: cold, lightning, or thunder. On a successful save, a creature takes half as much damage.


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