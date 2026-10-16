# Pawn Shop Kit: Interactive Fixtures, Props & Room (v0.9)

**65 game-ready prefabs** for shop and job simulators: 47 unique models plus 18 colour variants.

That covers 35 fixtures and props, plus a 12-piece modular room to put them in.

Every door, drawer, lid and dial:
- is its own object
- is pivoted where it actually moves
- has a collider that follows it

The pickup props carry their mass, ready for physics carry systems.
Tested on import in **Unity 6, Godot 4.7 and Blender 5.2**.

## Fixtures
Origin: floor, back-centre, so each one snaps flush against a wall.

| Asset | Size (W×D×H) | Moving parts | Variants |
|---|---|---|---|
| `SM_PawnCounter_A` | 150 × 60 × 95 cm | 2 sliding glass doors (staff side) | `_B` walnut / navy felt |
| `SM_FloorSafe_A` | 63 × 67 × 85 cm | hinged door with bolt work, spinning dial, turning handle | `_B` black, `_C` grey |
| `SM_CashRegister_A` | 40 × 43 × 36 cm | sliding cash drawer | `_B` black |
| `SM_DisplayCabinet_A` | 90 × 47 × 190 cm | 2 hinged glass doors, drawer | `_B` gloss black |
| `SM_OfficeDesk_A` | 120 × 61 × 75 cm | 3 sliding drawers | |
| `SM_WallShelf_A` | 100 × 35 × 200 cm | none (5 shelves) | |
| `SM_Pegboard_A` | 120 × 15 × 90 cm | none (hooks line up with the holes; 2 guitar hangers) | |

## Props
Origin: bottom-centre. Every prop has `pickup` and `mass_kg` metadata.

| Asset | Size (W×D×H) | Mass | Moving parts | Variants |
|---|---|---|---|---|
| `SM_RingBox_A` | 6.5 × 6 × 5.2 cm | 0.09 kg | hinged lid | `_B` red velvet |
| `SM_CashBox_A` | 30 × 24.5 × 11.7 cm | 1.6 kg | hinged lid | `_B` blue, `_C` grey |
| `SM_Toolbox_A` | 48 × 22.5 × 24 cm | 4.5 kg | hinged lid | `_B` red |
| `SM_JewelryCase_A` | 50 × 30.5 × 15.4 cm | 5 kg | hinged glass lid | |
| `SM_Laptop_A` | 32 × 22 × 2.3 cm | 1.6 kg | hinged lid | |
| `SM_VCR_A` | 36 × 27.3 × 9.8 cm | 3.5 kg | hinged cassette flap | |
| `SM_RecordPlayer_A` | 42 × 35 × 16 cm | 6 kg | spinning platter, hinged dust cover | `_B` black |
| `SM_BoomBox_A` | 50 × 15 × 58 cm (with antenna) | 4 kg | hinged cassette door | |
| `SM_GuitarCase_A` | 44 × 106 × 12 cm | 4.5 kg | hinged lid (the electric guitars fit inside) | `_B` brown leather |
| `SM_ElectricGuitar_A` | 35 × 6.8 × 99 cm | 3.6 kg | none | `_B` black, `_C` ocean blue, `_D` tobacco |
| `SM_AcousticGuitar_A` | 39 × 12.6 × 96 cm | 2.2 kg | none | |
| `SM_GuitarAmp_A` | 49 × 29 × 44 cm | 14 kg | none | |
| `SM_CRT_TV_A` | 50 × 44 × 71 cm (with antenna) | 12 kg | none | |
| `SM_GameConsole_A` | 30 × 26 × 6.5 cm | 3.2 kg | none | |
| `SM_Gamepad_A` | 16 × 10 × 3.5 cm | 0.25 kg | none | |
| `SM_Smartphone_A` | 7.2 × 14.7 × 0.8 cm | 0.19 kg | none | |
| `SM_VintageCamera_A` | 14.6 × 10.5 × 11.8 cm | 0.75 kg | none | |
| `SM_PowerDrill_A` | 28.6 × 8.6 × 24.5 cm | 1.8 kg | none | |
| `SM_Watch_A` | 4.1 × 21.6 × 1.5 cm | 0.12 kg | none | |
| `SM_Necklace_A` | 15.7 × 14.5 × 0.9 cm | 0.03 kg | none | |
| `SM_Bangle_A` | 7.1 × 7.1 × 0.7 cm | 0.04 kg | none | |
| `SM_Ring_A` | 2.6 × 2.2 × 0.6 cm | 0.005 kg | none | |
| `SM_RingTray_A` | 24 × 14 × 2.5 cm | 0.35 kg | none (3 ring slots) | |
| `SM_NecklaceStand_A` | 21.6 × 12.8 × 29.7 cm | 0.5 kg | none | |
| `SM_Sunglasses_A` | 13.8 × 15.1 × 4 cm | 0.03 kg | none | |
| `SM_GoldBar_A` | 8 × 4 × 1.9 cm | 1.0 kg | none | |
| `SM_CashStack_A` | 15.6 × 6.9 × 2 cm | 0.2 kg | none | |
| `SM_PriceTag_A` | 8.6 × 3.3 × 0.1 cm | 0.002 kg | none | |

