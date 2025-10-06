# **Awesome V-Sekai**

A curated list of awesome V-Sekai projects, tools, and resources, with a focus on its Godot Engine ecosystem. V-Sekai (pronounced vee-say-kai) aims to bring FOSS social VR/VRSNS/metaverse components to [Godot Engine](https://godotengine.org).

## **Contents**

* [Core Engine & Game Client](#bookmark=id.vxqcjaoda3mi)  
* [Engine Components & Core Modifications](#bookmark=id.dij5ppjwzui6)  
* [Godot 4 Modules (C++)](#bookmark=id.quzmdahlos6)  
* [Godot 4.x Addons (GDScript & GDExtensions)](#bookmark=id.acjpu4wjh8i)  
* [Interoperability & Importers](#bookmark=id.p48o6qtnqsm6)  
* [VR/XR Tools & Systems](#bookmark=id.gkdatykqa1gt)  
* [Developer & Build Tools](#bookmark=id.oera4xoh8k7l)  
* [Asset Libraries & Demos](#bookmark=id.rwwmx442pnwq)  
* [Artwork](#bookmark=id.nzlfkh2bmr6n)  
* [Affiliated Projects](#bookmark=id.8y5w7ct4ubx5)  
* [Other Tools](#bookmark=id.2xas5tpk50rf)  
* [Tools that bring me joy](#bookmark=id.cxkbudj91p2j)  
* [Websites & Community](#bookmark=id.vee5t243md83)  
* [Groups](#bookmark=id.fxhmdvdtt2z)  
* [Machine Learning experiments](#bookmark=id.xx64voqhro9)  
* [Other Awesome Lists](#bookmark=id.52l0nkcrv5bx)  
* [Contributing](#bookmark=id.7entg57ekap2)

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

* [Running Pre-trained Machine Learning Model in Godot (IREE.gd)](https://github.com/iree-gd/iree.gd) \- Module for integrating IREE (Intermediate Representation Execution Environment) with Godot, allowing execution of pre-trained ML models.  
* [In-editor scripting and sandboxing for Godot (libriscv)](https://github.com/libriscv/godot-sandbox) \- Provides a sandboxed RISC-V environment for in-editor scripting within Godot.  
* [Realtime Retarget](https://github.com/TokageItLab/realtime_retarget) \- A Godot module for retargeting animations in real-time.  
* [Hydro \- Dynamic water and buoyancy](https://github.com/godot-extended-libraries/hydro) \- A Godot module for simulating dynamic water and buoyancy effects.  
* [GuilhermeGSousa/godot-motion-matching](https://github.com/GuilhermeGSousa/godot-motion-matching) \- A Godot module implementing motion matching animation techniques.

## **Godot 4.x Addons (GDScript & GDExtensions)**

*Typically GDScript based or GDExtensions, enhancing editor or project capabilities.*

* [godot-humanoid](https://github.com/V-Sekai/godot-humanoid) \- Work in progress with humanoid muscle encoding to/from quaternion for animation/networking. (GDScript)  
* [godot-humanoid-project](https://github.com/V-Sekai/godot-humanoid-project) \- Project for humanoid avatar systems. (GDScript)  
* [godot-http-gltf2-binary](https://github.com/V-Sekai/godot-http-gltf2-binary) \- Godot Engine web server exporting the edited scene as a glTF2 binary. (GDScript)  
* [godot-whisper](https://github.com/V-Sekai/godot-whisper) \- GDExtension addon for Godot Engine that enables realtime audio transcription. (Metal, C++, GDScript, C)  
* [Godot Snappy for mesh snapping](https://github.com/jgillich/godot-snappy) \- An addon for Godot that provides mesh snapping functionalities.  
* [Point Cloud Multistroke Recognizer](https://github.com/V-Sekai/godot-point-cloud-multistroke-recognizer) \- A Godot addon for recognizing multistroke gestures from point cloud data.  
* [Godot Splerger to Split and Merge Godot Engine Scenes](https://github.com/V-Sekai/godot-splerger) \- An addon for splitting and merging Godot Engine scene files.  
* [Verlet Rope Simulation](https://github.com/V-Sekai/godot-verlet-rope) \- A Godot addon for simulating verlet rope physics.  
* [In-editor box modelling for gray boxing or prototyping 3d levels (Godot Ply).](https://github.com/jarneson/godot-ply) \- An addon that enables in-editor box modeling capabilities.  
* [AndreaCatania/godot\_tracy: provides visibility into Godot Engine performance](https://github.com/AndreaCatania/godot_tracy) \- A Godot integration for the Tracy profiler, offering detailed performance insights.  
* [Humanizer converts MPFB2 to Godot 4](https://github.com/NitroxNova/humanizer) \- An addon to convert MakeHuman Plugin for Blender (MPFB2) characters to be Godot 4 compatible.
* [Skeleton Merge Sample](https://github.com/V-Sekai-fire/SK_skeleton_merge_01) \- Allows merging two or more skeletons together. Like a base avatar and a clothing costume with a skeleton rigged.

## **Interoperability & Importers**

* [unidot\_importer](https://github.com/V-Sekai/unidot_importer) \- Import .unitypackage and other assets designed for Unity Engine as a GDScript addon for vanilla Godot 4.x.  
* [godot-vrm](https://github.com/V-Sekai/godot-vrm) \- Importer/Exporter for VRM avatars and MToon shader. (GDScript Addon, Godot Asset Library)  
  * [VRM for Portable Avatars Overview](https://github.com/fire/awesome-godot-procedural-generation/files/10690951/VRM.Overview.pdf) \- A document providing an overview of the VRM format for portable avatars.

## **VR/XR Tools & Systems**

* [xr-grid](https://github.com/V-Sekai/xr-grid) \- A VR interaction tool. (GDScript, Shell, Python)  
* [interaction\_system](https://github.com/V-Sekai/interaction_system) \- Interaction system for immersive and XR games, using canvas\_plane and lasso. (GDScript)  
* [canvas\_plane](https://github.com/V-Sekai/canvas_plane) \- Helper class for creating 3D interactive UIs for VR in Godot. (GDScript)  
* [TOOL\_model\_explorer](https://github.com/V-Sekai/TOOL_model_explorer) \- View models, materials & animations. Supports .vrm, .glb, .gltf. (GDScript Tool/Application)  
* [XR Tunneling shader (Vignette)](https://github.com/V-Sekai/godot_xr_vignette) \- A shader for Godot that implements XR tunneling (vignette) to reduce motion sickness.

## **Developer & Build Tools**

* [merge](https://github.com/V-Sekai/merge) \- Scripts for combining branches to create the "Godot Groups branch" (V-Sekai's custom Godot engine flavor via gitassembly-staging). (Shell, Just)  
* [elixir-libgodot](https://github.com/V-Sekai/elixir-libgodot) \- Elixir bindings or tools for LibGodot. (Elixir)

## **Asset Libraries & Demos**

* [avatar\_vr\_demo](https://github.com/V-Sekai/avatar_vr_demo) \- Minimalist test project for tuning VR player controllers and avatar IK. (GDScript)  
* [godot-vrm-test-bank](https://github.com/V-Sekai/godot-vrm-test-bank) \- Test assets for godot-vrm. (Asset files)  
* [sample-webrtc-signaling](https://github.com/V-Sekai/sample-webrtc-signaling) \- Demo of WebRTC signaling server and client for Godot, for multiplayer/social VR. (GDScript, JavaScript)

## **Artwork**

* [Blender Art Blue Tin Fox Models](https://github.com/V-Sekai/blender-art-blue-tin-fox-models) \- A repository of Blender art assets, specifically Blue Tin Fox models.

## **Affiliated Projects**

### **V-Sekai Fire**

*(Artwork, Tools & Experiments from the V-Sekai-fire group)*

* [V-Sekai-fire GitHub Organization](https://github.com/v-sekai-fire) \- Main page for V-Sekai Fire projects.  
* [V-Sekai-fire/godot\_bird\_plane](https://github.com/V-Sekai-fire/godot_bird_plane) \- Godot project, a demo. (GDScript, C++)  
* [V-Sekai-fire/godot-vrm-motion-checker](https://github.com/V-Sekai-fire/godot-vrm-motion-checker) \- Tool for checking VRM motions in Godot. (GDScript)

## **Other Tools**

* [Magika ONNX Minimal File Type Prediction](https://github.com/trevorhobenshield/magika_onnx) \- A minimal implementation for file type prediction using Magika with ONNX.  
* [Lottie](https://lottie.github.io/) \- A mobile library for Android and iOS that parses Adobe After Effects animations exported as json with Bodymovin and renders them natively on mobile\!  
* [SQLpage](https://github.com/lovasoa/SQLpage) \- SQL-only web server. Builds dynamic websites entirely in SQL.  
* [V-Sekai Blender Game Tools](https://github.com/V-Sekai/vsekai-blender-game-tools) \- Blender tools tailored for game development within the V-Sekai ecosystem.  
* [FBX2glTF FBX to GLTF Converter](https://github.com/godotengine/FBX2glTF) \- A command-line tool for converting FBX files to glTF 2.0.  
* [OpenVR driver for using VR controllers without an HMD](https://github.com/V-Sekai/V-Sekai-faceless) \- An OpenVR driver allowing the use of VR controllers without a head-mounted display.  
* [Differentiable Cloth Simulation](https://github.com/fire/differentiable_cloth) \- A project exploring differentiable cloth simulation.  
* [GLTF Extensions](https://github.com/omigroup/gltf-extensions) \- A collection of glTF extensions developed by the OMIgroup.  
* [XMP StableDiffusion DataMapper](https://github.com/Zirnworks/XMP-StableDiffusion-DataMapper) \- A tool for mapping XMP metadata with Stable Diffusion.  
* [Proton Graph](https://github.com/protongraph/protongraph) \- A node-based visual scripting system.  
* [Nomad Sculpt](https://nomadsculpt.com/) \- A sculpting application for mobile devices.  
* [Quadwild for quad-dominant re-meshing (with Bi-MDF)](https://github.com/cgg-bern/quadwild-bimdf) \- A tool for quad-dominant remeshing of 3D models.  
* [SystemAnimatorOnline](https://github.com/ButzYung/SystemAnimatorOnline) \- An online tool related to system animation.  
* [Tool to tokenize GPT input](https://tiktokenizer.vercel.app/) \- A web tool for visualizing how text is tokenized by GPT models.  
* [Lateral Thinking with Weathered Technology](https://en.wikipedia.org/wiki/Gunpei_Yokoi) \- An article discussing Gunpei Yokoi's design philosophy.  
* [Generate Blender Rigify armatures for VRM models.](https://github.com/nanoskript/vrm-rigify) \- A tool to generate Blender Rigify armatures for VRM avatar models.  
* [Three VRM Inspector](https://0b5vr.com/three-vrm-inspector/) \- A web-based inspector for VRM models using three.js.  
* [Worldtime Buddy](https://www.worldtimebuddy.com/) \- A world clock, time zone converter, and online meeting scheduler.  
* [Booth Avatars](https://boothplorer.com/avatars) \- A site for exploring avatars available on Booth.pm.  
* [Lazygit](https://github.com/jesseduffield/lazygit) \- A simple terminal UI for git commands.  
* [Approximate Convex Decomposition for 3D Meshes](https://github.com/SarahWeiii/CoACD) \- A tool for performing approximate convex decomposition of 3D meshes.  
* [Macroons: minimally-stateful bearer token, a blob signed with HMAC](https://fly.io/blog/macaroons-escalated-quickly/) \- A blog post explaining Macaroons for authentication.
* [SAMMI is a fully customizable streaming assistant](https://github.com/SAMMISolutions/SAMMI-Official) \- SAMMI is a fully customizable streaming assistant that lets your Twitch and YouTube Live audience control and interact with your stream. It is fully compatible with OBS Websocket, which can remotely control your OBS Studio.
* [Manage applications that are loaded automatically when Windows starts up.](https://www.hibitsoft.ir/StartupManager.html)

## **Tools that bring me joy**

* [Aurora appstore usable on the Meta Quest](https://auroraoss.com/) \- An alternative app store for Android, usable on devices like Meta Quest.  
* [World Clock](https://www.timeanddate.com/worldclock/) \- A tool for checking current times across the world.  
* [Elk: Mastadon client](https://elk.zone) \- A web-based client for the Mastodon social network.  
* [Libhunt: Shows trending GitHub repositories based on social media links](https://www.libhunt.com) \- A website for discovering popular software libraries and projects.  
* [Threadreaderapp: Provides pdf summaries of Twitter threads](https://threadreaderapp.com/) \- A service to unroll Twitter threads into readable articles.  
* [Rhino3d: CAD modeller with a visual procedural graph](https://www.rhino3d.com/) \- A 3D computer graphics and computer-aided design (CAD) application software.  
* [When2meet helps you find the best time for a group to get together](https://www.when2meet.com/) \- A simple tool for finding the best time for a group to meet.  
* [Hack for quick note-taking](https://hackmd.io/) \- A real-time, collaborative Markdown editor.  
* [Image comparison](https://imgsli.com) \- An online tool for comparing two images with a slider.  
* [Code Name Generator: Colors, Metal, Animals](https://www.codenamegenerator.com/) \- A tool for generating code names.  
* [Voice Changer Guide](https://rentry.co/VoiceChangerGuide) \- A guide for voice changing software and techniques.  
* [Sapling: A Scalable, User-Friendly Source Control System](https://github.com/facebook/sapling.git) \- A source control system developed by Facebook.  
* [Provide the user with inverse control over the hyper-parameters through a brush stroke metaphor](https://github.com/eliemichel/DagAmendment) \- A project exploring intuitive control over complex parameters.  
* [Ultorg is a general-purpose database app that connects to your existing data. Work quickly across tables, queries, and relationships without manual coding or page design.](https://www.ultorg.com/)  
* [VRM Downgrader](https://vrm-downgrader.pages.dev/) \- A tool to downgrade VRM model versions.  
* [HammerTime](https://hammertime.cyou) \- Generate timestamp indicators for Discord chat messages.
* [OPNsense](https://opnsense.org/) - OPNsense® is an open source, feature rich firewall and routing platform, offering cutting-edge network protection.
* [Latency Numbers](https://samwho.dev/numbers) - Latency Numbers Every Programmer Should Know
* [YamaPlayer](https://github.com/koorimizuw/YamaPlayer) - Modern video player for VRChat. 
* [VRM-Previewer](https://github.com/emptyngton/VRM-Previewer)

## **Websites & Community**

* [V-Sekai Website](https://v-sekai.org/) \- Official website.  
* [V-Sekai Discord](https://discord.gg/H3s3PD49XC) \- Main community chat.  
* [V-Sekai GitHub Organization](https://github.com/V-Sekai) \- Primary development hub.  
* [Coding for a Finite World](https://yoric.github.io/post/coding-for-a-finite-world/) \- A blog post discussing sustainable software development.  
* [How to atlas everything in your world](https://wiki.vrchat.com/wiki/How_to_Atlas_everything_in_your_World) \- A VRChat wiki page explaining texture atlasing.  
* [V-Sekai Manuals Website](https://github.com/V-Sekai/manuals) \- Repository for V-Sekai's documentation and manuals.  
* [Godot GLTF 2.0 Scene Exporter](https://godotengine.org/article/introducing-the-godot-gltf-2-0-scene-exporter/) \- Godot Engine article introducing the glTF 2.0 scene exporter.  
* [Animation Retargeting in Godot 4.0](https://godotengine.org/article/animation-retargeting-in-godot-4-0/) \- Godot Engine article on animation retargeting features in Godot 4.0.  
* [Godot Engine PRs by File](https://godotengine.github.io/godot-prs-by-file/) \- A tool to view Godot Engine pull requests sorted by file.  
* [Getty OpenContent CC0](https://www.getty.edu/art/collection/search?open_content=true) \- Getty Museum's open content image collection.  
* [Shader Motion Website](https://github.com/V-Sekai/shader-motion-navy-lead-ostrich) \- A website or project related to shader-based motion.  
* [A third-party item and avatar catalogue, primarily for VRChat, with items from BOOTH.pm and more](https://boothplorer.com/) \- A catalog for VRChat items and avatars.  
* [BOOTH: Global Marketplace for Creative Endeavors](https://booth.pm/) \- An online marketplace for independent creators.

## **Groups**

* [Godot Engine](https://godotengine.org/teams) \- Official Godot Engine teams page.  
* [Open Metaverse Interoperability Group](https://omigroup.org) \- A group focused on interoperability standards for the metaverse.  
* [Khronos](https://www.khronos.org/) \- An open consortium creating interoperability standards for 3D graphics, virtual reality, augmented reality, parallel programming, vision acceleration and machine learning.  
* [Polypixel: for low polygon art](https://github.com/recatek/polypixel-wiki/wiki) \- A community or resource for low-polygon art.

## **Machine Learning experiments**

* [Microsoft PHI-3](https://huggingface.co/collections/microsoft/phi-3-6626e15e9585a200d2d761e3) \- Collection of PHI-3 models by Microsoft on Hugging Face.  
* [MeshTransformer](https://github.com/lucidrains/meshgpt-pytorch/) \- PyTorch implementation of MeshGPT, a transformer for generating and manipulating 3D meshes.  
* [SpaceMesh](https://research.nvidia.com/labs/toronto-ai/space-mesh/) \- Research project on generating 3D meshes.  
* [together.ai Model training, fine-tuning, and inference](https://www.together.ai/) \- A platform for training, fine-tuning, and running AI models.

## **Articles**

* [Create Character Rigs With This Free Blender Add-on](https://80.lv/articles/create-character-rigs-with-this-free-blender-add-on)

## **Other Awesome Lists**

* [awesome-godot](https://github.com/godotengine/awesome-godot) \- A curated list of awesome Godot Engine frameworks, libraries, software and resources.  
* [Awesome Godot Scientific](https://github.com/Ivorforce/Awesome-Godot-Scientific) \- A curated list of Godot Engine projects and resources for scientific purposes.

## **Contributing**

Contributions are welcome\!  
When adding a new item, please try to include:

* A direct link to the repository or resource.  
* A concise description.  
* Relevant primary languages or technologies (e.g., GDScript, C++, GDExtension).  
* Any important notes, such as if it's a fork or its specific role in the V-Sekai ecosystem.

Let's make V-Sekai awesome together\!
