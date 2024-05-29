# logOne

`logOne` is a bash script for displaying a one-line log for each git commit.

## Installation

### Prerequisites

* Git

### Clone the repository

```bash
git clone https://github.com/Gideon-D-Adeti/logOne.git
```

Or, if you have [cloneO](https://github.com/Gideon-D-Adeti/cloneO) setup:

```bash
cloneO https://github.com/Gideon-D-Adeti/logOne.git
```

[cloneO](https://github.com/Gideon-D-Adeti/cloneO) allows you to clone and open a repo in Visual Studio Code.

### Make the script available system-wide

```bash
sudo cp logOne/logOne.sh /usr/local/bin/logOne
sudo chmod +x /usr/local/bin/logOne
```

Or, if you used [cloneO](https://github.com/Gideon-D-Adeti/cloneO):

```bash
sudo cp logOne.sh /usr/local/bin/logOne
sudo chmod +x /usr/local/bin/logOne
```

## Usage

To display the one-line git log, simply run:

```bash
logOne
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
