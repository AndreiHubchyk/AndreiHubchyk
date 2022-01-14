### Hi there 👋
<!-- If you're using "main" as default branch -->
![Metrics](https://github.com/AndreiHubchyk/AndreiHubchyk/blob/main/github-metrics.svg)
<!--
**AndreiHubchyk/AndreiHubchyk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<table>
  <td align="center">
    <details open><summary>With icons</summary>
      <img src="https://github.com/lowlighter/lowlighter/blob/master/metrics.plugin.topics.icons.svg">
    </details>
    <details open><summary>With labels</summary>
      <img src="https://github.com/lowlighter/lowlighter/blob/master/metrics.plugin.topics.svg">
    </details>
    <img width="900" height="1" alt="">
  </td>
</table>

This uses puppeteer to navigate through your starred topics page.

#### ➡️ Available options

<!--options-->
| Option | Type *(format)* **[default]** *{allowed values}* | Description |
| ------ | -------------------------------- | ----------- |
| `plugin_topics` | `boolean` **[no]** | Display starred topics |
| `plugin_topics_mode` | `string` **[starred]** *{"starred", "icons", "mastered"}* | Plugin mode |
| `plugin_topics_sort` | `string` **[stars]** *{"stars", "activity", "starred", "random"}* | Sorting method of starred topics |
| `plugin_topics_limit` | `number` **[15]** *{0 ≤ 𝑥 ≤ 20}* | Maximum number of topics to display |


<!--/options-->

*[→ Full specification](metadata.yml)*

#### ℹ️ Examples workflows

<!--examples-->
```yaml
name: Labels
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.topics.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ''
  plugin_topics: 'yes'
  plugin_topics_limit: 12

```
```yaml
name: Icons
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.topics.icons.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ''
  plugin_topics: 'yes'
  plugin_topics_limit: 0
  plugin_topics_mode: icons

```
<!--/examples-->

<div align="center">
	<img alt="devtools" width="73px" src="https://user-images.githubusercontent.com/89486551/143319750-2f729405-4b8a-4f73-8e16-b5c7780517fc.png" />
	<img alt="dbeaver" width="73px" src="https://user-images.githubusercontent.com/89486551/143319757-0bbd31ce-7860-447a-9571-504653849d0b.png" />
	<img alt="PostgreSQL" width="73px" src="https://user-images.githubusercontent.com/89486551/143319773-17f2e07b-8dc2-4f02-9b60-e9f0b421ce06.png" />
	<img alt="Git" width="73px" src="https://user-images.githubusercontent.com/89486551/143319775-c711ac23-04f8-44dd-9a0b-ea3698467e9e.png" />
	<img alt="charles" width="73px" src="https://user-images.githubusercontent.com/89486551/143319787-e5eb9aa4-5b57-454f-b903-64282274af76.png" />
	<img alt="fiddler" width="73px" src="https://user-images.githubusercontent.com/89486551/143319792-72034e75-f2fe-4589-b741-6f21a2433a71.png" />
	<img alt="android-studio" width="73px" src="https://user-images.githubusercontent.com/89486551/143319797-01713acf-1cc6-49c9-ae92-d520d55cef17.png" />
	<img alt="postman" width="73px" src="https://user-images.githubusercontent.com/89486551/143319803-99550e9f-bdde-4354-b38a-a3aa8ffc9a77.png" />
	<img alt="pycharm" width="73px" src="https://user-images.githubusercontent.com/89486551/143319814-3645ca4a-c3cc-4958-aa5b-ff27b47d704c.png" />
</div>

