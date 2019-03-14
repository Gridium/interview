## Question 1

As data arrives in our system throughout the day, we run a memory- and CPU-intensive analytics process. Each run reads data from a database and writes output to CSV files, and takes 10-20 minutes to run. We run about 3,000 processes a day.

In one or two paragraphs (200 words maximum), describe a possible design for this system using AWS. From a devops perspective, which tools, technologies, or services would you use, and why? How would you monitor the system, so that you can tell what's going wrong?

There's no right answer -- I'm interested in your experience, opinions, and ability to explain your recommendations.

## Question 2

You are tasked with setting up the infrastructure for a REST API that customers will access from the public internet. The API server(s) need access to a common database that contains valuable private information. The number of requests per minute is known and is unlikely to change much over time, but there is a high-availability requirement --- customers will be unsatisfied if the API is unavailable for several minutes during a deploy.

In one or two paragraphs, outline a design for this system in AWS and how your deploy automation would work, including diagrams if needed. What infrastructure/networking decisions can you incorporate into your design to improve security?

