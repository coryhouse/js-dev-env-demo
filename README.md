# Demo for ["Building a JavaScript Development Environment"](https://app.pluralsight.com/library/courses/javascript-development-environment) on Pluralsight

I build this development environment from scratch in ["Building a JavaScript Development Environment"](https://app.pluralsight.com/library/courses/javascript-development-environment) on Pluralsight

## Having Issues? Try these things first:
1. Run `npm install` - If you forget to do this, you'll see this: `babel-node: command not found`.
2. Make sure you're running the latest version of Node. Or, use [Node 6.9.1](https://nodejs.org/en/download/releases/) if you're having issues on Windows. Node 7 has issues on some Windows machines.
3. Make sure files with names that begin with a dot (.babelrc, .editorconfig, .eslintrc) are copied to the project directory root. This is easy to overlook is you copy this repository manually.
4. Don't run the project from a symbolic link. It will cause issues with file watches.
5. Having linting issues? Delete any .eslintrc that you're storing in your user directory. Also, disable any ESLint plugin / custom rules that you've enabled within your editor. These will conflict with the ESLint rules defined in the course.
6. Nothing above work? Delete your node_modules folder and re-run npm install.
