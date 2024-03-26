# vscode-db2i

<img src="./media/logo.png" align="right" width="150px">

[GitHub star this repo 🌟](https://github.com/codefori/vscode-db2i)
[View our documentation 📘](https://codefori.github.io/docs/extensions/db2i/)

Db2 for IBM i tools provides SQL functionality to VS Code. **Currently in preview**.

- Statement executor and result set view
- Schemas view
- Query history
- SQL Job Manager, with JDBC options editor and configuration manager

---

![](./media/main.png)

### Server Component

As of 0.3.0, the Db2 for i extension requires a server component. The component provides improved performance and makes it easy for us to add better features. This extension will manage the server component installation when you connect to a system with Code for IBM i and will ask the user to confirm any installation or update. [The server component is also open-source](https://github.com/ThePrez/CodeForIBMiServer).

## Building from source

1. This project requires VS Code and Node.js.
2. fork & clone repo
3. `npm i`
4. `npm run dsc` (to fetch the Server Component)
5. 'Run Extension' from vscode debug.
