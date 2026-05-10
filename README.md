export default function SAHAL22Website() {
const coffeeDesigns = [
{
title: 'Modern Coffee Lounge',
desc: 'Naqshad casri ah oo leh iftiin diiran iyo boorar qurux badan.',
image:
'https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?q=80&w=1200&auto=format&fit=crop',
},
{
title: 'Classic Red Coffee Bar',
desc: 'Style casaan iyo cadaan leh oo soo jiidasho leh.',
image:
'https://images.unsplash.com/photo-1509042239860-f550ce710b93?q=80&w=1200&auto=format&fit=crop',
},
{
title: 'Luxury Coffee Interior',
desc: 'Design premium ah oo ku habboon coffee shops casri ah.',
image:
'https://images.unsplash.com/photo-1521017432531-fbd92d768814?q=80&w=1200&auto=format&fit=crop',
},
{
title: 'Minimal Coffee Setup',
desc: 'Naqshad fudud laakiin aad u qurux badan.',
image:
'https://images.unsplash.com/photo-1511920170033-f8396924c348?q=80&w=1200&auto=format&fit=crop',
},
{
title: 'Coffee Billboard Design',
desc: 'Boorka coffee-ga oo leh xayeysiin casri ah.',
image:
'https://images.unsplash.com/photo-1453614512568-c4024d13c247?q=80&w=1200&auto=format&fit=crop',
},
{
title: 'Elegant Coffee Branding',
desc: 'Branding iyo design isku dhafan oo heer sare ah.',
image:
'https://images.unsplash.com/photo-1445116572660-236099ec97a0?q=80&w=1200&auto=format&fit=crop',
},
];


return (


{/* Header */}




SAHAL22



      <nav className="hidden md:flex gap-8 text-lg font-medium">
        <a href="#home" className="hover:text-red-200 transition">
          Home
        </a>
        <a href="#designs" className="hover:text-red-200 transition">
          Designs
        </a>
        <a href="#about" className="hover:text-red-200 transition">
          About
        </a>
        <a href="#contact" className="hover:text-red-200 transition">
          Contact
        </a>
      </nav>
    </div>
  </header>

  {/* Hero Section */}
  <section
    id="home"
    className="relative h-[90vh] flex items-center justify-center overflow-hidden"
  >
    <img
      src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?q=80&w=1600&auto=format&fit=crop"
      alt="Coffee Shop"
      className="absolute inset-0 w-full h-full object-cover"
    />

    <div className="absolute inset-0 bg-black/50"></div>

    <div className="relative z-10 text-center px-6">
      <h2 className="text-5xl md:text-7xl font-black text-white mb-6 leading-tight">
        Modern Coffee <span className="text-red-500">Designs</span>
      </h2>

      <p className="text-white text-lg md:text-2xl max-w-3xl mx-auto mb-8">
        Ku soo dhowow SAHAL22 — Website casri ah oo loogu talagalay Coffee Shop
        Designs iyo boorar qurux badan.
      </p>

      <a
        href="#designs"
        className="bg-red-600 hover:bg-red-700 text-white px-8 py-4 rounded-2xl text-lg font-bold shadow-2xl transition"
      >
        Explore Designs
      </a>
    </div>
  </section>

  {/* Featured Section */}
  <section className="py-20 bg-gray-50">
    <div className="max-w-7xl mx-auto px-6 text-center">
      <h3 className="text-4xl font-extrabold text-red-600 mb-4">
        Coffee Shop Inspirations
      </h3>

      <p className="text-gray-600 text-lg max-w-3xl mx-auto mb-14">
        Waxaan kuu soo bandhigeynaa design-yadii ugu casrisanaa ee Coffee
        Shops-ka, boorar xayeysiin leh iyo branding heer sare ah.
      </p>

      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
        {coffeeDesigns.map((item, index) => (
          <div
            key={index}
            className="bg-white rounded-3xl overflow-hidden shadow-xl hover:scale-105 transition duration-300"
          >
            <div className="overflow-hidden">
              <img
                src={item.image}
                alt={item.title}
                className="w-full h-72 object-cover hover:scale-110 transition duration-500"
              />
            </div>

            <div className="p-6 text-left">
              <h4 className="text-2xl font-bold text-red-600 mb-3">
                {item.title}
              </h4>

              <p className="text-gray-600 leading-relaxed">{item.desc}</p>

              <button className="mt-6 bg-red-600 hover:bg-red-700 text-white px-5 py-3 rounded-xl font-semibold transition">
                View More
              </button>
            </div>
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* Banner Section */}
  <section className="py-24 bg-red-600 text-white text-center px-6">
    <h3 className="text-5xl font-black mb-6">
      Creative Coffee Billboard Designs
    </h3>

    <p className="max-w-3xl mx-auto text-lg leading-relaxed mb-10">
      SAHAL22 waxay kuu sameyneysaa design casri ah oo leh boorar coffee,
      branding iyo muuqaal luxury ah.
    </p>

    <button className="bg-white text-red-600 hover:bg-gray-100 px-8 py-4 rounded-2xl font-bold text-lg shadow-xl transition">
      Start Your Project
    </button>
  </section>

  {/* About Section */}
  <section id="about" className="py-20 bg-white">
    <div className="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
      <div>
        <img
          src="https://images.unsplash.com/photo-1521017432531-fbd92d768814?q=80&w=1200&auto=format&fit=crop"
          alt="About"
          className="rounded-3xl shadow-2xl"
        />
      </div>

      <div>
        <h3 className="text-4xl font-extrabold text-red-600 mb-6">
          About SAHAL22
        </h3>

        <p className="text-gray-700 text-lg leading-relaxed mb-6">
          SAHAL22 waa website casri ah oo loogu talagalay Coffee Shop Design.
          Waxaan diiradda saarnaa naqshadaha boorarka coffee-ga, gudaha
          coffee shops-ka iyo branding muuqaal qurux badan leh.
        </p>

        <div className="grid grid-cols-2 gap-6">
          <div className="bg-gray-100 rounded-2xl p-6 shadow-md">
            <h4 className="text-3xl font-black text-red-600">120+</h4>
            <p className="text-gray-600 mt-2">Coffee Designs</p>
          </div>

          <div className="bg-gray-100 rounded-2xl p-6 shadow-md">
            <h4 className="text-3xl font-black text-red-600">50+</h4>
            <p className="text-gray-600 mt-2">Happy Clients</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  {/* Contact Section */}
  <section id="contact" className="py-24 bg-gray-50">
    <div className="max-w-4xl mx-auto px-6 text-center">
      <h3 className="text-5xl font-black text-red-600 mb-6">
        Contact Us
      </h3>

      <p className="text-gray-600 text-lg mb-12">
        Nala soo xiriir si aan kuugu sameyno Coffee Shop Design casri ah.
      </p>

      <div className="bg-white rounded-3xl shadow-2xl p-10 text-left">
        <div className="grid md:grid-cols-2 gap-6">
          <input
            type="text"
            placeholder="Your Name"
            className="border border-gray-300 rounded-2xl px-5 py-4 focus:outline-none focus:ring-2 focus:ring-red-500"
          />

          <input
            type="email"
            placeholder="Your Email"
            className="border border-gray-300 rounded-2xl px-5 py-4 focus:outline-none focus:ring-2 focus:ring-red-500"
          />
        </div>

        <textarea
          placeholder="Your Message"
          rows="6"
          className="w-full mt-6 border border-gray-300 rounded-2xl px-5 py-4 focus:outline-none focus:ring-2 focus:ring-red-500"
        ></textarea>

        <button className="mt-6 bg-red-600 hover:bg-red-700 text-white px-8 py-4 rounded-2xl font-bold text-lg transition shadow-lg">
          Send Message
        </button>
      </div>
    </div>
  </section>

  {/* Footer */}
  <footer className="bg-red-600 text-white py-8 text-center">
    <h4 className="text-2xl font-bold mb-2">SAHAL22</h4>
    <p className="text-red-100">
      © 2026 SAHAL22 - Modern Coffee Shop Designs.
    </p>
  </footer>
</div>



);
}

