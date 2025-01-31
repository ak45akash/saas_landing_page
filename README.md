# SaaS Landing Page

This project is a modern SaaS landing page built using **React** and **Vite**, with a fully responsive UI powered by **Tailwind CSS**.

## Features

- 🎨 Fully Responsive UI
- 📜 Smooth Scrolling ([react-scroll](https://github.com/fisshy/react-scroll))
- 🔄 Animated Number Counting ([react-countup](https://github.com/glennreyes/react-countup))
- 🔽 Collapsible FAQ ([react-slidedown](https://github.com/nkbt/react-slidedown))
- 📝 Reusable Components
- ⚡ Optimized Performance with Vite
- 🌗 Custom Scrollbar Styling

## Technologies Used

- **React**: Frontend library
- **Vite**: Fast development build tool
- **Tailwind CSS**: Utility-first CSS framework
- **react-scroll**: Smooth scrolling
- **react-countup**: Animated number counter
- **react-slidedown**: Collapsible sections

## Installation & Setup

### Clone the repository

```sh
git clone https://github.com/yourusername/saas_landing_page.git
cd saas_landing_page
```

### Install dependencies

```sh
npm install
```

_If you encounter dependency errors while installing `react-slidedown`, use:_

```sh
npm install react-slidedown --legacy-peer-deps
```

### Start the development server

```sh
npm run dev
```

### Build for production

```sh
npm run build
```

### Preview production build

```sh
npm run preview
```

## Custom Styling

### Tailwind CSS Configuration

Modify `tailwind.config.js` as needed:

```js
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### Custom Scrollbar Styling

Modify `index.css`:

```css
::-webkit-scrollbar {
  width: 8px;
}
::-webkit-scrollbar-track {
  background: #f1f1f1;
}
::-webkit-scrollbar-thumb {
  background: #4a90e2;
  border-radius: 10px;
}
```

## Project Structure

```plaintext
saas_landing_page/
│── src/
│   ├── components/      # Reusable components (Button, FAQItem, TestimonialItem, etc.)
│   ├── constants/       # Static data (plans, testimonials, etc.)
│   ├── sections/        # Page sections (Hero, Features, Pricing, Testimonials, etc.)
│   ├── assets/          # Images, icons, SVGs
│   ├── App.jsx          # Main app component
│   ├── main.jsx         # Entry point
│── public/
│── index.html
│── tailwind.config.js
│── postcss.config.js
│── package.json
│── README.md
```

## Contributing

1. Fork the repo
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Added new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request 🚀

## License

This project is **MIT Licensed**. Feel free to modify and use it.

## Contact

📧 Email: [iakash@gmail.com](mailto:iakash@gmail.com)  
💼 LinkedIn: [Akashdeep Kancha](https://www.linkedin.com/in/akashdeep-kancha-4ba330255/)  
🌍 Personal Website: [iakash.dev](https://iakash.dev)  
🎯 Upwork: [Upwork Profile](https://www.upwork.com/freelancers/akancha)

---

### 🚀 Happy Coding! 🎉