## Modular room
The room pieces snap on a **2 m grid**. Walls are 3 m high and 15 cm thick.

**Origins:**
- **Walls:** floor level, centre of the span, on the interior face. The wall extends behind the origin, so fixtures placed on the same line sit flush against it.
- **Floor and ceiling:** centre of the tile, on the walkable or visible surface.
- **Lights:** the ceiling mounting point; the geometry hangs below it.
- **Signs and the grille:** floor or mounting line, back-centre, like the fixtures.

| Asset | Size (W×D×H) | Moving parts | Variants |
|---|---|---|---|
| `SM_Wall_2m_A` | 200 × 16 × 300 cm | none (baseboard included) | `_B` sage green |
| `SM_Wall_2m_Window_A` | 200 × 20 × 300 cm | none (barred window, 120 × 120 cm) | `_B` sage green |
| `SM_Wall_2m_Door_A` | 200 × 21 × 300 cm | glass shop door swinging inward, shop bell | `_B` sage green |
| `SM_Wall_Corner_A` | 15 × 15 × 300 cm | none (closes outside corners) | |
| `SM_Floor_2m_A` | 200 × 200 × 2 cm | none (checker tiles) | `_B` oak planks |
| `SM_Ceiling_2m_A` | 200 × 200 × 2 cm | none (acoustic tiles) | |
| `SM_SecurityGrille_A` | 205 × 8 × 225 cm | sliding grille panel on a track | |
| `SM_Sign_Open_A` | 60 × 2 × 45 cm | none (emissive neon) | |
| `SM_Sign_WeBuyGold_A` | 120 × 4 × 40 cm | none | |
| `SM_Sign_PawnShop_A` | 200 × 5 × 50 cm | none | |
| `SM_CeilingLight_Panel_A` | 120 × 60 × 8 cm | none (emissive panel) | |
| `SM_PendantLight_A` | 36 × 36 × 96 cm | none (emissive bulb) | |

The emissive materials only glow. Add your own engine lights next to the light fittings and neon sign.

The sign lettering is Blender's built-in font converted to mesh, so no font files are shipped.

`manifest.json` lists exact sizes, triangle counts (12 to ~9.5k per model), materials, colliders and per-part metadata.

## Textures
- 53 materials: 47 textured PBR sets plus 6 flat emissive materials (neon, LEDs, bulbs). 46 of the sets are **seamless 1 m × 1 m tiles at 1024 px/m**; the 47th is the printed face of the kit's fictional banknote (marked "PROP MONEY - NOT LEGAL TENDER"), mapped across one note.
- Every mesh uses box-projected UV0 at 1 unit = 1 m, so texel density matches across the whole kit and you can swap any material without re-unwrapping.
- Wood grain and brushed-metal streaks run along the length of each panel.
- Each material ships as `Textures/T_<Name>_*.png`:

| Map | Use |
|---|---|
| `BaseColor` | sRGB albedo |
| `Normal` | OpenGL / Y+ (Unity, Godot, Blender) |
| `Normal_DX` | DirectX / Y− (Unreal) |
| `Roughness` | linear greyscale |
| `MetallicSmoothness` | Unity Standard / URP Lit (R = metallic, A = smoothness) |
| `ORM` | Unreal (R = AO, G = roughness, B = metallic) |

The GLBs embed their textures. The FBXs reference `Textures/` by relative path.

## Conventions
- **Scale and facing:** real-world metres. The front faces +Z in Unity and Godot (−Y in Blender).
- **Moving parts:** child objects whose origin is the pivot (hinge line, slide start or spin centre). The closed pose is the import pose.
- **Part metadata** (FBX user properties / glTF extras):
  - `interaction`: `slide`, `hinge` or `spin`
  - `amount`: metres or degrees
  - `axis_unity` / `axis_godot`: the axis in the parent's space, sign-adjusted for that engine
- **Root metadata:** props carry `pickup = true` and `mass_kg`. Colour variants carry `variant_of` and `finish`.
- **FBX hierarchy is flat:** every part is a direct child of the root. Parts that belong under another part (for example the safe dial on the door) carry `attach_to = <parent name>`. The Unity postprocessor re-parents them automatically; in Unreal, attach them in your Blueprint. The GLB keeps the real nesting.
- **Colliders:**
  - FBX: `UCX_<mesh>_NN` boxes. Unreal picks these up automatically; in Unity the included postprocessor converts them.
  - GLB: `-convcolonly` nodes, which Godot turns into collision shapes.
  - Cabinets, cases, drawers and boxes are hollow, so items can be placed inside.
