# Agent Workshop

A dark Grok Bot inspired theme for Omarchy: graphite surfaces, soft ivory text, violet focus accents, cyan details and warm amber highlights, with five cinematic agent wallpapers.

![Agent Workshop — a Grok Bot inspired Omarchy theme with five cinematic wallpapers](preview.png)

*The cover is AI-generated promotional artwork showing four examples and the palette direction. It is not a live desktop screenshot.*

## The theme

Small colourful agents quietly building, researching, organising and checking their work. The wallpapers translate Grok Bot style avatar shapes into tangible 3D characters, with workshop lighting, rainy windows, mountain scenery and subtle Omarchy emblems.

The interface takes a quieter approach: dark graphite and charcoal surfaces, soft ivory text, violet for focus and cyan for secondary detail. Warm amber reflects the lighting in the scenes. Terminal and status colours are softened for readability; they are not literal copies of the avatars' vivid colours.

| Colour | Value |
|---|---|
| Graphite background | `#11151d` |
| Raised charcoal | `#202734` |
| Soft ivory text | `#ddd9cf` |
| Violet focus accent | `#b49be8` |
| Cyan detail | `#83c8c5` |
| Warm amber | `#e2aa78` |
| Selection | `#333049` |
| Secondary text | `#a8aebd` |

This is a complete named Omarchy palette, including active and inactive window-border colours. Omarchy generates its supported shell, terminal and editor colours from colors.toml. The package supplies colours and backgrounds; it does not install bots or plugins, change fonts or rearrange the desktop.

## Five wallpapers

| Wallpaper | Scene |
|---|---|
| [Midnight Build](backgrounds/01-midnight-build-3440x1440.webp) | Violet, cyan and orange agents collaborating at a coding workbench |
| [Research After Hours](backgrounds/02-research-after-hours-3440x1440.webp) | Blue, yellow and magenta agents researching in a rain-lit library |
| [Quiet Operations](backgrounds/03-quiet-operations-3440x1440.webp) | A colourful agent team coordinating work above mountain scenery |
| [Automation Foundry](backgrounds/04-automation-foundry-3440x1440.webp) | Agents assembling and inspecting modules on a miniature conveyor |
| [Omarchy Workbench](backgrounds/05-omarchy-workbench-3440x1440.webp) | A small team assembling a desktop workstation |

All five backgrounds are **3440 × 1440 WebP exports**, upscaled from AI-generated originals approximately **1938–1939 × 811** pixels. Export uses Lanczos resampling with a small centred aspect-ratio crop where needed. These are not native 4K or native ultrawide-detail images. Separate 16:9 editions are not included; fill/crop modes on other screen ratios may trim the scene.

## Installation

```sh
omarchy theme install https://github.com/shaggyrs6-netizen/omarchy-agent-workshop-theme
```

Select it afterwards if needed:

```sh
omarchy theme set agent-workshop
```

Choose a scene using Omarchy's background picker, or cycle through the collection:

```sh
omarchy theme bg next
```

This is an Omarchy Quattro palette theme. Installing by repository URL does not require a marketplace listing. No registry listing is claimed.

## Validation and limits

The installed Omarchy **4.0.6-1** template renderer generated **19 configuration files** in an isolated workspace directory, with no unresolved palette tokens. Generated TOML and JSON were parsed. All five exported wallpapers decode at 3440 × 1440 and match the approved artwork exports.

**27 selected opaque text/surface contrast pairs** passed a 4.5:1 target; the lowest tested pair was **5.30:1**. These checks cover selected text colours against the background, raised surface and selection colour. They do not establish whole-desktop accessibility compliance; transparency, application colour combinations and display calibration can change the result.

The theme was installed and activated on the author's Omarchy desktop. The active palette and all five staged wallpapers matched the reviewed files, the running shell responded, Hyprland reported no configuration errors and the active border colour matched the violet accent. This was a local activation check, not an exhaustive application or multi-version compatibility test. The author's installation excluded automatic Obsidian vault theme sync; a normal Omarchy theme switch may apply its usual application integrations.

## Credits and licence

Prepared by Lee Shand / Wired Differently with AI assistance. All five wallpapers and the promotional cover are AI-generated artwork. Grok Bot avatar silhouettes and colours were informed by the public [Omabot avatar implementation](https://github.com/njpatel/omabot/blob/main/Avatar.qml), [palette definitions](https://github.com/njpatel/omabot/blob/main/bin/omabot-watch) and its public demo reference. No private bot roster or conversations were accessed or included. Omarchy's emblem informed the small marks in the scenes. These images are stylised interpretations, not official Grok Bot app screenshots or an endorsed product release.

The [MIT licence](LICENSE) covers the supplied theme files, artwork and documentation, to the extent applicable rights exist. It does not promise exclusive copyright in AI-generated imagery or grant rights in third-party trademarks or emblems. No endorsement by Grok Bot, xAI, Omabot's author or the Omarchy project is claimed.
