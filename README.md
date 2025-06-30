# Final Project Reflection

## How do I approach designing software?
I usually start by listing out what the program needs to do and who will use it. Then I sketch a simple outline of modules or components (for example, “scene setup,” “object drawing,” “input handling”) and think about how they interact. I try to keep each part focused on a single responsibility so it’s easier to tweak later.

---

## What new design skills did I learn working on this project?
- **Organizing scene elements**: Breaking the scene into logical parts (desk, monitor, mug, books) helped me keep the code clean.  
- **Using loops and arrays**: Turning the book stack into a loop with size arrays made it much faster to adjust all the books at once.  
- **Separating materials from geometry**: Defining materials in one place and applying them later meant I could play with looks without rewriting draw code.

---

## What was my design process for the project?
1. **Reference study**: I studied the 2D image to note proportions and lighting.  
2. **Blocking out shapes**: I placed simple, untextured shapes to get rough positions.  
3. **Refinement**: I adjusted scales and positions in small steps until things lined up.  
4. **Texturing & materials**: Once the geometry felt right, I added textures and tuned UV scales.  
5. **Lighting**: I added a main light, then a subtle spot for the monitor glow, tweaking intensities for a natural feel.

---

## How could I use these design tactics in the future?
- **Start simple**: Block out major shapes first, then refine details.  
- **Parameterize**: Keep key values (sizes, offsets) in arrays or variables, so I can tweak them easily.  
- **Iterate**: Make small changes, test, and repeat—this prevents getting lost in big rewrites.

---

## How do I approach developing programs?
I follow an incremental approach: implement a small feature, test it, then move on. I keep functions and classes focused, write clear comments, and commit often so I can rollback if something breaks.

---

## What new development strategies did I use here?
- **Central transform function**: I made `SetTransformations` handle scale, rotate, translate in one call.  
- **Texture registry**: I built a simple system to load textures once and reference them by name.  
- **Mesh reuse**: I loaded each mesh (plane, box, cylinder, etc.) just once, then drew it multiple times with different transforms.

---

## How did iteration factor into my development?
Every tweak—whether changing a book’s tilt or the light color—was a small step. I rarely wrote big blocks of code at once. Instead, I made one change, checked the result, then repeated. This kept my progress visible and bugs easy to isolate.

---

## How did my development approach evolve over the milestones?
- **Milestone 1**: I focused on getting basic shapes in place.  
- **Milestone 2**: I refactored repetitive code into loops and arrays (e.g., the book stack).  
- **Milestone 3**: I separated materials and added a multi-light setup.  
- **Milestone 4**: I added a blurred background, fine-tuned lighting, and polished UVs.

---

## How can computer science help me reach my goals?
Studying CS gives me a systematic way to solve problems and build real applications. The skills I’ve practiced—modular design, debugging, version control—will apply to almost any tech field I choose.

---

## How will computational graphics help me in my future?
- **Educational path**: I now have a better grasp of linear algebra and shader basics, which will help in advanced graphics or simulation courses.  
- **Professional path**: The workflow I used (prototyping, parameter tuning, lighting rigs) is similar to what game studios and VR firms use, so this experience is directly transferable.

