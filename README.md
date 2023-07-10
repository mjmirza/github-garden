# github-garden

🌳 Transforming your Github stats into a lush green oasis, fueled by the magic of Github Actions, powered by [Github Actions](https://github.com/features/actions)

[![Auto commit](https://github.com/mjmirza/github-garden/workflows/Auto%20commit/badge.svg)](https://github.com/mjmirza/github-garden/actions?query=workflow%3A%22Auto+commit%22)

![](screenshoot.png)

## Make it your own

- Create your own repo with click "**Use this template**" button (forked repo will not work)

Or just do in the manual way:

- Create your own repo
- Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- Change the `email` and `name` information on file [autocommit.yml, line 29 and 30](.github/workflows/autocommit.yml#L29)
- Change the scheduling time on file [autocommit.yml, line 10](.github/workflows/autocommit.yml#L10). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` .
- Consider to support me, at least click the 🌟 button

## Repo using this github-garden

- You can add your repo here


## Credits

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)


---

© 2023 Crafted by Mirza Iqbal

