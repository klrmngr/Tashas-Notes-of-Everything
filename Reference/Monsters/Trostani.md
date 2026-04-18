---
type: pc
race: "Fey"
class:
 - "Trostani"
subClass:
 - "CR 18"
cover: "Trostani.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/18
  - source/ggr
---
###### Trostani
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Trostani.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 252 (24d10 + 120) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 20 | 16 | 30 | 25 |
| **Mod** | +4 | +2 | +5 | +3 | +10 | +7 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 26
**Languages:** Common, Druidic, Elvish, Sylvan
**Saving Throws:** Con +11, Wis +16, Cha +13
**Skills:** Arcana +9, Insight +16, Nature +9, Perception +16, Persuasion +13
**Condition Immunities:** charmed; grappled

---

### Traits

**Legendary Resistance (3/Day).** If Trostani fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Trostani has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Trostani's weapon attacks are magical.

**Speak with Beasts and Plants.** Trostani can communicate with beasts and plants as if they shared a language.

**Tree Stride.** Once on her turn, Trostani can use 10 feet of her movement to step magically into one living tree within her reach and emerge from a second living tree within 60 feet of the first tree, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be Large or bigger.


---

### Actions

**Multiattack.** Trostani takes three actions: she uses Constrict and Touch of Order, and she casts a spell with a casting time of 1 action.

**Constrict.** Melee Weapon Attack: +11 to hit, reach 5 ft., one creature. *Hit:* 15 (3d6 + 5) bludgeoning damage, and the target is grappled (escape DC 19). Until this grapple ends, the target is restrained. Trostani can grapple no more than three targets at a time.

**Touch of Order.** Melee Spell Attack: +16 to hit, reach 5 ft., one creature. *Hit:* 23 (3d8 + 10) radiant damage, and Trostani can choose one magic item she can see in the target's possession. Unless it's an artifact, the item's magic is suppressed until the start of Trostani's next turn.

**Wrath of Mat'Selesnya (Recharge 5–6).** Trostani conjures a momentary whirl of branches and vines at a point she can see within 60 feet of her. Each creature in a 30-foot cube on that point must make a DC 24 Dexterity saving throw, taking 21 (6d6) bludgeoning damage and 21 (6d6) slashing damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Voice of Harmony.** Trostani makes one melee attack, with advantage on the attack roll.

**Voice of Life.** Trostani bestows 20 temporary hit points on another creature she can see within 120 feet of her.

**Voice of Order.** Trostani casts dispel magic.

**Chorus of the Conclave (Costs 2 Actions).** Trostani casts suggestion. This counts as one of her daily uses of the spell.

**Awaken Grove Guardians (Costs 3 Actions).** Trostani animates one or two trees she can see within 120 feet of her, causing them to uproot themselves and become awakened trees (see the Monster Manual for their stat blocks) for 1 minute or until Trostani uses a bonus action to end the effect. These trees understand Druidic and obey Trostani's spoken commands, but can't speak. If she issues no commands to them, the trees do nothing but follow her and take the Dodge action.


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