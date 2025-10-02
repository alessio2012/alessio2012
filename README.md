## Hi there 👋

**alessio2012/alessio2012** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

  ## Welcome to my profile!

### Latest pull requests

{{- range .PullRequests }}
* [#{{ .ID }} - {{ .Title }}]({{ .URL }}) on `{{ .ProjectOrg }}`
{{- end }}

### Latest blog posts

{{- range .Articles }}
* [{{ .Title }}]({{ .Link }}) *(published on {{ .GoDate | formatDate }})*
{{- end }}

### Latest starred repositories

{{- range .StarredRepos }}
* [{{ .Name }}]({{ .URL }}) (with {{ .Stars | humanizeBigNumber  }} stars)
{{- end }}
