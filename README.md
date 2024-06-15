# Localizations for [LEZ](https://lez.daztraxstudioss.com/)

Hi there, want to contribute and add localizations to the game to add more languages? You are in the right place.
This is the repository where all the localizations are added in the game and will be updated to the public builds when we release an update.

## Important / Read before starting contributing
- Before adding localizations, we recommend that you add the translations with your native languages and not as a secondary language or using a translator, the main purpose of this repository is so that the community can add translations that come naturally to people.
- We will only add the languages that are from the added folders on this repository for now, this is because we want to add languages that are in the list of [LootLocker SDK (lootlocker/unity-sdk)](- We will only add the languages that are from the added folders on this repository for now, this is because we want to add languages that are in the list of [Full Platform Supported Languages](https://partner.steamgames.com/doc/store/localization/languages#supported_languages) as an **API language code**.

# Getting started
To start adding the content for localizations, we recommend you to use [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/), or [Visual Studio Code](https://code.visualstudio.com/download) since the localization files are JSON files.

# Adding the content
- All the text that are on **{Curly Brackets}** should not be changed.
  - Example: a text in English "**Version: {gameVersion}**" should be in Spanish as "**Versión: {gameVersion}**" and not "**Versión: {VersiónDelJuego}**", or in Japanese as "**バージョン: {gameVersion}**" and not "**バージョン: {ゲームバージョン}**".
- The "Content" field is the text that will be displayed with its translation, however, the "Key" field should not be changed since the game will search the localization by the "Key" on English.
