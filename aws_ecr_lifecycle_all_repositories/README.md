# AWS ECR LifeCycle Put-Policy for all your repositories
There was not an easy way to apply a lifecycle policy for all of your ECR images as of 09/2019. Here is an easy way to apply a policy that expires images older than 30 revisions ago that are untagged.

Requires AWS ECR access.
