# Cartoon Jake

A Codex skill for expressive 2D cartoons with rounded shapes, clean black outlines, and vivid flat colors. It carries the same visual style across new subjects and poses while paying close attention to weight, contact, surface effects, and lighting.

## Usain Bolt's first step

This generated example captures Usain Bolt taking his first step after the starting gun at the World Championships.

![Usain Bolt taking his first step from the starting blocks in the Cartoon Jake style, with a Jamaican racing kit, a planted forefoot, and a cast shadow on the track.](examples/usain-bolt-first-step.png)

The original request, translated into English, was

```text
$artifact-template-cartoon-jake Draw Usain Bolt taking his first step just after the starting gun at the World Championships.
```

## Installation

Use Codex with access to the `imagegen` skill and an image generation tool. Ask the skill installer to install this repository's skill folder.

```text
$skill-installer https://github.com/rlatjr8362/cartoon-jake-skill/tree/main/skills/artifact-template-cartoon-jake
```

After installation, invoke `$artifact-template-cartoon-jake` in your next request. The skill's display name is **Cartoon Jake**.

## Usage

Describe the subject and action. Add a setting, viewpoint, expression, lighting direction, or transparent background requirement when those details matter.

```text
$artifact-template-cartoon-jake Draw Jake sprinting along a dirt path. Show the force through his planted foot and small puffs of dust kicked up behind him.
```

```text
$artifact-template-cartoon-jake Draw a basketball player at the top of a jump. Match the indoor court lighting and place the player's shadow on the floor below.
```

The skill uses the saved references to guide character proportions, line weight, and color treatment. For other subjects, it carries over the cartoon style while retaining their distinctive appearance and clothing.

Its motion guidance covers running, jumping, landing, braking, pushing, and resting. Surface effects adapt to the setting, and the character's shading, contact shadows, and cast shadow share a consistent light source.

## Repository layout

```text
cartoon-jake-skill/
├── README.md
├── examples/
│   └── usain-bolt-first-step.png
└── skills/
    └── artifact-template-cartoon-jake/
        ├── SKILL.md
        ├── artifact-template.json
        ├── agents/
        │   └── openai.yaml
        ├── assets/
        │   ├── preview.png
        │   ├── reference.png
        │   ├── reference-action.png
        │   └── reference-contact.png
        └── references/
            └── motion-and-light.md
```

The skill folder contains the creation instructions, interface metadata, three visual references, and a template preview. Detailed guidance covers motion, physical contact, and lighting. [Skill instructions](skills/artifact-template-cartoon-jake/SKILL.md) · [Motion and lighting guide](skills/artifact-template-cartoon-jake/references/motion-and-light.md)
