# Sample project for https://github.com/renovatebot/renovate/discussions/25090

* Run like:
```
docker run --rm -e RENOVATE_TOKEN=$GITHUB_TOKEN -e RENOVATE_PLATFORM=github -e LOG_LEVEL=debug -e RENOVATE_AUTODISCOVER=false -e RENOVATE_REPOSITORIES=mfriedenhagen/renovate-does-pause  renovate/renovate:36.67.1 --dry-run
```

* Please run like: `mvn --activate-profiles external clean verify`
