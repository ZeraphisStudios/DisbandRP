# Disband RP – Community Asset Submission Guidelines

## Overview

Disband RP is committed to maintaining a high-quality, immersive, and optimized roleplay experience. To ensure consistency across the server, all custom assets submitted for consideration must comply with the standards outlined in this document.

These guidelines apply to all community-submitted content, including but not limited to:

* Custom Clothing
* Vehicles
* MLOs / Interiors
* Props
* Maps
* Textures
* Models
* Other custom GTA V assets

Failure to comply with these guidelines may result in a submission being denied or returned for revision.

---

# Asset Submission Agreement

By submitting any asset ("Asset") to Disband RP, you ("the Submitter") acknowledge and agree to the following terms.

## 1. License Grant

The Submitter grants Disband RP a perpetual, worldwide, royalty-free, non-exclusive license to:

* Host
* Use
* Display
* Modify
* Adapt
* Implement
* Maintain

the submitted Asset across any server, platform, or service owned, operated, or affiliated with Disband RP.

This license remains valid after approval and implementation of the Asset.

---

## 2. Scope of Use

Disband RP may use submitted Assets solely within its own services and community infrastructure.

Disband RP will not intentionally resell or redistribute submitted Assets as standalone products.

Implementation of an Asset does not guarantee:

* Permanent inclusion
* Exclusive use
* Continued availability
* Ownership rights

Assets may be updated, modified, replaced, archived, or removed at any time.

---

## 3. Ownership & Third-Party Content

Submitters must either:

* Be the original creator of the Asset; or
* Possess the legal rights necessary to submit and license the Asset.

If third-party content is included, the Submitter must provide:

* Proper attribution
* License documentation
* Proof of authorization

Disband RP reserves the right to reject any Asset where ownership or licensing cannot be verified.

---

## 4. Removal Requests

Asset creators may request the removal of their content.

However, Disband RP reserves the right to retain and continue using any approved Asset where necessary for:

* Server stability
* Gameplay continuity
* Existing integrations
* Community operations

Approval of removal requests remains solely at the discretion of Disband RP management.

---

## 5. No Obligation to Implement

Submission does not guarantee:

* Review
* Approval
* Implementation
* Continued use

Disband RP reserves the right to reject, modify, discontinue, or remove any Asset at any time.

---

## 6. Acceptance of Terms

By submitting an Asset, the Submitter confirms that they:

* Have read these guidelines.
* Understand these guidelines.
* Agree to these guidelines.
* Possess the authority to submit the Asset.

---

# General Submission Standards

All submissions must adhere to the following requirements.

### Compliance

Assets must comply with:

* CFX.re Terms of Service
* Rockstar Games Policies
* Twitch Terms of Service
* Applicable copyright laws

### Prohibited Content

Assets may not contain:

* Stolen content
* Leaked content
* Ripped game assets
* Unauthorized modifications
* Copyright infringement

### Vanilla File Modifications

Any modifications to vanilla GTA V files must remain:

* Unencrypted
* Editable
* Merge-compatible

This ensures compatibility with existing server modifications.

### Asset Conflicts

Assets must not:

* Overlap existing custom assets
* Cause map conflicts
* Interfere with gameplay systems
* Create unnecessary performance issues

### Quality Expectations

Assets should:

* Match GTA V's visual style
* Fit a modern-day roleplay environment
* Maintain consistent quality standards
* Be optimized for multiplayer use

---

# Custom MP Clothing Requirements

## Quality Standards

All clothing submissions should:

* Match GTA V's visual quality.
* Fit a modern-day roleplay setting.
* Maintain proper proportions and scaling.
* Use proper vertex colors for water and sweat effects.
* Include clean UV mapping.

---

## Texture Optimization

| Texture Type | Maximum Resolution |
| ------------ | ------------------ |
| Diffuse      | 1024x1024          |
| Normal       | 1024x1024          |
| Specular     | 512x512            |

### Recommended Sizes

