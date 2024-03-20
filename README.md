**helm chart templates**
1. Create Helm Chart
helm create flip-chart

2. Set Up Helm Chart Repository Using GitHub Pages:
Ensure you have a GitHub repository for hosting your Helm charts.
Create a gh-pages branch in your GitHub repository for GitHub Pages.
Add your Helm chart files to this branch.

3. Setup Helm Chart Repository:
- Replace https://github.com/daviinaa/helm-chart/ with your GitHub repository URL.
helm repo add flip-repo https://daviinaa.github.io/helm-chart/

4. Verify Repository Addition:
helm repo list

5. Package Helm Chart:
helm package flip-chart

6. Update Helm Chart Repository Index:
helm repo index .
