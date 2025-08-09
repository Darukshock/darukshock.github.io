# Custom resources in Vanilla Minecraft
## Quick Intro
Minecraft **datapacks** and **resource packs** are **data-driven**, meaning a big part of the game is not **hardcoded**.
For instance, advancements are data-driven, so there's no need to recompile the game to add new ones. A simple `/reload` does the trick.
On top of that, it enables merging many game modifications seamlessly.
As a developper, it's a lot **quicker** and **easier** to broaden the game's data-driven contents rather than diving head first into the source code.<br>
But Vanilla Minecraft limits us to a given set of resources (aka registries), which can be found on [Misode's Generators](https://misode.github.io/generators/) (huge thanks to him !)<br>
Always wanting to make my code as extensible as possible, I went on a journey to find the best way to add custom resources. Here's a step-by-step guide on how to do it.
## Requirements
- Basic datapack knowledge (check out [Quackleb's beginner tutorial](https://www.youtube.com/watch?v=E0BLq5Ll37c))
- Python installed on your device (check out [Python Programmer's tutorial](https://www.youtube.com/watch?v=YKSpANU8jPE))
- [Beet](https://mcbeet.dev) setup (check out [Big Papi's Beet tutorial](https://www.youtube.com/watch?v=IOS-OnqE4GY))
- (Optional) [Visual Studio Code](https://code.visualstudio.com/) for your custom syntax highlighting and folder icons
    - Syntax highlighting: [Spyglass](https://marketplace.visualstudio.com/items?itemName=SPGoding.datapack-language-server) 
    - Custom folder & file icons : [Datapack Icons](https://marketplace.visualstudio.com/items?itemName=SuperAnt.mc-dp-icons)