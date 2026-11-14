# mlr-ex08 — leaf classifier on the phone

Live page: **https://cervenypanda.github.io/mlr-ex08/**

A single `index.html` that classifies leaves (apple, cherry, chestnut, maple) from the
phone's rear camera with `leaf_model.onnx`. The network runs in the browser with
ONNX Runtime Web; no image leaves the phone.

| File | What it is |
| --- | --- |
| `index.html` | the page: live camera, photo upload, check against the notebook, QR code |
| `leaf_model.onnx` | the model exported from the notebook (Task 2e) |
| `model_info.json` | classes, input size, mean and std of the preprocessing |
| `check_image.jpg`, `check_expected.json` | one validation image and the notebook's probabilities for it |
