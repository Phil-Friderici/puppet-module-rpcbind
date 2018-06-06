# Reference
<!-- DO NOT EDIT: This document was generated by Puppet Strings -->

## Classes

* [`rpcbind`](#rpcbind): rpcbind class

## Classes

### rpcbind

Manages rpcbind package and service.

#### Examples

##### Declaring the class

```puppet
include ::rpcbind
```

#### Parameters

The following parameters are available in the `rpcbind` class.

##### `package_ensure`

Data type: `String`

Value used for the ensure attribute of the rpcbind package resource.

Default value: 'installed'

##### `package_name`

Data type: `String`

Value used for the name attribute of the rpcbind package resource.

Default value: 'rpcbind'

##### `service_enable`

Data type: `Boolean`

Boolean used for the enable attribute of the rpcbind service resource.

Default value: `true`

##### `service_ensure`

Data type: `String`

Value used for the ensure attribute of the rpcbind service resource.

Default value: 'running'

##### `service_name`

Data type: `String`

Value used for the name attribute of the rpcbind service resource.

Default value: 'rpcbind'
