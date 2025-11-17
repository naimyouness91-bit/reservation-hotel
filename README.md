<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<!-- <title>Hotel Reservation Project Report</title> -->

</head>
<body>
<h1>🏨 HOTELIER — React Hotel Reservation Platform</h1>
<p>A modern, elegant and fully responsive hotel reservation web application built using React. This project provides room browsing, booking flow, service pages, staff pages, and more.</p>

<div class="section">
<h2>📸 Project Homepage Screenshot</h2>
<p>Below is a screenshot representing the homepage UI of the project:</p>
<img src="https://github.com/user-attachments/assets/b8e6a19e-746c-4b7a-80fd-3cc00e8cbf37" />
</div>

<div class="section">
<h2>🚀 Features</h2>
<ul>
 <li>Responsive UI with hero slider, booking form, services, rooms, and staff sections.</li>
 <li>Room listing with prices, details, and booking buttons.</li>
 <li>Services overview section.</li>
 <li>Team / Staff section with images and social links.</li>
 <li>Newsletter subscription section.</li>
 <li>Common reusable components (Header, Footer, Headings).</li>
</ul>
</div>

<div class="section">
<h2>📁 Project Structure</h2>
<pre>
src/
├── components/
│   ├── common/
│   │   ├── CommonHeading.jsx
│   │   ├── Footer.jsx
│   │   ├── Header.jsx
│   │   ├── Heading.jsx
│   │   └── Socialcons.jsx
│   ├── data/
│   │   └── Data.jsx
│   ├── home/
│   │   ├── About.js
│   │   ├── Book.js
│   │   ├── Carousel.js
│   │   ├── Home.js
│   │   ├── Newsletter.js
│   │   ├── Rooms.js
│   │   ├── Service.js
│   │   ├── Slider.js
│   │   └── Team.js
├── css/
│   ├── animate.css
│   ├── animate.min.css
│   ├── bootstrap.min.css
│   └── style.css
├── pages/
│   ├── AboutUs.js
│   ├── BookingPage.js
│   ├── ContactPage.js
│   ├── index.js
│   ├── PageNotFound.js
│   ├── RoomPage.js
│   ├── ServicesPage.js
│   ├── TeamPage.js
│   └── TestimonialPage.js
├── App.css
├── App.js
├── index.js
.gitignore
package-lock.json
package.json
README.md
</pre>
</div>

<div class="section">
<h2>🛠️ Tech Stack</h2>
<ul>
 <li><strong>React</strong> — Functional components & hooks</li>
 <li><strong>JavaScript (ES6+)</strong></li>
 <li><strong>Bootstrap + custom CSS</strong></li>
 <li><strong>Animate.css</strong> for transitions & effects</li>
 <li><strong>Node.js & npm</strong></li>
</ul>
</div>

<div class="section">
<h2>📌 Pages / Routes</h2>
<ul>
 <li>/ — Homepage</li>
 <li>/rooms — Rooms listing</li>
 <li>/room/:id — Single room details</li>
 <li>/booking — Booking page</li>
 <li>/services — Services detail page</li>
 <li>/about — About us page</li>
 <li>/team — Team page</li>
 <li>/contact — Contact page</li>
 <li>/* — Page Not Found</li>
</ul>
</div>

<div class="section">
<h2>🖥️ Design & UI Highlights</h2>
<ul>
 <li>Modern hotel-themed layout.</li>
 <li>Hero slider with booking search bar.</li>
 <li>Room cards with pricing, images, and ratings.</li>
 <li>Services displayed in interactive cards.</li>
 <li>Team section with social media icons.</li>
 <li>Newsletter subscription module.</li>
</ul>
</div>

<div class="section">
<h2>📦 Installation</h2>
<ol>
 <li>Clone the project:<br><span class="code">git clone &lt;repo-url&gt;</span></li>
 <li>Install dependencies:<br><span class="code">npm install</span></li>
 <li>Run development server:<br><span class="code">npm start</span></li>
 <li>Build for production:<br><span class="code">npm run build</span></li>
</ol>
</div>

<div class="section">
<h2>✔️ Conclusion</h2>
<p>This React-based hotel reservation platform delivers a professional, clean, and modern experience suitable for hotel businesses, agencies, or portfolio projects. It is modular, scalable, and ready for backend integration.</p>
</div>

</body>
</html>
