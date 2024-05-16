# 🍰 Ba9lawti

## 📋 Overview

Ba9lawti 🍰 is a premier online platform dedicated to offering a wide range of exquisite Algerian gateaux. Our website provides an effortless shopping experience, allowing users to purchase their favorite gateaux with ease 🛒 and have them delivered directly to their doorstep 🚚. Experience the sweetness of Algeria with Ba9lawti! ✨ Enjoy a delightful journey through our world of delicious sweets 🍬, all from the comfort of your home 🏠. Indulge in the finest Algerian gateaux today! 🎉

## 🌟 Features

- **Authentication:** Implements authentication and authorization features.
- **Buy Gateaux:** Browse and purchase from a diverse collection of traditional and contemporary Algerian gateaux, catering to all tastes and occasions.
- **Livraison Disponible:** Benefit from our reliable delivery service, ensuring your gateaux arrive fresh and on time, wherever you are.
- **Order Management:** Easily manage your orders, track deliveries, and view order history through our intuitive dashboard.
- **Customer Support:** Receive prompt and helpful assistance from our dedicated customer support team, available to answer any questions and resolve issues.
- **Responsive Design:** Fully responsive, ensuring functionality on all devices.
- **Enhanced User Experience:** Provides a seamless and intuitive interface, focusing on usability.

## 🛠️ Tech Stack

- **Next.js:** A React framework for enhanced server-side rendering and static site generation.
- **Supabase:** A scalable backend platform providing database and authentication solutions.
- **TypeScript:** A statically typed superset of JavaScript for improved developer productivity and code quality.
- **Shadcn/ui:** Modern React UI components designed for sleek user interfaces.
- **Tailwind CSS:** A utility-first CSS framework for creating custom designs quickly and efficiently.

## 🚀 Quick Start

To get Ba9lawti running locally on your machine, follow these steps:

1. **Clone the repository:** Use the `git clone` command followed by the repository URL. After cloning, navigate into the project directory using the `cd` command.

   ```bash
   git clone https://github.com/chouaib-dj/ba9lawti.git
   cd ba9lawti
   ```

2. **Install the dependencies:** Run the `pnpm install` command to install all required dependencies.

   ```bash
   pnpm install
   ```

3. **Set up your environment variables:** Create a `.env.local` file in the root directory. Inside this file, include your Supabase URL and Anon Key with the appropriate variable names.

   ```plaintext
   NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
   ```

4. **Run the database SQL script:** In Supabase's SQL editor, paste the contents of `database.sql` and execute the queries to create the database schema.

5. **Update email templates in Supabase:** In the Supabase dashboard, navigate to the "Authentication" section, then go to "Email Templates". Update the templates for the "confirm signup" and "magic link" emails.

6. **Run the development server:** Use the `pnpm dev` command to start the development server. Once running, you can access the application by visiting `http://localhost:3000` in your web browser.

   ```bash
   pnpm dev
   ```

Following these steps should get Ba9lawti up and running locally on your machine using pnpm.

## 📑 License

Ba9lawti is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📫 Contact

If you have any questions or need further assistance with Ba9lawti, please don't hesitate to reach out via email: [djaidri.chouaib.24@gmail.com](mailto:djaidri.chouaib.24@gmail.com).
