<h1 align="center">MrArCode - Java & Kotlin Developer</h1>

<p align="center" style="font-size: 18px;">
  I’m passionate about Java, with Kotlin as my go-to language for powerful, modern development. I thrive on challenges, and promoting innovative solutions is my passion. Let’s build something impactful together—I'm open to new and challenging projects!
</p>

## 🧰 Tech Stack & Skills

<div align="center" style="width: 100%;">
  
  <!-- Programming Languages -->
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" style="margin: 5px;"/>

  <!-- Build Tools -->
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" alt="Gradle" style="margin: 5px;"/>

  <!-- Version Control & Collaboration -->
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab" style="margin: 5px;"/>

  <!-- Database Technologies -->
  <img src="https://img.shields.io/badge/Oracle_SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle SQL" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apache-cassandra&logoColor=white" alt="Cassandra" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/JDBC-003B57?style=for-the-badge&logo=database&logoColor=white" alt="JDBC" style="margin: 5px;"/>

  <!-- Web Development & Frameworks -->
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/Jsoup-4285F4?style=for-the-badge&logo=java&logoColor=white" alt="Jsoup" style="margin: 5px;"/>

  <!-- DevOps & Cloud -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" style="margin: 5px;"/>

  <!-- Testing & Automation -->
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" style="margin: 5px;"/>
  <img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit" style="margin: 5px;"/>

  <!-- IDEs -->
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white" alt="IntelliJ IDEA" style="margin: 5px;"/>
</div>

## 📝 About Me

<p align="center" style="font-size: 18px;">
With a strong focus on backend development, I’m driven by a passion for understanding how various systems operate—from programming languages to databases and APIs. I specialize in creating scalable, high-performance applications and optimizing backend systems. Deeply interested in artificial intelligence, I regularly experiment with new tools and frameworks to stay at the forefront of tech innovation. Let’s build something impactful together!

</p>

## 🚀 Projects & Experience

### [SQLForge](https://github.com/MrArCode/SQLForge)

- **Description**: SQLForge is a Java-based tool designed to automate SQL script generation for database operations. It supports core **CRUD** operations (Create, Read, Update, Delete) and uses the **Faker** library to generate realistic test data, making it ideal for database testing and data manipulation.
  
- **Features**:
  - Generates `CREATE TABLE`, `INSERT`, `SELECT`, `UPDATE`, and `DELETE` SQL statements.
  - Supports the definition of primary/foreign keys, unique constraints, and data types.
  - Provides automated test data generation using **Faker**.

- **Technologies**: ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white), ![Faker](https://img.shields.io/badge/Faker-6DB33F?style=flat-square&logo=java&logoColor=white)

- **Core Methods**:
  - **ScriptBuilder**: `addTable`, `includeCreate`, `includeInsert`, `includeRead`, `includeUpdate`, `includeDelete`, `withDataGenerator`.
  - **Table and Column Management**: `addColumn`, `setPrimaryKey`, `setNotNull`, `setUnique`, `setForeignKey`.

> Developed by **MrArCode** | License: MIT License

### [Job Portal Aggregator and Auto-Apply System](https://github.com/MrArCode/JobPortalAggregator)

- **Description**: A Java-based tool that simplifies job applications by aggregating listings from multiple job portals and automating the submission process. This system collects job links, filters them, and automatically logs in to submit applications on behalf of the user.

- **Key Features**:
  - **Job Aggregation**: Collects job links from portals like Pracuj, Praca, and JustJoin.it.
  - **Link Caching**: Caches job pages to avoid redundant scraping.
  - **Automated Submission**: Uses Selenium to log in and apply to jobs automatically.

- **Technologies**: ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white), ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white), ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white), ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

- **Future Enhancements**:
  - **Additional Job Portals**: Expand support to more platforms.
  - **CAPTCHA Handling**: Enhance CAPTCHA bypass techniques for smoother automation.

> Developed by **MrArCode** | License: MIT License

### [🛒 Price Comparison Tool](https://github.com/MrArCode/PriceComparisonTool)

- **Description**: A Java-based application designed to streamline price comparisons by scraping product information from multiple online stores. This tool retrieves product names and prices, groups similar items based on spelling, and highlights the best deals for users by identifying the lowest prices.

- **Key Features**:
  - **Web Scraping and Caching**: Uses Jsoup and Playwright to collect and cache product data, ensuring faster comparisons.
  - **Price Comparison**: Identifies the lowest prices among listed items across stores.
  - **Product Grouping**: Groups similar items based on spelling, ensuring accurate comparisons.

- **Technologies**: ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white), ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white), ![Jsoup](https://img.shields.io/badge/Jsoup-4285F4?style=flat-square&logo=java&logoColor=white), ![Playwright](https://img.shields.io/badge/Playwright-2D8CFF?style=flat-square&logo=playwright&logoColor=white), ![Lombok](https://img.shields.io/badge/Lombok-007ACC?style=flat-square&logo=lombok&logoColor=white)

- **Supported Stores**:
  - [Biedronka](https://zakupy.biedronka.pl/), [Kaufland](https://sklep.kaufland.pl/), [Delio](https://delio.com.pl/), [Lisek](https://sklep.lisek.app/), [Frisco](https://www.frisco.pl/), [Auchan](https://zakupy.auchan.pl/)

- **Important Notes**:
  - **Website Structure Changes**: Changes in website layout may require updates to the scraping selectors.
  - **Kaufland Updates**: The Kaufland link may need manual updates to remain accurate with weekly offers.

> Developed by **MrArCode** | License: MIT License

## 📊 Stats

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=MrArCode&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=false" alt="GitHub Stats" width="400px"/>
      </td>
      <td align="center">
       <img src="https://leetcode-stats.vercel.app/api?username=MrArCode&theme=dark&extension=activity" alt="LeetCode Stats" width="400px"/>
      </td>
    </tr>
  </table>
</div>



## 📫 Social Media & Contact

<div align="left" style="width: 100%; font-size: 1.5em;">
  <a href="mailto:mr.arcode@example.com" style="margin: 0 15px;">
    <img src="https://img.icons8.com/color/48/000000/gmail-new.png" title="Email" width="40" height="40"/>
  </a>
  <a href="https://www.linkedin.com/in/mrarcode/" style="margin: 0 15px;">
    <img src="https://img.icons8.com/color/48/000000/linkedin.png" title="LinkedIn" width="40" height="40"/>
  </a>
</div>

## 📚 My Learning Journey

### 📘 Books
- **"Clean Code"** by Robert C. Martin  
  *Insightful guide on writing clean, maintainable code.*

### 📜 Courses

### 🎥 Videos & Tutorials
- **[Kotlin Course - Tutorial for Beginners](https://www.youtube.com/watch?v=F9UC9DY-vIU&t=1027s)**  
  *Beginner-friendly introduction to Kotlin programming.*



