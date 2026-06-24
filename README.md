# Endless Par🇮🇹le

This is a fork of [pietroppeter/wordle-it](https://github.com/pietroppeter/wordle-it)
modified to allow endless play. The original game is limited to one word per
day, but this version lets you play as many times as you want.

Each game is now driven by a visible numeric seed. The seed is shown below the
title, can be randomized, and can also be edited manually from the settings
panel, making it possible to replay a specific puzzle or share the same puzzle
seed with someone else. Starting a new seeded game resets the board, keyboard,
and saved in-progress state.

At the end of a game, the statistics screen now focuses on continuing play. The
new **Gioca ancora** button immediately starts another game with a fresh seed,
so winning or losing no longer blocks the player until the next day. The old
share action has been removed; in its place there is a **Resetta** button that
clears saved statistics and starts over with a new game.

The game is live at https://epistrephein.github.io/wordle-it-endless.
