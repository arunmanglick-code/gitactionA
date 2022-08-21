# github-actions-course
# Quick Questions:
# 1. What is difference between Action and Command
# 2. How to use output of a step in another step (gittogether\gitactionA\.github\workflows\02_actions.yml)
# 3. Can you run github action on PR pull_request: Closed & ReOpened (gittogether\gitactionA\.github\workflows\03_pullreqeust.yml)
# 4. How to run github actions on a cron schedule (gittogether\gitactionA\.github\workflows\04_cronschedule.yml)
# 5. How to run github actions against any activity that happens outside of GitHub (gittogether\gitactionA\.github\workflows\05_repositorydispatch.yml)
# 6. How you use Workflow/Job/Step level variables (gittogether\gitactionA\.github\workflows\06_env.yml)
# 7. How to print on which event name on which github triggered (gittogether\gitactionA\.github\workflows\06_env.yml)
# 8. What are various default Github event variables (https://docs.github.com/en/actions/learn-github-actions/environment-variables)
# 9. What is Workflow_dispatch in GitHub Actions? - This action triggers another GitHub Actions workflow, using the workflow_dispatch event. The workflow must be configured for this event type e.g. on: [workflow_dispatch] This allows you to chain workflows, the classic use case is have a CI build workflow, trigger a CD release/deploy workflow when it completes.
# 10. Use of Docker Container in addtion to runs-on in Github Actions (https://youtu.be/abJ00EesfZA)
# 11. Setting default values for jobs (https://docs.github.com/en/actions/using-jobs/setting-default-values-for-jobs)
# 12. What is the use of 'paths' - It specifies which files must have been modified in order to run the workflow
# 