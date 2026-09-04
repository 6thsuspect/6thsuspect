import {
  Github,
  Linkedin,
  Mail,
  ExternalLink,
  Code2,
  Building2,
  Cable,
  Layers3,
  GitFork,
  Star,
  ArrowUpRight,
} from "lucide-react";

const projects = [
  {
    name: "Section Designer",
    description:
      "Interactive structural section analysis and reinforcement design tool.",
    language: "TypeScript",
    icon: Layers3,
    stars: "★",
    github: "https://github.com/6thsuspect/Section-designer",
    tags: ["RCC", "Steel", "Section Analysis"],
  },
  {
    name: "Structural Node Designer",
    description:
      "Visual programming environment for structural engineering workflows.",
    language: "TypeScript",
    icon: Code2,
    stars: "★",
    github: "https://github.com/6thsuspect/structural-node-designer",
    tags: ["React", "Engineering", "Automation"],
  },
  {
    name: "Cable Profile Analysis Tool",
    description:
      "Analysis and visualization of suspension cable profiles and forces.",
    language: "Python",
    icon: Cable,
    stars: "★",
    github: "https://github.com/6thsuspect/cable-profile-analysis-tool",
    tags: ["Cable", "Structural", "Python"],
  },
  {
    name: "RCC Section Check",
    description:
      "Engineering tool for reinforced concrete section calculations.",
    language: "TypeScript",
    icon: Building2,
    stars: "★",
    github: "https://github.com/6thsuspect/rcc-section-check",
    tags: ["RCC", "Design", "Indian Codes"],
  },
];

const skills = [
  "Structural Engineering",
  "Bridge Design",
  "RCC Design",
  "PSC Design",
  "Steel Structures",
  "Finite Element Analysis",
  "Engineering Automation",
  "Python",
  "TypeScript",
  "React",
  "Electron",
  "Excel VBA",
  "STAAD.Pro",
  "MIDAS",
  "Sofistik",
];

