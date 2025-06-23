cat << 'EOF' > README.md
# EclipticX

**EclipticX** is a secure, AI-powered SaaS platform for document generation, business verification, KYC processing, voice & email services, and financial tools. Designed for businesses and individuals needing fast, automated solutions for identity, banking, and compliance.

![EclipticX Logo](https://caqqhiqlsfaxttpmyhvf.supabase.co/storage/v1/object/public/media/sitelogo.webp)

## 🌐 Live Preview
[https://eclipticx.com](https://eclipticx.com)

---

## ✨ Features

- 🧾 **Document Generation**: Auto-generate IRS, bank, ID, license, and business forms.
- 🔐 **Identity & Financial Verification**: Phone, SSN, TIN, BIN, Routing lookup and card validation.
- 📞 **Voice Services**: Call dialer, spoofing, forwarding, recording.
- 📩 **Email Services**: Spoofing, inbox viewer, redirecting.
- 🧠 **X’Assistant AI**: Chatbot with full dashboard control and smart routing.
- 🧑‍💼 **Admin Dashboard**: Full customer management, permissions, service controls.
- 💳 **Subscription Plans**: Tiered pricing with trial, checkout flow, and access-based service.

---

## 🏗️ Tech Stack

- **Frontend**: React + Tailwind CSS (Horizon AI Builder)
- **Backend**: Supabase (PostgreSQL, Auth, Storage, Functions)
- **APIs**:
  - Google Places (address autocomplete)
  - Modern Treasury (bank/card verification)
  - Vonage (phone verification)
  - TINCheck SOAP API (SSN/EIN verification)
  - Stripe (payments & subscription)
  - OpenAI (X’Assistant AI)

---

## 📁 Folder Structure

\`\`\`
/src
├── components/
├── pages/
├── layouts/
├── context/
├── hooks/
└── assets/
\`\`\`

---

## 🚀 Getting Started

\`\`\`bash
# 1. Clone the repo
git clone https://github.com/your-username/eclipticx.git

# 2. Install dependencies
npm install

# 3. Start development server
npm run dev
\`\`\`

---

## 🔐 Environment Variables

Create a `.env` file and include:

\`\`\`env
VITE_SUPABASE_URL=your_project_url
VITE_SUPABASE_ANON_KEY=your_anon_key
VITE_SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
VITE_OPENAI_API_KEY=your_openai_key
VITE_GOOGLE_API_KEY=your_google_places_key
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_pub_key
\`\`\`

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🤝 Contact

- 📧 support@eclipticx.com
- 🌐 [https://eclipticx.com/help-center](https://eclipticx.com/help-center)

---

> Built with love by the EclipticX team 💼
EOF
