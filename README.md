<p><strong>Author:</strong> Ralph Dainuel DS. Sadiarin</p>

<p><strong>Project Title:</strong> API Call</p>

<p><strong>Description:</strong> This project is a simple Laravel API practice application that demonstrates how API calls work using routes and controllers. It includes sample API endpoints for retrieving, inserting, updating and deleting student records from the database.</p>

<p><strong>Setup 101</strong></p>

<p>1. Clone or download this repository and open the project folder in VS Code.</p>

<p>2. Install Laravel Herd and the SQLite Viewer extension in VS Code for viewing the SQLite database.</p>

<p>3. Inside the project directory, run when its needed:</p>

<pre><code>composer install</code></pre>

<p>4. Copy the <code>.env.example</code> file and rename it to <code>.env</code>, then configure the database settings.</p>

<p>5. Generate the application key:</p>

<pre><code>php artisan key:generate</code></pre>

<p>6. Run the database migrations:</p>

<pre><code>php artisan migrate</code></pre>

<p>7. Start the Laravel development server:</p>

<pre><code>php artisan serve</code></pre>

<p>8. Open the following URL in your browser to display the student API data:</p>

<pre><code>http://127.0.0.1:8000/api/students</code></pre>

<p><strong>Testing with Postman</strong></p>

<p>Open Postman and create a new collection for this project.</p>

<p>Retrieve all student data:</p>

<pre><code>GET http://127.0.0.1:8000/api/students</code></pre>

<p>Retrieve a specific student record:</p>

<pre><code>GET http://127.0.0.1:8000/api/students/7</code></pre>

<p>Replace <code>7</code> with the desired student ID based on my video.</p>

<p><strong>Demo Tutorial</strong></p>

<p>
  Watch the demo tutorial here:
  <a href="https://drive.google.com/file/d/1g_iwxgq57QfguER1XRhIqfpLYoQ7Xmc7/view?usp=drivesdk" target="_blank">
    Demo Tutorial Video
  </a>
</p>

<p>The tutorial demonstrates how to test Laravel API endpoints using Postman.</p>
