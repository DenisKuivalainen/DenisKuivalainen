## Hi, I'm Denis Kuivalainen
 
Full-stack software developer with ~4 years of commercial experience, based in the EU and working remotely. I build backend services and the infrastructure they run on - most recently as a Fullstack Developer at **Reactron Technologies Oy** (Apr 2022 – Nov 2025).
 
I like problems where the interesting part is the plumbing: streaming data through a pipeline without buffering it, transcoding video off a work queue, retargeting a skeleton inside an undocumented binary format, or getting a whole environment to come up from one `terraform apply`.
 
### What I work with
 
| | |
|---|---|
| **Languages** | TypeScript / JavaScript, Python, Kotlin, C#, PHP, Lua |
| **Backend** | Node.js, Ktor, ASP.NET Core, Azure Functions, AWS Lambda |
| **Frontend** | React, Next.js, React Router, MUI, Tailwind |
| **Data** | PostgreSQL, MySQL, SQLite, DynamoDB, Cosmos DB, SQLAlchemy, jOOQ |
| **Cloud & infra** | AWS (CDK, Lambda, S3, SQS, API Gateway, RDS, Secrets Manager), Azure (Functions, Cosmos DB, Key Vault), Oracle Cloud, Terraform, Serverless Framework, Docker, LocalStack, GitHub Actions |
 
### Projects

**[edopro_web](https://github.com/ygovfproject/edopro_web)** - a browser client for EDOPro, the open-source Yu-Gi-Oh! duel simulator, so people can play online duels without installing the game. The client speaks the game's binary network protocol itself, rebuilds the duel board from the server's game messages. Browsers can't open raw TCP sockets, so a small Node.js proxy with no dependencies bridges WebSockets to the game servers. The same proxy hosts accounts and cloud deck storage on SQLite, with rate limits and daily cleanup. It runs on Oracle Cloud's free tier, set up and updated with Terraform, and the site deploys to GitHub Pages.
*TypeScript · Next.js · React · MUI · Node.js · WebSockets · SQLite · Terraform · Oracle Cloud*

**[transform-cgf](https://github.com/DenisKuivalainen/transform-cgf)** - reverse-engineered binary format work: parses CryEngine `.cgf` character meshes, rebuilds the bone table for an older skeleton, re-weights every vertex, and reskins surfaces using nearest-neighbour Gaussian interpolation over hand-fitted control points. Volunteer work for one Aion server, which uses it to add new character skins.
*Python · NumPy · pyffi · computational geometry*
 
**[dogtube](https://github.com/DenisKuivalainen/dogtube)** - a self-hosted video platform, and the biggest thing here. Kotlin/Ktor backend with a resumable chunked upload protocol, an ffmpeg transcoding pipeline driven by a background queue, HTTP range-request playback, a premium content tier, and a React Router 7 frontend with an admin area and analytics.
*Kotlin · Ktor · PostgreSQL · jOOQ · ffmpeg · React · TypeScript*
 
**[dogtube-filler-script](https://github.com/DenisKuivalainen/dogtube-filler-script)** - a traffic simulator that drives synthetic but plausible usage against Dogtube: generates users, watch sessions, likes, comments and subscriptions so the platform has realistic data to work with.
*Python · SQLAlchemy · Faker*

 
### Contact
 
- [LinkedIn](https://www.linkedin.com/in/denis-kuivalainen/)
- kuivalainendenis@gmail.com
- +358 46 950 1022
