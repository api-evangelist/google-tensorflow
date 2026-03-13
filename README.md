# Google TensorFlow (google-tensorflow)
Google TensorFlow is an open-source machine learning framework that provides APIs and tools for building, training, and deploying ML models. Its developer APIs include TensorFlow Serving for running model inference via REST, TensorFlow Hub for discovering and reusing pre-trained models, and TensorFlow Model Analysis for evaluating model performance at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Machine Learning, Deep Learning, AI, Model Serving, Open Source, Google

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-03-13

## APIs

### TensorFlow Serving REST API
TensorFlow Serving provides a REST API for serving trained TensorFlow models in production environments. The API supports model prediction (inference), classification, and regression requests against deployed models. It allows specifying model names and versions, and returns predictions in JSON format. TensorFlow Serving handles model lifecycle management, versioning, and concurrent request processing.

**Human URL:** [https://www.tensorflow.org/tfx/serving/api_rest](https://www.tensorflow.org/tfx/serving/api_rest)


#### Tags:

 - Model Serving, Inference, Predictions

#### Properties

- [Documentation](https://www.tensorflow.org/tfx/serving/api_rest)
- [OpenAPI](openapi/tensorflow-serving-openapi.yml)
- [JSONSchema](json-schema/google-tensorflow-predict-request-schema.json)

### TensorFlow Hub API
TensorFlow Hub provides a repository of reusable trained machine learning models. The API allows developers to search, discover, and download pre-trained models and model components (SavedModels, TF.js models, TFLite models) that can be reused for transfer learning and inference in new applications.

**Human URL:** [https://tfhub.dev](https://tfhub.dev)


#### Tags:

 - Models, Transfer Learning, Pre-trained Models

#### Properties

- [Documentation](https://www.tensorflow.org/hub)

### TensorFlow Model Analysis API
TensorFlow Model Analysis (TFMA) provides tools and APIs for evaluating TensorFlow models. It enables computing metrics over large datasets using Apache Beam, slicing evaluation results across different features, and tracking model performance over time for validation and monitoring purposes.

**Human URL:** [https://www.tensorflow.org/tfx/model_analysis/get_started](https://www.tensorflow.org/tfx/model_analysis/get_started)


#### Tags:

 - Model Evaluation, Metrics, Analysis

#### Properties

- [Documentation](https://www.tensorflow.org/tfx/model_analysis/get_started)

## Common Properties

- [GettingStarted](https://www.tensorflow.org/learn)
- [Pricing](https://www.tensorflow.org)
- [SDKs](https://www.tensorflow.org/install)
- [Support](https://www.tensorflow.org/community)
- [Status](https://github.com/tensorflow/tensorflow)
- [JSON-LD](json-ld/google-tensorflow-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
