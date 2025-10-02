# About
import React from "react";

// AboutPage.jsx
// Single-file React component for a modern, high-tech About page.
// Uses Tailwind CSS utility classes for styling (no imports required here).

export default function AboutPage() {
  return (
    <main className="min-h-screen bg-gradient-to-b from-slate-900 via-slate-800 to-black text-slate-100 flex items-center justify-center p-6">
      <div className="max-w-4xl w-full bg-slate-900/60 backdrop-blur-md border border-slate-700 rounded-2xl shadow-2xl overflow-hidden">
        <div className="md:flex">
          {/* Left column - profile card */}
          <section className="md:w-1/3 p-8 flex flex-col items-center gap-6 bg-gradient-to-b from-slate-800/30 to-transparent">
            <div className="w-36 h-36 rounded-full ring-2 ring-sky-500/60 overflow-hidden flex items-center justify-center bg-gradient-to-tr from-slate-700 to-slate-600">
              {/* Placeholder avatar - replace with <img src="/path.jpg" alt="..." /> */}
              <svg xmlns="http://www.w3.org/2000/svg" className="w-20 h-20 opacity-80" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth="1.5" d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zM6 20v-1a4 4 0 014-4h4a4 4 0 014 4v1" />
              </svg>
            </div>

            <div className="text-center">
              <h1 className="text-2xl font-semibold">Christian Arturi</h1>
              <p className="text-sm text-slate-300 mt-1">Financial Associate — Experior Financial Group</p>
            </div>

            <div className="w-full">
              <p className="text-xs text-slate-400">Dedicated to helping families build strong financial foundations through insurance, wealth planning, and tailored advice.</p>
            </div>

            <div className="flex gap-3 mt-2">
              <a className="text-sm px-3 py-2 rounded-lg bg-sky-600/90 hover:bg-sky-500 transition" href="mailto:hello@yourdomain.com">Email</a>
              <a className="text-sm px-3 py-2 rounded-lg border border-slate-700 hover:bg-slate-800 transition" href="https://www.linkedin.com/">LinkedIn</a>
            </div>
          </section>

          {/* Right column - about content */}
          <section className="md:w-2/3 p-8">
            <div className="flex items-start justify-between">
              <h2 className="text-xl font-semibold">About Me</h2>
              <span className="text-xs text-slate-400">Updated: Oct 1, 2025</span>
            </div>

            <p className="mt-4 text-slate-300 leading-relaxed">Hi — I'm Christian, a Financial Associate at <strong>Experior Financial Group</strong>. I work with families to create tailored, practical financial plans that protect today and build wealth for tomorrow. My approach is simple: listen first, explain clearly, and create solutions that fit each family's unique goals and budget.</p>

            <div className="mt-6 grid grid-cols-1 md:grid-cols-2 gap-4">
              <div className="p-4 rounded-xl border border-slate-700/60 bg-slate-800/30">
                <h3 className="text-sm font-medium">What I do</h3>
                <ul className="mt-2 text-sm text-slate-300 space-y-1">
                  <li>• Life & Disability Insurance</li>
                  <li>• Wealth accumulation strategies</li>
                  <li>• Retirement & estate planning basics</li>
                  <li>• Family-focused financial education</li>
                </ul>
              </div>

              <div className="p-4 rounded-xl border border-slate-700/60 bg-slate-800/30">
                <h3 className="text-sm font-medium">How I work</h3>
                <p className="mt-2 text-sm text-slate-300">I believe financial confidence comes from clear steps and consistent communication. Together we'll prioritize your goals, model options, and implement a straightforward plan you can stick to.</p>
              </div>
            </div>

            <div className="mt-6">
              <h3 className="text-sm font-medium">Values</h3>
              <div className="mt-3 flex flex-wrap gap-2">
                <span className="text-xs px-3 py-1 rounded-full bg-slate-700/60">Integrity</span>
                <span className="text-xs px-3 py-1 rounded-full bg-slate-700/60">Transparency</span>
                <span className="text-xs px-3 py-1 rounded-full bg-slate-700/60">Family-first</span>
                <span className="text-xs px-3 py-1 rounded-full bg-slate-700/60">Long-term focus</span>
              </div>
            </div>

            <div className="mt-6 flex items-center gap-4">
              <a className="px-4 py-2 rounded-lg bg-gradient-to-r from-sky-500 to-indigo-500 font-medium shadow-md hover:scale-[1.01] transition" href="mailto:hello@yourdomain.com?subject=Financial%20Conversation">Schedule a call</a>
              <a className="px-4 py-2 rounded-lg border border-slate-700 hover:bg-slate-800 transition text-sm" href="/services">Services</a>
            </div>

            <footer className="mt-8 text-xs text-slate-500">Experior Financial Group is the brokerage I work with. The information on this page is for general informational purposes and not personalized financial advice. For specific advice, please contact me directly.</footer>
          </section>
        </div>
      </div>
    </main>
  );
}

