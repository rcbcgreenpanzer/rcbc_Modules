# rcbc\_Tweaks
RCBC's tweaks to various scenes.

## Changelog 4.02:
* Overall:
  * Reupload with fixed line endings
* vin\_Base:
  * nude\_draw\_cms:
    * Rework actor generation and pronouns to support a transwoman art teacher.
  * show\_npc\_porn\_cms:
    * Opened previously ciswomen only roles to transwomen.
    * Move NonCon check under the straight/lesbian decision.
  * sucked\_by\_vampire\_cms:
    * Hoist sucked test up a level so the initial branch works.
* vin\_Bestiality:
  * catch\_neighbour\_cms:
    * Change gender conditions to allow transwomen.
    * Attempt to grab an existing neighbour first, then make new ones.
    * Hardcode Actor2 some stats to make sure it doesn't hate everything.
  * gf\_suggests\_cms:
    * Swap ciswomen-only conditions to allow transwomen.
    * Make a random check easier to always succeed.
  * undercover\_cop\_cms:
    * Player.isFemale() -> !Player.isMale()

## INSTALL:
  Copy to LifePlay/Content/Modules/

## Contents:
Changes to base mods:
* vin\_Base:
  * art\_discussion\_family:
    * Family doesn't judge you for knowing less
    * If you know less they inform you about things
    * If you know more you inform them about things
  * book\_discussion\_family:
    * Family doesn't judge you for knowing less
    * If you know less they inform you about things
    * If you know more you inform them about things
  * cherry\_boy\_cms:
    * Loosen trigger conditions so that actors with existing children and/or
      partners are valid.
    * If the triggering actor has a partner add them to the scene and give
      them a parent-child relationship with the kid.
    * Expand conditions for the player's partner to take part.
    * Add option for mutual impregnation when both the player and kid are
      trans.
  * dating\_jealouscutcontacts:
    * Prevent scene from firing in an open relationship.
  * dating\_sleeping\_sex:
    * Remove restriction on same gender partners
    * Give trans characters an equal chance to be on either side.
  * job\_interview:
    * Change < into <= in initial difficulty branch
    * Adjust age presets
    * Remove penalty for having better stats than your boss.
  * music\_discussion\_family:
    * Family doesn't judge you for knowing less
    * If you know less they inform you about things
    * If you know more you inform them about things
  * neighbour\_fixes:
    * Add openRelationship() as an alternative to the stat check for your
      partner to have some fun.
  * news\_discussion\_family:
    * Family doesn't judge you for knowing less
    * If you know less they inform you about things
    * If you know more you inform them about things
  * nude\_draw\_cms:
    * Rework actor generation and pronouns to support a transwoman art teacher.
  * show\_npc\_porn\_cms:
    * Opened previously ciswomen only roles to transwomen.
    * Move NonCon check under the straight/lesbian decision.
  * sucked\_by\_vampire\_cms:
    * Hoist sucked test up a level so the initial branch works.
  * surprise\_for\_dating\_gb:
    * Loosen invitation restrictions to allow trans characters.
  * technology\_discussion\_family:
    * Family doesn't judge you for knowing less
    * If you know less they inform you about things
    * If you know more you inform them about things
* vin\_Bestiality:
  * bestiality\_cheater\_cuckold\_impregnate:
    * Replace fertility monkeying with directly calling impregnate().
  * bestiality\_cheater\_cuckold\_impregnate\_h:
    * Replace fertility monkeying with directly calling impregnate().
  * catch\_neighbour\_cms:
    * Change gender conditions to allow transwomen.
    * Attempt to grab an existing neighbour first, then make new ones.
    * Hardcode Actor2 some stats to make sure it doesn't hate everything.
  * gf\_suggests\_cms:
    * Swap ciswomen-only conditions to allow transwomen.
    * Make a random check easier to always succeed.
  * pet\_care\_cms:
    * Add openRelationship() as a shortcut around the stat check.
  * undercover\_cop\_cms:
    * Player.isFemale() -> !Player.isMale()
* vin\_Incest:
  * caught\_family\_masturbating:
    * Adapt sections of Ravenger's caught\_family\_Fertile scene, edited for
      extra non-cishet energy.
  * cms\_cuck\_dad\_impregnate:
    * Open Actor & Actor2 to be stepparents.
    * Change gender criteria to effectively Actor.canGetPregnant &
      Actor2.canImpregnate.
    * Shorten isMale() || isTrans() to just !isFemale().
  * cms\_cuck\_dad:
    * Open Actor & Actor2 to be stepparents.
    * Change gender criteria to effectively Actor.canGetPregnant &
      Actor2.canImpregnate.
    * Shorten isMale() || isTrans() to just !isFemale().
  * cms\_cuck\_dad\_passive:
    * Open Actor & Actor2 to be stepparents.
    * Change gender criteria to effectively Actor.canGetPregnant &
      Actor2.canImpregnate.
    * Shorten isMale() || isTrans() to just !isFemale().
  * cms\_ica\_sep06:
    * Add condition for the actor's age to be at most the player's
  * cms\_ica\_sep07:
    * Correct typos so that the actor's stats are used/adjusted.
  * cms\_ica\_sep08:
    * Correct typos so that the actor's stats are used/adjusted.
  * creepy\_relative\_visited:
    * Replace condition that we haven't had sex with that their age must be at
      least the player's.
  * creepy\_relative\_visits:
    * Replace condition that we haven't had sex with that their age must be at
      least the player's.
  * creepy\_relative\_watches:
    * Replace condition that we haven't had sex with that their age must be at
      least the player's.
  * drunk\_dad\_cms:
    * Swap isInterestedIn() from Player to Dad
    * Add check that Dad is interested in women to make sure the dialogue works
    * Changed the random target from a flat value to Dad's intoxication.
  * family\_harem\_cms:
    * Replace player.isMale() with !Player.isFemale()
  * family\_peep:
    * Bypass stat check if you've already had sex.
  * family\_sit\_on\_lap:
    * Open criteria for Actor from child/stepchild to any relative whose age
      is at most the player's.
    * Replace player.isMale() with !Player.isFemale()
    * Add more stats to the stat check.
  * family\_threesome:
    * Remove same gender restriction.
  * friend\_confides:
    * Open criteria from siblings/cousins to any relative.
  * friend\_confides\_shy:
    * Open criteria from siblings/cousins to any relative.
  * help\_family\_practice:
    * Replace !Player.isDating() with (!Player.isDating || openRelationship())
  * incest\_breakup\_dating:
    * Trigger based on the difference of the actors' incest stats.
  * incest\_cherry\_boy\_cms:
    * Replace gender checks to allow trans characters in either role.
  * siblings\_gangbang\_cms:
    * Replace gender checks to allow trans characters in either role.
    * Replace "brother" with "sibling"
  * siblings\_gangbang\_fantasize\_cms:
    * Replace gender checks to allow trans characters in either role.
    * Replace "brother" with "sibling"
  * siblings\_gangbang\_rape\_cms:
    * Replace gender checks to allow trans characters in either role.
    * Replace "brother" with "sibling"
  * family\_sit\_on\_lap:
    * Open criteria for Actor from parent/stepparent to any relative whose age
      is at least the player's.
    * Replace player.isMale() with !Player.isFemale()
    * Add more stats to the stat check.
