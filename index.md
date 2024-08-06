---
title: Home
layout: home
nav_order: 1
---

# Welcome to Tory's Data Analytics and Data Science Workspace

Hello! I'm Tory, a passionate data professional specializing in analytics and data science. This space showcases my projects, skills, and journey in the world of data.

## What I Do

- **Data Analysis**: Transforming raw data into actionable insights
- **Machine Learning**: Developing predictive models and algorithms
- **Data Visualization**: Creating compelling visual narratives from complex datasets
- **Big Data Processing**: Handling large-scale data with advanced tools and techniques

## Featured Projects

Here are some of my recent projects:

1. **[Project Name 1](link-to-project)**
   Brief description of the project and its impact.

2. **[Project Name 2](link-to-project)**
   Short explanation of what you accomplished and the technologies used.

3. **[Project Name 3](link-to-project)**
   Highlight the problem solved and the results achieved.

## Skills & Tools

- **Programming Languages**: Python, R, SQL
- **Data Analysis Tools**: Pandas, NumPy, SciPy
- **Machine Learning Frameworks**: Scikit-learn, TensorFlow
- **Data Visualization**: Tableau, Matplotlib, Seaborn
- **Big Data Technologies**: Hadoop, Spark
- **Version Control**: Git, GitHub

## Recent Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Let's Connect!

I'm always excited to collaborate on interesting data projects or discuss the latest trends in data science. Feel free to reach out!

- **Email**: [your.email@example.com](mailto:your.email@example.com)
- **LinkedIn**: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- **GitHub**: [github.com/yourusername](https://github.com/yourusername)

Thank you for visiting my workspace. Explore my projects and don't hesitate to get in touch!