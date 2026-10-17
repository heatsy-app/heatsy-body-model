# Manifest

Heatsy 1.0 (build 1). The same data in machine-readable form is in `manifest.json`.

| File | Bytes | SHA-256 | Origin | Licence |
|---|---:|---|---|---|
| `model/body_superficial.app5m.glb` | 4,357,304 | `ce9859de013c2ee9713dbe3158275208b57be1b4ff31957eca87195b991c0ab1` | Adapted from Z-Anatomy, which is derived from BodyParts3D. The app's `body.hbody`, `body_f.hbody` and `body_f_home.hbody` are baked from this mesh. | CC BY-SA 4.0 |
| `data/muscles.json` | 51,635 | `da930e89dd70ac65b2a960df3bf20321898a5171716400a14dc620e6dedc9883` | DDDEV LTD: vocabulary that decodes `_PART_ID` | CC BY-SA 4.0 |
| `data/za_map.json` | 8,109 | `3a7466ea3537854db373364060f3428c3d1d22df683d1c4065a09519ade498af` | DDDEV LTD: map from each part to its Z-Anatomy objects | CC BY-SA 4.0 |
| `LICENSE` | 20,138 | `28a9529c7d0bb4dc51f4bf5c116a3d16ef247a052f7591466768ddf563fd1cf5` | creativecommons.org legalcode.txt | Licence text |

## Not included

- The heads used in the app. They come from a third-party commercial asset that is not licensed under CC BY-SA.
- The app's `.hbody` files, because they contain those heads.
- Animations (`.hclip`), equipment (`.heq`), skins, framing and face-animation data. These are the app's own content and are not adaptations of the model's geometry.
