# triplew
A triplesec wrapper (bash) for encrypting/decrypting files.
<pre>
___________      .__       .__           _________
\__    ___/______|__|_____ |  |   ____  /   _____/ ____   ____
  |    |  \_  __ \  \____ \|  | _/ __ \ \_____  \_/ __ \_/ ___\
  |    |   |  | \/  |  |_> >  |_\  ___/ /        \  ___/\  \___
  |____|   |__|  |__|   __/|____/\___  >_______  /\___  >\___  >
                    |__|             \/        \/     \/     \/
</pre>

## Getting Started
### Prerequisites
You need to have the triplesec python library installed, to install it with pip:

`$ pip install triplesec`
### Installing
You can get the script directly [here](https://raw.githubusercontent.com/agucova/triplew/master/triplew).

The script doesn't need any superuser privileges, just access to the files.

## Usage Examples
To encrypt a file:

`$ triplew enc p4ssw0rd confidential.md`

To decrypt a file:

`$ triplew dec p4ssw0rd confidential.md.triple`

*NOTE: The script automatically deletes your bash history to prevent the password to be found.*

_I don't know if this is a safe method of retrieving the password, so any help is appreciated._

## License
This script is licensed with the [MIT License](https://opensource.org/licenses/MIT).


<img alt="MIT License" src="https://opensource.org/files/ccby.png" width="100">
