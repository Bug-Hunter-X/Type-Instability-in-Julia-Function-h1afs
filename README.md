# Julia Type Instability Example

This repository demonstrates a common performance issue in Julia: type instability.  The `myfunction` in `bug.jl` suffers from this issue. The `bugSolution.jl` shows how to improve it.

**Bug:** The `myfunction` returns different types based on input resulting in type instability.

**Solution:** Using type annotations to ensure consistent return type.