<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reema Portfolio</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #fff1f5; /* soft pink background */
            color: #1e293b;
        }

        header {
            text-align: center;
            padding: 60px;
            background: #f472b6; /* main pink */
            color: white;
        }

        header h1 {
            font-size: 40px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
        }

        section {
            padding: 40px;
            max-width: 900px;
            margin: auto;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 15px;
            margin-top: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
        }

        h2 {
            border-bottom: 2px solid #ec4899;
            padding-bottom: 10px;
        }

        button {
            background: #ec4899;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 10px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #db2777;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #64748b;
        }
    </style>
</head>

<body>

    <header>
        <h1>Reema Aloraini 👩🏻‍💻</h1>
        <p>Computer Science Student | Artificial Intelligence | Data Analysis</p>
    </header>

    <section>
        <h2>About Me</h2>
        <div class="card">
            <p>
                Computer Science student with a strong interest in Artificial Intelligence, 
                Machine Learning, and Data Analysis. Skilled in Python and problem solving, 
                with hands-on experience in building data-driven projects. 
                Passionate about applying technology to solve real-world problems.
            </p>
        </div>
    </section>

    <section>
        <h2>Technical Skills</h2>
        <div class="card">
            <p>
                Python • C++ • Java • Data Analysis • Pandas • Problem Solving • Git
            </p>
        </div>
    </section>

    <section>
        <h2>Projects</h2>

        <div class="card">
            <h3>Arabic Sentiment Analysis</h3>
            <p>
                Developed a Machine Learning model to analyze sentiment in Arabic text 
                using Natural Language Processing (NLP) techniques.
            </p>
            <a href="https://github.com/ReemaRa1/arabic-sentiment-analysis" target="_blank">
                <button>View Project</button>
            </a>
        </div>

        <div class="card">
            <h3>Student Data Analysis</h3>
            <p>
                Built a data analysis project using Python and Pandas to process student data, 
                calculate performance metrics, and identify trends and insights.
            </p>
            <a href="https://github.com/ReemaRa1/student-data-analysis" target="_blank">
                <button>View Project</button>
            </a>
        </div>

    </section>

    <section>
        <h2>Contact</h2>
        <div class="card">
            <p>Email: reema.ebra@icloud.com</p>
        </div>
    </section>

    <footer>
        <p>© 2026 Reema Aloraini</p>
    </footer>

</body>
</html>
