# beanstalk-website

The published Beanstalk website (static files). Served by GitHub Pages at
https://poohbear2.github.io/beanstalk-website/

Do not edit these files by hand. The source is in the app project at `beanstalk/apps/web`; rebuild and copy with:

```bash
node apps/web/scripts/publish.mjs https://poohbear2.github.io /beanstalk-website ~/apps_I_build/beanstalk-website
```

Then commit and push this folder.
