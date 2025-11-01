# RKNN Modified YOLO11 ONNX Export

This is a fork of the Rockchip repository for exporting modified YOLO11 to ONNX format. Modifications make it more suitable to run on Rockchip NPU.

All I added is installation script/instructions with UV and model path as CLI argument.

## Installation

```bash
uv venv
```

```bash
uv pip install -e ".[dev]"
```

```bash
uv pip install onnx onnxscript
``` 

```bash
uv run --no-sync ultralytics/engine/exporter.py {model_path}
```

