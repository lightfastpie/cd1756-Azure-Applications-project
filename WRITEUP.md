# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
  ## VM
- Vms would provide lower up front cost to host the app as you dont need hardware. However, they are more expensive than app services.
- Allows you full control over the environment and infrastructure
- Supports linux and windows
- Flexibility in how optimized/compute heavy you want the VM to be, but also can be more time consuming for the developer.
- High Scalability and Availability

  ## App service

- Vertical and Horizontal scaling
- Better for lightweight services or minimal computational needs
- Only need to focus on the application and not the infrastructure
- Hardware limitations
- Support multiple languages, but also limited to those languages

### I chose the App Service option due to easier deployment. As a solo developer, it makes it easier to not think about the infrastructure requirements to deploy my app and let me focus on the development portion. In addition, hosting the Article CMS does not need much computational power unless it is very highly used and trafficked site. The scalability options would be useful for small to medium traffic to the app. I also believe that a VM would not be within my monthly budget.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*
### If there was a high security need, VMs are better for that purpose. VMs would also be better if the app had a large number of users (high traffic). If the site was expanding heavily, I would consider switching to VMs.
