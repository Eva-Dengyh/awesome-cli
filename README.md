# awesome-cli

> 开发者 CLI 工具合集 · 专为 AI Agent 场景整理

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

收录企业协作、云服务、AI/LLM、文件处理、网络调试、容器与 K8s、IaC、安全扫描、开发效率等方向的高质量 CLI 工具（均为 GitHub 10k+ star 或官方出品），帮助开发者和 AI Agent 通过命令行完成各类工程任务。

## 目录

- [企业协作](#企业协作)
- [国际协作平台](#国际协作平台)
- [腾讯系](#腾讯系)
- [内容平台](#内容平台)
- [云服务](#云服务)
- [国际云服务](#国际云服务)
- [AI 工具](#ai-工具)
- [文件处理](#文件处理)
- [网络与 API](#网络与-api)
- [容器与 K8s](#容器与-k8s)
- [数据库](#数据库)
- [版本与包管理](#版本与包管理)
- [CI/CD](#cicd)
- [IaC 与安全](#iac-与安全)
- [开发效率](#开发效率)
- [Shell 增强](#shell-增强)

---

## 企业协作

| 产品 | 仓库 | 简介 |
|------|------|------|
| 飞书 | [open.feishu.cn](https://open.feishu.cn/document/tools-and-resources/development-tools/ide-with-commands) | 飞书官方 CLI，支持消息、日历、文档、AI Agent |
| 钉钉 | [DingTalk-Real-AI/dingtalk-workspace-cli](https://github.com/DingTalk-Real-AI/dingtalk-workspace-cli) | 钉钉官方开源 CLI，统一封装全套能力 |
| 企业微信 | [WecomTeam/wecom-cli](https://github.com/WecomTeam/wecom-cli) | 企业微信官方 CLI，内置 12 个 Skills |

## 国际协作平台

| 产品 | 仓库 | 简介 |
|------|------|------|
| GitHub CLI | [cli/cli](https://github.com/cli/cli) | GitHub 官方 CLI，管理 PR、issue、workflow |
| GitLab CLI | [gitlab-org/cli](https://github.com/gitlab-org/cli) | GitLab 官方 CLI，管理 MR、issue、pipeline |
| Jira CLI | [ankitpokhrel/jira-cli](https://github.com/ankitpokhrel/jira-cli) | Jira 终端 CLI，支持 issue 浏览与操作 |

## 腾讯系

| 产品 | 仓库 | 简介 |
|------|------|------|
| 微信开放 | [Tencent/openclaw-weixin](https://github.com/Tencent/openclaw-weixin) | 微信开放平台 CLI |
| 腾讯会议 | [TencentCloud/tencentmeeting-cli](https://github.com/TencentCloud/tencentmeeting-cli) | 会议创建、管理、录制自动化 |
| 腾讯云 | [cloud.tencent.com/product/cli](https://intl.cloud.tencent.com/products/cli) | 腾讯云全线产品管理 |
| 腾讯云开发 | [CloudBase CLI V3](https://cloud.tencent.com/developer/article/2654434) | 面向 Agent 设计的云开发 CLI |

## 内容平台

| 产品 | 仓库 | 简介 |
|------|------|------|
| 抖音小程序 | [抖音开放平台](https://developer.open-douyin.com/docs/resource/zh-CN/mini-app/develop/dev-tools/developer-instrument/development-assistance/ide-cli) | 小程序开发、上传、发布 |
| 小红书 | [jackwener/xhs-cli](https://github.com/jackwener/xhs-cli) | 小红书内容数据操作（社区） |
| B站 | [timerring/bilitool](https://github.com/timerring/bilitool) | 视频数据、弹幕处理（社区） |
| 网易云音乐 | [chaunsin/netease-cloud-music](https://github.com/chaunsin/netease-cloud-music) | 网易云音乐 CLI（社区） |

## 云服务

| 产品 | 仓库 | 简介 |
|------|------|------|
| 阿里云 | [aliyun/aliyun-cli](https://github.com/aliyun/aliyun-cli) | 阿里云官方 CLI |
| 华为云 | [KooCLI](https://support.huaweicloud.com/productdesc-hcli/hcli_01.html) | 华为云官方 CLI |
| 京东云 | [jdcloud-api/jdcloud-cli](https://github.com/jdcloud-api/jdcloud-cli) | 京东云官方 CLI |
| 火山引擎 | [volcengine/volcengine-cli](https://github.com/volcengine/volcengine-cli) | 字节火山引擎 CLI |
| 百度千帆 | [Kilo CLI](https://cloud.baidu.com/doc/qianfan/s/emmyn316m) | 百度千帆大模型平台 CLI |

## 国际云服务

| 产品 | 仓库 | 简介 |
|------|------|------|
| AWS CLI | [aws/aws-cli](https://github.com/aws/aws-cli) | AWS 官方 CLI，覆盖全部云服务 |
| Vercel CLI | [vercel/vercel](https://github.com/vercel/vercel) | 前端项目一键部署 CLI |

## AI 工具

| 产品 | 仓库 | 简介 |
|------|------|------|
| 火山引擎 veCLI | [veCLI](https://www.ithome.com/0/882/544.htm) | 字节豆包大模型终端 AI 工具 |
| 腾讯 AI CLI | [腾讯 AI CLI](https://news.qq.com/rain/a/20250815A0371G00) | 腾讯 CodeBuddy 配套 CLI |
| Ollama | [ollama/ollama](https://github.com/ollama/ollama) | 本地运行 LLM 的 CLI 工具，100k+ star |
| llm | [simonw/llm](https://github.com/simonw/llm) | 通用 LLM 命令行接口，支持多模型 |

## 文件处理

| 产品 | 仓库 | 简介 |
|------|------|------|
| ripgrep | [BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep) | 极速正则搜索，自动忽略 .gitignore（49k+） |
| fzf | [junegunn/fzf](https://github.com/junegunn/fzf) | 通用命令行模糊查找器（66k+） |
| bat | [sharkdp/bat](https://github.com/sharkdp/bat) | 带语法高亮的 cat 替代品（49k+） |
| fd | [sharkdp/fd](https://github.com/sharkdp/fd) | 简洁快速的 find 替代品（34k+） |
| jq | [jqlang/jq](https://github.com/jqlang/jq) | 轻量级命令行 JSON 处理器（30k+） |
| yq | [mikefarah/yq](https://github.com/mikefarah/yq) | 类 jq 的 YAML/JSON/XML 处理工具（12k+） |

## 网络与 API

| 产品 | 仓库 | 简介 |
|------|------|------|
| mitmproxy | [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy) | 交互式 HTTPS 代理与流量分析（37k+） |
| hurl | [Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl) | 用纯文本文件运行和测试 HTTP 请求（13k+） |
| grpcurl | [fullstorydev/grpcurl](https://github.com/fullstorydev/grpcurl) | 类 curl 的 gRPC 命令行工具（11k+） |

## 容器与 K8s

| 产品 | 仓库 | 简介 |
|------|------|------|
| dive | [wagoodman/dive](https://github.com/wagoodman/dive) | 探索 Docker 镜像层内容（47k+） |
| helm | [helm/helm](https://github.com/helm/helm) | Kubernetes 包管理器（27k+） |
| kubectx | [ahmetb/kubectx](https://github.com/ahmetb/kubectx) | 快速切换 K8s context 和 namespace（17k+） |

## 数据库

| 产品 | 仓库 | 简介 |
|------|------|------|
| pgcli | [dbcli/pgcli](https://github.com/dbcli/pgcli) | PostgreSQL 智能补全 CLI（12k+） |

## 版本与包管理

| 产品 | 仓库 | 简介 |
|------|------|------|
| nvm | [nvm-sh/nvm](https://github.com/nvm-sh/nvm) | Node.js 版本管理（80k+） |
| pyenv | [pyenv/pyenv](https://github.com/pyenv/pyenv) | Python 版本管理（40k+） |
| uv | [astral-sh/uv](https://github.com/astral-sh/uv) | 极速 Python 包管理器（30k+） |
| pnpm | [pnpm/pnpm](https://github.com/pnpm/pnpm) | 高效 Node 包管理器（30k+） |
| asdf | [asdf-vm/asdf](https://github.com/asdf-vm/asdf) | 多语言版本管理（22k+） |
| rbenv | [rbenv/rbenv](https://github.com/rbenv/rbenv) | Ruby 版本管理（16k+） |

## CI/CD

| 产品 | 仓库 | 简介 |
|------|------|------|
| act | [nektos/act](https://github.com/nektos/act) | 本地运行 GitHub Actions（56k+） |
| ArgoCD | [argoproj/argo-cd](https://github.com/argoproj/argo-cd) | GitOps 持续交付工具（18k+） |
| Dagger | [dagger/dagger](https://github.com/dagger/dagger) | 可编程 CI/CD 引擎（12k+） |
| Earthly | [earthly/earthly](https://github.com/earthly/earthly) | 容器化构建自动化（11k+） |

## IaC 与安全

| 产品 | 仓库 | 简介 |
|------|------|------|
| Terraform | [hashicorp/terraform](https://github.com/hashicorp/terraform) | 基础设施即代码（43k+） |
| OpenTofu | [opentofu/opentofu](https://github.com/opentofu/opentofu) | Terraform 开源分支（23k+） |
| Trivy | [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | 容器与代码安全扫描（24k+） |
| Gitleaks | [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) | 密钥泄露检测（18k+） |
| TruffleHog | [trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog) | 密钥扫描工具（17k+） |
| Infracost | [infracost/infracost](https://github.com/infracost/infracost) | 云成本估算 CLI（11k+） |

## 开发效率

| 产品 | 仓库 | 简介 |
|------|------|------|
| kubectl | [kubernetes/kubectl](https://github.com/kubernetes/kubectl) | Kubernetes 命令行工具（14k+） |
| just | [casey/just](https://github.com/casey/just) | 现代 make 替代，任务运行器（22k+） |
| hyperfine | [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) | 命令行基准测试工具（21k+） |
| navi | [denisidoro/navi](https://github.com/denisidoro/navi) | 交互式命令速查（15k+） |
| direnv | [direnv/direnv](https://github.com/direnv/direnv) | 目录级环境变量管理（13k+） |
| tldr | [tldr-pages/tldr](https://github.com/tldr-pages/tldr) | 简化版 man pages（52k+） |
| task | [go-task/task](https://github.com/go-task/task) | 简洁任务运行器（11k+） |

## Shell 增强

| 产品 | 仓库 | 简介 |
|------|------|------|
| zoxide | [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide) | 智能 cd 替代，学习常用目录（23k+） |
| delta | [dandavison/delta](https://github.com/dandavison/delta) | git diff 语法高亮（22k+） |
| atuin | [atuinsh/atuin](https://github.com/atuinsh/atuin) | shell 历史增强，支持同步搜索（22k+） |
| eza | [eza-community/eza](https://github.com/eza-community/eza) | 现代 ls 替代（13k+） |

---

## 贡献

欢迎提交 PR 补充更多工具，请确保：

- 工具可正常访问
- 附上官方链接或 GitHub 地址
- 一句话说明用途

提交前请先阅读 [贡献指南](CONTRIBUTING.md)。

## License

CC0
