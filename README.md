# aframe-habitats

Lets beam some of the awesomeness of [AI Habitat](https://aihabitat.org/) over to A-Frame, so we can prototype IoT/AI simulations directly in the browser.

## Rooms

Facebook's AI-Habitat features 3D-scanned rooms from three datasets:

* [Matterport3D](https://niessner.github.io/Matterport/) (Straub, et al., 2019) — **90 building-scale scenes** — [non-commercial license](http://kaldir.vc.in.tum.de/matterport/MP_TOS.pdf)
* [Replica](https://github.com/facebookresearch/Replica-Dataset) (Chang et al., 2017)  — **18 Rooms: 3 appartments, 5 office, 3 rooms and 1 hotel room** — [non profit license](https://github.com/facebookresearch/Replica-Dataset/blob/master/LICENSE)
* [2D-3D-S](https://github.com/alexsax/2D-3D-Semantics) (Armeni et al., 2017) — **6 large-scale indoor areas that originate from 3 different buildings** — [Apache License](https://github.com/alexsax/2D-3D-Semantics/blob/master/LICENSE)

The goal of `aframe-habitats` is to make these rooms available as gtlf + navmesh, so you can use them in the browser using low-entry environments such as A-Frame.

Since some of the licenses are quite restricting, so we'd rather provide tools & tutorials on how to convert the original files to gltf + navmeshes.

## Habitat-Examples

Here are A-Frame scenes — created from the habitat test scenes, which you can download [here](http://dl.fbaipublicfiles.com/habitat/habitat-test-scenes.zip).

### Skokkloster Castle

Play with it → [here](habitats/skokloster-castle) ←

- 3D-Model of [King's Hall of Skokloster castle](https://en.wikipedia.org/wiki/Skokloster_Castle).
- The navmesh was created using the [recast plugin](https://github.com/donmccurdy/aframe-inspector-plugin-recast) for the A-frame-Inspector.
- This model is also available [via sketchfab](https://sketchfab.com/3d-models/the-king-s-hall-d18155613363445b9b68c0c67196d98d)

### Van Gogh Room
- **To be done**
- 3D-Model of [Van Gogh's bedroom in Arles](https://en.wikipedia.org/wiki/Bedroom_in_Arles)  
- This model is also available [via sketchfab](https://sketchfab.com/3d-models/van-gogh-room-311d052a9f034ba8bce55a1a8296b6f9)


### Appartment 1
- **To be done**