- **Second UV set:** UV1 holds non-overlapping lightmap UVs.
- **LODs:** models over 3,000 triangles ship two lighter levels in the FBX. Each mesh has decimated children `<mesh>_LOD1` (50%) and `<mesh>_LOD2` (20%), so moving parts keep their LODs. Unity gets a ready-made `LODGroup`. The GLBs leave them out, because Godot generates mesh LODs itself on import. `manifest.json` lists the triangles per level (`lod_triangles`).

## Unity
Import `PawnShopKit.unitypackage` (Unity 6 or newer). Use **Linear** colour space (the Unity 6 default).

| Folder | Contents |
|---|---|
| `Prefabs/Fixtures`, `Prefabs/Props`, `Prefabs/Room` | one prefab per model; colour variants in `Variants/` subfolders |
| `Models` | the FBX files |
| `Materials`, `Textures` | Built-in Standard materials (BaseColor, Normal, MetallicSmoothness) |
| `Scripts` | `PropInteractable`, `PropInfo`, the import postprocessor, the material converter and the demo player |
| `Demo/PawnShop_Demo.unity` | a walk-in pawn shop and back office built from the kit, using all 65 prefabs |

**Demo controls:**
- **WASD** to move and the **mouse** to look; hold **C** or **Left Ctrl** to crouch for the low shelves.
- **E** opens or closes the door, drawer or lid under the crosshair.
- **Click** picks up a prop; click again to drop it (it falls with its real mass), or aim at a holder to put it back in.
- **Esc** frees the cursor.

**Demo performance:** everything that never moves is marked static, so it is batched and occlusion-culled: the back office isn't drawn while you're in the shop. Only three lights cast shadows: the window daylight, the pendant over the counter and the office panel. Heavy models switch to their LODs with distance. Frame rates in the editor's Play mode run lower than in a build, especially with the Scene view open beside the Game view.

**Render pipelines:**
- **Built-in:** works as imported.
- **URP:** run **Tools > Pawn Shop Kit > Convert Materials to URP**, or use Unity's **Window > Rendering > Render Pipeline Converter**.
- **HDRP:** use Unity's HDRP material converter.

**In your own code:**
- Every moving part has a `PropInteractable`. Call `Toggle()` from your interaction raycast; `SetOpenAmount(0..1)` works for drag-to-open, including in edit mode.
- Holders (`PropContainer` on the ring tray, guitar cases, pegboard hangers, necklace stand, jewellery case, cash boxes and toolboxes) carry what's inside them and take items back: rings snap into tray slots, electric guitars go into the case or back onto the pegboard, and a necklace put on the stand drapes around the bust. Call `TryPlace(item, aimPoint, aimNormal, yaw)` to put an item in and `Detach(item)` to take it out.
- `SM_Necklace_A` has a second, hidden pose, `SM_Necklace_A_Draped`, which is the chain worn on `SM_NecklaceStand_A` with the necklace's origin at the stand's origin. The holder switches between the two poses automatically. In Godot, set that node's `visible` yourself.
- Every model root has a `PropInfo` with `category`, `pickup`, `massKg`, `variantOf` and `finish`. `PropInfo.EnsureRigidbody()` adds a Rigidbody with the right mass.
- The cash register's customer display is blank in the model. `RegisterDisplay` writes text on it: `WELCOME` by default, `NO SALE` while the drawer is open, or whatever you pass to `Show("19.99")` (call `ClearOverride()` to go back). It uses Unity's built-in font, so it needs no extra packages.
- Heavy models get a `LODGroup` on import, with levels at 35%, 12% and 1.5% of screen height. Change it on the prefab if you want different distances.
- `UCX_*` meshes become BoxColliders, and nested parts are re-parented on import. This applies to any kit FBX imported into a folder whose path contains `PawnShopKit`.

To use the raw FBX files from the download without the package, copy `Engine/Unity` into your project and import the FBXs and `Textures` into a `PawnShopKit` folder.

## Godot 4 (GLB)
1. Copy `Engine/Godot` into your project.
2. Select the `.glb` files. In the Import dock, set **Import Script** to `prop_kit_import.gd`, then click **Reimport**.
3. Moving parts get `prop_interactable.gd`. Call `toggle()` or `set_open_amount()` on them.
4. Prop metadata (`pickup`, `mass_kg`, `variant_of`...) is available via `get_meta("extras")` on the instanced scene's root.
5. LODs: leave **Meshes > Generate LODs** on (the default). Godot builds mesh LODs automatically.

## Unreal (FBX)
*Not yet tested in Unreal.*
1. Import with **Combine Meshes** off. Each part becomes its own Static Mesh, and the `UCX_` collision is attached automatically.
2. Build a material from `BaseColor`, `Normal_DX` and `ORM`.
3. Rebuild the hierarchy in a Blueprint, using the `attach_to` values.
4. Drive the moving parts with a Timeline using the `amount` values from `manifest.json`. Unreal axes: front = −Y, so drawers slide along −Y.
5. The `_LOD1` / `_LOD2` meshes import as separate Static Meshes. Either delete them and use Unreal's auto-LOD (Nanite or **LOD Settings > Number of LODs**), or import them as LODs of their base mesh.
