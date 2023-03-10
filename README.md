# Wynem Resource Packs
This repository contains a list of resource packs that will be available through the [Wynem Discord bot](https://wynem.com/) as custom game versions. This means that anyone using the bot will be able to browse its texture files using the bot.

## Submitting Resource Packs
Anyone can submit resource packs to this repository as long as the pack meets certain requirements:
1. You must have full permission from the pack author to put the pack on the bot
2. The pack must be of a high quality, and change a substantial amount of the textures in the game
3. The pack must not be larger than 20MB in size
4. The URL submitted for the pack must hosted on a trusted public website, such as CurseForge, Modrinth, MediaFire, etc.

Important: I have the final say of deciding if a pack is on the bot or not, even if it meets all the above criteria.

## How to Submit
1. Go to the `resourcepacks.json` file located in this repository
2. Add your pack to the list, following this format:
```js
"packID": {
  "download": "https://download.com/resourcepack.zip",
  "author": "0123456789"
}
```
3. Create a pull request, and show that you have permission to add the pack (if required)

## JSON format
- Download
  - A direct download link to the ZIP of the resource pack
- Author
  - Your Discord user ID. This will allow you to reload the pack using the `e!reloadpack` command
- Alias
  - An optional field that is an alias ID for the pack
- Name
  - An optional field that will be the name of the pack. By default this is generated from the ID by removing underscores and making it title case