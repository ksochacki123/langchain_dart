📣 Check out the [releases page](https://github.com/davidmigloz/langchain_dart/releases) or the [#announcements](https://discord.com/channels/1123158322812555295/1123250594644242534) channel on the [LangChain.dart Discord](https://discord.gg/x4qbhqecVR) server for more details.

---

## 0.7.8

 - **FEAT**: Implement Markdown text splitter ([#635](https://github.com/davidmigloz/langchain_dart/issues/635)). ([242e4be2](https://github.com/davidmigloz/langchain_dart/commit/242e4be227503f93120b209bca350ed6a055f362))
 - **FEAT**: Update dependencies (requires Dart 3.6.0) ([#709](https://github.com/davidmigloz/langchain_dart/issues/709)). ([9e3467f7](https://github.com/davidmigloz/langchain_dart/commit/9e3467f7caabe051a43c0eb3c1110bc4a9b77b81))
 - **FEAT**: Add to/fromMap serialization to ChatMessage, PromptValue & ChatHistory ([#681](https://github.com/davidmigloz/langchain_dart/issues/681)). ([d239c7c7](https://github.com/davidmigloz/langchain_dart/commit/d239c7c7b4a1504559e475466be7f176521a0473))
 - **FIX**: Correctly calculate start_index when using chunkOverlap in TextSplitter ([#640](https://github.com/davidmigloz/langchain_dart/issues/640)). ([71dd5ac3](https://github.com/davidmigloz/langchain_dart/commit/71dd5ac31351d0ea45989c43a250a35668cb01b6))
 - **FIX**: Fix linter issues ([#656](https://github.com/davidmigloz/langchain_dart/issues/656)). ([88a79c65](https://github.com/davidmigloz/langchain_dart/commit/88a79c65aad23bcf5859e58a7375a4b686cf02ef))
 - **FIX**: Made apiKey optional for `TavilyAnswerTool` and `TavilySearchResultsTool` ([#646](https://github.com/davidmigloz/langchain_dart/issues/646)). ([5085ea4a](https://github.com/davidmigloz/langchain_dart/commit/5085ea4ad8b5cd072832e73afcbb7075a6375307))

## 0.7.7+2

 - **FEAT**: Add support for DirectoryLoader ([#620](https://github.com/davidmigloz/langchain_dart/issues/620)). ([4730f2a3](https://github.com/davidmigloz/langchain_dart/commit/4730f2a376b152ea38e5204125209ef01f29cab9))
 - **REFACTOR**: Add new lint rules and fix issues ([#621](https://github.com/davidmigloz/langchain_dart/issues/621)). ([60b10e00](https://github.com/davidmigloz/langchain_dart/commit/60b10e008acf55ebab90789ad08d2449a44b69d8))

## 0.7.7+1

 - **FIX**: UUID 'Namespace' can't be assigned to the parameter type 'String?' ([#566](https://github.com/davidmigloz/langchain_dart/issues/566)). ([1e93a595](https://github.com/davidmigloz/langchain_dart/commit/1e93a595f2f166da2cae3f7cfcdbb28892abf9b5))

## 0.7.7

 - **REFACTOR**: Update deprecated UUID constant ([#558](https://github.com/davidmigloz/langchain_dart/issues/558)). ([8d9f14b4](https://github.com/davidmigloz/langchain_dart/commit/8d9f14b4c394f4652727eadf5849355cd9fa2f19))

## 0.7.6

 - **FEAT**: Add retry support for Runnables ([#540](https://github.com/davidmigloz/langchain_dart/issues/540)). ([1099725d](https://github.com/davidmigloz/langchain_dart/commit/1099725d88de4103381edad533209a9a098bdb7f))

## 0.7.5

 - **FEAT**: Add ToolsAgent for models with tool-calling support ([#530](https://github.com/davidmigloz/langchain_dart/issues/530)). ([f3ee5b44](https://github.com/davidmigloz/langchain_dart/commit/f3ee5b44c4ffa378343ec4ee1e08d8e594a6cb36))
 - **FEAT**: Deprecate OpenAIToolsAgent in favour of ToolsAgent ([#532](https://github.com/davidmigloz/langchain_dart/issues/532)). ([68d8011a](https://github.com/davidmigloz/langchain_dart/commit/68d8011a9aa09368875ba0434839d12623ba2bab))
 - **DOCS**: Add Code Assist AI in README and documentation ([#538](https://github.com/davidmigloz/langchain_dart/issues/538)). ([e752464c](https://github.com/davidmigloz/langchain_dart/commit/e752464c0d2fc7e0ccc878933b0ef934c9527567))

## 0.7.4

 - **FEAT**: Add Fallback support for Runnables ([#501](https://github.com/davidmigloz/langchain_dart/issues/501)). ([5887858d](https://github.com/davidmigloz/langchain_dart/commit/5887858d667d43c49978291ea98a92cab0069971))
 - **FEAT**: Implement additive options merging for cascade bind calls ([#500](https://github.com/davidmigloz/langchain_dart/issues/500)). ([8691eb21](https://github.com/davidmigloz/langchain_dart/commit/8691eb21d5d2ffbf853997cbc0eaa29a56c6ca43))
 - **REFACTOR**: Remove default model from the language model options ([#498](https://github.com/davidmigloz/langchain_dart/issues/498)). ([44363e43](https://github.com/davidmigloz/langchain_dart/commit/44363e435778282ed27bc1b2771cf8b25abc7560))
 - **REFACTOR**: Depend on exact versions for internal 1st party dependencies ([#484](https://github.com/davidmigloz/langchain_dart/issues/484)). ([244e5e8f](https://github.com/davidmigloz/langchain_dart/commit/244e5e8f30e0d9a642fe01a804cc0de5e807e13d))
 - **DOCS**: Update README.md with Ollama tool call support. ([e016b0bd](https://github.com/davidmigloz/langchain_dart/commit/e016b0bd02065971faab2a3a48be625ff33a08cf))

## 0.7.3

> Note: Anthropic integration (`ChatAnthropic`) is now available in the new [`langchain_anthropic`](https://pub.dev/packages/langchain_anthropic) package.

- **FEAT**: Add support for TavilySearchResultsTool and TavilyAnswerTool ([#467](https://github.com/davidmigloz/langchain_dart/issues/467)). ([a9f35755](https://github.com/davidmigloz/langchain_dart/commit/a9f35755dfac9d257efb251c4a6c5948673c2f6c))
- **DOCS**: Document existing integrations in README.md. ([cc4246c8](https://github.com/davidmigloz/langchain_dart/commit/cc4246c8ab907de2c82843bff145edfffe32d302))

## 0.7.2

> Note: ObjectBox Vector DB integration (`ObjectBoxVectorStore`) is now available in the [`langchain_community`](https://pub.dev/packages/langchain_community) package.

 - **FEAT**: Add support for ObjectBoxVectorStore ([#438](https://github.com/davidmigloz/langchain_dart/issues/438)). ([81e167a6](https://github.com/davidmigloz/langchain_dart/commit/81e167a6888fff9f8db381caaef6ee788acef3a8))
   + Check out the [ObjectBoxVectorStore documentation](https://langchaindart.dev/#/modules/retrieval/vector_stores/integrations/objectbox?id=objectbox) 
 - **REFACTOR**: Migrate to langchaindart.dev domain ([#434](https://github.com/davidmigloz/langchain_dart/issues/434)). ([358f79d6](https://github.com/davidmigloz/langchain_dart/commit/358f79d6e0bae2ecd657aeed2eae7fad16d97c18))

## 0.7.1

> Note: VertexAI for Firebase (`ChatFirebaseVertexAI`) is now available in the new [`langchain_firebase`](https://pub.dev/packages/langchain_firebase) package.

 - **DOCS**: Add docs for ChatFirebaseVertexAI ([#422](https://github.com/davidmigloz/langchain_dart/issues/422)). ([8d0786bc](https://github.com/davidmigloz/langchain_dart/commit/8d0786bc6228ce86de962d30e9c2cc9728a08f3f))
 - **DOCS**: Update ChatOllama docs ([#417](https://github.com/davidmigloz/langchain_dart/issues/417)). ([9d30b1a1](https://github.com/davidmigloz/langchain_dart/commit/9d30b1a1c811d73cfa27110b8c3c10b10da1801e))

## 0.7.0

> Note: This release has breaking changes.  
> If you are using "function calling" check [how to migrate to "tool calling"](https://github.com/davidmigloz/langchain_dart/issues/400).

 - **BREAKING** **FEAT**: Migrate from function calling to tool calling ([#400](https://github.com/davidmigloz/langchain_dart/issues/400)). ([44413b83](https://github.com/davidmigloz/langchain_dart/commit/44413b8321b1188ff6b4027b1972a7ee0002761e))
 - **BREAKING** **REFACTOR**: Improve Tool abstractions ([#398](https://github.com/davidmigloz/langchain_dart/issues/398)). ([2a50aec2](https://github.com/davidmigloz/langchain_dart/commit/2a50aec28385068f9be32392020d727fc9a1561e))

## 0.6.0+1

 - **FIX**: Allow async functions in Runnable.mapInput ([#396](https://github.com/davidmigloz/langchain_dart/issues/396)). ([e4c35092](https://github.com/davidmigloz/langchain_dart/commit/e4c3509267b7be28e2b0fa334a9255baadabfb6a))

## 0.6.0

> Note: This release has breaking changes.  
> If you are using `Runnable.fromFunction` check the [migration guide](https://github.com/davidmigloz/langchain_dart/issues/394).

 - **FEAT** Add support for RunnableRouter ([#386](https://github.com/davidmigloz/langchain_dart/issues/386)). ([827e262](https://github.com/davidmigloz/langchain_dart/commit/827e2627535941d702e8fbe300ca1426ddf50efe))
 - **FEAT**: Add support for Runnable.mapInputStream ([#393](https://github.com/davidmigloz/langchain_dart/issues/393)). ([a2b6bbb5](https://github.com/davidmigloz/langchain_dart/commit/a2b6bbb5ea7a65c36d1e955f9f96298cf2384afc))
 - **FEAT**: Add support for JsonOutputParser ([#392](https://github.com/davidmigloz/langchain_dart/issues/392)). ([c6508f0f](https://github.com/davidmigloz/langchain_dart/commit/c6508f0fadde3fd4d93accbcae5cea37b7beca20))
 - **FEAT**: Reduce input stream for PromptTemplate, LLM, ChatModel, Retriever and Tool ([#388](https://github.com/davidmigloz/langchain_dart/issues/388)). ([b59bcd40](https://github.com/davidmigloz/langchain_dart/commit/b59bcd409f4904fb2e16f928b3c7206a186ab3f4))
 - **BREAKING** **FEAT**: Support different logic for streaming in RunnableFunction ([#394](https://github.com/davidmigloz/langchain_dart/issues/394)). ([8bb2b8ed](https://github.com/davidmigloz/langchain_dart/commit/8bb2b8ede18bfe3a4f266b78ca32f1dfb83db1b1))
 - **DOCS**: Update LangChain Expression Language documentation ([#395](https://github.com/davidmigloz/langchain_dart/issues/395)). ([6ce75e5f](https://github.com/davidmigloz/langchain_dart/commit/6ce75e5fe6492c951f9b5209d7a2c3077ad178d2))

## 0.5.0+1

 - **DOCS**: Update README.md. ([8139113a](https://github.com/davidmigloz/langchain_dart/commit/8139113a3ca8faa94145cbb6b1b80ca3bc2f3979))

## 0.5.0

> Note: This release has breaking changes.  
> [Migration guide](https://github.com/davidmigloz/langchain_dart/discussions/374)

 - **BREAKING** **REFACTOR**: Introduce langchain_core and langchain_community packages ([#328](https://github.com/davidmigloz/langchain_dart/issues/328)). ([5fa520e6](https://github.com/davidmigloz/langchain_dart/commit/5fa520e663602d9cdfcab0c62a053090fa02b02e))
 - **BREAKING** **REFACTOR**: Simplify LLMResult and ChatResult classes ([#363](https://github.com/davidmigloz/langchain_dart/issues/363)). ([ffe539c1](https://github.com/davidmigloz/langchain_dart/commit/ffe539c13f92cce5f564107430163b44be1dfd96))
 - **BREAKING** **REFACTOR**: Simplify Output Parsers ([#367](https://github.com/davidmigloz/langchain_dart/issues/367)). ([f24b7058](https://github.com/davidmigloz/langchain_dart/commit/f24b7058949fba47ba624f071a3f548b8f6e915e))
 - **BREAKING** **REFACTOR**: Remove deprecated generate and predict APIs ([#335](https://github.com/davidmigloz/langchain_dart/issues/335)). ([c55fe50f](https://github.com/davidmigloz/langchain_dart/commit/c55fe50f0040cc04cbd2e90bca475887c093c654))
 - **REFACTOR**: Simplify internal .stream implementation ([#364](https://github.com/davidmigloz/langchain_dart/issues/364)). ([c83fed22](https://github.com/davidmigloz/langchain_dart/commit/c83fed22b2b89d5e51211984b12ec126a3ca225e))
 - **FEAT**: Implement .batch support ([#370](https://github.com/davidmigloz/langchain_dart/issues/370)). ([d254f929](https://github.com/davidmigloz/langchain_dart/commit/d254f929b03d9c950029e55c66831f9f89cc14a9))
 - **FEAT**: Add reduceOutputStream option to StringOutputParser ([#368](https://github.com/davidmigloz/langchain_dart/issues/368)). ([7f9a9fae](https://github.com/davidmigloz/langchain_dart/commit/7f9a9faeef93685ff810a88bbfe866da4b843369))
 - **DOCS**: Update LCEL docs. ([ab3ab573](https://github.com/davidmigloz/langchain_dart/commit/ab3ab573f62d9a497e7c82308da0a044337e957d))
 - **DOCS**: Add RAG example using OllamaEmbeddings and ChatOllama ([#337](https://github.com/davidmigloz/langchain_dart/issues/337)). ([8bddc6c0](https://github.com/davidmigloz/langchain_dart/commit/8bddc6c05b762be357a3c3ed0f6fc4af3aad866a))

## 0.4.2

 - **FEAT**: Update meta and test dependencies ([#331](https://github.com/davidmigloz/langchain_dart/issues/331)). ([912370ee](https://github.com/davidmigloz/langchain_dart/commit/912370ee0ba667ee9153303395a457e6caf5c72d))

## 0.4.1

 - **DOCS**: Update Supabase docs. ([4a2a5329](https://github.com/davidmigloz/langchain_dart/commit/4a2a532931cac7577102d78b0ec8a5cc4eafb93c))
 - **DOCS**: Update CHANGELOG.md. ([d0d46534](https://github.com/davidmigloz/langchain_dart/commit/d0d46534565d6f52d819d62329e8917e00bc7030))

## 0.4.0

 - **DOCS**: Update embeddings documentation ([#313](https://github.com/davidmigloz/langchain_dart/issues/313)). ([43463481](https://github.com/davidmigloz/langchain_dart/commit/4346348108dc105a1daaedc932641e725b648f3e))

## 0.3.3

 - **DOCS**: Add Anyscale and Together AI documentation ([#305](https://github.com/davidmigloz/langchain_dart/issues/305)). ([7daa3eb0](https://github.com/davidmigloz/langchain_dart/commit/7daa3eb052c32baa7473d7532c795b7f242ed9fc))

## 0.3.2

 - **REFACTOR**: Make all LLM options fields nullable and add copyWith ([#284](https://github.com/davidmigloz/langchain_dart/issues/284)). ([57eceb9b](https://github.com/davidmigloz/langchain_dart/commit/57eceb9b47da42cf19f64ddd88bfbd2c9676fd5e))
 - **FIX**: Export ConversationSummaryMemory ([#283](https://github.com/davidmigloz/langchain_dart/issues/283)). ([76b01d23](https://github.com/davidmigloz/langchain_dart/commit/76b01d2376c0d9727d1f4681dba83a46f4b02b3a))
 - **FEAT**: Update internal dependencies ([#291](https://github.com/davidmigloz/langchain_dart/issues/291)). ([69621cc6](https://github.com/davidmigloz/langchain_dart/commit/69621cc61659980d046518ee20ce055e806cba1f))

## 0.3.1+1

 - **FIX**: Export token_buffer.dart (ConversationTokenBufferMemory) ([#280](https://github.com/davidmigloz/langchain_dart/issues/280)). ([265fcb4b](https://github.com/davidmigloz/langchain_dart/commit/265fcb4b68a5aa6144456868aebf023e1b0ce539))

## 0.3.1

 - **FEAT**: Make ChatPromptTemplates more convenient to use ([#275](https://github.com/davidmigloz/langchain_dart/issues/275)). ([9f8e6f75](https://github.com/davidmigloz/langchain_dart/commit/9f8e6f75543a41b87aff72fbeb249acf859a9562))

## 0.3.0

> Note: This release has breaking changes.  
> [Migration guide](https://github.com/davidmigloz/langchain_dart/issues/269) 

 - **BREAKING** **REFACTOR**: Make MIME Type mandatory for base64 images in prompt ([#269](https://github.com/davidmigloz/langchain_dart/issues/269)). ([2fe076bb](https://github.com/davidmigloz/langchain_dart/commit/2fe076bb8d2ddacfee6ec077c3f564bff919dace))
 - **FEAT**: Allow to pass options to countTokens method ([#268](https://github.com/davidmigloz/langchain_dart/issues/268)). ([4ecb123b](https://github.com/davidmigloz/langchain_dart/commit/4ecb123bd34f0b01d377045b97dace89676d5d16))
 - **DOCS**: Update README.md and docs ([#272](https://github.com/davidmigloz/langchain_dart/issues/272)). ([306a1fdd](https://github.com/davidmigloz/langchain_dart/commit/306a1fdd6504ef28dc2066953ae575e975ab9025))

## 0.2.1

 - **FEAT**: Support customizing Tool input description ([#258](https://github.com/davidmigloz/langchain_dart/issues/258)). ([a9a1b2a0](https://github.com/davidmigloz/langchain_dart/commit/a9a1b2a0f4fa5fee320e9ca5b46a99a0b834035c))
 - **DOCS**: Update Mistral AI documentation ([#265](https://github.com/davidmigloz/langchain_dart/issues/265)). ([59b4127e](https://github.com/davidmigloz/langchain_dart/commit/59b4127eddb7a04bafa34b11b071336ab336e7a9))

## 0.2.0

> Note: This release has breaking changes.
>
> Migration guides:
> - [`Retriever`](https://github.com/davidmigloz/langchain_dart/issues/248)
> - [`Tools`](https://github.com/davidmigloz/langchain_dart/issues/243)

 - **BREAKING** **FEAT**: Move all retriever config options to RetrieverOptions ([#248](https://github.com/davidmigloz/langchain_dart/issues/248)). ([f5785b77](https://github.com/davidmigloz/langchain_dart/commit/f5785b772c11750bb57f4b143f978a84743f9222))
 - **BREAKING** **FEAT**: Allow to pass call options to tools ([#243](https://github.com/davidmigloz/langchain_dart/issues/243)). ([4a01adb9](https://github.com/davidmigloz/langchain_dart/commit/4a01adb9346b33cdb148d0f0aa7196e2b16867a9))
 - **FEAT**: Allow to mutate default options ([#256](https://github.com/davidmigloz/langchain_dart/issues/256)). ([cb5e4058](https://github.com/davidmigloz/langchain_dart/commit/cb5e4058fb89f33c8495ac22fb240ce92daa683c))
 - **REFACTOR**: Use JsonPath.readValues in JsonLoader ([#245](https://github.com/davidmigloz/langchain_dart/issues/245)). ([3e159254](https://github.com/davidmigloz/langchain_dart/commit/3e159254379d03b70655f274b6fe81fc07a5095f))
 - **FIX**: Out of rage error in ConversationBufferWindowMemory ([#249](https://github.com/davidmigloz/langchain_dart/issues/249)). ([1b38bff7](https://github.com/davidmigloz/langchain_dart/commit/1b38bff7eff10327cd0154c0a8d47bd363870e2d))
 - **FIX**: PromptTemplate stream should only emit if it has all inputs ([#247](https://github.com/davidmigloz/langchain_dart/issues/247)). ([a56a2ec5](https://github.com/davidmigloz/langchain_dart/commit/a56a2ec5e084d5c140b0e8469707ecaa19dfdaff))

## 0.1.1+1

 - **FIX**: Conditionally import dart:io in LocalFileStore ([#237](https://github.com/davidmigloz/langchain_dart/issues/237)). ([71d337e6](https://github.com/davidmigloz/langchain_dart/commit/71d337e62af49f173369e402fa6a72e363fd8724))

## 0.1.1

 - **FEAT**: Add support for OpenAIDallETool ([#231](https://github.com/davidmigloz/langchain_dart/issues/231)). ([541e8d77](https://github.com/davidmigloz/langchain_dart/commit/541e8d77d76246b25ffa8c4d3715b5ca728cfc3a))
 - **FEAT**: Support implementing custom agents using LCEL ([#230](https://github.com/davidmigloz/langchain_dart/issues/230)). ([625eeeb4](https://github.com/davidmigloz/langchain_dart/commit/625eeeb4ffa9d92c6fd8da003fa471f5d4752257))
 - **FEAT**: Add support for Runnable.mapInput() ([#229](https://github.com/davidmigloz/langchain_dart/issues/229)). ([7cc832ca](https://github.com/davidmigloz/langchain_dart/commit/7cc832ca82bd86b4031ca5f2c796e136ca646375))
 - **REFACTOR**: Rename RunnableMapFromItem to RunnableMapFromInput ([#228](https://github.com/davidmigloz/langchain_dart/issues/228)). ([7330cfcd](https://github.com/davidmigloz/langchain_dart/commit/7330cfcd0c7e19c831da1454c3ff4cc03d079cf7))
 - **REFACTOR**: Improve handling of input and output keys in chains ([#227](https://github.com/davidmigloz/langchain_dart/issues/227)). ([acf76b24](https://github.com/davidmigloz/langchain_dart/commit/acf76b240a076cf4b1f153bdaba9127580369d9e))

## 0.1.0+2

 - **DOCS**: Update README.md ([#225](https://github.com/davidmigloz/langchain_dart/issues/225)). ([afff8567](https://github.com/davidmigloz/langchain_dart/commit/afff856723f15022bcc3f0ba0285ff1ffed51c68))

## 0.1.0+1

 - **DOCS**: Add public_member_api_docs lint rule and document missing APIs ([#223](https://github.com/davidmigloz/langchain_dart/issues/223)). ([52380433](https://github.com/davidmigloz/langchain_dart/commit/523804331783970870b023946c016be6c0797920))

## 0.1.0

> Note: This release has breaking changes.  
> [Migration guide](https://github.com/davidmigloz/langchain_dart/issues/220)

 - **BREAKING** **FEAT**: Add multi-modal messages support with OpenAI Vision ([#220](https://github.com/davidmigloz/langchain_dart/issues/220)). ([6da2e069](https://github.com/davidmigloz/langchain_dart/commit/6da2e069932782eed8c27da45c56b4c290373fac))

## 0.0.15

 - **FEAT**: Add streaming support in LangChain Expression Language ([#192](https://github.com/davidmigloz/langchain_dart/issues/192)). ([2e4bcf91](https://github.com/davidmigloz/langchain_dart/commit/2e4bcf91f6b364b32b6f999e71252001ca6392c8))
 - **DOCS**: Add streaming to docs. ([bb87c190](https://github.com/davidmigloz/langchain_dart/commit/bb87c1901b34810aa2e841ed83da8e70703b9d08))
 - **FEAT**: Add streaming support to OutputFunctionsParsers ([#194](https://github.com/davidmigloz/langchain_dart/issues/194)). ([8b4e6a13](https://github.com/davidmigloz/langchain_dart/commit/8b4e6a138cd9942dd6ea1a97fe5e19e84a30000c))
 - **FIX**: Remove unused generic param in StringOutputParser ([#193](https://github.com/davidmigloz/langchain_dart/issues/193)). ([decd3176](https://github.com/davidmigloz/langchain_dart/commit/decd31765114bea1967f15e5fbd83110709938e4))

## 0.0.14

> Note: This release has breaking changes.

 - **REFACTOR**: Don't require implement getFormatInstructions. ([d8b1286d](https://github.com/davidmigloz/langchain_dart/commit/d8b1286db59e02b60179e395eb43cdc3828582c2))
 - **DOCS**: Update docs. ([af7ee827](https://github.com/davidmigloz/langchain_dart/commit/af7ee8278f18620a54072bb9d1772882956d5c2d))
 - **BREAKING** **FIX**: Change loaders lastModified metadata field to integer ([#172](https://github.com/davidmigloz/langchain_dart/issues/172)). ([72c724f8](https://github.com/davidmigloz/langchain_dart/commit/72c724f8a716e27b4a807b70bcbbafdd9feb0a18))
 - **BREAKING** **FEAT**: Update uuid internal dependency to 4.x.x ([#173](https://github.com/davidmigloz/langchain_dart/issues/173)). ([b01f4afe](https://github.com/davidmigloz/langchain_dart/commit/b01f4afea6cfcdf8a0aa6e1b11d3057efa6e5fc0))

## 0.0.13

> Check out the [LangChain Expression Language documentation](https://langchaindart.dev/#/expression_language/interface) for more details

 - **FEAT**: Add support for JsonOutputFunctionsParser ([#165](https://github.com/davidmigloz/langchain_dart/issues/165)). ([66c8e644](https://github.com/davidmigloz/langchain_dart/commit/66c8e64410d1dbf8b75e5734cb0cbb0e43dc0615))
 - **FEAT**: Add support for StringOutputParser ([#164](https://github.com/davidmigloz/langchain_dart/issues/164)). ([ee29e99a](https://github.com/davidmigloz/langchain_dart/commit/ee29e99a410c3cc6a7ae263fea1cde283f904edf))
 - **FEAT**: Implement LangChain Expression Language (LCEL) ([#163](https://github.com/davidmigloz/langchain_dart/issues/163)). ([85ea41af](https://github.com/davidmigloz/langchain_dart/commit/85ea41af9f5e2ff42bba620a60f765ca0f67c86c))
 - **FEAT**: Support custom doc prompt in StuffDocumentsQAChain ([#157](https://github.com/davidmigloz/langchain_dart/issues/157)). ([faa9d2d7](https://github.com/davidmigloz/langchain_dart/commit/faa9d2d768c2a70f17247d5703dd1d821af08240))

## 0.0.12

> Note: This release has breaking changes.

 - **DOCS**: Acknowledge sponsors in readme. ([092d94c8](https://github.com/davidmigloz/langchain_dart/commit/092d94c8ac166cf47f1ddab748b61d440f4b8585))
 - **DOCS**: Add topics to pubspecs. ([8c1d6297](https://github.com/davidmigloz/langchain_dart/commit/8c1d62970710cc326fd5930101918aaf16b18f74))
 - **BREAKING** **REFACTOR**: Change embedDocuments input to `List<Document>` ([#153](https://github.com/davidmigloz/langchain_dart/issues/153)). ([1b5d6fbf](https://github.com/davidmigloz/langchain_dart/commit/1b5d6fbf20bcbb7734581f91d66eff3a86731fec))

## 0.0.11

> Note: This release has breaking changes.

 - **DOCS**: Update readme. ([e1b5b295](https://github.com/davidmigloz/langchain_dart/commit/e1b5b2958bdf2b787c8b49aeeb6690c33c225943))
 - **BREAKING** **REFACTOR**: Remove addDocuments from VectorStoreRetriever ([#146](https://github.com/davidmigloz/langchain_dart/issues/146)). ([d32a5fd9](https://github.com/davidmigloz/langchain_dart/commit/d32a5fd94645d10deee5a35f0d83501f93be7308))
 - **BREAKING** **REFACTOR**: Rename VectorStoreRetrieverMemory and require vector store ([#145](https://github.com/davidmigloz/langchain_dart/issues/145)). ([67af3195](https://github.com/davidmigloz/langchain_dart/commit/67af319595755ec3c3834ceabaf4086cfa32ad8c))

## 0.0.10

 - **FEAT**: Add support for Chroma VectorStore ([#139](https://github.com/davidmigloz/langchain_dart/issues/139)). ([098783b4](https://github.com/davidmigloz/langchain_dart/commit/098783b4895ab30bb61d07355a0b587ff76b9175))
 - **DOCS**: Update readme. ([b61eda5b](https://github.com/davidmigloz/langchain_dart/commit/b61eda5ba506b4602592511c6a9be1e7aae5bf57))

## 0.0.9

 - **FEAT**: Support filtering in MemoryVectorStore ([#137](https://github.com/davidmigloz/langchain_dart/issues/137)). ([84da480f](https://github.com/davidmigloz/langchain_dart/commit/84da480f6820a81f092756f0194deb77c4cda151))
 - **FEAT**: Support filtering in VertexAI Matching Engine ([#136](https://github.com/davidmigloz/langchain_dart/issues/136)). ([768c6987](https://github.com/davidmigloz/langchain_dart/commit/768c6987de5b36b60090a1fe94f49483da11b885))
 - **FEAT**: Allow to pass vector search config ([#135](https://github.com/davidmigloz/langchain_dart/issues/135)). ([5b8fa5a3](https://github.com/davidmigloz/langchain_dart/commit/5b8fa5a3fcaf785615016be1d5da0a003178cfa9))
 - **DOCS**: Fix API documentation errors ([#138](https://github.com/davidmigloz/langchain_dart/issues/138)). ([1aa38fce](https://github.com/davidmigloz/langchain_dart/commit/1aa38fce17eed7f325e7872d03096740256d57be))

## 0.0.8

 - **REFACTOR**: Rename store folder to chat_message_history ([#126](https://github.com/davidmigloz/langchain_dart/issues/126)). ([fa54c7e2](https://github.com/davidmigloz/langchain_dart/commit/fa54c7e22410182848b1936b64e85d9cf709eaeb))
 - **REFACTOR**: Fix Dart 3.1.0 linter issues ([#125](https://github.com/davidmigloz/langchain_dart/issues/125)). ([cc32f3f1](https://github.com/davidmigloz/langchain_dart/commit/cc32f3f13240c28cf174a9dbffc7d61bc061f843))
 - **FEAT**: Add support for LocalFileStore ([#132](https://github.com/davidmigloz/langchain_dart/issues/132)). ([2c508dce](https://github.com/davidmigloz/langchain_dart/commit/2c508dcea4959dbe755ee713de43dc20c9680640))
 - **FEAT**: Add support for CacheBackedEmbeddings ([#131](https://github.com/davidmigloz/langchain_dart/issues/131)). ([27d8b777](https://github.com/davidmigloz/langchain_dart/commit/27d8b777b4da360e57f32de6e1e1fc09ea6b6333))
 - **FEAT**: Add FakeEmbeddings testing model ([#130](https://github.com/davidmigloz/langchain_dart/issues/130)). ([f06920d7](https://github.com/davidmigloz/langchain_dart/commit/f06920d792d1083876b040744213d78c9b11bd4c))
 - **FEAT**: Add support for EncoderBackedStore ([#129](https://github.com/davidmigloz/langchain_dart/issues/129)). ([85bb3191](https://github.com/davidmigloz/langchain_dart/commit/85bb31918308f7a956afd0f991a78cf65e6dcd8d))
 - **FEAT**: Add support for InMemoryStore ([#128](https://github.com/davidmigloz/langchain_dart/issues/128)). ([699c0904](https://github.com/davidmigloz/langchain_dart/commit/699c09045fec3f91666f7ee264525cec8b16f910))
 - **FEAT**: Add support for InMemoryDocStore ([#127](https://github.com/davidmigloz/langchain_dart/issues/127)). ([d9d7268d](https://github.com/davidmigloz/langchain_dart/commit/d9d7268ddcd9e346f67e1278127e25ee467ea99c))
 - **FEAT**: Initial vectors, ids, and delete in MemoryVectorStore ([#123](https://github.com/davidmigloz/langchain_dart/issues/123)). ([f87a738d](https://github.com/davidmigloz/langchain_dart/commit/f87a738d6e9c78aabcbd95014dd4fac2d6c58817))

## 0.0.7+1

 - **FIX**: Text splitters were not preserving docs IDs ([#122](https://github.com/davidmigloz/langchain_dart/issues/122)). ([a9d7f098](https://github.com/davidmigloz/langchain_dart/commit/a9d7f098e650329fe43f35e2f0e11a1f61778e4f))

## 0.0.7

 - **FEAT**: Integrate Vertex AI Matching Engine vector store ([#103](https://github.com/davidmigloz/langchain_dart/issues/103)). ([289c3eef](https://github.com/davidmigloz/langchain_dart/commit/289c3eef722206ac9dea0c968c036ad3289d10be))
 - **DOCS**: Update readme. ([a64860ce](https://github.com/davidmigloz/langchain_dart/commit/a64860ceda8fe926b720086cf7c86df2b02abf35))
 - **DOCS**: Update readme. ([8a58f4a1](https://github.com/davidmigloz/langchain_dart/commit/8a58f4a1923f474bc331e2d02b9cf14b79194331))

## 0.0.6

 - **REFACTOR**: Move Vertex AI client to its own package ([#111](https://github.com/davidmigloz/langchain_dart/issues/111)). ([d8aea156](https://github.com/davidmigloz/langchain_dart/commit/d8aea15633f1a9fb0df35cf9cc44bbc93ad46cd8))
 - **REFACTOR**: Always await or explicitly discard Futures ([#106](https://github.com/davidmigloz/langchain_dart/issues/106)). ([989e93db](https://github.com/davidmigloz/langchain_dart/commit/989e93dbf6b5d61f053550219d88842156aeb492))
 - **FIX**: Fix OpenAIQAWithSourcesChain returning empty strings ([#113](https://github.com/davidmigloz/langchain_dart/issues/113)). ([6181ff8d](https://github.com/davidmigloz/langchain_dart/commit/6181ff8df77653d38cd84cb066776c04c0ff74ad))
 - **FIX**: VectorStore k variable was ignored ([#110](https://github.com/davidmigloz/langchain_dart/issues/110)). ([80e61eb7](https://github.com/davidmigloz/langchain_dart/commit/80e61eb7a11757f4e541ce5ba6033fb11b1b01f0))
 - **FEAT**: Integrate Google Vertex AI PaLM Chat Model ([#99](https://github.com/davidmigloz/langchain_dart/issues/99)). ([3897595d](https://github.com/davidmigloz/langchain_dart/commit/3897595db597d5957ef80ae7a1de35c5f41265b8))
 - **FEAT**: Integrate Google Vertex AI PaLM Text model ([#98](https://github.com/davidmigloz/langchain_dart/issues/98)). ([b2746c23](https://github.com/davidmigloz/langchain_dart/commit/b2746c235d68045ba20afd1f2be7c24dcccb5f24))

## 0.0.5+1

 - **FIX**: OpenAIOptions class not exported ([#104](https://github.com/davidmigloz/langchain_dart/issues/104)). ([e50efc3d](https://github.com/davidmigloz/langchain_dart/commit/e50efc3ddf0b13ece43298b2e3fee531e944601d))
 - **DOCS**: Improve RetrievalQAChain API documentation ([#95](https://github.com/davidmigloz/langchain_dart/issues/95)). ([e6d0a9d3](https://github.com/davidmigloz/langchain_dart/commit/e6d0a9d3abd65704883452e50b40344428f9580d))

## 0.0.5

 - **FIX**: Suff and MapReduce docs chains don't handle chat messages ([#92](https://github.com/davidmigloz/langchain_dart/issues/92)). ([19182ca1](https://github.com/davidmigloz/langchain_dart/commit/19182ca1921e53fc2cb0fa61d96d602aacf830f3))
 - **FEAT**: Update AgentExecutor constructor to use agent's tools ([#89](https://github.com/davidmigloz/langchain_dart/issues/89)). ([3af56a45](https://github.com/davidmigloz/langchain_dart/commit/3af56a45930fff84b11f6bec29c50502a490c2b4))
 - **FEAT**: Add MessagePlaceholder ([#87](https://github.com/davidmigloz/langchain_dart/issues/87)). ([23ee95b6](https://github.com/davidmigloz/langchain_dart/commit/23ee95b6cb0bb15701a141adc41ee1b826684ad0))
 - **DOCS**: Update CONTRIBUTING.md. ([5f2b9264](https://github.com/davidmigloz/langchain_dart/commit/5f2b92641ae1f20fcc8803c977428b81e3f525bd))
 - **DOCS**: Fix typo in MessagePlaceholder API docs ([#90](https://github.com/davidmigloz/langchain_dart/issues/90)). ([f53e1a2b](https://github.com/davidmigloz/langchain_dart/commit/f53e1a2b9dc81c89a66a368758cfd1ec7df4c0f9))

## 0.0.4

 - **REFACTOR**: Extract default memory key and prefixes to constants. ([750fd01a](https://github.com/davidmigloz/langchain_dart/commit/750fd01a74f94042cbc26684d6651b531fb0a93c))
 - **FIX**: systemChatMessage was ignored in OpenAIFunctionsAgent ([#86](https://github.com/davidmigloz/langchain_dart/issues/86)). ([cfe1e009](https://github.com/davidmigloz/langchain_dart/commit/cfe1e00972d481f83b9dc9e225a32b7077aa5fd4))
 - **FIX**: Allow to add memory to an agent executor ([#80](https://github.com/davidmigloz/langchain_dart/issues/80)). ([8110464c](https://github.com/davidmigloz/langchain_dart/commit/8110464c4b4ad53f3b1826722df76943d0d66621))
 - **FEAT**: Add ConversationSummaryMemory ([#27](https://github.com/davidmigloz/langchain_dart/issues/27)). ([f631d9e5](https://github.com/davidmigloz/langchain_dart/commit/f631d9e529d99319afe671b5aff441436e43ea31))
 - **FEAT**: Support LLMChain in OpenAIFunctionsAgent and memory. ([bd4a1cb9](https://github.com/davidmigloz/langchain_dart/commit/bd4a1cb9101ba385ce9613f9aa0b7e5474380f32))
 - **FEAT**: Return ChatMessage when LLMChain used with ChatModel. ([bb5f4d23](https://github.com/davidmigloz/langchain_dart/commit/bb5f4d2325ae1f615159f2ffd11cc8ec4e87ed3c))
 - **FEAT**: Add FakeChatModel for testing purposes. ([659783a6](https://github.com/davidmigloz/langchain_dart/commit/659783a6ccad9fc3046040f38c39805743ffdff1))
 - **FEAT**: Add support for ConversationTokenBufferMemory ([#26](https://github.com/davidmigloz/langchain_dart/issues/26)). ([8113d1c0](https://github.com/davidmigloz/langchain_dart/commit/8113d1c0dc742ce9f6c49018c4b012cd3823fac1))
 - **FEAT**: Improve SummarizeChain.mapReduce summaryMaxTokens name and docs. ([0be06e02](https://github.com/davidmigloz/langchain_dart/commit/0be06e02f280de54a2790d150fac142d9fbe4222))
 - **FEAT**: Add support for CsvLoader ([#77](https://github.com/davidmigloz/langchain_dart/issues/77)). ([41d24e76](https://github.com/davidmigloz/langchain_dart/commit/41d24e7632a77b08234951c0e6bf911530dff56a))
 - **FEAT**: Add ConversationBufferWindowMemory ([#25](https://github.com/davidmigloz/langchain_dart/issues/25)). ([9c271f7e](https://github.com/davidmigloz/langchain_dart/commit/9c271f7e7a31bc59c122a895daf238a0bb5ac7d0))

## 0.0.3

 - **FIX**: Loaders tests. ([f0498300](https://github.com/davidmigloz/langchain_dart/commit/f049830057fc1b8ff315469afd1512aa13ceb459))
 - **FEAT**: Update internal dependencies (including http to 1.1.0). ([8f3e8bc8](https://github.com/davidmigloz/langchain_dart/commit/8f3e8bc811df5c8bdba2c7e33b6c53ea0c2edad4))
 - **FEAT**: Add support for VectorStoreRetrieverMemory ([#54](https://github.com/davidmigloz/langchain_dart/issues/54)). ([72cd1b10](https://github.com/davidmigloz/langchain_dart/commit/72cd1b100ad88e7213ec12d432674ec4666ce172))

## 0.0.2

 - **FIX**: OpenAIQAWithSourcesChain throws exception. ([45c6cb9d](https://github.com/davidmigloz/langchain_dart/commit/45c6cb9d32be670902dd2fe4cb92597765590d85))
 - **FEAT**: Add support for SummarizeChain ([#58](https://github.com/davidmigloz/langchain_dart/issues/58)). ([9499fc04](https://github.com/davidmigloz/langchain_dart/commit/9499fc047ae8be7e7b9dfb0d0ef8678b84245f5d))
 - **FEAT**: Add support for SequentialChain class ([#30](https://github.com/davidmigloz/langchain_dart/issues/30)). ([381a6768](https://github.com/davidmigloz/langchain_dart/commit/381a676812992370da61ced0e59de5fadf0ef164))
 - **FEAT**: Add support for WebBaseLoader ([#74](https://github.com/davidmigloz/langchain_dart/issues/74)). ([0b5bf4b0](https://github.com/davidmigloz/langchain_dart/commit/0b5bf4b0fb2cf6e1a7be116920e9512233e7e613))
 - **FEAT**: Add Support for JsonLoader ([#72](https://github.com/davidmigloz/langchain_dart/issues/72)). ([2457a973](https://github.com/davidmigloz/langchain_dart/commit/2457a9735aacc2aeffcca2710ce0afc7be2f6f09))
 - **FEAT**: Add support for MapReduceDocumentsChain ([#59](https://github.com/davidmigloz/langchain_dart/issues/59)). ([9f2190c4](https://github.com/davidmigloz/langchain_dart/commit/9f2190c4d5f45378f91eaa02d52d8305f7da254e))
 - **FEAT**: Add support for ReduceDocumentsChain ([#70](https://github.com/davidmigloz/langchain_dart/issues/70)). ([34cf10bd](https://github.com/davidmigloz/langchain_dart/commit/34cf10bd485618bff4cddb5b29a1b46ac9f3a9fa))
 - **FEAT**: Support estimating the number of tokens for a given prompt ([#3](https://github.com/davidmigloz/langchain_dart/issues/3)). ([e22f22c8](https://github.com/davidmigloz/langchain_dart/commit/e22f22c89f188a019b96a7c0003dbd26471bebb7))
 - **FEAT**: Add support for CodeTextSplitter ([#63](https://github.com/davidmigloz/langchain_dart/issues/63)). ([92a8c7da](https://github.com/davidmigloz/langchain_dart/commit/92a8c7daccda2be38a25d4bdb0235c2f397225a2))
 - **FEAT**: Add support for RecursiveCharacterTextSplitter ([#61](https://github.com/davidmigloz/langchain_dart/issues/61)). ([697cdcbf](https://github.com/davidmigloz/langchain_dart/commit/697cdcbfef8fc45930de127cb5b7ee2eb3d7ec37))
 - **DOCS**: Document sequential chain. ([b9693a4e](https://github.com/davidmigloz/langchain_dart/commit/b9693a4e2dfcc6bfc74025ebb935865be942b266))
 - **DOCS**: Document text, json and web loaders. ([a95b3e9f](https://github.com/davidmigloz/langchain_dart/commit/a95b3e9f843fcffce9449ea93f343df793512a09))
 - **DOCS**: Update API docs. ([7bfa6d17](https://github.com/davidmigloz/langchain_dart/commit/7bfa6d17cf57aac05906b1401ac3967c21e6f403))
 - **DOCS**: Update readme. ([dd394715](https://github.com/davidmigloz/langchain_dart/commit/dd39471557b37da0d0c2a87dea0c067463a45f45))

## 0.0.1

 - Initial public release. 

Check out the announcement post for all the details: 
https://blog.langchaindart.dev/introducing-langchain-dart-6b1d34fc41ef

## 0.0.1-dev.7

- Add support for Agent class (#33).
- Add support for AgentExecutor class (#56).
- Update hello_world_flutter example with local models.

## 0.0.1-dev.6

- Add support for PipelinePromptTemplate class (#18).
- LLMChain improvements (#43).

## 0.0.1-dev.5

- Add support for TextLoader (#47).
- Add support for BaseLoader (#46).
- Add support for RetrievalQAChain class (#42).
- Add support for StuffDocumentsQAChain (#50).
- Add support for StuffDocumentsChain (#49).
- Add support for BaseCombineDocumentsChain class (#41).
- Add support for ConditionalPromptSelector (#48).
- Add support for VectorStoreRetriever class (#45).
- Add support for MemoryVectorStore class (#44).
- Add support for VectorStore class (#36).
- Add support for OpenAIEmbeddings (#38).
- Add support for CharacterTextSplitter class (#39).
- Add support for OpenAI functions (#35).
- Add support for Calculator tool (#32).
- Add support for Tool class (#31).

## 0.0.1-dev.4

- Add support for LLMChain class (#20).
- Add support for ChatMessageHistory class (#29).
- Add support for ConversationBufferMemory class (#24).
- Add support for ConversationChain (#21).
- Add support for SimpleMemory class (#23).

## 0.0.1-dev.3

- Add support for ChatPromptTemplate class (#8).

## 0.0.1-dev.2

- Add support for LLMs - `BaseLLM` class (#14).
- Add support for Chat models - `BaseChatModel` class (#10).
- Add support for prompt templates - `PromptTemplate` class (#7).
- Publish LangChain.dart documentation on http://langchaindart.dev.

## 0.0.1-dev.1

- Bootstrap project.
