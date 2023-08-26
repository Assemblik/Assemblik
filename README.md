name: Example
uses: lowlighter/metrics@latest
with:
  template: repository
  filename: metrics.repository.svg
  token: ${{ secrets.METRICS_TOKEN_WITH_SCOPES }}
  user: lowlighter
  repo: metrics
  plugin_lines: yes
  plugin_followup: yes
  plugin_projects: yes
  plugin_projects_repositories: lowlighter/metrics/projects/1
