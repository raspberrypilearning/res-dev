## Project structure

### Directories and Files

Upon creating a project, you should see the following structure:

```bash
.
├── banner.png
├── CONTRIBUTING.md
├── crowdin.yml
├── en
│   ├── images
│   ├── meta.yml
│   ├── resources
│   ├── solutions
│   ├── step_1.md
│   ├── step_2.md
│   ├── step_n.md
├── LICENCE.md
└── README.md
```

#### banner.png
This will be the cover art used in the project. It's name should remain unchanged, and the file can be replaced once artwork has been completed

#### CONTRIBUTING.md
Contribution guidelines. You only need to edit the `## Issues` section.

```markdown
## Issues

If you find a mistake, bug, or other problem, please [open an issue](https://github.com/raspberrypilearning/my-cool-project/issues) in this repository.
```

#### crowdin.yml
Leave this alone unless you're doing translation work

#### en
This contains the English version of the project.
- `images` is where all images, animations and videos are stored
- `meta.yml` contains the meta data for the project
- `resources` should contain any starter files that a user might need
- `solutions` should contain a full solution for the project
- `steps_1 --> n.md` should be the project content

#### LICENCE.md
License information. You need to update the section with the project-name.
```markdown
Based on a work at https://github.com/raspberrypilearning/my-cool-project.
```

#### README.md
Information for GitHub users. You can leave this alone.
