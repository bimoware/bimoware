```ts
new User()
.addPersonalInfo({
    realName: process.env.REALNAME,
    username: 'Bimoware',
    age: 18,
    birthday: ['26','03','2007'],
    country: { name: 'Morocco', code: 'MA' }
})
.addTools({
    web: ['React', 'Next.js', 'Tailwind CSS', 'Node.js', 'Express.js'],
    mobile: null, // TODO: Learn React Native
    desktop: null, // TODO: Learn Electron
    database: null, // TODO: Learn PostgreSQL, SQLite or Firebase..
    cloud: ['Vercel'], // TODO: Stop being poor lmao
    design: ['Figma'],
    other: ['Github Desktop', 'Discord']
})
.setOS('Windows') // TODO: Try Linux
.setLanguages(['English', 'French', 'Arabic']) // TODO: Learn Japenese?
.setHobbies(['Programming', 'Music', 'Gaming']) // TODO: Get a life
.setSocials([
    { name: 'Discord', username: 'bimoware', token: process.env.DISCORD_TOKEN },
    { name: 'Github', username: 'bimoware' },
    { name: 'Instagram', username: process.env.INSTAGRAM_USERNAME }
])
.setProjects([
    {
        ready: true,
        priority: true,
        name: 'bimowy',
        slug: 'bimoware/bimowy',
        description: 'Auto-generated math training platform.',
        link: 'https://bimowy.dev/'
    },
    {
        ready: false,
        name: 'portfolio',
        slug: null,
        link: 'https://bimo.dev/'
    },
    {
        ready: false,
        priority: false,
        name: 'better-instagram',
        slug: 'bimoware/better-instagram',
        description: 'My better version of instagram. With a mix of Discord & Snapchat, all with astonishing UI design.',
        link: null
    }
])
.start()
```
<div align="center">

| I ... | Tools |
| - | - |
| am active on | [![My Skills](https://go-skill-icons.vercel.app/api/icons?i=stackoverflow,github,instagram&theme=dark&perline=15)](https://skillicons.dev) |
| work with | [![My Skills](https://go-skill-icons.vercel.app/api/icons?i=vercel,git,npm,next,discord,discordjs,svg,nodejs,pygame,py,react,tailwind,ts,vscode,canva&theme=dark&perline=15)](https://skillicons.dev) |
| used to work with | [![My Skills](https://go-skill-icons.vercel.app/api/icons?i=sqlite,css,html,obsidian,notion,sublime,nextjs,materialui,vscodium,mongodb,notion,opencv,replit&theme=dark&perline=15)](https://skillicons.dev) |
| unfortunatly forced to use | [![My Skills](https://go-skill-icons.vercel.app/api/icons?i=windows,chrome,chromium&theme=dark&perline=15)](https://skillicons.dev) |
| barely figure out | [![My Skills](https://go-skill-icons.vercel.app/api/icons?i=mysql,regex,latex,figma,robloxstudio,supabase&theme=dark&perline=15)](https://skillicons.dev) |
| plan on trying | [![My Skills](https://go-skill-icons.vercel.app/api/icons?i=bun,deno,electron,express,firebase,go,java,lua,ruby,sass,svelte,swift,androidstudio,arcbrowser&theme=dark&perline=15)](https://skillicons.dev) |
| am scared of | [![My Skills](https://go-skill-icons.vercel.app/api/icons?i=angular,latex,c,cs,cpp,godot,graphql,netlify,flutter,desmos,bootstrap,dotnet,figma,kotlin,neovim,nim,pnpm,postgres,rust,threejs&theme=dark&perline=15)](https://skillicons.dev) |
</div>
