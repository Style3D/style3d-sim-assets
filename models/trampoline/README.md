# Trampoline Models

All vertex positions in these OBJ files have their z coordinate set to `0`.

The outermost ring of each model consists of the following vertices. Indices
are **zero-based** and ranges are **inclusive**, referring to the order of
vertex position (`v`) records in each OBJ file.

| OBJ file | Outermost ring vertex indices | Vertex count in ring |
| --- | --- | --- |
| `trampoline_v93.obj` | `0–15` | 16 |
| `trampoline_v176.obj` | `0–31` | 32 |
| `trampoline_v977.obj` | `0–63` | 64 |
| `trampoline_v1051.obj` | `0–127` | 128 |

OBJ face records use one-based vertex indices. Add `1` to the indices above
when referring to vertices in face records.
