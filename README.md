<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0D1117,55:161B22,100:1F6FEB&amp;height=125&amp;section=header" alt="Profile header decoration">

  <a href="https://github.com/lasder-ca">
    <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+JP&amp;weight=700&amp;size=42&amp;duration=1600&amp;pause=1200&amp;color=F0F6FC&amp;center=true&amp;vCenter=true&amp;repeat=false&amp;width=760&amp;height=72&amp;lines=lasder-ca" alt="lasder-ca">
  </a>

  <p><strong>Security tools · AI agents · Systems</strong></p>
  <p>セキュリティ・AI・システム開発を学んでいる学生開発者です。</p>

  [![Website](https://img.shields.io/badge/lattee.jp-161B22?style=flat-square&logo=googlechrome&logoColor=58A6FF)](https://lattee.jp)
  [![X](https://img.shields.io/badge/@lattejp__-161B22?style=flat-square&logo=x&logoColor=F0F6FC)](https://x.com/lattejp_)
  [![Email](https://img.shields.io/badge/contact@lattee.jp-161B22?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:contact@lattee.jp)

  [![技術者倫理 遵守済み](https://img.shields.io/badge/%E6%8A%80%E8%A1%93%E8%80%85%E5%80%AB%E7%90%86-%E9%81%B5%E5%AE%88%E6%B8%88%E3%81%BF-0a0a0a?style=for-the-badge&labelColor=ffffff)](https://xn--zwqt06btym6jly7j.com)
</div>

## About

暗号化ツール、AI coding agentの評価基盤、最短経路探索アルゴリズムなどを開発しています。単に作るだけでなく、**失敗時の挙動、再現手順、検証結果、制約の明記**まで含めて設計することを重視しています。

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔐 <a href="https://github.com/latteworkspace/lvau">Lvau</a></h3>
      <p><em>Inspectable encrypted capsules for local files and developer workflows.</em></p>
      <p>CLI、ネイティブGUI、暗号ライブラリ、バージョン管理された <code>.lvau</code> 形式を含むRustワークスペースです。ストリーミング暗号化、改ざん検知、安全なファイル置換、署名、復旧共有などを扱います。</p>
      <p>
        <a href="https://github.com/latteworkspace/lvau/actions/workflows/ci.yml"><img src="https://github.com/latteworkspace/lvau/actions/workflows/ci.yml/badge.svg" alt="Lvau CI"></a>
        <a href="https://github.com/latteworkspace/lvau/releases"><img src="https://img.shields.io/github/v/release/latteworkspace/lvau?display_name=tag&amp;sort=semver&amp;style=flat-square" alt="Lvau release"></a>
        <a href="https://github.com/latteworkspace/lvau/blob/master/LICENSE"><img src="https://img.shields.io/github/license/latteworkspace/lvau?style=flat-square" alt="Lvau license"></a>
      </p>
      <sub>Experimental — not formally independently audited.</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/lasder-ca/PatchArena">PatchArena</a></h3>
      <p><em>Reproducible benchmarks for AI coding agents on real repositories.</em></p>
      <p>同じコミットとタスクから隔離Git worktreeを作り、agent実行、検証、Patch、ログ、監査記録を保存します。Codex CLI、Claude Code、Gemini CLIとカスタムadapterに対応しています。</p>
      <p>
        <a href="https://github.com/lasder-ca/PatchArena/actions/workflows/ci.yml"><img src="https://github.com/lasder-ca/PatchArena/actions/workflows/ci.yml/badge.svg" alt="PatchArena CI"></a>
        <a href="https://github.com/lasder-ca/PatchArena/releases"><img src="https://img.shields.io/github/v/release/lasder-ca/PatchArena?display_name=tag&amp;sort=semver&amp;style=flat-square" alt="PatchArena release"></a>
        <a href="https://github.com/lasder-ca/PatchArena/blob/main/LICENSE"><img src="https://img.shields.io/github/license/lasder-ca/PatchArena?style=flat-square" alt="PatchArena license"></a>
      </p>
      <sub>Evidence collection and orchestration — not an operating-system sandbox.</sub>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🧭 <a href="https://github.com/lasder-ca/aegis-acbs">Aegis ACBS</a></h3>
      <p><em>Exact bidirectional shortest-path search with a shared proof of optimality.</em></p>
      <p>前向き・逆向き探索が下界と上界を共有し、適応的schedulerが処理量を割り当てる道路グラフ研究CLIです。OSM・DIMACSのimport、経路探索、benchmark、tail分析、JSON・CSV・HTMLレポートに対応しています。</p>
      <p>公開済みの東京実験では、1つの記録済み条件下で <strong>10,000 / 10,000</strong> の最短経路距離がDijkstraと一致しました。</p>
      <p>
        <a href="https://github.com/lasder-ca/aegis-acbs/actions/workflows/ci.yml"><img src="https://github.com/lasder-ca/aegis-acbs/actions/workflows/ci.yml/badge.svg" alt="Aegis ACBS CI"></a>
        <a href="https://github.com/lasder-ca/aegis-acbs/releases"><img src="https://img.shields.io/github/v/release/lasder-ca/aegis-acbs?display_name=tag&amp;sort=semver&amp;style=flat-square" alt="Aegis ACBS release"></a>
        <a href="https://github.com/lasder-ca/aegis-acbs/blob/main/docs/TOKYO_EVIDENCE.md"><img src="https://img.shields.io/badge/evidence-Tokyo%20validation-7C3AED?style=flat-square" alt="Tokyo validation evidence"></a>
        <a href="https://github.com/lasder-ca/aegis-acbs/blob/main/LICENSE"><img src="https://img.shields.io/github/license/lasder-ca/aegis-acbs?style=flat-square" alt="Aegis ACBS license"></a>
      </p>
      <sub>Research prototype — novelty and broad performance generalization require independent review.</sub>
    </td>
  </tr>
</table>

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lasder-ca&amp;theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lasder-ca&amp;theme=github">
    <img width="100%" alt="GitHub profile activity summary" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lasder-ca&amp;theme=github">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=lasder-ca&amp;theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=lasder-ca&amp;theme=github">
    <img width="49%" alt="Most used languages in commits" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=lasder-ca&amp;theme=github">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=lasder-ca&amp;theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=lasder-ca&amp;theme=github">
    <img width="49%" alt="GitHub statistics" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=lasder-ca&amp;theme=github">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=lasder-ca&amp;theme=github-compact&amp;hide_border=true&amp;area=true&amp;days=60&amp;custom_title=Recent%20contribution%20activity">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=lasder-ca&amp;theme=github&amp;hide_border=true&amp;area=true&amp;days=60&amp;custom_title=Recent%20contribution%20activity">
    <img width="100%" alt="Recent GitHub contribution activity" src="https://github-readme-activity-graph.vercel.app/graph?username=lasder-ca&amp;theme=github&amp;hide_border=true&amp;area=true&amp;days=60&amp;custom_title=Recent%20contribution%20activity">
  </picture>
</p>

## Toolbox

<p align="center">
  <img src="https://img.shields.io/badge/-000000?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust" title="Rust">
  <img src="https://img.shields.io/badge/-00ADD8?style=for-the-badge&amp;logo=go&amp;logoColor=white" alt="Go" title="Go">
  <img src="https://img.shields.io/badge/-3178C6?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" title="TypeScript">
  <img src="https://img.shields.io/badge/-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=111827" alt="JavaScript" title="JavaScript">
  <img src="https://img.shields.io/badge/-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python" title="Python">
  <img src="https://img.shields.io/badge/-339933?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=white" alt="Node.js" title="Node.js">
  <img src="https://img.shields.io/badge/-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git" title="Git">
  <br>
  <img src="https://img.shields.io/badge/-2088FF?style=for-the-badge&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" title="GitHub Actions">
  <img src="https://img.shields.io/badge/-FCC624?style=for-the-badge&amp;logo=linux&amp;logoColor=111827" alt="Linux" title="Linux">
  <img src="https://img.shields.io/badge/-E95420?style=for-the-badge&amp;logo=ubuntu&amp;logoColor=white" alt="Ubuntu" title="Ubuntu">
  <img src="https://img.shields.io/badge/-4EAA25?style=for-the-badge&amp;logo=gnubash&amp;logoColor=white" alt="Bash" title="Bash">
  <img src="https://img.shields.io/badge/-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white" alt="Docker" title="Docker">
  <img src="https://img.shields.io/badge/-F38020?style=for-the-badge&amp;logo=cloudflare&amp;logoColor=white" alt="Cloudflare" title="Cloudflare">
  <img src="https://img.shields.io/badge/-000000?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Vercel" title="Vercel">
</p>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:1F6FEB,55:161B22,100:0D1117&amp;height=90&amp;section=footer" alt="Profile footer decoration">
</div>
