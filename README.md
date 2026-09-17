# graff-skills

A public catalog of Agent Skills (`SKILL.md` playbooks) for [Codegraff](https://github.com/justrach/codegraff).

This is not a second copy of the harness. Each folder is one skill. The harness already loads skills from personal and project directories; clone or copy a folder there.

## Install

Personal (every project):

```sh
git clone https://github.com/justrach/graff-skills.git
cp -R graff-skills/mcp-setup ~/.graff/skills/mcp-setup
```

This project only:

```sh
mkdir -p .harness/skills
cp -R path/to/graff-skills/skill-creator .harness/skills/skill-creator
```

A skill is a directory with a `SKILL.md`. Frontmatter needs `name` and `description`. The body loads on demand.

## Template

Copy `_template/` and fill in the frontmatter plus the steps a future session would otherwise forget.
