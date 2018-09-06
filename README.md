# Virtual host for developers

V 1.0.1

## Requirement
- Apache 2
- Open SSL

## Installation

Open terminal and run command
   `wget https://raw.githubusercontent.com/RomixUA/virtual-host/1.x/vhost && chmod +x vhost && sudo mv vhost /usr/local/bin`

## Usage

Run: `vhost <server-name>`

You can use the following options:
* -m&emsp;--mail&emsp;&emsp;Server administrator Email address (--mail=admin@example.com)
* -s&emsp;--ssll&emsp;&emsp;&emsp;Generate self-signed SSL certificate
* -v&emsp;--version&emsp;Get script version

Run `vhost --help` if you need help.