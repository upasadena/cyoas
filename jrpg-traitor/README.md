# JRPG Traitor: Interactive

## Changelog

* Fixed child sections so that they appear and disappear with their parent
    * Permanently hid (removed in a future release) the "Toggle Child Tabs"
      buttons
* Allowed the **Three Dragons** Side Quest to have more than one dragon
  selected
* Added new **Ending** section that is shortened significantly and hidden
  behind a side-by-side tabbed menu
* Separated the **Notes** section from the main title, and gave it a left
  alignment so that it's easier to read
* Only shows **Basic Tokens** by default now, rather than both **Basic Tokens**
  and **Advanced Tokens**


## TODO

- [ ] Forcibly activate the choices that you can get for free with your class
    - [ ] It seems I had tried that but disabled that for some reason. How
      about: for the powers involved, have it in a negative state. That is,
      have the powers be free by default, but only cost when the class is not
      chosen.
    - [ ] Ooh maybe, make it free if the base class is selected (not the select
      free power option), and a Not Selected requirement for the ones that are
      adjacent
- [ ] Enforce how many mentors/apprentices you can have (unless you have one of
  the specific gifts that allow you as many as you wish)
    * How would you account for getting new mentors after your old one died or
      otherwise is no longer teaching you? A section that prompts you about it?
      Maybe a section for each option that possibly ends in your mentors death?
      **Maybe those options forcibly add to the Mentor count?**
- [ ] For **AGE** section, allow taking Advanced Tokens too, as it doesn't
  actually specify *against* taking it
- [ ] Use Lt Ouromov's viewer

## Far off TODO

- [ ] Fix beginning images that are slightly cut off
- [ ] For powers that require "X amount of tokens spent", add an invisible
  Point Type that is incremented automatically, and for those specific powers,
  check if that Point Type is over or equal to the X threshold
    - [ ] Use Words to dynamically show the amount of Points spent? Somehow?
      Where would I put it? Maybe have it able to be toggled, and maybe in the
      Debug Points section.
- [ ] For powers that require "X number of elements", much the same as above
