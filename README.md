# ML-Deployment-Architecture-Zoo

## System architectures
- U-Net to perform image segmentation | [Reference](https://theaisummer.com/deep-learning-production/) | [Pic](https://theaisummer.com/static/fd0f5f2bafd32d6e18d40a1d5312f758/d8f62/full-system-architecture.png)
- Flask with Nginx and uWSG | [Reference](https://theaisummer.com/uwsgi-nginx/) | [Pic w/o Nginx](https://theaisummer.com/static/3bc002a80c39d1e6c423a1da33585f97/c0388/uwsgi.png) | [Pic with Nginx](https://theaisummer.com/static/262c3377a828afecc2fa0f099886f428/91e7e/nginx.png)
- Flask with Nginx and uWSG in Docker containers | [Reference](https://theaisummer.com/docker/) | [Pic](https://theaisummer.com/static/3a5039d102228b995182c4f97e30e179/eb645/docker-flask-tensorflow-uwsgi-nginx.png)
- Introduction to Kubernetes with Google Cloud: Deploy your Deep Learning model effortlessly | [Reference](https://theaisummer.com/kubernetes/) | [Architecture w/o k8s](https://theaisummer.com/static/6cd65865454a470166023923fbcb3136/cac9f/modern-app-design.png) | [Architecture with k8s](https://theaisummer.com/static/a302684341347a8e633b8bbe3329fba8/63b67/app-with-kubernetes-design.png)
- Stock Market Kafka Real Time Data Engineering Project | [Reference](https://github.com/darshilparmar/stock-market-kafka-data-engineering-project) | [Pic](https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/Architecture.jpg)
- Smart City e2e Realtime Data Engineering Project with Kafka, Spark, Athena and Redshift | [Reference](https://www.youtube.com/watch?v=Vv_fvwF41_0&t=3s)
- Realtime Data Streaming using Airflow, Spark, Kafka and Cassandra |  [Reference](https://github.com/airscholar/e2e-data-engineering) | [Pic](https://github.com/airscholar/e2e-data-engineering/blob/main/Data%20engineering%20architecture.png)
- AI chatbot with Streamlit, OpenAI, LangChain, PineCone, FastAPI | [Reference](https://www.linkedin.com/posts/danleedata_curious-about-how-to-build-an-%3F%3F-%3F%3F%3F%3F%3F%3F%3F-activity-7194018029007945728-gpQ8?utm_source=combined_share_message&utm_medium=member_android) | [Pic](https://media.licdn.com/dms/image/D4D22AQGdML84CgZ1SQ/feedshare-shrink_2048_1536/0/1715187541272?e=2147483647&v=beta&t=UAP0xTeae86QbgWAEbK_3V3wjen3660-WPatLCceP7s)
- How to fine tune a LLM model and deplopy it (Weights and Biases, Hydra, DVC, ONNX, Docker, FastAPI, GitHub Actions, AWS ECR, AWS Lambda, Kibana) | [Reference](https://github.com/graviraja/MLOps-Basics?tab=readme-ov-file) | [Pic](https://github.com/graviraja/MLOps-Basics/blob/main/images/summary.png)
***

## Step-by-step guide
- How to scale your DL application in the cloud using GCP xx steps | [Reference]() | [Step #1](https://theaisummer.com/static/9f4ba7de6f896cda85ca80d09f1048cd/eb645/one-instance.png) | [Step #2](https://theaisummer.com/static/eadc14719c0a025d2709d52f4dac7dbc/eb645/ci-cd.png) | [Step #3](https://theaisummer.com/static/f447929a1f3624263861ee936110dc9c/eb645/vertical-scaling.png) | [Step #4](https://theaisummer.com/static/0d51a1402766e4a5095fc8c85a87937d/eb645/horizontal-scaling.png) | [Step #5](https://theaisummer.com/static/74b861df449a29ef4416e01906b74d6a/eb645/scaling-out.png) | [Step #6](https://theaisummer.com/static/1c8d6df851c30ccab364a7ea28f2e822/eb645/cache.png) | [Step #7](https://theaisummer.com/static/08f941a0f6861a898c6e5e03e22d0b75/eb645/error-reporting.png) | [Step #8](https://theaisummer.com/static/3c0b6cb4ece0dda52d4c882c2bf94264/eb645/retrain.png) | [Step #9](https://theaisummer.com/static/ae52892e7790aa9d181e9e9399239d7f/eb645/offline-inference.png) 
***

## Cloud provider offering
- [AWS cloud services cheat sheet](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_lossy/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F915d1659-0779-460e-b71f-a7dd9d812556_1415x1536.gif)
- [Azure cloud services cheat sheet](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_lossy/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc905b80e-685f-4145-a12c-02d704f70efd_1414x1536.gif)
***

## Comparisons
- [How a big data pipeline would look like in AWS, GCP and Azure](https://www.ml4devs.com/articles/scalable-efficient-big-data-analytics-machine-learning-pipeline-architecture-on-cloud/)
- [AWS Redshift vs. AWS Athena](https://www.chaossearch.io/blog/when-to-deploy-aws-redshift-or-athena-use-cases)
- [API zoo](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff4e965c2-b545-4f79-a489-e0e72d473c06_1109x1600.png?utm_source=substack&utm_medium=email)
- [Statefull vs. stateless applications](https://www.redhat.com/en/topics/cloud-native-apps/stateful-vs-stateless)
***

## Decision diagrams
- [SQL vs. NoSQL](https://www.ml4devs.com/articles/datastore-choices-sql-vs-nosql-database/)
- [Amazon Sagemaker vs. Anyscale Endpoints vs. FastAPI vs. OpenLLM vs. NVIDIA Triton Inference Server](https://outerbounds.com/blog/the-many-ways-to-deploy-a-model/?utm_source=substack&utm_medium=email)
- [Semantic versioning](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fefaeb917-d62e-4f04-b3bc-0644d50fa948_800x988.gif)
***

## Utilities
- A free, open-source API for generating random user data. [Link](https://randomuser.me/)
- [Best way to test system functionality](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd18e5226-8335-4455-909d-5a6ef98747a6_1280x1664.gif)
***

## Databases
- [Database shrading](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F571827ac-b3da-44a3-886a-8ca9770bb443_1337x1600.png?utm_source=substack&utm_medium=email)
- [Database scaling strategies](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0f560185-6b26-4359-ae8a-123b44d8884a_1345x1536.gif)
- [CRUD and RDB](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd7e87813-2921-4379-a1c9-c101092fda5d_1241x1600.png?utm_source=substack&utm_medium=email)
***

## How to scale
- [8 must-know strategies to scale your system](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_lossy/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff2497aa7-95ab-45b0-a8f7-0af03b663342_1280x1683.gif)
***
