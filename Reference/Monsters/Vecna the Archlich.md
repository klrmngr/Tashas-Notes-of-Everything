---
type: pc
race: "Undead (wizard)"
class:
 - "Vecna the Archlich"
subClass:
 - "CR 26"
cover: "Vecna the Archlich.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/26
  - source/vd
---
###### Vecna the Archlich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VD
___

> [!infobox|no-t right]
> ![[Vecna the Archlich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Medium Undead (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 272 (32d8 + 128) |
> | :FasUserGroup: Race | Undead (wizard) |
> | :FasBook: Source | VD |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 18 | 22 | 24 | 16 |
| **Mod** | +2 | +3 | +4 | +6 | +7 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 25
**Languages:** Common, Draconic, Elvish, Infernal
**Saving Throws:** Con +12, Int +14, Wis +15
**Skills:** Arcana +22, History +14, Insight +15, Perception +15
**Damage Resistances:** cold; lightning; necrotic
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Legendary Resistance (5/Day).** If Vecna fails a saving throw, he can choose to succeed instead.

**Special Equipment.** Vecna carries a magic dagger named Afterthought. In the hands of anyone other than Vecna, Afterthought is a +2 dagger.

**Undying.** If Vecna is slain, his soul refuses to accept its fate and lives on as a disembodied spirit that fashions a new body for itself after 1d100 years. Vecna's soul can fashion a new body even if its old body was burned to ash or otherwise obliterated. When the new body is complete, Vecna regains all his hit points and becomes active again. Vecna's new body appears anywhere within 100 miles of where Vecna was slain.

**Unusual Nature.** Vecna doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** Vecna uses Flight of the Damned (if available), Rotten Fate, or Spellcasting. He then makes two attacks with *Afterthought*.

**Afterthought.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage, plus 9 (2d8) necrotic damage. If the target is a creature, it is afflicted by entropic magic, taking 9 (2d8) necrotic damage at the start of each of its turns. Immediately after taking this damage on its turn, the target can make a DC 20 Constitution saving throw, ending the effect on itself on a success. Until it succeeds on this save, the afflicted target can't regain hit points.

**Flight of the Damned (Recharge 5–6).** Vecna conjures a torrent of flying, spectral entities that fill a 120-foot cone and pass through all creatures in that area before dissipating. Each creature in that area must make a DC 22 Constitution saving throw. On a failed save, the creature takes 36 (8d8) necrotic damage and is frightened of Vecna for 1 minute. On a successful save, the creature takes half as much damage and isn't frightened. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Rotten Fate.** Vecna causes necrotic magic to engulf one creature he can see within 120 feet of himself. The target must make a DC 22 Constitution saving throw, taking 96 (8d8 + 60) necrotic damage on a failed save, or half as much damage on a successful one. A Humanoid killed by this magic rises as a zombie at the start of Vecna's next turn and acts immediately after Vecna in the initiative order. The zombie is under Vecna's control.


---

### Bonus Actions

**Vile Teleport.** Vecna teleports, along with any equipment he is wearing or carrying, up to 30 feet to an unoccupied space he can see. He can cause each creature of his choice within 15 feet of his destination space to take 10 (3d6) psychic damage. If at least one creature takes this damage, Vecna regains 80 hit points.


---

### Reactions

**Dread Counterspell.** Vecna utters a dread word to interrupt a creature he can see that is casting a spell. If the spell is 4th level or lower, it fails and has no effect. If the spell is 5th level or higher, Vecna makes an Intelligence check (DC 10 + the spell's level). On a success, the spell fails and has no effect. Whatever the spell's level, the caster takes 10 (3d6) psychic damage if the spell fails.

**Fell Rebuke.** In response to being hit by an attack, Vecna utters a fell word, dealing 10 (3d6) necrotic damage to the attacker, and Vecna teleports, along with any equipment he is wearing or carrying, up to 30 feet to an unoccupied space he can see.


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