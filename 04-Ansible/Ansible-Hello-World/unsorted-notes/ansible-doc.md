ansible-doc -h

Usage: ansible-doc [-l|-F|-s] [options] [-t <plugin type> ] [plugin]

plugin documentation tool

Options:
  -a, --all             **For internal testing only** Show documentation for
                        all plugins.
  -h, --help            show this help message and exit
  -l, --list            List available plugins
  -F, --list_files      Show plugin names and their source files without
                        summaries (implies --list)
  -M MODULE_PATH, --module-path=MODULE_PATH
                        prepend colon-separated path(s) to module library
                        (default=['/Users/butuzov/.ansible/plugins/modules',
                        '/usr/share/ansible/plugins/modules'])
  -s, --snippet         Show playbook snippet for specified plugin(s)
  -t TYPE, --type=TYPE  Choose which plugin type (defaults to "module")
  -v, --verbose         verbose mode (-vvv for more, -vvvv to enable
                        connection debugging)
  --version             show program's version number and exit

See man pages for Ansible CLI options or website for tutorials
https://docs.ansible.com
