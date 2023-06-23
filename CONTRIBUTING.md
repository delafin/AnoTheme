## How to contribute

1. Fork and clone this repo.
2. Create a branch for your changes. `git checkout -b my-new-feature`
3. Install dependencies. `npm install`
4. Open the _visual-studio-code_ folder in vscode.
5. Hack away.
6. Build and examine your changes in an Extension Development Host.
   - Debug > Start Debugging or use F5 as a shortcut
7. Commit and push your changes.
8. Submit a PR for discussion, keeping in mind that not all suggestions can be accepted.

## Creating your own Color Theme

- Read the [article](https://code.visualstudio.com/api/extension-guides/color-theme#create-a-new-color-theme);
- Install `npm install -g yo generator-code`;
- Run `yo code`, `New Color Theme`;
- Create your [theme](https://themes.vscode.one/);
- Run `vsce package`;
- [Publish your theme](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#get-a-personal-access-token);
- Useful Links:
  - [How to create a Custom VS Code Theme](https://www.youtube.com/watch?v=mbi27VNowks);
  - [How To Create And Deploy A VSCode Extension](https://www.youtube.com/watch?v=q5V4T3o3CXE).
