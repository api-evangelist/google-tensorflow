# Google TensorFlow (google-tensorflow)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
