# saasland.com-BE

[SaaS Land](https://saasland.com) brings together all the latest blogs, videos, and training for SaaS on AWS.
![SaaSLand](/resources/slandpipeline.png)

This is SaaS Land repository. It is split into 2 components:
Part 1: The front-end, an auto-building static website.
Part 2: The backend, am automated content aggregation workflow.

**Part 1: Automated content aggregation** (the backend application):
### [Code](/backend) | [Blog](https://aws.amazon.com/blogs/compute/building-serverless-land-part-1-automating-content-aggregation/)

![backend](/resources/backend.png)

**Part 2: An auto-building static site** (the front-end site)
### [Code](/frontend) | [Blog](https://aws.amazon.com/blogs/compute/building-serverless-land-part-2-an-auto-building-static-site/) 

This is a static website that automatically aggregates content from a number of RSS feeds. The content exists in static JSON files, which generate a new site build each time they are updated. The result is a low-maintenance, low-latency serverless website, with almost limitless scalability.

![frontend](/resources/frontend.png)
