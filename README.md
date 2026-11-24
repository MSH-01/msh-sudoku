**sudoku - studio msh**

#### brief
i'm a long time sudoku enjoyer, but using the sudoku.com app has gotten to the point where it's actively ruining my enjoyment. they're pushing so much shitty slop that its becoming genuinely intrusive to the gameplay, random animations + scenes mid game when you complete a row / column / cell that freeze input for a second, random events / game modes extra shite that i just am not interested in. i voiced my opinion to the dev team, have opened many a support ticket yet they're unwilling to disable them or at least add a setting to turn them off, its frustrating, but i guess they built the thing for casual players.

i'm trying to make this new sudoku app feel more like chess.com - a place for casuals and serious players to play the game, competitively, gain ELO, have a rank, go head to head with other players, learn about their technique, and not be incumbered by the garbage that is ever present on sudoku.com. this version is untitled as of right now, but i'm thinkin about what to call this thing.

#### features
- one daily puzzle for everyone, and a public-domain painting for each one you solve (in colour on the day, black and white after), hung in a gallery by month with a masterpiece to unveil
- quick play at five levels: easy, medium, hard, expert, master
- ranked versus: race doku at your own rating (glicko-2), with a level, a bar to the next and your history
- friends and head to head matches, with replays
- daily leaderboards, streaks and standing
- learn: a course of techniques, hints that point before they tell, lessons from your own games, a review of every digit
- zen mode: quick play with no clock, no score, and nothing leaving your phone
- widgets: the daily, a calendar of your paintings, a streak wall
- full setup customisation, light and dark
- free!

#### what it runs on
- **ios** (`ios/`): native swiftui app and widgets, on testflight.
- **android** (`android/`): native kotlin + jetpack compose, material 3, at parity with ios. signed apks go out as releases on the public [sudoku-android](https://github.com/MSH-01/sudoku-android) repo, which app stores like obtainium follow.
- **web**: planned, in `docs/plans/web.md`.

#### install
download the apk from the [latest release](https://github.com/MSH-01/sudoku-android/releases/latest), or point an app store that follows github releases (like [obtainium](https://github.com/ImranR98/Obtainium)) at this repo for updates. the app plays as a guest; your games are kept on your phone and synced to your account.

#### things i want to do still
- [ ] tighten gameplay loop
  - [ ] ui improvements on grid and game screen
  - [ ] ability to fail a game
  - [ ] better hints
  - [ ] max mistake amount
- [ ] better challenge and friend screen
- [ ] animations baby
- [ ] web version
- [ ] a shinier result screen with the points broken down, and live "brilliant" moves (see `docs/plans/backlog.md`)
