Wrapper for CUDA profiler start/stop API functions. Zero dependencies.

Example:
```python
import cudaprofile

cudaprofile.start()
# ... do expensive cuda stuff ...
cudaprofile.stop()
```
and run the script from `nvprof` or `nvvp`.

You may want to use `nvprof` with `--profile-from-start-off` and only call `start()` when desired.
