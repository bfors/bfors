### Welcome

I'm currently working on learning rust and low level data management through implementing simple storage engines.

<details>
<summary>Log-structured key-value store</summary>
https://github.com/bfors/lskv/

Based on bitcask, designed for high throughput and crash resilience.

All commands are written to a log file in the order they are received, and an in-memory index maps keys to the corresponding file locations where the values are found. Log files are append only, and periodically get compacted to drop stale data.
  
![lskv](https://github.com/bfors/lskv/blob/main/diagram.svg)
</details>

<details>
<summary>Log-structured merge tree</summary>
https://github.com/bfors/lsmt/

TODO

</details>

<details>
<summary>Hash ring</summary>

Implementation of consistent hashing

todo

</details>

<!--
**bfors/bfors** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
