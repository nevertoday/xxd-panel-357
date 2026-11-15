<div align="center">

# XXD Panel 357｜One Light in the Darkroom

**Shrinks the subject very small and sets it low in front of the only soft light in a near-black field.**

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 357 · 01 · Desert camel"><br><sub>01 · Desert camel</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 357 · 02 · Meadow horse"><br><sub>02 · Meadow horse</sub></td>
  </tr>
</table>

<p align="center"><sub>Top: the original photo. Bottom: the same photo in this style.</sub></p>

## What it is

A Skill for AI agents such as Claude Code and Codex. Give it a photo and it paints a finished PNG following the original Panel 357 prompt.

- **What it looks like:** The lower half keeps only the most recognisable subject, outline, structure, pose and narrative relation, shrunk very small and set low in front of the single light, while the upper half stays the original photograph with no added words, and signs or printed text already in the photo are not copied down. The field is almost entirely black; the light is one soft-edged, self-luminous rectangle, the side turned toward it bright and the far side sunk into black, with a faint cool rim and a faint warm rim on the contour, the light and subject slightly soft like a snapshot that missed focus, while a tiny, evenly spaced white cross grid covers the whole field and stays sharp, and a thin cool glow lies on the ground where the light sweeps. Light and subject sit a little off centre, the rest clean black, the subject complete with a little space above the head and nothing touching the centre fold; the colour is the coldest, quietest saturated colour from the photograph, held as near-black, one saturated cool light and near-white lit edges, the cool light only inside the rectangle and its halo. One short word, an inner line and a metaphor for this photograph, that does not name the thing is enlarged into the main mark, white bold sans-serif with wide letter-spacing, stretched across the middle clear of both edges and covering only part of the subject so the whole word stays readable, with one very small white sentence at the top and one bottom line in three short segments, the year begun anew each time, and Chinese set in simplified characters.
- **Keywords:** Near-black field · One soft-edged cool light · Very small, low subject · White cross grid · Widely spaced white word
- **What you can make:** A top–bottom comparison (photo above, design below), a left–right comparison, the design alone, or a wallpaper set for phone, tablet, desktop and watch. Pick several at once, at any ratio or exact pixel size.
- **What it is not:** Not a filter and not a template: every image is redrawn from your photo, and each photo is its own job.

## Get started in three steps

