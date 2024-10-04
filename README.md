# VMEmu ROM repository

This repository contains all ROMs needed by the [VMEmu](https://github.com/VMEmu/VMEmu) emulator. For development versions of VMEmu, the recommended way to use this repository is to clone it instead of downloading the tagged releases.

Note that some ROMs in this repository may be for dev-branched machines and devices, meaning that they will not do anything on regular release builds. If you are confused why some device does not appear despite the ROM being present in the set, check that you are using an appropriate build of VMEmu before reporting issues.

## Contributing ROMs
Before new ROMs can be accepted in this repository, the code that uses the ROMs needs to be in the upstream VMEmu repository. Once you've made an VMEmu pull request, open a pull request here. This applies to removals as well in inverse. 

Note that your ROM(s) will not be merged to master until the code is in VMEmu master. However, if the development is happening in an upstream VMEmu branch, a corresponding branch can be created here until the feature is ready for master.

## Committing guidelines
- Do not use vague commit messages.

  **Acceptable:**
  - "Add ASUS P2B-VM ROM"
  - "Remove ASUS P5B-VM ROM".

  **Unacceptable:**
  - "Add files via upload"
  - "Romset update"
  - "Delete ROM"

- Separate additions and removals to different commits.
- The subject line shouldn't be longer than 50 characters. If you're having trouble fitting what you did in the subject, consider splitting your changes to multiple commits. If you genuinely need to give a lot of background information and splitting is not appropriate, write it in the description.

If you make no effort to follow these guidelines, your contribution will not be merged until you correct highlighted issues. Don't be ashamed to ask for help if you've made a mistake and don't know how to correct it.
