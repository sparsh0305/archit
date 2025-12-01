import React, { useState, useEffect, useRef } from 'react';
import { 
  Menu, X, ExternalLink, Mail, Linkedin, Github, 
  Instagram, ChevronRight, Download, MapPin, 
  Award, Briefcase, GraduationCap, ArrowUpRight 
} from 'lucide-react';

/* --- PORTFOLIO CONFIGURATION & DATA ---
  Content extracted from Archit Sinha_CV.pdf
*/

const DATA = {
  name: "Archit Sinha",
  title: "Digital Business & Media Strategist",
  tagline: "BBA & B.Sc. Mathematics Student • Market Researcher • Media Consultant",
  location: "New Delhi / Bangalore, India",
  email: "archit.sinha24@iimb.ac.in",
  socials: {
    linkedin: "#", // Placeholder
    instagram: "#", // Placeholder
    github: "#"     // Placeholder
  },
  about: [
    "I am a dual-degree student pursuing a B.Sc. (Hons) in Mathematics from Ramjas College (DU) and a BBA in Digital Business & Entrepreneurship from IIM Bangalore. My academic journey bridges the gap between quantitative analysis and strategic business management.",
    "With experience ranging from political consulting to media strategy, I specialize in building brand identities and optimizing operations. I have mentored over 500 students and led media teams to achieve significant organic growth.",
    "I thrive in dynamic environments where I can apply data-driven insights to solve real-world problems, whether it's launching a zero-investment venture or consulting for digital brands."
  ],
  experience: [
    {
      role: "Intern",
      company: "Policy Politics Governance Foundation",
      period: "Oct 2025 – Present",
      description: "Introductory Course on Political Consulting Program. Gaining insights into political strategy and governance frameworks."
    },
    {
      role: "Media Consultant",
      company: "Zedital Media",
      period: "July 2025 – Aug 2025",
      description: "Advised brands on marketing strategy, connecting with 400+ prospective clients. Generated ₹10k-15k in potential business through targeted outreach."
    },
    {
      role: "Director of Media & PR",
      company: "EntreConnect",
      period: "Nov 2024 – May 2025",
      description: "Led the media team to build brand identity, achieving 50,000+ organic Instagram views. Contributed to successful incubation at NSRCEL, IIM Bangalore."
    },
    {
      role: "Academic Mentor",
      company: "CampusCompass",
      period: "Nov 2024 – Present",
      description: "Mentoring a community of 500 students on exam strategy and study planning."
    }
  ],
  education: [
    {
      degree: "BBA (Digital Business & Entrepreneurship)",
      institution: "Indian Institute of Management Bangalore",
      year: "2027 (Pursuing)",
      score: "Active"
    },
    {
      degree: "B.Sc. (Hons) Mathematics",
      institution: "Ramjas College, University of Delhi",
      year: "2027 (Pursuing)",
      score: "Active"
    },
    {
      degree: "Class XII (CBSE)",
      institution: "Sapphire International School, Noida",
      year: "2024",
      score: "85%"
    },
    {
      degree: "Class X (CBSE)",
      institution: "Sapphire International School, Noida",
      year: "2022",
      score: "97% (School Rank 2)"
    }
  ],
  projects: [
    {
      title: "BluOrng Social Strategy",
      category: "Marketing",
      description: "Built a 360° social media strategy covering audience research, content calendar, and KPIs to strengthen brand presence.",
      tech: ["Strategy", "Analytics", "Content"]
    },
    {
      title: "HR & Operations Optimization",
      category: "Operations",
      description: "Led a ₹26,000 project under B-Think. Shortlisted 16 candidates from 200+ applicants and streamlined workflows.",
      tech: ["Management", "HR", "Process Design"]
    },
    {
      title: "Zero-Investment Tuition Venture",
      category: "Entrepreneurship",
      description: "Conducted a 4-hour tuition service, teaching 6 students and generating revenue at 100% profit margin.",
      tech: ["Teaching", "Sales", "Bootstrapping"]
    },
    {
      title: "Mobile Tea Business",
      category: "Entrepreneurship",
      description: "Launched a mobile tea stall with ₹250 capital. Sold 25 cups in 30 mins with 20% ROI to understand pricing mechanics.",
      tech: ["Sales", "Costing", "Customer Exp"]
    }
  ],
  skills: {
    core: ["Strategic Planning", "Public Relations", "Digital Marketing", "Leadership", "Event Management"],
    tools: ["SQL", "MS Excel", "MS PowerPoint", "IoT (Tryst-IIT Delhi Certified)"],
    languages: ["English (Bilingual)", "Hindi (Bilingual)"]
  }
};

