# .github


## README.md automation

- [`.github/workflows/update.yml`](https://github.com/geoffreygarrett/.github/blob/36bdda2afec950f73fc412d4a34b24c7c4859643/.github/workflows/update.yml#L9) determines how often to update. See [cron docs](https://www.netiq.com/documentation/cloud-manager-2-5/ncm-reference/data/bexyssf.html) for modifying this behaviour.
- [`.github/profile/src/update.py`](https://github.com/geoffreygarrett/.github/blob/36bdda2afec950f73fc412d4a34b24c7c4859643/profile/src/update.py#L110) determines how many seconds need to pass before the launch cached launch data is written over with new data with a `GET` request from the public API.
