# Dysco
Dysco(Dynamic PHP Shell Command for RCE). This is example PHP Shell with support for dynamic RCE command, it's useful when you are don't know which php function is disabled.

# Why

When You are uploading php reverse shell and it doesn't give you reverse shell without any reason? You only have one chance to upload shell, don't waste your time. Use this, it will use and check available command and then run your requested command.

# Supported Function

- exec
- shell_exec
- system
- passthru
- eval
- More soon

# Usage

Upload this to your target and then open script:

http://blablabla.com/dysco.php?cmd=your_command_execution

# Screenshot

See screenshot:
![Screenshot](https://i.imgur.com/403deJC.png)


# Feedback and Suggestion

Feel free to create Issue in this repository. Your feedback and suggestion is useful.

# License

Dysco is licensed under MIT. Please see [LICENSE](https://github.com/aancw/Dysco/blob/master/LICENSE) for the full license text.
