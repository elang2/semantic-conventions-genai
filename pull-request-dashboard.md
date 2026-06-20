> [!NOTE]
> Open non-draft PRs grouped by who is expected to act next. Draft PRs are listed separately. The grouping is partly performed by an LLM ([source](https://github.com/open-telemetry/semantic-conventions-genai/blob/main/.github/scripts/pull-request-dashboard/dashboard.py)) and could contain mistakes.
>
> Reviewers column: ✅ approved · ✔️ approved (non-code-owner) · 💬 open thread · 🔴 changes requested.

## Waiting on maintainers

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [Add `gen_ai.agent.finish_reason` attribute for agent loop termination (#238)](https://github.com/open-telemetry/semantic-conventions-genai/pull/238) | Nik-Reddy | aabmass&nbsp;✅<br>lmolkova&nbsp;🔴<br>MikeGoldsmith&nbsp;✅<br>trask | ✅ | ❌ | 6d |

## Waiting on reviewers

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [gen-ai: make input-messages BlobPart content optional and add stripped_reason (#144)](https://github.com/open-telemetry/semantic-conventions-genai/pull/144) | Mandark-droid | lmolkova<br>trask | ✅ | ❌ | 9d |
| [Add experimental GenAI context selection event (#190)](https://github.com/open-telemetry/semantic-conventions-genai/pull/190) | caioribeiroclw-pixel | trask | ❌ | ❌ | 7d |
| [gen-ai: model agent-to-agent handoff as execute_tool span (#98)](https://github.com/open-telemetry/semantic-conventions-genai/pull/98) | Krishnachaitanyakc | lmolkova<br>MikeGoldsmith&nbsp;✅<br>trask | ✅ | ❌ | 3d |
| [Add GenAI client metrics to the anthropic reference scenario (#283)](https://github.com/open-telemetry/semantic-conventions-genai/pull/283) | AgentGymLeader | JWinermaSplunk<br>MikeGoldsmith&nbsp;🔴 | ✅ | ✅ | 1d |
| [Clarify that gen_ai.invoke_agent.duration is about in-proc / internal span (#321)](https://github.com/open-telemetry/semantic-conventions-genai/pull/321) | lmolkova | trask&nbsp;✅ | ✅ | ❌ | 1d |
| [Add Agent Framework reference scenario (#325)](https://github.com/open-telemetry/semantic-conventions-genai/pull/325) | eavanvalkenburg |  | ✅ | ✅ | 1d |
| [Update dependency google-adk to v2 (#328)](https://github.com/open-telemetry/semantic-conventions-genai/pull/328) | app/renovate |  | ❌ | ✅ | 19h |
| [Add json-schema annotation for complex attributes, render boilerplate note in templates (#330)](https://github.com/open-telemetry/semantic-conventions-genai/pull/330) | lmolkova | trask&nbsp;✅ | ✅ | ✅ | 18h |
| [Generalize review guidance comment (#329)](https://github.com/open-telemetry/semantic-conventions-genai/pull/329) | trask |  | ✅ | ✅ | 18h |
| [Migrate anthropic reference scenario to opentelemetry-util-genai (#324)](https://github.com/open-telemetry/semantic-conventions-genai/pull/324) | AgentGymLeader |  | ✅ | ✅ | 17h |
| [Update dependency open-telemetry/weaver to v0.24.0 (#331)](https://github.com/open-telemetry/semantic-conventions-genai/pull/331) | app/renovate |  | ✅ | ✅ | 14h |

## Waiting on authors

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [Add gen_ai.server.inter_token_latency metric (#164)](https://github.com/open-telemetry/semantic-conventions-genai/pull/164) | Jwrede | Cirilla-zmh<br>lmolkova&nbsp;💬<br>trask | ✅ | ❌ | 32d |
| [gen-ai: add evaluation operation name and gen_ai.evaluate.internal span (#185)](https://github.com/open-telemetry/semantic-conventions-genai/pull/185) | hippoley | Cirilla-zmh&nbsp;💬<br>singankit&nbsp;💬 | ❌ | ✅ | 30d |
| [gen-ai: add gen_ai.response.id to deepeval evaluation result event (#184)](https://github.com/open-telemetry/semantic-conventions-genai/pull/184) | hippoley | lmolkova&nbsp;✅<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ✅ | 23d |
| [Add modality, cache, and phase breakdowns for token usage (#197)](https://github.com/open-telemetry/semantic-conventions-genai/pull/197) | trask | alexmojaki&nbsp;💬<br>lmolkova&nbsp;💬<br>Nik-Reddy&nbsp;💬 | ✅ | ❌ | 20d |
| [gen-ai: add optional byte_size to multimodal content parts (#143)](https://github.com/open-telemetry/semantic-conventions-genai/pull/143) | Mandark-droid | Cirilla-zmh<br>trask&nbsp;💬 | ✅ | ❌ | 18d |
| [Add gen_ai.invoke_agent.server span (SERVER kind) (#252)](https://github.com/open-telemetry/semantic-conventions-genai/pull/252) | singankit | Cirilla-zmh&nbsp;💬<br>trask | ✅ | ❌ | 15d |
| [Add gen_ai.agent.invocation.id attribute for invoke_agent spans (#250)](https://github.com/open-telemetry/semantic-conventions-genai/pull/250) | singankit | lmolkova&nbsp;💬<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ❌ | 9d |
| [Clarify scope of `gen_ai.client.operation.duration` metric (#215)](https://github.com/open-telemetry/semantic-conventions-genai/pull/215) | trask | lmolkova | ✅ | ❌ | 9d |
| [Add workflow node convention (#188)](https://github.com/open-telemetry/semantic-conventions-genai/pull/188) | RKest | aabmass<br>lmolkova&nbsp;🔴<br>trask | ✅ | ❌ | 9d |
| [Add gen_ai.agent.steps metric (#203)](https://github.com/open-telemetry/semantic-conventions-genai/pull/203) | pvlsirotkin | aabmass&nbsp;✅<br>lmolkova&nbsp;💬<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ❌ | 9d |
| [Add gen_ai.agent.input.content.size and gen_ai.agent.output.content.size metrics (#202)](https://github.com/open-telemetry/semantic-conventions-genai/pull/202) | pvlsirotkin | lmolkova&nbsp;💬<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ❌ | 9d |
| [chore: auto-regenerate outputs on SEMCONV_VERSION bumps via Renovate post-upgrade task (#290)](https://github.com/open-telemetry/semantic-conventions-genai/pull/290) | lmolkova | Copilot<br>lmolkova&nbsp;✔️<br>trask&nbsp;💬 | ✅ | ✅ | 6d |
| [gen-ai: add run guardrail span and security finding (#262)](https://github.com/open-telemetry/semantic-conventions-genai/pull/262) | nagkumar91 | aabmass<br>habibam&nbsp;✔️<br>trask | ✅ | ❌ | 4d |
| [Propose GenAI agent entity (#270)](https://github.com/open-telemetry/semantic-conventions-genai/pull/270) | aabmass | AgentGymLeader&nbsp;✔️<br>lmolkova&nbsp;✅<br>trask&nbsp;💬 | ✅ | ❌ | 2d |
| [proposal: agent.threat.detection.* attributes + event (closes #132) (#165)](https://github.com/open-telemetry/semantic-conventions-genai/pull/165) | eeee2345 |  | ✅ | ❌ | 2d |
| [semconv for a2a protocol (#195)](https://github.com/open-telemetry/semantic-conventions-genai/pull/195) | eternalcuriouslearner | aabmass<br>JWinermaSplunk<br>pwkowalski&nbsp;💬<br>trask | ✅ | ❌ | 2d |
| [Add prompt versioning and variable support to GenAI attributes (#179)](https://github.com/open-telemetry/semantic-conventions-genai/pull/179) | steverao | alexmojaki&nbsp;💬⁠✅<br>lmolkova&nbsp;✅<br>trask | ✅ | ❌ | 1d |
| [Align attributes between invoke_agent.internal and execute_tool spans and metrics (#322)](https://github.com/open-telemetry/semantic-conventions-genai/pull/322) | lmolkova | trask&nbsp;✅ | ✅ | ❌ | 19h |

## Waiting on external

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [Update dependency google-genai to v2 (#112)](https://github.com/open-telemetry/semantic-conventions-genai/pull/112) | app/renovate | lmolkova&nbsp;✅ | ❌ | ✅ | 31d |

## Draft pull requests

| PR | Author | Updated |
|---|---|:---:|
| [Add time_budget value for gen_ai.agent.finish_reason (#267)](https://github.com/open-telemetry/semantic-conventions-genai/pull/267) | Nik-Reddy | 9d |
| [genai: add `gen_ai.token.cache` and `gen_ai.token.reasoning` metric attributes (#96)](https://github.com/open-telemetry/semantic-conventions-genai/pull/96) | Nik-Reddy | 9d |
| [Scope PR dashboard Slack notifications (#282)](https://github.com/open-telemetry/semantic-conventions-genai/pull/282) | trask | 9d |
| [feat(gen-ai): add agent authorization observability attributes (#180) (#291)](https://github.com/open-telemetry/semantic-conventions-genai/pull/291) | thebenignhacker | 4d |

<details>
<summary>Diagnostics</summary>

```text
PR #330
llm: PRRT_kwDOSUeMrM6K7L7y -> none (The only comment is a purely social approval-style reaction with no requested follow-up, so no action is needed.)

PR #322
llm: PRRT_kwDOSUeMrM6Kth7r -> reviewer (The author has responded with an explanation for the proposed removal, so the ball is back with the reviewer to confirm or continue the review.)
llm: PRRT_kwDOSUeMrM6Ktirm -> reviewer (The only comment is from the PR author and reads like an unresolved observation about a bug, so the ball is with the reviewer to respond or confirm.)
llm: PRRT_kwDOSUeMrM6K6k6e -> author (A bot reviewer flagged that `gen_ai.tool.name` and `gen_ai.tool.type` should be set at span creation time, so the PR author needs to update the scenario accordingly.)
llm: PRRT_kwDOSUeMrM6K6k6l -> author (The bot raised a concrete fix request about providing sampling-relevant attributes at span creation time, and there’s no reply closing the thread, so the author needs to update the PR.)
llm: PRRT_kwDOSUeMrM6K6k6x -> author (Automation flagged that the span attributes must be set at creation time, so the PR author needs to update the scenario.)
llm: PRRT_kwDOSUeMrM6K6k6- -> author (The bot reviewer left a concrete fix request on the changelog fragment (single logical line and canonical `execute_tool` spelling), so the PR author needs to update it.)
llm: PRRT_kwDOSUeMrM6K6k7M -> author (The only comment is a bot review note flagging formatting issues in `model/gen-ai/spans.yaml`; it leaves the author with the next action to fix or respond.)
llm: PRRT_kwDOSUeMrM6K6k7R -> author (The latest comment is a bot review requesting updates to reference scenarios to pass sampling-relevant attributes at span creation, so the PR author needs to make that change.)

PR #290
llm: PRRT_kwDOSUeMrM6JXzS- -> author (Automation flags a real issue in `.github/renovate.json5` and requests a config change (`matchDepNames` or capturing `packageName`), so the PR author needs to update the PR.)
llm: PRRT_kwDOSUeMrM6J7Q-G -> author (Reviewer says this configuration only works on self-hosted Renovate and points to an alternative, so the PR author needs to change the config or respond.)

PR #283
llm: PRRT_kwDOSUeMrM6KQIPN -> reviewer (The author replied with a fix and asked whether `gen_ai.client.token.usage` should also include `error.type`, so the ball is back with the reviewer to confirm or request more changes.)
llm: pr-conversation -> reviewer (The author says all review comments are addressed and asks the reviewer for another look, with one remaining question about `error.type`.)

PR #270
llm: PRRT_kwDOSUeMrM6KX_pc -> author (A reviewer raised a naming concern and offered an alternative; the PR author needs to respond or adjust the model accordingly.)
llm: PRRT_kwDOSUeMrM6KYD9u -> author (A reviewer asked why the limitation exists and suggested rephrasing, so the author needs to जवाब/clarify and possibly update the wording.)

PR #262
llm: pr-conversation -> author (The latest reviewer comment offers to add worked examples but asks the author to choose whether to land them in the reference scenario or docs, so the author needs to respond.)

PR #252
llm: PRRT_kwDOSUeMrM6HO1Cy -> author (The latest comment is a reviewer bot requesting new reference scenario coverage and regenerated outputs, so the PR author needs to implement the requested changes.)
llm: PRRT_kwDOSUeMrM6IKVVh -> author (A reviewer left a suggestion with no follow-up reply yet, so the author needs to apply or respond to it.)
llm: pr-conversation -> author (The latest comment is a reviewer asking for clarification about span nesting, so the PR author needs to जवाब/respond or update the PR.)

PR #250
llm: PRRT_kwDOSUeMrM6HQjux -> reviewer (The author replied with a proposed interpretation and supporting example, so the thread is now waiting on the reviewer to confirm or push back.)
llm: pr-conversation -> author (The latest comment is a reviewer request to move the changelog entry into a Towncrier fragment and remove the direct CHANGELOG.md edit, so the PR author needs to act.)

PR #238
llm: pr-conversation -> reviewer (The author responded with a rework addressing the requested changes, so the ball is back with the reviewer to assess the update.)

PR #215
llm: PRRT_kwDOSUeMrM6Fl7mu -> none (The latest comment is a reviewer acknowledgement that the clarification is directionally aligned and does not ask for further action.)
llm: pr-conversation -> author (The latest and only comment is from the PR author asking to make a changelog-file change in this PR, so the author still needs to act.)

PR #203
llm: PRRT_kwDOSUeMrM6HGaQ9 -> reviewer (The author answered the question and clarified the note; the reviewer now needs to confirm or close the thread.)
llm: PRRT_kwDOSUeMrM6IqQGv -> author (The latest comment is from the reviewer/approver and raises substantive concerns about the proposed metric generalization, so the author needs to respond or revise the PR.)
llm: pr-conversation -> reviewer (The author’s last comment is a status update that says open review threads still need follow-up, so the ball is back with the reviewer/maintainer side.)

PR #202
llm: PRRT_kwDOSUeMrM6Is_Ar -> author (A reviewer suggested a concrete model change and nothing in the thread indicates it was addressed, so the PR author needs to respond or update the PR.)
llm: PRRT_kwDOSUeMrM6ItCxM -> author (The last comment is a reviewer asking for a wording change, so the PR author needs to revise the description and reply.)
llm: PRRT_kwDOSUeMrM6ItDZZ -> author (The latest comment is from a reviewer asking to remove justification text from the spec, so the PR author needs to update or respond.)
llm: pr-conversation -> author (The latest comment is from the PR author and says there are still open review threads that need follow-up in this PR, so the author side still has work to do.)

PR #197
llm: PRRT_kwDOSUeMrM6E-Ear -> reviewer (The reviewer asked whether to add an embeddings token metric, and the author replied with a preferred metric name and pointed to the change they made; the ball is back with the reviewer to confirm/close the thread.)
llm: PRRT_kwDOSUeMrM6FkB2H -> author (The reviewer’s last comment provided follow-up details and left the question open; the ball is back with the author to respond or decide whether to change the schema.)
llm: PRRT_kwDOSUeMrM6F1og7 -> author (The latest comment is from a reviewer and ends with a deferred suggestion about future work, so the ball is with the author to respond or follow up.)
llm: PRRT_kwDOSUeMrM6F1nUT -> author (The latest comment is from a reviewer/approver asking a design question about token phase handling, so the PR author needs to जवाब/decide and respond.)
llm: PRRT_kwDOSUeMrM6HcJqe -> author (A reviewer suggested a breaking rename approach and there’s no author reply yet, so the PR author needs to respond or update the change.)
llm: PRRT_kwDOSUeMrM6HcSsx -> author (A reviewer asked whether the spec should use a template or complex object instead of enumerating combinations, so the PR author needs to respond or adjust the design.)
llm: PRRT_kwDOSUeMrM6HckTh -> author (The latest comment is from a reviewer/approver and raises a substantive design concern/suggestion, so the PR author needs to respond or adjust the implementation.)
llm: PRRT_kwDOSUeMrM6HcoWo -> author (A reviewer asked whether span attributes and metrics should be in the same PR, so the author needs to जवाब/confirm the scope.)
llm: pr-conversation -> reviewer (The latest comment is from the author-role participant and asks for a changelog move, so the ball is with the reviewer/maintainer to review the update.)

PR #195
llm: PRRT_kwDOSUeMrM6KRsU9 -> author (A reviewer asked for clarification and a concrete change to the model description/status logic; the author needs to respond or update the PR.)

PR #190
llm: pr-conversation -> reviewer (The author addressed the reviewer’s Towncrier request and reported the changelog move as done, so the ball is back with the reviewer to check and close the thread.)

PR #188
llm: PRRT_kwDOSUeMrM6EP5P6 -> reviewer (The author answered the reviewer’s question with concrete instrumentation sources and an example trace, so the ball is back with the reviewer to confirm or continue the review.)
llm: PRRT_kwDOSUeMrM6H_pco -> author (The author’s latest reply is a self-deferral: they acknowledge the concern but say the exact wording will be handled in another PR, so follow-up work is still on the author side.)
llm: PRRT_kwDOSUeMrM6KiI8p -> author (The bot reviewer says the `invoke_node` span is empty and should contain validation logic, so the PR author needs to update the scenario.)
llm: PRRT_kwDOSUeMrM6KiI9k -> author (The latest comment is a review bot flagging a mismatch in the report data, so the PR author needs to update the scenario/report or respond to the inconsistency.)
llm: pr-conversation -> author (A reviewer asked the PR author to move the changelog entry into a Towncrier fragment and remove the direct `CHANGELOG.md` edit, so the author needs to act.)

PR #185
llm: PRRT_kwDOSUeMrM6DuuPn -> author (The only comment is a reviewer bot request for a terminology alignment change, so the PR author needs to respond or update the spec.)
llm: PRRT_kwDOSUeMrM6E_Amb -> author (A reviewer asked for a wording fix (“we need a verb here”), so the author needs to update the PR.)
llm: PRRT_kwDOSUeMrM6E_COY -> author (The reviewer asked for clarification and a prototype, so the PR author needs to जवाब/act next.)
llm: PRRT_kwDOSUeMrM6HOBHP -> author (A reviewer/approver raised a substantive concern and there is no author reply yet, so the PR author needs to address it.)
llm: PRRT_kwDOSUeMrM6HOBik -> author (The latest comment is a reviewer request to apply the same feedback to another attribute, so the PR author needs to update or जवाब back.)
llm: pr-conversation -> author (A reviewer asked for clarification and no author reply has been made, so the author needs to respond.)

PR #184
llm: pr-conversation -> author (A reviewer requested changes and there is no author follow-up, so the PR author needs to respond and update the branch.)

PR #179
llm: PRRT_kwDOSUeMrM6Kz7CF -> author (The only comment is a reviewer note flagging that the prompt template feature is deprecated, so the author needs to respond or update the PR.)

PR #165
llm: PRRT_kwDOSUeMrM6KdZA7 -> author (The latest comment is a bot review note flagging missing changelog and reference scenario updates, so the PR author needs to act.)
llm: PRRT_kwDOSUeMrM6KdZBh -> author (The bot flagged a mismatch between the PR description and committed generated artifacts, so the PR author needs to update the description or adjust the artifacts.)

PR #164
llm: PRRT_kwDOSUeMrM6C-3Kb -> author (A reviewer asked for clarification and questioned the need for a new metric, so the PR author needs to जवाब/respond or update the PR.)
llm: pr-conversation -> author (The latest comment is from an approver requesting the author to move the changelog entry into a Towncrier fragment and remove the direct CHANGELOG.md edit.)

PR #144
llm: pr-conversation -> reviewer (The latest comment is from the PR author and answers the review thread, so the ball is back with the reviewer/maintainer to respond or decide the remaining open points.)

PR #143
llm: PRRT_kwDOSUeMrM6F1Aqk -> none (The latest reviewer comment is just an acknowledgment/realization about #144 and does not request any follow-up, so this thread appears closed.)
llm: PRRT_kwDOSUeMrM6F0-FD -> author (The latest comment from the reviewer asks the author to add reference scenarios for FilePart and UriPart, so the author needs to act next.)
llm: pr-conversation -> reviewer (The author replied that the requested changelog move is done and the PR was rebased; the ball is back with the reviewer to confirm or continue review.)

PR #112
llm: pr-conversation -> external (The reviewer says the change cannot work until google-adk relaxes its google-genai dependency and is bumped, so the thread is blocked on an upstream release outside this repository.)

```

</details>

_Approvers may [force a refresh](https://github.com/open-telemetry/semantic-conventions-genai/actions/workflows/pull-request-dashboard.yml)._

