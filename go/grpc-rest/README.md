This is a template for using [grpc-gateway]("https://github.com/grpc-ecosystem/grpc-gateway") to expose a service through a rest endpoint.

It will generate the standard proto libraries for go as well as a swagger.json from the proto files. For

To use it:

1. `cd proto`
2. create your `.proto` files in `<PackageName>/<name>.proto`
3. create a .yaml file with your route configuration in `<PackageName>/<name>.yaml`
4. buf generate
