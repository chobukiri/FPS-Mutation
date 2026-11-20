# 🧬 Subject 7: Escape From Mutation (Unreal Engine 5)

A three-level third-person action-survival game built in **Unreal Engine 5** (Blueprints) by a five-member development team. Players navigate a mutated underground laboratory, manage health and combat resources, fight hostile mutants with firearm mechanics, and survive a multi-stage boss encounter to escape.

---

## ✨ Core Gameplay & Systems
* **Three-Level Progression:** Structured escape sequence spanning underground laboratory and facility maps (`Content/Maps/`, `Content/Level3/`, `Content/ThirdPerson/`).
* **Combat & Firearm Mechanics:** Third-person shooting, enemy encounters, and boss combat logic built with Unreal Engine Blueprints (`Content/Blueprints/`, `Content/Input/`).
* **Health & Survival Systems:** Player and boss health bar UI paired with collectible recovery items (`Content/FirstAidKit/`).
* **Cutscenes & Character Setup:** Integrated in-game video sequences and playable/enemy character assets (`Content/Movies/`, `Content/Characters/`).

## 🛠️ Tech Stack
* **Engine:** Unreal Engine 5
* **Scripting:** UE5 Blueprints
* **Version Control:** Git & Git LFS (tracking `.uasset`, `.umap`, `.fbx`, `.png`, `.wav`, and `.mp4`)

## 📂 Repository Structure
```text
├── Assignment2.uproject         # Unreal Engine project file
├── Config/                      # Engine, input, and game configuration
└── Content/
    ├── Blueprints/              # Core gameplay & combat Blueprints
    ├── Characters/              # Character assets and animations
    ├── FirstAidKit/             # Health pickup mechanics & assets
    ├── Input/                   # Enhanced Input actions & mappings
    ├── Level3/                  # Level 3 gameplay assets
    ├── Maps/                    # Game level maps
    ├── Movies/                  # Cutscene & intro media files
    ├── ShiJun/                  # Individual contributor modules
    ├── Z_Weiping/               # Individual contributor modules
    └── ThirdPerson/             # Player controller & map actors
```

## 📦 Prerequisites (Excluded Third-Party Asset Packs)
To respect third-party licensing terms and keep repository size manageable, unmodified Unreal Marketplace / Fab asset packs are excluded via `.gitignore`. To open the project with all environment meshes and character models intact, add the following packs into `Content/` via the Epic Games Launcher / Fab:

* `WW2City`
* `ParagonRampage`
* `ParagonGrux`
* `ParagonTwinblast`
* `Sewers`
* `Underground`
* `UndergroundFacility`
* `Sewerage`

## 🚀 Running Locally
1. Install **Git LFS** and clone the repository:
   ```bash
   git lfs install
   git clone [https://github.com/chobukiri/FPS-Mutation.git](https://github.com/chobukiri/FPS-Mutation.git)
   ```
2. Add the required Fab/Marketplace asset packs listed above into the `Content/` directory.
3. Double-click **`Assignment2.uproject`** to open in Unreal Engine 5 (the engine will automatically regenerate `Intermediate/`, `Saved/`, and `DerivedDataCache/` on first launch).

## 📸 Gameplay Previews
*(Add gameplay screenshots, level captures, or a short boss-fight demo GIF here.)*