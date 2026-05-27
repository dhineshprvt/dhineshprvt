export default function GitHubProfilePreview() {
  return (
    <div className="min-h-screen bg-[#0D1117] text-white font-sans">
      {/* Hero Section */}
      <div className="relative overflow-hidden bg-gradient-to-r from-[#0f2027] via-[#203a43] to-[#2c5364] py-20 text-center">
        <h1 className="text-6xl font-extrabold tracking-wide">Dhineshkumar</h1>
        <p className="mt-4 text-xl text-emerald-300 font-semibold">
          Full Stack Developer | Java Backend Engineer | Tech Explorer
        </p>

        <div className="mt-8 flex flex-wrap justify-center gap-4">
          <span className="rounded-full bg-black/30 px-5 py-2 text-sm border border-emerald-400">
            🚀 Full Stack Developer
          </span>
          <span className="rounded-full bg-black/30 px-5 py-2 text-sm border border-emerald-400">
            ☕ Java & Spring Boot Developer
          </span>
          <span className="rounded-full bg-black/30 px-5 py-2 text-sm border border-emerald-400">
            ⚡ Building Scalable Systems
          </span>
        </div>
      </div>

      {/* About Me */}
      <section className="max-w-6xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h2 className="text-4xl font-bold text-emerald-400 mb-6">💫 About Me</h2>

          <div className="bg-[#161B22] rounded-3xl p-6 shadow-xl border border-gray-800">
            <pre className="text-sm leading-7 whitespace-pre-wrap text-gray-300">
{`Name: Dhineshkumar
Education: Electronics & Communication Engineering
College: Karpagam Institute of Technology (KIT)

Interests:
- Backend Development
- Cloud Computing
- DevOps
- System Design
- Open Source

Currently Learning:
- Spring Boot
- Microservices
- PostgreSQL
- AWS
- Docker & Kubernetes

2026 Goals:
- Build scalable real-world projects
- Master backend architecture
- Contribute to open source
- Become industry-ready`}
            </pre>
          </div>
        </div>

        <div className="flex justify-center">
          <img
            className="rounded-3xl shadow-2xl w-full max-w-md"
            src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif"
            alt="Developer GIF"
          />
        </div>
      </section>

      {/* Connect */}
      <section className="bg-[#161B22] py-16">
        <div className="max-w-5xl mx-auto text-center px-6">
          <h2 className="text-4xl font-bold text-emerald-400 mb-10">
            🌐 Connect With Me
          </h2>

          <div className="flex flex-wrap justify-center gap-5">
            {[
              {
                name: 'Gmail',
                link: 'mailto:dhinesh1434k@gmail.com',
              },
              {
                name: 'LinkedIn',
                link: 'https://www.linkedin.com/in/dhineshkumar-v/',
              },
              {
                name: 'Instagram',
                link: 'https://instagram.com/dhinesh._.prvt',
              },
              {
                name: 'GitHub',
                link: 'https://github.com/dhineshprvt',
              },
            ].map((item) => (
              <a
                key={item.name}
                href={item.link}
                target="_blank"
                className="px-6 py-3 rounded-2xl bg-black border border-emerald-400 hover:scale-105 transition-all duration-300 shadow-lg"
              >
                {item.name}
              </a>
            ))}
          </div>
        </div>
      </section>

      {/* Tech Stack */}
      <section className="max-w-6xl mx-auto px-6 py-16">
        <h2 className="text-4xl font-bold text-center text-emerald-400 mb-12">
          ⚒️ Tech Stack
        </h2>

        <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
          {[
            {
              title: '🚀 Languages',
              items: 'Java, JavaScript, Go, HTML, CSS',
            },
            {
              title: '⚡ Backend & Database',
              items: 'Spring Boot, Node.js, PostgreSQL, MySQL',
            },
            {
              title: '☁️ Cloud & DevOps',
              items: 'AWS, Docker, Kubernetes, Git, GitHub',
            },
            {
              title: '🛠️ Tools & IDEs',
              items: 'VS Code, IntelliJ, Maven, Postman, Linux',
            },
          ].map((card) => (
            <div
              key={card.title}
              className="bg-[#161B22] border border-gray-800 rounded-3xl p-6 shadow-xl hover:border-emerald-400 transition-all duration-300"
            >
              <h3 className="text-xl font-semibold mb-4 text-emerald-300">
                {card.title}
              </h3>
              <p className="text-gray-300 leading-7">{card.items}</p>
            </div>
          ))}
        </div>
      </section>

      {/* Stats */}
      <section className="bg-[#161B22] py-16 px-6">
        <div className="max-w-6xl mx-auto text-center">
          <h2 className="text-4xl font-bold text-emerald-400 mb-12">
            📊 GitHub Analytics
          </h2>

          <div className="grid md:grid-cols-2 gap-8">
            <img
              className="rounded-3xl shadow-2xl"
              src="https://github-readme-stats.vercel.app/api?username=dhineshprvt&show_icons=true&theme=tokyonight&hide_border=true&border_radius=15&bg_color=0D1117"
              alt="GitHub Stats"
            />

            <img
              className="rounded-3xl shadow-2xl"
              src="https://streak-stats.demolab.com?user=dhineshprvt&theme=tokyonight&hide_border=true&border_radius=15"
              alt="GitHub Streak"
            />
          </div>
        </div>
      </section>

      {/* Developer Philosophy */}
      <section className="max-w-5xl mx-auto px-6 py-16">
        <h2 className="text-4xl font-bold text-center text-emerald-400 mb-10">
          💻 Developer Philosophy
        </h2>

        <div className="bg-black rounded-3xl p-8 border border-gray-800 overflow-x-auto shadow-2xl">
          <pre className="text-emerald-300 text-sm leading-7">
{`class Developer {

    public static void main(String[] args) {

        while (alive) {

            eat();
            sleep();
            code();
            debug();
            learn();
            repeat();

            if(success == false) {
                tryAgain();
            }
        }
    }
}`}
          </pre>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gradient-to-r from-[#0f2027] via-[#203a43] to-[#2c5364] py-14 text-center mt-10">
        <h2 className="text-3xl font-bold text-emerald-300">
          💚 Thanks for Visiting My Profile
        </h2>

        <p className="mt-5 text-lg text-gray-200">
          ⭐ Star Your Favorite Repositories • 🚀 Keep Learning Keep Building • 💻 Code. Create. Innovate.
        </p>

        <div className="mt-8 text-gray-300">
          ⭐ From Dhineshkumar
        </div>
      </footer>
    </div>
  );
}
