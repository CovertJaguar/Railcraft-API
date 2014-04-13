Railcraft-API
=============

An API for interacting with Railcraft.

The latest version can be dowloanded from:
https://dl.dropboxusercontent.com/u/38558957/Minecraft/Railcraft/Railcraft_API_latest.zip

The Railcraft API is provided as Open Source with no limitation on use (MIT License - http://choosealicense.com/licenses/mit/).

When attempting to use this API, please use ONLY the classes you need, deleting those you don't.
This helps to reduce conflict if the API changes slighty between versions.

Ore Dictionary Tags:
	blockSteel
	dustCharcoal
	dustObsidian
	dustSaltpeter
	dustSulfur
	ingotSteel
	oreSaltpeter
	oreSulfur

| ____Message____ | ______________Syntax______________ | Description |
|-----------------|------------------------------------|-------------|
| "ballast"       | "[modid]:[blockName]@[metadata]"   | Registers a block as a valid ballast for the Tunnel Bore and Undercutter.
| "boiler-fuel-liquid"  | "[liquidName]@[fuelValuePerBucket]" | Specifies a fuel value for a bucket of liquid fuel. The liquid name should be the English display name of the liquid (ie. the tag used to lookup the liquid in the LiquidDictionary).
