<div id="repo-list"></div>

<script>
// Array of repository objects: { name: "Nazwa Repozytorium", link: "link_do_repo" }
const repositories = [
  { name: "Observer pattern", link: "https://github.com/KarolKucinski2001/Observer-pattern" },
  { name: "Command pattern", link: "https://github.com/KarolKucinski2001/Command-pattern" }
];

// Generate repository links dynamically
const repoList = document.getElementById("repo-list");
repositories.forEach(repo => {
  const repoLink = document.createElement("a");
  repoLink.href = repo.link;
  repoLink.textContent = repo.name;
  repoList.appendChild(repoLink);
  repoList.appendChild(document.createElement("br"));
});
</script>
