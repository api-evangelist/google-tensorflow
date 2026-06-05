# Google TensorFlow (google-tensorflow)

Google TensorFlow is an open-source machine learning framework providing APIs and tools for building, training, and deploying ML models, including TensorFlow Serving for model inference and TensorFlow Hub for reusable model components.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- Deep Learning
- Google
- Machine Learning
- Model Serving
- Open Source

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### TensorFlow Serving REST API

TensorFlow Serving provides a REST API for serving trained TensorFlow models in production environments. The API supports model prediction (inference), classification, and regression requests against deployed models. It allows specifying model names and versions, and returns predictions in JSON format. TensorFlow Serving handles model lifecycle management, versioning, and concurrent request processing.

- **Human URL:** [https://www.tensorflow.org/tfx/serving/api_rest](https://www.tensorflow.org/tfx/serving/api_rest)
- **Base URL:** `http://localhost:8501`

#### Tags

- Inference
- Model Serving
- Predictions

#### Properties

- [Documentation](https://www.tensorflow.org/tfx/serving/api_rest)
- [OpenAPI](openapi/tensorflow-serving-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tensorflow-serving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tensorflow-serving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-tensorflow-predict-request-schema.json) — [JSON Schema](https://json-schema.org/specification)

### TensorFlow Hub API

TensorFlow Hub provides a repository of reusable trained machine learning models. The API allows developers to search, discover, and download pre-trained models and model components (SavedModels, TF.js models, TFLite models) that can be reused for transfer learning and inference in new applications.

- **Human URL:** [https://tfhub.dev](https://tfhub.dev)
- **Base URL:** `https://tfhub.dev`

#### Tags

- Models
- Pre-Trained Models
- Transfer Learning

#### Properties

- [Documentation](https://www.tensorflow.org/hub)
- [Postman Collection](collections/tensorflow-serving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tensorflow-serving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TensorFlow Model Analysis API

TensorFlow Model Analysis (TFMA) provides tools and APIs for evaluating TensorFlow models. It enables computing metrics over large datasets using Apache Beam, slicing evaluation results across different features, and tracking model performance over time for validation and monitoring purposes.

- **Human URL:** [https://www.tensorflow.org/tfx/model_analysis/get_started](https://www.tensorflow.org/tfx/model_analysis/get_started)
- **Base URL:** `https://localhost`

#### Tags

- Analysis
- Metrics
- Model Evaluation

#### Properties

- [Documentation](https://www.tensorflow.org/tfx/model_analysis/get_started)
- [Postman Collection](collections/tensorflow-serving.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tensorflow-serving.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/tensorflowdev)
- [Getting Started](https://www.tensorflow.org/learn)
- [Pricing](https://www.tensorflow.org)
- [S D Ks](https://www.tensorflow.org/install)
- [Support](https://www.tensorflow.org/community)
- [Status Page](https://github.com/tensorflow/tensorflow)
- [JSON-LD](json-ld/google-tensorflow-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
