# Northern PhpStorm Settings

## Importing Settings

Steps to import PhpStorm Code Style Schemes:

- From the main menu: `File -> Settings` (or `PhpStorm -> Preferences` on macOS)
- Navigate to: `Tools -> Settings Repository`
- Click on the plus button in the `Read-only Sources` section
- Paste `https://github.com/northernco/northern-phpstorm-settings.git` into the URL input and click `OK`
- Click `Apply` then `OK`
- Restart PhpStorm

You should now be able to select a code style scheme by doing the following:

- From the main menu: `File -> Settings` (or `PhpStorm -> Preferences` on macOS)
- Navigate to: `Editor -> Code Style`
- Open the `Scheme` dropdown
- The list should include Northern code styles

## Extra Settings

Unfortunately not all settings can be imported using the Settings Repository tool. 

Please set the following settings below using `File -> Settings` (or `PhpStorm -> Preferences` on macOS):
- `Editor -> General` below the `On Save` heading, check `Ensure every saved file ends with a line break` and `Remove trailing blank lines at the end of saved files`
- `Editor -> General -> Auto Import` below the `PHP` heading, uncheck both `Enable auto-import in file scope` and `Enable auto-import in namespace scope`
- `Editor -> Inspections` navigate to `PHP -> Code Style -> Fully qualified name usage` and change `Severity` to `No highlighting, only fix`
