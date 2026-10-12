Yes — I’d add the new control directly into your existing structure rather than creating too many separate categories. The key additions are **Subject Part**, **Framing / Crop**, **Camera Position**, and **Point of Focus**.

Here is your updated section with those added and the iPhone example expanded:

# 08-ref-lrn-prompt

Reference and learning guide for **AI image prompting**.

---

## Image Prompting

| Category                | Subcategories                                                             | Description                                                |
| ----------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------- |
| **Subject**             | Person, Animal, Object, Product, Character                                | Defines the main subject.                                  |
| **Subject Part**        | Face, Head, Hands, Engine, Wheel, Screen, Lens, Handle                    | Defines which specific part of the subject is shown.       |
| **Appearance**          | Face, Hair, Clothing, Body, Materials, Colors                             | Describes how it looks.                                    |
| **Pose & Action**       | Standing, Sitting, Walking, Holding, Running                              | Defines position or action.                                |
| **Environment**         | Studio, Indoor, Outdoor, Forest, City, Beach                              | Defines where it is.                                       |
| **Composition**         | Close-up, Medium Shot, Full Body, Wide Shot, Centered                     | Defines image arrangement.                                 |
| **Framing / Crop**      | Full View, Partial View, Tight Crop, Extreme Close-up                     | Controls how much of the subject is visible in the frame.  |
| **Camera Position**     | Front, Behind, Above, Below, Inside, Beside                               | Defines where the camera is physically positioned.         |
| **Camera Angle**        | Eye-level, Low Angle, High Angle, Top-down, Bottom-up                     | Defines the direction the camera looks at the subject.     |
| **View / Orientation**  | Front View, Rear View, Side View, Three-quarter Front, Three-quarter Rear | Defines which side or orientation of the subject is shown. |
| **Point of Focus**      | Face, Engine, Wheel, Lens, Stitching, Logo                                | Defines the specific area that receives visual attention.  |
| **Lighting**            | Natural, Studio, Soft, Dramatic, Backlight, Golden Hour                   | Defines how the subject is illuminated.                    |
| **Style**               | Realistic, Cinematic, Anime, Illustration, 3D, Editorial                  | Defines the visual style.                                  |
| **Background**          | Plain, White, Black, Transparent, Blurred, Detailed                       | Defines what appears behind the subject.                   |
| **Color**               | Palette, Monochrome, Warm, Cool, Contrast                                 | Defines the color treatment.                               |
| **Materials & Texture** | Metal, Leather, Fabric, Glass, Wood, Skin                                 | Defines surface appearance.                                |
| **Details**             | Features, Accessories, Patterns, Surface Details                          | Adds specific visual details.                              |
| **Mood**                | Calm, Dark, Energetic, Dramatic, Peaceful                                 | Defines the atmosphere.                                    |
| **Perspective**         | First Person, Third Person, Wide, Distortion                              | Defines spatial viewpoint.                                 |
| **Aspect Ratio**        | 1:1, 4:5, 3:4, 16:9, 9:16                                                 | Defines image proportions.                                 |
| **Constraints**         | No Text, No Logo, Single Subject, Clean Background                        | Controls what should or should not appear.                 |
| **Negative Prompting**  | Remove Objects, Avoid Artifacts, Avoid Styles                             | Specifies unwanted elements.                               |
| **Image Editing**       | Add, Remove, Replace, Extend, Change, Restore                             | Defines changes to an existing image.                      |
| **Reference Images**    | Image-to-Image, Style, Character, Product                                 | Uses an image to guide the result.                         |
| **Consistency**         | Character, Product, Clothing, Environment                                 | Keeps elements consistent.                                 |
| **Product Photography** | Product Shot, Studio, Commercial, Catalog                                 | Focuses on product presentation.                           |
| **Portraits**           | Headshot, Half Body, Full Body, Fashion                                   | Focuses on people and faces.                               |
| **Landscape**           | Nature, Mountains, Forest, Cityscape, Architecture                        | Focuses on environments and scenes.                        |
| **Characters**          | Design, Outfit, Pose, Expression, Turnaround                              | Focuses on fictional or stylized characters.               |

---

## Prompt Building

| Order | Category                | Purpose                                      |
| ----: | ----------------------- | -------------------------------------------- |
|    01 | **Subject**             | What is in the image?                        |
|    02 | **Subject Part**        | Which specific part is shown?                |
|    03 | **Appearance**          | What does it look like?                      |
|    04 | **Pose / Action**       | What is it doing?                            |
|    05 | **Environment**         | Where is it?                                 |
|    06 | **Composition**         | How is it arranged?                          |
|    07 | **Framing / Crop**      | How much of the subject is visible?          |
|    08 | **Camera Position**     | Where is the camera physically located?      |
|    09 | **Camera Angle**        | Which direction is the camera looking?       |
|    10 | **View / Orientation**  | Which side or orientation is shown?          |
|    11 | **Point of Focus**      | What specific area gets attention?           |
|    12 | **Lighting**            | How is it illuminated?                       |
|    13 | **Style**               | What visual style is used?                   |
|    14 | **Background**          | What appears behind the subject?             |
|    15 | **Color**               | What colors are used?                        |
|    16 | **Materials & Texture** | What does the surface look and feel like?    |
|    17 | **Details**             | What specific details are included?          |
|    18 | **Mood**                | What feeling or atmosphere does it have?     |
|    19 | **Perspective**         | From what spatial viewpoint is it seen?      |
|    20 | **Aspect Ratio**        | What are the image proportions?              |
|    21 | **Constraints**         | What should or should not appear?            |
|    22 | **Negative Prompting**  | What unwanted elements should be avoided?    |
|    23 | **Reference Images**    | What existing image should guide the result? |
|    24 | **Consistency**         | What elements need to remain consistent?     |
|    25 | **Image Editing**       | What should be changed in an existing image? |

---

# Example 01 — iPhone 17 Product Showcase

## Category Breakdown

| Category               | Example                                                     |
| ---------------------- | ----------------------------------------------------------- |
| **Subject**            | iPhone 17                                                   |
| **Subject Part**       | Camera module and rear upper section                        |
| **Appearance**         | Premium smartphone, titanium frame, clean modern design     |
| **Pose / Action**      | Standing upright                                            |
| **Environment**        | Minimalist studio                                           |
| **Composition**        | Product centered, close-up                                  |
| **Framing / Crop**     | Tight crop around the upper rear section                    |
| **Camera Position**    | Positioned slightly above and behind the phone              |
| **Camera Angle**       | Slight high angle                                           |
| **View / Orientation** | Rear three-quarter view                                     |
| **Point of Focus**     | Camera lenses and polished titanium edges                   |
| **Lighting**           | Soft studio lighting, subtle rim light                      |
| **Style**              | Premium commercial product photography                      |
| **Background**         | Clean minimal background                                    |
| **Details**            | Detailed camera lenses, polished edges, realistic materials |
| **Constraints**        | No hands, no people, no text, no extra objects              |

## Complete Prompt

```text
A premium iPhone 17 smartphone,
clean modern design with a titanium frame,
standing upright in a minimalist studio,

showing only the upper rear section of the phone,
tight crop around the camera module,
camera positioned slightly above and behind the phone,
slight high-angle camera,
rear three-quarter view,

camera lenses and polished titanium edges as the main point of focus,

soft studio lighting with a subtle rim light,
premium commercial product photography,
detailed camera lenses, polished edges, realistic materials,
clean minimal background,

no hands, no people, no text, no extra objects.
```

---
