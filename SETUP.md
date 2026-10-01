# Setup

## Upload to the profile repository

Repository:

https://github.com/longhn0710/longhn0710

Copy the files in this package into the repository root.

Example:

```bash
git clone git@github.com:longhn0710/longhn0710.git
cd longhn0710

# copy the package contents here, then:
git add .
git commit -m "feat(profile): add personal GitHub profile"
git push origin master
```

## Pinned repositories

Pinned repositories are configured in the GitHub UI, not in README.md.

Open your profile and choose **Customize your pins**.

Suggested pins:

1. jenkinsci/ansible-tower-plugin, if GitHub offers it in the pin selector
2. devsecopslonghn/fund-management-helm-chart
3. devsecopslonghn/card-credit-helm-chart
4. devsecopslonghn/ansible-playbook-api
5. devsecopslonghn/database-manager
6. devsecopslonghn/fund-management-mcp

## Metrics workflow

`.github/workflows/metrics.yml` is optional.

It is intentionally configured for manual execution only. To use it:

1. Create a GitHub Personal Access Token with the minimum permissions required by lowlighter/metrics.
2. Add it to the repository as a secret named `METRICS_TOKEN`.
3. Run the workflow manually.
4. If desired, uncomment the schedule block.

Do not commit a token into the repository.

## Notes

The main profile feature only requires `README.md` in the special `longhn0710/longhn0710` repository.
