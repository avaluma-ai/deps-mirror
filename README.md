# deps-mirror

Public mirror of third-party build dependencies whose upstream download disappeared.
The files are unmodified upstream artifacts, published as release assets (not in the Git history).
Nix fetches them by URL and verifies them against the pinned hash.

| Release tag | File | Upstream | License |
|---|---|---|---|
| `onnxruntime-v1.31.0` | `onnxruntime-linux-x64-gpu_cuda12-1.31.0.tgz` | `github.com/microsoft/onnxruntime` (no longer reachable, 2026-11) | MIT, see [licenses/onnxruntime/](licenses/onnxruntime/) |

sha256 of `onnxruntime-linux-x64-gpu_cuda12-1.31.0.tgz`:
`62d3af5269af2143b5d37494337573f1ffb8885f3ad7477ae0cb1cc79c8dedfd`
(SRI `sha256-YtOvUmmvIUO103SUM3Vz8f+4iF8610d64Mscx5yN7f0=`)

Only add unmodified upstream files whose license allows redistribution, with their license
texts under `licenses/<name>/`. Nothing internal belongs in this repository: it is public.
