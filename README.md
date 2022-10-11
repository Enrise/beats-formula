# Archived and unmaintained

This is an old repository that is no longer used or maintained. We advice to no longer use this repository.

## Original README can be found below:

# beats-formula

This formula will install elastic search beats (currently supported: filebeat, topbeat, packetbeat).

## Compatibility

This formula currently only works on Debian-based systems (Debian, Ubuntu etc).

## Contributing

Pull requests for other OSes and bug fixes are more than welcome.

## Usage

Include "beats" in your project, and configure which beats to install and with what config using pillars. You may find
an example of a pillar in [example.pillar](example.pillar).

### Note

The configuration you put in the pillar is being put in the configuration files verbatim.
