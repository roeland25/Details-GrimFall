# Details! for GrimFall

A modified version of **Details! Damage Meter** made to work with the **GrimFall WoW server**.

This version uses the cleaner, more modern Details interface instead of the ugly versions commonly found on legacy WoW addon websites like Felbite.

![Details meter](https://i.imgur.com/sZdoFgg.png)

## Download

**Do not use `Code -> Download ZIP`.** (if you know how to rename an addon folder then do so, i'm not your boss)

Download the ready-to-install addon from the Releases page instead:

### [Download the latest release](https://github.com/roeland25/Details-GrimFall/releases/latest)

Under **Assets**, download:

`Details-GrimFall.zip`

## Installation

1. Download `Details-GrimFall.zip` from the [latest release](https://github.com/roeland25/Details-GrimFall/releases/latest).
2. Extract the ZIP file.
3. You should now have a folder named:

   `Details`

4. Place that folder inside:

   `GrimFall\Games\Wotlk\Interface\AddOns\`

Your final folder structure should look like this:

```text
GrimFall
└── Games
    └── Wotlk
        └── Interface
            └── AddOns
                └── Details
                    ├── Details.toc
                    ├── Details.xml
                    ├── boot.lua
                    └── ...
```

## Troubleshooting

### Details does not appear in the AddOns list

Make sure the folder is named exactly:

`Details`

and not:

```text
Details-GrimFall
Details-GrimFall-main
Details-main
```

The `Details.toc` file should be directly inside the `Details` folder.

Correct:

```text
AddOns\Details\Details.toc
```

Incorrect:

```text
AddOns\Details-GrimFall\Details\Details.toc
```






