# Ansible-Base

Base directory structure for Ansible.

```console
$ tree -a
.
├── .envrc
├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
└── Taskfile.yml
```

Clone all other Ansible repositories beneath this directory.

## Setup Ansible Installation

Configure Python virtual environment via `direnv`:

```console
$ direnv allow .
```

Install all Ansible packages and tools needed:

```console
$ task update
```

## License

[MIT](https://github.com/dreknix/ansible-base/blob/main/LICENSE)
