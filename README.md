New language
--------------

To add new language as submodule please create github repo, then run here (before run please replace `<language>`):
```bash
git submodule add --name <language> https://github.com/codenjoyme/codenjoy-<language>-client.git
git mv codenjoy-<language>-client/ <language>
```