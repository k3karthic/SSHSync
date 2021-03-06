# SSHSync
Sync changes made to a folder to a remote server via SSH / SCP.

## Usage Examples

#### Sync changes made to python code in a directory and its sub-directories

```shell
$ sshsync . --recursive --hostname example.com --destination /my/code/ --patterns '.*py'
```

## Modules Required

1. [Six](http://pythonhosted.org/six/)
2. [Watchdog](http://pythonhosted.org/watchdog/)
3. [HashRing](https://pypi.python.org/pypi/pyhashring/)

## License
The MIT License (MIT)

Copyright (c) 2015 Karthic Kumaran Krisnakumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
