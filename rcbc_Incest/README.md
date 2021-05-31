# rcbc\_Tweaks
RCBC's tweaks to various scenes.

## Changelog 4.0s.0:
  * drunk\_dad\_cms:
    * Expand conditions:
      * Character can be either male or trans, with dialogue changed to reflect.
    * New Conditions:
      * Character either doesn't have a partner or is in a polyamorous
        relationship.
  * family\_incest\_erotica:
    * Lowered the max perversion requirement and raised the max incest
  * family\_incest\_game:
    * Lowered the max perversion requirement and added a max incest
  * family\_incest\_porn:
    * Added a max incest
  * help\_family\_practice:
    * Combined random stat checks into one, replaced interpersonal with
      perversion, and removed redundant Random() calls.
    * Increased Actor2's perversion when increasing their incest.
  * incest\_cherry\_boy\_cms:
    * Expanded WHEN by a couple hours
    * Lowered timeout (It's already limited by an external factor.)
  * incest\_cherry\_boy\_repeat\_cms:
    * Let Actor2 be trans
  * incest\_owned:
    * Ensure the actors parent/child
    * Let Actor2 be trans
    * Raise the minimum and lower the maximum masochism to proc
    * Trans players can go through either branch of the scene (depending on
      stats)

## Contents:
* Scenes:
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
    * Character can be either male or trans, with dialogue changed to reflect.
    * Character either doesn't have a partner or is in a polyamorous relationship.
  * family\_harem\_cms:
    * Replace player.isMale() with !Player.isFemale()
  * family\_incest\_erotica:
    * Lowered the max perversion requirement and raised the max incest
  * family\_incest\_game:
    * Lowered the max perversion requirement and added a max incest
  * family\_incest\_porn:
    * Added a max incest
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
    * Combined random stat checks into one, replaced interpersonal with
      perversion, and removed redundant Random() calls.
    * Increased Actor2's perversion when increasing their incest.
  * incest\_breakup\_dating:
    * Trigger based on the difference of the actors' incest stats.
  * incest\_cherry\_boy\_cms:
    * Replace gender checks to allow trans characters in either role.
    * Expanded WHEN by a couple hours
    * Lowered timeout (It's already limited by an external factor.)
  * incest\_cherry\_boy\_repeat\_cms:
    * Let Actor2 be trans
  * incest\_owned:
    * Ensure the actors parent/child
    * Let Actor2 be trans
    * Raise the minimum and lower the maximum masochism to proc
    * Trans players can go through either branch of the scene (depending on
      stats)
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
