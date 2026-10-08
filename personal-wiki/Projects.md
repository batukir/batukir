# Selected projects
[Overview](Home.md) · [Skills](Skills.md) · [All repositories](Repositories.md)

## NewsLens

**AI workflows, source-aware analysis, and evaluation**

NewsLens compares how different outlets cover the same story. It groups related articles, extracts factual claims, identifies disagreements, and runs a grading pass on the comparison results.

The engineering centers on a LangGraph pipeline with separate extraction, comparison, and grading nodes. Claims and disagreements use structured models, and source quotations accompany the analysis. Bundled sample stories and labeled findings support a precision/recall evaluation workflow.

The project combines a FastAPI application, embedding-based clustering, an OpenAI-compatible model interface, tests for non-LLM pipeline components, and Docker configuration.

[Repository and setup](https://github.com/batukir/llm-agent-news-contradiction-detector) · [Pipeline implementation](https://github.com/batukir/llm-agent-news-contradiction-detector/blob/main/app/agent/graph.py) · [Evaluation](https://github.com/batukir/llm-agent-news-contradiction-detector/blob/main/eval/run_eval.py)

## PulseCheck

**Background processing, scheduling, and operational visibility**

PulseCheck explores uptime monitoring through Django, Redis, and django-q2. Scheduled jobs queue HTTP checks, completion hooks update monitor state, and digest tasks aggregate results for email summaries.

The implementation includes task chains, result retention, database-driven email templates, queue inspection commands, and deliberate timeout/failure examples. Together, these make asynchronous execution concrete and easier to inspect during development.

[Repository and setup](https://github.com/batukir/pulsecheck) · [Task implementation](https://github.com/batukir/pulsecheck/blob/main/monitors/tasks.py)

## Football Clubs

**React application development and relational API design**

Football Clubs connects a React interface to Django REST Framework. Users browse club records, create and edit details, and confirm deletions. Forms combine reusable input components with Formik and Yup; the table presents related data through Material React Table.

The backend models countries and leagues with foreign keys and characteristics with a many-to-many relationship. Serializers return both relationship IDs and readable nested details, allowing the frontend to edit records and display meaningful labels.

[Repository and setup](https://github.com/batukir/football-clubs-react-django) · [Data models](https://github.com/batukir/football-clubs-react-django/blob/main/backend/api/models.py) · [Serializers](https://github.com/batukir/football-clubs-react-django/blob/main/backend/api/serializers.py)

## GraphQL Project Manager

**Schema design, relationships, and application state changes**

This application organizes clients and projects through React and GraphQL. Queries retrieve individual records and collections; mutations create clients and projects, update project status, and delete records. Mongoose models connect the schema to MongoDB.

The frontend separates queries, mutations, forms, and pages. The schema resolves a project's associated client, giving the application a clear relationship between its domain entities.

[Repository](https://github.com/batukir/CRUD-GraphQL) · [GraphQL schema](https://github.com/batukir/CRUD-GraphQL/blob/main/server/schema/schema.js)

## Analytics Dashboard

**Data-rich interfaces and frontend state management**

The dashboard combines React, Redux Toolkit, Material UI, and Nivo to present sales, products, customers, transactions, geography, and performance. Dedicated screens, chart components, data-grid controls, and backend domain modules organize the application around different reporting needs.

[Repository](https://github.com/batukir/redux-dashboard) · [Dashboard screens](https://github.com/batukir/redux-dashboard/tree/main/client/src/scenes)

## Additional work

- [Social Media App](https://github.com/batukir/social-media-app): React profile and feed screens with an Express/Mongoose backend, bcrypt password hashing, and JWT authentication.
- [TripCoach](https://github.com/batukir/tripcoach): React routing and interactive Leaflet maps driven by travel preferences and world-city data.
- [XML Form](https://github.com/batukir/dp-technical): TypeScript and Material UI inputs that generate a downloadable XML document.
- [Browser Object Detection](https://github.com/batukir/tensorflow.js): COCO-SSD webcam inference with on-screen object boxes and intersection logic.
- [LangGraph Workshop](https://github.com/batukir/LangGraph-workshop): Practical exercises in graph flow, RAG, memory, drafting, and ReAct agents.
