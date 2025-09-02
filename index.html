import React, { useState, useEffect } from 'react'
import { motion } from 'framer-motion'

// Vihan Shahini — Modern Portfolio component
// Usage: place this component in a React app configured with Tailwind CSS and Framer Motion.
// - For GitHub Pages: build with `npm run build` and deploy the `build` folder.
// - Tailwind: need tailwindcss configured (postcss) or use CDN during prototyping.
// - This is a single-file starter. Replace photos, links, and copy where needed.

const translations = {
  en: {
    name: 'Vihan Shahini',
    tagline: 'Aspiring AI Researcher & MIT Hopeful',
    heroLead: 'I build principled machine learning projects, translate technical material into Persian, and prepare for research-level challenges.',
    aboutTitle: 'About',
    aboutText: 'I am a 16-year-old machine learning enthusiast from Gorgan, Iran. My work focuses on applied ML for agriculture, educational translations of core mathematics, and preparing for the AI Olympiad and university research.',
    projectsTitle: 'Projects',
    project1: {
      title: 'Crop Yield Prediction',
      desc: 'Predicting crop yield and classifying soil quality using environmental and soil features (India dataset).',
    },
    project2: {
      title: 'Linear Regression: Zero to Hero',
      desc: 'Comprehensive guide and R demonstrations covering cost functions and optimization from first principles.',
    },
    project3: {
      title: 'Breakthrough Junior Challenge Video',
      desc: 'Explained the bias–variance tradeoff in an educational video submission.',
    },
    project4: {
      title: 'Gilbert Strang Translations',
      desc: 'Translated multiple linear algebra lectures into academic Persian.',
    },
    writingTitle: 'Writing & Code',
    achievementsTitle: 'Achievements',
    achievementsList: [
      'AI Olympiad competitor aiming for gold',
      'Trilingual: Persian, English, German (learning Azerbaijani Turkish & Russian)',
      'Published technical documents and educational translations',
    ],
    contactTitle: 'Contact',
    contactText: 'Email me for collaborations, mentorship, or research opportunities.',
    email: 'Vihanshahini@yahoo.com',
    github: 'https://github.com/ItzShahVihan',
    medium: 'https://medium.com/@shahvihan',
    linkedin: 'https://www.linkedin.com/posts/vihan-shahini-1a286b24d',
  },
  fa: {
    name: 'ویهان شاهینی',
    tagline: 'پژوهشگر هوش مصنوعی در آستانهٔ MIT',
    heroLead: 'من پروژه‌های ماشین لرنینگ کاربردی می‌سازم، مطالب فنی را به فارسی ترجمه می‌کنم و برای چالش‌های پژوهشی آماده می‌شوم.',
    aboutTitle: 'درباره من',
    aboutText: 'من یک علاقه‌مند ۱۶ ساله به یادگیری ماشین از گرگان، ایران هستم. کارم بر روش‌های کاربردی در کشاورزی، ترجمهٔ آموزشی ریاضیات پایه، و آماده‌سازی برای المپیاد هوش مصنوعی و پژوهش‌های دانشگاهی تمرکز دارد.',
    projectsTitle: 'پروژه‌ها',
    project1: {
      title: 'پیش‌بینی عملکرد محصول',
      desc: 'پیش‌بینی عملکرد محصول و طبقه‌بندی کیفیت خاک با استفاده از ویژگی‌های محیطی و خاک (مجموعه دادهٔ هند).',
    },
    project2: {
      title: 'رگرسیون خطی: از صفر تا قهرمان',
      desc: 'راهنمای کامل با مثال‌های R دربارهٔ توابع هزینه و بهینه‌سازی از اصول اولیه.',
    },
    project3: {
      title: 'ویدئوی Breakthrough Junior Challenge',
      desc: 'توضیح trade-off بایاس-واریانس در قالب یک ویدیوی آموزشی.',
    },
    project4: {
      title: 'ترجمه‌های Gilbert Strang',
      desc: 'ترجمهٔ چندین جلسهٔ جبر خطی به فارسی با لحن آکادمیک.',
    },
    writingTitle: 'نوشته‌ها و کد',
    achievementsTitle: 'دستاوردها',
    achievementsList: [
      'شرکت‌کنندهٔ المپیاد هوش مصنوعی با هدف مدال طلا',
      'سه‌زبانه: فارسی، انگلیسی، آلمانی (در حال یادگیری ترکی آذربایجانی و روسی)',
      'منتشرکنندهٔ اسناد فنی و ترجمه‌های آموزشی',
    ],
    contactTitle: 'تماس',
    contactText: 'برای همکاری، منتورینگ یا فرصت‌های پژوهشی با من ایمیل بزنید.',
    email: 'Vihanshahini@yahoo.com',
    github: 'https://github.com/ItzShahVihan',
    medium: 'https://medium.com/@shahvihan',
    linkedin: 'https://www.linkedin.com/posts/vihan-shahini-1a286b24d',
  },
  de: {
    name: 'Vihan Shahini',
    tagline: 'Aufstrebender KI-Forscher & MIT-Bewerber',
    heroLead: 'Ich entwickle angewandte ML-Projekte, übersetze technische Inhalte ins Persische und bereite mich auf Forschung und Wettbewerbe vor.',
    aboutTitle: 'Über mich',
    aboutText: 'Ich bin 16 Jahre alt, komme aus Gorgan, Iran, und interessiere mich leidenschaftlich für Machine Learning. Meine Arbeit konzentriert sich auf angewandte ML-Lösungen für die Landwirtschaft, pädagogische Übersetzungen und die Vorbereitung auf die AI-Olympiade sowie akademische Forschung.',
    projectsTitle: 'Projekte',
    project1: {
      title: 'Ertragsvorhersage für Feldfrüchte',
      desc: 'Vorhersage von Erträgen und Klassifikation der Bodenqualität mithilfe von Umwelt- und Bodenmerkmalen (Indisches Datenset).',
    },
    project2: {
      title: 'Lineare Regression: Zero to Hero',
      desc: 'Umfassender Leitfaden mit R-Beispielen zu Kostenfunktionen und Optimierung von Grund auf.',
    },
    project3: {
      title: 'Breakthrough Junior Challenge Video',
      desc: 'Erklärung des Bias–Varianz-Dilemmas in einem pädagogischen Video.',
    },
    project4: {
      title: 'Gilbert Strang Übersetzungen',
      desc: 'Übersetzung mehrerer Lineare Algebra-Vorlesungen ins Persische.',
    },
    writingTitle: 'Schriften & Code',
    achievementsTitle: 'Erfolge',
    achievementsList: [
      'Teilnehmer der AI-Olympiade mit Goldambitionen',
      'Dreisprachig: Persisch, Englisch, Deutsch (lernt Aserbaidschanisch und Russisch)',
      'Veröffentlichte technische Dokumente und Lehrübersetzungen',
    ],
    contactTitle: 'Kontakt',
    contactText: 'Schreiben Sie mir bei Interesse an Zusammenarbeit, Mentoring oder Forschungsprojekten.',
    email: 'Vihanshahini@yahoo.com',
    github: 'https://github.com/ItzShahVihan',
    medium: 'https://medium.com/@shahvihan',
    linkedin: 'https://www.linkedin.com/posts/vihan-shahini-1a286b24d',
  },
}

