![A screenshot of a JetBrains IDE showing Julia code with syntax highlighting and intelligent code completion](https://plugins.jetbrains.com/files/29356/screenshot_be9fb331-3c75-4902-8cbb-95615eaa5733)

# Flexible Julia

[Flexible Julia](https://plugins.jetbrains.com/plugin/29356-flexible-julia) is a plugin for JetBrains IDEs that empowers you to develop high-performance Julia code for scientific computing, data science, and numerical analysis with confidence.

This repository exists as a community hub and issue tracker.

## Feedback and Support

If you have any feedback, suggestions, or issues with the plugin, please use our Github repository to report them (you may have found it already). You can also use the repository to contribute to the plugin development or request new features.

- Github repository: [Flexible Julia](https://github.com/ilscipio/flexible-julia-jetbrains-plugin)
- Ilscipio Agency: [Ilscipio](https://www.ilscipio.com/en)
- Our awesome developer tools: [Aivory](https://aivory.net)

## Features

- Syntax highlighting for Julia language including macros, unicode operators, and string interpolation
- Code completion and navigation for Julia functions, types, modules, and custom definitions
- Intelligent brace matching for Julia's control structures and bracket types
- Code folding for functions, modules, structs, and control flow blocks
- Real-time syntax validation and error detection
- Support for Julia's extensive unicode operator set (∈, ≤, ∘, ⊕, and hundreds more)
- Smart commenting with proper Julia comment syntax
- Code formatting that respects Julia style conventions
- Type annotation support with :: operator highlighting
- Multiple dispatch and parametric type syntax support

## Installation

You can install Flexible Julia from the JetBrains Marketplace or from the IDE settings.

- **From the Marketplace:** Go to [Flexible Julia](https://plugins.jetbrains.com/plugin/29356-flexible-julia) and click on the Install button. Then restart your IDE to activate the plugin.
- **From the IDE settings:** Go to File > Settings > Plugins and search for Flexible Julia. Click on the Install button and restart your IDE to activate the plugin.

## Usage

To use Flexible Julia, you need to have Julia source files in your project.

1. Install the plugin
2. Check that *.jl file types are correctly associated (Settings > File Types > "Flexible Julia" > List should include *.jl; Add if missing)
3. Open any Julia file (.jl) and start coding with full syntax highlighting and code completion
4. Use Ctrl+Space (or Cmd+Space on Mac) to trigger code completion
5. Navigate through your code using Ctrl+Click (or Cmd+Click) on identifiers
6. Use code folding to collapse/expand function definitions and modules
7. Enjoy real-time syntax validation as you type

### Working with Julia Projects

- Open Julia package projects with `Project.toml` files - the plugin recognizes standard Julia project structures
- Write and edit Julia modules with proper syntax support
- Develop macros and metaprogramming code with specialized highlighting
- Use unicode operators naturally - the plugin supports Julia's extensive mathematical notation
- Format your code according to Julia community style guidelines

### Key Features in Action

- **Syntax Highlighting:** All Julia keywords, operators, types, and constructs are beautifully highlighted
- **Code Completion:** Get intelligent suggestions for Julia built-ins and your custom functions
- **Error Detection:** Catch syntax errors before running your code
- **Unicode Support:** Type mathematical operators and symbols with full IDE support
- **Navigation:** Jump to definitions and find usages across your project

## Requirements

- JetBrains IDE (IntelliJ IDEA, PyCharm, WebStorm, etc.) version 2023.3 or later
- Julia language runtime (not required for the plugin to work, but needed to run your code)

## Contributing

We welcome contributions! If you'd like to improve the plugin or add new features, please feel free to submit issues or pull requests to our repository.

## License

See the LICENSE file in this repository for details.

## About Ilscipio

We are Ilscipio, developers with a passion for creating tools that make developers' lives easier. From E-Commerce solutions to AI projects and JetBrains plugins, we're committed to building quality software for the developer community.

Visit us at [www.ilscipio.com](https://www.ilscipio.com) or reach out at `info@ilscipio.com` for custom plugin development, consulting, or just to say hello!
