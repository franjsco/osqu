<h1 align="center">osqu (openSUSE QA Updates)</h1>
<p>
    <a href="https://github.com/franjsco/osqu/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/franjsco/iliadly/blob/master/LICENSE" target="_blank">
    <img alt="License: GPL--2.0" src="https://img.shields.io/github/license/franjsco/osqu" />
  </a>
  <a href="https://twitter.com/franjsco" target="_blank">
    <img alt="Twitter: franjsco" src="https://img.shields.io/twitter/follow/franjsco.svg?style=social" />
  </a>
</p>


> A command-line interface tool to view the latest builds of openSUSE Tumbleweed from openQA

Data: https://openqa.opensuse.org/

<a href="https://asciinema.org/a/391337" target="_blank"><img src="https://asciinema.org/a/391337.svg" /></a>

## Requirements
- GNU/Linux
- Python3
- pip3


## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/franjsco/osqu ~/.osqu

    cd ~/.osqu
    ```

2. Install dependencies:
    ```sh
    pip3 install -r requirements.txt
    ```

3. Make the script executable:
    ```sh
    chmod +x osqu.sh
    ```

4. Create a symbolic link:
    ```sh
    cd /usr/local/bin
    sudo ln -s ~/.osqu/osqu.sh osqu
    ```


## Use
Open the terminal and launch:
```sh
osqu
```
