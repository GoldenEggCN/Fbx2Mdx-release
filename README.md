# Fbx2Mdx

**Easily convert .fbx / .glb to Warcraft III models.**

<p align="center">
<img src="docs/assets/401858-9f9d4f69f2c5275748efc35cbb4ac65e.webp" width="76%" alt="Fbx2Mdx">
</p>

<p align="center"><a href="https://github.com/GoldenEggCN/Fbx2Mdx-release/releases/latest"><b>Download latest release</b></a> &nbsp;·&nbsp; <a href="https://goldeneggcn.github.io/Fbx2Mdx-release/">Full introduction (with GIF demos)</a> &nbsp;·&nbsp; <a href="https://www.hiveworkshop.com/threads/fbx2mdx-easily-convert-fbx-glb-to-wc3-model.373975/">Hive Workshop thread</a></p>

---

### What is it?

A model format conversion tool.

It lets you easily convert common model formats such as FBX/GLB into the model format used by Warcraft III.

Beginner-friendly and easy to use - one-click operation, no professional tools or plugins required.

High compatibility and stability spare you from all kinds of special problems.

### Features

- Supports preserving the model's initial bind/rest pose.
- Supports MDX classic mode restoring smooth weight behaviour.
- Supports MDX auto-adding attachment points and collision shapes.
- Supports editing offset, rotation, scale and other parameters.
- Supports quickly merging animation data that shares the same skeleton.
- Supports optimizing the model and animations to reduce file size.

### Contact

Author - **GoldenEggCN** <img src="docs/assets/401659-23acabcfa3435da90f880faf67e8e0ed.webp" width="16">

---

## Effect Demonstration

<p align="center">
FBX: <img src="docs/assets/401734-84b4477bd63c57e42878104864c88ee7.webp" width="40%"> → MDX: <img src="docs/assets/401735-51ddeafc1cd2fac1bf8e8c15c3b17440.webp" width="40%">
</p>

**As you can see, even when converted to classic MDX, it can still maintain smooth dancing poses and movements.**

<p align="center">
<img src="docs/assets/401737-1d507546f8f4ab3542e12ee6002492fb.webp" width="48%"> <img src="docs/assets/401738-2bf53b517396f03cd1da481b0506e22a.webp" width="48%">
</p>

**Quickly adjust the model with operations such as translation, rotation, and scaling.**

<p align="center">
<img src="docs/assets/404180-ec56dd1c238d6f9179c0724b1125553c.webp" width="48%"> <img src="docs/assets/404181-6f33580d89a8fe76a9df192f65bfda34.webp" width="48%">
</p>

<p align="center">
<img src="docs/assets/404182-72067d5f379f6381aaf56cfba7df44db.webp" width="48%"> <img src="docs/assets/404183-6897748d28b8d658e3dceedecde6ef41.webp" width="48%">
</p>

The **"Reduce Polygons"** feature can drastically cut down vertex counts and ease the rendering load for games.

<p align="center">
<img src="docs/assets/404162-b6fc649292e8be2f7f369620464c4b21.webp" width="48%"> <img src="docs/assets/404163-58fdf494df97de390fb9e55b87093e62.webp" width="48%">
</p>

**You can also synthesize more animations for her... provided there is a source with the same skeleton.**

<p align="center">
<img src="docs/assets/401739-5a301b6f2bead5420249f527cd4b8b7b.webp" width="32%"> <img src="docs/assets/401740-54161d4e7b92839124c95eb0898181d7.webp" width="32%"> <img src="docs/assets/401741-3a1197d343aa74fb2fc765a74b863e75.webp" width="32%">
</p>

The "**attachment points**" required by the game will automatically recognize the bones and be added to the model.

Of course, there are also material textures.

<p align="center">
<img src="docs/assets/401743-3a9d090dd524454281d9f3c1083af1df.gif" width="48%"> <img src="docs/assets/401746-cd3c75609a4f835f6c365cec359253bc.webp" width="48%">
</p>

**If you want to create a mirror image... simply set the scale value to a negative number.**

<p align="center">
<img src="docs/assets/404194-3b3d320edeb1ee8281b139e278b08db2.webp" width="78%">
</p>

Adjusting the **“Denoise”** and **“Smoothing”** levels of the animation, this will make character movements much smoother.

<p align="center">
<img src="docs/assets/404193-f8057a3f48a07a87acc7e25a68132afe.gif" width="78%">
</p>

**origin → denoise → denoise & smoothing**

<p align="center">
<img src="docs/assets/401836-fd7726be27ebb84fea650352d1801323.webp" width="32%"> <img src="docs/assets/401837-dd9ab74a1b0e7049c59a5bb294547f0c.webp" width="32%"> <img src="docs/assets/401838-8d9b99c797a979f366cc6b311baf9feb.webp" width="32%">
</p>

**The topology of AI-generated models is often messy, with high polygon counts and difficult skinning workflows.**

But now you can use this **"Retopology and Bake"** tool to quickly reconstruct your models.

<p align="center">
<img src="docs/assets/404063-9782e3ad8710f2e6cf40929f0251c5a4.webp" width="78%">
</p>

After retopology, the model 's feature has its vertex count reduced by a whopping 50%! Moreover, the mesh topology becomes much cleaner.

<p align="center">
<img src="docs/assets/404068-68021307fb79527592464592e2f1d13d.webp" width="40%"> → <img src="docs/assets/404069-4740172ef99bee29c087f10858f7ce66.webp" width="40%">
</p>

And the color blocks on the texture maps also become neater, you will find it much easier to paint color patterns on it.

<p align="center">
<img src="docs/assets/404070-98d81ccb71f25013316d1e671e30b991.webp" width="40%"> → <img src="docs/assets/404071-5d32b06b11e6effde2670784f118f356.webp" width="40%">
</p>

**Fortunately, this process preserves the model's skin weights and skeletal animations!**

<p align="center">
<img src="docs/assets/404505-b142de05ee3e3a314b09febcb6160e80.webp" width="78%">
</p>

---

### FAQ

<details>
<summary><b>Q: Is this software paid?</b></summary>

A: It is completely free. In the future, only certain AI features maybe charged for.

</details>

<details>
<summary><b>Q: Does the converted MDX model come with animations? Can it convert particle effects?</b></summary>

A: If the original model has animations, the converted MDX model will retain them. As for particle effects, they are native to the game engine and not stored inside model files, so particle effects cannot be converted.

</details>

<details>
<summary><b>Q: Why does this software take a long time to import and export, and why does the exported FBX take up more disk space?</b></summary>

A: The software bakes all of the model's skeletal animations intokeyframes, so that they adapt to almost every game engine andfully reproduce the animation. This trades time and disk space forcompatibility - a necessary compromise.

</details>

<details>
<summary><b>Q: Some people have already used AI to create a DLL that can read and recognize all types of Blizzard model resources in-game. Why do we still need a converter?</b></summary>

A: Blizzard's model formats are very simple and stable. Butclosed-source formats like FBX tend to be wildly varied and messy,so reading them directly in-game is very unrealistic - the only wayto use them is through conversion.

</details>

<details>
<summary><b>Q: What makes this converter different from other lightweight MDX converters or plugins?</b></summary>

A: It is more like an FBX editor, or an "FBX purifier". It turns allkinds of FBX files into more stable versions so that they can bepassed between various modeling software and game engineswithout obstacles. Therefore it is not limited to Blizzard gameresources; it has an industrial-grade pipeline and betterextensibility.

</details>

## Enjoy!
