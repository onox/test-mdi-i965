Draws two triangles using ARB_shader_draw_parameters extension with the i965 Mesa driver.

Expected colors: blue and blue

| Architecture | Generation | Mesa      | Actual colors  |
|--------------|------------|-----------|----------------|
| Ivy Bridge   | 7.0        | ?         | Red and yellow |
| Haswell      | 7.5        | ?         | ?              |
| Broadwell    | 8.0        | ?         | ?              |
| Sky Lake     | 9.0        | ?         | ?              |
| Kaby Lake    | 9.5        | 18.0.5    | Blue and blue  |

Required GL extensions:

  - ARB_shader_draw_parameters
  - ARB_direct_state_access
  - ARB_multi_draw_indirect

Dependencies:

```sh
sudo apt install --no-install-recommends libglfw3-dev libglew-dev pkgconf g++-7
```

Compile and run:

```sh
./compile-mdi.sh
./mdi
```
