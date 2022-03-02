## Enable Shell Access Mode
First, access the [control panel](https://panel.alaister.net){:target="_blank"}.

![](../assets/portal/open_panel.png)

Start or restart your server.

Look at the console. When you are prompted, type `yes` and press ++enter++.

![](../assets/panel/console_enable_shell.png)

??? info "How to skip the prompt when restarting my server?"
    You can hide this prompt from every server restart by changing the option in the `Startup` tab.

    ![](../assets/panel/startup_nav.png)

    ![](../assets/panel/startup_enable_shell.png)

You can now run shell commands like `npm install discord.js`.

![](../assets/panel/console_shell_npm.png)

To exit and start your server normally, type `exit` and press ++enter++.

![](../assets/panel/console_shell_exit.png)

!!! failure
    You should not run long-running commands, start background processes, or use terminal text editor in the Shell Access Mode.