/* --- REUSABLE ANIMATION COMPONENT ---
  Uses IntersectionObserver to trigger fade-in/slide-up animations
*/
const RevealOnScroll = ({ children, className = "", delay = 0 }) => {
  const [isVisible, setIsVisible] = useState(false);
  const ref = useRef(null);

  useEffect(() => {
    const observer = new IntersectionObserver(
      ([entry]) => {
        if (entry.isIntersecting) {
          setIsVisible(true);
          observer.unobserve(entry.target);
        }
      },
      { threshold: 0.1, rootMargin: "0px 0px -50px 0px" }
    );
    if (ref.current) observer.observe(ref.current);
    return () => {
      if (ref.current) observer.unobserve(ref.current);
    };
  }, []);

  const transitionDelay = `${delay * 100}ms`;

  return (
    <div
      ref={ref}
      style={{ transitionDelay }}
      className={`transition-all duration-700 ease-[cubic-bezier(0.2,0.9,0.3,1)] transform ${
        isVisible ? "opacity-100 translate-y-0" : "opacity-0 translate-y-8"
      } ${className}`}
    >
      {children}
    </div>
  );
};

/* --- MAIN APP COMPONENT --- 
*/
const App = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [activeSection, setActiveSection] = useState('hero');
  const [isScrolled, setIsScrolled] = useState(false);

  // Handle Scroll Spy & Navbar Styling
  useEffect(() => {
    const handleScroll = () => {
      setIsScrolled(window.scrollY > 50);
      
      const sections = ['hero', 'about', 'skills', 'experience', 'projects', 'contact'];
      const current = sections.find(section => {
        const element = document.getElementById(section);
        if (element) {
          const rect = element.getBoundingClientRect();
          return rect.top >= 0 && rect.top <= 300;
        }
        return false;
      });
      if (current) setActiveSection(current);
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  const scrollToSection = (id) => {
    setIsMenuOpen(false);
    const element = document.getElementById(id);
    if (element) {
      window.scrollTo({
        top: element.offsetTop - 80,
        behavior: 'smooth'
      });
    }
  };

  return (
    <div className="min-h-screen bg-white text-[#0F1724] font-sans selection:bg-[#FF6A00] selection:text-white overflow-x-hidden">
      
      {/* Inject Fonts */}
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Poppins:wght@600;700;800&display=swap');
        .font-display { font-family: 'Poppins', sans-serif; }
        .font-body { font-family: 'Inter', sans-serif; }
      `}</style>

      {/* --- NAVIGATION --- */}
      <nav 
        className={`fixed top-0 w-full z-50 transition-all duration-300 ${
          isScrolled ? "bg-white/90 backdrop-blur-md shadow-sm py-4" : "bg-transparent py-6"
        }`}
      >
        <div className="max-w-7xl mx-auto px-6 flex justify-between items-center">
          <a href="#" onClick={() => scrollToSection('hero')} className="font-display font-bold text-xl tracking-tight z-50 relative group">
            Archit<span className="text-[#FF6A00]">.</span>
          </a>

          {/* Desktop Menu */}
          <div className="hidden md:flex items-center gap-8">
            {['About', 'Skills', 'Experience', 'Projects', 'Contact'].map((item) => (
              <button
                key={item}
                onClick={() => scrollToSection(item.toLowerCase())}
                className="text-sm font-medium text-gray-600 hover:text-[#FF6A00] transition-colors relative group"
              >
                {item}
                <span className="absolute -bottom-1 left-0 w-0 h-0.5 bg-[#FF6A00] transition-all group-hover:w-full"></span>
              </button>
            ))}
            <button className="px-5 py-2.5 bg-[#FF6A00] text-white text-sm font-semibold rounded-full hover:bg-[#FF8A33] transition-all hover:scale-105 hover:shadow-[0_0_20px_rgba(255,106,0,0.3)]">
              Download CV
            </button>
          </div>

          {/* Mobile Hamburger */}
          <button 
            onClick={() => setIsMenuOpen(!isMenuOpen)}
            className="md:hidden z-50 relative p-2 text-gray-800 focus:outline-none"
            aria-label="Toggle menu"
          >
            {isMenuOpen ? <X size={28} /> : <Menu size={28} />}
          </button>
        </div>
      </nav>

      {/* --- MOBILE DRAWER --- */}
      <div 
        className={`fixed inset-0 bg-white z-40 flex flex-col items-center justify-center gap-8 transition-transform duration-500 ease-[cubic-bezier(0.2,0.9,0.3,1)] md:hidden ${
          isMenuOpen ? "translate-x-0" : "translate-x-full"
        }`}
      >
        {['About', 'Skills', 'Experience', 'Projects', 'Contact'].map((item) => (
          <button
            key={item}
            onClick={() => scrollToSection(item.toLowerCase())}
            className="font-display text-3xl font-bold text-[#0F1724] hover:text-[#FF6A00] transition-colors"
          >
            {item}
          </button>
        ))}
        <button className="mt-8 px-8 py-3 bg-[#FF6A00] text-white font-semibold rounded-full text-lg">
          Download CV
        </button>
      </div>

      {/* --- HERO SECTION --- */}
      <section id="hero" className="min-h-screen flex items-center pt-20 relative overflow-hidden">
        {/* Abstract Background Decoration */}
        <div className="absolute top-0 right-0 w-[50vw] h-[50vw] bg-orange-50 rounded-full blur-3xl opacity-50 -translate-y-1/2 translate-x-1/4 pointer-events-none"></div>
        
        <div className="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center w-full">
          <div className="order-2 md:order-1">
            <RevealOnScroll delay={0}>
              <h2 className="text-[#FF6A00] font-semibold tracking-wide uppercase text-sm mb-4">
                👋 Welcome to my portfolio
              </h2>
            </RevealOnScroll>
            
            <RevealOnScroll delay={1}>
              <h1 className="font-display text-5xl md:text-7xl font-bold leading-[1.1] mb-6 text-[#0F1724]">
                Hi, I'm <br/>
                <span className="text-transparent bg-clip-text bg-gradient-to-r from-[#FF6A00] to-[#FF8A33]">
                  {DATA.name}
                </span>
              </h1>
            </RevealOnScroll>
            
            <RevealOnScroll delay={2}>
              <p className="text-xl md:text-2xl text-gray-500 font-body mb-8 max-w-lg leading-relaxed">
                {DATA.tagline}
              </p>
            </RevealOnScroll>
            
            <RevealOnScroll delay={3}>
              <div className="flex flex-wrap gap-4">
                <button 
                  onClick={() => scrollToSection('contact')}
                  className="px-8 py-3.5 bg-[#0F1724] text-white font-semibold rounded-full hover:bg-gray-800 transition-all hover:scale-105 flex items-center gap-2"
                >
                  Let's Talk <Mail size={18} />
                </button>
                <button 
                  className="px-8 py-3.5 bg-white border-2 border-gray-200 text-[#0F1724] font-semibold rounded-full hover:border-[#FF6A00] hover:text-[#FF6A00] transition-all flex items-center gap-2"
                >
                  Download CV <Download size={18} />
                </button>
              </div>
            </RevealOnScroll>

            <RevealOnScroll delay={4}>
              <div className="mt-12 flex items-center gap-4 text-gray-500 text-sm">
                <div className="flex -space-x-3">
                  {[1,2,3].map(i => (
                    <div key={i} className="w-10 h-10 rounded-full bg-gray-200 border-2 border-white flex items-center justify-center text-xs font-bold text-gray-400">
                      IIM
                    </div>
                  ))}
                </div>
                <p>Mentored 500+ Students & <br/> Advised 40+ Clients</p>
              </div>
            </RevealOnScroll>
          </div>

          <div className="order-1 md:order-2 relative flex justify-center">
            <RevealOnScroll delay={2}>
              <div className="relative w-72 h-72 md:w-[28rem] md:h-[28rem]">
                {/* Decorative Elements */}
                <div className="absolute inset-0 border-2 border-[#FF6A00]/20 rounded-full animate-[spin_10s_linear_infinite]"></div>
                <div className="absolute inset-4 border border-[#FF6A00]/40 rounded-full"></div>
                
                {/* Image Placeholder */}
                <div className="absolute inset-8 rounded-full overflow-hidden bg-gray-100 shadow-2xl group">
                   <div className="w-full h-full bg-gradient-to-tr from-gray-200 to-gray-50 flex items-center justify-center text-gray-400">
                      <span className="font-display text-4xl font-bold opacity-20">AS</span>
                      {/* Replace src below with actual image */}
                      <img 
                        src="/api/placeholder/400/400" 
                        alt="Archit Sinha" 
                        className="w-full h-full object-cover opacity-90 group-hover:scale-110 transition-transform duration-700 mix-blend-multiply"
                      />
                   </div>
                </div>

                {/* Floating Badge */}
                <div className="absolute bottom-10 -left-4 bg-white p-4 rounded-2xl shadow-xl flex items-center gap-3 animate-bounce" style={{ animationDuration: '3s' }}>
                   <div className="p-2 bg-orange-100 rounded-lg text-[#FF6A00]">
                     <Award size={24} />
                   </div>
                   <div>
                     <p className="text-xs text-gray-400 font-bold uppercase">Rank 1</p>
                     <p className="text-sm font-bold text-gray-800">Olympiad Winner</p>
                   </div>
                </div>
              </div>
            </RevealOnScroll>
          </div>
        </div>
      </section>

      {/* --- ABOUT SECTION --- */}
      <section id="about" className="py-24 bg-gray-50/50">
        <div className="max-w-7xl mx-auto px-6">
          <RevealOnScroll>
            <div className="max-w-3xl mx-auto text-center mb-16">
              <h2 className="font-display text-3xl md:text-4xl font-bold mb-6">About Me</h2>
              <div className="w-20 h-1.5 bg-[#FF6A00] mx-auto rounded-full mb-8"></div>
              <div className="space-y-4 text-gray-600 leading-relaxed text-lg text-left md:text-center">
                {DATA.about.map((paragraph, idx) => (
                  <p key={idx}>{paragraph}</p>
                ))}
              </div>
            </div>
          </RevealOnScroll>

          {/* Education Cards */}
          <div className="grid md:grid-cols-2 gap-6 mt-12">
             {DATA.education.slice(0, 2).map((edu, idx) => (
               <RevealOnScroll key={idx} delay={idx + 1}>
                 <div className="bg-white p-8 rounded-3xl shadow-sm border border-gray-100 hover:border-[#FF6A00]/30 transition-all hover:shadow-lg group">
                   <div className="flex items-start justify-between mb-4">
                     <div className="p-3 bg-orange-50 rounded-xl text-[#FF6A00] group-hover:bg-[#FF6A00] group-hover:text-white transition-colors">
                       <GraduationCap size={28} />
                     </div>
                     <span className="text-xs font-bold tracking-wider text-gray-400 bg-gray-50 px-3 py-1 rounded-full uppercase">
                       {edu.year}
                     </span>
                   </div>
                   <h3 className="text-xl font-bold text-[#0F1724] mb-2">{edu.degree}</h3>
                   <p className="text-gray-500">{edu.institution}</p>
                 </div>
               </RevealOnScroll>
             ))}
          </div>
        </div>
      </section>

      {/* --- SKILLS SECTION --- */}
      <section id="skills" className="py-24">
        <div className="max-w-7xl mx-auto px-6">
          <RevealOnScroll>
            <div className="flex flex-col md:flex-row md:items-end justify-between mb-12">
              <div>
                <h2 className="font-display text-3xl md:text-4xl font-bold mb-2">Technical Proficiency</h2>
                <p className="text-gray-500">Tools and technologies I use to drive results.</p>
              </div>
              <div className="hidden md:block w-1/3 h-[1px] bg-gray-200 mb-2"></div>
            </div>
          </RevealOnScroll>

          <div className="grid md:grid-cols-3 gap-12">
            {Object.entries(DATA.skills).map(([category, items], idx) => (
              <RevealOnScroll key={category} delay={idx}>
                <div className="space-y-6">
                  <h3 className="text-xl font-bold capitalize flex items-center gap-2">
                    <span className="w-2 h-2 rounded-full bg-[#FF6A00]"></span>
                    {category}
                  </h3>
                  <div className="flex flex-wrap gap-3">
                    {items.map(skill => (
                      <div key={skill} className="px-4 py-2 bg-gray-50 border border-gray-100 rounded-lg text-sm font-medium text-gray-600 hover:border-[#FF6A00] hover:text-[#FF6A00] transition-colors cursor-default">
                        {skill}
                      </div>
                    ))}
                  </div>
                </div>
              </RevealOnScroll>
            ))}
          </div>
        </div>
      </section>

      {/* --- EXPERIENCE SECTION --- */}
      <section id="experience" className="py-24 bg-[#0F1724] text-white relative overflow-hidden">
        {/* Decorative blobs */}
        <div className="absolute top-0 left-0 w-96 h-96 bg-[#FF6A00] opacity-5 blur-[100px] rounded-full pointer-events-none"></div>
        
        <div className="max-w-5xl mx-auto px-6 relative z-10">
          <RevealOnScroll>
            <h2 className="font-display text-3xl md:text-4xl font-bold mb-16 text-center">Professional Journey</h2>
          </RevealOnScroll>

          <div className="space-y-12">
            {DATA.experience.map((job, idx) => (
              <RevealOnScroll key={idx} delay={idx}>
                <div className="relative pl-8 md:pl-0">
                  {/* Timeline Line (Desktop) */}
                  <div className="hidden md:block absolute left-[50%] top-0 bottom-0 w-px bg-gray-800 -translate-x-1/2"></div>
                  
                  {/* Timeline Dot (Desktop) */}
                  <div className="hidden md:block absolute left-[50%] top-0 w-4 h-4 rounded-full bg-[#FF6A00] -translate-x-1/2 shadow-[0_0_10px_#FF6A00]"></div>

                  {/* Mobile Line */}
                  <div className="md:hidden absolute left-0 top-2 bottom-0 w-px bg-gray-800"></div>
                  <div className="md:hidden absolute left-[-5px] top-2 w-3 h-3 rounded-full bg-[#FF6A00]"></div>

                  <div className={`md:flex items-start justify-between gap-12 ${idx % 2 === 0 ? 'flex-row-reverse' : ''}`}>
                    <div className="md:w-1/2 mb-2 md:mb-0 md:text-right">
                       <span className={`inline-block px-3 py-1 rounded-full text-xs font-bold tracking-wide bg-gray-800 text-gray-300 mb-2 ${idx % 2 === 0 ? 'md:mr-auto' : 'md:ml-auto'}`}>
                         {job.period}
                       </span>
                    </div>
                    
                    <div className="md:w-1/2">
                      <h3 className="text-xl font-bold text-white mb-1">{job.role}</h3>
                      <h4 className="text-[#FF6A00] font-medium mb-3">{job.company}</h4>
                      <p className="text-gray-400 text-sm leading-relaxed">{job.description}</p>
                    </div>
                  </div>
                </div>
              </RevealOnScroll>
            ))}
          </div>
        </div>
      </section>

      {/* --- PROJECTS SECTION --- */}
      <section id="projects" className="py-24 bg-gray-50">
        <div className="max-w-7xl mx-auto px-6">
          <RevealOnScroll>
            <div className="text-center mb-16">
              <h2 className="font-display text-3xl md:text-4xl font-bold mb-4">Selected Projects</h2>
              <p className="text-gray-500 max-w-2xl mx-auto">
                A showcase of entrepreneurial ventures, strategic consulting, and operational leadership.
              </p>
            </div>
          </RevealOnScroll>

          <div className="grid md:grid-cols-2 gap-8">
            {DATA.projects.map((project, idx) => (
              <RevealOnScroll key={idx} delay={idx}>
                <div className="group bg-white rounded-3xl overflow-hidden hover:shadow-xl transition-all duration-300 border border-gray-100 flex flex-col h-full">
                  <div className="p-8 flex flex-col flex-grow">
                    <div className="flex justify-between items-start mb-4">
                      <span className="text-xs font-bold text-[#FF6A00] uppercase tracking-wider">{project.category}</span>
                      <ArrowUpRight className="text-gray-300 group-hover:text-[#FF6A00] group-hover:translate-x-1 group-hover:-translate-y-1 transition-all" size={20} />
                    </div>
                    <h3 className="text-2xl font-bold mb-3 text-[#0F1724] group-hover:text-[#FF6A00] transition-colors">
                      {project.title}
                    </h3>
                    <p className="text-gray-600 mb-6 flex-grow">{project.description}</p>
                    
                    <div className="flex flex-wrap gap-2 pt-4 border-t border-gray-50">
                      {project.tech.map(tag => (
                        <span key={tag} className="px-3 py-1 bg-gray-50 text-xs font-medium text-gray-500 rounded-md">
                          #{tag}
                        </span>
                      ))}
                    </div>
                  </div>
                  {/* Decorative colored bottom bar */}
                  <div className="h-1.5 w-full bg-gradient-to-r from-gray-100 via-gray-100 to-[#FF6A00] bg-[length:200%_100%] bg-right-bottom group-hover:bg-left-bottom transition-all duration-500"></div>
                </div>
              </RevealOnScroll>
            ))}
          </div>
        </div>
      </section>

      {/* --- CONTACT SECTION --- */}
      <section id="contact" className="py-24 bg-white relative">
        <div className="max-w-4xl mx-auto px-6 relative z-10">
          <RevealOnScroll>
            <div className="bg-[#0F1724] rounded-[2.5rem] p-8 md:p-16 text-center text-white overflow-hidden relative">
              {/* Background accents */}
              <div className="absolute top-0 right-0 w-64 h-64 bg-[#FF6A00] opacity-10 rounded-full blur-3xl -translate-y-1/2 translate-x-1/2"></div>
              <div className="absolute bottom-0 left-0 w-48 h-48 bg-[#FF8A33] opacity-10 rounded-full blur-3xl translate-y-1/2 -translate-x-1/2"></div>

              <h2 className="font-display text-3xl md:text-5xl font-bold mb-6">Let's work together.</h2>
              <p className="text-gray-400 mb-10 text-lg max-w-xl mx-auto">
                Open for consulting, media strategy roles, and business collaborations.
              </p>
              
              <div className="flex flex-col md:flex-row items-center justify-center gap-6">
                 <a 
                   href={`mailto:${DATA.email}`} 
                   className="w-full md:w-auto px-8 py-4 bg-[#FF6A00] text-white font-bold rounded-full hover:bg-[#FF8A33] transition-all hover:scale-105 shadow-lg shadow-orange-500/20 flex items-center justify-center gap-2"
                 >
                   <Mail size={20} /> Say Hello
                 </a>
                 <button 
                   onClick={() => navigator.clipboard.writeText(DATA.email)}
                   className="w-full md:w-auto px-8 py-4 bg-white/10 backdrop-blur-sm text-white font-bold rounded-full hover:bg-white/20 transition-all border border-white/10"
                 >
                   Copy Email
                 </button>
              </div>

              <div className="mt-16 pt-8 border-t border-gray-800 flex justify-center gap-8">
                 <a href={DATA.socials.linkedin} className="text-gray-400 hover:text-white hover:scale-110 transition-all"><Linkedin size={24} /></a>
                 <a href={DATA.socials.github} className="text-gray-400 hover:text-white hover:scale-110 transition-all"><Github size={24} /></a>
                 <a href={DATA.socials.instagram} className="text-gray-400 hover:text-white hover:scale-110 transition-all"><Instagram size={24} /></a>
              </div>
            </div>
          </RevealOnScroll>
        </div>
      </section>

      {/* --- FOOTER --- */}
      <footer className="py-8 bg-white border-t border-gray-100">
        <div className="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center text-sm text-gray-500">
          <p>© 2025 Archit Sinha. All rights reserved.</p>
          <div className="flex items-center gap-6 mt-4 md:mt-0">
             <span>New Delhi, India</span>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default App;
