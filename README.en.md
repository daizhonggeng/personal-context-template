# Personal Context Template

[中文说明](README.md)

A Markdown and Git template for organizing your background, preferences, goals, and life records, so AI applications can read relevant personal context when needed.

This public repository contains blank templates and guidelines. Create a **private repository from the template** before adding personal information. Do not fill a public fork with private records.

## Start small

1. Read the [privacy and publishing guide](docs/隐私与发布.md) and [recording rules](docs/记录规范.md) (in Chinese).
2. Fill only the necessary parts of the three core files. Blank fields and “not applicable” are valid.
3. Keep detailed records in the relevant subject folders. Use the [inbox](00-收件箱/README.md) for material awaiting classification or confirmation.
4. Give each AI application access only to the files required for its current task. Follow the [AI access guide](docs/AI接入.md) and check whether the application follows [AGENTS.md](AGENTS.md).

| Core file | Purpose |
| --- | --- |
| [PROFILE.md](PROFILE.md) | Concise background, with links to detailed records |
| [PREFERENCES.md](PREFERENCES.md) | Communication and collaboration preferences |
| [CURRENT.md](CURRENT.md) | Current priorities, active goals, and constraints |

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
