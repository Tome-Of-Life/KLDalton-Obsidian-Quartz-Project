This is a personal learning Quartz installation. See the [documentation](https://quartz.jzhao.xyz/)  for how to get started.
# [# Obsidian / Quartz / GitHub Pages Template:Hosting](https://quartz.jzhao.xyz/hosting)

GitHub repository for Quartz. If you haven’t already, [make sure you do so](https://quartz.jzhao.xyz/setting-up-your-GitHub-repository)

[#-get-started](https://quartz.jzhao.xyz/#-get-started)

Quartz requires **at least [Node](https://nodejs.org/) v20** and `npm` v9.3.1 to function correctly. Ensure you have this installed on your machine before continuing.
	NOTE: Currently running on GITHUB for deployment: 
[Deployment_Web](content/index/Deployment_Web/Deployment_Web.md) 
	NOTE: Direct Quartz Web Deployment to DOCS directory.
			## GitHub Pages
			Patient need for update to happen after uploads.
			github-pages Last[deployed](https://github.com/Tome-Of-Life/KLDalton-Obsidian-Quartz-Project/actions/runs/11313728035/job/31462832481) # minutes ago

[https://tome-of-life.github.io/KLDalton-Obsidian-Quartz-Project/](https://tome-of-life.github.io/KLDalton-Obsidian-Quartz-Project/)
# Obsidian / Quartz / GitHub Pages Template:CI Deployment Section

Deployed URL: https://defenderofbasic.github.io/obsidian-quartz-template

Template for hosting your Obsidian notebook on GitHub pages with CI deployment. 

## Basic setup

Full tutorial with screenshots & videos: https://dev.to/defenderofbasic/host-your-obsidian-notebook-on-github-pages-for-free-8l1. {LOCAL} [A:\GitHub\obsidian\obsidian-quartz-template](File://A:\GitHub\obsidian\obsidian-quartz-template)

It's basically (1) fork this (2) go to repo's "Settings" > "Pages", Under "Build and Deployment" select GitHub Actions. Then go to "Actions" and enable GitHub actions for your fork. Edit the pages in [source/content](./source/content) with Obsidian or any text editor. It generates HTML using [Quartz](https://github.com/jackyzha0/quartz) {LOCAL} [A:\GitHub\obsidian\quartz_jackyzha0](A:\GitHub\obsidian\quartz_jackyzha0).  To generate the HTML locally, run `npx quartz build --serve` in `./source/`
**==NOTE: Currently deleted as had issue with the fork from original as stated above.==**

## Raw HTML pages

There is a [source/raw_html](./source/raw_html) folder that gets copied into the build folder in CI. This lets you host arbitrary HTML outside of quartz. Example: https://defenderofbasic.github.io/obsidian-quartz-template/raw-html-test.html

I made the "raw HTML" option for people who are generating HTML UI's with Claude/ChatGPT but want to tweak them/host them themselves. Or make a personal archive of web pages, etc.

## Further customization

> Quartz is meant to be extremely configurable, even if you don’t know any coding. Most of the configuration you should need can be done by just editing [quartz.config.ts](quartz.config.ts) or changing the layout in [quartz.layout.ts](quartz.layout.ts)
> NOTE: Setup {EXT}{DOT}ts to default to NOTEPAD++

https://quartz.jzhao.xyz/configuration

Created with [Quartz v#](https://quartz.jzhao.xyz/), © 2024

- [GitHub](https://github.com/jackyzha0/quartz)
- [Discord Community](https://discord.gg/cRFFHYye7t)