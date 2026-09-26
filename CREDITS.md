# Credits and licences

## 3D characters: KayKit by Kay Lousberg (www.kaylousberg.com), CC0 1.0

Downloaded 2026-09-26 from Kay Lousberg's official GitHub account (github.com/KayKit-Game-Assets; its profile links to kaylousberg.com, and the READMEs link to kaylousberg.itch.io). There was no account, login, payment or donation prompt.

| Pack | Source (repo @ commit) | Licence file | Files used |
|---|---|---|---|
| KayKit Character Pack: Adventurers 1.0 | https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Adventures-1.0 @ 672074b73ba2 | `assets/kaykit/adventurers/LICENSE.txt` (repo root LICENSE.txt): "License: (Creative Commons Zero, CC0)" | Barbarian, Knight, Mage, Rogue, Rogue_Hooded (.glb, from `addons/kaykit_character_pack_adventures/Characters/gltf/`) + their textures |
| KayKit Character Pack: Skeletons 1.0 | https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Skeletons-1.0 @ 15b62b9bad12 | `assets/kaykit/skeletons/LICENSE.txt` (repo root LICENSE.txt): "License: (Creative Commons Zero, CC0)" | Skeleton_Mage, Skeleton_Minion, Skeleton_Rogue, Skeleton_Warrior (.glb, from `addons/kaykit_character_pack_skeletons/Characters/gltf/`) + skeleton_texture.png |

Attribution is not required by CC0; we credit Kay Lousberg anyway, as the licence asks.

SHA-256 of the downloaded files:
```
cefc311a0e10c7858b6141f5ada7e33268727564fb8ac1347aab97d000669cc6  adventurers/Barbarian.glb
60428e3abc09ba83e595d256e3af8c5c976b46cdae599f0802fc82b4a3445168  adventurers/Knight.glb
cf898585da33fab50c724d31605fb931eb2912e6d2280092141e98ca81ad507d  adventurers/Mage.glb
e825437cd4d2ee9c1960b517a74a69101e33eb409ae7fa8cedc7134a998fbb7d  adventurers/Rogue.glb
93e6e25213009952276d9cf34f5d96a243767334c66f280db0433ddfabb91545  adventurers/Rogue_Hooded.glb
e05b0f5cfa395271c9f75fd07c0a0613c56f401ece4ab644e080001a79971075  skeletons/Skeleton_Mage.glb
6ffc003f895bed0b074791e0e490846210a2e2f8fc7da300aba53cc185f95968  skeletons/Skeleton_Minion.glb
4003f2b77891bb56f7e0de7d555abcb497aebbcaee35b614211f16275f9ccae3  skeletons/Skeleton_Rogue.glb
178b6fda810b814c250d8a2010c24dfd9b458b9006dd323353e620b7ff118bbe  skeletons/Skeleton_Warrior.glb
```

## Engine

Godot Engine 4.7.2-stable, MIT licence (godotengine.org/license). No plugins or GDExtensions are used.

The web build ships the engine's own licence texts next to `index.html`, generated from the engine binary itself
(`Engine.get_license_text()`, `Engine.get_copyright_info()`, `Engine.get_license_info()`):

- `GODOT-LICENSE.txt`: the Godot Engine MIT licence and copyright.
- `GODOT-THIRD-PARTY-NOTICES.txt`: Godot's COPYRIGHT list (every bundled third-party component, its files,
  copyright holders and licence) followed by the full text of each of those licences.

## Other visuals

- Weapon models: the thrown axes reuse the `1H_Axe` mesh inside KayKit's `Barbarian.glb` (credited above).
- Shade the spirit panther, the orbs, daggers, bolts, glaives, lightning, embers, slashes and rings are built in
  code from Godot primitive meshes and shaders. No other assets are used.
