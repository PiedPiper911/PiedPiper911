# Renliang Wu (吴仁亮) — Frontend Engineer · AI Direction

**Frontend / AI Engineer building production-grade AI Agent UIs, node-based workflows, and browser audio/video tooling.**

I focus on **agent workflow canvases, audio/video processing, SSR performance, and developer tooling**.  
用前端工程让 AI Agent 可交互、可观测、可落地，用设计让复杂工作流清晰、好用。

`TypeScript` · `React` · `Agent Workflow` · `Audio/Video` · `Developer Tools`

**Open to Frontend / AI Agent opportunities · 上海**

---

## Projects

### [dsh-workflow-canvas](https://github.com/PiedPiper911/dsh-workflow-canvas) — node-based AI workflow canvas
基于 React Flow (@xyflow/react) + Zustand + Vite 的 AI 工作流无限画布，支持节点编排、实时运行态与 Dify/Coze 风格交互，用于零代码搭建 Agent 流程。

### [dsh-video-tools](https://github.com/PiedPiper911/dsh-video-tools) — browser audio/video processing toolkit
基于 FFmpeg.wasm / WebAV / video.js 的浏览器端音视频处理工具，覆盖录制、剪辑、转码与帧级处理，把服务端视频能力搬到前端。

---

## Selected open-source contributions

| Repository | Contribution |
| --- | --- |
| [AgentScope #2468](https://github.com/agentscope-ai/agentscope/pull/2468) | `Merged` 修复 AgentScope 2.0 web_ui 前端在浏览器内置暗色模式下侧边栏按钮（Chat/Schedule/MCP Hub 等）不可见：定位为 `color-scheme: light dark` 声明但 `.dark` 变量从未被激活，接入 `prefers-color-scheme` 自动切换暗色 token |
| [Deer Flow #4865](https://github.com/bytedance/deer-flow/pull/4865) | `Merged` 修复非安全上下文（http://LAN-IP）下 artifact 预览/编辑失效（后端 ETag 下发真实 SHA-256，前端免 crypto.subtle 本地哈希），并按 review 优化大文件哈希性能 |
| [Mastra #19413](https://github.com/mastra-ai/mastra/pull/19413) | `Merged` 修复独立 Agent 执行后的内存泄漏（`stream()` 临时 Mastra 实例钩子未清理，模块级 emitter 持有引用导致堆线性增长） |
| [Cherry Studio #18436](https://github.com/CherryHQ/cherry-studio/pull/18436) | `Merged` 修复 Windows 平台 MCP 服务器工具加载失败（`npx.cmd` 跨平台解析失败，回退 bun 解析出错误包） |
| [0-AI-UG / cate #565](https://github.com/0-AI-UG/cate/pull/565) | `Merged` 修复映射网络驱动器在路径校验中的处理 |
| [pi #6847](https://github.com/earendil-works/pi/pull/6847) | `Merged` 补全 TypeScript Agent Harness 包 `@earendil-works/pi-coding-agent` 公共 API 缺失的 `ToolExecution*Event` 类型导出（此前仅从内部模块导出，`dist/index.d.ts` 无声明，扩展开发者无法 `import type`） |

[View all pull requests →](https://github.com/search?q=is%3Apr+author%3APiedPiper911&type=pullrequests)

---

## Toolbox

**Frontend** — React · TypeScript · Zustand · Tailwind CSS · Vite · Next.js(SSR) · @xyflow/react  
**Audio/Video** — FFmpeg.wasm · WebAV · video.js · Fabric.js · Web Worker · WebSocket/SSE  
**AI / Agent** — Mastra · MCP · RAG(ChromaDB) · Agent Runtime · Workflow Engine  
**Engineering** — Unit Test(Jasmine/Vitest) · Performance(LCP/Core Web Vitals) · Monorepo · CI

---

📮 [1162831964@qq.com](mailto:1162831964@qq.com)
