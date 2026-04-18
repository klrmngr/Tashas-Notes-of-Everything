---
type: pc
race: "Giant (wizard)"
class:
 - "Death Giant Shrouded One"
subClass:
 - "CR 15"
cover: "Death Giant Shrouded One.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/15
  - source/bgg
---
###### Death Giant Shrouded One
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Death Giant Shrouded One.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Giant (wizard) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 195 (17d12 + 85) |
> | :FasUserGroup: Race | Giant (wizard) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 20 | 23 | 16 | 16 |
| **Mod** | +8 | +2 | +5 | +6 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Common, Giant
**Saving Throws:** Con +10, Int +11, Wis +8, Cha +8
**Skills:** Arcana +11, Perception +8, Stealth +7
**Damage Immunities:** necrotic
**Condition Immunities:** frightened

---

### Traits

**Death Rune.** The giant has a death rune inscribed on a giant's skull in its possession. While holding or wearing the skull bearing the rune, the giant can use its Reaping Scythe action and Shroud of Souls bonus action.
The skull bearing the death rune has AC 18; 35 hit points; and immunity to necrotic, poison, and psychic damage. The skull regains all its hit points at the end of every turn, but it turns to dust if reduced to 0 hit points or when the giant dies. If the rune is destroyed, the giant can inscribe a death rune on another skull in its possession when it finishes a short or long rest.


---

### Actions

**Multiattack.** The giant makes three Soul Burst attacks. Alternatively, if the giant has its death rune, it can make three Reaping Scythe attacks.

**Soul Burst.** Melee or Ranged Spell Attack: +11 to hit, reach 10 ft. or range 120 ft., one target. *Hit:* 28 (4d10 + 6) necrotic damage. If the target has the frightened condition, the giant gains temporary hit points equal to the damage dealt.

**Reaping Scythe (Requires Death Rune).** Melee Spell Attack: +11 to hit, reach 15 ft., one creature. *Hit:* 38 (7d10) necrotic damage, and the target can't regain hit points until the end of its next turn. The target dies if it is reduced to 0 hit points by this attack.


---

### Bonus Actions

**Frightening Teleport (Recharge 4–6).** The giant magically teleports, along with any equipment it is wearing or carrying, up to 40 feet to an unoccupied space it can see. Each creature within 10 feet of the location the giant left must succeed on a DC 19 Wisdom saving throw or have the frightened condition until the end of that creature's next turn.

**Shroud of Souls (Requires Death Rune).** The giant shrouds itself in a torrent of souls. While the giant is shrouded, each creature that starts its turn within 5 feet of the giant must succeed on a DC 19 Wisdom saving throw or have disadvantage on saving throws until the end of that creature's next turn. The shroud disappears after 1 minute, when the giant dies, when the giant uses this bonus action again, or when the giant's death rune is destroyed.


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