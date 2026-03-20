# Source Image Map

Tracks which source screenshots map to which component images.
Each component gets its own copy so you can independently crop/annotate.

---

## claude-web-empty-state.png
- **Source**: Mobbin — Claude Web, highlighted screen
- **Resolution**: 3024 × 1890
- **Mobbin URL**: `https://mobbin.com/screens/62dfb8b8-3b30-4bdf-ad13-0ff594a77f1e`
- **CDN URL**: `https://bytescale.mobbin.com/FW25bBB/image/mobbin.com/prod/content/app_screens/ed5d4b26-2bb7-4db3-a6b0-9a1560624cd1.png`
- **What it shows**: Claude's new chat empty state — sidebar nav, input field, model selector, suggestion chips, greeting
- **Components covered** (8 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `01-new-chat-entry-point.png` | New chat entry point | Top-left sidebar: "New chat" button |
  | `01-chat-history-sidebar.png` | Chat history sidebar | Left sidebar: Chats, Projects, Artifacts, Recents |
  | `02-auto-resizing-text-field.png` | Auto-resizing text field | Center: "How can I help you today?" input |
  | `02-send-button.png` | Send button | Input bar: orange arrow button (right) |
  | `02-model-selector.png` | Model selector | Input bar: "Sonnet 4 ▾" dropdown |
  | `05-empty-state-suggestion-cards.png` | Empty-state suggestion cards | Gemini: "What's on your mind today?" with Guided learning suggestions |
  | `08-collapsible-sidebar.png` | Collapsible sidebar | Full left sidebar structure |
  | `15-welcome-empty-state.png` | Welcome/empty state | Full page: "What's new, Sam?" + all elements |

---

## claude-web-screen-2.png
- **Source**: Mobbin — Claude Web, screen 2 of 12
- **What it shows**: Active conversation with artifact preview panel (CodePet interactive app). Split-pane layout with chat on left, live artifact preview on right.
- **Components covered** (5 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `03-artifact-canvas-panel.png` | Artifact/canvas panel | Right pane: CodePet artifact preview |
  | `08-split-pane-chat-artifact.png` | Split-pane (chat + artifact) | Full page: left chat + right artifact |
  | `03-user-assistant-message-bubbles.png` | User/assistant message bubbles | Left pane: conversation messages |
  | `03-markdown-rendering.png` | Markdown rendering | Left pane: formatted AI response text |
  | `10-interactive-live-preview.png` | Interactive live preview | Right pane: rendered interactive artifact |

---

## claude-web-screen-3.png
- **Source**: Mobbin — Claude Web, screen 3 of 12
- **What it shows**: Conversation with artifact code view open (HTML/CSS source). Code tab selected in artifact panel.
- **Components covered** (3 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `03-code-blocks-with-syntax-highlighting.png` | Code blocks with syntax highlighting | Right pane: syntax-highlighted HTML/CSS |
  | `03-copy-button-on-code-blocks.png` | Copy button on code blocks | Right pane: copy button in code view |
  | `03-code-block-action-buttons.png` | Code block action buttons | Right pane: action buttons above code |

---

## claude-web-screen-4.png
- **Source**: Mobbin — Claude Web, screen 4 of 12
- **What it shows**: AI response with clarifying follow-up questions, action bar with thumbs up/down, copy, retry buttons.
- **Components covered** (5 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `06-thumbs-up-down.png` | Thumbs up/down | Below response: thumbs icons |
  | `06-regenerate-response.png` | Regenerate response | Below response: retry/regenerate button |
  | `06-copy-full-response.png` | Copy full response | Below response: copy button |
  | `05-clarifying-questions.png` | Clarifying questions | Response content: follow-up questions from AI |
  | `06-edit-and-resubmit.png` | Edit and resubmit | User message: edit pencil icon |

---

## claude-web-screen-5.png
- **Source**: Mobbin — Claude Web, screen 5 of 12
- **What it shows**: Chat history page — "Your chat history" with search bar, list of conversations with timestamps and previews.
- **Components covered** (4 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `01-search-past-conversations.png` | Search past conversations | Top: search bar |
  | `01-auto-manual-rename.png` | Auto/manual rename | Chat list: conversation titles |
  | `01-resume-conversation.png` | Resume conversation | Chat list: clickable conversation rows |
  | `01-delete-archive-chat.png` | Delete/archive chat | Chat list: context menu actions |

---

## claude-web-screen-6.png
- **Source**: Mobbin — Claude Web, screen 6 of 12
- **What it shows**: Projects page with project cards showing descriptions and conversation counts.
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `01-projects-workspaces.png` | Projects/workspaces | Full page: project cards grid |

---

## claude-web-screen-8.png
- **Source**: Mobbin — Claude Web, screen 8 of 12
- **What it shows**: Artifact detail page (Flashcards) with "Customize" button, starting prompt, about section — functions as a conversation template/preset.
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `01-conversation-templates-presets.png` | Conversation templates/presets | Full page: artifact as reusable template |

---

## claude-web-screen-7.png (no components mapped)
- **Source**: Mobbin — Claude Web, screen 7 of 12
- **What it shows**: Artifacts gallery — grid of artifact thumbnails. No direct pending component match but available for future use.

## claude-web-screen-9.png through 12.png (login/signup — skipped)
- **Source**: Mobbin — Claude Web, screens 9-12
- **What it shows**: Login, email verification, account creation flows. Not relevant to chat primitives.

---

## chatgpt-web-screen-1.png
- **Source**: Mobbin — ChatGPT Web, screen 1 of 12
- **Resolution**: ~3024 × 1890
- **What it shows**: Empty state — "What can I help with?" greeting, left sidebar (ChatGPT, Sora, Library, Explore GPTs), input bar with Search/Reason/Deep Research/Create Image mode buttons, suggestion chips, mic/voice button
- **Components covered** (4 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `01-modes-agents.png` | Modes/agents | Input bar: Search, Reason, Deep Research, Create Image buttons |
  | `02-voice-input.png` | Voice input | Input bar: microphone button (right side) |
  | `08-full-page-chat-view.png` | Full-page chat view | Full page: sidebar + center input + suggestions |
  | `15-capability-list-what-can-i-do.png` | Capability list / "What can I do?" | Below input: suggestion chips (Write, Browse, Code, etc.) |

---

## chatgpt-web-screen-2.png
- **Source**: Mobbin — ChatGPT Web, screen 2 of 12
- **What it shows**: Active conversation with code block (HTML/CSS), syntax highlighting, Copy/Edit buttons on code block, sidebar with chat history
- **Components covered** (2 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `04-blinking-cursor-caret.png` | Blinking cursor/caret | Conversation: generation cursor indicator |
  | `04-token-by-token-streaming.png` | Token-by-token streaming | Conversation: text streaming in progress |

---

## chatgpt-web-screen-3.png
- **Source**: Mobbin — ChatGPT Web, screen 3 of 12
- **What it shows**: Image generation — "Create image related family picnic" with AI-generated image displayed inline in conversation
- **Components covered** (2 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `10-image-generation.png` | Image generation | Conversation: AI-generated picnic image |
  | `03-inline-image-display.png` | Inline image display | Conversation: image rendered inline |

---

## chatgpt-web-screen-4.png
- **Source**: Mobbin — ChatGPT Web, screen 4 of 12
- **What it shows**: Canvas mode — split pane with conversation on left, "Picnic Itinerary" editable document on right, "Write or code" input at bottom
- **Components covered** (2 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `06-inline-refinement-magic-highlight.png` | Inline refinement ("Magic Highlight") | Right pane: editable Canvas document |
  | `06-inline-iteration-controls.png` | Inline iteration controls | Right pane: Canvas editing controls |

---

## chatgpt-web-screen-5.png
- **Source**: Mobbin — ChatGPT Web, screen 5 of 12
- **What it shows**: GPT Store — "Explore GPTs" page with search, categories (Top Picks, Writing, Productivity), Featured GPTs (SciSpace, Wolfram, etc.), "My GPTs" + "+ Create" buttons
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `05-prompt-library-templates.png` | Prompt library/templates | Full page: GPT Store as template marketplace |

---

## chatgpt-web-screen-6.png
- **Source**: Mobbin — ChatGPT Web, screen 6 of 12
- **What it shows**: Custom GPT detail modal — "Journalist Pro" with conversation starters, capabilities list, ratings, "Start Chat" button
- **Components covered** (2 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `15-capability-discovery.png` | Capability discovery | Modal: capabilities list + conversation starters |
  | `15-sample-conversation-gallery.png` | Sample conversation gallery | Modal: conversation starter prompts |

---

## chatgpt-web-screen-7.png
- **Source**: Mobbin — ChatGPT Web, screen 7 of 12
- **What it shows**: Projects view — "Holiday" project with "New chat in this project", Project files, Instructions cards
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `07-file-document-context.png` | File/document context | Full page: project files and instructions |

---

## chatgpt-web-screen-8.png through 12.png (pricing/login — skipped)
- **Source**: Mobbin — ChatGPT Web, screens 8-12
- **What it shows**: Pricing modal (Free/Plus/Pro), OpenAI landing page, login/signup flows. Not relevant to chat primitives.

---

## perplexity-web-screen-1.png
- **Source**: Mobbin — Perplexity Web, screen 1 of 10
- **What it shows**: Empty state — "perplexity pro" branding, "Ask anything. Type @ for mentions." input bar, mode buttons (Search, Deep Research, Labs), suggestion chips (Finance, Analyze, Fact Check, Sports, Summarize), sidebar (Library, Discover, Spaces, Finance, More), Comet Assistant promo
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `02-mention-context-references.png` | @-mention context references | Input bar: "Type @ for mentions" text |

---

## perplexity-web-screen-2.png
- **Source**: Mobbin — Perplexity Web, screen 2 of 10
- **What it shows**: Answer view with "20 sources" panel open — source cards with favicons/titles/snippets, table in answer body, "Related" follow-up questions (5 items), action bar (share, copy, rewrite, sources)
- **Components covered** (4 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `03-inline-citations.png` | Inline citations | Answer text: superscript numbered citations [1][2][3] |
  | `14-source-attribution-citations.png` | Source attribution/citations | Right panel: "20 sources" card list with favicons |
  | `05-follow-up-suggestion-chips.png` | Follow-up suggestion chips | Below answer: "Related" questions (5 items) |
  | `03-tables.png` | Tables | Answer body: rendered data table |

---

## perplexity-web-screen-3.png (no components mapped)
- **Source**: Mobbin — Perplexity Web, screen 3 of 10
- **What it shows**: Library page — Threads/Pages/Media/Apps tabs, search bar, conversation list with previews and timestamps, "Sort: Newest" dropdown, "Labs" tags. Available for future use.

## perplexity-web-screen-4.png (no components mapped)
- **Source**: Mobbin — Perplexity Web, screen 4 of 10
- **What it shows**: Discover page — news feed layout, "For You/Top/Topics" tabs, interest picker, stock market data sidebar. Available for future use.

## perplexity-web-screen-5.png
- **Source**: Mobbin — Perplexity Web, screen 5 of 10
- **What it shows**: Spaces — "Market Pulse - Daily Stock Insights" space with description, custom instructions indicator, "4 sources", input bar, "My threads" list
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `12-team-shared-workspaces.png` | Team/shared workspaces | Full page: Perplexity Space with threads and instructions |

---

## perplexity-web-screen-6.png
- **Source**: Mobbin — Perplexity Web, screen 6 of 10
- **What it shows**: Finance — NVIDIA Corporation stock page with interactive chart, data table, watchlist, "Latest Price Movement" section, "Ask anything about NVIDIA Corporation" input
- **Components covered** (2 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `10-interactive-data-cards.png` | Interactive data cards | Right panel: stock data cards, watchlist, price movement |
  | `10-interactive-charts-visualizations.png` | Interactive charts/visualizations | Center: NVIDIA stock price chart |

---

## perplexity-web-screen-7.png through 10.png (login/signup — skipped)
- **Source**: Mobbin — Perplexity Web, screens 7-10
- **What it shows**: Login modal flows (Google, Apple, email, SSO), email verification. Not relevant to chat primitives.

---

## gemini-web-screen-1.png (no components mapped)
- **Source**: Mobbin — Google Gemini Web, screen 1 of 12
- **What it shows**: Empty state — "Hello, Sam", suggestion cards (Explain Python, Create outline, Business plan, Chart), input bar with mic button, Gemini Advanced branding

## gemini-web-screen-2.png
- **Source**: Mobbin — Google Gemini Web, screen 2 of 12
- **What it shows**: Active conversation with Draft 1/2/3 variant tabs, business plan response with markdown formatting, speaker/audio button, "Hide drafts" toggle
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `03-draft-variants.png` | Draft variants | Top: Draft 1/2/3 tab cards with regenerate button |

---

## gemini-web-screen-3.png
- **Source**: Mobbin — Google Gemini Web, screen 3 of 12
- **What it shows**: End of response with action bar (thumbs up/down, modify, share, Google "G"), detailed rating survey expanded with categories (Correct, Easy to understand, Complete) and free text
- **Components covered** (2 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `06-detailed-rating-survey.png` | Detailed rating/survey | Bottom: "Why did you choose this rating?" with categories |
  | `05-google-it-verification.png` | "Google it" verification | Action bar: Google "G" button |

---

## gemini-web-screen-4.png
- **Source**: Mobbin — Google Gemini Web, screen 4 of 12
- **What it shows**: "Pin this chat" dialog with emoji picker, custom name field, sidebar open with chat history, Help/Activity/Settings links
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `01-pin-favorite-chats.png` | Pin/favorite chats | Center: "Pin this chat" dialog with emoji picker |

---

## gemini-web-screen-5.png
- **Source**: Mobbin — Google Gemini Web, screen 5 of 12
- **What it shows**: "Send feedback to Google" dialog with text field, attached screenshot with "Highlight or Hide Info" annotation tool, privacy notice
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `06-report-flag-response.png` | Report/flag response | Right panel: feedback dialog with screenshot annotation |

---

## gemini-web-screen-6.png
- **Source**: Mobbin — Google Gemini Web, screen 6 of 12
- **What it shows**: "Your Gemini Apps Activity" page — turn on/off toggle, auto-delete settings, activity log with prompt history and timestamps
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `14-data-privacy-notices.png` | Data privacy notices | Full page: activity toggle, privacy explanation, prompt log |

---

## gemini-web-screen-7.png
- **Source**: Mobbin — Google Gemini Web, screen 7 of 12
- **What it shows**: Gemini Extensions page — Google Flights, Hotels, Maps with on/off toggles, descriptions, sample prompts, sidebar with chat history
- **Components covered** (1 file):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `07-ecosystem-app-integration.png` | Ecosystem/app integration | Center: Extension cards with toggles and sample prompts |

---

## gemini-web-screen-8.png
- **Source**: Mobbin — Google Gemini Web, screen 8 of 12
- **What it shows**: "Your public links" management page — shared conversation link with copy/delete buttons, link URL, creation timestamp
- **Components covered** (2 files):
  | File | Component | Highlight region |
  |------|-----------|-----------------|
  | `06-share-conversation.png` | Share conversation | Full page: public link management with copy/delete |
  | `12-shareable-conversation-link.png` | Shareable conversation link | Center: conversation link card with URL |

---

## gemini-web-screen-9.png through 12.png (login/landing — skipped)
- **Source**: Mobbin — Google Gemini Web, screens 9-12
- **What it shows**: Landing page, Google Sign in flows. Not relevant to chat primitives.

---

## How to add new sources

1. Download to `_sources/` with a descriptive name (e.g., `chatgpt-conversation-view.png`)
2. Duplicate to `images/XX-component-name.png` for each component it covers
3. Add an entry here with the source details and component mapping
4. Update the markdown: replace `<!-- pending: XX-name.png -->` with `![Component — Product](images/XX-name.png)`

---

## cursor-web (Cursor Web App)

### cursor-web-screen-1.png
- **Content**: Dashboard overview — Pro Plan info, usage-based spending, "Your Analytics" with Lines of Agent Edits line chart (1,252), Tabs Accepted (0)
- → `15-year-in-review-usage-summaries.png` — Crop to analytics section with chart

### cursor-web-screen-2.png
- **Content**: "Link GitHub Account" OAuth dialog — GitHub Account + Cursor Account fields, warning message, Cancel/Link Account buttons
- _(unmapped — OAuth linking, not a conversational AI pattern)_

### cursor-web-screen-3.png
- **Content**: Integrations page — GitHub (connected), Slack, Linear with Connect buttons; User API Keys section with "+ New API Key"
- _(unmapped — integrations management, ecosystem-app-integration already covered by Gemini)_

### cursor-web-screen-4.png
- **Content**: Bugbot — "Automatically review pull requests (PRs) for bugs and issues", analytics (2 PRs Reviewed, 0.0% Resolved, 1 Unique Users, 1 Est. Hours Saved), PR chart
- _(unmapped — automated PR review analytics, niche feature)_

### cursor-web-screen-5.png
- **Content**: "Included Usage Summary" with token table (claude-4-sonnet, o3, gpt-5 models with input/output/cache columns), date range selector, "All Raw Events" log with timestamps and token counts
- → `14-audit-logging.png` — Full screen shows both usage summary and raw event log

### cursor-web-screen-6.png
- **Content**: Agent empty state — "Ask Cursor to build, fix bugs, explore" placeholder, GPT-5 MAX model selector dropdown, image upload button, "Select repository" dropdown, suggestion chips ("Write documentation", "Optimize performance", "Find and fix 3 bugs")
- → `02-working-set-context-selector.png` — Crop to repo selector + model selector area

### cursor-web-screen-7.png
- **Content**: Agent with filled multi-line prompt — detailed coding task with bullet points typed into auto-resizing text field, GPT-5 MAX model, send button active, same suggestion chips below
- → `02-enter-shift-enter-behavior.png` — Full prompt area showing multi-line text entry

### cursor-web-screen-8.png
- **Content**: Background Agent running — left sidebar with agent list (3 agents, different statuses), center panel with code diff (green additions in API_DOCUMENTATION.md), right summary panel with file descriptions, follow-up input at bottom
- → `11-background-agent-notifications.png` — Crop to left sidebar showing agent list with statuses
- → `03-diff-display.png` — Crop to center code diff panel with green additions
- → `11-multi-step-workflow-progress.png` — Crop to right summary panel showing progress/files

### cursor-web-screen-9.png through cursor-web-screen-12.png
- **Content**: Marketing homepage, sign in, sign up pages
- _(skipped — not conversational AI patterns)_

## Orphaned files

_(All orphaned files from earlier naming mistakes have been deleted.)_
