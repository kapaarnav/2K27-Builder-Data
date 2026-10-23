# 2K27 Builder Data

`data/2k27.sqlite` is an NBA 2K27 MyPlayer database.

- Attribute caps for every position, height, wingspan, and weight (`latest_attribute_caps`)
- Badges and the attribute ratings required for Bronze, Silver, Gold, and Hall of Fame (`badges`, `badge_requirements`)
- Animations and the heights and attribute ratings required to unlock them (`animations`, `animation_requirements`)
- Takeovers and the attribute ratings required to equip them (`takeovers`, `takeover_requirements`)

An `and` requirement needs every listed attribute. An `or` requirement needs any one of them. Jumper bases list a `rating` rather than one shooting attribute. Heights are in inches.
