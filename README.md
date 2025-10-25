KubeGlide 🚀

KubeGlide is a single-page web app that simulates the core value of a developer-centric Platform Engineering tool. This MVP is designed to showcase how abstraction and immediate feedback can solve key Kubernetes user pain points related to complexity, security, and cost opacity.

This project is live! Check it out here: https://waltqiii.github.io/kubeglide/

(Note: You will need to take a screenshot of your app, name it kubeglide_screenshot.png, and add it to the root of your repo for the image to work)

The Problem It Solves

Kubernetes is powerful but notoriously complex for development teams. Common pain points include:

YAML Complexity: Writing and maintaining complex YAML files is difficult and error-prone.

Security Bottlenecks: Security misconfigurations are common and often caught too late in the "shift-left" process.

Cost Opacity: It's very difficult to understand the true cost of running a service, leading to budget overruns.

How KubeGlide Addresses This

This MVP simulates a platform that provides three layers of value:

Developer-Centric Abstraction: A simple UI (the "Application Deployment Blueprint") abstracts away all the YAML. Developers just define what they need, not how to build it.

Proactive Policy Enforcement: Integrated policy checks (like "Production requires >= 3 replicas" or "Image must be secure") run before deployment, giving developers instant feedback.

Unified Visibility: A single dashboard provides immediate, simulated feedback on cost (FinOps) and logs, eliminating the need to check multiple tools.

How to Use

Open the live app.

Fill out the "Application Deployment Blueprint" form.

Try to deploy with "bad" inputs (e.g., nginx:latest or 1 replica in Production).

Observe the "Policy Check Status" and "Logs" provide immediate, actionable error messages.

Try to deploy with "good" inputs (e.g., my-app:1.2-secure and 3 replicas in Production) and see the success messages.
