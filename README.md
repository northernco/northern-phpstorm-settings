# Northern PhpStorm Settings

## Importing Settings

Steps to import PhpStorm Code Style Schemes:

- From the main menu: `File > Manage IDE Settings > Settings Repository`
> *Note:* For older PhpStorm versions, this may be under `File -> Settings > Tools -> Settings Repository`
- Paste `https://github.com/northernco/northern-phpstorm-settings.git` as the Upstream URL and click `Overwrite Local`
- You may need a [GitHub Personal Access Token](https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#creating-a-personal-access-token) if it prompts you for one.
- Restart PhpStorm

You should now be able to select a code style scheme by doing the following:

- From the main menu: `File -> Settings`
- Navigate to: `Editor -> Code Style`
- Open the `Scheme` dropdown
- The list should now include Northern code styles

## Extra Settings

Unfortunately not all settings can be imported using the Settings Repository tool. 

Please set the following settings below using `File -> Settings`:
- `Editor -> General` below the `On Save` heading, check `Ensure every saved file ends with a line break` and `Remove trailing blank lines at the end of saved files`
- `Editor -> General -> Auto Import` below the `PHP` heading, uncheck both `Enable auto-import in file scope` and `Enable auto-import in namespace scope`
- `Editor -> Inspections` navigate to `PHP -> Code Style -> Fully qualified name usage` and change `Severity` to `No highlighting, only fix`
- `Editor -> File Types` select `PHP` and add `*.theme` as a file name pattern

## Drupal Notes

PhpStorm will automatically change the code styles if it detects that the project is on Drupal.
After setting up the project in PhpStorm, please double check that the `Northern Drupal` code styles are being used.
