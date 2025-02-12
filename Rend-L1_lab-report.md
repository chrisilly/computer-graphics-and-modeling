**Chris Illy Culling**

Lap report for DA307A **ASSIGNMENT 1**

11-02-2025

# Cube

In order to learn how to work with the framework, I made a `cube.h` and `cube.cpp` identical to `QuadModel` (inheriting from `Model`).

I tried instantiating and rendering my (alleged) "cube" object by mimicking lines for the pre-existing `Model* m_quad;` and `Model* m_sponza;` objects in:

1. `OurTestScene::Init()`
2. `OurTestScene::Update(...)` (I gave my `m_cube` an `m_cube_transform` to match `m_quad`'s `m_quad_transform`)
3. `OurTestScene::Render()`

After dealing with a confusing linker error, I finally realised that I needed to add my new files to the `Source Files` of the Visual Studio Solution Explorer. I really wish there was a `launch.json` and `task.json` included in the GitHub repository for VSCode users.

