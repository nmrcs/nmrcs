**Fullstack Engineer · Software Architect**

Payments, credit risk analytics and LLM agents with the harness that tests them, built end to end in TypeScript and Python.

## Projects

- **[OpenMycel](https://openmycel.app)** — your own AI assistant, running on your iPhone and working with the apps you already use. No server, no sign-up email, even offline. In development; two parts are already open:
  - **[expo-llama](https://github.com/openmycel/expo-llama)** — run GGUF models on iPhone with llama.cpp, an Expo native module in Swift. The engine is compiled from a pinned tag; 171 of its 195 MB were debug symbols, the package ships 8.7 MB.
  - **[expo-rich-text](https://github.com/openmycel/expo-rich-text)** — a WYSIWYG markdown editor for Expo and React Native on Tiptap. The editor page loads nothing and reaches no network.
- **[mamir](https://github.com/nmrcs/mamir)** — a risk analytics engine: calibrated event scoring, portfolio money at risk, point-in-time backtest, scenario stress. 26.5M real loan-months; on the 2007 window calibration broke a full year before ROC-AUC noticed, and the portfolio loss came out 3.4× the prediction.
- **[cart-agent](https://github.com/nmrcs/cart-agent)** — a store chat assistant on a local Qwen 9B that builds a cart for the buyer's task. Code owns every price and total: 0 wrong totals against 3 in 6 conversations when the model builds the cart alone.
- **[support-agent](https://github.com/nmrcs/support-agent)** — a first-line support agent with a bench: the model skipped a required tool call in 1 turn of 24, measured instead of hidden.
- **[toastkit](https://github.com/nmrcs/toastkit)** — sonner-style toasts for vanilla JavaScript, published as `@mrcs/toastkit`. Zero dependencies, 2.7 KB JS + 2.0 KB CSS gzipped.

## Stack

- **Languages:** TypeScript, Python, SQL
- **Backend:** Node.js, NestJS, Prisma, PostgreSQL, Kafka, Zod, REST/OpenAPI, JWT, 2FA
- **AI:** LLM orchestration, RAG, embeddings, Qdrant, LangChain, CV/OCR inference (CLIP, PaddleOCR, torch)
- **Realtime:** WebSocket, SSE, streaming STT/TTS
- **Frontend:** React, Vite, Tailwind, HeroUI, Zustand, React Router, TanStack Query, Motion
- **Infra:** Docker, Kubernetes, ArgoCD/Kustomize, GitLab CI, Yandex Cloud, Prometheus, Sentry

## Links

- [mrcs.page](https://mrcs.page) — portfolio: projects and articles
- [Habr](https://habr.com/en/users/nmrcs/) — 217K views across 10 technical articles
