A tutorial example of a program that draws a triangle. Written in C language, for **MacOS**.

<img width="200" alt="image" src="https://github.com/ingram12/vulkan_api_first_triangle_c_lang/assets/2664683/be2c8bc3-422f-4c31-b843-b2d57bbf90cd">

For compile shaders:
```
/path/to/VulkanSDK/1.3.268.1/macOS/bin/glslc shader.frag -o frag.spv
/path/to/VulkanSDK/1.3.268.1/macOS/bin/glslc shader.vert -o vert.spv
```

To compile `main.c` without VScode you need to run something like:
```
/usr/bin/clang -g /path/to/main.c -o /path/to/main -I/path/to/glfw/3.3.8/include -I/path/to/cglm/0.8.9/include -I/path/to/VulkanSDK/1.3.268.1/macOS/include -L/path/to/glfw/3.3.8/lib -L/path/to/cglm/0.8.9/lib -lglfw -L/path/to/VulkanSDK/1.3.268.1/macOS/lib -lvulkan
```
