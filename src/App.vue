<template>
  <div>
    <h1>{{ greeting }}</h1>
    <p>
      <b>Congratulations</b> on setting up your Vue project! To streamline your
      development process and enhance collaboration, consider integrating
      GitHub Actions into your workflow. 
    </p>

    <p>
      <strong>GitHub Actions</strong> allow you to automate tasks and workflows
      directly in your GitHub repository. Whether it's building, testing, or
      deploying your Vue application, GitHub Actions can help streamline these
      processes.
    </p>

    <p>
      To get started, create a <code>.github/workflows</code> directory in your
      repository and define your workflows using YAML files. Customize
      <a href="https://docs.github.com/en/actions" target="_blank">
        GitHub Actions documentation
      </a>
      .
    </p>

    <p>
      Customize the workflow to fit your project's needs. You can trigger actions
      on specific events, use different runners, and execute various commands.
    </p>

    <p>
      Happy coding and best of luck with your Vue project!
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      greeting: 'Welcome to Your Vue Project!',
    };
  },
};
</script>

<style scoped>
body {
  font-family: 'Arial', sans-serif;
  margin: 40px;
  text-align: center;
}

h1 {
  color: #2c3e50;
}

p {
  color: #34495e;
  font-size: 1.2em;
  line-height: 1.6em;
}

code {
  background-color: #ecf0f1;
  padding: 2px 4px;
  border-radius: 4px;
  font-family: 'Courier New', Courier, monospace;
}

a {
  color: #3498db;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
