# M1

<br />

## Defaults

### Mission Control

Choose whether to rearrange Spaces automatically


#### Set to `true` (default value)

  - Do reorder Spaces based on most recent use

```shell
defaults write com.apple.dock "mru-spaces" -bool "true" && killall Dock
```

#### Set to `false`

  - Keep the spaces arrangement

```shell
defaults write com.apple.dock "mru-spaces" -bool "false" && killall Dock
```


#### Read the current value

```shell
defaults read com.apple.dock "mru-spaces"
```

#### Reset default value

```shell
defaults delete com.apple.dock "mru-spaces" && killall Dock
```

