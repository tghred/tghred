<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taghred Salah Ashry - Data Engineer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #e2e8f0;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .container {
            background-color: rgba(30, 41, 59, 0.8);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            margin-top: 20px;
            border: 1px solid #334155;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 30px;
            border-bottom: 2px solid #3b82f6;
        }
        
        h1 {
            color: #60a5fa;
            font-size: 2.8rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #60a5fa, #38bdf8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        h2 {
            color: #38bdf8;
            font-size: 1.8rem;
            margin-bottom: 30px;
        }
        
        h3 {
            color: #7dd3fc;
            font-size: 1.5rem;
            margin: 25px 0 15px;
        }
        
        h4 {
            color: #a5b4fc;
            font-size: 1.2rem;
            margin-bottom: 10px;
        }
        
        .badges {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
            flex-wrap: wrap;
        }
        
        .badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 10px 20px;
            background-color: #1e293b;
            border-radius: 30px;
            color: #e2e8f0;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            border: 1px solid #334155;
        }
        
        .badge:hover {
            background-color: #3b82f6;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(59, 130, 246, 0.4);
        }
        
        .tech-section {
            margin: 40px 0;
        }
        
        .tech-category {
            margin-bottom: 30px;
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            gap: 20px;
            margin-top: 15px;
        }
        
        .tech-item {
            background-color: #1e293b;
            border-radius: 12px;
            padding: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid #334155;
            height: 120px;
        }
        
        .tech-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(59, 130, 246, 0.2);
            border-color: #3b82f6;
        }
        
        .tech-icon {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #60a5fa;
        }
        
        .tech-icon img {
            width: 40px;
            height: 40px;
            object-fit: contain;
        }
        
        .tech-name {
            font-size: 0.9rem;
            text-align: center;
            color: #cbd5e1;
        }
        
        .about-section {
            background-color: rgba(30, 41, 59, 0.6);
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            border-left: 4px solid #3b82f6;
        }
        
        .highlight {
            color: #60a5fa;
            font-weight: 600;
        }
        
        .snapshot {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 25px;
        }
        
        .snapshot-item {
            background-color: #1e293b;
            padding: 20px;
            border-radius: 12px;
            border-top: 4px solid #3b82f6;
        }
        
        .snapshot-item i {
            color: #3b82f6;
            margin-right: 10px;
            font-size: 1.2rem;
        }
        
        .contact-info {
            text-align: center;
            margin-top: 40px;
            padding-top: 30px;
            border-top: 1px solid #334155;
        }
        
        .contact-link {
            color: #60a5fa;
            text-decoration: none;
            font-weight: 600;
        }
        
        .contact-link:hover {
            text-decoration: underline;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .tech-grid {
                grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
            }
            
            .badges {
                flex-direction: column;
                align-items: center;
            }
        }
        
        @media (max-width: 480px) {
            .tech-grid {
                grid-template-columns: repeat(3, 1fr);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Hey 👋 I'm Taghred Salah Ashry</h1>
            <h2>Data Engineer | ETL Developer | Big Data Engineer</h2>
            
            <div class="badges">
                <a href="https://www.linkedin.com/in/taghredsalah199/" target="_blank" class="badge">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
                <a href="mailto:taghred.ashry@gmail.com" class="badge">
                    <i class="fas fa-envelope"></i> Gmail
                </a>
                <a href="https://www.facebook.com/tghred.salah/" target="_blank" class="badge">
                    <i class="fab fa-facebook"></i> Facebook
                </a>
            </div>
        </div>
        
        <div class="tech-section">
            <h3>🛠️ Technologies & Tools</h3>
            
            <div class="tech-category">
                <h4>Programming Languages</h4>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-python"></i>
                        </div>
                        <div class="tech-name">Python</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-java"></i>
                        </div>
                        <div class="tech-name">Java</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-js"></i>
                        </div>
                        <div class="tech-name">JavaScript</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-code"></i>
                        </div>
                        <div class="tech-name">Scala</div>
                    </div>
                </div>
            </div>
            
            <div class="tech-category">
                <h4>Data Engineering Technologies</h4>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg" alt="Apache Spark">
                        </div>
                        <div class="tech-name">Apache Spark</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/d/de/AirflowLogo.png" alt="Apache Airflow">
                        </div>
                        <div class="tech-name">Apache Airflow</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://www.getdbt.com/ui/img/logos/dbt-icon.png" alt="dbt">
                        </div>
                        <div class="tech-name">dbt</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-database"></i>
                        </div>
                        <div class="tech-name">Oracle</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-server"></i>
                        </div>
                        <div class="tech-name">SQL Server</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://www.snowflake.com/wp-content/themes/snowflake/assets/img/brand-guidelines/logo-snowflake.svg" alt="Snowflake">
                        </div>
                        <div class="tech-name">Snowflake</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-aws"></i>
                        </div>
                        <div class="tech-name">Redshift</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-stream"></i>
                        </div>
                        <div class="tech-name">Kafka</div>
                    </div>
                </div>
            </div>
            
            <div class="tech-category">
                <h4>Databases</h4>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-database"></i>
                        </div>
                        <div class="tech-name">PostgreSQL</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-database"></i>
                        </div>
                        <div class="tech-name">MySQL</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-leaf"></i>
                        </div>
                        <div class="tech-name">MongoDB</div>
                    </div>
                </div>
            </div>
            
            <div class="tech-category">
                <h4>Cloud Computing</h4>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-aws"></i>
                        </div>
                        <div class="tech-name">AWS</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-microsoft"></i>
                        </div>
                        <div class="tech-name">Azure</div>
                    </div>
                </div>
            </div>
            
            <div class="tech-category">
                <h4>Other Tools & Technologies</h4>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-git-alt"></i>
                        </div>
                        <div class="tech-name">Git</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-docker"></i>
                        </div>
                        <div class="tech-name">Docker</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fab fa-linux"></i>
                        </div>
                        <div class="tech-name">Linux</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <i class="fas fa-terminal"></i>
                        </div>
                        <div class="tech-name">Bash</div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="about-section">
            <h3>🚀 About Me</h3>
            <p>Passionate about data and big data. My skills in data engineering, cloud architecture, and data pipelines are focused on building scalable, cost-efficient ELT/ETL data pipelines that enables accurate business intelligence and real-time decision-making.</p>
            
            <div class="snapshot">
                <div class="snapshot-item">
                    <h4><i class="fas fa-tasks"></i> Currently Working On</h4>
                    <p>Enhancing <span class="highlight">data pipelines</span> and <span class="highlight">ETL processes</span> within a <span class="highlight">Big Data (Spark)</span> environment.</p>
                </div>
                
                <div class="snapshot-item">
                    <h4><i class="fas fa-graduation-cap"></i> Actively Learning</h4>
                    <p>Building expertise in <span class="highlight">Streaming Data Pipelines</span> and <span class="highlight">Cloud Infrastructure</span> for data engineering.</p>
                </div>
                
                <div class="snapshot-item">
                    <h4><i class="fas fa-briefcase"></i> Open to Roles</h4>
                    <p>Data Engineer, ETL Developer, and Big Data Engineer positions.</p>
                </div>
            </div>
        </div>
        
        <div class="contact-info">
            <h3>📫 Contact Me</h3>
            <p>You can contact me via email: <a href="mailto:taghred.ashry@gmail.com" class="contact-link">taghred.ashry@gmail.com</a></p>
            <p>Or through my social media accounts mentioned above.</p>
        </div>
    </div>
    
    <script>
        // Add simple interactive effects
        document.addEventListener('DOMContentLoaded', function() {
            const techItems = document.querySelectorAll('.tech-item');
            
            techItems.forEach(item => {
                item.addEventListener('mouseenter', function() {
                    this.style.transform = 'translateY(-8px) scale(1.05)';
                });
                
                item.addEventListener('mouseleave', function() {
                    this.style.transform = 'translateY(0) scale(1)';
                });
            });
            
            // Add effects for icons
            const icons = document.querySelectorAll('.tech-icon i, .tech-icon img');
            icons.forEach(icon => {
                icon.addEventListener('mouseenter', function() {
                    this.style.transition = 'transform 0.3s ease';
                    this.style.transform = 'rotate(10deg)';
                });
                
                icon.addEventListener('mouseleave', function() {
                    this.style.transform = 'rotate(0)';
                });
            });
        });
    </script>
</body>
</html>