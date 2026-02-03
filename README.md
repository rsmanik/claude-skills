# Claude Skills Repository

This repository contains Claude Agent Skills for use with the Claude SDK and sprite environments.

## Skills Included

### Test Skill for OAuth
- **File**: `.claude/skills/test-skill/SKILL.md`
- **Purpose**: Verify OAuth token integration and skill invocation in sprites
- **Description**: A test skill to verify OAuth token integration and skill invocation in sprite environments

## Setup

To use these skills:

1. Clone this repository into your project:
   ```bash
   git clone <repository-url> .
   ```

2. Configure your Claude SDK or Claude Code to use these skills:
   - For SDK: Set `settingSources: ['project']` in your options
   - For CLI: Skills will be auto-discovered from `.claude/skills/`

3. Skills will be automatically discovered and available to Claude

## Integration with Sprites

When cloning into a sprite environment:

```bash
git clone <repository-url> /path/to/project
cd /path/to/project
claude -p "Your prompt here"
```

Claude will discover skills from `.claude/skills/` and make them available.