function App() {
  return (
    <div className="min-h-screen bg-[#05080d] text-white selection:bg-emerald-500/30">
      {/* Background */}
      <div className="pointer-events-none fixed inset-0 overflow-hidden">
        <div className="absolute left-1/2 top-[-300px] h-[600px] w-[900px] -translate-x-1/2 rounded-full bg-emerald-500/10 blur-[140px]" />
        <div className="absolute bottom-[-200px] right-[-200px] h-[500px] w-[500px] rounded-full bg-cyan-500/5 blur-[120px]" />
      </div>

      <div className="relative mx-auto max-w-7xl px-6">
        {/* NAVBAR */}
        <header className="flex h-20 items-center justify-between border-b border-white/10">
          <a
            href="#"
            className="flex items-center gap-3 font-mono text-sm font-bold"
          >
            <div className="flex h-9 w-9 items-center justify-center rounded-lg border border-emerald-400/30 bg-emerald-400/10 text-emerald-400">
              6S
            </div>

            <span className="hidden sm:block">6thsuspect</span>
          </a>

          <nav className="hidden items-center gap-8 text-sm text-gray-400 md:flex">
            <a href="#about" className="transition hover:text-white">
              About
            </a>

            <a href="#projects" className="transition hover:text-white">
              Projects
            </a>

            <a href="#stack" className="transition hover:text-white">
              Stack
            </a>

            <a href="#contact" className="transition hover:text-white">
              Contact
            </a>
          </nav>

          <a
            href="https://github.com/6thsuspect"
            target="_blank"
            rel="noreferrer"
            className="flex items-center gap-2 rounded-lg border border-white/10 px-4 py-2 text-sm transition hover:border-emerald-400/40 hover:bg-white/5"
          >
            <Github size={17} />
            GitHub
          </a>
        </header>

        {/* HERO */}
        <section className="relative flex min-h-[650px] items-center py-24">
          <div className="max-w-4xl">
            <div className="mb-7 inline-flex items-center gap-2 rounded-full border border-emerald-400/20 bg-emerald-400/5 px-4 py-2 font-mono text-xs text-emerald-400">
              <span className="h-2 w-2 animate-pulse rounded-full bg-emerald-400" />
              ENGINEERING × SOFTWARE
            </div>

            <h1 className="text-5xl font-bold leading-[1.05] tracking-tight sm:text-6xl lg:text-8xl">
              Structural
              <br />

              <span className="bg-gradient-to-r from-white via-emerald-200 to-emerald-500 bg-clip-text text-transparent">
                Engineering
              </span>

              <br />

              <span className="text-gray-500">reimagined in code.</span>
            </h1>

            <p className="mt-8 max-w-2xl text-lg leading-8 text-gray-400">
              Bridge Design Engineer building practical engineering software
              for structural analysis, design automation and visualization.
            </p>

            <div className="mt-10 flex flex-wrap gap-4">
              <a
                href="#projects"
                className="group flex items-center gap-2 rounded-xl bg-emerald-500 px-6 py-3 font-semibold text-black transition hover:bg-emerald-400"
              >
                Explore Projects
                <ArrowUpRight
                  size={17}
                  className="transition group-hover:translate-x-1 group-hover:-translate-y-1"
                />
              </a>

              <a
                href="https://github.com/6thsuspect"
                target="_blank"
                rel="noreferrer"
                className="flex items-center gap-2 rounded-xl border border-white/10 px-6 py-3 font-semibold transition hover:border-white/30 hover:bg-white/5"
              >
                <Github size={18} />
                github.com/6thsuspect
              </a>
            </div>
          </div>

          {/* Hero decoration */}
          <div className="absolute bottom-10 right-0 hidden w-[380px] lg:block">
            <div className="relative rounded-3xl border border-white/10 bg-white/[0.025] p-6 backdrop-blur-xl">
              <div className="mb-6 flex items-center justify-between">
                <span className="font-mono text-xs text-gray-500">
                  STRUCTURAL_SYSTEM
                </span>

                <span className="text-xs text-emerald-400">ONLINE</span>
              </div>

              <div className="space-y-3 font-mono text-xs">
                <div className="flex justify-between border-b border-white/5 pb-3">
                  <span className="text-gray-500">DISCIPLINE</span>
                  <span>BRIDGE DESIGN</span>
                </div>

                <div className="flex justify-between border-b border-white/5 pb-3">
                  <span className="text-gray-500">MATERIAL</span>
                  <span>RCC / PSC / STEEL</span>
                </div>

                <div className="flex justify-between border-b border-white/5 pb-3">
                  <span className="text-gray-500">AUTOMATION</span>
                  <span>PYTHON / VBA</span>
                </div>

                <div className="flex justify-between">
                  <span className="text-gray-500">SOFTWARE</span>
                  <span>REACT / ELECTRON</span>
                </div>
              </div>
            </div>
          </div>
        </section>

        {/* STATS */}
        <section className="grid grid-cols-2 overflow-hidden rounded-2xl border border-white/10 bg-white/[0.02] md:grid-cols-4">
          <Stat value="6+" label="Years Engineering" />
          <Stat value="20+" label="Engineering Tools" />
          <Stat value="15+" label="Technologies" />
          <Stat value="∞" label="Problems to Automate" />
        </section>

        {/* ABOUT */}
        <section id="about" className="py-28">
          <SectionTitle
            eyebrow="01 / ABOUT"
            title="Engineer first. Builder always."
          />

          <div className="grid gap-10 md:grid-cols-2">
            <div>
              <p className="text-xl leading-9 text-gray-300">
                I work at the intersection of{" "}
                <span className="text-white">structural engineering</span> and{" "}
                <span className="text-emerald-400">
                  software development
                </span>
                .
              </p>

              <p className="mt-6 leading-8 text-gray-500">
                My work focuses on bridges, RCC, prestressed concrete and steel
                structures. Alongside engineering design, I develop tools that
                automate repetitive calculations and make engineering
                workflows easier to understand.
              </p>
            </div>

            <div className="grid grid-cols-2 gap-3">
              {[
                "Bridge Design",
                "RCC Structures",
                "PSC Structures",
                "Steel Structures",
                "FEM Analysis",
                "Design Automation",
              ].map((item) => (
                <div
                  key={item}
                  className="rounded-xl border border-white/10 bg-white/[0.02] p-5 text-sm text-gray-400 transition hover:border-emerald-400/30 hover:text-white"
                >
                  {item}
                </div>
              ))}
            </div>
          </div>
        </section>

        {/* STACK */}
        <section id="stack" className="border-t border-white/10 py-28">
          <SectionTitle
            eyebrow="02 / STACK"
            title="Engineering meets technology."
          />

          <div className="flex flex-wrap gap-3">
            {skills.map((skill) => (
              <span
                key={skill}
                className="rounded-lg border border-white/10 bg-white/[0.025] px-4 py-3 font-mono text-sm text-gray-400 transition hover:border-emerald-400/30 hover:bg-emerald-400/5 hover:text-emerald-300"
              >
                {skill}
              </span>
            ))}
          </div>
        </section>

        {/* PROJECTS */}
        <section id="projects" className="border-t border-white/10 py-28">
          <SectionTitle
            eyebrow="03 / PROJECTS"
            title="Things I build."
          />

          <div className="grid gap-5 md:grid-cols-2">
            {projects.map((project) => {
              const Icon = project.icon;

              return (
                <a
                  key={project.name}
                  href={project.github}
                  target="_blank"
                  rel="noreferrer"
                  className="group rounded-2xl border border-white/10 bg-white/[0.02] p-7 transition duration-300 hover:-translate-y-1 hover:border-emerald-400/30 hover:bg-white/[0.04]"
                >
                  <div className="flex items-start justify-between">
                    <div className="flex h-11 w-11 items-center justify-center rounded-xl border border-white/10 bg-white/5 text-emerald-400">
                      <Icon size={21} />
                    </div>

                    <ExternalLink
                      size={18}
                      className="text-gray-600 transition group-hover:text-emerald-400"
                    />
                  </div>

                  <h3 className="mt-7 text-xl font-semibold">
                    {project.name}
                  </h3>

                  <p className="mt-3 min-h-[52px] text-sm leading-6 text-gray-500">
                    {project.description}
                  </p>

                  <div className="mt-6 flex flex-wrap gap-2">
                    {project.tags.map((tag) => (
                      <span
                        key={tag}
                        className="rounded-md bg-white/5 px-2.5 py-1 text-xs text-gray-500"
                      >
                        {tag}
                      </span>
                    ))}
                  </div>

                  <div className="mt-7 flex items-center gap-5 border-t border-white/5 pt-5 text-xs text-gray-500">
                    <span className="flex items-center gap-1.5">
                      <Code2 size={14} />
                      {project.language}
                    </span>

                    <span className="flex items-center gap-1.5">
                      <Star size={14} />
                      {project.stars}
                    </span>

                    <span className="ml-auto flex items-center gap-1.5">
                      <GitFork size={14} />
                      View repository
                    </span>
                  </div>
                </a>
              );
            })}
          </div>
        </section>

        {/* GITHUB */}
        <section className="border-t border-white/10 py-28">
          <SectionTitle
            eyebrow="04 / GITHUB"
            title="Open source engineering."
          />

          <div className="overflow-hidden rounded-2xl border border-white/10 bg-white/[0.02] p-6">
            <div className="mb-6 flex items-center justify-between">
              <div>
                <p className="font-mono text-sm text-gray-400">
                  github.com/6thsuspect
                </p>

                <p className="mt-1 text-xs text-gray-600">
                  Engineering • Software • Automation
                </p>
              </div>

              <Github className="text-gray-500" />
            </div>

            <div className="grid grid-cols-7 gap-1">
              {Array.from({ length: 175 }).map((_, index) => (
                <div
                  key={index}
                  className={`aspect-square rounded-[2px] ${
                    index % 17 === 0
                      ? "bg-emerald-400/80"
                      : index % 11 === 0
                      ? "bg-emerald-400/40"
                      : index % 7 === 0
                      ? "bg-emerald-400/20"
                      : "bg-white/5"
                  }`}
                />
              ))}
            </div>

            <div className="mt-5 flex justify-between font-mono text-[10px] text-gray-600">
              <span>LESS</span>
              <span>MORE</span>
            </div>
          </div>
        </section>

        {/* CONTACT */}
        <section id="contact" className="border-t border-white/10 py-28">
          <div className="rounded-3xl border border-emerald-400/20 bg-emerald-400/[0.03] p-10 text-center md:p-16">
            <p className="font-mono text-xs text-emerald-400">
              LET'S CONNECT
            </p>

            <h2 className="mt-5 text-4xl font-bold md:text-6xl">
              Have an engineering
              <br />
              problem worth solving?
            </h2>

            <p className="mx-auto mt-6 max-w-xl text-gray-500">
              I'm interested in structural engineering software, automation,
              analysis tools and practical engineering problems.
            </p>

            <div className="mt-9 flex flex-wrap justify-center gap-3">
              <a
                href="mailto:arvindrawat400@gmail.com"
                className="flex items-center gap-2 rounded-xl bg-white px-5 py-3 font-semibold text-black"
              >
                <Mail size={17} />
                Email
              </a>

              <a
                href="https://www.linkedin.com/in/arvindrawat400/"
                target="_blank"
                rel="noreferrer"
                className="flex items-center gap-2 rounded-xl border border-white/10 px-5 py-3 font-semibold hover:bg-white/5"
              >
                <Linkedin size={17} />
                LinkedIn
              </a>

              <a
                href="https://github.com/6thsuspect"
                target="_blank"
                rel="noreferrer"
                className="flex items-center gap-2 rounded-xl border border-white/10 px-5 py-3 font-semibold hover:bg-white/5"
              >
                <Github size={17} />
                GitHub
              </a>
            </div>
          </div>
        </section>

        {/* FOOTER */}
        <footer className="flex flex-col justify-between gap-4 border-t border-white/10 py-8 text-xs text-gray-600 sm:flex-row">
          <span>© 2026 Arvind Singh Rawat</span>

          <span className="font-mono">
            ENGINEERED WITH CODE
          </span>
        </footer>
      </div>
    </div>
  );
}

function SectionTitle({
  eyebrow,
  title,
}: {
  eyebrow: string;
  title: string;
}) {
  return (
    <div className="mb-12">
      <p className="font-mono text-xs text-emerald-400">{eyebrow}</p>

      <h2 className="mt-3 text-3xl font-bold tracking-tight md:text-5xl">
        {title}
      </h2>
    </div>
  );
}

function Stat({
  value,
  label,
}: {
  value: string;
  label: string;
}) {
  return (
    <div className="border-r border-white/10 p-6 last:border-r-0">
      <div className="text-3xl font-bold text-white">{value}</div>
      <div className="mt-2 text-xs text-gray-600">{label}</div>
    </div>
  );
}

export default App;
