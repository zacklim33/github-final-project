All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.


How Do I Submit A (Good) Bug Report?
Bugs are tracked as GitHub issues. After you've determined which repository your bug is related to, create an issue on that repository and provide the following information by filling in the template.

Explain the problem and include additional details to help maintainers reproduce the problem:

Use a clear and descriptive title for the issue to identify the problem.
Describe the exact steps which reproduce the problem in as many details as possible. For example, start by explaining how you started Atom, e.g. which command exactly you used in the terminal, or how you started Atom otherwise. When listing steps, don't just say what you did, but explain how you did it. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or an Atom command, and if so which one?
Provide specific examples to demonstrate the steps. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use Markdown code blocks.
Describe the behavior you observed after following the steps and point out what exactly is the problem with that behavior.
Explain which behavior you expected to see instead and why.
Include screenshots and animated GIFs which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, record the GIF with the Keybinding Resolver shown. You can use this tool to record GIFs on macOS and Windows, and this tool or this tool on Linux.
If you're reporting that Atom crashed, include a crash report with a stack trace from the operating system. On macOS, the crash report will be available in Console.app under "Diagnostic and usage information" > "User diagnostic reports". Include the crash report in the issue in a code block, a file attachment, or put it in a gist and provide link to that gist.
If the problem is related to performance or memory, include a CPU profile capture with your report.
If Chrome's developer tools pane is shown without you triggering it, that normally means that you have a syntax error in one of your themes or in your styles.less. Try running in Safe Mode and using a different theme or comment out the contents of your styles.less to see if that fixes the problem.
If the problem wasn't triggered by a specific action, describe what you were doing before the problem happened and share more information using the guidelines below.
Provide more context by answering these questions:

Can you reproduce the problem in safe mode?
Did the problem start happening recently (e.g. after updating to a new version of Atom) or was this always a problem?
If the problem started happening recently, can you reproduce the problem in an older version of Atom? What's the most recent version in which the problem doesn't happen? You can download older versions of Atom from the releases page.
Can you reliably reproduce the issue? If not, provide details about how often the problem happens and under which conditions it normally happens.
If the problem is related to working with files (e.g. opening and editing files), does the problem happen for all files and projects or only some? Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or Python files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?
Include details about your configuration and environment:

Which version of Atom are you using? You can get the exact version by running atom -v in your terminal, or by starting Atom and running the Application: About command from the Command Palette.
What's the name and version of the OS you're using?
Are you running Atom in a virtual machine? If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
Which packages do you have installed? You can get that list by running apm list --installed.
Are you using local configuration files config.cson, keymap.cson, snippets.cson, styles.less and init.coffee to customize Atom? If so, provide the contents of those files, preferably in a code block or with a link to a gist.
Are you using Atom with multiple monitors? If so, can you reproduce the problem when you use a single monitor?
Which keyboard layout are you using? Are you using a US layout or some other layout?
Suggesting Enhancements
This section guides you through submitting an enhancement suggestion for Atom, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion 📝 and find related suggestions 🔎.

Before creating enhancement suggestions, please check this list as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please include as many details as possible. Fill in the template, including the steps that you imagine you would take if the feature you're requesting existed.

Before Submitting An Enhancement Suggestion
Check the debugging guide for tips — you might discover that the enhancement is already available. Most importantly, check if you're using the latest version of Atom and if you can get the desired behavior by changing Atom's or packages' config settings.
Check if there's already a package which provides that enhancement.
Determine which repository the enhancement should be suggested in.
Perform a cursory search to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
How Do I Submit A (Good) Enhancement Suggestion?
Enhancement suggestions are tracked as GitHub issues. After you've determined which repository your enhancement suggestion is related to, create an issue on that repository and provide the following information:

Use a clear and descriptive title for the issue to identify the suggestion.
Provide a step-by-step description of the suggested enhancement in as many details as possible.
Provide specific examples to demonstrate the steps. Include copy/pasteable snippets which you use in those examples, as Markdown code blocks.
Describe the current behavior and explain which behavior you expected to see instead and why.
Include screenshots and animated GIFs which help you demonstrate the steps or point out the part of Atom which the suggestion is related to. You can use this tool to record GIFs on macOS and Windows, and this tool or this tool on Linux.
Explain why this enhancement would be useful to most Atom users and isn't something that can or should be implemented as a community package.
List some other text editors or applications where this enhancement exists.
Specify which version of Atom you're using. You can get the exact version by running atom -v in your terminal, or by starting Atom and running the Application: About command from the Command Palette.
Specify the name and version of the OS you're using.
