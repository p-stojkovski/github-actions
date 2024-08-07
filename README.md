# github-actions

### Continuous intergation, delivery and deployment
- Continuous intergation responsibilities are validation the build and generating artifacts (compiling the app, run the tests, linting the code, making sure the format matches what you expect).
- Continuous delivery doesn't deploy all the way to production without a manual stop, you have to click a button that says deploy to prod, and that's the only manual step.
- Continuous deployment which is as you deploy through different environments if all deployments are successfull then it deploys all the way to prod without any manual stop.
![image](https://github.com/user-attachments/assets/8d5670f6-28ae-4f6f-b403-ea588891c9bc)
![image](https://github.com/user-attachments/assets/d2c50551-eb99-4920-b685-52b0ad28d55d)

### GitHub Actions Glossary
- Workflow = Everything
- Triggers = What starts a Workflow
- Jobs = Series of steps
- Steps = An individual task
- Runners = VMs that run jobs
