# e2e-mock-demo
End-to-end demo of a simple project that creates a Customer Lifetime Value (CLV) prediction model using Featuretools' mock customer data

.
├── .github
│   └── workflows
│       ├── ci.yaml
│       ├── cd.yaml
│       └── security.yaml
├── components
│   ├── train_model
│   │   ├── component.py
│   │   ├── Dockerfile
│   │   ├── requirements.txt
│   │   └── tests
│   │       └── test_train_model.py
│   └── upload_model
│       ├── component.py
│       ├── Dockerfile
│       ├── requirements.txt
│       └── tests
│           └── test_upload_model.py
├── pipelines
│   ├── training_pipeline.py
│   └── deployment_pipeline.py
└── README.md
