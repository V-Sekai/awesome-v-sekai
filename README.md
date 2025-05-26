# **Awesome V-Sekai**

A curated list of awesome V-Sekai projects, tools, and resources, with a focus on its Godot Engine ecosystem. V-Sekai (pronounced vee-say-kai) aims to bring FOSS social VR/VRSNS/metaverse components to [Godot Engine](https://godotengine.org).

## **Contents**

* [Core Engine & Game Client](#bookmark=id.whx4brb07kou)  
* [Engine Components & Core Modifications](#bookmark=id.a0wdtj2196qc)  
* [Godot 4 Modules (C++)](#bookmark=id.76gwm6aytyrb)  
* [Godot 4.x Addons (GDScript & GDExtensions)](#bookmark=id.sq7nkdjut0x9)  
* [Interoperability & Importers](#bookmark=id.55sc9h5o1mne)  
* [VR/XR Tools & Systems](#bookmark=id.ot3izxxgafb6)  
* [Developer & Build Tools](#bookmark=id.pxa0upq26uda)  
* [Asset Libraries & Demos](#bookmark=id.5kxi1geedvw6)  
* [Artwork](#bookmark=id.ghcb3dryxeb4)  
* [Affiliated Projects](#bookmark=id.f3nbtg22thud)  
* [Other Tools](#bookmark=id.azo6gt6avgde)  
* [Tools that bring me joy](#bookmark=id.431q8pb8lh6r)  
* [Websites & Community](#bookmark=id.er91mcv6zn11)  
* [Groups](#bookmark=id.nhzfqqyv1w3z)  
* [Machine Learning experiments](#bookmark=id.kcuji8w3fng2)  
* [Other Awesome Lists](#bookmark=id.bgue5v9iw9j5)  
* [Contributing](#bookmark=id.95n77lt2uaq)

## **Core Engine & Game Client**

* [V-Sekai/godot](https://github.com/V-Sekai/godot) \- V-Sekai's fork of the Godot Engine – Multi-platform 2D and 3D game engine. (C++, Tailored for V-Sekai social VR features, target of V-Sekai/merge)  
* [v-sekai-game](https://github.com/V-Sekai/v-sekai-game) \- Open-source VR socials, the main V-Sekai application. (GDScript)  
* [world-godot](https://github.com/V-Sekai/world-godot) \- V-Sekai Godot Engine build and map editor. (C++, C\#, etc.)  
* [V-Sekai Uro Online Services](https://github.com/V-Sekai/uro/issues/new/choose) \- Online services infrastructure for V-Sekai.

## **Engine Components & Core Modifications**

*This section includes modules deeply integrated into V-Sekai's custom Godot Engine build.*

* [godot-goal-task-planner](https://github.com/V-Sekai/godot-goal-task-planner) \- Determines a PlannerPlan to accomplish a "todo list" from a provided state. (C++, C, Python, AI Planning) 
* [godot-speech](https://github.com/V-Sekai/godot-speech) \- Speech processor and compressor addon for Godot. (C++, Fork of SaracenOne/godot\_speech)  
* [lasso](https://github.com/V-Sekai/lasso) \- A custom Godot Engine module designed to make the task of selecting objects in VR easier. (C++, C, Python)  
* [godot\_openxr\_vendors](https://github.com/V-Sekai/godot_openxr_vendors) \- Godot 4 wrapper for OpenXR vendors loaders and extensions. (C++, fork of GodotVR/godot\_openxr\_vendors)  
* [libgodot\_project](https://github.com/V-Sekai/libgodot_project) \- Project related to LibGodot for embedding Godot. (C++. See also elixir-libgodot)  
* [godot-vsk-sqlite](https://github.com/V-Sekai/godot-vsk-sqlite) \- SQLite integration for Godot. (C++, C, Python, Module/GDExtension)  
* [Fast Subdivision with opensubdiv](https://github.com/V-Sekai/godot-subdiv) \- (C++)  
* [Inverse Kinematics System Solver for Multi-chain Skeletons and with Constraints](https://github.com/V-Sekai/many_bone_ik) \- (C++)  
* [Humanoid Inverse Kinematics Rig for Avatars (RenIK)](https://github.com/V-Sekai/renik) \- (C++)

## **Godot 4 Modules (C++)**

*Typically C++ based, extending core engine functionality, often as GDExtensions or engine modules not necessarily merged into the core V-Sekai build by default.*

* [Running Pre-trained Machine Learning Model in Godot (IREE.gd)](https://github.com/iree-gd/iree.gd) 
* [In-editor scripting and sandboxing for Godot (libriscv)](https://github.com/libriscv/godot-sandbox)  
* [Realtime Retarget](https://github.com/TokageItLab/realtime_retarget)  
* [Hydro \- Dynamic water and buoyancy](https://github.com/godot-extended-libraries/hydro)  
* [GuilhermeGSousa/godot-motion-matching](https://github.com/GuilhermeGSousa/godot-motion-matching)

## **Godot 4.x Addons (GDScript & GDExtensions)**

*Typically GDScript based or GDExtensions, enhancing editor or project capabilities.*

* [godot-humanoid](https://github.com/V-Sekai/godot-humanoid) \- Work in progress with humanoid muscle encoding to/from quaternion for animation/networking. (GDScript)  
* [godot-humanoid-project](https://github.com/V-Sekai/godot-humanoid-project) \- Project likely for humanoid avatar systems. (GDScript)  
* [godot-http-gltf2-binary](https://github.com/V-Sekai/godot-http-gltf2-binary) \- Godot Engine web server exporting the edited scene as a glTF2 binary. (GDScript)  
* [godot-whisper](https://github.com/V-Sekai/godot-whisper) \- GDExtension addon for Godot Engine that enables realtime audio transcription. (Metal, C++, GDScript, C)  
* [Godot Snappy for mesh snapping](https://github.com/jgillich/godot-snappy)  
* [Point Cloud Multistroke Recognizer](https://github.com/V-Sekai/godot-point-cloud-multistroke-recognizer)  
* [Godot Splerger to Split and Merge Godot Engine Scenes](https://github.com/V-Sekai/godot-splerger)  
* [Verlet Rope Simulation](https://github.com/V-Sekai/godot-verlet-rope)  
* [In-editor box modelling for gray boxing or prototyping 3d levels (Godot Ply).](https://github.com/jarneson/godot-ply)  
* [AndreaCatania/godot\_tracy: provides visibility into Godot Engine performance](https://github.com/AndreaCatania/godot_tracy)  
* [Humanizer converts MPFB2 to Godot 4](https://github.com/NitroxNova/humanizer)

## **Interoperability & Importers**

* [unidot\_importer](https://github.com/V-Sekai/unidot_importer) \- Import .unitypackage and other assets designed for Unity Engine as a GDScript addon for vanilla Godot 4.x.  
* [godot-vrm](https://github.com/V-Sekai/godot-vrm) \- Importer/Exporter for VRM avatars and MToon shader. (GDScript Addon, Godot Asset Library)  
  * [VRM for Portable Avatars Overview](https://github.com/fire/awesome-godot-procedural-generation/files/10690951/VRM.Overview.pdf)  

## **VR/XR Tools & Systems**

* [xr-grid](https://github.com/V-Sekai/xr-grid) \- A VR interaction tool. (GDScript, Shell, Python)  
* [interaction\_system](https://github.com/V-Sekai/interaction_system) \- Interaction system for immersive and XR games, using canvas\_plane and lasso. (GDScript)  
* [canvas\_plane](https://github.com/V-Sekai/canvas_plane) \- Helper class for creating 3D interactive UIs for VR in Godot. (GDScript)  
* [TOOL\_model\_explorer](https://github.com/V-Sekai/TOOL_model_explorer) \- View models, materials & animations. Supports .vrm, .glb, .gltf. (GDScript Tool/Application) (Previously VSK Model Explorer)  
* [XR Tunneling shader (Vignette)](https://github.com/V-Sekai/godot_xr_vignette)

## **Developer & Build Tools**

* [merge](https://github.com/V-Sekai/merge) \- Scripts for combining branches to create the "Godot Groups branch" (V-Sekai's custom Godot engine flavor via gitassembly-staging). (Shell, Just. *The exact list of repositories managed by gitassembly-staging is not publicly itemized in the file's content based on available information.*)  
* [elixir-libgodot](https://github.com/V-Sekai/elixir-libgodot) \- Elixir bindings or tools for LibGodot. (Elixir)

## **Asset Libraries & Demos**

* [avatar\_vr\_demo](https://github.com/V-Sekai/avatar_vr_demo) \- Minimalist test project for tuning VR player controllers and avatar IK. (GDScript)  
* [godot-vrm-test-bank](https://github.com/V-Sekai/godot-vrm-test-bank) \- Test assets for godot-vrm. (Asset files)  
* [sample-webrtc-signaling](https://github.com/V-Sekai/sample-webrtc-signaling) \- Demo of WebRTC signaling server and client for Godot, for multiplayer/social VR. (GDScript, JavaScript)

## **Artwork**

* [Blender Art Blue Tin Fox Models](https://github.com/V-Sekai/blender-art-blue-tin-fox-models)

## **Affiliated Projects**

### **V-Sekai Fire**

*(Artwork, Tools & Experiments from the V-Sekai-fire group)*

* [V-Sekai-fire GitHub Organization](https://github.com/v-sekai-fire) \- Main page for V-Sekai Fire projects.  
* [V-Sekai-fire/godot\_bird\_plane](https://github.com/V-Sekai-fire/godot_bird_plane) \- Godot project, likely a demo or tool. (GDScript, C++)  
* [V-Sekai-fire/godot-vrm-motion-checker](https://github.com/V-Sekai-fire/godot-vrm-motion-checker) \- Tool for checking VRM motions in Godot. (Likely GDScript)

## **Other Tools**

* [Magika ONNX Minimal File Type Prediction](https://github.com/trevorhobenshield/magika_onnx)  
* [Lottie](https://lottie.github.io/)  
* [SQLpage](https://github.com/lovasoa/SQLpage)  
* [V-Sekai Blender Game Tools](https://github.com/V-Sekai/vsekai-blender-game-tools)  
* [FBX2glTF FBX to GLTF Converter](https://github.com/godotengine/FBX2glTF)  
* [OpenVR driver for using VR controllers without an HMD](https://github.com/V-Sekai/V-Sekai-faceless)  
* [Differentiable Cloth Simulation](https://github.com/fire/differentiable_cloth)  
* [GLTF Extensions](https://github.com/omigroup/gltf-extensions)  
* [XMP StableDiffusion DataMapper](https://github.com/Zirnworks/XMP-StableDiffusion-DataMapper)  
* [Proton Graph](https://github.com/protongraph/protongraph)  
* [Nomad Sculpt](https://nomadsculpt.com/)  
* [Quadwild for quad-dominant re-meshing (with Bi-MDF)](https://github.com/cgg-bern/quadwild-bimdf)  
* [SystemAnimatorOnline](https://github.com/ButzYung/SystemAnimatorOnline)  
* [Tool to tokenize GPT input](https://tiktokenizer.vercel.app/)  
* [Lateral Thinking with Weathered Technology](https://en.wikipedia.org/wiki/Gunpei_Yokoi)  
* [Generate Blender Rigify armatures for VRM models.](https://github.com/nanoskript/vrm-rigify)  
* [Three VRM Inspector](https://0b5vr.com/three-vrm-inspector/)  
* [ultorg: A User Interface for Relational Data](https://www.ultorg.com/)  
* [Worldtime Buddy](https://www.worldtimebuddy.com/)  
* [Booth Avatars](https://boothplorer.com/avatars)  
* [Lazygit](https://github.com/jesseduffield/lazygit)  
* [Approximate Convex Decomposition for 3D Meshes](https://github.com/SarahWeiii/CoACD)  
* [Macroons: minimally-stateful bearer token, a blob signed with HMAC](https://fly.io/blog/macaroons-escalated-quickly/)

## **Tools that bring me joy**

* [Aurora appstore usable on the Meta Quest](https://auroraoss.com/)  
* [World Clock](https://www.timeanddate.com/worldclock/)  
* [Elk: Mastadon client](https://elk.zone)  
* [Libhunt: Shows trending GitHub repositories based on social media links](https://www.libhunt.com)  
* [Threadreaderapp: Provides pdf summaries of Twitter threads](https://threadreaderapp.com/)  
* [Rhino3d: CAD modeller with a visual procedural graph](https://www.rhino3d.com/)  
* [When2meet helps you find the best time for a group to get together](https://www.when2meet.com/)  
* [Hack for quick note-taking](https://hackmd.io/)  
* [Image comparison](https://imgsli.com)  
* [Code Name Generator: Colors, Metal, Animals](https://www.codenamegenerator.com/)  
* [Voice Changer Guide](https://rentry.co/VoiceChangerGuide)  
* [Sapling: A Scalable, User-Friendly Source Control System](https://github.com/facebook/sapling.git)  
* [Provide the user with inverse control over the hyper-parameters through a brush stroke metaphor](https://github.com/eliemichel/DagAmendment)  
* [Ultorg is a general-purpose database app that connects to your existing data. Work quickly across tables, queries, and relationships without manual coding or page design.](https://www.ultorg.com/) (Duplicate of ultorg above, consider keeping one)  
* [VRM Downgrader](https://vrm-downgrader.pages.dev/)  
* [Generate timestamp indicators for Discord chat messages](https://hammertime.cyou/)  
* [Discord timestamps](https://r.3v.fi/discord-timestamps/)

## **Websites & Community**

* [V-Sekai Website](https://v-sekai.org/) \- Official website.  
* [V-Sekai Discord](https://discord.gg/H3s3PD49XC) \- Main community chat.  
* [V-Sekai GitHub Organization](https://github.com/V-Sekai) \- Primary development hub.  
* [Coding for a Finite World](https://yoric.github.io/post/coding-for-a-finite-world/)  
* [How to atlas everything in your world](https://wiki.vrchat.com/wiki/How_to_Atlas_everything_in_your_World)  
* [V-Sekai Manuals Website](https://github.com/V-Sekai/manuals)  
* [Godot GLTF 2.0 Scene Exporter](https://godotengine.org/article/introducing-the-godot-gltf-2-0-scene-exporter/)  
* [Animation Retargeting in Godot 4.0](https://godotengine.org/article/animation-retargeting-in-godot-4-0/)  
* [Godot Engine PRs by File](https://godotengine.github.io/godot-prs-by-file/)  
* [Getty OpenContent CC0](https://www.getty.edu/art/collection/search?open_content=true)  
* [Shader Motion Website](https://github.com/V-Sekai/shader-motion-navy-lead-ostrich)  
* [A third-party item and avatar catalogue, primarily for VRChat, with items from BOOTH.pm and more](https://boothplorer.com/)  
* [BOOTH: Global Marketplace for Creative Endeavors](https://booth.pm/)

## **Groups**

* [Godot Engine](https://godotengine.org/teams)  
* [Open Metaverse Interoperability Group](https://omigroup.org)  
* [Khronos](https://www.khronos.org/)  
* [Polypixel: for low polygon art](https://github.com/recatek/polypixel-wiki/wiki)

## **Machine Learning experiments**

* [Microsoft PHI-3](https://huggingface.co/collections/microsoft/phi-3-6626e15e9585a200d2d761e3)  
* [MeshTransformer](https://github.com/lucidrains/meshgpt-pytorch/)  
* [SpaceMesh](https://research.nvidia.com/labs/toronto-ai/space-mesh/)  
* [together.ai Model training, fine-tuning, and inference](https://www.together.ai/)

## **Other Awesome Lists**

* [awesome-godot](https://github.com/godotengine/awesome-godot) \- A curated list of awesome Godot Engine frameworks, libraries, software and resources.  
* [Awesome Godot Scientific](https://github.com/Ivorforce/Awesome-Godot-Scientific)

## **Contributing**

Contributions are welcome\! 

When adding a new item, please try to include:

* A direct link to the repository or resource.  
* A concise description.  
* Relevant primary languages or technologies (e.g., GDScript, C++, GDExtension).  
* Any important notes, such as if it's a fork or its specific role in the V-Sekai ecosystem.

Let's make V-Sekai awesome together\!
