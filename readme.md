<div id="fa" dir="rtl">
  <h1 align="center">✨Task Manager✨</h1>
  <p align="center">
    <a href="#fa">🗺️ Persian</a> / <a href="#en">English 🗺️</a>
  </p>
  <h3>📃درباره پروژه : </h3>
  <p>
    پروژه <strong>Task Manager</strong>،
    یک برنامه کاربردی برای مدیریت کارهای روزانه است.
    <br /> این پروژه با استفاده از <a href="#tech">فناوری های زیر</a> ساخته شده است.
  </p>
  <h3>🏗️چطور پروژه را اجرا کنیم؟</h3>
  <p>
    ابتدا وارد پوشه ای شوید که می خواهید پروژه را در آنجا داشته باشید و سپس دستورات زیر را وارد کنید.
  </p>
  <pre dir="ltr"><code class="language-bash">git clone https://github.com/AlirezaaMoradi/Task-Manager.git<br /><br />cd Task-Manager</code></pre>
  <p>
    ⚠️اگر 
    <strong>Git</strong> را ندارید می توانید آن را <a href="https://github.com/git-for-windows/git/releases/download/v2.51.0.windows.1/Git-2.51.0-64-bit.exe">از اینجا</a> بگیرید.
  </p>
  <p>
    وارد پوشه پروژه شوید،
    ابتدا باید اطلاعات فایل <ins><b>.env</b></ins>
    را در پوشه های <ins><b>server</b></ins> و <ins><b>client</b><ins> با اطلاعات خودتان تغییر دهید.
  </p>
  <p>
    شما میتوانید این پروژه را به دو صورت زیر اجرا کنید :<br />
    <a href="#withDocker">با استفاده از Docker</a> |
    <a href="#withoutDocker">بدون استفاده از Docker</a>
  </p>
  <h4 id="withDocker">⭐با استفاده از Docker :</h4>
  <strong>پیش نیازها :</strong>
  <p>
  برای اجرا کردن پروژه با Docker شما تنها باید <strong>Docker Desktop</strong> را روی سیستم خود نصب داشته باشید.
  </p>
  <p>
  با در نظر گرفتن اینکه شما پیش نیاز های پروژه را دارید، وارد پوشه پروژه شوید و دستورات زیر را وارد کنید :
  </p>
  <pre dir="ltr"><code class="language-bash">docker compose up -d</code></pre>
  <p>
  بعد از اتمام کار، مرورگر خود را باز کنید و به آدرس <b>http://localhost:3000</b> بروید.
  </p>
  <h4 id="withoutDocker">⭐بدون استفاده از Docker :</h4>
  <strong>پیش نیازها :</strong>
  <p>
    <a href="https://nodejs.org/en">Node.js</a> | <a href="https://www.postgresql.org/">PostgreSQL</a>
  </p>
  <p>
    وارد <strong>PgAdmin</strong> شوید و کویری زیر را اجرا کنید.
  </p>
  <pre dir="ltr"><code class="language-bash">CREATE DATABASE task-manager;</code></pre>
  <p>و بعد از ساختن دیتابیس وارد ترمینال پروژه شوید و دستورات زیر را وارد کنید.</p>
  <pre dir="ltr"><code class="language-bash">npm install</code></pre>
  <pre dir="ltr"><code class="language-bash">npm run build</code></pre>
  <pre dir="ltr"><code class="language-bash">node dist/main.js</code></pre>
  <p>
  بعد از اتمام کار، مرورگر خود را باز کنید و به آدرس <b>http://localhost:3000</b> بروید.
  </p>
  <h3 id="tech">🛠️تکنولوژی ها :</h3>
  <table dir="ltr">
    <thead>
      <th>فرانت اند</th>
      <th>بک اند</th>
    </thead>
    <tbody>
      <tr>
        <td>TypeScript</td>
        <td>Node.js</td>
      </tr>
      <tr>
        <td>React</td>
        <td>NestJS</td>
      </tr>
      <tr>
        <td>Redux</td>
        <td>PostgreSQL</td>
      </tr>
      <tr>
        <td>Next.js</td>
        <td>Swagger</td>
      </tr>
      <tr>
        <td>React Query</td>
        <td>Bcrypt</td>
      </tr>
      <tr>
        <td>Axios</td>
        <td>JWT</td>
      </tr>
      <tr>
        <td>Shadcn/UI</td>
        <td>Nodemailer</td>
      </tr>
      <tr>
        <td>Tailwindcss</td>
        <td>Multer</td>
      </tr>
      <tr>
        <td>Docker</td>
        <td>Docker</td>
      </tr>
      <tr>
        <td>Git</td>
        <td>Git</td>
      </tr>
      <tr>
        <td>...</td>
        <td>...</td>
      </tr>
    </tbody>
  </table>
  <h3>🍵توسعه دهنده ها :</h3>
  <p>توسعه دهنده فرانت اند : 
    <a href="https://github.com/AlirezaaMoradi">
      <b>علیرضا مرادی</b>
    </a>
  </p>
  <p>توسعه دهنده بک اند : 
    <a href="https://github.com/AlirezaaMoradi">
      <b>علیرضا مرادی</b>
    </a>
  </p>
