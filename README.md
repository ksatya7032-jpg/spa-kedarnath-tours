
export default function SPAKedarnathToursWebsite() { const packages = [ { title: "Char Dham Yatra", desc: "Complete spiritual journey covering Kedarnath, Badrinath, Gangotri & Yamunotri with comfortable travel and stay.", }, { title: "Do Dham Yatra", desc: "Special Uttarakhand pilgrimage packages for Kedarnath & Badrinath with taxi and hotel support.", }, { title: "Single Dham Tours", desc: "Affordable and flexible tours for Kedarnath, Badrinath, Gangotri or Yamunotri.", }, { title: "Taxi Services", desc: "Reliable taxi services from Rishikesh, Haridwar, Dehradun and across Uttarakhand.", }, ];

const destinations = [ "Kedarnath", "Badrinath", "Gangotri", "Yamunotri", "Rishikesh", "Haridwar", "Auli", "Mussoorie", ];

return ( <div className="min-h-screen bg-gradient-to-b from-white to-orange-50 text-gray-800"> {/* Hero Section */} <section className="relative overflow-hidden bg-gradient-to-r from-orange-600 via-orange-500 to-yellow-500 text-white"> <div className="absolute inset-0 opacity-20 bg-[url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1600&auto=format&fit=crop')] bg-cover bg-center" />

<div className="relative max-w-7xl mx-auto px-6 py-24 grid lg:grid-cols-2 gap-10 items-center">
      <div>
        <h1 className="text-5xl md:text-6xl font-bold leading-tight mb-6">
          Kedarnath SPS Tours & Travels
        </h1>

        <p className="text-lg md:text-xl text-orange-100 mb-8 leading-relaxed">
          Trusted Uttarakhand Tours, Char Dham Yatra Packages, Mussoorie Tours, Taxi Services & Spiritual Journeys from Rishikesh.
        </p>

        <div className="flex flex-wrap gap-4">
          <a
            href="https://wa.me/917032616726"
            className="bg-white text-orange-600 px-6 py-3 rounded-2xl font-semibold shadow-lg hover:scale-105 transition"
          >
            Book on WhatsApp
          </a>

          <a
            href="tel:+917032616726"
            className="border border-white px-6 py-3 rounded-2xl font-semibold hover:bg-white hover:text-orange-600 transition"
          >
            Call Now
          </a>
        </div>
      </div>

      <div className="bg-white/10 backdrop-blur-md rounded-3xl p-8 border border-white/20 shadow-2xl">
        <h2 className="text-2xl font-bold mb-6">Why Travel With Us?</h2>

        <div className="space-y-4 text-orange-50">
          <div className="bg-white/10 p-4 rounded-2xl">
            ✔ Experienced local Uttarakhand travel team
          </div>
          <div className="bg-white/10 p-4 rounded-2xl">
            ✔ Comfortable taxi & travel services
          </div>
          <div className="bg-white/10 p-4 rounded-2xl">
            ✔ Budget & premium pilgrimage packages
          </div>
          <div className="bg-white/10 p-4 rounded-2xl">
            ✔ Custom family, group & solo tours
          </div>
        </div>
      </div>
    </div>
  </section>

  {/* About */}
  <section className="max-w-7xl mx-auto px-6 py-20">
    <div className="grid md:grid-cols-2 gap-10 items-center">
      <div>
        <img
          src="https://images.unsplash.com/photo-1528127269322-539801943592?q=80&w=1200&auto=format&fit=crop"
          alt="Kedarnath Tour"
          className="rounded-3xl shadow-2xl h-[420px] object-cover w-full"
        />
      </div>

      <div>
        <h2 className="text-4xl font-bold text-orange-600 mb-6">
          Explore Divine Uttarakhand
        </h2>

        <p className="text-lg leading-relaxed mb-6 text-gray-700">
          Kedarnath SPS Tours & Travels is based in Rishikesh and provides trusted tours, pilgrimage journeys and taxi services across Uttarakhand. We help devotees and travelers experience the beauty of the Himalayas with safe, comfortable and affordable travel solutions.
        </p>

        <p className="text-lg leading-relaxed text-gray-700">
          Whether you are planning a Char Dham Yatra, Kedarnath trip, family holiday or adventure journey, our team is ready to make your travel smooth and memorable.
        </p>
      </div>
    </div>
  </section>

  {/* Services */}
  <section className="bg-white py-20">
    <div className="max-w-7xl mx-auto px-6">
      <div className="text-center mb-14">
        <h2 className="text-4xl font-bold text-orange-600 mb-4">
          Our Services
        </h2>
        <p className="text-gray-600 text-lg">
          Complete Uttarakhand travel, pilgrimage and holiday tour solutions across Uttarakhand.
        </p>
      </div>

      <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
        <div className="bg-white rounded-3xl p-6 shadow-lg border-2 border-orange-200 lg:col-span-4">
          <h3 className="text-3xl font-bold text-orange-600 mb-6 text-center">Tour Package Prices</h3>
          <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-4 text-gray-700">
            <div className="bg-orange-50 p-5 rounded-2xl">
              <h4 className="font-bold text-xl mb-2">Single Dham</h4>
              <p>Starting from ₹6,000 per person</p>
            </div>
            <div className="bg-orange-50 p-5 rounded-2xl">
              <h4 className="font-bold text-xl mb-2">Do Dham Yatra</h4>
              <p>Starting from ₹8,999 per person</p>
            </div>
            <div className="bg-orange-50 p-5 rounded-2xl">
              <h4 className="font-bold text-xl mb-2">Three Dham</h4>
              <p>Starting from ₹14,999 per person</p>
            </div>
            <div className="bg-orange-50 p-5 rounded-2xl">
              <h4 className="font-bold text-xl mb-2">Char Dham Yatra</h4>
              <p>Starting from ₹17,999 per person</p>
            </div>
          </div>

          <div className="mt-8 grid md:grid-cols-2 gap-4">
            <div className="bg-yellow-50 p-5 rounded-2xl">
              <h4 className="font-bold text-2xl mb-2 text-orange-600">Taxi Rates</h4>
              <p>Ertiga: ₹4,500 per day + taxes</p>
              <p>Swift Dzire: ₹3,500 per day + taxes</p>
            </div>

            <div className="bg-yellow-50 p-5 rounded-2xl">
              <h4 className="font-bold text-2xl mb-2 text-orange-600">Special Packages</h4>
              <p>Mussoorie Tour Packages</p>
              <p>Nainital Packages</p>
              <p>All Uttarakhand Holiday Tours</p>
            </div>
          </div>
        </div>
        {packages.map((item, index) => (
          <div
            key={index}
            className="bg-orange-50 rounded-3xl p-6 shadow-lg hover:-translate-y-2 transition"
          >
            <div className="text-4xl mb-4">🛕</div>
            <h3 className="text-2xl font-bold mb-3 text-orange-700">
              {item.title}
            </h3>
            <p className="text-gray-700 leading-relaxed">{item.desc}</p>
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* Destinations */}
  <section className="py-20 bg-gradient-to-b from-orange-50 to-white">
    <div className="max-w-7xl mx-auto px-6">
      <div className="text-center mb-14">
        <h2 className="text-4xl font-bold text-orange-600 mb-4">
          Popular Destinations
        </h2>
        <p className="text-gray-600 text-lg">
          Discover the sacred and scenic beauty of Uttarakhand.
        </p>
      </div>

      <div className="grid grid-cols-2 md:grid-cols-4 gap-6">
        {destinations.map((place, index) => (
          <div
            key={index}
            className="bg-white rounded-3xl p-8 text-center shadow-lg hover:shadow-2xl transition"
          >
            <div className="text-5xl mb-4">🏔️</div>
            <h3 className="text-xl font-bold text-gray-800">{place}</h3>
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* CTA */}
  <section className="py-20 bg-orange-600 text-white">
    <div className="max-w-5xl mx-auto px-6 text-center">
      <h2 className="text-4xl md:text-5xl font-bold mb-6">
        Book Your Uttarakhand Trip Today
      </h2>

      <p className="text-xl text-orange-100 mb-10 leading-relaxed">
        We are accepting bookings for Char Dham Yatra, Kedarnath Tours, Taxi Services and custom Uttarakhand travel packages.
      </p>

      <div className="flex flex-wrap justify-center gap-4">
        <a
          href="https://wa.me/917032616726"
          className="bg-white text-orange-600 px-8 py-4 rounded-2xl text-lg font-bold shadow-lg hover:scale-105 transition"
        >
          WhatsApp Booking
        </a>

        <a
          href="tel:+917032616726"
          className="border-2 border-white px-8 py-4 rounded-2xl text-lg font-bold hover:bg-white hover:text-orange-600 transition"
        >
          Contact Us
        </a>
      </div>
    </div>
  </section>

  {/* Footer */}
  <footer className="bg-gray-900 text-gray-300 py-10">
    <div className="max-w-7xl mx-auto px-6 grid md:grid-cols-3 gap-10">
      <div>
        <h3 className="text-2xl font-bold text-white mb-4">
          Kedarnath SPS Tours & Travels
        </h3>
        <p className="leading-relaxed text-gray-400">
          Trusted travel partner for Uttarakhand tours, Char Dham Yatra and taxi services from Rishikesh.
        </p>
      </div>

      <div>
        <h4 className="text-xl font-semibold text-white mb-4">Services</h4>
        <ul className="space-y-2 text-gray-400">
          <li>Char Dham Yatra</li>
          <li>Do Dham Packages</li>
          <li>Kedarnath Tours</li>
          <li>Taxi Services</li>
        </ul>
      </div>

      <div>
        <h4 className="text-xl font-semibold text-white mb-4">Contact</h4>
        <div className="space-y-3 text-gray-400">
          <p>📍 Rishikesh, Uttarakhand</p>
          <p>📞 +91 7032616726 / +91 630062422</p>
          <p>📧 yourmail@gmail.com</p>
        </div>
      </div>
    </div>

    <div className="border-t border-gray-800 mt-10 pt-6 text-center text-gray-500 text-sm">
      © 2026 Kedarnath SPS Tours & Travels. All rights reserved.
    </div>
  </footer>
</div>

); }
