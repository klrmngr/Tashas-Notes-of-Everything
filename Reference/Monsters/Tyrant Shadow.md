---
type: pc
race: "Aberration"
class:
 - "Tyrant Shadow"
subClass:
 - "CR 17"
cover: "Tyrant Shadow.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/17
  - source/coa
---
###### Tyrant Shadow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Tyrant Shadow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 16 | 20 | 20 | 16 | 20 |
| **Mod** | +6 | +3 | +5 | +5 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** understands all, telepathy 300 ft.
**Saving Throws:** Int +11, Wis +9
**Skills:** Arcana +11, Deception +17, Perception +9, Stealth +15
**Damage Resistances:** fire
**Damage Immunities:** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** blinded; charmed; frightened; poisoned

---

### Traits

**Empath.** The shadow uses telepathy to sense nearby creatures. The shadow can see a creature if that creature has thoughts and is within the range of the shadow's telepathy. The shadow can't see creatures immune to telepathy.

**Undying Connection.** The shadow was originally spawned from a specific devil and, if the shadow is slain, it returns to life in 10 (1d20) days within 1 mile of that devil. The shadow is killed permanently only if its progenitor devil is slain first.


---

### Actions

**Multiattack.** The shadow makes three Claw attacks. It can replace one of the attacks with Shadows of Death (if available).

**Claw.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 16 (3d6 + 6) necrotic damage, plus 7 (2d6) psychic damage.

**Cloak of Shadows.** The shadow bends darkness around itself, and now has the invisible condition for 1 minute. The invisibility ends if the shadow is subjected to a Daylight spell or similar.

**Empathic Link.** The shadow attempts to form a link between itself and a creature it can see. The target must make a DC 19 Intelligence saving throw, taking 13 (2d12) psychic damage on a success. On a failed save, the creature and the shadow are linked. While linked, every time the shadow is damaged, the creature takes half of that damage as psychic damage. The creature may repeat the saving throw at the end of each of its turns, taking 13 (2d12) psychic damage on a failed save, or ending the effect on a successful one.

**Shadows of Death (Recharge 6).** The shadow discharges inky-black shadows in a 90-foot-radius sphere around itself. Creatures in the shadows must succeed on a DC 19 Wisdom saving throw or take 27 (6d8) necrotic damage and have the frightened condition for 1 minute. A frightened creature may repeat the saving throw at the end of each of its turns, ending the effect on a successful save, but taking the damage again on a failed save.


---

### Bonus Actions

**Change Shape.** The shadow transforms into a Beast, Humanoid or Fiend that it has an Empathic Link with, or back into its true form. In a new form, the shadow retains its alignment, hit points, hit dice, telepathy, and Intelligence, Wisdom, and Charisma scores, as well as this action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features, lair actions, or legendary actions of that form.


---

### Legendary Actions

### 

**Shadow Blink.** The shadow surrounds itself in black mist, then teleports up to 60 feet to an unoccupied space that it can see.

**Shapeshift.** The shadow uses its Change Shape ability.

**Mind Spike (Costs 2 Actions).** Ranged Spell Attack: +11 to hit, range 300 ft., one target. *Hit:* 16 (2d10 + 5) psychic damage.


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