**1. Install.** Works with Claude Code, Codex and other agents that support Skills:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-357 --skill xxd-panel-357
```

Then restart your agent session. You can also `git clone` this repository and link the folder to `~/.claude/skills/xxd-panel-357` or `~/.codex/skills/xxd-panel-357`.

**2. Make sure your agent can generate images.** This Skill has no image model of its own; it uses your agent's image generation, preferably GPT Image 2.

- Codex works as is when its built-in image generation is on.
- Claude Code and other agents without built-in image generation need an OpenAI-compatible image API. It takes about five minutes: see [Setting up image generation](#setting-up-image-generation).

Not sure? Just try it. If images can't be generated, the Skill stops and tells you before doing any work.

**3. Send a photo and say one sentence:**

> Use xxd-panel-357 to turn this photo into a 3:4 top–bottom poster with an English title.

If your request is complete, it starts right away; anything you left out (layout, ratio, text) it asks about, usually in one or two questions. Results are PNGs in a new folder under `~/Desktop/xxd/xxd-panel-357/`.

## Which photos work best

**Works well**

- A person, animal or object alone with one light: someone at a window, a cat with its head down, a window lit at night
- A single thing with a clear outline and pose: a person turned sideways, a house with a readable silhouette, an instrument on a table
- Photos with a messy frame, a cluttered background or a small subject, which are darkened and reduced to one thing in front of the light

**Not a good fit**

- Photos that need a whole street, a crowd or many objects kept at once, since only one thing remains
- Requests to light the field, draw the subject large, or show it facing the camera
- Requests for a second light, warm colour spread across the field, or shop signs copied into the lower half

## Samples

Each image below is a finished result this Skill made from one photo. The top–bottom and left–right sets use different photos.

### Top–bottom: photo above, design below

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 357 · 01 · Desert camel"><br><sub>01 · Desert camel</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 357 · 02 · Meadow horse"><br><sub>02 · Meadow horse</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 357 · 03 · Pond duck"><br><sub>03 · Pond duck</sub></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 357 · 04 · Crawling tortoise"><br><sub>04 · Crawling tortoise</sub></td>
  </tr>
</table>

<details>
<summary>Show 16 more</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 357 · 05 · Floating otter"><br><sub>05 · Floating otter</sub></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 357 · 06 · A red fox"><br><sub>06 · A red fox</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 357 · 07 · A cat fast asleep"><br><sub>07 · A cat fast asleep</sub></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 357 · 08 · Meditating by the sea"><br><sub>08 · Meditating by the sea</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 357 · 09 · Walking slowly alone"><br><sub>09 · Walking slowly alone</sub></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 357 · 10 · A dog in a field"><br><sub>10 · A dog in a field</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 357 · 11 · Parked bicycle"><br><sub>11 · Parked bicycle</sub></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 357 · 12 · Wooden boat by the shore"><br><sub>12 · Wooden boat by the shore</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 357 · 13 · An empty chair"><br><sub>13 · An empty chair</sub></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 357 · 14 · Black iron kettle"><br><sub>14 · Black iron kettle</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 357 · 15 · Person in a straw hat"><br><sub>15 · Person in a straw hat</sub></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 357 · 16 · Canvas tent"><br><sub>16 · Canvas tent</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 357 · 17 · A loaf of bread"><br><sub>17 · A loaf of bread</sub></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 357 · 18 · White porcelain soup bowl"><br><sub>18 · White porcelain soup bowl</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 357 · 19 · A bowl of pears"><br><sub>19 · A bowl of pears</sub></td>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 357 · 20 · Sheep on grass"><br><sub>20 · Sheep on grass</sub></td>
  </tr>
</table>

</details>

### Left–right: photo left, design right

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-21.png" alt="XXD Panel 357 · 21 · Sea lion on a rock"><br><sub>21 · Sea lion on a rock</sub></td>
    <td width="50%"><img src="./assets/examples/sample-22.png" alt="XXD Panel 357 · 22 · Person in a doorway"><br><sub>22 · Person in a doorway</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-23.png" alt="XXD Panel 357 · 23 · Solo yoga"><br><sub>23 · Solo yoga</sub></td>
    <td width="50%"><img src="./assets/examples/sample-24.png" alt="XXD Panel 357 · 24 · Dancer leaning back"><br><sub>24 · Dancer leaning back</sub></td>
  </tr>
</table>

<details>
<summary>Show 16 more</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-25.png" alt="XXD Panel 357 · 25 · Standing giraffe"><br><sub>25 · Standing giraffe</sub></td>
    <td width="50%"><img src="./assets/examples/sample-26.png" alt="XXD Panel 357 · 26 · Penguin on a rock"><br><sub>26 · Penguin on a rock</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-27.png" alt="XXD Panel 357 · 27 · Macaw"><br><sub>27 · Macaw</sub></td>
    <td width="50%"><img src="./assets/examples/sample-28.png" alt="XXD Panel 357 · 28 · Lop-eared rabbit"><br><sub>28 · Lop-eared rabbit</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-29.png" alt="XXD Panel 357 · 29 · Courtyard rooster"><br><sub>29 · Courtyard rooster</sub></td>
    <td width="50%"><img src="./assets/examples/sample-30.png" alt="XXD Panel 357 · 30 · Flamingo in the shallows"><br><sub>30 · Flamingo in the shallows</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-31.png" alt="XXD Panel 357 · 31 · Columnar cactus"><br><sub>31 · Columnar cactus</sub></td>
    <td width="50%"><img src="./assets/examples/sample-32.png" alt="XXD Panel 357 · 32 · An owl on a post"><br><sub>32 · An owl on a post</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-33.png" alt="XXD Panel 357 · 33 · Lone pine on a rock"><br><sub>33 · Lone pine on a rock</sub></td>
    <td width="50%"><img src="./assets/examples/sample-34.png" alt="XXD Panel 357 · 34 · An aloe plant"><br><sub>34 · An aloe plant</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-35.png" alt="XXD Panel 357 · 35 · A bottle"><br><sub>35 · A bottle</sub></td>
    <td width="50%"><img src="./assets/examples/sample-36.png" alt="XXD Panel 357 · 36 · Standing rain boots"><br><sub>36 · Standing rain boots</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-37.png" alt="XXD Panel 357 · 37 · Wooden ladder against a wall"><br><sub>37 · Wooden ladder against a wall</sub></td>
    <td width="50%"><img src="./assets/examples/sample-38.png" alt="XXD Panel 357 · 38 · Person in a coat"><br><sub>38 · Person in a coat</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-39.png" alt="XXD Panel 357 · 39 · A bunch of grapes"><br><sub>39 · A bunch of grapes</sub></td>
    <td width="50%"><img src="./assets/examples/sample-40.png" alt="XXD Panel 357 · 40 · Potted palm"><br><sub>40 · Potted palm</sub></td>
  </tr>
</table>

</details>

## Just say it

No parameters to memorise. Say what you want:

| You want | Say |
|---|---|
| Top–bottom comparison | Make a 3:4 top–bottom comparison |
| Left–right comparison | Make a 16:9 left–right comparison, photo on the left |
| Design only | Just the design, no photo, 9:16 portrait |
| A wallpaper set | Make matching wallpapers for phone, tablet, desktop and watch |
| Several ratios | Make this one at 1:1, 3:4 and 16:9 |
| Your own text | Use the title “Let the wind pass through” exactly as written |
| No text | No text at all |
| Text language | Write the text in Japanese |
| A whole folder | Turn every photo in this folder into a top–bottom comparison |
| Same as last time | Use my settings from last time |

Prefer the command line? The flags map one to one:

```text
/xxd-panel-357 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale en-US
/xxd-panel-357 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-357 ./photos --mode left-right --size 16:9 --text prompt --locale ja-JP
```

All flags are listed under [Parameters](#parameters).

## FAQ

**Does the original photo have to appear?** No. Ask for “design only” or a wallpaper set and the whole canvas is design.

**Who writes the text?** By default the image model writes it from your photo; you only choose the language. Give your own words and they are used exactly; or ask for no text. Anything that looks factual (places, dates, numbers) comes only from you or from what is visible in the photo, never invented.

**What if I don't like the result?** Say “one more”. It redraws from the original photo instead of editing the last result, so every attempt is different.

**Do photos in a batch mix together?** No. Each photo is generated on its own and never borrows another photo's colours, text or layout. Settings are asked once for the whole batch.

**Where do my photos go?** Only to the image model your agent uses. The Skill uploads nothing elsewhere and never prints endpoints or keys.

**How does this relate to other Panels?** XXD Panels are a family of styles, one per number, fully independent; install only the ones you like. To have AI recommend a style for a photo, or compare several at once, use the catalog [xxd-panel-all](https://github.com/nevertoday/xxd-panel-all).

## Original prompt

This style is defined entirely by Xiaoxiaodong's [original prompt](references/original-prompt/zh-CN.md) (in Chinese). The Skill only appends the layout, size and text settings you choose; it never summarises, translates or rewrites the prompt.

Reading translations (for reading only; never sent to the image model): [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## Setting up image generation

You need an OpenAI-compatible API that serves `gpt-image-2` (or a compatible model) and its API key. This creates a separate config and leaves your Codex settings alone:

```bash
mkdir -p ~/.xxd-imagegen
cat > ~/.xxd-imagegen/config.toml <<'EOF'
model_provider = "image"

