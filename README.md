# hi-there
This group of files have the prerequisites for a .deb

## Building
Enter 'debuild' in ./hi-there/hi-there to create a .deb file in ./hi-there

## Prerequisites
* To create the binary from hi-there.py, use `pyinstaller --onefile hi-there.py`
* You must create a gpg key using `gpg --gen-key` and these values: 'Ross Jacobs (Project Manager) <projectmerlink@gmail.com>'
* You can use different values if you change the same contents in the changelog and control file ('Maintainer')
