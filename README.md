<div align="center">

![Continue logo](media/readme.png)

</div>

<h1 align="center">Continue</h1>

<div align="center">

**[Continue](https://docs.continue.dev) is the leading open-source AI code assistant. You can connect any models and any context to build custom autocomplete and chat experiences inside [VS Code](https://marketplace.visualstudio.com/items?itemName=Continue.continue) and [JetBrains](https://plugins.jetbrains.com/plugin/22707-continue-extension)**

</div>

<div align="center">

<a target="_blank" href="https://opensource.org/licenses/Apache-2.0" style="background:none">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" style="height: 22px;" />
</a>
<a target="_blank" href="https://docs.continue.dev" style="background:none">
    <img src="https://img.shields.io/badge/continue_docs-%23BE1B55" style="height: 22px;" />
</a>
<a target="_blank" href="https://discord.gg/vapESyrFmJ" style="background:none">
    <img src="https://img.shields.io/badge/discord-join-continue.svg?labelColor=191937&color=6F6FF7&logo=discord" style="height: 22px;" />
</a>

<p></p>

## Chat

[Chat](https://continue.dev/docs/chat/how-to-use-it) makes it easy to ask for help from an LLM without needing to leave the IDE

![chat](docs/static/img/chat.gif)

## Autocomplete

[Autocomplete](https://continue.dev/docs/autocomplete/how-to-use-it) provides inline code suggestions as you type

![autocomplete](docs/static/img/autocomplete.gif)

## Edit

[Edit](https://continue.dev/docs/edit/how-to-use-it) is a convenient way to modify code without leaving your current file

![edit](docs/static/img/edit.gif)

## Actions

[Actions](https://continue.dev/docs/actions/how-to-use-it) are shortcuts for common use cases.

![actions](docs/static/img/actions.gif)

</div>

## Getting Started

Learn about how to install and use Continue in the docs [here](https://continue.dev/docs/getting-started/install)

## Contributing

Check out the [contribution ideas board](https://github.com/orgs/continuedev/projects/2), read the [contributing guide](https://github.com/continuedev/continue/blob/main/CONTRIBUTING.md), and join [#contribute on Discord](https://discord.gg/vapESyrFmJ)

## License

[Apache 2.0 © 2023 Continue Dev, Inc.](./LICENSE)

```
continuefork
├─ .changes
│  ├─ extensions
│  │  ├─ intellij
│  │  │  ├─ 0.0.34.md
│  │  │  ├─ 0.0.38.md
│  │  │  ├─ 0.0.42.md
│  │  │  ├─ 0.0.53.md
│  │  │  ├─ 0.0.54.md
│  │  │  ├─ v0.0.1.md
│  │  │  ├─ v0.0.19.md
│  │  │  ├─ v0.0.21.md
│  │  │  ├─ v0.0.25.md
│  │  │  └─ v0.0.26.md
│  │  └─ vscode
│  │     ├─ 0.8.14.md
│  │     ├─ 0.8.15.md
│  │     ├─ 0.8.24.md
│  │     ├─ 0.8.42.md
│  │     ├─ 0.8.43.md
│  │     ├─ 0.8.45.md
│  │     ├─ 0.8.46.md
│  │     ├─ 0.8.47.md
│  │     ├─ 0.8.48.md
│  │     ├─ 0.8.49.md
│  │     ├─ 0.8.50.md
│  │     ├─ 0.8.51.md
│  │     ├─ 0.8.52.md
│  │     ├─ v0.5.0.md
│  │     ├─ v0.6.0.md
│  │     ├─ v0.6.16.md
│  │     ├─ v0.6.19.md
│  │     ├─ v0.6.4.md
│  │     ├─ v0.8.1.md
│  │     └─ v0.8.2.md
│  ├─ header.tpl.md
│  └─ unreleased
│     └─ .gitkeep
├─ .changie.yaml
├─ .git
│  ├─ HEAD
│  ├─ config
│  ├─ description
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  ├─ sendemail-validate.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     └─ remotes
│  │        └─ origin
│  │           └─ HEAD
│  ├─ objects
│  │  ├─ info
│  │  └─ pack
│  │     ├─ pack-3ad7bf592d5d7749f6d75f4749bfbfd17219a69d.idx
│  │     ├─ pack-3ad7bf592d5d7749f6d75f4749bfbfd17219a69d.pack
│  │     └─ pack-3ad7bf592d5d7749f6d75f4749bfbfd17219a69d.rev
│  ├─ packed-refs
│  └─ refs
│     ├─ heads
│     │  └─ main
│     ├─ remotes
│     │  └─ origin
│     │     └─ HEAD
│     └─ tags
├─ .github
│  ├─ ISSUE_TEMPLATE
│  │  ├─ bug_report.yml
│  │  ├─ config.yml
│  │  └─ improvement_suggestion.yml
│  ├─ dependabot.yml
│  ├─ pull_request_template.md
│  └─ workflows
│     ├─ README.md
│     ├─ auto-assign.yaml
│     ├─ dev_pr.yaml
│     ├─ jetbrains-release.yaml
│     ├─ main.yaml
│     ├─ preview.yaml
│     └─ ts-check.yaml
├─ .gitignore
├─ .idea
│  ├─ .name
│  ├─ compiler.xml
│  ├─ gradle.xml
│  ├─ jarRepositories.xml
│  ├─ kotlinc.xml
│  ├─ misc.xml
│  └─ vcs.xml
├─ .nvmrc
├─ .prettierignore
├─ .prettierrc
├─ .vscode
│  ├─ launch.json
│  ├─ settings.json
│  └─ tasks.json
├─ CHANGELOG.md
├─ CODE_OF_CONDUCT.md
├─ CONTRIBUTING.md
├─ LICENSE
├─ README.md
├─ binary
│  ├─ .gitignore
│  ├─ README.md
│  ├─ build.js
│  ├─ importMetaUrl.js
│  ├─ jest.config.js
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ pkgJson
│  │  ├─ darwin-arm64
│  │  │  ├─ package-lock.json
│  │  │  └─ package.json
│  │  ├─ darwin-x64
│  │  │  ├─ package-lock.json
│  │  │  └─ package.json
│  │  ├─ linux-arm64
│  │  │  ├─ package-lock.json
│  │  │  └─ package.json
│  │  ├─ linux-x64
│  │  │  ├─ package-lock.json
│  │  │  └─ package.json
│  │  ├─ win32-arm64
│  │  │  ├─ package-lock.json
│  │  │  └─ package.json
│  │  └─ win32-x64
│  │     ├─ package-lock.json
│  │     └─ package.json
│  ├─ src
│  │  ├─ IpcIde.ts
│  │  ├─ IpcMessenger.ts
│  │  ├─ TcpMessenger.ts
│  │  ├─ index.ts
│  │  └─ logging.ts
│  ├─ test
│  └─ tsconfig.json
├─ core
│  ├─ .eslintrc.json
│  ├─ .gitignore
│  ├─ .npmignore
│  ├─ .vscode
│  │  └─ launch.json
│  ├─ autocomplete
│  │  ├─ ImportDefinitionsService.ts
│  │  ├─ NearbyDefinitionsService.ts
│  │  ├─ README.md
│  │  ├─ ast.ts
│  │  ├─ brackets.ts
│  │  ├─ cache.ts
│  │  ├─ charStream.ts
│  │  ├─ completionProvider.ts
│  │  ├─ constructPrompt.ts
│  │  ├─ filter.ts
│  │  ├─ languages.ts
│  │  ├─ lineStream.ts
│  │  ├─ postprocessing.ts
│  │  ├─ ranking.ts
│  │  ├─ recentlyEdited.ts
│  │  ├─ retrieval.ts
│  │  ├─ slidingWindow.ts
│  │  ├─ templates.ts
│  │  └─ util.ts
│  ├─ commands
│  │  ├─ index.ts
│  │  ├─ slash
│  │  │  ├─ cmd.ts
│  │  │  ├─ comment.ts
│  │  │  ├─ commit.ts
│  │  │  ├─ draftIssue.ts
│  │  │  ├─ edit.ts
│  │  │  ├─ http.ts
│  │  │  ├─ index.ts
│  │  │  ├─ onboard.ts
│  │  │  ├─ review.ts
│  │  │  ├─ share.ts
│  │  │  └─ stackOverflow.ts
│  │  └─ util.ts
│  ├─ config
│  │  ├─ ConfigHandler.ts
│  │  ├─ default.ts
│  │  ├─ load.ts
│  │  ├─ onboarding.ts
│  │  ├─ profile
│  │  │  ├─ ControlPlaneProfileLoader.ts
│  │  │  ├─ IProfileLoader.ts
│  │  │  ├─ LocalProfileLoader.ts
│  │  │  └─ doLoadConfig.ts
│  │  ├─ promptFile.ts
│  │  ├─ types.ts
│  │  └─ util.ts
│  ├─ context
│  │  ├─ index.ts
│  │  ├─ providers
│  │  │  ├─ CodeContextProvider.ts
│  │  │  ├─ CodeHighlightsContextProvider.ts
│  │  │  ├─ CodeOutlineContextProvider.ts
│  │  │  ├─ CodebaseContextProvider.ts
│  │  │  ├─ ContinueProxyContextProvider.ts
│  │  │  ├─ CurrentFileContextProvider.ts
│  │  │  ├─ CustomContextProvider.ts
│  │  │  ├─ DatabaseContextProvider.ts
│  │  │  ├─ DiffContextProvider.ts
│  │  │  ├─ DocsContextProvider.ts
│  │  │  ├─ FileContextProvider.ts
│  │  │  ├─ FileTreeContextProvider.ts
│  │  │  ├─ FolderContextProvider.ts
│  │  │  ├─ GitHubIssuesContextProvider.ts
│  │  │  ├─ GitLabMergeRequestContextProvider.ts
│  │  │  ├─ GoogleContextProvider.ts
│  │  │  ├─ HttpContextProvider.ts
│  │  │  ├─ JiraIssuesContextProvider
│  │  │  │  ├─ JiraClient.ts
│  │  │  │  └─ index.ts
│  │  │  ├─ LocalsProvider.ts
│  │  │  ├─ OSContextProvider.ts
│  │  │  ├─ OpenFilesContextProvider.ts
│  │  │  ├─ PostgresContextProvider.ts
│  │  │  ├─ ProblemsContextProvider.ts
│  │  │  ├─ RepoMapContextProvider.ts
│  │  │  ├─ SearchContextProvider.ts
│  │  │  ├─ TerminalContextProvider.ts
│  │  │  ├─ URLContextProvider.ts
│  │  │  ├─ context_provider_server.py
│  │  │  └─ index.ts
│  │  ├─ rerankers
│  │  │  ├─ ContinueProxyReranker.ts
│  │  │  ├─ cohere.ts
│  │  │  ├─ freeTrial.ts
│  │  │  ├─ index.ts
│  │  │  ├─ llm.ts
│  │  │  ├─ tei.ts
│  │  │  └─ voyage.ts
│  │  └─ retrieval
│  │     ├─ fullTextSearch.ts
│  │     ├─ pipelines
│  │     │  ├─ BaseRetrievalPipeline.ts
│  │     │  ├─ NoRerankerRetrievalPipeline.ts
│  │     │  └─ RerankerRetrievalPipeline.ts
│  │     ├─ recentlyEditedFilesCache.ts
│  │     ├─ repoMapRequest.ts
│  │     ├─ retrieval.ts
│  │     └─ util.ts
│  ├─ continueServer
│  │  ├─ interface.ts
│  │  └─ stubs
│  │     ├─ client.ts
│  │     └─ headers.ts
│  ├─ control-plane
│  │  ├─ TeamAnalytics.ts
│  │  ├─ analytics
│  │  │  ├─ ContinueProxyAnalyticsProvider.ts
│  │  │  ├─ IAnalyticsProvider.ts
│  │  │  ├─ LogStashAnalyticsProvider.ts
│  │  │  └─ PostHogAnalyticsProvider.ts
│  │  ├─ auth
│  │  │  └─ index.ts
│  │  ├─ client.ts
│  │  └─ schema.ts
│  ├─ core.ts
│  ├─ deploy
│  │  └─ constants.ts
│  ├─ diff
│  │  ├─ streamDiff.ts
│  │  ├─ test-examples
│  │  │  ├─ README.md
│  │  │  ├─ add-comments.diff
│  │  │  ├─ fastapi-tabs-vs-spaces.diff
│  │  │  ├─ fastapi.diff
│  │  │  └─ mock-llm.diff
│  │  └─ util.ts
│  ├─ index.d.ts
│  ├─ indexing
│  │  ├─ CodeSnippetsIndex.ts
│  │  ├─ CodebaseIndexer.ts
│  │  ├─ FullTextSearchCodebaseIndex.ts
│  │  ├─ LanceDbIndex.ts
│  │  ├─ README.md
│  │  ├─ TestCodebaseIndex.ts
│  │  ├─ chunk
│  │  │  ├─ ChunkCodebaseIndex.ts
│  │  │  ├─ basic.ts
│  │  │  ├─ chunk.ts
│  │  │  ├─ code.ts
│  │  │  └─ markdown.ts
│  │  ├─ docs
│  │  │  ├─ DocsCrawler.skip.ts
│  │  │  ├─ DocsCrawler.ts
│  │  │  ├─ DocsService.ts
│  │  │  ├─ article.ts
│  │  │  ├─ migrations.ts
│  │  │  ├─ preIndexed.ts
│  │  │  └─ preIndexedDocs.ts
│  │  ├─ embeddings
│  │  │  ├─ BaseEmbeddingsProvider.ts
│  │  │  ├─ BedrockEmbeddingsProvider.ts
│  │  │  ├─ CohereEmbeddingsProvider.ts
│  │  │  ├─ ContinueProxyEmbeddingsProvider.ts
│  │  │  ├─ DeepInfraEmbeddingsProvider.ts
│  │  │  ├─ FreeTrialEmbeddingsProvider.ts
│  │  │  ├─ GeminiEmbeddingsProvider.ts
│  │  │  ├─ HuggingFaceTEIEmbeddingsProvider.ts
│  │  │  ├─ MistralEmbeddingsProvider.ts
│  │  │  ├─ NvidiaEmbeddingsProvider.ts
│  │  │  ├─ OllamaEmbeddingsProvider.ts
│  │  │  ├─ OpenAIEmbeddingsProvider.ts
│  │  │  ├─ TransformersJsEmbeddingsProvider.ts
│  │  │  ├─ TransformersJsWorkerThread.js
│  │  │  ├─ VoyageEmbeddingsProvider.ts
│  │  │  └─ index.ts
│  │  ├─ ignore.ts
│  │  ├─ refreshIndex.ts
│  │  ├─ types.ts
│  │  └─ walkDir.ts
│  ├─ jest.config.js
│  ├─ jest.global-setup.ts
│  ├─ jest.setup-after-env.ts
│  ├─ llm
│  │  ├─ asyncEncoder.ts
│  │  ├─ autodetect.ts
│  │  ├─ constants.ts
│  │  ├─ constructMessages.ts
│  │  ├─ countTokens.ts
│  │  ├─ images.ts
│  │  ├─ index.ts
│  │  ├─ llamaTokenizer.d.ts
│  │  ├─ llamaTokenizer.js
│  │  ├─ llamaTokenizer.mjs
│  │  ├─ llamaTokenizerWorkerPool.mjs
│  │  ├─ llms
│  │  │  ├─ Anthropic.ts
│  │  │  ├─ Azure.ts
│  │  │  ├─ Bedrock.ts
│  │  │  ├─ BedrockImport.ts
│  │  │  ├─ Cloudflare.ts
│  │  │  ├─ Cohere.ts
│  │  │  ├─ CustomLLM.ts
│  │  │  ├─ DeepInfra.ts
│  │  │  ├─ Deepseek.ts
│  │  │  ├─ Fireworks.ts
│  │  │  ├─ Flowise.ts
│  │  │  ├─ FreeTrial.ts
│  │  │  ├─ Gemini.ts
│  │  │  ├─ Groq.ts
│  │  │  ├─ HuggingFaceInferenceAPI.ts
│  │  │  ├─ HuggingFaceTGI.ts
│  │  │  ├─ Kindo.ts
│  │  │  ├─ LMStudio.ts
│  │  │  ├─ LlamaCpp.ts
│  │  │  ├─ Llamafile.ts
│  │  │  ├─ Mistral.ts
│  │  │  ├─ Mock.ts
│  │  │  ├─ Msty.ts
│  │  │  ├─ Nvidia.ts
│  │  │  ├─ Ollama.ts
│  │  │  ├─ OpenAI.ts
│  │  │  ├─ OpenRouter.ts
│  │  │  ├─ Replicate.ts
│  │  │  ├─ SageMaker.ts
│  │  │  ├─ SambaNova.ts
│  │  │  ├─ TextGenWebUI.ts
│  │  │  ├─ Together.ts
│  │  │  ├─ Vllm.ts
│  │  │  ├─ WatsonX.ts
│  │  │  ├─ index.ts
│  │  │  └─ stubs
│  │  │     └─ ContinueProxy.ts
│  │  ├─ stream.ts
│  │  ├─ templates
│  │  │  ├─ chat.ts
│  │  │  ├─ edit.ts
│  │  │  └─ options.ts
│  │  └─ tiktokenWorkerPool.mjs
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ promptFiles
│  │  ├─ createNewPromptFile.ts
│  │  ├─ getContextProviderHelpers.ts
│  │  ├─ getPromptFiles.ts
│  │  ├─ handlebarUtils.ts
│  │  ├─ index.ts
│  │  ├─ renderTemplatedString.ts
│  │  ├─ slashCommandFromPromptFile.ts
│  │  └─ updateChatHistory.ts
│  ├─ protocol
│  │  ├─ core.ts
│  │  ├─ coreWebview.ts
│  │  ├─ ide.ts
│  │  ├─ ideCore.ts
│  │  ├─ ideWebview.ts
│  │  ├─ index.ts
│  │  ├─ passThrough.ts
│  │  ├─ util.ts
│  │  └─ webview.ts
│  ├─ tag-qry
│  │  ├─ tree-sitter-c-tags.scm
│  │  ├─ tree-sitter-c_sharp-tags.scm
│  │  ├─ tree-sitter-cpp-tags.scm
│  │  ├─ tree-sitter-elisp-tags.scm
│  │  ├─ tree-sitter-elixir-tags.scm
│  │  ├─ tree-sitter-elm-tags.scm
│  │  ├─ tree-sitter-go-tags.scm
│  │  ├─ tree-sitter-java-tags.scm
│  │  ├─ tree-sitter-javascript-tags.scm
│  │  ├─ tree-sitter-ocaml-tags.scm
│  │  ├─ tree-sitter-php-tags.scm
│  │  ├─ tree-sitter-python-tags.scm
│  │  ├─ tree-sitter-ql-tags.scm
│  │  ├─ tree-sitter-ruby-tags.scm
│  │  ├─ tree-sitter-rust-tags.scm
│  │  └─ tree-sitter-typescript-tags.scm
│  ├─ test
│  │  ├─ .gitignore
│  │  ├─ context
│  │  │  └─ providers
│  │  │     └─ index.skip.ts
│  │  ├─ editme.py
│  │  └─ util
│  │     ├─ fixtures.ts
│  │     ├─ indexing.ts
│  │     └─ testDir.ts
│  ├─ tsconfig.json
│  ├─ tsconfig.npm.json
│  ├─ util
│  │  ├─ GlobalContext.ts
│  │  ├─ LruCache.ts
│  │  ├─ ca.ts
│  │  ├─ devdata.ts
│  │  ├─ devdataSqlite.ts
│  │  ├─ extractMinimalStackTraceInfo.ts
│  │  ├─ fetchWithOptions.ts
│  │  ├─ filesystem.ts
│  │  ├─ history.ts
│  │  ├─ ideUtils.ts
│  │  ├─ index.ts
│  │  ├─ lcs.ts
│  │  ├─ merge.ts
│  │  ├─ messageIde.ts
│  │  ├─ messenger.ts
│  │  ├─ parameters.ts
│  │  ├─ paths.ts
│  │  ├─ posthog.ts
│  │  ├─ ranges.ts
│  │  ├─ repoMap.ts
│  │  ├─ reverseMessageIde.ts
│  │  ├─ treeSitter.ts
│  │  ├─ tts.ts
│  │  ├─ verticalEdit.ts
│  │  └─ withExponentialBackoff.ts
│  └─ vendor
│     ├─ .gitignore
│     ├─ README.md
│     ├─ modules
│     │  ├─ .package-lock.json
│     │  └─ @xenova
│     │     └─ transformers
│     │        ├─ LICENSE
│     │        ├─ README.md
│     │        ├─ package-lock.json
│     │        ├─ package.json
│     │        ├─ src
│     │        │  ├─ backends
│     │        │  │  └─ onnx.js
│     │        │  ├─ configs.js
│     │        │  ├─ env.js
│     │        │  ├─ models.js
│     │        │  ├─ pipelines.js
│     │        │  ├─ processors.js
│     │        │  ├─ tokenizers.js
│     │        │  ├─ transformers.js
│     │        │  └─ utils
│     │        │     ├─ audio.js
│     │        │     ├─ core.js
│     │        │     ├─ data-structures.js
│     │        │     ├─ generation.js
│     │        │     ├─ hub.js
│     │        │     ├─ image.js
│     │        │     ├─ maths.js
│     │        │     └─ tensor.js
│     │        └─ types
│     │           ├─ backends
│     │           │  ├─ onnx.d.ts
│     │           │  └─ onnx.d.ts.map
│     │           ├─ configs.d.ts
│     │           ├─ configs.d.ts.map
│     │           ├─ env.d.ts
│     │           ├─ env.d.ts.map
│     │           ├─ models.d.ts
│     │           ├─ models.d.ts.map
│     │           ├─ pipelines.d.ts
│     │           ├─ pipelines.d.ts.map
│     │           ├─ processors.d.ts
│     │           ├─ processors.d.ts.map
│     │           ├─ tokenizers.d.ts
│     │           ├─ tokenizers.d.ts.map
│     │           ├─ transformers.d.ts
│     │           ├─ transformers.d.ts.map
│     │           └─ utils
│     │              ├─ audio.d.ts
│     │              ├─ audio.d.ts.map
│     │              ├─ core.d.ts
│     │              ├─ core.d.ts.map
│     │              ├─ data-structures.d.ts
│     │              ├─ data-structures.d.ts.map
│     │              ├─ generation.d.ts
│     │              ├─ generation.d.ts.map
│     │              ├─ hub.d.ts
│     │              ├─ hub.d.ts.map
│     │              ├─ image.d.ts
│     │              ├─ image.d.ts.map
│     │              ├─ maths.d.ts
│     │              ├─ maths.d.ts.map
│     │              ├─ tensor.d.ts
│     │              └─ tensor.d.ts.map
│     ├─ package-lock.json
│     ├─ package.json
│     └─ tree-sitter.wasm
├─ docs
│  ├─ .gitignore
│  ├─ CHANGELOG.md
│  ├─ README.md
│  ├─ babel.config.js
│  ├─ docs
│  │  ├─ actions
│  │  │  ├─ context-selection.md
│  │  │  ├─ how-it-works.md
│  │  │  ├─ how-to-customize.md
│  │  │  ├─ how-to-use-it.md
│  │  │  └─ model-setup.md
│  │  ├─ autocomplete
│  │  │  ├─ context-selection.md
│  │  │  ├─ how-it-works.md
│  │  │  ├─ how-to-customize.md
│  │  │  ├─ how-to-use-it.md
│  │  │  └─ model-setup.md
│  │  ├─ chat
│  │  │  ├─ context-selection.md
│  │  │  ├─ how-it-works.md
│  │  │  ├─ how-to-customize.md
│  │  │  ├─ how-to-use-it.md
│  │  │  └─ model-setup.mdx
│  │  ├─ customize
│  │  │  ├─ changelog.mdx
│  │  │  ├─ config.mdx
│  │  │  ├─ context-providers.md
│  │  │  ├─ deep-dives
│  │  │  │  ├─ autocomplete.md
│  │  │  │  ├─ codebase.md
│  │  │  │  ├─ docs.md
│  │  │  │  └─ prompt-files.md
│  │  │  ├─ development-data.md
│  │  │  ├─ model-providers
│  │  │  │  ├─ assets
│  │  │  │  │  └─ watsonx2.gif
│  │  │  │  ├─ more
│  │  │  │  │  ├─ SambaNova.md
│  │  │  │  │  ├─ cloudflare.md
│  │  │  │  │  ├─ cohere.md
│  │  │  │  │  ├─ deepinfra.md
│  │  │  │  │  ├─ flowise.md
│  │  │  │  │  ├─ free-trial.md
│  │  │  │  │  ├─ groq.md
│  │  │  │  │  ├─ huggingfaceinferenceapi.md
│  │  │  │  │  ├─ ipex_llm.md
│  │  │  │  │  ├─ kindo.md
│  │  │  │  │  ├─ llamacpp.md
│  │  │  │  │  ├─ llamafile.md
│  │  │  │  │  ├─ lmstudio.md
│  │  │  │  │  ├─ msty.md
│  │  │  │  │  ├─ openrouter.md
│  │  │  │  │  ├─ replicatellm.md
│  │  │  │  │  ├─ sagemaker.md
│  │  │  │  │  ├─ textgenwebui.md
│  │  │  │  │  ├─ together.md
│  │  │  │  │  ├─ vllm.md
│  │  │  │  │  └─ watsonx.md
│  │  │  │  └─ top-level
│  │  │  │     ├─ anthropic.md
│  │  │  │     ├─ azure.md
│  │  │  │     ├─ bedrock.md
│  │  │  │     ├─ deepseek.md
│  │  │  │     ├─ gemini.md
│  │  │  │     ├─ mistral.md
│  │  │  │     ├─ ollama.md
│  │  │  │     └─ openai.md
│  │  │  ├─ model-types
│  │  │  │  ├─ autocomplete.md
│  │  │  │  ├─ chat.md
│  │  │  │  ├─ embeddings.md
│  │  │  │  └─ reranking.md
│  │  │  ├─ overview.md
│  │  │  ├─ slash-commands.md
│  │  │  └─ tutorials
│  │  │     ├─ build-your-own-context-provider.md
│  │  │     ├─ build-your-own-slash-command.md
│  │  │     ├─ custom-code-rag.md
│  │  │     ├─ how-to-self-host-a-model.md
│  │  │     ├─ llama3.1.md
│  │  │     ├─ running-continue-without-internet.md
│  │  │     └─ set-up-codestral.md
│  │  ├─ edit
│  │  │  ├─ context-selection.md
│  │  │  ├─ how-it-works.md
│  │  │  ├─ how-to-customize.md
│  │  │  ├─ how-to-use-it.md
│  │  │  └─ model-setup.md
│  │  ├─ getting-started
│  │  │  ├─ install.md
│  │  │  └─ overview.mdx
│  │  ├─ introduction.md
│  │  ├─ telemetry.md
│  │  └─ troubleshooting.md
│  ├─ docusaurus.config.js
│  ├─ netlify.toml
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ sidebars.js
│  ├─ src
│  │  ├─ css
│  │  │  └─ custom.css
│  │  └─ theme
│  │     └─ NotFound
│  │        └─ Content
│  │           └─ index.js
│  └─ static
│     ├─ .nojekyll
│     ├─ img
│     │  ├─ actions.gif
│     │  ├─ ask-continue.png
│     │  ├─ autocomplete.gif
│     │  ├─ chat.gif
│     │  ├─ classes.gif
│     │  ├─ codebase.gif
│     │  ├─ codespaces-install.png
│     │  ├─ context-menu.png
│     │  ├─ context-provider-example.png
│     │  ├─ continue-screenshot.png
│     │  ├─ continue-screenshot2.png
│     │  ├─ continue-social-card.png
│     │  ├─ docs.gif
│     │  ├─ edit.gif
│     │  ├─ error.gif
│     │  ├─ favicon.ico
│     │  ├─ intro.png
│     │  ├─ jetbrains-getting-started.png
│     │  ├─ jetbrains-quickstart.png
│     │  ├─ logo.png
│     │  ├─ mistral-x-continue.png
│     │  ├─ move-to-right-sidebar.gif
│     │  ├─ move-to-right-sidebar.png
│     │  ├─ prerelease.png
│     │  ├─ quick-actions-demo.gif
│     │  ├─ quick-actions.png
│     │  └─ slash-commands.png
│     └─ schemas
│        └─ config.json
├─ eval
│  └─ .gitignore
├─ extensions
│  ├─ intellij
│  │  ├─ .gitignore
│  │  ├─ .gradle
│  │  │  ├─ 8.3
│  │  │  │  ├─ checksums
│  │  │  │  │  ├─ checksums.lock
│  │  │  │  │  ├─ md5-checksums.bin
│  │  │  │  │  └─ sha1-checksums.bin
│  │  │  │  ├─ dependencies-accessors
│  │  │  │  │  ├─ 5ff144de810dd952e050983bda2040fa7aa351f8
│  │  │  │  │  │  ├─ classes
│  │  │  │  │  │  │  └─ org
│  │  │  │  │  │  │     └─ gradle
│  │  │  │  │  │  │        └─ accessors
│  │  │  │  │  │  │           └─ dm
│  │  │  │  │  │  │              ├─ LibrariesForLibs$BundleAccessors.class
│  │  │  │  │  │  │              ├─ LibrariesForLibs$PluginAccessors.class
│  │  │  │  │  │  │              ├─ LibrariesForLibs$VersionAccessors.class
│  │  │  │  │  │  │              ├─ LibrariesForLibs.class
│  │  │  │  │  │  │              ├─ LibrariesForLibsInPluginsBlock$BundleAccessors.class
│  │  │  │  │  │  │              ├─ LibrariesForLibsInPluginsBlock$PluginAccessors.class
│  │  │  │  │  │  │              ├─ LibrariesForLibsInPluginsBlock$VersionAccessors.class
│  │  │  │  │  │  │              └─ LibrariesForLibsInPluginsBlock.class
│  │  │  │  │  │  └─ sources
│  │  │  │  │  │     └─ org
│  │  │  │  │  │        └─ gradle
│  │  │  │  │  │           └─ accessors
│  │  │  │  │  │              └─ dm
│  │  │  │  │  │                 ├─ LibrariesForLibs.java
│  │  │  │  │  │                 └─ LibrariesForLibsInPluginsBlock.java
│  │  │  │  │  ├─ dependencies-accessors.lock
│  │  │  │  │  ├─ executionHistory.bin
│  │  │  │  │  └─ gc.properties
│  │  │  │  ├─ fileChanges
│  │  │  │  │  └─ last-build.bin
│  │  │  │  ├─ fileHashes
│  │  │  │  │  ├─ fileHashes.bin
│  │  │  │  │  ├─ fileHashes.lock
│  │  │  │  │  └─ resourceHashesCache.bin
│  │  │  │  ├─ gc.properties
│  │  │  │  └─ vcsMetadata
│  │  │  ├─ buildOutputCleanup
│  │  │  │  ├─ buildOutputCleanup.lock
│  │  │  │  ├─ cache.properties
│  │  │  │  └─ outputFiles.bin
│  │  │  ├─ file-system.probe
│  │  │  └─ vcs-1
│  │  │     └─ gc.properties
│  │  ├─ .idea
│  │  │  ├─ .name
│  │  │  ├─ compiler.xml
│  │  │  ├─ gradle.xml
│  │  │  ├─ jarRepositories.xml
│  │  │  ├─ kotlinc.xml
│  │  │  ├─ misc.xml
│  │  │  └─ vcs.xml
│  │  ├─ .run
│  │  │  ├─ Run IDE for UI Tests.run.xml
│  │  │  ├─ Run Plugin.run.xml
│  │  │  ├─ Run Qodana.run.xml
│  │  │  ├─ Run Tests.run.xml
│  │  │  └─ Run Verifications.run.xml
│  │  ├─ CHANGELOG.md
│  │  ├─ README.md
│  │  ├─ build.gradle.kts
│  │  ├─ gradle
│  │  │  ├─ libs.versions.toml
│  │  │  └─ wrapper
│  │  │     ├─ gradle-wrapper.jar
│  │  │     └─ gradle-wrapper.properties
│  │  ├─ gradle.properties
│  │  ├─ gradlew
│  │  ├─ gradlew.bat
│  │  ├─ qodana.yml
│  │  ├─ settings.gradle.kts
│  │  └─ src
│  │     ├─ main
│  │     │  ├─ kotlin
│  │     │  │  └─ com
│  │     │  │     └─ github
│  │     │  │        └─ continuedev
│  │     │  │           └─ continueintellijextension
│  │     │  │              ├─ MyBundle.kt
│  │     │  │              ├─ actions
│  │     │  │              │  └─ ContinuePluginActions.kt
│  │     │  │              ├─ activities
│  │     │  │              │  └─ ContinuePluginStartupActivity.kt
│  │     │  │              ├─ auth
│  │     │  │              │  ├─ AuthListener.kt
│  │     │  │              │  ├─ ContinueAuthDialog.kt
│  │     │  │              │  └─ ContinueAuthService.kt
│  │     │  │              ├─ autocomplete
│  │     │  │              │  ├─ AcceptAutocompleteAction.kt
│  │     │  │              │  ├─ AutocompleteActionGroup.kt
│  │     │  │              │  ├─ AutocompleteEditorListener.kt
│  │     │  │              │  ├─ AutocompleteLookupListener.kt
│  │     │  │              │  ├─ AutocompleteService.kt
│  │     │  │              │  ├─ AutocompleteSpinnerWidgetFactory.kt
│  │     │  │              │  ├─ CancelAutocompleteAction.kt
│  │     │  │              │  ├─ ContinueCustomElementRenderer.kt
│  │     │  │              │  ├─ ContinueMultilineCustomElementRenderer.kt
│  │     │  │              │  ├─ DisableTabAutocompleteAction.kt
│  │     │  │              │  ├─ EnableTabAutocompleteAction.kt
│  │     │  │              │  └─ PartialAcceptAutocompleteAction.kt
│  │     │  │              ├─ constants
│  │     │  │              │  └─ ServerConstants.kt
│  │     │  │              ├─ continue
│  │     │  │              │  ├─ ConfigJsonSchemaProviderFactory.kt
│  │     │  │              │  ├─ CoreMessenger.kt
│  │     │  │              │  ├─ CoreMessengerManager.kt
│  │     │  │              │  ├─ Diffs.kt
│  │     │  │              │  ├─ GetTheme.kt
│  │     │  │              │  ├─ HistoryManager.kt
│  │     │  │              │  ├─ IdeProtocolClient.kt
│  │     │  │              │  ├─ InlineBoxPresentation.kt
│  │     │  │              │  ├─ InputBoxCodeVision.kt
│  │     │  │              │  ├─ InputBoxInlay.kt
│  │     │  │              │  └─ Proxy.kt
│  │     │  │              ├─ editor
│  │     │  │              │  ├─ ContinueEditorLinePainter.kt
│  │     │  │              │  ├─ DiffStreamHandler.kt
│  │     │  │              │  ├─ DiffStreamService.kt
│  │     │  │              │  ├─ EditorComponentInlaysManager.kt
│  │     │  │              │  ├─ InlineEditAction.kt
│  │     │  │              │  ├─ ToggleInlineEditAction.kt
│  │     │  │              │  └─ ToolTipComponent.kt
│  │     │  │              ├─ factories
│  │     │  │              │  └─ CustomhandlerFactory.kt
│  │     │  │              ├─ listeners
│  │     │  │              │  └─ ContinuePluginSelectionListener.kt
│  │     │  │              ├─ services
│  │     │  │              │  ├─ ContinueExtensionSettingsService.kt
│  │     │  │              │  ├─ ContinuePluginService.kt
│  │     │  │              │  ├─ TelemetryService.kt
│  │     │  │              │  └─ TerminalActivityTrackingService.kt
│  │     │  │              ├─ toolWindow
│  │     │  │              │  ├─ ContinueBrowser.kt
│  │     │  │              │  ├─ ContinuePluginToolWindowFactory.kt
│  │     │  │              │  └─ MessageTypes.kt
│  │     │  │              └─ utils
│  │     │  │                 ├─ Debouncer.kt
│  │     │  │                 ├─ DispatchEventToWebView.kt
│  │     │  │                 └─ Utils.kt
│  │     │  └─ resources
│  │     │     ├─ META-INF
│  │     │     │  └─ plugin.xml
│  │     │     ├─ config_schema.json
│  │     │     ├─ continue_code
│  │     │     │  └─ copiedCode.txt
│  │     │     ├─ continue_tutorial.py
│  │     │     ├─ icons
│  │     │     │  └─ continue.svg
│  │     │     ├─ messages
│  │     │     │  └─ MyBundle.properties
│  │     │     ├─ tool-window-icon.svg
│  │     │     ├─ tool-window-icon_dark.svg
│  │     │     └─ webview
│  │     │        ├─ index.html
│  │     │        └─ logos
│  │     │           ├─ anthropic.png
│  │     │           ├─ google-palm.png
│  │     │           ├─ hf.png
│  │     │           ├─ llamacpp.png
│  │     │           ├─ lmstudio.png
│  │     │           ├─ meta.png
│  │     │           ├─ mistral.png
│  │     │           ├─ ollama.png
│  │     │           ├─ openai.png
│  │     │           ├─ replicate.png
│  │     │           ├─ together.png
│  │     │           └─ wizardlm.png
│  │     └─ test
│  │        ├─ kotlin
│  │        │  └─ com
│  │        │     └─ github
│  │        │        └─ continuedev
│  │        │           └─ continueintellijextension
│  │        │              └─ MyPluginTest.kt
│  │        └─ testData
│  │           └─ rename
│  │              ├─ foo.xml
│  │              └─ foo_after.xml
│  └─ vscode
│     ├─ .eslintrc.json
│     ├─ .gitignore
│     ├─ .npmrc
│     ├─ .vscodeignore
│     ├─ CHANGELOG.md
│     ├─ CONTRIBUTING.md
│     ├─ LICENSE.txt
│     ├─ README.md
│     ├─ builtin-themes
│     │  ├─ dark_modern.json
│     │  ├─ dark_plus.json
│     │  ├─ dark_vs.json
│     │  ├─ hc_black.json
│     │  ├─ hc_light.json
│     │  ├─ light_modern.json
│     │  ├─ light_plus.json
│     │  └─ light_vs.json
│     ├─ config_schema.json
│     ├─ continue_rc_schema.json
│     ├─ continue_tutorial.py
│     ├─ gui
│     │  ├─ continue-dev-square.png
│     │  ├─ continue.gif
│     │  ├─ index.html
│     │  ├─ logos
│     │  │  ├─ anthropic.png
│     │  │  ├─ google-palm.png
│     │  │  ├─ hf.png
│     │  │  ├─ llamacpp.png
│     │  │  ├─ lmstudio.png
│     │  │  ├─ meta.png
│     │  │  ├─ mistral.png
│     │  │  ├─ ollama.png
│     │  │  ├─ openai.png
│     │  │  ├─ replicate.png
│     │  │  ├─ together.png
│     │  │  └─ wizardlm.png
│     │  ├─ onigasm.wasm
│     │  └─ play_button.png
│     ├─ media
│     │  ├─ above-line-edit.gif
│     │  ├─ autocomplete.gif
│     │  ├─ edit.png
│     │  ├─ explain.png
│     │  ├─ generate.png
│     │  ├─ icon.png
│     │  ├─ image.gif
│     │  ├─ move-to-right-sidebar.gif
│     │  ├─ readme.gif
│     │  ├─ readme.png
│     │  ├─ scratch.gif
│     │  ├─ sidebar-icon.png
│     │  └─ welcome.md
│     ├─ models
│     │  ├─ README.md
│     │  └─ all-MiniLM-L6-v2
│     │     ├─ README.md
│     │     ├─ config.json
│     │     ├─ onnx
│     │     │  └─ model_quantized.onnx
│     │     ├─ special_tokens_map.json
│     │     ├─ tokenizer.json
│     │     ├─ tokenizer_config.json
│     │     └─ vocab.txt
│     ├─ package-lock.json
│     ├─ package.json
│     ├─ scripts
│     │  ├─ esbuild.js
│     │  ├─ importMetaUrl.js
│     │  ├─ package-all.js
│     │  ├─ package.js
│     │  ├─ prepackage-cross-platform.js
│     │  ├─ prepackage.js
│     │  ├─ utils.js
│     │  └─ versionCheck.js
│     ├─ src
│     │  ├─ ContinueGUIWebviewViewProvider.ts
│     │  ├─ VsCodeIde.ts
│     │  ├─ activation
│     │  │  ├─ activate.ts
│     │  │  ├─ api.ts
│     │  │  ├─ inlineTips.ts
│     │  │  ├─ languageClient.ts
│     │  │  └─ proxy.ts
│     │  ├─ autocomplete
│     │  │  ├─ completionProvider.ts
│     │  │  ├─ lsp.ts
│     │  │  ├─ recentlyEdited.ts
│     │  │  └─ statusBar.ts
│     │  ├─ commands.ts
│     │  ├─ debug
│     │  │  └─ debug.ts
│     │  ├─ decorations.ts
│     │  ├─ diff
│     │  │  ├─ horizontal.ts
│     │  │  ├─ verticalPerCharacter.ts
│     │  │  └─ verticalPerLine
│     │  │     ├─ decorations.ts
│     │  │     ├─ handler.ts
│     │  │     └─ manager.ts
│     │  ├─ extension
│     │  │  ├─ VsCodeExtension.ts
│     │  │  ├─ VsCodeMessenger.ts
│     │  │  ├─ autocomplete.ts
│     │  │  └─ indexing.ts
│     │  ├─ extension.ts
│     │  ├─ lang-server
│     │  │  ├─ codeActions.ts
│     │  │  └─ codeLens
│     │  │     ├─ index.ts
│     │  │     ├─ providers
│     │  │     │  ├─ ConfigPyCodeLensProvider.ts
│     │  │     │  ├─ DiffViewerCodeLensProvider.ts
│     │  │     │  ├─ QuickActionsCodeLensProvider.ts
│     │  │     │  ├─ SuggestionsCodeLensProvider.ts
│     │  │     │  ├─ TutorialCodeLensProvider.ts
│     │  │     │  ├─ VerticalPerLineCodeLensProvider.ts
│     │  │     │  └─ index.ts
│     │  │     └─ registerAllCodeLensProviders.ts
│     │  ├─ otherExtensions
│     │  │  └─ git.d.ts
│     │  ├─ quickEdit
│     │  │  ├─ ContextProvidersQuickPick.ts
│     │  │  ├─ HistoryQuickPick.ts
│     │  │  ├─ ModelSelectionQuickPick.ts
│     │  │  ├─ QuickEditQuickPick.ts
│     │  │  └─ index.ts
│     │  ├─ stubs
│     │  │  ├─ SecretStorage.ts
│     │  │  ├─ WorkOsAuthProvider.ts
│     │  │  ├─ activation.ts
│     │  │  ├─ auth.ts
│     │  │  ├─ promiseUtils.ts
│     │  │  └─ remoteConfig.ts
│     │  ├─ suggestions.ts
│     │  ├─ terminal
│     │  │  └─ terminalEmulator.ts
│     │  ├─ test
│     │  │  ├─ runner
│     │  │  │  ├─ mochaRunner.ts
│     │  │  │  └─ runTestOnVSCodeHost.ts
│     │  │  └─ test-suites
│     │  ├─ util
│     │  │  ├─ battery.ts
│     │  │  ├─ cleanSlate.ts
│     │  │  ├─ expandSnippet.ts
│     │  │  ├─ getTheme.ts
│     │  │  ├─ ideUtils.ts
│     │  │  ├─ loadAutocompleteModel.ts
│     │  │  ├─ messages.ts
│     │  │  ├─ util.ts
│     │  │  ├─ vscode.ts
│     │  │  └─ workspaceConfig.ts
│     │  └─ webviewProtocol.ts
│     ├─ tag-qry
│     │  ├─ tree-sitter-c-tags.scm
│     │  ├─ tree-sitter-c_sharp-tags.scm
│     │  ├─ tree-sitter-cpp-tags.scm
│     │  ├─ tree-sitter-elisp-tags.scm
│     │  ├─ tree-sitter-elixir-tags.scm
│     │  ├─ tree-sitter-elm-tags.scm
│     │  ├─ tree-sitter-go-tags.scm
│     │  ├─ tree-sitter-java-tags.scm
│     │  ├─ tree-sitter-javascript-tags.scm
│     │  ├─ tree-sitter-ocaml-tags.scm
│     │  ├─ tree-sitter-php-tags.scm
│     │  ├─ tree-sitter-python-tags.scm
│     │  ├─ tree-sitter-ql-tags.scm
│     │  ├─ tree-sitter-ruby-tags.scm
│     │  ├─ tree-sitter-rust-tags.scm
│     │  └─ tree-sitter-typescript-tags.scm
│     ├─ textmate-syntaxes
│     │  ├─ ASPVBnet.plist
│     │  ├─ Batch File.tmLanguage
│     │  ├─ Clojure.tmLanguage
│     │  ├─ Dockerfile.tmLanguage
│     │  ├─ Groovy.tmLanguage
│     │  ├─ Handlebars.json
│     │  ├─ JSON.tmLanguage
│     │  ├─ Jade.json
│     │  ├─ JavaScript.tmLanguage.json
│     │  ├─ MagicPython.tmLanguage.json
│     │  ├─ MagicRegExp.tmLanguage.json
│     │  ├─ Makefile.json
│     │  ├─ Objective-C.tmLanguage
│     │  ├─ Perl 6.tmLanguage
│     │  ├─ Perl.plist
│     │  ├─ Platform.tmLanguage
│     │  ├─ PowershellSyntax.tmLanguage
│     │  ├─ R.plist
│     │  ├─ Regular Expressions (JavaScript).tmLanguage
│     │  ├─ Ruby.plist
│     │  ├─ SQL.plist
│     │  ├─ Shell-Unix-Bash.tmLanguage.json
│     │  ├─ TypeScript.tmLanguage.json
│     │  ├─ TypeScriptReact.tmLanguage.json
│     │  ├─ c++.json
│     │  ├─ c.json
│     │  ├─ coffeescript.json
│     │  ├─ cshtml.json
│     │  ├─ css.plist
│     │  ├─ diff.tmLanguage
│     │  ├─ fsharp.json
│     │  ├─ git-commit.tmLanguage
│     │  ├─ git-rebase.tmLanguage
│     │  ├─ go.json
│     │  ├─ html.json
│     │  ├─ java.json
│     │  ├─ less.tmLanguage.json
│     │  ├─ lua.json
│     │  ├─ markdown.tmLanguage
│     │  ├─ php.json
│     │  ├─ properties.plist
│     │  ├─ rust.json
│     │  ├─ scss.json
│     │  ├─ shaderlab.json
│     │  ├─ swift.json
│     │  ├─ xml.json
│     │  ├─ xsl.json
│     │  └─ yaml.json
│     ├─ tree-sitter
│     │  ├─ code-snippet-queries
│     │  │  ├─ c.scm
│     │  │  ├─ c_sharp.scm
│     │  │  ├─ cpp.scm
│     │  │  ├─ elisp.scm
│     │  │  ├─ elixir.scm
│     │  │  ├─ go.scm
│     │  │  ├─ java.scm
│     │  │  ├─ javascript.scm
│     │  │  ├─ ocaml.scm
│     │  │  ├─ php.scm
│     │  │  ├─ python.scm
│     │  │  ├─ ql.scm
│     │  │  ├─ ruby.scm
│     │  │  ├─ rust.scm
│     │  │  └─ typescript.scm
│     │  └─ import-queries
│     │     └─ typescript.scm
│     ├─ tsconfig.json
│     └─ vsc-extension-quickstart.md
├─ gui
│  ├─ .gitignore
│  ├─ README.md
│  ├─ editorInset
│  │  ├─ index.html
│  │  └─ vite.config.ts
│  ├─ index.html
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ postcss.config.cjs
│  ├─ public
│  │  ├─ jetbrains_editorInset_index.html
│  │  ├─ jetbrains_index.html
│  │  └─ logos
│  │     ├─ WatsonX.png
│  │     ├─ anthropic.png
│  │     ├─ azure.png
│  │     ├─ cohere.png
│  │     ├─ deepseek.png
│  │     ├─ fireworks.png
│  │     ├─ flowiseai.png
│  │     ├─ gemini.png
│  │     ├─ google-palm.png
│  │     ├─ groq.png
│  │     ├─ hf.png
│  │     ├─ ibm.png
│  │     ├─ llamacpp.png
│  │     ├─ llamafile.png
│  │     ├─ lmstudio.png
│  │     ├─ meta.png
│  │     ├─ mistral.png
│  │     ├─ msty.png
│  │     ├─ ollama.png
│  │     ├─ openai.png
│  │     ├─ replicate.png
│  │     ├─ sambanova.png
│  │     ├─ together.png
│  │     └─ wizardlm.png
│  ├─ src
│  │  ├─ App.tsx
│  │  ├─ components
│  │  │  ├─ AddModelButtonSubtext.tsx
│  │  │  ├─ ChatScrollAnchor.tsx
│  │  │  ├─ CheckDiv.tsx
│  │  │  ├─ ContinueLogo.tsx
│  │  │  ├─ HeaderButtonWithText.tsx
│  │  │  ├─ InfoHover.tsx
│  │  │  ├─ Layout.tsx
│  │  │  ├─ OnboardingCard
│  │  │  │  ├─ OnboardingCard.tsx
│  │  │  │  ├─ components
│  │  │  │  │  ├─ BestExperienceConfigForm.tsx
│  │  │  │  │  ├─ JetBrainsFetchGitHubTokenDialog.tsx
│  │  │  │  │  ├─ OllamaCompletedStep.tsx
│  │  │  │  │  ├─ OllamaModelDownload.tsx
│  │  │  │  │  ├─ OllamaStatus.tsx
│  │  │  │  │  ├─ OnboardingCardTabs.tsx
│  │  │  │  │  ├─ ProviderAlert.tsx
│  │  │  │  │  └─ QuickStartSubmitButton.tsx
│  │  │  │  ├─ hooks
│  │  │  │  │  ├─ index.ts
│  │  │  │  │  ├─ useCheckOllamaModels.ts
│  │  │  │  │  ├─ useOnboardingCard.ts
│  │  │  │  │  └─ useSubmitOnboarding.ts
│  │  │  │  ├─ index.ts
│  │  │  │  ├─ tabs
│  │  │  │  │  ├─ OnboardingBestTab.tsx
│  │  │  │  │  ├─ OnboardingLocalTab.tsx
│  │  │  │  │  ├─ OnboardingQuickstartTab.tsx
│  │  │  │  │  └─ index.ts
│  │  │  │  └─ utils.ts
│  │  │  ├─ PosthogPageView.ts
│  │  │  ├─ ProfileSwitcher.tsx
│  │  │  ├─ SafeImg.tsx
│  │  │  ├─ dialogs
│  │  │  │  ├─ AddContextGroupDialog.tsx
│  │  │  │  ├─ AddDocsDialog.tsx
│  │  │  │  ├─ ConfirmationDialog.tsx
│  │  │  │  ├─ KeyboardShortcuts.tsx
│  │  │  │  └─ index.tsx
│  │  │  ├─ gui
│  │  │  │  ├─ Alert.tsx
│  │  │  │  ├─ ErrorStepContainer.tsx
│  │  │  │  ├─ StepContainer.tsx
│  │  │  │  └─ TimelineItem.tsx
│  │  │  ├─ index.tsx
│  │  │  ├─ loaders
│  │  │  │  ├─ BlinkingDot.tsx
│  │  │  │  ├─ IndexingProgressBar.tsx
│  │  │  │  ├─ Loader.tsx
│  │  │  │  ├─ ProgressBar.tsx
│  │  │  │  ├─ RingLoader.tsx
│  │  │  │  └─ StatusDot.tsx
│  │  │  ├─ mainInput
│  │  │  │  ├─ CodeBlockExtension.tsx
│  │  │  │  ├─ CommandsExtension.ts
│  │  │  │  ├─ ContextItemsPeek.tsx
│  │  │  │  ├─ ContinueButton.tsx
│  │  │  │  ├─ ContinueInputBox.tsx
│  │  │  │  ├─ InputToolbar.tsx
│  │  │  │  ├─ MentionExtension.ts
│  │  │  │  ├─ MentionList.tsx
│  │  │  │  ├─ TipTapEditor.css
│  │  │  │  ├─ TipTapEditor.tsx
│  │  │  │  ├─ TutorialCard.tsx
│  │  │  │  ├─ getSuggestion.ts
│  │  │  │  ├─ inputModifiers.ts
│  │  │  │  ├─ resolveInput.ts
│  │  │  │  └─ types.d.ts
│  │  │  ├─ markdown
│  │  │  │  ├─ CodeBlockToolbar.tsx
│  │  │  │  ├─ CodeSnippetPreview.tsx
│  │  │  │  ├─ CopyButton.tsx
│  │  │  │  ├─ LinkableCode.tsx
│  │  │  │  ├─ MonacoCodeBlock.tsx
│  │  │  │  ├─ PreWithToolbar.tsx
│  │  │  │  ├─ StyledMarkdownPreview.tsx
│  │  │  │  ├─ SyntaxHighlightedPre.tsx
│  │  │  │  ├─ VSCodeFileLink.tsx
│  │  │  │  ├─ katex.css
│  │  │  │  ├─ markdown.css
│  │  │  │  └─ monaco.css
│  │  │  └─ modelSelection
│  │  │     ├─ ModelCard.tsx
│  │  │     ├─ ModelProviderTag.tsx
│  │  │     ├─ ModelSelect.tsx
│  │  │     ├─ ModelSelectionListbox.tsx
│  │  │     ├─ ModelSettings.tsx
│  │  │     └─ Toggle.tsx
│  │  ├─ context
│  │  │  ├─ IdeMessenger.ts
│  │  │  ├─ SubmenuContextProviders.ts
│  │  │  └─ VscTheme.ts
│  │  ├─ editorInset
│  │  │  ├─ EditorInset.tsx
│  │  │  └─ main.tsx
│  │  ├─ forms
│  │  │  └─ AddModelForm.tsx
│  │  ├─ hooks
│  │  │  ├─ CustomPostHogProvider.tsx
│  │  │  ├─ useAppendedString.ts
│  │  │  ├─ useArrayState.ts
│  │  │  ├─ useAuth.tsx
│  │  │  ├─ useChatHandler.ts
│  │  │  ├─ useHistory.tsx
│  │  │  ├─ useInputHistory.ts
│  │  │  ├─ useNavigationListener.tsx
│  │  │  ├─ useSetup.ts
│  │  │  ├─ useSubmenuContextProviders.tsx
│  │  │  ├─ useTutorialCard.ts
│  │  │  ├─ useUIConfig.ts
│  │  │  ├─ useUpdatingRef.tsx
│  │  │  ├─ useVscTheme.ts
│  │  │  └─ useWebviewListener.ts
│  │  ├─ index.css
│  │  ├─ main.tsx
│  │  ├─ pages
│  │  │  ├─ AddNewModel
│  │  │  │  ├─ AddNewModel.tsx
│  │  │  │  ├─ ConfigureProvider.tsx
│  │  │  │  ├─ configs
│  │  │  │  │  ├─ completionParamsInputs.ts
│  │  │  │  │  ├─ models.ts
│  │  │  │  │  └─ providers.ts
│  │  │  │  └─ index.ts
│  │  │  ├─ error.tsx
│  │  │  ├─ gui.tsx
│  │  │  ├─ history.tsx
│  │  │  ├─ migration.tsx
│  │  │  ├─ monaco.tsx
│  │  │  ├─ more.tsx
│  │  │  ├─ settings.tsx
│  │  │  └─ stats.tsx
│  │  ├─ redux
│  │  │  ├─ selectors
│  │  │  │  ├─ index.ts
│  │  │  │  ├─ modelSelectors.ts
│  │  │  │  └─ uiStateSelectors.ts
│  │  │  ├─ slices
│  │  │  │  ├─ configSlice.ts
│  │  │  │  ├─ miscSlice.ts
│  │  │  │  ├─ serverStateReducer.ts
│  │  │  │  ├─ stateSlice.ts
│  │  │  │  └─ uiStateSlice.ts
│  │  │  └─ store.ts
│  │  ├─ util
│  │  │  ├─ freeTrial.ts
│  │  │  ├─ index.ts
│  │  │  └─ localStorage.ts
│  │  └─ vite-env.d.ts
│  ├─ tailwind.config.cjs
│  ├─ tsconfig.json
│  ├─ tsconfig.node.json
│  └─ vite.config.ts
├─ manual-testing-sandbox
│  ├─ example.ipynb
│  ├─ nested-folder
│  │  └─ helloNested.py
│  ├─ readme.md
│  ├─ test.css
│  ├─ test.csv
│  ├─ test.js
│  └─ test.rs
├─ media
│  ├─ IntelliJRunPluginScreenshot.png
│  ├─ above-line-edit.gif
│  ├─ autocomplete.gif
│  ├─ image.gif
│  ├─ readme.gif
│  ├─ readme.png
│  └─ scratch.gif
├─ packages
│  ├─ config-types
│  │  ├─ package-lock.json
│  │  ├─ package.json
│  │  ├─ src
│  │  │  └─ index.ts
│  │  └─ tsconfig.json
│  ├─ fetch
│  │  ├─ jest.config.d.ts
│  │  ├─ jest.config.js
│  │  ├─ jest.config.ts
│  │  ├─ package-lock.json
│  │  ├─ package.json
│  │  ├─ src
│  │  │  ├─ fetch.ts
│  │  │  ├─ index.ts
│  │  │  └─ stream.ts
│  │  └─ tsconfig.json
│  ├─ llm-info
│  │  ├─ README.md
│  │  ├─ package-lock.json
│  │  ├─ package.json
│  │  ├─ src
│  │  │  ├─ index.ts
│  │  │  ├─ models
│  │  │  │  ├─ anthropic.ts
│  │  │  │  ├─ google.ts
│  │  │  │  ├─ mistral.ts
│  │  │  │  └─ openai.ts
│  │  │  └─ types.ts
│  │  └─ tsconfig.json
│  └─ openai-adapters
│     ├─ .npmignore
│     ├─ jest.config.mjs
│     ├─ package-lock.json
│     ├─ package.json
│     ├─ src
│     │  ├─ apis
│     │  │  ├─ Anthropic.ts
│     │  │  ├─ AzureOpenAI.ts
│     │  │  ├─ Cohere.ts
│     │  │  ├─ DeepSeek.ts
│     │  │  ├─ Gemini.ts
│     │  │  ├─ Jina.ts
│     │  │  ├─ OpenAI.ts
│     │  │  └─ base.ts
│     │  └─ index.ts
│     ├─ test
│     └─ tsconfig.json
├─ scripts
│  ├─ install-dependencies.ps1
│  ├─ install-dependencies.sh
│  ├─ uninstall.js
│  └─ util
│     └─ index.js
└─ sync
   ├─ .vscode
   │  └─ settings.json
   ├─ Cargo.lock
   ├─ Cargo.toml
   └─ src
      ├─ README.md
      ├─ db
      │  └─ mod.rs
      ├─ gitignore.rs
      ├─ lib.rs
      ├─ sync
      │  ├─ merkle.rs
      │  └─ mod.rs
      ├─ sync.rs
      ├─ sync_db.rs
      ├─ utils
      │  └─ mod.rs
      └─ utils.rs

```