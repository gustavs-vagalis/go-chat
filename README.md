# go-chat

go-chat is a small server written in Go that behaves like a messaging service.
It can be used with any TCP client like `netcat`,

## Usage
- Simply run `/path/to/go-chat portnum`, where `portnum` is the port that should be used for communications.
- Connecting via netcat: `netcat ip_address port`
- The server will prompt you for a username which will be displayed to other clients.

## Known issues
- After any client disconnects, other's screens are filled with empty messages.

## TODO
- [] Add a prompt string to the clients
- [] More logging serverside
- [] Chat commands like /disconnect