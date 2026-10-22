# Personal Context Template

[中文说明](README.md)

A Markdown and Git template for organizing your background, preferences, goals, and life records, so AI applications can read relevant personal context when needed.

This public repository contains blank templates and guidelines. Create a **private repository from the template** before adding personal information. Do not fill a public fork with private records.

## Start small

1. Read the [privacy and publishing guide](docs/隐私与发布.md) and [recording rules](docs/记录规范.md) (in Chinese).
2. Fill only the necessary parts of the three core files. Blank fields and “not applicable” are valid.
3. Keep detailed records in the relevant subject folders. Use the [inbox](00-收件箱/README.md) for material awaiting classification or confirmation.
4. Give each AI application access only to the files required for its current task. Follow the [AI access guide](docs/AI接入.md) and check whether the application follows [AGENTS.md](AGENTS.md).

## Core summaries and subject folders

Subject folders hold detailed records organized by topic. The three core files contain selected, concise summaries and links, presenting three views of the same knowledge base:

| Core file | Purpose | Relationship to subject records |
| --- | --- | --- |
| [PROFILE.md](PROFILE.md) | Who I am | Select relevant, relatively stable background from personal, work, learning, or other records |
| [PREFERENCES.md](PREFERENCES.md) | How to work with me | Keep confirmed preferences useful across tasks; topic-specific details remain in subject folders |
| [CURRENT.md](CURRENT.md) | What matters now | Summarize current goals and constraints, link active records, and remove outdated summaries |

This is a many-to-many relationship: one subject can inform several core files, and one core file can reference several subjects. Most details can stay only in subject records. A short fact that needs no detailed record can live only in a core file; do not duplicate it just to fill the structure.

When an authorized detail changes, check any existing core summary within the granted read scope and update its source link and date only within the write authorization. Summaries are maintained deliberately, not automatically extracted from every conversation or folder. Reading a core file does not authorize reading all its linked files; an AI application selects relevant files within the granted scope.

`README.md` is navigation, `AGENTS.md` defines collaboration rules, the inbox holds unprocessed or unconfirmed material, templates provide blank formats, and the archive holds historical records. These are not current personal facts. See the [structure guide](docs/资料结构.md) (in Chinese) for examples and maintenance rules.

The [Chinese directory map](README.md#目录导航) covers 17 life areas, plus an inbox, templates, and an archive. Folder names are optional categories, not evidence about your life. Templates, examples, and unanswered fields are not personal facts.

## Boundaries

- AI may record personal information only when you explicitly say **“保存”** (“save”) and specify the content. A statement, a quoted instruction, or a discussion about saving is not authorization.
- Save only the necessary, organized information with its date, source, and status. Do not upload raw chats, conversation transcripts, or tool logs.
- Read selectively. This template does not automatically connect accounts, share memory across devices, index mail, or sync external sources.
- The `AI读取` (AI access) field defaults to “需确认” (confirmation required), and to “禁止” (denied) for highly sensitive records. Applications must enforce the actual permissions.
- Never commit passwords, API keys, private keys, recovery codes, or full sensitive identification numbers.
- A private repository and written instructions do not themselves enforce encryption, access controls, or an AI provider’s data policy. Configure and verify each application separately.

Keep your populated instance private and backed up. When contributing to this public template, submit only generic improvements and clearly fictional examples, including in issues, pull requests, screenshots, and Git history.

The template is available under the [MIT License](LICENSE). This does not require you to publish the personal information in your private instance.
