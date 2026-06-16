> [!NOTE]
> Open non-draft PRs grouped by who is expected to act next. Draft PRs are listed separately. The grouping is partly performed by an LLM ([source](https://github.com/open-telemetry/semantic-conventions-genai/blob/main/.github/scripts/pull-request-dashboard/dashboard.py)) and could contain mistakes.
>
> Reviewers column: ✅ approved · ✔️ approved (non-code-owner) · 💬 open thread · 🔴 changes requested.

## Waiting on maintainers

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [Add `gen_ai.agent.finish_reason` attribute for agent loop termination (#238)](https://github.com/open-telemetry/semantic-conventions-genai/pull/238) | Nik-Reddy | aabmass&nbsp;✅<br>lmolkova&nbsp;🔴<br>MikeGoldsmith&nbsp;✅<br>trask | ✅ | ✅ | 1d |

## Waiting on reviewers

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [Update dependency google-adk to v2 (#173)](https://github.com/open-telemetry/semantic-conventions-genai/pull/173) | app/renovate | MikeGoldsmith | ❌ | ✅ | 27d |
| [gen-ai: make input-messages BlobPart content optional and add stripped_reason (#144)](https://github.com/open-telemetry/semantic-conventions-genai/pull/144) | Mandark-droid | lmolkova<br>trask | ✅ | ✅ | 5d |
| [gen-ai: model agent-to-agent handoff as execute_tool span (#98)](https://github.com/open-telemetry/semantic-conventions-genai/pull/98) | Krishnachaitanyakc | lmolkova<br>MikeGoldsmith&nbsp;✅<br>trask | ✅ | ❌ | 5d |
| [Limit supported  part types  on `gen_ai.system_instructions` to text only (#257)](https://github.com/open-telemetry/semantic-conventions-genai/pull/257) | lmolkova | MikeGoldsmith&nbsp;✅<br>trask | ✅ | ✅ | 3d |
| [Add experimental GenAI context selection event (#190)](https://github.com/open-telemetry/semantic-conventions-genai/pull/190) | caioribeiroclw-pixel | trask | ❌ | ❌ | 2d |
| [Remove gen_ai.provider.name from internal agent spans (#289)](https://github.com/open-telemetry/semantic-conventions-genai/pull/289) | lmolkova | JWinermaSplunk | ✅ | ❌ | 2d |
| [Add `gen_ai.request.reasoning.level` attribute (#258)](https://github.com/open-telemetry/semantic-conventions-genai/pull/258) | katsuhisa91 | JWinermaSplunk&nbsp;✅<br>lmolkova<br>trask | ✅ | ✅ | 1d |
| [Add prompt versioning and variable support to GenAI attributes (#179)](https://github.com/open-telemetry/semantic-conventions-genai/pull/179) | steverao | lmolkova<br>trask | ✅ | ✅ | 20h |
| [Add GenAI client metrics to the anthropic reference scenario (#283)](https://github.com/open-telemetry/semantic-conventions-genai/pull/283) | AgentGymLeader |  | ✅ | ✅ | 11h |
| [semconv for a2a protocol (#195)](https://github.com/open-telemetry/semantic-conventions-genai/pull/195) | eternalcuriouslearner | aabmass<br>JWinermaSplunk<br>trask | ✅ | ✅ | 3h |
| [Bump the python-security group across 6 directories with 2 updates (#293)](https://github.com/open-telemetry/semantic-conventions-genai/pull/293) | app/dependabot |  | ✅ | ✅ | 1h |

## Waiting on authors

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [Add gen_ai.server.inter_token_latency metric (#164)](https://github.com/open-telemetry/semantic-conventions-genai/pull/164) | Jwrede | Cirilla-zmh<br>lmolkova&nbsp;💬<br>trask | ✅ | ❌ | 28d |
| [gen-ai: add evaluation operation name and gen_ai.evaluate.internal span (#185)](https://github.com/open-telemetry/semantic-conventions-genai/pull/185) | hippoley | Cirilla-zmh&nbsp;💬<br>Copilot&nbsp;💬<br>singankit&nbsp;💬 | ❌ | ✅ | 25d |
| [gen-ai: add gen_ai.response.id to deepeval evaluation result event (#184)](https://github.com/open-telemetry/semantic-conventions-genai/pull/184) | hippoley | lmolkova&nbsp;✅<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ✅ | 18d |
| [gen-ai: add optional byte_size to multimodal content parts (#143)](https://github.com/open-telemetry/semantic-conventions-genai/pull/143) | Mandark-droid | Cirilla-zmh<br>trask&nbsp;💬 | ✅ | ✅ | 17d |
| [Add modality, cache, and phase breakdowns for token usage (#197)](https://github.com/open-telemetry/semantic-conventions-genai/pull/197) | trask | alexmojaki&nbsp;💬<br>lmolkova&nbsp;💬<br>Nik-Reddy&nbsp;💬 | ✅ | ❌ | 16d |
| [Add gen_ai.invoke_agent.server span (SERVER kind) (#252)](https://github.com/open-telemetry/semantic-conventions-genai/pull/252) | singankit | Cirilla-zmh&nbsp;💬<br>Copilot&nbsp;💬<br>trask | ✅ | ❌ | 11d |
| [Add gen_ai.agent.invocation.id attribute for invoke_agent spans (#250)](https://github.com/open-telemetry/semantic-conventions-genai/pull/250) | singankit | lmolkova&nbsp;💬<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ❌ | 5d |
| [Clarify scope of `gen_ai.client.operation.duration` metric (#215)](https://github.com/open-telemetry/semantic-conventions-genai/pull/215) | trask | lmolkova | ✅ | ❌ | 5d |
| [Add workflow node convention (#188)](https://github.com/open-telemetry/semantic-conventions-genai/pull/188) | RKest | aabmass<br>lmolkova&nbsp;🔴<br>trask | ✅ | ❌ | 5d |
| [semconv for compaction (#162)](https://github.com/open-telemetry/semantic-conventions-genai/pull/162) | eternalcuriouslearner | JWinermaSplunk&nbsp;✅<br>lmolkova&nbsp;✅<br>trask | ✅ | ❌ | 5d |
| [Add gen_ai.workflow.steps metric (#203)](https://github.com/open-telemetry/semantic-conventions-genai/pull/203) | pvlsirotkin | aabmass&nbsp;✅<br>lmolkova&nbsp;💬<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ❌ | 5d |
| [Add gen_ai.agent.request.size and gen_ai.agent.response.size metrics (#202)](https://github.com/open-telemetry/semantic-conventions-genai/pull/202) | pvlsirotkin | lmolkova&nbsp;💬<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ❌ | 4d |
| [Add gen_ai.agent.invocation.duration and gen_ai.tool.execution.duration metrics (#201)](https://github.com/open-telemetry/semantic-conventions-genai/pull/201) | pvlsirotkin | lmolkova&nbsp;💬⁠✅<br>MikeGoldsmith&nbsp;🔴<br>trask | ✅ | ✅ | 4d |
| [chore: auto-regenerate outputs on SEMCONV_VERSION bumps via Renovate post-upgrade task (#290)](https://github.com/open-telemetry/semantic-conventions-genai/pull/290) | web-flow | Copilot<br>Copilot&nbsp;💬<br>lmolkova&nbsp;✅ | ✅ | ✅ | 2d |
| [Propose GenAI agent entity (#270)](https://github.com/open-telemetry/semantic-conventions-genai/pull/270) | aabmass | lmolkova&nbsp;💬⁠✅<br>trask&nbsp;💬 | ✅ | ❌ | 1d |
| [gen-ai: add run guardrail span and security finding (#262)](https://github.com/open-telemetry/semantic-conventions-genai/pull/262) | nagkumar91 | aabmass<br>trask | ✅ | ✅ | 12h |

## Waiting on external

| PR | Author | Reviewers | CI | Conflicts | Age |
|---|---|---|:---:|:---:|:---:|
| [Update dependency google-genai to v2 (#112)](https://github.com/open-telemetry/semantic-conventions-genai/pull/112) | app/renovate | lmolkova&nbsp;✅ | ❌ | ✅ | 27d |

## Draft pull requests

| PR | Author | Updated |
|---|---|:---:|
| [proposal: agent.threat.detection.* attributes + event (closes #132) (#165)](https://github.com/open-telemetry/semantic-conventions-genai/pull/165) | eeee2345 | 24d |
| [Add time_budget value for gen_ai.agent.finish_reason (#267)](https://github.com/open-telemetry/semantic-conventions-genai/pull/267) | Nik-Reddy | 5d |
| [genai: add `gen_ai.token.cache` and `gen_ai.token.reasoning` metric attributes (#96)](https://github.com/open-telemetry/semantic-conventions-genai/pull/96) | Nik-Reddy | 5d |
| [Scope PR dashboard Slack notifications (#282)](https://github.com/open-telemetry/semantic-conventions-genai/pull/282) | trask | 5d |
| [feat(gen-ai): add agent authorization observability attributes (#180) (#291)](https://github.com/open-telemetry/semantic-conventions-genai/pull/291) | thebenignhacker | 8h |

<details>
<summary>Diagnostics</summary>

```text
PR #290
llm: PRRT_kwDOSUeMrM6JXzS- -> author (The latest comment is a reviewer request to change `.github/renovate.json5` so Renovate matches the custom regex correctly; the PR author needs to implement or respond.)

PR #289
llm: PRRT_kwDOSUeMrM6JXu8q -> reviewer (The author’s comment appears to be a review note on what should change, and the thread has no follow-up reply yet, so the reviewer/maintainer needs to respond or act next.)

PR #270
llm: PRRT_kwDOSUeMrM6I6cGM -> reviewer (The latest comment is from the author and proposes two paths forward after offline discussion, so the ball is back with the reviewer to react/choose.)
llm: pr-conversation -> author (A reviewer requested a concrete doc change and no author reply followed, so the PR author needs to respond or implement the clarification.)

PR #262
llm: pr-conversation -> author (The latest comment is from a reviewer proposing worked examples and asking whether to add them to the reference scenario or a doc example, so the author needs to respond/choose the next step.)

PR #258
llm: pr-conversation -> reviewer (The author’s latest update says all CI checks pass and the PR is ready for review, so the ball is with the reviewer.)

PR #257
llm: pr-conversation -> reviewer (The latest comment is from the author responding to the review point, so the ball is back with the reviewer to acknowledge or continue the discussion.)

PR #252
llm: PRRT_kwDOSUeMrM6HO1Cy -> author (Reviewer asked for additional reference scenario coverage and regenerated outputs; the author needs to implement and respond.)
llm: PRRT_kwDOSUeMrM6IKVVh -> author (A reviewer left a suggestion with no follow-up reply yet, so the author needs to apply or respond to it.)
llm: pr-conversation -> author (The latest comment is a reviewer asking for clarification about span nesting, so the PR author needs to जवाब/respond or update the PR.)

PR #250
llm: PRRT_kwDOSUeMrM6HQjux -> reviewer (The author replied with a proposed interpretation and supporting example, so the thread is now waiting on the reviewer to confirm or push back.)
llm: pr-conversation -> author (The latest comment is a reviewer request to move the changelog entry into a Towncrier fragment and remove the direct CHANGELOG.md edit, so the PR author needs to act.)

PR #238
llm: pr-conversation -> reviewer (The author addressed the requested changes and explained the rework; the reviewer now needs to re-review or respond.)

PR #215
llm: PRRT_kwDOSUeMrM6Fl7mu -> none (The latest comment is a reviewer acknowledgement that the clarification is directionally aligned and does not ask for further action.)
llm: pr-conversation -> author (The latest and only comment is from the PR author asking to make a changelog-file change in this PR, so the author still needs to act.)

PR #203
llm: PRRT_kwDOSUeMrM6HGVHV -> reviewer (The author answered by saying they moved the recommendation into the YAML note, so the next step is for the reviewer to confirm or close the thread.)
llm: PRRT_kwDOSUeMrM6HGVko -> reviewer (The reviewer asked for an `attributes.gen_ai.error` reference, and the author replied "Added."; the ball is now with the reviewer to confirm/resolve.)
llm: PRRT_kwDOSUeMrM6HGaQ9 -> reviewer (The author answered the question and clarified the note; the reviewer now needs to confirm or close the thread.)
llm: PRRT_kwDOSUeMrM6IqQGv -> author (The latest comment is from the reviewer/approver and raises substantive concerns about the proposed metric generalization, so the author needs to respond or revise the PR.)

PR #202
llm: PRRT_kwDOSUeMrM6HFBTV -> reviewer (The author has replied with a decision and rationale, so the ball is back with the reviewer to accept it, push back, or resolve the thread.)
llm: PRRT_kwDOSUeMrM6Is_Ar -> author (A reviewer suggested a concrete model change and nothing in the thread indicates it was addressed, so the PR author needs to respond or update the PR.)
llm: PRRT_kwDOSUeMrM6ItCxM -> author (The last comment is a reviewer asking for a wording change, so the PR author needs to revise the description and reply.)
llm: PRRT_kwDOSUeMrM6ItDZZ -> author (The latest comment is from a reviewer asking to remove justification text from the spec, so the PR author needs to update or respond.)

PR #201
llm: PRRT_kwDOSUeMrM6FY1gg -> reviewer (The author confirmed they kept the existing `conditionally_required` level and made the requested capitalization fix, so the thread is back with the reviewer for any final acknowledgment or resolution.)
llm: PRRT_kwDOSUeMrM6I26yL -> author (A reviewer left a non-social note about a needed change if #270 lands first, so the author should acknowledge or act on it.)
llm: PRRT_kwDOSUeMrM6I27Y- -> author (The reviewer asked the PR author to update the PR title and description, so the next action is on the author.)
llm: PRRT_kwDOSUeMrM6Iouwr -> author (The latest reviewer comment disagrees with the author’s rationale and proposes keeping both attributes, so the author needs to respond or update the metric dimensions.)

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
llm: pr-conversation -> reviewer (The author’s latest reply says they removed the disputed metric and asks for another look, so the next action is on the reviewer to re-review.)

PR #190
llm: pr-conversation -> reviewer (The author addressed the reviewer’s Towncrier request and reported the changelog move as done, so the ball is back with the reviewer to check and close the thread.)

PR #188
llm: PRRT_kwDOSUeMrM6EP5P6 -> reviewer (The author answered the reviewer’s question with concrete instrumentation sources and an example trace, so the ball is back with the reviewer to confirm or continue the review.)
llm: PRRT_kwDOSUeMrM6H_pco -> author (The author’s latest reply is a self-deferral: they acknowledge the concern but say the exact wording will be handled in another PR, so follow-up work is still on the author side.)
llm: pr-conversation -> author (A reviewer asked the PR author to move the changelog entry into a Towncrier fragment and remove the direct `CHANGELOG.md` edit, so the author needs to act.)

PR #185
llm: PRRT_kwDOSUeMrM6DuuPn -> author (The latest comment is a reviewer request to align the span naming/operation terminology, so the PR author needs to respond or make the change.)
llm: PRRT_kwDOSUeMrM6E_Amb -> author (A reviewer asked for a wording fix (“we need a verb here”), so the author needs to update the PR.)
llm: PRRT_kwDOSUeMrM6E_COY -> author (The reviewer asked for clarification and a prototype, so the PR author needs to जवाब/act next.)
llm: PRRT_kwDOSUeMrM6HOBHP -> author (A reviewer/approver raised a substantive concern and there is no author reply yet, so the PR author needs to address it.)
llm: PRRT_kwDOSUeMrM6HOBik -> author (The latest comment is a reviewer request to apply the same feedback to another attribute, so the PR author needs to update or जवाब back.)
llm: pr-conversation -> author (A reviewer asked for clarification and no author reply has been made, so the author needs to respond.)

PR #184
llm: pr-conversation -> author (A reviewer requested changes and there is no author follow-up, so the PR author needs to respond and update the branch.)

PR #173
llm: pr-conversation -> author (The reviewer identified a CI snapshot mismatch and explicitly said investigation is needed before landing, so the PR author needs to act on the scenario/update.)

PR #164
llm: PRRT_kwDOSUeMrM6C-3Kb -> author (A reviewer asked for clarification and questioned the need for a new metric, so the PR author needs to जवाब/respond or update the PR.)
llm: pr-conversation -> author (The latest comment is from an approver requesting the author to move the changelog entry into a Towncrier fragment and remove the direct CHANGELOG.md edit.)

PR #162
llm: pr-conversation -> author (The reviewer asked the PR author to move the changelog entry into a Towncrier fragment and remove the direct `CHANGELOG.md` edit, so the author still needs to act.)

PR #144
llm: pr-conversation -> reviewer (The author’s latest comment is a reply that leaves the choice open and asks maintainers to decide between approaches, so the next action is on the reviewer/maintainer side.)

PR #143
llm: PRRT_kwDOSUeMrM6F1Aqk -> author (The latest comment is from a reviewer and adds a follow-up point about #144; by the thread heuristic, the author still needs to respond or act unless the reviewer clearly closes it, which they didn’t.)
llm: PRRT_kwDOSUeMrM6F0-FD -> author (The latest comment is a reviewer request to add reference scenarios for FilePart and UriPart, so the PR author needs to act.)
llm: pr-conversation -> reviewer (The author’s latest comment says the requested changelog fix is done and the PR was rebased, so the ball is back with the reviewer to confirm or continue review.)

PR #112
llm: pr-conversation -> external (The reviewer says the change cannot work until google-adk relaxes its google-genai dependency and is bumped, so the thread is blocked on an upstream release outside this repository.)

PR #98
llm: pr-conversation -> reviewer (The author replied that the changelog was updated as requested, so the ball is back with the reviewer to verify and close the thread.)

```

</details>

_Approvers may [force a refresh](https://github.com/open-telemetry/semantic-conventions-genai/actions/workflows/pull-request-dashboard.yml)._

