# Fbx2Mdx

<p align="center"><a href="https://github.com/GoldenEggCN/Fbx2Mdx-release/releases/latest"><b>Download latest release</b></a> &nbsp;·&nbsp; <a href="https://goldeneggcn.github.io/Fbx2Mdx-release/">Full introduction</a> &nbsp;·&nbsp; <a href="https://www.hiveworkshop.com/threads/fbx2mdx-easily-convert-fbx-glb-to-wc3-model.373975/">Hive Workshop thread</a></p>

<p align="center">
<img src="docs/assets/401858-9f9d4f69f2c5275748efc35cbb4ac65e.webp" width="76%" alt="Fbx2Mdx">
</p>

---

Author: GoldenEggCN <img src="docs/assets/401659-23acabcfa3435da90f880faf67e8e0ed.webp" width="16">

Forum: [Hive Workshop](https://www.hiveworkshop.com/threads/fbx2mdx-easily-convert-fbx-glb-to-wc3-model.373975/)

QQ Group: 181519522

### What is this?

A model format conversion tool.

It can easily convert common model formats such as FBX/GLB into the model format used by Warcraft III.

Easy to get started, one-click operation, no professional tools or plugins required. Excellent compatibility and stability keep you free from all kinds of tricky issues.

It also makes model files more stable, making them easier to transfer and use across various game engines and modeling software.

### Features

Supports FBX , GLB , OBJ and MDX ( Classic, Reforged ) and other model formats.

When exporting, bake animation frames, and preserve the model's rest bind pose. This makes the model file more standardized.

Exported MDX restores smooth weight performance, and automatically adds attachment points and click spheres.

Visually edit offset, rotation, scale and other parameters, as well as recalculate normals.

Quickly rig and skin a model that has no skeleton. Make it able to move.

Merge multiple animation clips. For a properly named skeleton, you can instantly add preset combat animations.

Reduce the model's polygon count. Perform retopology and texture baking on high-poly models with messy topology.

---

## Effect Demo

<p align="center">
FBX: <img src="docs/assets/401734-84b4477bd63c57e42878104864c88ee7.webp" width="40%"> → MDX: <img src="docs/assets/401735-51ddeafc1cd2fac1bf8e8c15c3b17440.webp" width="40%">
</p>

As you can see, even when converted to classic MDX, it still maintains smooth dance movements and poses.

<p align="center">
<img src="docs/assets/401737-1d507546f8f4ab3542e12ee6002492fb.webp" width="48%"> <img src="docs/assets/401738-2bf53b517396f03cd1da481b0506e22a.webp" width="48%">
</p>

Quickly adjust the model through operations such as translate, rotate, and scale.

<p align="center">
<img src="docs/assets/404180-ec56dd1c238d6f9179c0724b1125553c.webp" width="48%"> <img src="docs/assets/404181-6f33580d89a8fe76a9df192f65bfda34.webp" width="48%">
</p>

<p align="center">
<img src="docs/assets/404182-72067d5f379f6381aaf56cfba7df44db.webp" width="48%"> <img src="docs/assets/404183-6897748d28b8d658e3dceedecde6ef41.webp" width="48%">
</p>

The “**Decimate Mesh**” feature can significantly reduce the vertex count, thereby lessening the game's rendering load.

<p align="center">
<img src="docs/assets/404162-b6fc649292e8be2f7f369620464c4b21.webp" width="48%"> <img src="docs/assets/404163-58fdf494df97de390fb9e55b87093e62.webp" width="48%">
</p>

You can also synthesize more animations for her… as long as you have an asset with the same skeleton.

<p align="center">
<img src="docs/assets/401739-5a301b6f2bead5420249f527cd4b8b7b.webp" width="32%"> <img src="docs/assets/401740-54161d4e7b92839124c95eb0898181d7.webp" width="32%"> <img src="docs/assets/401741-3a1197d343aa74fb2fc765a74b863e75.webp" width="32%">
</p>

The "**attachment points**" required by the game are automatically identified from the skeleton and added to the model.

Of course, there are also material textures.

<p align="center">
<img src="docs/assets/401743-3a9d090dd524454281d9f3c1083af1df.gif" width="48%"> <img src="docs/assets/401746-cd3c75609a4f835f6c365cec359253bc.webp" width="48%">
</p>

To achieve the mirror effect... just set the scale value to a negative number.

<p align="center">
<img src="docs/assets/404194-3b3d320edeb1ee8281b139e278b08db2.webp" width="78%">
</p>

Adjusting the **"Noise Reduction"** and **"Smoothing"** strength of the animation can make the character's movements smoother.

<p align="center">
<img src="docs/assets/404193-f8057a3f48a07a87acc7e25a68132afe.gif" width="78%">
</p>

Comparison of effects: Original → Noise Reduction → Noise Reduction & Smoothing

<p align="center">
<img src="docs/assets/401836-fd7726be27ebb84fea650352d1801323.webp" width="32%"> <img src="docs/assets/401837-dd9ab74a1b0e7049c59a5bb294547f0c.webp" width="32%"> <img src="docs/assets/401838-8d9b99c797a979f366cc6b311baf9feb.webp" width="32%">
</p>

AI-generated models often have messy topology and a high polygon count, which is not conducive to the skinning workflow.

But now you can use this "Retopology and Baking" tool to rebuild this model.

<p align="center">
<img src="docs/assets/404063-9782e3ad8710f2e6cf40929f0251c5a4.webp" width="78%">
</p>

After retopology, the model's vertex count dropped by a full 50%! And the mesh topology is much cleaner too.

<p align="center">
<img src="docs/assets/404068-68021307fb79527592464592e2f1d13d.webp" width="40%"> → <img src="docs/assets/404069-4740172ef99bee29c087f10858f7ce66.webp" width="40%">
</p>

The blocks of color on the texture are also tidier, and you'll find it much easier to paint patterns and color schemes on it.

<p align="center">
<img src="docs/assets/404070-98d81ccb71f25013316d1e671e30b991.webp" width="40%"> → <img src="docs/assets/404071-5d32b06b11e6effde2670784f118f356.webp" width="40%">
</p>

**Fortunately, this process preserves the model's skinning weights and skeletal animation!**

<p align="center">
<img src="docs/assets/404505-b142de05ee3e3a314b09febcb6160e80.webp" width="78%">
</p>

---

### Frequently Asked Questions

Q: Is this software paid?

A: It is completely free. Perhaps in the future only some AI features may be charged for.

Q: Do the converted MDX models come with animations? Can particle effects be converted?

**A: If the original model has animations, they will naturally be preserved in the converted MDX. As for particle effects, they are a product of the game engine and are not stored in the model file, so they cannot be converted.**

Q: Why does this software's conversion feature take a long time, and why do the exported FBX files take up even more disk space?

A: The software bakes all skeletal animations of the model into keyframes, so it can adapt to almost any game engine and fully reproduce the animation effects. This trades time and disk space for compatibility, which is a necessary trade-off.

Q: Someone has already used AI to create a DLL that can read and recognize various Blizzard model assets in-game, so why is a converter still needed?

Answer: Blizzard's model format is very simple and stable. But closed-source formats like FBX are often endlessly variable and very messy, so reading them directly in-game is highly impractical; the only way is to convert them.

Q: How is this converter different from other lightweight MDX converters or plugins?

Answer: It's more like an FBX editor, or rather an "FBX purifier." It turns all kinds of FBX files into more stable versions, so they can flow smoothly between various modeling software and game engines. Therefore, it is not limited to Blizzard's game assets; it has an industrial-grade pipeline and better extensibility.

## Enjoy using it!