[model_providers.image]
base_url = "https://api.openai.com/v1"   # or your compatible endpoint
env_key = "XXD_IMAGE_API_KEY"
EOF

# add to ~/.zshrc or ~/.bashrc so your agent can read them
echo 'export XXD_IMAGEGEN_CODEX_DIR=~/.xxd-imagegen' >> ~/.zshrc
echo 'export XXD_IMAGE_API_KEY=your-key' >> ~/.zshrc
```

Reopen your terminal and agent, then check once from this Skill's folder:

```bash
python3 scripts/configured_imagegen.py probe
```

`"ok":true` means it works. The check only reports readiness; it never prints the endpoint or key. If your Codex already generates images through a compatible API, skip this step.

## Parameters

| Flag | Values |
|---|---|
| `--mode` | `top-bottom` · `left-right` · `design-only` · `wallpaper-pack` (phone, tablet, desktop, watch); combine freely |
| `--size` | `auto` recommended · `source` match the photo · `1:1` `3:4` `4:3` `4:5` `5:4` `2:3` `3:2` `9:16` `16:9` `21:9` `5:7` `7:5` · exact pixels such as `2160x3840`; combine freely |
| `--text` | `prompt` written from the photo · `exact` your words (with `--copy "…"`) · `none` no text |
| `--locale` | text language, e.g. `zh-CN` `en-US` `ja-JP` `ko-KR` `ar` |
| `--wallpaper` | `linked` a matching set · `independent` four separate designs |
| `--wallpaper-size` | device pixels, e.g. `phone=1440x3200,desktop=3840x2160` |
| `--out` | another output root (default `~/Desktop/xxd/xxd-panel-357/`) |
| `--prefs` | `last` reuse · `edit` start from last time · `new` choose again · `off` don't remember this time · `clear` forget |

- With every value given, nothing is asked; otherwise only the missing values are. Pass a folder instead of `photo.jpg` to batch.
- Combinations are generated one by one: 2 modes × 3 sizes = 6 images, each composed for its own canvas rather than cropped.
- Comparisons are exactly 50:50. Usually the model paints only the design half and a script places the untouched photo beside it, so the split is centred and the photo is unchanged.
- Files are named like `source-001-street-top-bottom-3x4-1152x1536.png`, all in one flat task folder.
- Only layout, size, text mode and language are remembered, never photos, copy or keys.

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Xiaoxiaodong multi-platform membership · CNY 699/year

> **Advertising disclosure:** The QR code, membership, and paid-service links below are XXD promotional information. Scanning or purchasing is entirely optional and does not affect access to this project.

One annual membership unlocks three benefits together: **Knowledge Planet + the XXD Member Prompt Library + membership for all General Skills**. They are included in one membership; no separate purchase is required.

<!-- xxd-panel-command-system:start -->

### How the Skills work together

| Level | Included | What it does |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detects available numbered Skills, recommends them by image, theme, or use, and organizes multi-style and batch tasks. |
| **Soldier** | `xxd-panel-NNN` | Each numbered Skill follows its own original brief and aesthetic to complete the specific task assigned by the General. |

<!-- xxd-panel-command-system:end -->

### What you receive

1. **One-to-one WeChat AI learning and project support**
   Add Xiaoxiaodong on WeChat via the QR code below to discuss AI learning, tools, and real projects one to one, with practical guidance and answers. Representative questions may be organized into member resources.
2. **A growing member prompt library**
   The [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) currently contains about 32,000 prompts and will keep expanding, with a goal of exceeding 100,000.
3. **All General Skills and usage support**
   One membership covers every General Skill, with usage guidance and Q&A when you need help.
4. **Priority for high-need requests**
   Frequently requested, high-need prompts and Skills are reviewed and developed first where appropriate.

### How to join

- [Activate membership on the member website](https://vip.xiaoxiaodong.ai/).
- Or scan the QR code below to add Xiaoxiaodong on WeChat for one-to-one activation support.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Contact Xiaoxiaodong" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## License

**Free for noncommercial use; commercial use needs separate permission.** This project (Skill, original prompts, scripts and documentation) is licensed under [PolyForm Noncommercial 1.0.0](LICENSE). The source is public, but it is not open source as the OSI defines it.

- **Free:** personal study and hobby work; making images from your own photos to keep or share on your personal accounts (not ads, sponsored posts or product promotion); noncommercial changes and redistribution with the LICENSE included.
- **Commercial use by individuals needs permission:** paid client work, ads and product promotion, small-batch merchandise, paid courses or communities. Usually granted, as the author confirms in writing.
- **Organisations must sign an agreement:** any commercial use by a company, studio, MCN or brand, internal use included, and any integration into an app, website, SaaS or API.
- **Not licensed:** reselling, renaming or repackaging the Skills, prompts or samples.
- The Xiaoxiaodong membership does not include a commercial licence. The original photos in the samples belong to their photographers and are shown for demonstration only.

To apply, add Xiaoxiaodong on WeChat and write "commercial licence". Full terms and the QR code: [Commercial licensing](COMMERCIAL.md).
