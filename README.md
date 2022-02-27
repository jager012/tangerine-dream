# tangerine-dream
Tangerine dark theme for Gitea

## Screenshots
![tangerine-1](https://user-images.githubusercontent.com/77502609/155892175-3433c107-4caa-4cfd-b490-9f8df9122bf7.png)
![tangerine-2](https://user-images.githubusercontent.com/77502609/155892177-9243a643-870e-42ca-ad0e-3ed679197ab6.png)
![tangerine-3](https://user-images.githubusercontent.com/77502609/155892178-5bef6778-9b3c-49fb-9a8f-00f5ad587e08.png)
![tangerine-4](https://user-images.githubusercontent.com/77502609/155892179-9d158aef-fc14-4084-ab3f-aa9a3401a57e.png)
![tangerine-5](https://user-images.githubusercontent.com/77502609/155892180-cc3718eb-4a05-4a60-80fd-3cfc43768e89.png)
![tangerine-6](https://user-images.githubusercontent.com/77502609/155892182-1d8b122c-f867-4647-a381-c572646128a4.png)
![tangerine-7](https://user-images.githubusercontent.com/77502609/155892183-f74554c1-bf26-409b-b9de-cc6f0e381207.png)
![tangerine-8](https://user-images.githubusercontent.com/77502609/155892184-9ac0582f-ddd0-40ac-8f63-a1fbc8a6d4dc.png)
![tangerine-9](https://user-images.githubusercontent.com/77502609/155892186-d752320d-d2aa-4033-982c-7e60247eb0e1.png)

## Installation
> See also [Customizing the look of Gitea](https://docs.gitea.io/en-us/customizing-gitea/#customizing-the-look-of-gitea)
- Copy `theme-tangerine-dream.css` to `$GITEA_PUBLIC/public/css`
- Edit the `[ui]` section of `app.ini`
  - Add `tangerine-dream` to the `THEMES` setting. This setting should be a comma-separated list of the themes you want to be available on your setup (_e.g._ `THEMES = gitea,tangerine-dream`)
  - If you want to set this theme as default, add `DEFAULT_THEME = tangerine-dream`
- Restart gitea
