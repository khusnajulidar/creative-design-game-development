# Illustration & 3D Production

## Scope

Create, refine, and prepare 2D illustrations, 3D models, characters, environments, props, textures, renders, and real-time visual assets. This reference covers visual asset production; time-based storytelling belongs to Motion, Animation & Video, while interface behavior belongs to UI/UX.

## 1. Asset brief and art direction

Define:
- Purpose and intended use (print, web, game, animation, product visualization, learning media).
- Audience, tone, style, and visual references.
- Subject, silhouette, pose, expression, proportions, and required details.
- Camera/view, composition, background, lighting, and palette.
- Dimensions, aspect ratio, resolution, file format, transparency, and color requirements.
- Whether the asset must be editable, layered, rigged, animated, or optimized for real-time use.
- Constraints involving identity, culture, context, safety, accessibility, or project-specific content.

Record which reference features are mandatory and which allow interpretation.

## 2. Visual consistency

Create a style and asset guide for recurring subjects. Define proportions, shape language, line or edge treatment, materials, color relationships, lighting, camera conventions, and detail density.

For recurring characters and objects, maintain model sheets or reference views where useful. Check consistency across poses, angles, expressions, outfits, scale, and scenes. Do not make unapproved changes to established character identity or approved assets.

Respect project-specific representation constraints in the project brief. Do not assume a rule from one project applies to all projects.

## 3. 2D illustration workflow

1. Clarify subject, purpose, composition, and output.
2. Establish silhouette and major shapes.
3. Resolve pose, proportions, perspective, and focal hierarchy.
4. Develop palette, light, shadow, materials, and detail.
5. Review readability at intended size and against the target background.
6. Clean edges, layers, transparency, and export settings.
7. Prepare alternate sizes or variants only when required.

Use vector workflows for scalable, clean geometric assets; raster workflows for painterly detail, texture, or complex rendering. Preserve layers and editable source when requested and supported.

## 4. 3D production workflow

### Pre-production
Define target engine or renderer, scale and units, polygon/complexity budget, camera, level of detail, animation/rigging needs, material requirements, and delivery format.

### Modeling
Build clean forms and topology appropriate to the intended use. Use subdivision, sculpting, hard-surface, procedural, or kit-based approaches as suitable. Check silhouette, proportions, intersections, normals, and geometry integrity.

### Retopology and UVs
For deforming or real-time assets, use topology suitable for deformation and performance. Create efficient UV layouts with appropriate texel density, padding, and minimal distortion. Avoid unnecessary seams in prominent areas.

### Materials and textures
Use physically plausible or intentionally stylized material behavior appropriate to the art direction. Maintain consistent roughness, metallic response, color space, texture resolution, and naming. Check texture paths and missing dependencies.

### Rigging and deformation
When required, verify hierarchy, pivots, joint orientation, skin weights, constraints, and deformation through representative poses. Do not describe a model as rigged or animation-ready unless these requirements have been completed and checked.

### Lighting and rendering
Set lighting and camera to support form, readability, and intended mood. Check shadows, reflections, clipping, noise, color management, transparency, and render output. Keep render settings and scene dependencies organized.

### Optimization
For real-time assets, consider polygon count, draw calls, material slots, texture memory, compression, LODs, collision meshes, and target device performance. Optimize without damaging the approved visual quality.

## 5. Formats and interchange

Select formats according to the destination:
- PNG/JPEG/WebP for raster images.
- SVG for supported vector graphics.
- Layered native formats for editable 2D work.
- Blender or other native scene formats for editable 3D projects.
- FBX, OBJ, GLB/glTF, USD, or other interchange formats when supported by the target pipeline.

Verify that the chosen format preserves the required geometry, materials, textures, animation, hierarchy, color, and transparency. Export compatibility is application- and version-dependent; test in the target environment when possible.

## 6. AI-assisted asset creation

AI-generated imagery can accelerate concept exploration and asset creation. Inspect for anatomical or structural errors, inconsistent details, malformed text, impossible geometry, unwanted artifacts, and mismatches with references. For production assets, verify editability, repeatability, licensing, and integration requirements.

Do not claim that a generated 2D image is a fully editable 3D model, rig, vector asset, or layered source file. A rendered image is not a substitute for structured source data when the task requires it.

## 7. Integration

Name and organize assets consistently. Include dimensions, scale, pivot/origin, orientation, texture dependencies, color-space notes, license/source, and intended use. Check transparency, cropping, file size, import settings, and visual appearance in the actual target application or engine.

For asset families, document shared conventions and dependencies. Avoid breaking existing references or replacing an asset without checking where it is used.

## 8. Quality checks

- Silhouette, proportions, perspective, and visual hierarchy.
- Style consistency across the asset family.
- Clean geometry, normals, topology, UVs, and deformation where relevant.
- Material and texture correctness; no missing links.
- Lighting, shadows, color management, and render artifacts.
- Resolution, transparency, dimensions, and export integrity.
- Performance and memory suitability for target hardware.
- Reference fidelity, project constraints, and rights records.
- Successful import and appearance in the intended environment when tested.

## Deliverables

Provide the agreed renders and/or source assets, editable scene or layered files when requested, texture and dependency folders, export notes, naming and version details, license/source records, and a handoff describing limitations or integration requirements.

## Definition of done

The asset fulfills its intended role, matches the approved art direction, meets technical and platform requirements, has been inspected at its intended size or in its target environment, and includes the necessary source, dependencies, and handoff information.
