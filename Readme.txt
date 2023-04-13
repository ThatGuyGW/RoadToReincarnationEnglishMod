Mod Operation by @Cadenza

This mod is made of several independant parts. 
First, we're analysing AssetBundles and dumping untranslated lines (in _Data\StreamingAssets).
Then, we have another system to translate TextAssets (think of it as .json files) objects.

	>>General Operation
In Bepinex\plugins\Translations, you'll find the translation directories used to patch AssetBundles (TAKV.txt, UITextKV.txt). 
In Bepinex\plugins\Dump, you'll find the untranslated lines. TAKVUn.txt is generated in real-time. UITextKVUn might too, i'm not sure anymore. 
But a more solid way to populate UITextKVUn.txt is to press F1 in-game. The plugin will parse all the assets and bundles, locate UnityEngine.UI.Text object and output any untranslated (i.e. not in Translations\UITextKV.txt) line to Dump\UITextKV.txt). 
After that, you'll just have to add said lines to the file in Translation.
Same goes for TAKV.txt except, again, this one is populated in real time.
 
Lastly, err... well.. there is the whole Metadata patching stuff. Let's say I've done it. And if there's an update, we'll talk about it. It's not complicated, but it's something that takes 10min. It's what I used to do with IWOL when building updates. It's not much, but it has to be done by someone. 

	>>Note 1
The mod has a large performance cost on game start and new save generation. 
After that, there may be a performance impact, but I tried to keep it as low as possible. Further optimization is possible if people are enjoying the game. 

	>>Note 2
When you'll first run the game with the mod, it *will* take time to start. That's not related to the mod. It's just BepinEx getting ready. It's a first-time only operation.	
	
@Cadenza out
