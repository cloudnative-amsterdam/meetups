## Speaker Jan van der Vegt

- Name: Jan van der Vegt
- Affiliation: CEO at Cubonacci
- Bio: Jan is a data scientist that spent a lot of time thinking about improving the way we manage the lifecycle of machine learning models. He started Cubonacci in 2018 with the goal to build a platform to give more autonomy to data science teams to get their models to production. The whole platform runs on Kubernetes and leverages autoscaling to an extreme degree to manage the highly dynamic payloads required for machine learning flows.
- Region: Amsterdam
- Have you spoke before at our community events?: Not yet
- Able to travel: Yes, around the Randstad
- Talk 1 abstract: 3d autoscaling. Cubonacci leverages the cluster autoscaler, the horizontal pod autoscaler and the vertical pod autoscaler to continuously adapt to the needs of our users. In this talk we will showcase how each component helps us manage the machine learning payloads.
- Talk 2 abstract: Metacontroller for CRDs. Using custom resource definitions allows developers building applications on top of Kubernetes to allow for higher layers of abstractions. Next to registering these CRDs at the Kubernetes API you need a controller to manage other resources based on the declarative instances of the CRDs. First we will look at the patterns that happen with controllers. After this we will go into Metacontroller. Metacontroller is a project that makes it easier to create CRD controllers by tracking the state for you and communicating with your custom API.