# Linux

## Cheatsheets
![Linux basic commands](images/linux_basic_commands.jpg)

# React-Native

## Troubleshooting

1. ENOSPC start error:
    ```
    echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
    ```
