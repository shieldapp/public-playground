# ⚠️ public-playground ⚠️
Testing out GitHub features that require a public repository.

## GitHub Workflow Environment Test
The `.github/workflows/environment-test.yml` workflow shows how it's possible to require a review on a specific environment before continuing the workflow using [Reviewing deployments](https://docs.github.com/en/actions/managing-workflow-runs/reviewing-deployments).

Furthermore, the above-mentioned workflow also shows how the jobs can be triggered based on the output from the previous job.

### GitHub Environment use-case

Check out the flow charts in the following cases:

**[Reviewing Deployment Required](https://github.com/shieldapp/public-playground/actions/runs/676588957)**

*Before review*
![image](https://user-images.githubusercontent.com/4225398/112024610-a94eb500-8b34-11eb-8836-a3a5925b857f.png)


*After review*
![image](https://user-images.githubusercontent.com/4225398/112026595-a654c400-8b36-11eb-99b4-fa77981b44a8.png)


**[Automatic Deployment](https://github.com/shieldapp/public-playground/actions/runs/676547108)**

![image](https://user-images.githubusercontent.com/4225398/112026872-ec118c80-8b36-11eb-9867-a509459567c9.png)


### More on GitHub Environment
Using GitHub Environments also provides deployment information such as:

**Branch deployment status**

![image](https://user-images.githubusercontent.com/4225398/112026116-2b8ba900-8b36-11eb-8f59-09ccd309f2ef.png)

**Deployment activity**

![image](https://user-images.githubusercontent.com/4225398/112027329-5de9d600-8b37-11eb-908b-0298147408e8.png)
