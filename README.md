# Unreal Engine Mod Loader
A tool used to load Blueprint and basic SDK based C++ Mods for Unreal Engine 4 games

## 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Information about this fork
This fork exists to work with [BR_MagicMod](https://github.com/Redacted00/BR_MagicMod) only. Please don't use [Unreal Engine Mod Loader](https://github.com/RussellJerome/UnrealModLoader) in 2026 - use [RE-UE4SS](https://github.com/UE4SS-RE/RE-UE4SS)
> More details about *Redacted's Magic Mod* [here](https://github.com/Redacted00/BR_MagicMod)

### Build instructions
1. Clone this repo
2. Execute this command: `git submodule update --init --recursive`

Then you can open `.sln` file in `UnrealEngineModLoader` folder and build it from Visual Studio.

### How to install?
1. Copy **UnrealEngineModLoader.dll**, **xinput1_3.dll** from your build folder and **ModLoaderInfo.ini**, **Profiles** from cloned repo to `(your-steam-folder)\steamapps\common\Brick Rigs\BrickRigs\Binaries\Win64`
2. In **ModLoaderInfo.ini** file add path to **UnrealEngineModLoader.dll** as below:

   ```ini
   [INFO]
   LoaderPath=(your-steam-folder)\steamapps\common\Brick Rigs\BrickRigs\Binaries\Win64\UnrealEngineModLoader.dll
   ```
3. Copy **RedactedMagicMod.dll** from your build folder to `(your-steam-folder)\steamapps\common\Brick Rigs\BrickRigs\Content\CoreMods` (*create CoreMods folder*)

## 🇷🇺 Информация по поводу форка
Этот форк существует только ради работы моего старого мода. Умоляю не используйте [Unreal Engine Mod Loader](https://github.com/RussellJerome/UnrealModLoader) в 2026 году - используйте [RE-UE4SS](https://github.com/UE4SS-RE/RE-UE4SS)
> Подробнее по поводу *Redacted's Magic Mod* [здесь](https://github.com/Redacted00/BR_MagicMod)

### Инструкция как скомпилить
1. Клонируйте репозиторий куда вам удобно.
2. Пропишите эту команду в этой папке: `git submodule update --init --recursive`

Далее вы можете открыть `.sln` файл в `UnrealEngineModLoader` папке и скомпилить проект с помощью Visual Studio.

### Как установить?
1. Скопируйте **UnrealEngineModLoader.dll**, **xinput1_3.dll** из вашей билд папки и **ModLoaderInfo.ini**, **Profiles** из папки с этим репозиторием в `(your-steam-folder)\steamapps\common\Brick Rigs\BrickRigs\Binaries\Win64`
2. В **ModLoaderInfo.ini** добавьте путь к **UnrealEngineModLoader.dll** как ниже:
   
   ```ini
   [INFO]
   LoaderPath=(your-steam-folder)\steamapps\common\Brick Rigs\BrickRigs\Binaries\Win64\UnrealEngineModLoader.dll
   ```
3. Скопируйте **RedactedMagicMod.dll** из вашей билд папки в `(your-steam-folder)\steamapps\common\Brick Rigs\BrickRigs\Content\CoreMods` (*создайте папку CoreMods*)
   
