/*
Single-file React component + instructions to recreate a modern landing page.
Place this file as `RecreatedPage.jsx` inside a React + Tailwind project (Vite or Create React App).

Quick setup (Vite + Tailwind):
1. npm create vite@latest my-app --template react
2. cd my-app
3. npm install
4. Install Tailwind: https://tailwindcss.com/docs/guides/vite
   - npm install -D tailwindcss postcss autoprefixer
   - npx tailwindcss init -p
   - configure tailwind.config.js content and add @tailwind directives to index.css
5. Drop this file into src/ and import it in src/main.jsx: import RecreatedPage from './RecreatedPage';
   then render <RecreatedPage /> instead of <App />.

This component is a starting point. Tell me what parts of the original site you want matched (fonts, colors, layout, interactions, assets) and I'll iterate.
*/

import React from 'react';

export default function RecreatedPage() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-900">
      <header className="max-w-6xl mx-auto p-6 flex items-center justify-between">
        <div className="flex items-center gap-3">
          <div className="w-10 h-10 bg-gradient-to-tr from-indigo-500 to-pink-500 rounded-lg flex items-center justify-center text-white font-bold">IT</div>
          <div>
            <h1 className="text-lg font-semibold">Ideal Trout</h1>
            <p className="text-sm text-gray-500">Prototype recreation</p>
          </div>
        </div>
        <nav className="hidden md:flex gap-6 items-center text-sm">
          <a className="hover:underline cursor-pointer">Features</a>
          <a className="hover:underline cursor-pointer">Pricing</a>
          <a className="hover:underline cursor-pointer">Docs</a>
          <button className="ml-4 px-4 py-2 rounded-lg bg-indigo-600 text-white text-sm">Get started</button>
        </nav>
        <button className="md:hidden p-2">☰</button>
      </header>

      <main className="max-w-6xl mx-auto px-6 py-12 grid grid-cols-1 md:grid-cols-2 gap-10 items-center">
        <section>
          <h2 className="text-4xl font-extrabold leading-tight">Beautiful UI, built fast.</h2>
          <p className="mt-4 text-gray-600">Recreate web apps quickly with composable components, accessible defaults, and delightful interactions.</p>
          <div className="mt-6 flex gap-3">
            <button className="px-5 py-3 rounded-lg bg-indigo-600 text-white font-medium">Try it free</button>
            <button className="px-5 py-3 rounded-lg border border-gray-200">View docs</button>
          </div>

          <div className="mt-8 grid grid-cols-3 gap-4 text-sm text-gray-600">
            <div className="p-3 bg-white rounded-lg shadow-sm">
              <div className="font-semibold">99.9%</div>
              <div className="text-xs">Uptime</div>
            </div>
            <div className="p-3 bg-white rounded-lg shadow-sm">
              <div className="font-semibold">1k+</div>
              <div className="text-xs">Teams</div>
            </div>
            <div className="p-3 bg-white rounded-lg shadow-sm">
              <div className="font-semibold">24/7</div>
              <div className="text-xs">Support</div>
            </div>
          </div>
        </section>

        <section className="relative">
          <div className="aspect-w-4 aspect-h-3 bg-gradient-to-br from-pink-50 to-indigo-50 rounded-2xl overflow-hidden shadow-lg p-6 flex items-center justify-center">
            <div className="w-full h-full grid grid-rows-3 grid-cols-3 gap-3">
              <div className="col-span-2 row-span-2 bg-white rounded-lg shadow p-4 flex flex-col justify-between">
                <div className="flex items-center justify-between">
                  <div className="text-sm font-medium">Dashboard</div>
                  <div className="text-xs text-gray-400">v1.2</div>
                </div>
                <div className="mt-4 text-xs text-gray-500">Charts, tables and KPIs to monitor your product.</div>
                <div className="mt-4 bg-gray-100 rounded p-2 text-xs">Sample card</div>
              </div>
              <div className="bg-white rounded-lg shadow p-3 text-xs">Activity</div>
              <div className="bg-white rounded-lg shadow p-3 text-xs">Users</div>
              <div className="bg-white rounded-lg shadow p-3 text-xs">Settings</div>
            </div>
          </div>

          <div className="absolute -bottom-6 left-6 flex gap-3">
            <div className="p-3 bg-white rounded-xl shadow-md">Built with React</div>
            <div className="p-3 bg-white rounded-xl shadow-md">Tailwind CSS</div>
          </div>
        </section>
      </main>

      <section className="max-w-6xl mx-auto px-6 py-12">
        <h3 className="text-2xl font-semibold">Features</h3>
        <div className="mt-6 grid grid-cols-1 md:grid-cols-3 gap-6">
          <div className="p-6 bg-white rounded-lg shadow">
            <h4 className="font-semibold">Fast setup</h4>
            <p className="mt-2 text-sm text-gray-600">Start a prototype in minutes with templates and examples.</p>
          </div>
          <div className="p-6 bg-white rounded-lg shadow">
            <h4 className="font-semibold">Accessible</h4>
            <p className="mt-2 text-sm text-gray-600">Built with accessibility best practices in mind.</p>
          </div>
          <div className="p-6 bg-white rounded-lg shadow">
            <h4 className="font-semibold">Composable</h4>
            <p className="mt-2 text-sm text-gray-600">Use small components to compose complex UIs.</p>
          </div>
        </div>
      </section>

      <footer className="border-t mt-8 bg-white">
        <div className="max-w-6xl mx-auto px-6 py-6 flex flex-col md:flex-row justify-between items-center text-sm text-gray-600">
          <div>© {new Date().getFullYear()} Ideal Trout — Prototype</div>
          <div className="flex gap-4 mt-3 md:mt-0">
            <a>Privacy</a>
            <a>Terms</a>
            <a>Contact</a>
          </div>
        </div>
      </footer>
    </div>
  );
}
