# legal-toa-plugin
Obsidian.md plugin to generate legal table of authorities from text of legal brief.

Written mainly by Google Gemini Pro with about eight hours of prompting from Alan Harrison.

Started off leveraging eyecite-ts but transitioned to a pure regex-search paradigm for reliability.

Most effective vibe-coding approach turned out to be manually generating "gold standard" ToAs and feeding the original briefs + gold standards to Gemini with instruction to iterate the code.

Focused currently on Federal and Connecticut law.
