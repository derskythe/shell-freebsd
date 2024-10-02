# shell-freebsd

Get a free shell for `FreeBSD` in `GitHub Actions`


![FreeBSD Logo](https://upload.wikimedia.org/wikipedia/ru/f/fb/FreeBSD_logo.png)

> [!NOTE]
>
> This is a fork of https://github.com/vmactions/shell-freebsd
> 

If you need a `FreeBSD` VM shell, you can use this repo.

# Instruction

1. First fork [this repo](https://github.com/vmactions/shell-freebsd)
2. Click the `Actions` menu on your Repo, and then enable `GitHub Action` on your fork
3. Then Select `All Workflows` ➡️ `Shell` on the left
4. Then click the `Run Workflow` dropdown menu on the right side
5. Then click the `Run Workflow` button


Wait a few seconds, the GitHub Action will run in your repo.

Click `Shell` ➡️ `Start a FreeBSD shell`,  to open the log window, you will see a FreeBSD vm is booting there.

Wait about 5-8 minutes, the FreeBSD vm will be ready.

And you will see the SSH address like below:

```cmd
Setting up tmate...

Running tmate...
```

To connect to this session copy-n-paste the following into a terminal:
```cmd
$ ssh 3R7dS7j45xk4CGzkz52psXpqr@nyc1.tmate.io
```

After connecting you can run: 
```cmd
$ touch /tmp/keepalive
```
to disable the 15m timeout.

Good.  Use the address to connect:

```cmd
$ ssh 3R7dS7j45xk4CGzkz52psXpqr@nyc1.tmate.io
```


You will get a shell like:


```cmd
Mac-1606142911434:shell-freebsd runner $
```

Then you can ssh to the FreeBSD VM:

```cmd
$ ssh freebsd
```


# Under the hood

Uses [GitHub CI in FreeBSD](https://github.com/vmactions/freebsd-vm)<br />
[View on Marketplace](https://github.com/marketplace/actions/freebsd-vm)
