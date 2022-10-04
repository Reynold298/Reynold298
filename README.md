- 👋 Hi, I’m @Reynold298
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Reynold298/Reynold298 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
https://github.com/leecher1337/ntvdmx64/issues/65#issuecomment-540013118
Just to clarify what's what:

OpenNT: the name of the project that no longer exists

old-src: the original hack-job to build the leaked NT 4 source code as is with minimal amount of changes; it comes with its own build environment. I referred to it as old/obsolete because the original plan was to get all the components refactored into the MinNT and other component-specific repositories, as the original NT 4 source tree is just a big mess.

MinNT (Minimal NT): initiative to isolate only the essential core components (such as kernel and subsystems) out of the leaked NT 4 source code and refactor them to NT 5.1-esque source tree; the MinNT repository does not come with its own build environment and uses NTOSBE as its build environment.

NTOSBE (NT Operating System Build Environment): the unified build environment for OpenNT Project. The main goal was to provide single unified build environment that can be used to build all OpenNT components (not including then-declared-obsolete old-src, of course).
🚀
