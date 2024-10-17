<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
      #language-chart {
            max-width: 600px;
            margin: auto;
        }
    </style>
</head>
<body>
    <h2>👋 Hi! I'm Patty</h2>
    <p>I'm a fullstack developer with a strong focus on frontend and experience in backend. I'm passionate about creating efficient and scalable web applications, using HTML, CSS, JavaScript, Angular, React, TypeScript, and Bootstrap on the frontend, as well as Java and Python to develop robust solutions on the backend.</p>

<h3>🛠️ Skills & Technologies:</h3>
    <ul>
        <li><strong>Frontend:</strong>
            <ul>
                <li>Languages: HTML, CSS, JavaScript (ES6+), TypeScript</li>
                <li>Frameworks & Libraries: Angular, React, Bootstrap</li>
                <li>Design: Responsive Design, UI/UX, CSS Grid, Flexbox</li>
            </ul>
        </li>
        <li><strong>Backend:</strong>
            <ul>
                <li>Languages: Java, Python</li>
                <li>Frameworks: Spring Boot (Java), Django (Python)</li>
                <li>Databases: MySQL, PostgreSQL</li>
            </ul>
        </li>
        <li><strong>Tools:</strong> Git, GitHub, npm</li>
    </ul>

<h3>🎮 Hobbies & Interests:</h3>
    <p>Besides coding, I love playing video games 🎮, relaxing with a good book 📚, and enjoying a picnic 🧺 or a coffee ☕ in a cozy café. I find inspiration by blending my passion for technology with these moments of relaxation.</p>
    <h3>🚀 Currently working on:</h3>
    <p>Optimizing performance in complex web applications and deepening my knowledge of microservices architecture using Java and Python on the backend.</p>

   <h3>💬 Ask me about:</h3>
    <p>Frontend development with Angular/React ⚛️, designing RESTful APIs in Java or Python 🐍, and best practices in fullstack programming 💻.</p>

 <h3>🎯 Future Goals:</h3>
    <p>Focusing on improving my skills in advanced frontend frameworks 📈, deepening my expertise in React and Angular, and learning more about performance optimization techniques 🚀 and user experience 🖥️. I also aim to explore new libraries and frontend design patterns to create more intuitive and accessible interfaces 🎨.</p>

  <h3>🌐 Languages Used:</h3>
    <div id="language-chart" style="width: 100%; height: 400px;">
        <canvas id="myChart"></canvas>
    </div>

 <script>
        const ctx = document.getElementById('myChart').getContext('2d');
        const myChart = new Chart(ctx, {
            type: 'doughnut',
            data: {
                labels: ['HTML', 'CSS', 'JavaScript', 'TypeScript', 'Angular', 'React', 'Java', 'Python'],
                datasets: [{
                    label: 'Languages Used',
                    data: [20, 15, 25, 10, 10, 10, 5, 5], // Adjust the usage percentages here
                    backgroundColor: [
                        'rgba(255, 99, 132, 0.2)',
                        'rgba(54, 162, 235, 0.2)',
                        'rgba(255, 206, 86, 0.2)',
                        'rgba(75, 192, 192, 0.2)',
                        'rgba(153, 102, 255, 0.2)',
                        'rgba(255, 159, 64, 0.2)',
                        'rgba(255, 0, 0, 0.2)',
                        'rgba(0, 0, 255, 0.2)'
                    ],
                    borderColor: [
                        'rgba(255, 99, 132, 1)',
                        'rgba(54, 162, 235, 1)',
                        'rgba(255, 206, 86, 1)',
                        'rgba(75, 192, 192, 1)',
                        'rgba(153, 102, 255, 1)',
                        'rgba(255, 159, 64, 1)',
                        'rgba(255, 0, 0, 1)',
                        'rgba(0, 0, 255, 1)'
                    ],
                    borderWidth: 1
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: {
                        position: 'top',
                    },
                    title: {
                        display: true,
                        text: 'Languages Used'
                    }
                }
            }
        });
    </script>
</body>
</html>

