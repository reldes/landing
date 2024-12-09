<template>
  <v-container>
    <h1>Installation Guide</h1>
    <ol>
      <li>
        <strong>Clone the API Repository:</strong>
        <pre><code>git clone git@github.com:reldes/client-api.git</code></pre>
      </li>
      <li>
        <strong>Navigate to the Repository:</strong>
        <pre><code>cd client-api</code></pre>
      </li>
      <li>
        <strong>Build the Docker Image:</strong>
        <pre><code>docker-compose build</code></pre>
      </li>
      <li>
        <strong>Run the Docker Container:</strong>
        <pre><code>docker-compose up</code></pre>
      </li>
      <li>
        <strong>Open a New Terminal:</strong>
      </li>
      <li>
        <strong>Find the Container ID:</strong>
        <pre><code>docker ps</code></pre>
        The container will be named <code>openlab-api</code>. Copy the container ID and run:
        <pre><code>docker exec -it container_id bash</code></pre>
      </li>
      <li>
        <strong>Copy the Environment File:</strong>
        <pre><code>cp .env.example .env</code></pre>
      </li>
      <li>
        <strong>Install Composer Dependencies:</strong>
        <pre><code>composer install</code></pre>
      </li>
      <li>
        <strong>Run Database Migrations:</strong>
        <pre><code>php artisan migrate</code></pre>
      </li>
      <li>
        <strong>Generate Application Key:</strong>
        <pre><code>php artisan key:generate</code></pre>
      </li>
      <li>
        <strong>Access the Application:</strong>
        Open your browser and navigate to <a href="http://localhost:8080" target="_blank">http://localhost:8080</a>
      </li>
    </ol>
  </v-container>
</template>

<script lang="ts">
export default {
  name: 'Install',
}
</script>