| Asset Type        | Recommended Resolution |
| ----------------- | ---------------------- |
| Shirts            | 1024x1024              |
| Jackets           | 1024x1024              |
| Pants             | 1024x1024              |
| Glasses           | 512x512                |
| Jewelry           | 256x256                |
| Small Accessories | 256x256                |

### Texture Restrictions

* 2048x2048 textures should be avoided whenever possible.
* 4K textures are prohibited.
* Texture memory usage should be minimized.
* Reuse texture space efficiently where appropriate.

---

## Character Models

Custom peds are generally discouraged.

Disband RP utilizes expanded character customization systems, allowing players to create unique appearances through:

* Clothing
* Tattoos
* Accessories
* Hairstyles

Submissions relying solely on unique ped models may be denied due to performance concerns.

---

## Clothing Polycount Limits

### Weighted Clothing

| Item             | Slot  | Maximum Polycount |
| ---------------- | ----- | ----------------- |
| Masks            | berd  | 10,000            |
| Hair             | hair  | 10,000            |
| Neck Accessories | teef  | 5,000             |
| Torso            | upper | 5,000             |
| Jackets          | jbib  | 15,000            |
| Vests            | task  | 25,000            |
| Shirts           | accs  | 10,000            |
| Decals           | decl  | 5,000             |
| Bags             | hand  | 5,000             |
| Pants            | lowr  | 5,000             |
| Shoes            | feet  | 5,000             |

### Unweighted Props

| Item        | Slot     | Maximum Polycount |
| ----------- | -------- | ----------------- |
| Hats        | p_head   | 5,000             |
| Glasses     | p_eyes   | 2,500             |
| Earrings    | p_ears   | 1,000             |
| Left Wrist  | p_lwrist | 1,000             |
| Right Wrist | p_rwrist | 1,000             |

---

## Level of Detail (LOD) Requirements

### Medium LOD

* Aim for 50% or less of the high LOD polycount.
* Maintain silhouette quality while reducing geometry.

### Low LOD

* Under 1,000 polygons whenever possible.
* Vanilla GTA V averages approximately 100–400 polygons.

### LOD Materials

LOD models should:

* Use dedicated materials.
* Use diffuse textures only.
* Avoid embedded texture maps.

---

# Custom MLO Requirements

## Quality Standards

MLOs should:

* Match GTA V's visual style.
* Fit the surrounding environment.
* Maintain realistic scale and proportions.
* Support smooth third-person camera movement.
* Include intuitive navigation and layouts.

### Recommended Practices

* Proper vertex lighting.
* Baked lighting where applicable.
* Optimized collision meshes.
* Thoughtful environmental storytelling.

---

## Optimization Requirements

MLOs must pass performance review.

### Texture Standards

* Limited use of 2K textures.
* No 4K textures.
* Texture dictionaries must be used.
* Embedded textures are prohibited.

### LOD Requirements

Large-scale exterior modifications must include:

* Custom LOD models.
* Proper streaming distances.
* Dedicated LOD files.
* Separate YMAP structures.

Custom LODs must never overwrite vanilla files.

---

# Custom Vehicle Requirements

## Quality Standards

Vehicles must:

* Match GTA V's quality standards.
* Fit a modern-day roleplay environment.
* Include properly configured LODs.
* Maintain realistic proportions.

---

## Optimization Requirements

Vehicles must pass performance testing.

### Texture Standards

* Limited 2K texture usage.
* No 4K textures.
* Efficient material usage.
* Proper texture dictionaries.

### Model Standards

Vehicles should:

* Include functional LODs.
* Use optimized geometry.
* Avoid unnecessary detail.
* Follow GTA V vehicle conventions.

---

# Final Notes

Disband RP reserves the right to request revisions to any submitted Asset prior to approval.

Meeting these guidelines does not guarantee acceptance. Final approval decisions are made based on quality, optimization, compatibility, server needs, and overall fit within the Disband RP community.
