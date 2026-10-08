# root

*Community 0 | 1 files | cohesion 1.00*

## Definition

This community groups 1 file(s) rooted at `root` with dominant language py (cohesion 1.00). Central symbols: `Block`, `Blockchain`, `__init__`, `add_block`, `calculate_hash`, `create_genesis_block`. Core file: `main.py` (7 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `main.py` | py | utility | 7 | no |

## Key Symbols

- `Block` (class, `main.py:4`) `class Block`
- `__init__` (method, `main.py:5`) `def __init__(self, index, timestamp, data, previous_hash)`
- `calculate_hash` (method, `main.py:12`) `def calculate_hash(self)`
- `Blockchain` (class, `main.py:16`) `class Blockchain`
- `__init__` (method, `main.py:17`) `def __init__(self)`
- `create_genesis_block` (method, `main.py:21`) `def create_genesis_block(self)`
- `add_block` (method, `main.py:25`) `def add_block(self, data)`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 0
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 1 file(s) lack file-level docs (e.g. `main.py`)? What purpose do they serve?
- What would break if the most connected file in root changed?
- Should root be split, given cohesion 1.00?

## Sources

- `main.py`
