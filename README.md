# No Summon Vision

In core Foundry, when a player selects a token with "Has Vision" disabled, they can only see their previously explored portions of the map through the fog of war.
They can't see other tokens, including their own, because they are hidden by the fog of war.
This is very inconvenient for cases where a player has summoned a creature or token, but you don't want the player to be able to see through that token's vision, such as a spiritual weapon or the like.
Previous workarounds basically required giving the token vision, which could result in spoilers or simply a tactical advantage from seeing around corners.

"No Summon Vision" to the rescue!
Now, summons can have "Has Vision" disabled, but the player will still be able to see through their default view—the union of the vision of all of their tokens with vision.

## Compatibility

This module is likely incompatible with any module which overrides `SightLayer#updateToken`. This includes, but is not limited to:

- ❌ Haste by grape_juice

I'll be working to add compatibility for these as soon as possible.
Compatibility patches for No Summon Vision are possible and easy.
If you encounter a conflict, please ping me (@cole#9640) and the other module author on Discord and I'd be happy to help them set up compatibility with No Summon Vision.

## License

Licensed under the GPLv3 License (see [LICENSE](LICENSE)).
