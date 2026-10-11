# Fbx2Mdx

<p align="center"><a href="https://github.com/GoldenEggCN/Fbx2Mdx-release/releases/latest"><b>Download latest release</b></a> &nbsp;·&nbsp; <a href="https://goldeneggcn.github.io/Fbx2Mdx-release/">Full introduction</a> &nbsp;·&nbsp; <a href="https://www.hiveworkshop.com/threads/fbx2mdx-easily-convert-fbx-glb-to-wc3-model.373975/">Hive Workshop thread</a></p>

<p align="center">
<img src="docs/assets/401858-9f9d4f69f2c5275748efc35cbb4ac65e.webp" width="76%" alt="Fbx2Mdx">
</p>

---

Author GoldenEggCN

Full description · Original thread: [Hive Workshop](https://www.hiveworkshop.com/threads/fbx2mdx-easily-convert-fbx-glb-to-wc3-model.373975/) · [Back to repository](https://github.com/GoldenEggCN/Fbx2Mdx-release) · [English](index.html)

### What is this?

A model format conversion tool.

It can easily convert common model formats like FBX/GLB into the model format used by Warcraft III.

Beginner-friendly and easy to get started — one-click operation, no professional tools or plugins required.

Excellent compatibility and stability, freeing you from all kinds of tricky issues.

### Features

Supports preserving the model's idle bound pose.

Recalculate normals.

Supports MDX export restoration with smooth weight performance, and automatically adds attachment points and click spheres.

Edit offset, rotation, scale and other parameters.

Quickly merge animation clips.

Optimize the model's mesh and animation.

---

## Demo

<p align="center">
FBX: <img src="docs/assets/401734-84b4477bd63c57e42878104864c88ee7.webp" width="40%"> → MDX: <img src="docs/assets/401735-51ddeafc1cd2fac1bf8e8c15c3b17440.webp" width="40%">
</p>

As you can see, even when converted to classic MDX, it still maintains smooth dance movements and poses.

<p align="center">
<img src="docs/assets/401737-1d507546f8f4ab3542e12ee6002492fb.webp" width="48%"> <img src="docs/assets/401738-2bf53b517396f03cd1da481b0506e22a.webp" width="48%">
</p>

Quickly adjust the model through operations such as translation, rotation, and scaling.

<p align="center">
<img src="docs/assets/404180-ec56dd1c238d6f9179c0724b1125553c.webp" width="48%"> <img src="docs/assets/404181-6f33580d89a8fe76a9df192f65bfda34.webp" width="48%">
</p>

<p align="center">
<img src="docs/assets/404182-72067d5f379f6381aaf56cfba7df44db.webp" width="48%"> <img src="docs/assets/404183-6897748d28b8d658e3dceedecde6ef41.webp" width="48%">
</p>

The "**Simplify Mesh**" feature can significantly reduce the number of vertices, thereby easing the game's rendering load.

<p align="center">
<img src="docs/assets/404162-b6fc649292e8be2f7f369620464c4b21.webp" width="48%"> <img src="docs/assets/404163-58fdf494df97de390fb9e55b87093e62.webp" width="48%">
</p>

You can even synthesize more animations for her... all you need is a piece of material with the same skeleton.

<p align="center">
<img src="docs/assets/401739-5a301b6f2bead5420249f527cd4b8b7b.webp" width="32%"> <img src="docs/assets/401740-54161d4e7b92839124c95eb0898181d7.webp" width="32%"> <img src="docs/assets/401741-3a1197d343aa74fb2fc765a74b863e75.webp" width="32%">
</p>

The "**attachment points**" required by the game will automatically recognize bones and add them to the model.

Of course, there are also material textures.

<p align="center">
<img src="docs/assets/401743-3a9d090dd524454281d9f3c1083af1df.gif" width="48%"> <img src="docs/assets/401746-cd3c75609a4f835f6c365cec359253bc.webp" width="48%">
</p>

If you want to achieve a mirror effect… simply set the scale value to a negative number.

<p align="center">
<img src="docs/assets/404194-3b3d320edeb1ee8281b139e278b08db2.webp" width="78%">
</p>

Adjusting the animation's **"Noise Reduction"** and **"Smoothing"** strength can make the character's movements smooth.

<p align="center">
<img src="docs/assets/404193-f8057a3f48a07a87acc7e25a68132afe.gif" width="78%">
</p>

Effect comparison: Original → Denoised → Denoised & Smoothed

<p align="center">
<img src="docs/assets/401836-fd7726be27ebb84fea650352d1801323.webp" width="32%"> <img src="docs/assets/401837-dd9ab74a1b0e7049c59a5bb294547f0c.webp" width="32%"> <img src="docs/assets/401838-8d9b99c797a979f366cc6b311baf9feb.webp" width="32%">
</p>

AI-generated models often have messy topology and high poly counts, which is not conducive to the skinning process.

But now you can use this "retopology and baking" tool to rebuild this model.

<p align="center">
<img src="docs/assets/404063-9782e3ad8710f2e6cf40929f0251c5a4.webp" width="78%">
</p>

After retopology, the model's vertex count dropped by a full 50%! And the mesh topology is much cleaner as well.

<p align="center">
<img src="docs/assets/404068-68021307fb79527592464592e2f1d13d.webp" width="40%"> → <img src="docs/assets/404069-4740172ef99bee29c087f10858f7ce66.webp" width="40%">
</p>

The color blocks on the texture are also neater now, and you'll find it much easier to draw patterns and color schemes on top.

<p align="center">
<img src="docs/assets/404070-98d81ccb71f25013316d1e671e30b991.webp" width="40%"> → <img src="docs/assets/404071-5d32b06b11e6effde2670784f118f356.webp" width="40%">
</p>

**Fortunately, this process preserves the model's skin weights and skeletal animation!**

<p align="center">
<img src="docs/assets/404505-b142de05ee3e3a314b09febcb6160e80.webp" width="78%">
</p>

---

### FAQ

<details>
<summary><b>Q: Is this software paid?</b></summary>

A: It's completely free. In the future, only some AI features may be charged for.

</details>

<details>
<summary><b>Q: Do the converted MDX models come with animations? Can particle effects be converted?</b></summary>

A: If the original model has animations, they will be preserved in the converted MDX. As for particle effects, they are native to the game engine and are not stored in the model file, so they cannot be converted.

</details>

<details>
<summary><b>Q: Why is this software so slow at importing and exporting, and why does the exported FBX take up even more disk space?</b></summary>

</details>

Answer: The software bakes all of the model's skeletal animations into keyframes, making it compatible with almost any game engine and fully preserving the animation. This trades time and disk space for compatibility — a necessary trade-off.

<details>
<summary><b>Q: Someone has already used AI to make a DLL that can read and recognize various Blizzard model resources in-game, so why is a converter still needed?</b></summary>

</details>

Answer: Blizzard's model format is very simple and stable. But closed-source formats like FBX tend to be highly varied and messy, making it unrealistic to read them directly in-game — the only option is to convert them.

<details>
<summary><b>Q: How is this converter different from other lightweight MDX converters or plugins?</b></summary>

</details>

Answer: It's more like an FBX editor, or an "FBX purifier." It converts all kinds of FBX files into a more stable version, so they can flow freely between various modeling software and game engines. Therefore, it isn't limited to Blizzard's game assets; it has an industrial-grade workflow and better extensibility.

## Enjoy using it!
