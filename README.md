# test-repo-for-github-action

 act pull_request_target -e /Users/jayghiya/Documents/unoplat/unoplat-observability-prom-stack/.github/local-github-workflows/pr-opened.json -s KUBE_CONFIG="~/.kube/config" -s GITHUB_TOKEN="$(gh auth token)" -s GITHUB_RUN_ATTEMPT="1" -W .github/workflows/container-vuln-analysis-and-fix.yaml --container-architecture linux/arm64