export default function Portfolio() {
  const [lang, setLang] = useState('en')
  const t = translations[lang]

  // Set dir for Persian (fa)
  useEffect(() => {
    document.documentElement.lang = lang === 'fa' ? 'fa' : 'en'
    document.documentElement.dir = lang === 'fa' ? 'rtl' : 'ltr'
  }, [lang])

  return (
    <div className="min-h-screen bg-gray-50 text-gray-900 antialiased">
      <header className="max-w-6xl mx-auto p-6 flex items-center justify-between">
        <div>
          <div className="text-sm text-gray-600">{t.name}</div>
          <div className="text-xs text-gray-500">{t.tagline}</div>
        </div>
        <div className="flex items-center gap-3">
          <nav className="hidden sm:flex gap-4 text-sm text-gray-600">
            <a href="#about">{t.aboutTitle}</a>
            <a href="#projects">{t.projectsTitle}</a>
            <a href="#writing">{t.writingTitle}</a>
            <a href="#contact">{t.contactTitle}</a>
          </nav>

          <div className="flex items-center gap-2">
            <button
              onClick={() => setLang('en')}
              className={`px-3 py-1 rounded-md text-sm ${lang === 'en' ? 'bg-gray-900 text-white' : 'bg-white border'}`}>
              EN
            </button>
            <button
              onClick={() => setLang('fa')}
              className={`px-3 py-1 rounded-md text-sm ${lang === 'fa' ? 'bg-gray-900 text-white' : 'bg-white border'}`}>
              فارسی
            </button>
            <button
              onClick={() => setLang('de')}
              className={`px-3 py-1 rounded-md text-sm ${lang === 'de' ? 'bg-gray-900 text-white' : 'bg-white border'}`}>
              DE
            </button>
          </div>
        </div>
      </header>

      <main className="max-w-6xl mx-auto px-6 pb-24">
        <section className="grid grid-cols-1 md:grid-cols-2 gap-8 items-start">
          <motion.div initial={{ opacity: 0, x: -20 }} animate={{ opacity: 1, x: 0 }} className="pt-8">
            <h1 className="text-4xl font-semibold leading-tight">{t.name}</h1>
            <p className="mt-4 text-gray-700 max-w-xl">{t.heroLead}</p>

            <div className="mt-6 flex flex-wrap gap-3">
              <a href={t.github} className="px-4 py-2 bg-gray-900 text-white rounded-md text-sm">GitHub</a>
              <a href={t.linkedin} className="px-4 py-2 border rounded-md text-sm">LinkedIn</a>
              <a href={t.medium} className="px-4 py-2 border rounded-md text-sm">Medium</a>
              <a href={`mailto:${t.email}`} className="px-4 py-2 border rounded-md text-sm">Email</a>
            </div>
          </motion.div>

          <motion.div initial={{ opacity: 0, x: 20 }} animate={{ opacity: 1, x: 0 }} className="flex items-center justify-center">
            <div className="w-56 h-56 rounded-2xl bg-gradient-to-br from-gray-200 to-gray-300 flex items-center justify-center shadow-lg">
              {/* Replace with real photo */}
              <div className="text-center text-gray-700">Photo<br/>Replace</div>
            </div>
          </motion.div>
        </section>

        <section id="about" className="mt-12">
          <motion.div initial={{ opacity: 0, y: 10 }} animate={{ opacity: 1, y: 0 }}>
            <h2 className="text-2xl font-semibold">{t.aboutTitle}</h2>
            <p className="mt-4 text-gray-700 max-w-3xl">{t.aboutText}</p>
          </motion.div>
        </section>

        <section id="projects" className="mt-12">
          <h3 className="text-xl font-semibold">{t.projectsTitle}</h3>
          <div className="mt-6 grid grid-cols-1 md:grid-cols-2 gap-6">
            {[t.project1, t.project2, t.project3, t.project4].map((p, i) => (
              <motion.article key={i} whileHover={{ y: -6 }} className="p-6 bg-white rounded-2xl shadow-md">
                <h4 className="font-medium">{p.title}</h4>
                <p className="mt-2 text-gray-600">{p.desc}</p>
                <div className="mt-4 flex gap-2 text-sm">
                  <a href={t.github} className="px-3 py-1 border rounded">Code</a>
                  <a href={t.medium} className="px-3 py-1 border rounded">Write-up</a>
                </div>
              </motion.article>
            ))}
          </div>
        </section>

        <section id="writing" className="mt-12">
          <h3 className="text-xl font-semibold">{t.writingTitle}</h3>
          <div className="mt-4 text-gray-700">
            <p>Find essays, technical write-ups, and notebooks on my GitHub and Medium profiles linked above.</p>
          </div>
        </section>

        <section id="achievements" className="mt-12">
          <h3 className="text-xl font-semibold">{t.achievementsTitle}</h3>
          <ul className="mt-4 list-disc ml-6 text-gray-700">
            {t.achievementsList.map((a, i) => (
              <li key={i}>{a}</li>
            ))}
          </ul>
        </section>

        <section id="contact" className="mt-12">
          <h3 className="text-xl font-semibold">{t.contactTitle}</h3>
          <p className="mt-4 text-gray-700 max-w-3xl">{t.contactText}</p>
          <div className="mt-4">
            <a className="inline-block px-4 py-2 bg-gray-900 text-white rounded-md" href={`mailto:${t.email}`}>{t.email}</a>
          </div>
        </section>

        <footer className="mt-16 py-12 text-sm text-gray-500">
          <div className="flex flex-col md:flex-row md:justify-between md:items-center gap-4">
            <div>© {new Date().getFullYear()} {t.name}. All rights reserved.</div>
            <div>Designed for academic clarity — MIT application friendly.</div>
          </div>
        </footer>
      </main>
    </div>
  )
}
