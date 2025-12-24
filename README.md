<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Développeuse Full-Stack</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 40px 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 40px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: 700;
        }
        
        .header p {
            font-size: 1.1em;
            opacity: 0.95;
            line-height: 1.6;
        }
        
        .content {
            padding: 50px 40px;
        }
        
        .section {
            margin-bottom: 45px;
        }
        
        .section h2 {
            color: #667eea;
            font-size: 1.8em;
            margin-bottom: 25px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
            display: inline-block;
        }
        
        .badges-container {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin-top: 20px;
        }
        
        .badge {
            display: inline-flex;
            align-items: center;
            padding: 10px 16px;
            border-radius: 25px;
            font-weight: 600;
            font-size: 0.95em;
            color: white;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }
        
        .badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.15);
        }
        
        .badge.language {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .badge.frontend {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        }
        
        .badge.backend {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        }
        
        .badge.mobile {
            background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
        }
        
        .badge.database {
            background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
            color: #333;
            font-weight: 700;
        }
        
        .badge.security {
            background: linear-gradient(135deg, #ff6b6b 0%, #ff8e72 100%);
        }
        
        .badge.ai {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .badge.design {
            background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
            color: #333;
            font-weight: 700;
        }
        
        .badge.tools {
            background: linear-gradient(135deg, #30cfd0 0%, #330867 100%);
        }
        
        .footer {
            background: #f8f9fa;
            padding: 40px;
            text-align: center;
            border-top: 2px solid #667eea;
        }
        
        .social-badges {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 25px;
            flex-wrap: wrap;
        }
        
        .social-badge {
            display: inline-flex;
            align-items: center;
            padding: 12px 20px;
            border-radius: 25px;
            font-weight: 600;
            color: white;
            text-decoration: none;
            transition: transform 0.3s;
        }
        
        .social-badge:hover {
            transform: scale(1.05);
        }
        
        .instagram {
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
        }
        
        .linkedin {
            background: #0a66c2;
        }
        
        .gmail {
            background: #ea4335;
        }
        
        .footer p {
            font-size: 1.2em;
            color: #667eea;
            font-weight: 700;
            margin-top: 20px;
        }
        
        @media (max-width: 768px) {
            .header {
                padding: 40px 25px;
            }
            
            .header h1 {
                font-size: 1.8em;
            }
            
            .content {
                padding: 30px 25px;
            }
            
            .section h2 {
                font-size: 1.4em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>👋 Salut ! Je suis une Développeuse Full-Stack</h1>
            <p>Passionnée par la création 🚀<br>Créant des applications web sécurisées et scalables avec du code propre et les meilleures pratiques.</p>
        </div>
        
        <div class="content">
            <div class="section">
                <h2>💬 Langages que j'utilise</h2>
                <div class="badges-container">
                    <span class="badge language">HTML5</span>
                    <span class="badge language">CSS3</span>
                    <span class="badge language">JavaScript</span>
                    <span class="badge language">Java</span>
                    <span class="badge language">Python</span>
                    <span class="badge language">PHP</span>
                    <span class="badge language">C</span>
                    <span class="badge language">C++</span>
                </div>
            </div>
            
            <div class="section">
                <h2>🎨 Développement Frontend</h2>
                <div class="badges-container">
                    <span class="badge frontend">React</span>
                    <span class="badge frontend">Blazor</span>
                    <span class="badge frontend">Bootstrap</span>
                    <span class="badge frontend">Tailwind CSS</span>
                </div>
            </div>
            
            <div class="section">
                <h2>⚙️ Développement Backend</h2>
                <div class="badges-container">
                    <span class="badge backend">Node.js</span>
                    <span class="badge backend">Django</span>
                    <span class="badge backend">REST APIs</span>
                    <span class="badge backend">SOA</span>
                    <span class="badge backend">JEE</span>
                </div>
            </div>
            
            <div class="section">
                <h2>📱 Développement Mobile</h2>
                <div class="badges-container">
                    <span class="badge mobile">Flutter</span>
                    <span class="badge mobile">Android</span>
                </div>
            </div>
            
            <div class="section">
                <h2>💾 Bases de Données</h2>
                <div class="badges-container">
                    <span class="badge database">MongoDB</span>
                    <span class="badge database">MySQL</span>
                    <span class="badge database">Firebase</span>
                </div>
            </div>
            
            <div class="section">
                <h2>🔒 Sécurité & Cybersécurité</h2>
                <div class="badges-container">
                    <span class="badge security">Prévention XSS</span>
                    <span class="badge security">Protection CSRF</span>
                    <span class="badge security">Prévention SQL Injection</span>
                    <span class="badge security">Burp Suite</span>
                </div>
            </div>
            
            <div class="section">
                <h2>📊 Données & IA</h2>
                <div class="badges-container">
                    <span class="badge ai">Big Data</span>
                    <span class="badge ai">Machine Learning</span>
                    <span class="badge ai">Power BI</span>
                </div>
            </div>
            
            <div class="section">
                <h2>🎭 Design UI/UX</h2>
                <div class="badges-container">
                    <span class="badge design">Tailwind CSS</span>
                    <span class="badge design">Figma</span>
                </div>
            </div>
            
            <div class="section">
                <h2>📚 Outils & Productivité</h2>
                <div class="badges-container">
                    <span class="badge tools">VS Code</span>
                    <span class="badge tools">Visual Studio</span>
                    <span class="badge tools">IntelliJ IDEA</span>
                    <span class="badge tools">Eclipse</span>
                    <span class="badge tools">Postman</span>
                    <span class="badge tools">Excel</span>
                    <span class="badge tools">Word</span>
                    <span class="badge tools">PowerPoint</span>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <h2>📍 Où me trouver</h2>
            <div class="social-badges">
                <a href="#" class="social-badge instagram">📸 Instagram</a>
                <a href="#" class="social-badge linkedin">💼 LinkedIn</a>
                <a href="#" class="social-badge gmail">✉️ Gmail</a>
            </div>
            <p>✨ Toujours en apprentissage, toujours en construction ! 🚀</p>
        </div>
    </div>
</body>
</html>
