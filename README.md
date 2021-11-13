# Setup

[fira_reg](https://raw.githubusercontent.com/gmbrianlaw/setup/main/fira_regular.otf)

[fira_med](https://raw.githubusercontent.com/gmbrianlaw/setup/main/fira_medium.otf)

[fira_bld](https://raw.githubusercontent.com/gmbrianlaw/setup/main/fira_bold.otf)

### Name: FiraMono Nerd Font Mono

### ITERM don't change size, COLOR: #161616

### VSCode: Shell:, Workspaces: Manage

### VSCode: Atom, Material
### PRESS ESC when prompt

```json
{

    "editor.bracketPairColorization.enabled": true,
    "editor.fontFamily": "FiraMono Nerd Font Mono, Monaco, 'Courier New', monospace",
    "editor.renderWhitespace": "all",
    "editor.rulers": [100],

    "explorer.compactFolders": false,

    "files.exclude": {
        "**/.DS_Store": true,
        "**/.git/": true,
        "**/.hg/": true,
        "**/.svn/": true,
        "**/CVS/": true,
        "**/__pycache__": true,
        "**/venv/": true
    },

    "window.zoomLevel": -0.75,

    "workbench.colorTheme": "Atom One Dark",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "none"

}
```

### USE SUDO when installing starship

### Get Icons at https://nerdfonts.com/cheat-sheet

```toml
format = """
$directory\
$line_break\
$battery\
$memory_usage\
$time\
$cmd_duration\
$line_break\
$java\
$python\
$git_branch\
$git_commit\
$git_metrics\
$git_state\
$git_status\
$line_break\
$character\
"""

command_timeout = 10000
scan_timeout = 10000

[battery]

    format = "\\[ [$symbol $percentage]($style) \\]"

    charging_symbol = "" # nf-mdi-battery_charging
    discharging_symbol = "" # nf-mdi-battery_charging
    empty_symbol = "" # nf-mdi-battery_charging
    full_symbol = "" # nf-mdi-battery_charging
    unknown_symbol = "" # nf-mdi-battery_charging

    [[battery.display]]

        threshold = 100

        style = "#FFFF00"

[character]

    format = "\\[ $symbol \\] "

    error_symbol = "[](#FF0000)" # nf-fa-arrow_right
    success_symbol = "[](#00FF00)" # nf-fa-arrow_right
    vicmd_symbol = "[](#FF0000)" # nf-fa-arrow_right

[cmd_duration]

    min_time = 1

    format = "\\[ [羽$duration]($style) \\]" # nf-mdi-timer_sand

    style = "#FF00FF"

    show_milliseconds = true

[directory]

    format = "\\[ ([$read_only ]($read_only_style))[$path]($style) \\]"

    style = "#00BFFF"

    read_only = "" # nf-mdi-lock

    truncation_length = 100

[git_branch]

    format = "\\[ [$symbol $branch]($style) \\]"

    style = "#FF00FF"

    symbol = "" # nf-dev-git_branch

[git_commit]

    format = "\\[ [ $hash]($style) \\]" # nf-dev-git_commit

    style = "#FF00FF"

[git_metrics]

    disabled = false

    format = "(\\[ ([+ $added ]($added_style))([- $deleted ]($deleted_style))\\])"

    added_style = "#FF00FF"
    deleted_style = "#FF00FF"

[git_state]

    format = "\\[ [$state( <$progress_current/$progress_total>)]($style) \\]"

    style = "#FF00FF"

[git_status]

    format = "(\\[ [($all_status )(<$ahead_behind> )]($style)\\])"

    style = "#FF00FF"

    deleted = "x"

[java]

    format = "\\[ [$symbol $version]($style) \\]"

    style = "#FF0000"

    symbol = "" # nf-dev-java

    version_format = "$raw"

[line_break]

[memory_usage]

    disabled = false

    threshold = 1

    format = "\\[ [$symbol $ram_pct]($style) \\]"

    style = "#FFFFFF"

    symbol = "" # nf-mdi-memory

[python]

    format = "\\[ [$symbol $version( <$virtualenv>)]($style) \\]"

    style = "#00FF00"

    symbol = "" # nf-dev-python

    python_binary = "python3"

    version_format = "$raw"

[time]

    disabled = false

    format = "\\[ [ $time]($style) \\]" # nf-weather-time_3

    style = "#FFA500"

```

### iTerm no change in size, NO title bar, name 'Default'

### git config --global (init.defaultBranch, user.name, user.email)

### WHEN getting GH; remember remember: PRIVACY > turn thingis off ALSO GIVE FULL DISK ACCESS

### NO ZOOM

### for GH:

```sh
tar -xf gh....
cd gh...
sudo mv share /usr/local
sudo mv bin/gh /usr/local/bin
```
