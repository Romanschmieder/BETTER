/* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Basic styling */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Header and Navigation Bar */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

nav .logo h1 {
    font-size: 24px;
    margin-left: 20px;
}

nav ul {
    list-style-type: none;
    float: right;
    margin-right: 20px;
}

nav ul li {
    display: inline;
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
}

/* Hero Section */
.hero {
    background: #333;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
}

.cta-button:hover {
    background-color: #0056b3;
}

/* Services Section */
#services {
    background: #fff;
    padding: 40px 20px;
    text-align: center;
}

.service-container {
    display: flex;
    justify-content: space-around;
    margin-top: 30px;
}

.service {
    padding: 20px;
    background: #f4f4f4;
    border-radius: 10px;
    width: 30%;
}

.service h3 {
    color: #007bff;
}

/* Contact Section */
#contact {
    background: #f4f4f4;
    padding: 40px 20px;
    text-align: center;
}

#contact form {
    max-width: 500px;
    margin: 0 auto;
    text-align: left;
}

#contact input, #contact textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
}

#contact button {
    padding: 10px 20px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

#contact button:hover {
    background-color: #0056b3;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