* vin\_Netori:
  * owned\_netori\_cms:
    * Replace isFemale() criteria with !isMale()
    * Prevent event from firing if Cuck is dating the player.
    * Replace Player.isMale() with !Player.isFemale()
* vin\_NTR:
  * boss\_asks\_impregnate\_cms:
    * Add check that the boss can impregnate and dating can be impregnated.
    * Adjust logic so that the boss still asks to impregnate your partner if
      you've previously agreed to share.
  * dating\_cheating\_family\_cms:
    * Add logic for open relationship using relative\_asks\_cms
  * dating\_cheating\_family\_shower\_cms:
    * Add logic for open relationship using relative\_asks\_cms
  * dating\_visits\_office\_cms:
    * Split player and dating logic trees so that both can fire
    * Add logic for open relationship using boss\_asks\_cms
  * owned\_ntr\_cms:
    * Replace isFemale() criteria with !isMale()
    * Replace Player.isMale() with !Player.isFemale()
* vin\_Polyamorous:
  * polies\_dress:
    * Replace same gender criteria for either both male or both not male.
  * poly\_fucks\_poly:
    * Add logic for when both actors can impregnate and become pregnant.
* vin\_Pregnancy:
  * breeding\_party\_cms:
    * Remove sb\_Better\_Pregnancy dependency
    * Adjust verbiage to reflect the aim to get the player pregnant.
    * Expand guest conditions to allow trans characters.
    * Add one's companion as a potential partner.
  * breeding\_party\_companion\_cms:
    * Remove sb\_Better\_Pregnancy dependency
    * Consolidate conditions so only one call to Random() is made
    * Add more stats to the mix
    * Expand guest conditions to allow trans characters.
  * dildo\_impregnate\_cms:
    * Prevent scene from firing is actor is already pregnant.
    * Add shorter timeout when you choose to participate.
  * double\_breeding:
    * Expand guest conditions to allow trans characters.
  * ex\_pregnancy\_plot:
    * Rework trigger logic to make sure that at least one participant can get
      the other prregnant.
  * go\_last\_cms:
    * Replace Player.isMale() with !Player.isFemale()
    * Expand guest conditions to allow trans characters.
  * lesbian\_sperm\_donor:
    * Expand guest conditions to allow trans characters.
    * Change scene to support lesbian couples with one member already pregnant.
    * Add option to both get impregnated (if neither was pregnant before)
  * lesbian\_sperm:
    * Expand guest conditions to allow trans characters.
    * Add option to both get impregnated
  * look\_like\_you\_cms:
    * Replace Actor.isFemale() with !Actor.isMale()
    * Replace Player.isMale() with !Player.isFemale()
  * make\_baby:
    * Add options to "This isn't working" to follow up with various other
      scenes.
  * NPC\_discovers\_pregnancy:
    * Prevent spouse from making a fuss if they're in a poly
  * NPC\_gives\_birth:
    * They're still a relative, even if they're growing up in another family
  * NPC\_gives\_birth\_neutral:
    * Rename actors to prevent confusion
    * Father shows up
    * Kid will be a relative if either parent is either a relative or a spouse
    * Currently implemented:
      * Sibling (either parent is also your parent)
      * Stepchild (either parent is dating you)
      * Stepsibling (either parent is your stepparent)
      * ParentSibling (either parent is your grandparent)
      * Cousin (either parent is your parentsibling)
      * Cousin (default catchall)
  * player\_gives\_birth:
    * Rename variables to keep who is who straight
    * Add both the real father and fake father if they are different.
  * pregnancy\_arousal:
    * Change the criteria from the one who impregnated you to who you're dating
  * pregnancy\_doctor:
    * Expand guest conditions to allow trans characters.
  * pregnancy\_energy:
    * Change the criteria from the one who impregnated you to who you're dating
  * pregnancy\_mood:
    * Change the criteria from the one who impregnated you to who you're dating
  * pregnancy\_pact:
    * Expand guest conditions to allow trans characters.
  * propose\_baby:
    * Change logic for extra non-cishet energy.
  * surrogate:
    * Expand guest conditions to allow trans characters.
