# 🚀 Crash course into Astro & Storyblok

This is a workshop blog example of how to use [Astro](https://astro.build) with [Storyblok](https://www.storyblok.com) as a headless CMS.

![blog screenshot](https://a.storyblok.com/f/251047/3837x2014/9824a3f3db/blog_screenshot.png)

## 📖 Workshop Notion
> [!NOTE]
> Keep [this workshop Notion](https://www.notion.so/storyblok/CityJS-Berlin-Crash-course-into-Astro-and-Storyblok-5b5f2f27eeb84a0cbb849ab9d22f173c?pvs=4) next to you to check when you work on. It contains all the steps and explanations.

> [!IMPORTANT]
> 🚨 This workshop has a few different steps and modifications from [Astro Storyblok Ultimate Tutorial](https://www.storyblok.com/tp/the-storyblok-astro-ultimate-tutorial) to fit in time. You can follow the rest of the steps from the URL link to add i18n, popular articles, article overview page, and deploy into production.

## ❓ FAQ
- Where I should look when I get lost during the workshop? → Jump to the relevant branch following the name of the tutorial part. (i.e. Go to `part-1` branch when you get lost in **Ultimate Tutorial part 1**)

- I don't think my environment variable is working. → Make sure you have `.env` file in the **root directory** and it has `STORYBLOK_TOKEN` variable with your Storyblok **preview** API key token. (i.e. `STORYBLOK_TOKEN=your-token`)

- Storyblok CLI retunrs errors when I run `storyblok push-components` → Logout once if you already have used Storyblok CLI. Then, login again with `storyblok login` command.

```bash
storyblok logout
storyblok login
```

## 📝 Additional resources
- [@storyblok/create-demo](https://github.com/storyblok/storyblok-create-demo)
- [Storyblok CLI](https://github.com/storyblok/storyblok-cli)