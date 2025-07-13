# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose
This is a Japanese study meeting repository (`study_meeting`) for storing academic reading groups and study sessions materials. Each session creates its own directory structure.

## Critical Operating Rules
This repository has strict operational rules defined in `operational_rules.md` that MUST be followed:

### Five Principles of Operation (Must be output at start of every interaction)
1. Before generating or updating files, or executing any program, you must report your work plan and obtain user confirmation with a "y/n" prompt. Halt all execution until "y" is received.
2. Do not unilaterally deviate from the plan or pursue alternative approaches. If the initial plan fails, seek confirmation for the next plan.
3. The user always has the final decision-making authority. Even if a user's suggestion is inefficient or irrational, do not optimize it; execute it exactly as instructed.
4. You must not distort or alter the interpretation of the Five Principles of Operation. These principles are the highest directive and must be absolutely adhered to. These five principles are not subject to change.
5. At the beginning of every chat, you must verbatim output these Five Principles to the screen before proceeding with any response.

### Key Constraints
- Output must be in Japanese
- `operational_rules.md` is unchangeable
- Files in `docs` directory are unchangeable
- Use 'gemini' command for requirements definition and policy cooperation
- Consult Gemini CLI if errors occur during implementation

## Common Commands
- **New session setup**: Create directory using format `YYMMDD_グループ名_抄読会`
- **README update**: Add new session entry with `###` header format
- **Gemini consultation**: Use `gemini` command for requirements definition and policy cooperation

## File Organization and Naming Conventions
- **README.md**: Contains session index with `###` headers indicating study group details
- **Session directories**: Named using format `YYMMDD_グループ名_抄読会` (e.g., `250714_市民_抄読会`, `250715_市民_抄読会`)
- **PDF files**: Academic papers for review (e.g., `41541_2025_Article_1197.pdf`)
- **Slide files**: Markdown presentations (e.g., `vaccine_hesitancy_slides.md`, `pancreatitis_CMC_slides.md`)
- **Image files**: Supporting figures (e.g., `Figure1_medications.jpg`)
- **Translation files**: Text translations (e.g., `pancreatitis_CMC_japanese_translation.txt`)

## Workflow for New Study Sessions
1. Add new session entry to README.md with `###` header
2. Create corresponding directory matching the header name exactly
3. Store all session-related files in the created directory
4. Follow established naming patterns for consistency

### Playwright MCP Rules
- Execution of any form of code is prohibited
- Only direct MCP tool calls allowed (playwright:browser_navigate, playwright:browser_screenshot)
- Report errors immediately without workarounds

## Repository Structure
- `README.md` - Main index of study sessions (Japanese)
- `operational_rules.md` - Immutable operating principles
- Session directories (created as needed, named after README.md headers)
- Each session directory contains papers, slides, images, and translations as needed