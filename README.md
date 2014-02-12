puppet-svn
==========

A puppet module to manage subversion repositories.

## Sample Usage
Install svn and use the provided configuration defaults:
```puppet
node default {
	class {'svn':}
}
```
or
```puppet
node default {
	include svn
}
```

Uninstall svn:
```puppet
node default {
	class {'svn':
		ensure => absent,
	}
}
```

Contact
-------

Principal developer:
	[Leonardo Thibes](http://leonardothibes.com) => [eu@leonardothibes.com](mailto:eu@leonardothibes.com)

Support
-------

Please log tickets and issues at our [Projects site](https://github.com/leonardothibes/puppet-svn/issues)