</div>

<div id="en" dir="ltr">
  <h1 align="center">✨Task Manager✨</h1>
  <p align="center">
    <a href="#fa">🗺️ Persian</a> / <a href="#en">English 🗺️</a>
  </p>
  <h3>📃About the Project :</h3>
  <p>
    The <strong>Task Manager</strong> project is an application for managing daily tasks.
    <br />This project is built using the following<a href="#tech">technologies </a>.
  </p>
  <h3>🏗️ How to run the project?</h3>
  <p>
    First, navigate to the folder where you want to have the project, and then enter the following commands.
  </p>
  <pre><code class="language-bash">git clone https://github.com/AlirezaaMoradi/Task-Manager.git<br /><br />cd Task-Manager</code></pre>
  <p>
    ⚠️If you don’t have <strong>Git</strong>, you can get it <a href="https://github.com/git-for-windows/git/releases/download/v2.51.0.windows.1/Git-2.51.0-64-bit.exe">here</a>.
  </p>
  <p>
  Navigate to the project folder.
  First, you need to update the <ins><b>.env</b></ins> file in the <ins><b>server</b></ins> and <ins><b>client</b></ins> folders with your own information.
  </p>
  <p>
    You can run this project in two ways:<br /> <a href="#withDocker">Using Docker</a> | <a href="#withoutDocker">Without Docker</a>
  </p>
  <h4 id="withDocker">⭐Using Docker:</h4>
  <strong>Prerequisites:</strong>
  <p>
    To run the project with Docker, you only need to have <strong>Docker Desktop</strong> installed on your system.
  </p>
  <p>
    Considering that you already have the project prerequisites, navigate to the project folder and run the following command:
  </p>
  <pre><code class="language-bash">docker compose up -d</code></pre>
  <p>
    After the process is complete, open your browser and go to <b>http://localhost:3000</b>.
  </p>
  <h4 id="withoutDocker">⭐Without using Docker:</h4>
  <strong>Prerequisites:</strong>
  <p>
    <a href="https://nodejs.org/en">Node.js</a> | <a href="https://www.postgresql.org/">PostgreSQL</a>
  </p>
  <p>
    Open <strong>PgAdmin</strong> and run the following query:
  </p>
  <pre dir="ltr"><code class="language-bash">CREATE DATABASE task-manager;</code></pre>
  <p>
    After creating the database, open a terminal in the project folder and run the following commands:

  </p>
  <pre><code class="language-bash">npm install</code></pre>
  <pre><code class="language-bash">npm run build</code></pre>
  <pre><code class="language-bash">node dist/main.js</code></pre>
  <p>  
    After the process is complete, open your browser and go to <b>http://localhost:3000</b>.  
  </p>
  <h3 id="tech">🛠️Tecknologies :</h3>
  <table dir="ltr">
    <thead>
      <th>Frontend</th>
      <th>Backend</th>
    </thead>
    <tbody>
      <tr>
        <td>TypeScript</td>
        <td>Node.js</td>
      </tr>
      <tr>
        <td>React</td>
        <td>NestJS</td>
      </tr>
      <tr>
        <td>Redux</td>
        <td>PostgreSQL</td>
      </tr>
      <tr>
        <td>Next.js</td>
        <td>Swagger</td>
      </tr>
      <tr>
        <td>React Query</td>
        <td>Bcrypt</td>
      </tr>
      <tr>
        <td>Axios</td>
        <td>JWT</td>
      </tr>
      <tr>
        <td>Shadcn/UI</td>
        <td>Nodemailer</td>
      </tr>
      <tr>
        <td>Tailwindcss</td>
        <td>Multer</td>
      </tr>
      <tr>
        <td>Docker</td>
        <td>Docker</td>
      </tr>
      <tr>
        <td>Git</td>
        <td>Git</td>
      </tr>
      <tr>
        <td>...</td>
        <td>...</td>
      </tr>
    </tbody>
  </table>
  <h3>🍵Developers :</h3>
  <p>Frontend Developer :
    <a href="https://github.com/AlirezaaMoradi">
      <b>Alireza Moradi</b>
    </a>
  </p>
  <p>Backend Developer : 
    <a href="https://github.com/AlirezaaMoradi">
      <b>Alireza Moradi</b>
    </a>
  </p>
</div>