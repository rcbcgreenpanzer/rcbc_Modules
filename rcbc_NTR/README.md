# rcbc\_NTR
RCBC's tweaks to vin\_NTR

## Changelog 4.0s.0:
* night\_with\_colleagues\_cms:
  * Attempt to grab an already generated colleague before generating someone new.
  * Make the colleague permament

## Contents:
* Scenes:
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
  * night\_with\_colleagues\_cms:
    * Attempt to grab an already generated colleague before generating someone new.
    * Make the colleague permament
