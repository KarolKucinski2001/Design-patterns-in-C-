## Other Repositories

<div id="repo-list"></div>


<script>
// List of repositories: { name: "Repository Name", link: "repository_link" }
const repositories = [
  { name: "Observer pattern", link: "https://github.com/KarolKucinski2001/Observer-pattern" },
  { name: "Command pattern", link: "https://github.com/KarolKucinski2001/Command-pattern" }
];

// Generate dynamic repository links
const repoList = document.getElementById("repo-list");
repositories.forEach(repo => {
  const repoLink = document.createElement("a");
  repoLink.href = repo.link;
  repoLink.textContent = repo.name;
  repoList.appendChild(repoLink);
  repoList.appendChild(document.createElement("br"));
});
</script>
