---
type: pc
race: "Aberration"
class:
 - "Zargon the Returner"
subClass:
 - "CR 17"
cover: "Zargon the Returner.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/17
  - source/qftis
---
###### Zargon the Returner
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Zargon the Returner.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 253 (22d12 + 110) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 20 | 14 | 18 | 18 |
| **Mod** | +6 | +0 | +5 | +2 | +4 | +4 |

**Speed:** 40 ft., swim 80 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +6, Cha +10
**Skills:** History +8, Perception +10
**Damage Resistances:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Legendary Resistance (4/Day).** If Zargon fails a saving throw, it can choose to succeed instead.

**Regeneration.** Zargon regains 20 hit points at the start of each of its turns. If Zargon takes cold or fire damage, this trait doesn't function at the start of Zargon's next turn. Zargon dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Shrouded Being.** Zargon can't be targeted by divination magic or perceived through magical scrying sensors.

**Slimy Demise.** When Zargon dies, its body dissolves into foul slime, leaving only its horn behind. Zargon re-forms in 1d10 days, regrowing from the horn. The horn is immune to all damage and can be destroyed only by submerging it in a cleansing waterfall on one of the Upper Planes for 101 days. While the horn is submerged in this way, Zargon doesn't re-form, and the horn slowly dissolves, sending corrupting slime downriver that permanently fouls the water for 10 miles from the place where the horn dissolved. The fouled water is unfit to drink, chokes aquatic wildlife, and withers plants.


---

### Actions

**Multiattack.** Zargon makes two Barbed Tentacle attacks, one Bite attack, and one Gore attack.

**Barbed Tentacle.** Melee Weapon Attack: +12 to hit, reach 20 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 20), and Zargon can pull the creature up to 20 feet straight toward itself. Zargon has six tentacles, each of which can grapple one creature. Zargon can move at its full speed while dragging creatures it is grappling.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 19 (2d12 + 6) piercing damage plus 7 (2d6) acid damage.

**Gore.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) force damage, and a 10-foot-radius invisible sphere of antimagic, like that created by an Antimagic Field spell, surrounds the target. The sphere is centered on the target, moves with the target, and lasts until the end of Zargon's next turn.

**Slime Wave (Recharge 5–6).** Zargon spews slime in a 60-foot cone. Each creature in that area that isn't an Aberration or Ooze must make a DC 19 Constitution saving throw. On a failed save, the creature takes 38 (7d10) acid damage and has the poisoned condition for 1 minute. On a successful save, the creature takes half as much damage only. A poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
A creature reduced to 0 hit points by the acid damage dies and dissolves into a puddle of slime that rises as a gibbering mouther at the start of Zargon's next turn. The creature obeys Zargon's commands and takes its turn immediately after Zargon's. Only a Wish spell can reverse this transformation and restore the creature to life.


---

### Reactions

**Defiant Essence.** When a creature casts a spell that targets Zargon or would deal damage to it, Zargon attempts to absorb the magic into its horn. The creature must make a DC 19 Charisma saving throw. On a failed save, the creature takes 6 (1d12) force damage, and the spell it cast fails and is wasted.

**Slime Spray.** When a creature ends its turn within 30 feet of Zargon, Zargon sprays toxic slime at the creature. The target must make a DC 19 Dexterity saving throw (with disadvantage if it has the poisoned condition). On a failed save, the creature takes 7 (2d6) poison damage. On a successful save, it takes half as much damage.


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