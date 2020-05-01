# Northern PhpStorm Settings

## Importing Settings

Steps to import PhpStorm Code Style Schemes:

- From the main menu: `File -> Settings`
- Navigate to: `Tools -> Settings Repository`
- Click on the plus button in the `Read-only Sources` section
- Paste `https://github.com/northernco/northern-phpstorm-settings.git` into the URL input and click `OK`
- Click `Apply` then `OK`
- Restart PhpStorm

You should now be able to select a code style scheme by doing the following:

- From the main menu: `File -> Settings`
- Navigate to: `Editor -> Code Style`
- Open the `Scheme` dropdown
- The list should include Northern code styles

## Extra Settings

Unfortunately not all settings can be imported using the Settings Repository tool. 

Please set the following settings below using `File -> Settings`:
- `Editor -> General` check `Ensure line feed at file end on Save` below the `Other` heading
- `Editor -> General -> Auto Import` uncheck both `Enable auto-import in file scope` and `Enable auto-import in namespace scope` below the `PHP` heading
- `Editor -> Inspections` navigate to `PHP -> Code Style -> Fully qualified name usage` and change `Severity` to `No highlighting, only fix`
