kratos service registry/discovery implementation based on consul.    
comparing with the official contrib package, this package's registry provides the `ListServices` method that 
lists all the services registered on the registry server rather than the watched services by the official's method.