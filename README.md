# Mobile-First React Vite eCommerce UI Template
A premium, highly optimized, and type-safe headless storefront boilerplate built for developers who want a seamless, high-speed frontend layout canvas.

Get the complete source code ZIP archive instantly on 
- [Gumroad](https://dianaborro.gumroad.com/l/nezpwk)
- Fiverr (Coming Soon)
- [Payhip](https://payhip.com/b/21Pl7)
- [Etsy](https://sunflowerycreations.etsy.com/listing/4589962589)

## 🚀 Tech Stack Included
- **Framework Core:** React 19 + Vite
- **Type Safety:** TypeScript
- **Routing Engine:** Modern React Router (`createBrowserRouter` Data Architecture)
- **Data Hydration:** Asynchronous Route Loaders (`useLoaderData`)
- **Styling Layer:** Modular Responsive CSS (Mobile-First Architecture)

## 🛠️ Environment Configuration
This is a pure frontend template engineered to connect directly with your custom API gateway or serverless functions. To link your backend server routing loops, create a `.env` file at the root directory of this project and add your server domain:

```env
VITE_API_URL=http://localhost:5000
```

The `ProductPage.tsx` component features a pre-configured, asynchronous transaction handler that automatically forwards an inventory `stripePriceId` payload to your `${import.meta.env.VITE_API_URL}/api/v1/payment/create-checkout-session` POST endpoint.

## 🏃‍♂️ Quick Start Local Setup
1. Extract the project ZIP directory contents.
2. Open your terminal at the root project folder and download dependencies:
   ```bash
   npm install
   ```
3. Fire up the local Vite development server:
   ```bash
   npm run dev
   ```
4. To build highly optimized, static production files for hosting deployment:
   ```bash
   npm run build
   ```

## 📂 Architecture Structure
All data states, component layouts, and presentational sheets follow clean lowercase modular separation of concerns. To change the inventory data display, simply open `src/data/mockProducts.ts` and swap the placeholder boilerplate parameters inside the strongly-typed array.

Demo: [https://youtu.be/Wi3Js5QI-_Q?si=OiGyVliWJk01HRT6]

<img width="1440" height="775" alt="Screenshot 2026-10-06 at 18 20 18" src="https://github.com/user-attachments/assets/156ac105-b605-4b39-8367-97c6e467a778" />

<img width="1440" height="776" alt="Screenshot 2026-10-06 at 18 20 52" src="https://github.com/user-attachments/assets/34da3a8d-380c-4b32-b814-8b1a54c2fb70" />

<img width="585" height="743" alt="Screenshot 2026-10-06 at 20 33 43" src="https://github.com/user-attachments/assets/44cf0356-1c45-438b-aac0-21799ca2918f" />
