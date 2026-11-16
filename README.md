<div align="center">

<h1>The Spatial-Free World Model</h1>

<em>Why doesn't artificial intelligence need to understand space?</em>

<br /><br />

<sub>English · <a href="README.zh-CN.md">中文</a></sub>

<br /><br />

<img src="https://img.shields.io/badge/status-manifesto-8A2BE2?style=flat-square&labelColor=202020" alt="status: manifesto" />
<img src="https://img.shields.io/badge/space-optional-2F81F7?style=flat-square&labelColor=202020" alt="space: optional" />
<img src="https://img.shields.io/badge/learns_from-change-8957E5?style=flat-square&labelColor=202020" alt="learns from change" />

</div>

<br />

---

We have always taught AI to understand the world the way humans do.

We tell it what distance is, what position is, what front and back mean, what three-dimensional space is.

But we have overlooked one question:

<p align="center"><strong>Can AI actually feel space?</strong></p>

Even if we give a robot a body — let it walk, turn, and touch objects — it remains a brain in a vat, one that merely happens to be able to act.

What it comes into contact with is always information delivered by sensors, never the physical world as humans understand it.

<p align="center"><em>Are distance, position, and depth the essence of the world —<br />
or an explanatory framework that humans built in order to understand the world?</em></p>

For a model, what it actually receives are images, pixels, changes of scale, and the differences in information between consecutive observations.

A distant car gradually grows larger; a nearby pedestrian gradually shrinks. The world presents different information at different scales.

So why must these changes be translated back into 3D coordinates?

Why not learn scale, relations, and change directly?

---

### The core idea

> Do not reconstruct three-dimensional space. Do not fixate on absolute distance. Do not force the model to understand positions defined by humans.
>
> Learn the world directly from observations. Learn regularities from changes of scale. Predict the future from actions and feedback.

```mermaid
flowchart LR
    O["observation<br/>pixels · frames"] --> S["scale · relation · change"] --> P["prediction<br/>actions · feedback"]
```

<p align="center"><sub>No coordinates in between. Only what actually varies between observations.</sub></p>

### Two ways of understanding

| | Reconstructive world model | Spatial-free world model |
| :-- | :-- | :-- |
| Assumes | 3D space is the world | observations are the world |
| Learns | coordinates, depth, pose | scale, relation, change |
| Unit | meters | differences in information |
| Goal | rebuild the scene | predict the next observation |

---

We are not trying to make AI understand the world the way humans do.

We are looking for a way of understanding information that suits AI itself.

<p align="center"><em>Space may be the language of humans —<br />
but not necessarily the language in which AI understands the world.</em></p>

<br />

<p align="center">
<sub><a href="README.zh-CN.md">中文</a> · English</sub>
</p>
