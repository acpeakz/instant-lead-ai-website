import React from "react";

export default function Website() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-900 p-6">
      <header className="max-w-5xl mx-auto py-10 text-center">
        <h1 className="text-4xl font-bold mb-4">Instant Lead AI Response System</h1>
        <p className="text-lg text-gray-600">
          Convert more leads with automated, human‑quality responses in seconds.
        </p>
      </header>

      <section className="max-w-4xl mx-auto grid md:grid-cols-2 gap-8 mt-12">
        <div className="bg-white p-6 rounded-2xl shadow">
          <h2 className="text-2xl font-semibold mb-3">Why Your Business Needs This</h2>
          <p className="text-gray-600">
            78% of customers buy from the company that replies first. Most
            businesses lose leads simply because they respond too slowly.
            Instant Lead AI fixes that.
          </p>
        </div>
        <div className="bg-white p-6 rounded-2xl shadow">
          <h2 className="text-2xl font-semibold mb-3">What It Does</h2>
          <ul className="list-disc ml-5 text-gray-600 space-y-2">
            <li>Reads incoming leads instantly</li>
            <li>Generates personalized replies with AI</li>
            <li>Sends emails or SMS within seconds</li>
            <li>Fully customized per business</li>
          </ul>
        </div>
      </section>

      <section className="max-w-4xl mx-auto mt-16 bg-white p-8 rounded-2xl shadow">
        <h2 className="text-3xl font-bold mb-6 text-center">Pricing</h2>
        <div className="grid md:grid-cols-3 gap-6">
          <div className="border p-6 rounded-xl text-center">
            <h3 className="text-xl font-semibold mb-2">Starter</h3>
            <p className="text-3xl font-bold mb-4">£99/mo</p>
            <ul className="text-gray-600 space-y-2">
              <li>1 AI automation</li>
              <li>Email responses</li>
              <li>Basic support</li>
            </ul>
          </div>
          <div className="border p-6 rounded-xl text-center bg-gray-100">
            <h3 className="text-xl font-semibold mb-2">Growth</h3>
            <p className="text-3xl font-bold mb-4">£249/mo</p>
            <ul className="text-gray-600 space-y-2">
              <li>Up to 3 automations</li>
              <li>Email & SMS responses</li>
              <li>Priority support</li>
            </ul>
          </div>
          <div className="border p-6 rounded-xl text-center">
            <h3 className="text-xl font-semibold mb-2">Scale</h3>
            <p className="text-3xl font-bold mb-4">£499/mo</p>
            <ul className="text-gray-600 space-y-2">
              <li>Unlimited automations</li>
              <li>Full customization</li>
              <li>Advanced reporting</li>
            </ul>
          </div>
        </div>
      </section>

      <section className="max-w-4xl mx-auto mt-16 text-center">
        <h2 className="text-3xl font-bold mb-4">Ready to Increase Your Sales?</h2>
        <p className="text-gray-600 mb-6">
          Book a free 10‑minute audit and see how much revenue you're losing
          from slow responses.
        </p>
        <button className="px-6 py-3 rounded-xl bg-blue-600 text-white text-lg shadow hover:bg-blue-700 transition">
          Book Free Audit
        </button>
      </section>

      <footer className="mt-20 text-center text-gray-500 pb-10">
        © 2025 AC Productions
      </footer>
    </div>
  );
}
