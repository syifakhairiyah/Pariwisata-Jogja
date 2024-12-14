/* Global Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #fdf8f2; /* Warna krem */
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background-color: #8b4513; /* Cokelat kayu */
    color: white;
    padding: 1rem;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 1000;
}

header h1 {
    font-size: 2rem;
    margin: 0;
    font-family: 'Georgia', serif;
}

nav {
    margin-top: 0.5rem;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 1rem;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    background-image: url('hero-image.jpg'); /* Ganti dengan foto Yogyakarta */
    background-size: cover;
    background-position: center;
    height: 70vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    position: relative;
}

.hero::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5); /* Overlay gelap */
    z-index: 1;
}

.hero h2 {
    font-size: 2.5rem;
    z-index: 2;
    position: relative;
}

.hero p {
    font-size: 1.2rem;
    margin-top: 0.5rem;
    z-index: 2;
    position: relative;
}

/* Section */
section {
    padding: 2rem;
    margin: 1rem auto;
    max-width: 1200px;
}

section h2 {
    text-align: center;
    margin-bottom: 1.5rem;
    font-family: 'Georgia', serif;
    color: #8b4513;
}

/* Gallery */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
}

.gallery img {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Pricing Table */
.pricing {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
}

.pricing .card {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 1.5rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 300px;
}

.pricing .card h3 {
    color: #8b4513;
}

.pricing .card p {
    margin: 1rem 0;
}

/* Contact Form */
.contact-form {
    max-width: 600px;
    margin: 0 auto;
}

.contact-form input, .contact-form textarea {
    width: 100%;
    padding: 0.75rem;
    margin-bottom: 1rem;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 1rem;
}

.contact-form button {
    background-color: #8b4513;
    color: white;
    border: none;
    padding: 0.75rem 1.5rem;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 4px;
}

.contact-form button:hover {
    background-color: #a0522d;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}

footer a {
    color: #ffa500;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
