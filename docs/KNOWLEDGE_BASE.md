# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM.
> No LLMs. No tokens. Pure static analysis. See more [here](https://github.com/grisuno/ReadMenator)

**Total Files Parsed:** 1 | **Total Symbols Extracted:** 7 | **Total Imports:** 2

## Structural Knowledge Map
```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray:5 5,color:#aaa;
    main_py["main.py (py)"]
    class main_py mod;
    main_py_Block["Block"]
    class main_py_Block cls;
    main_py --> main_py_Block
    main_py_Blockchain["Blockchain"]
    class main_py_Blockchain cls;
    main_py --> main_py_Blockchain
    main_py___init__["__init__"]
    class main_py___init__ fn;
    main_py --> main_py___init__
    main_py_calculate_hash["calculate_hash"]
    class main_py_calculate_hash fn;
    main_py --> main_py_calculate_hash
    main_py___init__["__init__"]
    class main_py___init__ fn;
    main_py --> main_py___init__
    ext_hashlib["hashlib"]
    class ext_hashlib ext;
    main_py -.->|imports| ext_hashlib
    ext_json["json"]
    class ext_json ext;
    main_py -.->|imports| ext_json
```

---

## Architecture Reference

### PY (1 files)

#### `main.py`
**Path:** `main.py`

**Classes:**
- `Block` (line 4) `class Block`
- `Blockchain` (line 16) `class Blockchain`

**Functions:**
- `__init__` (line 5) `def __init__(self, index, timestamp, data, previous_hash)`
- `calculate_hash` (line 12) `def calculate_hash(self)`
- `__init__` (line 17) `def __init__(self)`
- `create_genesis_block` (line 21) `def create_genesis_block(self)`
- `add_block` (line 25) `def add_block(self, data)`
