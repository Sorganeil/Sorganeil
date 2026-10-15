# About me

Full-stack dev and web security researcher, doing this for a few years now. I like building things and I like taking them apart to see how they work.

Outside of web dev I'm into appsec, reverse engineering, networking and systems programming.

## What I do

- Full-stack: web apps, APIs, backend services
- Security research: mostly web apps, finding bugs and exploiting them
- Reverse engineering: usually for game modding
- Infra: Linux, networking, databases, server admin

## What I use

I'm not doing the 40-badge thing. Plenty of profiles list every logo they've ever seen, and AI made it worse. This is what I actually use:

- TypeScript for frontend
- Go for backend and most other things. Simple, quick to write, and more than fast and efficient enough for most tasks.
- C++ when Go won't cut it: low-level stuff, native interop, game mods
- MongoDB when a document model fits
- MySQL when the data is relational

### Why not Rust?

Most of my low-level work is C interop or stuff that's unsafe by nature. So I'd end up writing a lot of `unsafe` Rust, which is awkward, and I'd lose most of the memory safety that makes Rust worth it.

Go handles about 90% of what I do. I ship faster with it, and the performance and memory gains I'd get from Rust usually wouldn't be noticeable for my projects. For the other 10% I'd rather just write C++. If the code is unsafe anyway, I'll take native C interop and a bigger, more mature ecosystem.

Rust is fine. It just doesn't fit what I build.

## How I work

I spend a lot of time on research and planning before writing code, sometimes more than on the code itself. I don't have a fixed stack. I like comparing options, looking at the trade-offs, and picking what fits the project.

Bad decisions early on are expensive to undo, so I'd rather get them right the first time.
